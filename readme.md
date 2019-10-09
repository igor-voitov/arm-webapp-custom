<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Figor-voitov%2Farm-webapp-custom%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Figor-voitov%2Farm-webapp-custom%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

<img src="overview.png"/>	

ARM template which deploys the following:

	• An Azure Datalake Gen 2 storage account
	• A key vault with a secret
	• A virtual network
	• A web app that can access both the datalake storage and the key vault secret
	• Use tags to group the resources

