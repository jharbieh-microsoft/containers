# Azure container platforms — summary & table of contents

This repository contains short reference documents for Azure container platforms as top-level files. Below is a concise summary and a linked table of contents that points to each file with a one-line description to help you find the right topic quickly.

## Quick summary

The `containers/` docs cover managed Kubernetes (AKS), AKS variants for automatic and edge scenarios, serverless container hosting (Azure Container Apps, Azure Container Instances), App Service for containerized web apps, Service Fabric for stateful microservices, and a comparison matrix that highlights trade-offs across these offerings.

## Table of contents

- [AKS.md](./AKS.md) — Azure Kubernetes Service (AKS): Microsoft’s managed Kubernetes service for deploying, managing, and scaling containerized applications with built-in integration to Azure services.
- [AKS_AUTOMATIC.md](./AKS_AUTOMATIC.md) — AKS Automatic: opinionated, fully managed AKS mode with production-ready defaults and automated node lifecycle management.
- [AKS_EDGE_ESSENTIALS.md](./AKS_EDGE_ESSENTIALS.md) — AKS Edge Essentials: lightweight on‑prem/edge AKS distribution (K8s/K3s) managed via Azure Arc for IoT and edge scenarios.
- [APPSERVICE_WEBAPP_CONTAINERS.md](./APPSERVICE_WEBAPP_CONTAINERS.md) — Web App for Containers: run custom Docker web apps on Azure App Service (PaaS) with sidecar support and integrated monitoring.
- [CONTAINERS.md](./CONTAINERS.md) — Comparison matrix: consolidated table comparing AKS Edge, Container Apps, Container Instances, Service Fabric, and Web App for Containers.
- [CONTAINER_APPS.md](./CONTAINER_APPS.md) — Azure Container Apps: serverless, event-driven, microservices platform with scale-to-zero and deep Azure integration.
- [CONTAINER_INSTANCES.md](./CONTAINER_INSTANCES.md) — Azure Container Instances (ACI): fast, VM‑less containers for short-lived or burst workloads with per-second billing.
- [SERVICE_FABRIC.md](./SERVICE_FABRIC.md) — Azure Service Fabric: distributed systems platform for building scalable, reliable stateful and stateless microservices.

## How to use

- Open any file for a focused overview, core concepts, features, and common use cases (for example, `AKS.md`).
- Use the comparison in `CONTAINERS.md` when deciding which Azure container option best fits your workload (edge vs serverless vs managed K8s vs stateful microservices).

---

Maintained as a navigational landing page for the `containers/` documentation set.
