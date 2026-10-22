# Use nginx:alpine-slim as base Docker Image
FROM nginx:alpine-slim

# Custom Labels
LABEL maintainer="Ranjeet Bandal"  
LABEL version="2.0"
LABEL description="A simple Nginx Application"
# OCI Labels
LABEL org.opencontainers.image.authors="Ranjeet Bandal"
LABEL org.opencontainers.image.title="Nginx Alpine Slim Application"
LABEL org.opencontainers.image.description="A lightweight Nginx application built on Alpine."
LABEL org.opencontainers.image.version="2.0"
LABEL org.opencontainers.image.revision="1234567890abcdef" 
LABEL org.opencontainers.image.created="2025-10-22T08:30:00Z"
LABEL org.opencontainers.image.url="https://github.com/ranjeet2603/docker-in-a-weekend"
LABEL org.opencontainers.image.source="https://github.com/ranjeet2603/docker-in-a-weekend/tree/main/04-Dockerfile-LABELS/Dockerfiles"
LABEL org.opencontainers.image.documentation="https://github.com/ranjeet2603/docker-in-a-weekend/tree/main/04-Dockerfile-LABELS"
LABEL org.opencontainers.image.vendor="Ranjeet Bandal"
LABEL org.opencontainers.image.licenses="Apache-2.0"

# Using COPY to copy a local file
COPY index.html /usr/share/nginx/html
