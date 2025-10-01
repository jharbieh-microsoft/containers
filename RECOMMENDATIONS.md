# Container Platform Recommendations

Use the following guidance to choose a container platform based on environment and workload characteristics.

- **AKS Edge Essentials** — Best for disconnected or resource‑constrained environments where lightweight, edge-optimized Kubernetes is required.
- **AKS Automatic** — Ideal for cloud‑native workloads where simplicity and fast provisioning are priorities.
- **AKS Standard** — Use when you need full control, customization, and advanced cluster configuration.
- **ACI (Azure Container Instances)** — Good for simple, ephemeral workloads or quick testing of containers without managing orchestration.
- **ACA (Azure Container Apps)** — Recommended for microservices when you want a lightweight, serverless, and scalable environment with managed orchestration.
- **Azure App Service Containers** — Use for fully managed container-based web app hosting focused on rapid development with minimal infrastructure management.

Notes:
- Consider operational constraints (connectivity, scale, SLA) and developer workflows when choosing.
- For production-grade Kubernetes on Azure, AKS Standard typically offers the most flexibility; for ephemeral tasks prefer ACI; for serverless microservices prefer ACA.
