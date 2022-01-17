# Easy Buttons for Azure Deployments of Redis Enterprise
The following buttons, as well as the ARM template that they link to, can be used to deploy Azure Cache for Redis Enterprise (ACRE) to your Azure account. The templates can be modified to constrain the options which a developer or operator has when they are deploying a Redis Cache to Azure.  

### Easy Button for single E10 deployment
The following button is an example of using a button to trigger the deployment of an ARM template, [easy-button.json](https://github.com/Redislabs-Solution-Architects/acre-deploy-with-alerts/blob/main/easy-button.json), to deploy Azure Cache for Redis Enterprise with only options for Redis Enterprise.\  
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fseanbot2000%2Feasy-button%2Fmain%2Feasy-button.json)

### Easy Button for single E10 deployment with recommended Alerts
This button is an example of using a button to trigger the deployment of an ARM template, [easy-button-alerts.json](https://github.com/Redislabs-Solution-Architects/acre-deploy-with-alerts/blob/main/easy-button-alerts.json), to deploy Azure Cache for Redis Enterprise with only options for Redis Enterprise as well as a set of recommended alerts which will be enabled but without alert actions.\
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fseanbot2000%2Feasy-button%2Fmain%2Feasy-button-alerts.json)

### Easy Button for E10 Georeplicated Cache with recommended Alerts
This button is an example of using a button to trigger the deployment of an ARM template, [easy-button-geo.json](https://github.com/Redislabs-Solution-Architects/acre-deploy-with-alerts/blob/main/easy-button-geo.json), to deploy Azure Cache for Redis Enterprise with an active-active geo-replicated Redis Enterprise cluster as well as a set of recommended alerts which will be enabled but without alert actions. You can edit this template prior to deployment to add the preferred regions for the geo-replicated cache which the organization prefers.\ 
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fseanbot2000%2Feasy-button%2Fmain%2Feasy-button-geo.json)
