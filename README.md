# f5-azure-bigiq-arm

Use the appropriate button below to deploy:

- **BIGIQ**: This allows you to deploy BIG-IQ in Azure.

Commercial

  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMikej81%2Ff5-azure-bigiq-arm%2Fmaster%2Fazuredeploy.json)

MAG

  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMikej81%2Ff5-azure-bigiq-arm%2Fmaster%2Fazuredeploy.json)


- **Note**:  If you need to add a DCD, this will not currently work.  The InitScripts do not set a master key and those will need to be recreated.  [K10799025: Error Message: Master Keys differ between this BIG-IQ and the one you are attempting to discover](https://support.f5.com/csp/article/K10799025)
