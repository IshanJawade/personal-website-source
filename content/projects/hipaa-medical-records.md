---
title: "HIPAA-Compliant Medical Records System"
year: 2024
date: 2024-06-01
category: "Health / Full-stack"
summary: "Patient-controlled access to encrypted medical records — React + Node/Express + PostgreSQL with AES-256-GCM encryption, JWT role-based auth, and a load-balanced Docker Compose stack."
---

Built a hospital-grade records system where patients own their data: medical professionals can only view records after a patient explicitly grants access, and patients can revoke it or set an expiry at any time.

- Implemented role-based workflows for patients, medical professionals, and admins — registration with admin approval, access requests, grant/decline with expiry, and record download.
- Encrypted record payloads at rest with AES-256-GCM, hashed passwords with bcrypt, and protected all sensitive endpoints with JWT role claims; every query is parameterized against SQL injection.
- Shipped a production-style Docker Compose stack with an Nginx reverse proxy load-balancing three frontend and two backend replicas plus managed PostgreSQL, with one-command migrations and seeding.

[View on GitHub →](https://github.com/IshanJawade/med-secure-project)
