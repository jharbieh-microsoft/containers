# Web App for Containers (Azure App Service)

Azure App Service Containers allows you to run containerized web applications in a fully managed PaaS environment, providing seamless deployment, scalability, and integration with other Azure services.

## Overview

Azure App Service supports custom Docker containers that can host web applications on Windows or Linux. It abstracts the underlying infrastructure, enabling developers to run containerized apps without managing VMs. Applications can pull container images from Azure Container Registry (ACR) or external registries, and updates can be managed through image tags or continuous deployment workflows.

## Key features

1. **Custom container deployments** – Deploy images from ACR or Docker Hub with support for many languages and frameworks.
2. **Sidecars** – App Service supports auxiliary sidecar containers alongside a main container for telemetry, caching, or AI inference.
3. **Scaling and management** – Autoscaling (including scale-to-zero in some scenarios), health checks, and self-healing mechanisms.
4. **Volume mounts and storage** – Persistent storage via Azure Storage or App Service mounted volumes.
5. **Integrated monitoring and security** – Integration with Azure Monitor, Log Analytics, Key Vault, and managed identities.
6. **Seamless updates** – Update via continuous deployment or explicit image tags for predictable releases.

## Common use cases

- Web applications built with .NET, Node.js, Python, Java, or custom frameworks.
- Microservices with sidecars for auxiliary functions.
- AI/ML inference alongside application containers.
- Dev/test environments integrated with CI/CD pipelines.

## Integration with Azure services

- Azure Container Registry (ACR)
- Azure Monitor & Log Analytics
- Azure Front Door / Application Gateway
- Azure Storage for persistent mounts

## Summary

Azure App Service Containers empowers developers to deploy, scale, and manage containerized web applications in a managed environment while abstracting infrastructure complexity.

## References

[2]: https://learn.microsoft.com/en-us/azure/app-service/quickstart-custom-container
[3]: https://learn.microsoft.com/en-us/azure/app-service/overview-sidecar
[4]: https://learn.microsoft.com/en-us/azure/well-architected/service-guides/azure-container-apps
[5]: https://stackoverflow.com/questions/65716530/azure-app-service-using-containers-when-is-the-container-updated
[7]: https://hals.app/blog/azure-app-service-container-volume-mounts/