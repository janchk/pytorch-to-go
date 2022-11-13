# Pytorch-To-Go

Simple config for [Visual Studio Code](https://code.visualstudio.com) to start working with [Pytorch](https://pytorch.org/) right away.

***

This config based on [Devcontainer](https://code.visualstudio.com/docs/devcontainers/containers) extension of vscode.

### How-to:  *(docker gpu)*
1. Install [Visual Studio Code](https://code.visualstudio.com) on your host system
2. Open this repository with your vscode editor
3. Install docker on your host system
4. Install nvidia-docker
    * (On Linux) [Guide](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker)
    * (On Windows) [Guide](https://docs.nvidia.com/cuda/wsl-user-guide/index.html)
5. Install [devcontainer](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension of vscode.
6. Now you should be able to execute command **Dev Containers: Open Folder in Container...** from vscode which will open current directory insude container with pytorch.

You can add `.devcontainer` folder to the project you like and develop it inside container with GPU support!