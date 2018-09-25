---
services: Kubernetescluster
platforms: java
author: milismsft
---

## Getting Started with Kubernetescluster - Manage Kubernetes Cluster - in Java ##


  Azure Container Service (AKS) sample for managing a Kubernetes cluster.
    - Create an Azure Container Service (AKS) with managed Kubernetes cluster
    - Create a SSH private/public key
    - Update the number of agent virtual machines in the Kubernetes cluster
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aks-java-manage-kubernetes-cluster.git

    cd aks-java-manage-kubernetes-cluster

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.