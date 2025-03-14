FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04
# Install dependencies
RUN apt-get update && apt-get install -y \
    graphviz

# Clean up
RUN apt-get clean && rm -rf /var/lib/apt/lists/*
