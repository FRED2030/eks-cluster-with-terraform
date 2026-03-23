# AWS EKS Cluster Deployment with Terraform
# This repository helps you provision a cluster in AWS EKS using Terraform
## 📌 Overview
This project demonstrates how to provision a fully functional Kubernetes cluster on AWS using Terraform. It showcases Infrastructure as Code (IaC) principles to automate the deployment and management of cloud infrastructure.

## 🚀 Technologies Used
- Terraform (Infrastructure as Code)
- AWS EKS (Elastic Kubernetes Service)
- AWS VPC (Networking)
- Kubernetes
- AWS CLI

## 🛠️ Key Features
- Automated provisioning of AWS VPC and networking components
- Deployment of EKS cluster using Terraform modules
- Configuration of worker nodes for container workloads
- Scalable and repeatable infrastructure setup

## 📂 Project Structure

## ⚙️ How It Works
1. Terraform initializes the AWS provider
2. VPC and networking resources are created
3. EKS cluster is provisioned
4. Worker nodes are attached to the cluster
5. Kubernetes is configured for deployment

## ▶️ How to Run
```bash
terraform init
terraform plan
terraform apply
