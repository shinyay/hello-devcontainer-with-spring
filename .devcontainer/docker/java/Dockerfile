FROM mcr.microsoft.com/devcontainers/java:1-21-bullseye

RUN apt-get update && apt-get -y install git zip unzip curl vim && \
curl -s "https://get.sdkman.io" | bash

WORKDIR /work