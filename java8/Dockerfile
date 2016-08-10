FROM ubuntu:xenial
MAINTAINER Philip Stehlik "p@pstehlik.com"

# fix the bash issues that can come up in ubuntu docker runs
RUN rm /bin/sh && ln -s /bin/bash /bin/sh

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y openjdk-8-jdk  --no-install-recommends && \
  rm -rf /var/lib/apt/lists/*
