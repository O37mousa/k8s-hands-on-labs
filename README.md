# Kubernetes 5-Lab

This course covers hands-on labs (`labs`) to master Kubernetes (`k8s`). Each lab includes a YAML configuration file.

## 📂 Course Structure

### **Lab 1:**
- Setting Up Minikube
- Deploying Your First Pod
- Working with ReplicaSets
- Creating Deployments

### **Lab 2:**
- Default Limit Range
- Limits and Requests
- Node Affinity
- Node Selector
- Resource Quota
- Taints and Tolerations
- Namespaces
- Running a Java App from Docker Hub in a Pod

### **Lab 3:**
- External Web Service (NodePort)
- Internal Web Test (ClusterIP)
- Testing Two Applications with Services
- DaemonSet
- Theoretical Questions and Solutions

### **Lab 4:**
- Persistent Volume (PV) and Persistent Volume Claim (PVC)
- Environment Variables
- ConfigMap
- Secret with MySQL
- Theoretical Questions and Solutions
- Init Container
- Multi-Container Pods

### **Lab 5:**
- **Exploring `etcd`:**
    - Saving an `etcd` Snapshot
    - Examining `etcd` Data Directory
- **Working with Ingress:**
    - Deploying a Basic Ingress
- **Exploring Gateway API:**
    - Deploying Gateway API Resources
- **Horizontal Pod Autoscaling (HPA):**
    - Implementing Horizontal Pod Autoscaling
- **Monitoring with Metrics Server & Vertical Pod Autoscaling (VPA):**
    - Installing Metrics Server
    - Implementing Vertical Pod Autoscaling

## **Setting Up Minikube to Start**
```sh
minikube start
```

