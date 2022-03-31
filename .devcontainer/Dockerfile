FROM rust:1.59.0
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt-get update && \
    apt-get install -y --no-install-recommends curl ca-certificates gcc libc6-dev git lldb && \
    cargo install cargo-edit && \
    rm -rf /var/lib/apt/lists/*