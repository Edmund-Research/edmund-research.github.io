---
title: "Attack Surface Reduction through Infrastructure as Code"
excerpt: "Building secure-by-design cloud environments using Terraform and policy-as-code frameworks."
header:
  overlay_image: /assets/images/projects/iac-hardening.jpg
  caption: "Embedding compliance and threat prevention at the IaC level"
tech_stack: ["Terraform", "Checkov", "OPA", "AWS Config", "GitHub Actions"]
---

## Problem Statement
Infrastructure teams often automate deployments but neglect security validation early in the process.  
Misconfigurations such as open ports, weak IAM policies, or public storage expose systems to breaches long before production.

## Approach
- Defined cloud infrastructure using **Terraform**, focusing on AWS EC2, S3, and IAM.  
- Integrated **Checkov** and **Open Policy Agent (OPA)** to enforce compliance baselines before deployment.  
- Added **GitHub Actions** workflows to scan IaC for vulnerabilities on every pull request.  
- Configured **AWS Config** to continuously monitor drift from compliance policies.

## Tools Used
Terraform, Checkov, OPA, AWS Config, GitHub Actions.

## Key Lessons Learned
- Security must begin in the infrastructure definition phase.  
- Policy-as-code enables consistent enforcement across teams.  
- Automated compliance reduces manual review cycles and risk of configuration drift.
