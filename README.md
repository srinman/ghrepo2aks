# Azure Kubernetes Service, Azure Active Directory Federated Credentials and Github Actions

This demonstrates how to leverage federated identity credential with user-assigned managed identity to deploy K8S workload into AKS cluster with Azure RBAC for Kubernetes Authorization.  It's important to note that this does not require any administrator to login to AKS/K8S to setup any roles as it's taken care of by Azure RBAC for K8S auth layer. In few steps,  you could a good secured process to deploy workload into your AKS cluster without any secrets laying around!


https://learn.microsoft.com/en-us/azure/active-directory/workload-identities/workload-identity-federation-create-trust-user-assigned-managed-identity?pivots=identity-wif-mi-methods-azp


##