# Azure: Zero to Expert

A structured, hands-on repository covering Microsoft Azure cloud architecture from foundational core concepts to advanced enterprise-grade solutions, with a strong focus on `.NET` workloads and modern DevOps practices.

## Module Roadmap

### Phase 1: Core Cloud Foundations & Compute (`01` – `05`)
| # | Module | Key Topics (.NET & Azure Architecture Focus) |
| :--- | :--- | :--- |
| [01](./01-azure-foundations-and-rbac/README.md) | Azure Foundations & RBAC | Subscriptions, Management Groups, Resource Groups, Role-Based Access Control (RBAC), Azure Policy & Initiatives |
| [02](./02-infrastructure-as-code-bicep/README.md) | Infrastructure as Code with Bicep | Declarative ARM/Bicep templates, modular architectures, parameters, outputs, and `what-if` deployment validation |
| [03](./03-terraform-on-azure/README.md) | Terraform on Azure | HashiCorp HCL, AzureRM provider, remote state management in Azure Blob Storage, and state locking |
| [04](./04-virtual-machines-and-vmss/README.md) | Virtual Machines & Scale Sets | Linux/Windows VM hardening, disk encryption, availability sets, fault/update domains, and auto-scaling VMSS |
| [05](./05-app-service-plans-and-web-apps/README.md) | App Service Plans & Web Apps | Compute tier selection (Basic vs. Premium), Linux/Windows runtimes, deployment slots, and custom TLS/SSL |

---

### Phase 2: Networking, Identity & Security (`06` – `10`)
| # | Module | Key Topics (.NET & Azure Architecture Focus) |
| :--- | :--- | :--- |
| [06](./06-virtual-networks-and-connectivity/README.md) | Virtual Networks & Connectivity | VNets, subnets, Network Security Groups (NSGs), VNet peering, Azure Bastion, and Site-to-Site VPN gateways |
| [07](./07-entra-id-and-app-registrations/README.md) | Microsoft Entra ID & App Registrations | Users, groups, enterprise applications, app registrations, secret management, and OAuth2/OpenID Connect flows |
| [08](./08-managed-identities-and-oidc/README.md) | Managed Identities & OIDC | System-assigned vs. user-assigned managed identities, and passwordless **Workload Identity Federation (OIDC)** |
| [09](./09-azure-key-vault-and-secrets/README.md) | Azure Key Vault & Secrets | Key Vault access policies, Azure RBAC for Key Vault, secret rotation, certificates, and app configuration integration |
| [10](./10-private-link-endpoints-and-firewalls/README.md) | Private Link, Endpoints & Firewalls | Securing PaaS services (Azure SQL, ACR, Storage) behind private IP endpoints, and Azure Firewall configuration |

---

### Phase 3: Container Platforms & Orchestration (`11` – `15`)
| # | Module | Key Topics (.NET & Azure Architecture Focus) |
| :--- | :--- | :--- |
| [11](./11-azure-container-registry/README.md) | Azure Container Registry (ACR) | Private container registries, multi-stage Dockerfile optimization for .NET, image tagging, and vulnerability scanning |
| [12](./12-azure-container-apps/README.md) | Azure Container Apps (ACA) | Serverless microservices, KEDA-based event-driven scaling (scale-to-zero), internal ingress, and Dapr integration |
| [13](./13-aks-cluster-architecture/README.md) | AKS Cluster Architecture | AKS cluster architecture, node pools, Azure CNI vs. Kubenet, Azure RBAC, and network policies |
| [14](./14-kubernetes-workloads-and-helm/README.md) | Kubernetes Workloads & Helm | Deployments, Services, Ingress controllers, Helm charts (`values-dev.yaml` vs `values-prod.yaml`), and secrets |
| [15](./15-container-reliability-and-probes/README.md) | Container Reliability & Probes | Configuring liveness, readiness, and startup probes for .NET 8 Web APIs to achieve zero-downtime rollouts |

---

### Phase 4: Enterprise Data, Governance & Capstone (`16` – `20`)
| # | Module | Key Topics (.NET & Azure Architecture Focus) |
| :--- | :--- | :--- |
| [16](./16-azure-sql-database-and-ha/README.md) | Azure SQL Database & High Availability | DTU vs. vCore models, active geo-replication, serverless pools, performance tuning, and automated backups |
| [17](./17-database-cicd-efcore-dacpac/README.md) | Database CI/CD & Migrations | Automating schema changes via **EF Core Migration Bundles (`efbundle`)** and SQL `.dacpac` deployment tasks |
| [18](./18-cosmos-db-and-storage-accounts/README.md) | Cosmos DB & Storage Accounts | Cosmos DB partition keys/consistency levels, and Azure Blob storage tiers (Hot/Cool/Archive) with lifecycle management |
| [19](./19-monitoring-insights-and-kql/README.md) | Monitoring, App Insights & KQL | App Insights telemetry for .NET, Log Analytics workspaces, custom metrics, alerts, and Kusto Query Language (KQL) |
| [20](./20-waf-and-enterprise-capstone/README.md) | WAF & Enterprise Capstone | Well-Architected Framework (WAF) 5 pillars, disaster recovery, and end-to-end multi-region Azure architecture |

---

## Tech Stack Covered
- **Cloud Platform:** Microsoft Azure (Compute, Networking, Containers, Databases, Identity, Security)
- **Application Stack:** .NET 8 (C#, ASP.NET Core Web API, Entity Framework Core) & SPA Frontend (Angular)
- **Infrastructure & DevOps Tools:** Azure Bicep, Terraform, Docker, Kubernetes, Helm, Azure DevOps Pipelines
- **Security & Observability:** Microsoft Entra ID, Azure Key Vault, Application Insights, Log Analytics
