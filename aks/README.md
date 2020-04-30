# Deployment

```
- az login --service-principal --username $AZURE_APP_ID  --password $AZURE_PASSWORD --tenant $AZURE_TENANT_ID
- az aks get-credentials --resource-group $AZURE_RESOURCE_GROUP --name $AZURE_AKS_NAME
- helm upgrade ...
```