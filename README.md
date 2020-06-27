# k8s Notebook


## 安裝 kubectl

## 安裝az-cli

*[Azure CLI](https://docs.microsoft.com/zh-tw/cli/azure/install-azure-cli?view=azure-cli-latest)

```bash
az login
```

* 綁定config

```bash
az aks get-credentials --resource-group NissanLineBC --name TagSystem
```

## 進入Mongo DB

```bash
kubectl --namespace=tagsystem exec -it mongo-774fff85d5-6h29s -- mongo
```