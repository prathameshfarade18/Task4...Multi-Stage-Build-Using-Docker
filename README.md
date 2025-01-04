# Task4...Multi-Stage-Build-Using-Docker

#What is multi-Stage Build
A multi-stage build allows us to use multiple FROM statements within a single Dockerfile. Each stage can have its own base image, and we can selectively copy only the necessary artifacts to the final stage. This helps reduce the final image size and avoid unnecessary build dependencies in production.
