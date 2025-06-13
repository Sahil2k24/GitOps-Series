# 🚀 Multi-Cluster Deployment using Argo CD

Managing applications across **multiple Kubernetes clusters** can become increasingly complex. In this project, I tackled that challenge by using **Argo CD** with a GitOps approach to automate and standardize deployments across environments.

---

## 🧭 Project Overview

This project demonstrates a **Hub-and-Spoke architecture** for centralized GitOps management of **three Amazon EKS clusters**:

* 🧪 Dev
* 🔍 QA
* 🚀 Prod

Using **Argo CD** deployed in the **Hub cluster**, I enabled secure, scalable, and automated management of applications across all Spoke clusters, with **Git as the single source of truth**.

---

## 🔍 Key Highlights

* ✅ Centralized Argo CD setup in a **Hub cluster**
* ✅ Secure access and authentication to **Spoke clusters**
* ✅ **Drift detection** and **self-healing** for application state
* ✅ **ApplicationSets** for declarative multi-cluster deployments
* ✅ Provisioning EKS clusters using `eksctl` and managing Argo CD with Helm

---

## 🧠 What I Learned

This project helped me explore and master:

* 🌐 GitOps workflows using Argo CD
* ⚙️ Argo CD internals, RBAC, and ApplicationSets
* 🛡️ Secure multi-cluster access patterns
* 🔁 Continuous delivery practices for Kubernetes
* 🧱 Infrastructure provisioning and Git-based automation

---

## 📂 Explore the Project

All configurations, manifests, and setup scripts are available in my GitHub repository:
🔗 **[GitOps-Series by Sahil2k24](https://github.com/Sahil2k24/GitOps-Series)**

---

## ✅ Technologies Used

* **Amazon EKS**
* **Argo CD**
* **Helm**
* **eksctl**
* **ApplicationSets**
* **GitOps**
* **Kubernetes**

---

## 💡 Why GitOps?

Using GitOps with Argo CD provides:

* Single source of truth for infrastructure and app configuration
* Automated, consistent deployments across environments
* Easy rollbacks and audit trails via Git history
* Improved collaboration between dev and ops teams

---

## 📬 Let’s Connect

If you're working with GitOps, multi-cluster deployments, or platform engineering, I’d love to connect and collaborate!

---

### 📌 Tags

`#GitOps` `#ArgoCD` `#Kubernetes` `#MultiCluster` `#DevOps` `#EKS` `#InfrastructureAsCode` `#Automation` `#CloudEngineering` `#PlatformEngineering`

---
