# 2048-game


Kubernetes End-to-End Project on EKS with ALB Ingress Controller
This repository demonstrates the deployment of a scalable, production-ready e-commerce application using Amazon Elastic Kubernetes Service (EKS) and the AWS Load Balancer Controller (ALB Ingress Controller). The project encompasses the full lifecycle—from provisioning the EKS cluster to deploying microservices and exposing them via an Application Load Balancer (ALB).

## Project Overview
This project guides you through setting up an EKS cluster and deploying a multi-tier e-commerce application with the following components:

Frontend: User interface for product browsing and cart management.

Backend: Business logic handling user authentication and order processing.

Database: Persistent storage for user data and transactions.

The AWS Load Balancer Controller integrates with Kubernetes Ingress resources to manage external HTTP/S traffic, providing secure and efficient routing to services within the cluster.
<img width="813" height="757" alt="image" src="https://github.com/user-attachments/assets/ddc0a09e-f110-4112-a99c-9903885c34c4" />


# Prerequisites

AWS CLI: Installed and configured with appropriate IAM permissions.

kubectl: Kubernetes command-line tool configured to interact with your EKS cluster.

eksctl: Utility for creating and managing EKS clusters.

Helm: Package manager for Kubernetes, used to install the AWS Load Balancer Controller.

IAM OIDC Provider: Set up for your EKS cluster to allow service account integration.

