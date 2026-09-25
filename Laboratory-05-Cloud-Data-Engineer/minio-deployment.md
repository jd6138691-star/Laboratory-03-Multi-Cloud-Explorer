# MinIO Deployment Documentation

## Technical Steps

### 1. Deploy MinIO Using Docker

I deployed the MinIO storage server using the following Docker command:


docker run -d --name minio \
  -p 9000:9000 \
  -p 9001:9001 \
  -e "MINIO_ROOT_USER=admin" \
  -e "MINIO_ROOT_PASSWORD=password123" \
  quay.io/minio/minio server /data --console-address ":9001"
