# MinIO Deployment

## Technical Deployment Steps

MinIO was deployed using Docker.

### Docker Command

```bash
docker run -d --name minio \
  -p 9000:9000 \
  -p 9001:9001 \
  -e "MINIO_ROOT_USER=admin" \
  -e "MINIO_ROOT_PASSWORD=password123" \
  quay.io/minio/minio server /data --console-address ":9001"


# Laboratory 05 - Cloud Data Engineer

## Mission Overview

The mission of this laboratory is to deploy and configure MinIO as an object storage server using Docker. The deployment demonstrates how cloud storage concepts can be implemented locally using containerization.

## Objectives

- Deploy a MinIO server using Docker.
- Configure MinIO using environment variables.
- Access the MinIO web console.
- Create and manage an object storage bucket.
- Document the technical deployment process.
- Understand the role of Docker in deploying cloud-based services.

## Tools Used

- Docker
- MinIO
- GitHub
- Web Browser
- Markdown

## Skills Learned

- Deploying applications using Docker containers.
- Configuring applications using environment variables.
- Working with MinIO object storage.
- Creating and managing storage buckets.
- Accessing a web-based cloud storage console.
- Writing technical documentation using Markdown.
- Managing laboratory files using GitHub.

