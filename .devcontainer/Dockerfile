FROM mcr.microsoft.com/devcontainers/base:ubuntu

ARG BUN_VERSION

# bunのインストール
RUN curl -fsSL https://bun.sh/install | BUN_INSTALL=/usr bash -s "bun-v${BUN_VERSION}"