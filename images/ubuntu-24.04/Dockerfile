FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive
ENV TZ=Etc/UTC

RUN apt-get update && apt-get install -y --no-install-recommends \
    bash \
    bash-completion \
    sudo \
    ca-certificates \
    curl \
    wget \
    git \
    openssh-client \
    vim \
    nano \
    less \
    file \
    procps \
    iproute2 \
    iputils-ping \
    dnsutils \
    build-essential \
    cmake \
    pkg-config \
    python3 \
    python3-pip \
    python3-venv \
    nodejs \
    npm \
    && rm -rf /var/lib/apt/lists/*

ENV HOME=/root
WORKDIR /workspace

CMD ["/bin/bash"]
