# vscode-remote-container-python-flask
此專案是嘗試使用vscode的remote container套件來建議python flask的開發環境  
特別的是因為我使用了 podman 來當作 docker 的引擎所以`.devcontainer/devcontainer.json`的`"remoteUser": "vscode"`是註解起來的，如果是用docker要記得把他解除註解
