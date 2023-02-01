---

layout: col-sidebar
title: OWASP Cloud Tenant Isolation
tags: builders defenders
level: 2
type: documentation
pitch: A guide for mitigating cross-tenant vulnerabilities in cloud application development

---

## Overview

Cross-tenant vulnerabilities are a new type of security risk that is characteristic of cloud-based applications. Such bugs can enable malicious tenants to break security boundaries, escape tenant isolation and access other tenants' data. The goal of this project is to create highly practical guidance for cloud developers to manage the risk of isolation escape by ensuring proper implementation of strong security boundaries, and thereby mitigate potential cross-tenant vulnerabilities in their SaaS/PaaS applications.

## Description

The goals of this project:
1. Create a list of common security mistakes in PaaS and SaaS solutions which could enable cross-tenant vulnerabilities, such as misconfigured containers, overly permissive firewall rules, lack of data hygiene, etc.
2. Write best practices specific to each major cloud provider (AWS, Azure and GCP) to help developers avoid making such mistakes in their application architecture.
3. Develop example architecture diagrams and Terraform files representing secure applications which implement strong mitigations against cross-tenant vulnerabilities.
