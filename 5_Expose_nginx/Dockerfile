# Use nginx:alpine-slim as base Docker Image
FROM nginx:alpine-slim

# OCI Labels
LABEL org.opencontainers.image.authors="Vivek Sangwan"
LABEL org.opencontainers.image.title="ADD Instruction to Fetch Files from a URL"

COPY ./index.html /usr/share/nginx/html

EXPOSE 80