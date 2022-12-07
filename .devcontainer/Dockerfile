FROM ubuntu:22.04

RUN adduser -q --gecos "" --disabled-password mesonuser \
    && apt-get update \
    && apt-get install -y meson ninja-build \
    && rm -fr /var/lib/apt/lists/*
