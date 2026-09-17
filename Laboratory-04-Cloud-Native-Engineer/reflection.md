# Checkpoint 7 - Mission Reflection

## Mission Reflection

### 1. How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?

A Docker container can start much faster than a Virtual Machine because it does not need to boot a complete operating system. It uses the host operating system's kernel and only includes the application and its necessary dependencies. In comparison, a Virtual Machine requires a full operating system to be installed, configured, and started, which takes more time and system resources.

### 2. Why is port mapping (-p 8080:80) necessary when running a web server inside a container?

Port mapping is needed so that the web server inside the container can be accessed from the host computer. In `-p 8080:80`, port `8080` is the port exposed on the host, while port `80` is the port where Nginx is running inside the container. This connection allows me to access the Nginx web server through the host machine.

### 3. What happens to the data inside a container when you use the docker rm command?

The `docker rm` command deletes the specified container. Data that exists only in the container's writable layer is also removed when the container is deleted. For important data that needs to remain available, persistent storage such as Docker volumes should be used.

### 4. How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?

Containerization helps developers and IT operations teams use a more consistent application environment. Developers can package an application together with its dependencies, while the operations team can use the same container when testing and deploying the application. This can reduce configuration differences and make the development and deployment process more organized.

### 5. How is your GitHub portfolio evolving?

My GitHub portfolio is gradually becoming more organized as I add laboratory activities, source code, documentation, screenshots, and reflections. I am learning that a portfolio is not only about uploading code but also about showing the process behind each project. The activities in this laboratory are helping me build a record of the technical skills I am developing as an IT student.

