# Kubernetes Security Testing using DVWA

## Project Overview
This project focuses on hands-on Kubernetes security testing by deploying a deliberately vulnerable web application (DVWA – Damn Vulnerable Web Application) on a Kubernetes cluster using Minikube. The objective is to simulate real-world web attacks in a containerized environment and analyze security risks in cloud-native systems.

---

## Implementation Summary

- Deployed DVWA on Kubernetes using custom YAML manifests
- Configured and managed a local Kubernetes cluster using Minikube
- Exposed the application using Kubernetes Services
- Performed security testing on a live containerized workload
- Analyzed runtime and networking security risks in Kubernetes

---

## Attack Vectors Demonstrated

The following real-world vulnerabilities were tested:

- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection

These attacks were executed against DVWA running inside Kubernetes to understand how application-layer vulnerabilities impact cloud-native deployments.

---

## Kubernetes Architecture

> Architecture diagram is included in this repository.

![Kubernetes Architecture](architecture.jpg)

---

## Tech Stack

- Kubernetes
- Minikube
- Docker
- DVWA (Damn Vulnerable Web Application)
- YAML
- kubectl
- Linux

---

## Repository Contents

- Kubernetes manifests for DVWA deployment
- Service and networking configuration files
- Architecture diagram
- Documentation and setup instructions

---

## Learning Outcomes

- Practical experience with Kubernetes deployments
- Understanding of containerized application security
- Exposure to cloud-native security risks
- Hands-on DevSecOps fundamentals
- Kubernetes networking and service management

---

## Disclaimer

This project uses intentionally vulnerable software for educational and testing purposes only.  
Do NOT deploy this setup in a production environment.

---

## Author

Satyam Tiwari  
GitHub: https://github.com/satyamtiwari06
