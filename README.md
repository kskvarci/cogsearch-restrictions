# Azure Cognitive Search - ARM Template

This repository contains an ARM template and parameters file that will deploy a cognitive search resource using new API IP whitelisting functionality contained in the latest preview API.

To deploy, simply adjust the parameters and deploy the template with your tool of choice. 

Example for Azure CLI:

```
az group deployment create --resource-group CogSearch-Rg --name cogsearch1 --template-file ./azuredeploy.json --parameters ./azuredeploy.parameters.json
```