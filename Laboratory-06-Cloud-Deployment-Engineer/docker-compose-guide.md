# Docker Compose Guide

## Overview

Docker Compose is a tool used to define and manage multi-container Docker applications. Instead of creating and configuring each container separately, we can describe the entire application in a YAML file.

In this project, the application consists of two containers:

1. A **Nextcloud application container**.
2. A **MariaDB database container**.

The Docker Compose file defines both containers and allows them to communicate with each other.

---

## 1. What does the `services:` block do?

The `services:` block defines the different containers, or services, that make up the application.

For example:

```yaml
services:
  app:
    image: nextcloud
    ports:
      - "8080:80"
    environment:
      MYSQL_HOST: db
      MYSQL_DATABASE: nextcloud
      MYSQL_USER: nextcloud
      MYSQL_PASSWORD: password

  db:
    image: mariadb
    environment:
      MYSQL_DATABASE: nextcloud
      MYSQL_USER: nextcloud
      MYSQL_PASSWORD: password
      MYSQL_ROOT_PASSWORD: rootpassword
