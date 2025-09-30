+++ 
draft = false
date = 2025-09-18T09:36:44-05:00
title = "Portfolio"
menu = "main"
sectionPagesMenu = 'main'
description = ""
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

# PROJECTS

## Scalable 2-Tier Web Application w/ Kubernetes, Docker, & MongoDB
[Github](https://github.com/DJENJNY/Wiz-Project)
-- 


## 3-Tier Web Application Deployment – Terraform + AWS
[Github](https://github.com/DJENJNY/3TierWeb)
- Provisioned a secure, scalable environment using public and private subnets, NAT, IGW, EC2, IAM, RDS with Terraform.
- Segmented application into web, app, and database layers for improved security and fault isolation.
- Configured security groups, IAM roles, and VPC networking to enforce least-privilege access.
- Used remote state management with Terraform to ensure consistent deployments.

## DevOps Lab: VM Environment with NGINX Monitoring Stack
[Github](https://github.com/DJENJNY/Vmenvir)
- Created a self-contained development environment using Vagrant, Docker, and modern observability tools.
- Provisioned two virtual machines using Vagrant to simulate a local DevOps setup.
- Used Docker Compose to deploy an NGINX web server with log and metric monitoring.
- Integrated Grafana Loki, Prometheus, and Alloy to collect and visualize NGINX container logs and performance metrics.
- Configured persistent volume storage for data durability across reboots.

## Kubernetes Cluster Setup – "The Hard Way" on Vagrant
[Github](https://github.com/DJENJNY/K8s-Bootstrap)
- Manually configured a production-like Kubernetes cluster
- Provisioned multi-node cluster using Vagrant, including dedicated controller and worker nodes.
- Set up PKI infrastructure to issue and manage TLS certificates for secure API and node communication.
- Bootstrapped the Kubernetes API server, controller manager, scheduler, and kubelet processes manually.
- Configured internal cluster networking, including static routes and CoreDNS setup.