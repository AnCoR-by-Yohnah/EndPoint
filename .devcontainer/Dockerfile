FROM mcr.microsoft.com/devcontainers/base:bookworm

RUN apt-get update && apt-get -y dist-upgrade && \
    apt-get -y install iputils-ping python3-pip && \
    pip install build twine --break-system-packages && \
    pip install ipython --break-system-packages
