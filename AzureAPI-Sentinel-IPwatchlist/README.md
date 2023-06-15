# AzureAPI-Sentinel-IPwatchlist

This Logic App runs daily and creates a Microsoft Sentinel Watchlist for Public IP addresses in your Azure tenant. 

The Playbook's Managed Identity needs two Azure RBAC role assignments:
* **Azure Reader** role for your Tenant Root Management Group for full visibility, or some other scope if needed. 
* **Sentinel Contributor** role for your Sentinel Resource Group. 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikoiv%2FMicrosoftSentinel-Playbooks%2Fmain%2FAzureAPI-Sentinel-IPwatchlist%2Fazuredeploy.json)
