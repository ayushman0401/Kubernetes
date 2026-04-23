# Kubernetes

## Part 1 - Basics

[Go to Basics →](./Basics/README.md)

| Topic | What's covered |
|---|---|
| What is Kubernetes | Container orchestration, declarative infrastructure, why it exists |
| Cluster Architecture | Master node, control plane components (API server, etcd, scheduler, controller-manager) |
| Worker Nodes | kubelet, kube-proxy, container runtime, CRI |
| Pods | Smallest deployable unit, resource sharing, network and storage within a pod |
| Creating a Cluster | kind setup - single node and multi-node, managing contexts |
| Creating a Pod | kubectl run, manifest files, pod lifecycle |
| Deployments | ReplicaSet, Deployment resource, rollouts, rollbacks, internal flow |
| Services | ClusterIP, NodePort, LoadBalancer - when and how to use each |

---

## Part 2 - Advanced

[Go to Advanced →](./Advanced/README-advanced.md)

| Topic | What's covered |
|---|---|
| Downsides of Services | Why LoadBalancer-per-service breaks down at scale |
| Ingress | Ingress resource vs Ingress Controller, the split and why it exists |
| Namespaces | Logical cluster partitioning, scoped operations, default namespace behavior |
| Ingress Controllers | NGINX via Helm, path-based routing, rewrite-target annotation, Traefik comparison |
| Secrets & ConfigMaps | Non-sensitive config vs sensitive data, env var injection, mounting secrets as files |
| Volumes in Docker | Ephemeral storage, bind mounts, Docker-managed volume mounts |
| Volumes in Kubernetes | emptyDir, PersistentVolume, PersistentVolumeClaim, NFS setup, dynamic provisioning via StorageClasses |
| Horizontal Pod Autoscaler | cAdvisor, metrics-server, HPA control loop, scaling formula, resource requests and limits |
| Cluster Autoscaler | Node-level autoscaling, HPA + Cluster Autoscaler working together |