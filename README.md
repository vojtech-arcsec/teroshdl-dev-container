# TerosHDL Dev Container

## General

Since TerosHDL plugin for VS Code has a lot of [prerequisities](https://terostechnology.github.io/terosHDLdoc/docs/installation_checklist/installation), it was benefitial to bundle them in a Docker container. 

## Requirements

1. Docker running in WSL 2
   - [this manual](https://dev.to/bowmanjd/install-docker-on-windows-wsl-without-docker-desktop-34m9) can be useful. Not all the steps are necessarry
1. [Development container plugin in VS Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
   - [these docs](https://code.visualstudio.com/docs/devcontainers/containers) explain the basics and more advanced stuff

## Usage

1. Clone the repository
1. Open the repo in VS Code
1. Hit <kbd>F1</kbd> and search for `Dev container: Reopen the folder in container`
1. Docker then shall build the image and VS Code backend (running in the container) shall install the TerosHDL plugin. 
