# Project: **Social Isolation Prediction**

## 📘 Introduction

The development of the framework consists of 3 parts: RADARBASE which can be found at the following link: https://github.com/ecariel/RADAR-kubernetes, the prediction of social isolation present in this repository and the visualization which is done using Elasticsearch and Kibana.

## 🛠️ Use monitoring predictions

1. Image your-user/modelos-image:latest: Build this image from the models-image/ directory:

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
