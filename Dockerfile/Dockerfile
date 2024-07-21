FROM rust:1.79.0-alpine3.20

WORKDIR /data

RUN rustup component add clippy
RUN rustup component add rustfmt

EXPOSE 8080