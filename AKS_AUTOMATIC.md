# AKS Automatic

AKS Automatic is a fully managed, opinionated mode of AKS that simplifies cluster deployment and operations while preserving Kubernetes capabilities. It provides production-ready clusters with preconfigured best practices for security, scaling, networking, and observability.

## Overview

AKS Automatic provides:

- **Automated cluster setup**: Node management, scaling, OS patching, upgrades, and health monitoring are handled automatically.
- **Production-ready defaults**: Clusters come preconfigured for performance, reliability, and security, adhering to Microsoft's well-architected guidelines.
- **Extensible Kubernetes access**: Full Kubernetes API and ecosystem are available for customization when needed.

## Key features

1. **One-click, production-ready clusters** – Create Standard tier clusters with up to 5,000 nodes, availability zone spread, and SLA-backed uptime. Pods are efficiently bin-packed to optimize resource use.
2. **Automatic node management & scaling** – Node autoprovisioning, Karpenter, HPA, VPA, and KEDA for event-driven scaling. Automatic node repair and upgrades included.
3. **Built-in security & policy enforcement** – Preconfigured RBAC via Microsoft Entra, API server vNet integration for private network access, image hygiene, workload identity, and Azure Policy integration.
4. **Streamlined networking** – Managed Azure CNI with Cilium, managed NAT gateway for egress, managed NGINX ingress, and optional Istio-based service mesh.
5. **Observability & monitoring** – Managed Prometheus, Managed Grafana, and Container Insights with built-in dashboards.
6. **Simple application deployment** – Automated deployment pipelines via GitHub Actions or other CI/CD tools.

## Operational benefits

- **Reduced complexity** – Shift focus from cluster operations to application development; day‑2 management automated.
- **High reliability & security** – Hardened defaults, automated upgrades, and proactive patching.
- **Elastic scalability** – Nodes and pods dynamically provisioned based on workload demands.
- **Developer-friendly** – Full Kubernetes API compatibility and existing toolchain support.
- **Cost efficiency** – Dynamic scaling and optimized resource usage minimize idle costs.

## Limitations & considerations

- **Opinionated defaults** – Reduced low-level configuration flexibility; may not suit very custom architectures.
- **Regional & quota constraints** – Availability tied to regions supporting API server vNet integration.
- **Operational cost variability** – Dynamic node provisioning can yield unpredictable costs without guardrails.
- **Vendor reliance** – Managed defaults use Azure-specific primitives, increasing operational coupling.

## Common use cases

- Startups and small teams that want managed, production-ready clusters.
- Enterprise platform teams providing self-service, secure clusters to developers.
- AI/ML workloads with GPU support and auto-scaling.
- Microservices and cloud-native applications that benefit from managed defaults.

## Integration with Azure services

- Azure Monitor, Metrics, and Grafana for monitoring.
- Azure Key Vault for secrets management.
- CI/CD pipelines via GitHub Actions or Azure DevOps.

## Summary

AKS Automatic empowers teams to deploy highly available, secure, and scalable Kubernetes clusters with minimal manual intervention while retaining the full Kubernetes API surface.

## References

[1]: https://learn.microsoft.com/en-us/azure/aks/intro-aks-automatic
[2]: http://blog.aks.azure.com/2024/05/22/aks-automatic
[3]: https://azurebeast.com/posts/aks-automatic/
[4]: https://windowsforum.com/threads/aks-automatic-production-ready-one-click-kubernetes-on-azure.381078/