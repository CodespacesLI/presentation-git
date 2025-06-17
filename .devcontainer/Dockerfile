# [Choice] Node version (use any LTS or latest as needed)
FROM node:lts-bookworm-slim

# Install zsh & git
RUN apt-get update && apt-get install -y zsh git && rm -rf /var/lib/apt/lists/*

# Set default shell
SHELL ["/bin/zsh", "-c"]

WORKDIR /workspaces/Todoly

