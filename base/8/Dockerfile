FROM cypress/base:8

# override apt sources.list
COPY sources.list /etc/apt/

# install additional packages
RUN apt-get update -y && apt-get install -y \
    jq \
    && rm -rf /var/lib/apt/lists/*
