---
title: "Automated Kubernetes Cluster Provisioning"
excerpt: "Deploying secure, high-availability Kubernetes clusters using Terraform, Ansible, and kubeadm."
header:
  overlay_image: /assets/images/projects/k8s-provisioning.jpg
  caption: "Automating K8s with Terraform & Ansible"
tech_stack: ["Terraform", "Ansible", "Kubernetes", "AWS"]
date: 2024-08-12
---

## Overview
Provisioned and configured HA Kubernetes clusters across multiple environments with **Terraform**, **Ansible**, and **kubeadm**, reducing deployment time from hours to under 20 minutes.

## Key Features
- Automated **VPC** and **security group** creation via Terraform.
- **Immutable** node images built with Packer.
- Configured **RBAC**, **TLS**, and **etcd encryption**.
- Integrated CI/CD with GitHub Actions for continuous delivery.

## Outcomes
- Reduced provisioning errors by **>90%**.
- Improved environment consistency across dev, staging, and prod.
- Increased developer confidence through automated validation steps.

[🔗 View Source on GitHub](https://github.com/Edmund-Research/k8s-provisioning)
