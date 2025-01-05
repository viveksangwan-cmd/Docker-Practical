# Use nginx:alpine-slim as base Docker Image
FROM nginx:alpine-slim

# OCI Labels
LABEL org.opencontainers.image.authors="Vivek Sangwan"
LABEL org.opencontainers.image.title="ADD Instruction to Fetch Files from a URL"

# Using GitHub Repository to download files
ADD https://github.com/stacksimplify/docker-add-fetch-url-demo.git#v1.0.0:docs /usr/share/nginx/html
