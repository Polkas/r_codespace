FROM rocker/tidyverse:4.4.2

# Update package lists, install dependencies, and clean up cache
RUN apt-get update && apt-get install -y \
    libcurl4-openssl-dev \
    libssl-dev \
    libxml2-dev \
    git \
    libgit2-dev \
    build-essential \
    pandoc \
    && rm -rf /var/lib/apt/lists/*
