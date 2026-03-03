# KubeScope

KubeScope is a lightweight Kubernetes operations IDE designed for DevOps engineers and platform teams.

It provides a fast and simple interface to inspect clusters, troubleshoot workloads, and perform operational tasks such as etcd maintenance directly from your desktop.

KubeScope connects to clusters using your kubeconfig and requires no agents or additional infrastructure.

---

## Features

### Kubernetes Cluster Exploration

• Explore clusters and namespaces  
• Inspect Kubernetes resources  
• View pod logs and resource details  
• Multi-cluster support via kubeconfig  

---

### Workload Troubleshooting

• Quickly identify problematic pods  
• Inspect logs and resource states  
• Monitor pod health and failures across namespaces  

---

### Workload Topology Visualization

KubeScope helps you understand how workloads are connected.

• Visualize relationships between pods and cluster resources  
• See connected volumes (PVC / PV)  
• View linked ConfigMaps and Secrets  
• Understand workload dependencies at a glance  

This makes troubleshooting and debugging much faster.

---

### RBAC Visibility

KubeScope provides a clear view of Kubernetes RBAC configuration.

• Visualize RoleBindings and ClusterRoleBindings  
• Map users, groups, and service accounts to their permissions  
• Quickly identify elevated privileges  

---

### etcd Maintenance Tools

KubeScope includes built-in utilities for etcd maintenance.

• etcd compact  
• etcd defragment  

These operations can be executed directly from the KubeScope interface.

---

### Operational Utilities

• Velero backup visibility  
• Cluster resource inspection  
• Kubernetes operational helpers  

---

## Why KubeScope?

Many Kubernetes tools focus primarily on application development workflows.

KubeScope focuses on **cluster operations, troubleshooting, and operational visibility**, helping DevOps engineers and SREs understand cluster state and resolve issues quickly.

---

## Architecture

KubeScope runs as a desktop application and connects directly to Kubernetes clusters using kubeconfig.

Optional operational components can be installed inside the cluster when additional functionality is required.

---

## Installation

Download the latest release:

https://github.com/proofops/kubescope/releases

Available builds:

• macOS  
• Linux  
• Windows  

KubeScope is distributed as a **single binary**.

No additional dependencies are required.

---

## Requirements

• Kubernetes cluster  
• kubeconfig access  

Optional:

• Velero (for backup visibility)

---

## Support the Project

KubeScope is free to use.

If it helps you manage Kubernetes clusters more efficiently, consider supporting the project.


---

## License

Copyright © ProofOps

KubeScope is proprietary software distributed as a free binary.

Redistribution or modification without permission is not allowed.

---

## Project Site

