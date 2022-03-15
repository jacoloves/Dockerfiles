FROM rust:1.59.0-alpine3.15

RUN apk add --no-cache bash docker-cli git tree && \
    rustup component add rls rust-analysis rust-src rustfmt clippy