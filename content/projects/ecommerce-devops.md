---
title: "E-Commerce Platform with DevOps Automation"
year: 2025
date: 2025-08-01
category: "Backend / DevOps"
summary: "Spring Boot microservices (catalog, cart, orders, users) with Jenkins CI/CD, deployed to AWS EKS behind CloudFront."
---

Built a microservice e-commerce platform designed for fault isolation and independent scaling of each service.

- Implemented catalog, cart, orders, and user services on Spring Boot + PostgreSQL with per-service schemas, fronted by a React UI over REST APIs.
- Automated end-to-end CI/CD on Jenkins + Docker with multi-stage builds and automated test gates, reducing releases to a single merge.
- Deployed to AWS EKS with Kubernetes and served through CloudFront CDN.
