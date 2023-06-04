# Deploy Azure Machine Learning extension on AKS

## Prerequisites
- An AKS cluster running in Azure. If you have not previously used cluster extensions, you need to register the KubernetesConfiguration service provider.
- Or an Arc Kubernetes cluster is up and running. Follow instructions in connect existing Kubernetes cluster to Azure Arc.
If the cluster is an Azure RedHat OpenShift Service (ARO) cluster or OpenShift Container Platform (OCP) cluster, you must satisfy other prerequisite steps as documented in the Reference for configuring Kubernetes cluster article.
- For production purposes, the Kubernetes cluster must have a minimum of 4 vCPU cores and 14-GB memory. For more information on resource detail and cluster size recommendations, see Recommended resource planning.
- Cluster running behind an outbound proxy server or firewall needs extra network configurations.
- Install or upgrade Azure CLI to version 2.24.0 or higher.
- Install or upgrade Azure CLI extension k8s-extension to version 1.2.3 or higher.
