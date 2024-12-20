# Project: **Social Isolation Prediction**

## 📘 Introduction

The development of the framework consists of 3 parts: RADARBASE which can be found at the following link: https://github.com/ecariel/RADAR-kubernetes, the prediction of social isolation present in this repository and the visualization which is done using Elasticsearch and Kibana.

---

## 🎯 Objectives

1. **Automation:** Simplify the deployment and management of RADAR-base using Kubernetes.
2. **Scalability:** Ensure services can scale horizontally and vertically based on system demands.
3. **Security:** Implement and manage secrets and credentials in a centralized manner.
4. **Modularity:** Allow services to be easily interchangeable or configurable.
5. **Monitoring and analysis:** Integrate tools like Elasticsearch and Kibana for real-time data monitoring.

---

## 🛠️ Use monitoring predictions

   ```shell
   cd modelos-image/
   docker build -t tu-usuario/modelos-image:latest .
   docker push tu-usuario/modelos-image:latest
   cd ..
   ```

### **Prerequisites**

Before you begin, make sure you have the following installed and configured:

1. **Kubernetes Cluster**
   - A running Kubernetes cluster.
   - `kubectl` configured to interact with the cluster.
2. **Helm**
   - A package manager for Kubernetes.
   - [Installation guide](https://helm.sh/docs/intro/install/)
3. **Git**
   - To clone the repository.
4. **Docker**
   - To build custom images, if needed.

### **Installation Steps**

1. **Clone the repository**
   ```bash
   git clone https://github.com/ecariel/RADAR-kubernetes.git
   cd RADAR-kubernetes
