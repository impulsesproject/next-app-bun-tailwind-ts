FROM oven/bun:latest

RUN apt update -y && apt upgrade -y

WORKDIR /workspace
COPY . .

RUN chmod +x .devcontainer/postCreate.sh