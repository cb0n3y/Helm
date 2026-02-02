# Helm – Kubernetes Packaging Manager for Developers and DevOps

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![GitHub Repo Size](https://img.shields.io/github/repo-size/cb0n3y/helm)
![Last Commit](https://img.shields.io/github/last-commit/cb0n3y/helm)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cb0n3y/helm/ci.yml?label=CI%2FCD)
![Languages Count](https://img.shields.io/github/languages/count/cb0n3y/helm)

Welcome to **Helm – Kubernetes Packaging Manager for Developers and DevOps** 🚀
This repository is a **hands-on course and reference** for learning how to package, deploy, and manage Kubernetes applications using **Helm**.

---

## 🎯 Who this course is for

This course is ideal for:

- Kubernetes users who want **repeatable, versioned deployments**
- Developers deploying apps to Kubernetes
- DevOps / Platform Engineers managing environments at scale
- Anyone tired of copying YAML files between clusters 😉

**Basic Kubernetes knowledge is recommended**, but you don’t need prior Helm experience.

---

## 📦 What you’ll learn

By the end of this course, you will be able to:

- Understand **what Helm is** and how it works
- Create Helm charts from scratch
- Use:
  - `values.yaml`
  - templates
  - helpers (`_helpers.tpl`)
- Manage:
  - releases
  - upgrades
  - rollbacks
- Package and version applications
- Work with:
  - dependencies
  - environments (dev / staging / prod)
- Apply **Helm best practices** used in real production setups

---

## 🛠 Prerequisites

You’ll need:

- Kubernetes (local or remote)
  - Recommended: **minikube**, **kind**, or **k3s**
- `kubectl`
- `helm` (v3+)
- Basic YAML knowledge

---

## 📁 Repository Structure

```text
.
├── charts/          # Example Helm charts
├── examples/        # Hands-on examples
├── values/          # Values files for different environments
├── docs/            # Additional documentation
└── README.md
```

---

## 🚀 Getting Started

Clone the repository:
```bash
git clone https://github.com/cb0n3y/helm.git
cd helm
```

Verify Helm installation:
```bash
helm version
```

📚 Course Roadmap

- [ ] Helm fundamentals
- [ ] Helm in action
- [ ] Advanced Commands
- [ ] Create Charts
- [ ] Templates & values - Deep Dive
- [ ] Advanced Charts
- [ ] Repositories
- [ ] Chart Security
- [ ] Usecase
- [ ] Starters
- [ ] Plugins
