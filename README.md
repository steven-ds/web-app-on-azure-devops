1) Create a static web application : I had to deploy it through **Azure App Service Deployment** --> [(https://pizza-time.azurewebsites.net/) ](https://pizza-time.azurewebsites.net/)
2) Package it : Dockerfile 
4) Create a deployable configuration file (on Azure DevOps) : I created a YAML file that describes the target environment, the steps, and the tasks.
5) Configure a deployment pipeline that automates the process (on Azure DevOps).

    **Jobs :**
![jobs](https://github.com/devopssteven/web-app-on-azure-devops/assets/126707958/9d6f1dfa-c4b8-4a6f-91e7-8949c0af34f5)
  
    **Deployment:**
![deployment](https://github.com/devopssteven/web-app-on-azure-devops/assets/126707958/605e40f1-3bb0-42c5-b11c-acc748550c5c)
