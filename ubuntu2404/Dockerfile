# syntax=docker/dockerfile:1

FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install -y \
    build-essential \
    ccache \
    clang \
    cmake \
    gdb \
    git \
    libprotobuf-dev \
    libpython3-dev \
    lldb \
    ninja-build \
    pkg-config \
    protobuf-compiler \
    python3-dev \
    qtbase5-dev \
&& rm -rf /var/lib/apt/lists/*
