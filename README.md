# hththt
# hththt

## Multi-architecture Docker Build
To build a multi-architecture Docker image, use the following command:
```bash
docker buildx build --platform linux/amd64,linux/arm64 -t your-image-name:latest .
```
This command uses Docker Buildx to build the image for both `linux/amd64` and `linux/arm64` platforms.
