az account show --output table
az disk create \
  --resource-group rs-aks \
  --name aks-disk \
  --size-gb 20 \
  --query id --output tsv

az disk show -g rs-aks -n aks-disk
az disk show -g rs-aks -n aks-disk -o table
az disk show -g rs-aks -n aks-disk -o tsv --query id

az disk delete --name aks-disk --resource-group aks-disk
