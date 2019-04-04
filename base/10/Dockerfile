# cypress/base:10 uses node:10.13
# cypress/base:10.15.3 uses node:10.15.3
FROM cypress/base:10.15.3

# install additional packages
RUN apt-get update -y && apt-get install -y \
    jq \
    && rm -rf /var/lib/apt/lists/*
