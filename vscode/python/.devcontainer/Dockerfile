FROM mcr.microsoft.com/devcontainers/python:1-3.10-bookworm

COPY .vscode/git.alias /home/vscode/.git.alias
COPY .vscode/.gitconfig /home/vscode/.gitconfig

RUN echo 'source $HOME/.git.alias' >> /home/vscode/.bashrc