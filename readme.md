Quickstart: Create a Kubernetes dev space with Azure Dev Spaces (.NET Core and Visual Studio)
> https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-netcore-visualstudio

Create a new AKS cluster
> az aks create --name rakbr-kub-dev01 --dns-name-prefix rakbr-kub-dev01 --resource-group FlashStoreDev --node-vm-size Standard_DS2_v2 --node-count 2 --kubernetes-version 1.11.3 --location eastus --generate-ssh-keys