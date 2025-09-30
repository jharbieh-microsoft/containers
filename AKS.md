[# Azure Kubernetes Service (AKS)
Azure Kubernetes Service (AKS) is Microsoft’s managed Kubernetes service that simplifies deployment, management, and scaling of containerized applications while offloading operational overhead to Azure. It provides high availability, security, and integration with Azure services.

## Core concepts

AKS is built on the **Kubernetes open-source platform** for container orchestration and includes two main components:
- **Control plane**: Managed by Azure, hosting the API server, etcd, scheduler, controller manager, and cloud-controller manager to orchestrate your cluster and workloads [^1^] [^3^] [^4^].  
- **Nodes (worker/agent VMs)**: Run the containerized applications (pods). Users manage the node pools, including scaling, upgrades, and maintenance, while Azure handles control plane operations [^3^] [^7^].  
  
AKS clusters support **Linux (Ubuntu/Azure Linux)** and **Windows Server nodes**, with container runtimes using containerd for both platforms [^1^]
. Nodes are grouped into **system** and **user node pools**, with system pools hosting essential Kubernetes services and user pools running workloads [^1^] [^7^].
## Key features

1. **Managed Kubernetes control plane** – Azure handles health monitoring, patching, upgrades, and high availability without extra cost, reducing operational complexity [^4^] [^5^].
2. **Autoscaling** – Supports **Horizontal Pod Autoscaler (HPA)**, cluster autoscaler for nodes, and **KEDA** for event-driven workloads, enabling dynamic scaling to match demand [^5^].  
3. **Networking and Connectivity** – Offers **Kubenet** or **Azure CNI** networking models, enabling secure communication between pods and external resources, with support for service meshes like Istio [^7^].  
4. **Security and Compliance** – Integrates with **Azure RBAC**, **Microsoft Entra ID**, private clusters, Azure Policy enforcement, and image hygiene tools, ensuring regulatory compliance (SOC, ISO, HIPAA, PCI DSS) [^4^] [^6^].  
5. **Observability** – Built-in monitoring via **Azure Monitor**, **Container Insights**, and support for managed Prometheus and Grafana dashboards [^5^].  
6. **Storage and Workload Flexibility** – Persistent storage support with Azure Disks, Files, and NetApp Files; GPU-enabled nodes for AI/ML workloads [^5^] [^6^].  
7. **Development Tool Integration** – Supports Helm, Kubernetes CLI (kubectl), Visual Studio Code extensions, and CI/CD pipelines (GitHub Actions, Azure DevOps) [^5^] [^6^].  
  
## Operational benefits

- **Reduced complexity** – Offloads the management of control plane components to Azure and simplifies node operations [^4^].
- **High reliability** – SLA-backed uptime (up to 99.95% with Premium tier), self-healing clusters, and high availability across regions and availability zones [^3^].
- **Cost efficiency** – Only pay for worker nodes and adjustable VM sizes, with options for **standard, reserved, or spot VMs** to optimize budget [^6^].
- **Elastic and flexible** – Easily scale clusters up or out, support mixed OS and GPU workloads, and integrate with multi-region or hybrid deployments via Azure Arc [^4^] [^6^].
- **Developer-friendly** – Focus on deploying applications rather than managing infrastructure, with full Kubernetes API compatibility for advanced use cases [^4^].
  
## Common use cases

- **Microservices applications** – Simplified deployment with scalable, resilient architecture [^5^].
- **AI/ML workloads** – GPU support and cloud integration for model training and inference [^5^] [^6^].
- **CI/CD and DevOps automation** – Integrates with GitHub Actions, Azure DevOps, and Kubernetes Event-Driven Autoscaling for streamlined pipelines [^5^].
- **Edge and IoT solutions** – Deploy containers closer to end-users with low-latency performance [^5^].
- **Hybrid and multi-cloud** – Manage Kubernetes across on-premises, Azure, and other clouds using Azure Arc [^5^].
  
## Integration with Azure services

- **Azure Monitor & Container Insights** – Centralized logging and metrics.
- **Azure Policy** – Governance and policy enforcement across clusters.
- **Azure Key Vault** – Secret management for secure applications.
- **Azure Networking Services** – Managed CNI, NAT gateway, DNS, and ingress controllers.
  
## Limitations & considerations

- Users **do not control the master nodes**, limiting full customization of control plane components [^3^] [^7^].
- Cluster creation and scaling are subject to **regional availability and quotas**.
- Opinionated defaults and automation may not suit highly customized environments.
- Cost dynamics depend on dynamic node scaling; proper monitoring and budgeting are recommended [^6^].
  
## Summary

AKS provides a production-ready, managed Kubernetes environment that enables rapid deployment, scalability, and integration with Azure services. It offloads operational responsibilities for the control plane, reduces complexity, enforces security best practices, and allows teams to focus on application development while maintaining full Kubernetes extensibility for advanced workloads.

## References

[1]: https://learn.microsoft.com/en-us/azure/aks/core-aks-concepts
[3]: https://docs.azure.cn/en-us/aks/what-is-aks
[4]: https://learn.microsoft.com/en-us/azure/aks/what-is-aks
[5]: https://dotstark.com/blogs/azure-kubernetes-service-guide
[6]: https://collabnix.com/what-is-azure-kubernetes-serviceaks-and-why-do-you-need-it-part-1/
[7]: https://learn.microsoft.com/en-us/azure/aks/faq