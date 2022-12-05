FROM mcr.microsoft.com/devcontainers/base:alpine-3.16

# [Optional] Uncomment this section to install additional OS packages.
RUN apk update \
    && export DEBIAN_FRONTEND=noninteractive \
    && apk add --no-cache git sudo nano bash openjdk-17-jdk
