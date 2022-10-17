# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.238.1/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version (use ubuntu-22.04 or ubuntu-18.04 on local arm64/Apple Silicon): ubuntu-22.04, ubuntu-20.04, ubuntu-18.04
ARG VARIANT="jammy"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#    && apt-get -y install --no-install-recommends make gcc g++ openjdk-17-jdk \
#    && curl "https://nodejs.org/dist/v16.18.0/node-v16.18.0.tar.gz" -O \
#    && tar xvzf node-v16.18.0.tar.gz \
#    && cd node-v16.18.0 \
#    && ./configure \
#    && make \
#    && sudo make install
