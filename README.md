# mi100-server

Build locally and push to ghcr:
```bash
docker buildx build --no-cache -f Dockerfile.mi100   --build-arg MAX_JOBS=$(nproc)   -t ghcr.io/ekatralis/vllm-mi100-cern:v1.0.0   -t ghcr.io/ekatralis/vllm-mi100-cern:latest   --push .
```

