FROM ubuntu:latest

# Install necessary packages, including iproute2
RUN apt-get update && \
    apt-get install -y iproute2 iputils-ping curl wireguard tcpdump openresolv openssh-client && \
    rm -rf /var/lib/apt/lists/*

