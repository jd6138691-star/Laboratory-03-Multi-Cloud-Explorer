# Checkpoint 6 - Mission Reflection

## Mission Reflection

Object storage is better suited for storing millions of photos than traditional block storage because it is designed for large amounts of unstructured data. Instead of treating each photo like data on a physical hard drive, object storage stores each image as an object with its own unique identifier and metadata. This makes it easier to organize, access, and scale storage as the number of photos increases. Object storage is also commonly designed for high durability and large-scale storage.

Using Docker made deploying the MinIO storage server much easier because I did not need to manually install and configure every component of the server. With a single Docker command, I was able to create a container, configure the required environment variables, expose the necessary ports, and start the MinIO server. Docker also makes the deployment more consistent because the application runs in an isolated container.

A bucket in cloud storage is a container used to organize and store objects. For example, a bucket can contain thousands or millions of image files. It provides a logical location where applications can upload, store, and retrieve objects.

Large enterprise companies use several methods to prevent object storage data from being lost when a physical server crashes. They can replicate data across multiple physical servers, disks, availability zones, or even different geographic locations. They may also use redundancy, backups, versioning, and automated recovery systems so that a hardware failure does not result in permanent data loss.

My confidence in navigating the Linux command line is also growing. At first, commands and options were unfamiliar, but working with Docker and MinIO helped me become more comfortable using commands, checking files, and managing services from the terminal. I am learning that the command line can be a fast and powerful way to deploy and manage cloud-related applications.

