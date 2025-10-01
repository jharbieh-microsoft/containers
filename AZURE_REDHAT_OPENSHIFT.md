Azure Red Hat OpenShift (ARO)

Azure Red Hat OpenShift (ARO) is a jointly operated, fully managed OpenShift service from Microsoft and Red Hat that runs on Azure. It provides single-tenant OpenShift clusters with enterprise support, integrated security, and native connectivity to Azure services.

---

## What it is

ARO is a managed OpenShift platform that combines Red Hat OpenShift with Azure infrastructure and operations. It offers a Kubernetes-native developer and operator experience while delegating control plane and platform management to the service.

## Core concepts

- Managed control plane — Red Hat and Microsoft operate the control plane and platform lifecycle; customers run workloads and manage node pools.[^1]
- Single-tenant clusters — Dedicated clusters improve isolation and compliance for enterprise workloads.[^1]
- OpenShift tooling — Built-in support for Operators, Source-to-Image (S2I) builds, and the OpenShift developer console.

## Key features

1. Joint Red Hat–Microsoft operations — Platform lifecycle, updates, and joint support are provided by Red Hat and Microsoft.[^1]
2. Azure-native integration — Microsoft Entra ID (Azure AD), Azure networking, Storage, Key Vault, and monitoring services.
3. Platform services — Image build pipelines, Operators, logging, metrics, and optional service mesh capabilities.
4. Scalability & availability — Support for multi-zone/regional deployments with automated updates and resiliency features.[^1]
5. Enterprise compliance — Certifications and controls appropriate for regulated workloads.[^2]

## Operational benefits

- Reduced operational overhead — Control plane and platform management are handled by the managed service.
- Unified support — A single support experience for platform and infrastructure problems via the Red Hat–Microsoft arrangement.[^1]
- Standardized platform — Operator-driven components and platform-as-code patterns for repeatable deployments.

## Common use cases

- Enterprise applications that require OpenShift-specific operators and tooling.
- Workloads requiring stronger isolation or regulatory compliance.
- Teams that want the OpenShift developer experience without operating the control plane.

## Integration with Azure services

- Observability — Azure Monitor and Log Analytics for metrics and logs.
- Identity — Microsoft Entra ID for authentication and RBAC.
- Storage & secrets — Azure Storage and Azure Key Vault for persistent volumes and secret management.

## Limitations & considerations

- Limited control-plane customization — Customers cannot directly manage control plane components; deep customization is restricted.[^1]
- Regional availability and quotas — Validate availability and capacity in target regions before planning production deployments.
- Cost and sizing — Compare ARO to AKS or other Azure container services for trade-offs around cost, control, and required features.

## Summary

Azure Red Hat OpenShift (ARO) provides a managed OpenShift experience on Azure for organizations that need enterprise OpenShift features with the operational benefits of a managed cloud platform.

## References

