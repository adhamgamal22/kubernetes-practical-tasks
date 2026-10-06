<div align="center">

# ☸️ Kubernetes Tasks

**Hands-on Kubernetes exercises: from first Pod to exposed, scalable applications**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![Minikube](https://img.shields.io/badge/Minikube-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![kubectl](https://img.shields.io/badge/kubectl-326CE5?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

---

## 📖 About

This repository contains my hands-on Kubernetes tasks and practice exercises. The goal is to build solid fundamentals by **deploying, managing, scaling, and exposing containerized applications** on a real cluster.

## 🎯 Topics Covered

| Icon | Topic | What I Practiced |
|------|-------|------------------|
| 📦 | **Pods** | Creating and inspecting the smallest deployable unit |
| 🚀 | **Deployments** | Declarative rollouts, updates, and rollbacks |
| 🌐 | **Services** | Exposing apps with ClusterIP, NodePort, and LoadBalancer |
| 📈 | **Replicas & Scaling** | Scaling workloads up and down manually |
| 🏷️ | **Labels & Selectors** | Organizing and targeting resources |
| 🔌 | **Networking** | Pod-to-pod and external communication |
| ⚙️ | **Configuration** | Managing app settings and environment variables |
| 📝 | **YAML Manifests** | Writing clean, reusable Kubernetes manifests |
| 🛠️ | **App Management** | Deploying and troubleshooting containerized apps |

## 🧰 Tools & Technologies

- ☸️ **Kubernetes**: container orchestration
- ⌨️ **kubectl**: cluster command-line tool
- 📄 **YAML**: resource definitions
- 🧊 **Minikube**: local Kubernetes cluster

## ⚡ Getting Started

### Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)

### Run a task

```bash
# 1. Clone the repository
git clone https://github.com/adhamgamal22/<repo-name>.git
cd <repo-name>

# 2. Start the local cluster
minikube start

# 3. Apply a manifest
kubectl apply -f <file>.yaml

# 4. Verify resources
kubectl get pods,deployments,services
```

## 🔍 Handy Commands

```bash
kubectl get all                         # List all resources
kubectl describe pod <pod-name>         # Inspect a pod
kubectl logs <pod-name>                 # View logs
kubectl scale deployment <name> --replicas=3   # Scale a deployment
kubectl rollout undo deployment <name>  # Roll back a deployment
kubectl delete -f <file>.yaml           # Clean up resources
minikube service <service-name>         # Open a service in the browser
```

## 🎓 Purpose

To practice **Kubernetes fundamentals** and gain real hands-on experience with deploying, managing, and exposing containerized applications.

## 👤 Author

**Adham Gamal**
☕ Java Backend Developer | 🐳 DevOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adhamgamal74-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adhamgamal74)

---

<div align="center">

⭐ If you find this useful, consider giving the repo a star!

</div>
