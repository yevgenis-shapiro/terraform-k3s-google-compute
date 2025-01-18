![k3s-on-gcp](https://github.com/user-attachments/assets/fd973fb9-d423-4358-97b6-09a7ab4b6d88)

## Terraform GCP Module - K3S ( Kubernetes )   | ⭐⭐⭐
K3s is a lightweight Kubernetes distribution created by Rancher Labs, and it is fully certified by the Cloud Native Computing.K3s is highly available and production-ready. It has a very small binary size and very low resource requirements . Kubernetes-Native Platform for Edge , Internet of Things (IoT) , Continuous Integration (CI) , Embedded K8s , Air-Gapped Environments.


🚀  Key Features
```
✅ Lightweight : The binary containing the non-containerized components 
✅ Fast deployment : Single command to install and deploy K3s cluster or single machine 
✅ Simplified : Self-contained single binary package
✅ Easy to update : Reduced dependencies
✅ Easy to deploy remotely : Bootstrapped with manifests after K3s comes installed
✅ Great for resource-constrained environments : K3s is the better choice for IoT and edge computing. 
```


### Complements :
```
📃 Containerd / Dockerd Container Runtime
📃 Flannel Container Network Interface (CNI)
📃 CoreDNS Cluster DNS
📃 ServiceLB Load-Balancer Controller
📃 Local-path-provisioner Persistent Volume controller
```


🔨 External Datastore Integration :
```
# MySQL
# MariaDB
# PostgresSQL
# Cassandra
```

### Config

```
terraform plan -out tfplan.out
terraform apply tfplan.out
```

