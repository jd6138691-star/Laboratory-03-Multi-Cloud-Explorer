# Checkpoint 2 - Research: Types of Cloud Storage

## Cloud Storage Comparison

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| **Block Storage** | Stores data as fixed-size blocks that can be attached to a virtual machine and managed like a disk. | Best for operating systems, databases, and applications that need low-latency disk access. | AWS EBS |
| **File Storage** | Stores data as files organized in folders and directories. Multiple systems can access the same file system. | Best for shared files, content management, and applications that require a traditional file system. | AWS EFS |
| **Object Storage** | Stores data as objects together with metadata and a unique identifier inside containers called buckets. | Best for large amounts of unstructured data such as images, videos, documents, backups, and logs. | AWS S3 |

## Recommendation for User-Uploaded Images

Object Storage is the best choice for storing user-uploaded images because it is designed to handle large amounts of unstructured data such as image files. It also provides scalable storage and easy access to objects, making it suitable as the number of uploaded images grows.

