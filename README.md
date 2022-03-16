# Hello World Flask webapp

Using Vscode to demo a webapp to work locally in Python, locally with Docker, and deployed remotely to Azure.

## Locally in Python

cf. tutorial on [Flask with VScode](https://code.visualstudio.com/docs/python/tutorial-flask)

Run in VScode: left menu "Run and Debug (Ctrl+Shift+D)", then run it by selecting "Python: Flask".

This configuration is defined in `launch.json`.

## Locally with Docker

cf. same tutorial as above on [Flask with VScode (run in Docker)](https://code.visualstudio.com/docs/python/tutorial-flask#_create-a-container-for-a-flask-app-using-the-docker-extension)

Run in VScode: left menu "Run and Debug (Ctrl+Shift+D)", then run it by selecting "Docker: Python - Flask".

This configuration is defined in `launch.json`.

## Remotely in Azure

- [ ] you will need to create a "container registry" in your Azure subscription.

Tutorial to [deploy a container in Azure](https://docs.microsoft.com/en-us/learn/modules/deploy-run-container-app-service/) and/or [Deploy Docker containers to Azure App Service with Visual Studio Code](https://docs.microsoft.com/en-us/azure/developer/python/tutorial-deploy-containers-01).