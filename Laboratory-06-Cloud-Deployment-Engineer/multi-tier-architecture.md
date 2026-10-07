# Two-Tier Architecture

A Two-Tier Architecture separates an application into two main layers: the Web/Application Tier and the Database Tier. Each tier has a specific responsibility and communicates with the other over a network.

## The Web/Application Tier

The Web/Application Tier is responsible for interacting with users and handling application logic. It serves the user interface, receives and processes HTTP requests, and communicates with the database when it needs to retrieve or store information.

## The Database Tier

The Database Tier is responsible for storing and managing persistent data. This includes information such as user accounts, application records, and other data that needs to remain available even when the application is restarted.

## Why Separate Them?

Separating the web server and database into two containers makes the system easier to manage, scale, and secure because each container has a specific responsibility. It also allows the web application and database to be updated, restarted, or scaled independently without unnecessarily affecting the other component.
