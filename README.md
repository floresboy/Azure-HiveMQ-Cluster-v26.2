# HiveMQ Virtual Machine Cluster

### vKS-26.2
This template deploys an n-Node HiveMQ cluster to Azure.


[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffloresboy%2FAzure-HiveMQ-Cluster-v26.2%2Frefs%2Fheads%2Fmain%2Fazuredeploy.json)




The following resources will be deployed bis this template:

- n Virtual Machines with HiveMQ and the HiveMQ Azure Cluster Discovery Extension installed
- An Azure Storage Account used by the Extension
- An Availability Set in which the Virtual Machines are placed
- An Azure Load Balancer used to access the HiveMQ services
- A Virtual Network in which the Virtual Machines and Load Balancer are placed
- Network Interfaces with Public IP-Addresses for the Virtual Machines
- A Network Interface with a (user selectable-)Public IP-Address for the Load Balancer

