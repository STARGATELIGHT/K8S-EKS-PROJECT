##### Kubernetes EKS Project

This repository contains an **AWS EKS (Elastic Kubernetes Service) deployment**, showcasing how to set up a **highly available, scalable, and secure Kubernetes cluster** on AWS. It includes configurations for **IAM roles, networking (VPC, subnets), load balancing, monitoring, and CI/CD integration**.

## Features

- **Automated Kubernetes Cluster Deployment** on AWS EKS  
- **Infrastructure as Code (IaC)** using **Terraform**  
- **CI/CD Pipeline** integration for automated deployments  
- **Networking & Security** with **VPC, Security Groups, IAM Roles**  
- **Cluster Autoscaling** for optimized resource utilization  
- **Monitoring & Logging** with **Prometheus, Grafana, and AWS CloudWatch**  
- **Deployment of Microservices** using Kubernetes manifests  
- **Ingress Controller & Load Balancer** for external access  

## Prerequisites

Before deploying the project, ensure you have:

- **AWS CLI** installed (`aws --version`)  
- **Kubectl** installed (`kubectl version --client`)  
- **Terraform** installed (`terraform --version`)  
- **Helm** installed (`helm version`)  
- **IAM User** with necessary permissions (`AdministratorAccess` or fine-grained permissions)  
- **Docker** installed (`docker --version`)  

## 🚀 Setup Instructions

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/STARGATELIGHT/K8S-EKS-PROJECT.git
cd K8S-EKS-PROJECT
