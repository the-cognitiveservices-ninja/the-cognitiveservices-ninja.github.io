---
tags:
- development
- visual studio code
categories: []
layout: post
title: Visual Studio Code Remote Development
text: ''

---
**Visual Studio Code Remote Development** allows you to use a container, remote machine, or the [Windows Subsystem for Linux](https://docs.microsoft.com/windows/wsl) (WSL) as a full-featured development environment. You can:

* Develop on the **same operating system** you deploy to or use **larger or more specialized** hardware.
* **Separate** your development environment to avoid impacting your local **machine configuration**.
* Make it easy for new contributors to **get started** and keep everyone on a **consistent environment**.
* Use tools or runtimes **not available** on your local OS or manage **multiple versions** of them.
* Develop your Linux-deployed applications using the **Windows Subsystem for Linux**.
* Access an **existing** development environment from **multiple machines or locations**.
* Debug an **application running somewhere else** such as a customer site or in the cloud.

No source code needs to be on your local machine to get these benefits. Each extension in the Remote Development extension pack can run commands and other extensions directly inside a container, in WSL, or on a remote machine so that everything feels like it does when you run locally.

## Getting started

### 123Code extension pack

The [123Code extension pack](https://marketplace.visualstudio.com/items?itemName=holgerimbery.123code) includes three extensions of the Microsoft [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) beside some other very usefull extentions to support you developing remotely. See the following articles to get started with each of them:

* [Remote - SSH](https://code.visualstudio.com/docs/remote/ssh) - Connect to any location by opening folders on a remote machine/VM using SSH.
* [Remote - Containers](https://code.visualstudio.com/docs/remote/containers) - Work with a separate toolchain or container-based application inside (or mounted into) a container.
* [Remote - WSL](https://code.visualstudio.com/docs/remote/wsl) - Get a Linux-powered development experience in the Windows Subsystem for Linux.

## Remote tutorials (source Microsoft)

The tutorials below will walk you through running Visual Studio Code with the Remote Development extensions.


* [Remote via SSH](https://code.visualstudio.com/docs/remote/ssh-tutorial)
Connect to remote and virtual machines with Visual Studio Code via SSH.

* [Work in WSL](https://code.visualstudio.com/docs/remote/wsl-tutorial)
Run Visual Studio Code in Windows Subsystem for Linux.

* [Develop in Containers](https://code.visualstudio.com/docs/remote/containers-tutorial)
Run Visual Studio Code in a Docker Container.

* [GitHub Codespaces](https://docs.github.com/github/developing-online-with-codespaces/using-codespaces-in-visual-studio-code)
Connect to a codespace with Visual Studio Code.