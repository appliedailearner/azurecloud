# 10 - Core Services (Azure Building Blocks)

**For everyone: hands-on learning of essential Azure services.**

---

## 💻 What's In This Folder?

This folder covers the **core Azure services** that power most cloud solutions. Each subfolder focuses on one domain.

## 📂 Structure

```
10-core-services/
  README.md
  compute/            # VMs, App Service, Functions, Container Apps
  networking/         # VNets, NSG, VPN, Load Balancer, Application Gateway
  storage/            # Blob, Files, Queues, Cosmos DB
  identity/           # Entra ID, RBAC, access management
```

## 🎯 Learning Paths by Role

### 🎓 Students

1. **Start with Compute** (`compute/`)
   - Azure App Service (easy first app)
   - Azure Functions (serverless)
   - Pick 1-2 and build a project

2. **Add Storage** (`storage/`)
   - Azure Blob Storage (files, images)
   - Azure Queues (async messaging)
   - Integrate with your compute project

3. **Learn Networking Basics** (`networking/`)
   - Virtual Networks (VNets)
   - Network Security Groups (NSG)
   - Connect your services

4. **Identity Later** (`identity/`)
   - RBAC essentials
   - Entra ID basics

### 💼 Professionals

**Focus on your domain:**

- **Backend/DevOps:** Compute + Networking (App Service, VMs, AKS)
- **Full-Stack/Web:** Compute + Storage (App Service, Functions, Blob)
- **Data Engineer:** Storage + advanced networking (Synapse, Cosmos DB)
- **Security:** Identity + Networking (Entra, RBAC, NSG, Firewall)

## 🚀 Quick Start

1. Choose your focus: **Compute**, **Storage**, or **Networking**
2. Read the lesson file in that subfolder (concepts)
3. Do 2-3 hands-on labs
4. Build a mini-project combining 2 services
5. Expand to other domains as needed

## 📚 Subfolder Summaries

### **compute/** - Computing Power
- **Azure App Service** - Host web apps, APIs, static sites
- **Azure Functions** - Serverless, event-driven code execution
- **Virtual Machines** - Full OS control, lift-and-shift
- **Container Apps** - Modern containerized workloads

### **networking/** - Connectivity & Security
- **VNets & Subnets** - Isolate and organize resources
- **NSG (Network Security Groups)** - Firewall rules
- **VPN & ExpressRoute** - Hybrid on-prem connections
- **Load Balancer** - Distribute traffic

### **storage/** - Data at Rest
- **Blob Storage** - Files, images, backups
- **Azure Files** - Cloud file shares (SMB)
- **Queues** - Async messaging
- **Cosmos DB** - Globally distributed NoSQL database

### **identity/** - Access & Authentication
- **Entra ID (Azure AD)** - User and app identity
- **RBAC** - Who can do what
- **Service Principals** - App-to-app auth
- **Managed Identity** - Secure service-to-service

---

## ✅ Do First

- Pick ONE service and get deep (2-3 weeks)
- Build something real with it
- Connect it to at least one other service
- Use the exercises in Microsoft Learn as reference

## ❌ Don't Skip

- Networking is essential, even for beginners
- Identity/RBAC is critical for security (don't ignore!)
- Always clean up resources to avoid costs

---

**Next:** Choose a subfolder and open its README →