[^1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[^2]: https://www.redhat.com/en/technologies/containers/openshift
- Single-tenant clusters — Dedicated clusters improve isolation and compliance for enterprise workloads.[^1]
- OpenShift tooling — Built-in support for Operators, S2I builds, integrated CI/CD patterns, and the OpenShift developer console.

## Key features

1. Joint Red Hat–Microsoft operations — Platform lifecycle, updates, and joint support are provided by Red Hat and Microsoft.[^1]
2. Azure-native integration — Microsoft Entra ID (Azure AD), Azure networking, Storage, Key Vault, and monitoring services.
3. Platform services — Image build pipelines, Operators, logging, metrics, and optional service mesh capabilities.
4. Scalability & availability — Support for multi-zone/regional deployments with automated updates and resiliency features.[^1]
5. Enterprise compliance — Certifications and controls appropriate for regulated workloads.[^2]

## Operational benefits

- Reduced operational overhead — Control plane and platform management are handled by the managed service.
- Unified support — A single support experience for platform and infrastructure problems via the Red Hat–Microsoft arrangement.[^1]
- Standardized platform — Operator-driven components and platform-as-code patterns for repeatable deployments.

## Common use cases

- Enterprise applications that require OpenShift-specific operators and tooling.
- Workloads requiring stronger isolation or regulatory compliance.
- Teams that want the OpenShift developer experience without operating the control plane.

## Integration with Azure services

- Observability — Azure Monitor and Log Analytics for metrics and logs.
- Identity — Microsoft Entra ID for authentication and RBAC.
- Storage & secrets — Azure Storage and Azure Key Vault for persistent volumes and secret management.

## Limitations & considerations

- Limited control-plane customization — Customers cannot directly manage control plane components; deep customization is restricted.[^1]
- Regional availability and quotas — Validate availability and capacity in target regions before planning production deployments.
- Cost and sizing — Compare ARO to AKS or other Azure container services for trade-offs around cost, control, and required features.

## Summary

Azure Red Hat OpenShift (ARO) provides a managed OpenShift experience on Azure for organizations that need enterprise OpenShift features combined with the operational benefits of a managed cloud platform.

## References

[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift
Azure Red Hat OpenShift (ARO)

Azure Red Hat OpenShift (ARO) is a jointly operated, fully managed OpenShift service from Microsoft and Red Hat that runs on Azure. ARO delivers single-tenant OpenShift clusters with enterprise support, integrated security, and native connectivity to Azure services.

---

## What it is

ARO is a managed OpenShift platform that combines Red Hat OpenShift with Azure infrastructure and operations. It offers a Kubernetes-native developer and operator experience (Operators, Source-to-Image, Developer Console) while delegating control plane and platform management to the service.

## Core concepts

- Managed control plane — Red Hat and Microsoft operate the control plane and platform lifecycle; customers run workloads and manage node pools.[^1]
- Single-tenant clusters — Dedicated clusters improve isolation and compliance for enterprise workloads.[^1]
- OpenShift tooling — Built-in support for Operators, S2I builds, integrated CI/CD patterns, and the OpenShift developer console.

## Key features

1. Joint Red Hat–Microsoft operations — Platform lifecycle, updates, and joint support are provided by Red Hat and Microsoft.[^1]
2. Azure-native integration — Microsoft Entra ID (Azure AD), Azure networking, Storage, Key Vault, and monitoring services.
3. Platform services — Image build pipelines, Operators, logging, metrics, and optional service mesh capabilities.
4. Scalability & availability — Support for multi-zone/regional deployments with automated updates and resiliency features.[^1]
5. Enterprise compliance — Certifications and controls appropriate for regulated workloads.[^2]

## Operational benefits

- Reduced operational overhead — Control plane and platform management are handled by the managed service.
- Unified support — A single support experience for platform and infrastructure problems via the Red Hat–Microsoft arrangement.[^1]
- Standardized platform — Operator-driven components and platform-as-code patterns for repeatable deployments.

## Common use cases

- Enterprise applications that require OpenShift-specific operators and tooling.
- Workloads requiring stronger isolation or regulatory compliance.
- Teams that want the OpenShift developer experience without operating the control plane.

## Integration with Azure services

- Observability — Azure Monitor and Log Analytics for metrics and logs.
- Identity — Microsoft Entra ID for authentication and RBAC.
- Storage & secrets — Azure Storage and Azure Key Vault for persistent volumes and secret management.

## Limitations & considerations

- Limited control-plane customization — Customers cannot directly manage control plane components; deep customization is restricted.[^1]
- Regional availability and quotas — Validate availability and capacity in target regions before planning production deployments.
- Cost and sizing — Compare ARO to AKS or other Azure container services for trade-offs around cost, control, and required features.

## Summary

Azure Red Hat OpenShift (ARO) provides a managed OpenShift experience on Azure for organizations that need enterprise OpenShift features combined with the operational benefits of a managed cloud platform.

## References

[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift

---

## What it is

ARO is a managed OpenShift platform that combines Red Hat OpenShift with Azure infrastructure and operations. It offers a Kubernetes-native developer and operator experience (Operators, Source-to-Image, Developer Console) while delegating control plane and platform management to the service.

## Core concepts

- Managed control plane — Red Hat and Microsoft operate the control plane and platform lifecycle; customers run workloads and manage node pools.[^1]
- Single-tenant clusters — Dedicated clusters improve isolation and compliance for enterprise workloads.[^1]
- OpenShift tooling — Built-in support for Operators, S2I builds, integrated CI/CD patterns, and the OpenShift developer console.

## Key features

1. Joint Red Hat–Microsoft operations — Platform lifecycle, updates, and joint support are provided by Red Hat and Microsoft.[^1]
2. Azure-native integration — Microsoft Entra ID (Azure AD), Azure networking, Storage, Key Vault, and monitoring services.
3. Platform services — Image build pipelines, Operators, logging, metrics, and optional service mesh capabilities.
4. Scalability & availability — Support for multi-zone/regional deployments with automated updates and resiliency features.[^1]
5. Enterprise compliance — Certifications and controls appropriate for regulated workloads.[^2]

## Operational benefits

- Reduced operational overhead — Control plane and platform management are handled by the managed service.
- Unified support — A single support experience for platform and infrastructure problems via the Red Hat–Microsoft arrangement.[^1]
- Standardized platform — Operator-driven components and platform-as-code patterns for repeatable deployments.

## Common use cases

- Enterprise applications that require OpenShift-specific operators and tooling.
- Workloads requiring stronger isolation or regulatory compliance.
- Teams that want the OpenShift developer experience without operating the control plane.

## Integration with Azure services

- Observability — Azure Monitor and Log Analytics for metrics and logs.
- Identity — Microsoft Entra ID for authentication and RBAC.
- Storage & secrets — Azure Storage and Azure Key Vault for persistent volumes and secret management.

## Limitations & considerations

- Limited control-plane customization — Customers cannot directly manage control plane components; deep customization is restricted.[^1]
- Regional availability and quotas — Validate availability and capacity in target regions before planning production deployments.
- Cost and sizing — Compare ARO to AKS or other Azure container services for trade-offs around cost, control, and required features.

## Summary

Azure Red Hat OpenShift (ARO) provides a managed OpenShift experience on Azure for organizations that need enterprise OpenShift features combined with the operational benefits of a managed cloud platform.

## References

[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift

Azure Red Hat OpenShift (ARO)

Azure Red Hat OpenShift (ARO) is a jointly operated, fully managed OpenShift service from Microsoft and Red Hat that runs on Azure. ARO provides single-tenant OpenShift clusters with enterprise support, integrated security, and native connectivity to Azure services.

---

## Core concepts

- **Managed OpenShift platform** — ARO runs Red Hat OpenShift and provides a managed control plane and platform services while customers manage workloads and node pools.[^1]
- **Single-tenant clusters** — Dedicated clusters improve isolation, compliance, and predictable performance.[^1]
- **OpenShift developer and operator tooling** — Includes Operators, Source-to-Image (S2I), Developer Console, and integrated CI/CD workflows.

## Key features

1. **Joint Red Hat–Microsoft operations** — Platform lifecycle, upgrades, and platform-level support are handled collaboratively.[^1]
2. **Azure-native identity and security** — Integrates with Microsoft Entra ID (Azure AD), RBAC, network policies, and Azure security services.[^1]
3. **Platform services** — Built-in image build pipelines, Operators, logging, metrics, and optional service mesh capabilities.
4. **Scalability & availability** — Supports multi-zone and regional deployments with automated updates and resilience features.[^1]
5. **Azure integration** — First-class connectivity to Azure Storage, Key Vault, networking, and observability services.

## Operational benefits

- Reduces operational overhead by shifting control plane and platform management to the managed service.
- Offers a single support experience from Red Hat and Microsoft for platform and infrastructure issues.[^1]
- Provides a standardized, operator-driven platform that simplifies platform-as-code and reproducible deployments.

## Common use cases

- Enterprise applications that need OpenShift-specific features and operator ecosystems.
- Workloads requiring stronger isolation or compliance with regulatory frameworks.
- Teams that want the OpenShift developer experience but prefer a managed cloud offering.

## Integration with Azure services

- Azure Monitor & Log Analytics for metrics and logs.
- Microsoft Entra ID for identity and access control.
- Azure Storage and Azure Key Vault for persistent storage and secret management.

## Limitations & considerations

- Customers do not control the control plane directly; deep control-plane customization is limited.[^1]
- Regional availability, quotas, and pricing should be validated for planned deployments.
- Evaluate ARO against alternatives (AKS, Azure Container Apps) for cost, control, and feature trade-offs.

## Summary

Azure Red Hat OpenShift (ARO) delivers a managed OpenShift experience on Azure for customers who need enterprise OpenShift features with the operational benefits of a managed cloud platform.

## References

[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift

[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift
[1]: https://learn.microsoft.com/en-us/azure/openshift/intro-openshift
[2]: https://www.redhat.com/en/technologies/containers/openshift