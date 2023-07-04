I created a static web application that I had to deploy through Azure App Service Deployment --> pizza-time.azurewebsites.net 

1) Build a YAML file for pipeline. I'll use it later as an artifact.
2) Publish it.
  
    **Jobs :**
![jobs](https://github.com/devopssteven/web-app-on-azure-devops/assets/126707958/9d6f1dfa-c4b8-4a6f-91e7-8949c0af34f5)

3) Deploy it by linking it to an Azure Ressource Manager Service Connection (principal).
  
    **Deployment:**
![deployment](https://github.com/devopssteven/web-app-on-azure-devops/assets/126707958/605e40f1-3bb0-42c5-b11c-acc748550c5c)
