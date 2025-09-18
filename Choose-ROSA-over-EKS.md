# Why Choose AWS Red Hat OpenShift Service (ROSA) Over Amazon EKS?

This document outlines the key reasons why customers might choose **AWS Red Hat OpenShift Service (ROSA)** over **Amazon EKS**.
(Answers from Amazon Q)
---

## Enterprise-Grade Features and Support

### 24/7 Red Hat SRE Support with 99.95% SLA
- ROSA provides **dedicated Red Hat Site Reliability Engineer (SRE) support** around the clock.
- Backed by **Red Hat's 99.95% uptime service-level agreement (SLA)**.
- **Joint support** from both AWS and Red Hat, offering enterprise-grade operational support.

### Fully Managed Operations
- Red Hat SRE handles **cluster installation, maintenance, and upgrades**.
- Reduces operational overhead compared to EKS, where customers manage more of the cluster lifecycle.

---

## Developer Experience and Productivity

### Built-in Developer Tools
- **Integrated developer productivity tools**, including:
  - Service Mesh
  - CodeReady Workspaces
  - Serverless capabilities
- **Rich web console** with an enhanced developer experience.
- **Built-in CI/CD capabilities** and image registry.

### OpenShift-Specific Features
- **Projects**: Enhanced namespaces with additional governance.
- **Routes**: Advanced ingress capabilities.
- **ImageStreams**: For container image management.
- **DeploymentConfigs**: With advanced deployment strategies.

---

## Security and Compliance

### Enhanced Security Model
- **Security Context Constraints (SCCs)**: Provide more granular security controls than standard Kubernetes.
- **Built-in role-based access control (RBAC)** with enterprise-grade features.
- **Integrated image scanning** and vulnerability assessments.
- **Red Hat's security-focused approach** with regular security updates.

---

## Existing OpenShift Investment

### Seamless Migration Path
- For organizations **already using Red Hat OpenShift on-premises**.
- **Familiar APIs, tools, and operational procedures**.
- **Consistent experience** across hybrid and multi-cloud deployments.
- Preserves **existing skills and training investments**.

---

## Enterprise Kubernetes Platform

### Comprehensive Platform Approach
- OpenShift is positioned as a **complete enterprise Kubernetes platform**, not just orchestration.
- Includes **monitoring, logging, and metrics** as integrated platform services.
- **More opinionated approach** that can reduce decision fatigue for enterprises.

---

## Hybrid and Multi-Cloud Strategy

### Consistent Experience Across Environments
- Enables applications to run **consistently across on-premises data centers and multiple cloud environments**.
- Better suited for organizations with **hybrid cloud strategies**.
- **Consistent operational model** regardless of deployment location.

---

## Simplified Billing and Licensing

### Single AWS Bill
- **Red Hat OpenShift licensing, billing, and support** are all handled directly through AWS.
- **Simplified procurement and billing processes**.
- No separate Red Hat licensing agreements needed.

---

## Specific Use Cases Where ROSA Excels

### Regulated Industries
- Enhanced security features may be preferred in **highly regulated environments**.
- More comprehensive **audit and compliance capabilities**.

### Large Enterprise Deployments
- Better suited for organizations requiring **extensive governance and policy management**.
- More comprehensive **multi-tenancy features**.

### Development Teams Preferring Opinionated Platforms
- Teams that prefer a **more complete, integrated platform** over assembling individual components.
- Organizations wanting to **minimize the number of technology decisions**.

---

## Trade-offs to Consider
While ROSA offers these advantages, it's important to note that it typically comes with:
- **Higher costs** compared to EKS.
- **Less flexibility** in some areas due to the more opinionated approach.
- **Dependency on Red Hat's roadmap and decisions**.

The choice between EKS and ROSA often comes down to whether an organization values the **additional enterprise features, support model, and integrated experience** that ROSA provides, versus the **cost savings and flexibility** that EKS offers.

---

## Sources
- [ROSA architecture - Red Hat OpenShift Service on AWS](https://example.com)
- [Red Hat OpenShift Service on AWS - Overview of Deployment Options on AWS](https://example.com)
- [Red Hat OpenShift on AWS - Telco Edge Workloads on Red Hat OpenShift - Wavelength and Local Zones](https://example.com)
- [What is Red Hat OpenShift Service on AWS? - Red Hat OpenShift Service on AWS](https://example.com)
- [Migrate your container workloads from Azure Red Hat OpenShift (ARO) to Red Hat OpenShift Service on AWS (ROSA) - AWS Prescriptive Guidance](https://example.com)
