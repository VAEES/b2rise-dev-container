ARG NODE_VERSION="20"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${NODE_VERSION}

RUN apt-get update && apt-get -y install --no-install-recommends curl git sqlite3

USER node
RUN npm install -g @sap/cds-dk
WORKDIR /home/node
