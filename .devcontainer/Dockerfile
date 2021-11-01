ARG VARIANT="16-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

WORKDIR = /home/

COPY . .

RUN bash ./setup.sh