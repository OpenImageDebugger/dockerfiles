# syntax=docker/dockerfile:1

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install -y \
    build-essential \
    ninja-build \
    clang \
    cmake \
    gdb \
    lldb \
    git \
    qt5-default \
    python3-dev \
    libpython3-dev \
    pkg-config \
&& rm -rf /var/lib/apt/lists/*
