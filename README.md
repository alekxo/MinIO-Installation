# MinIO (Installation on Ubuntu Server)

MinIO is an open-source object storage server that acts as an alternative to Amazon S3. MinIO is suitable for those who prefer more control on their object storage server but also want compatibility with S3. Applications that work with S3 for object storage can also work with MinIO.

The service stores unstructured data such as photos, videos, log files, backups, and container/VM images, and can even provide a single object storage server that pools multiple drives spread across many servers.

I will be installing single instance MinIO server on Ubuntu Server 20.04.5 LTS through Ansible and set up an SSL/TLS certificate for secure data transmission.
