# Kubernetes Security Testing using DVWA 🔐

## Project Overview
This project demonstrates **hands-on Kubernetes security testing** by deploying a deliberately vulnerable web application (**DVWA – Damn Vulnerable Web Application**) on a Kubernetes cluster using **Minikube**. The primary goal is to simulate real-world web attacks in a containerized environment and analyze security risks in **cloud-native systems**.

This project is designed for **learning, experimentation, and portfolio demonstration**.

---

## Key Highlights

- Deployed DVWA on Kubernetes using custom YAML manifests
- Set up and managed a local Kubernetes cluster using Minikube
- Exposed the application using Kubernetes Services
- Simulated real-world web attacks in a containerized setup
- Analyzed Kubernetes networking and runtime security risks

---

## Attack Vectors Demonstrated

The following vulnerabilities were successfully tested:

- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection

These attack scenarios help understand how traditional web vulnerabilities translate into serious risks in cloud-native deployments.

---

## Kubernetes Architecture

> The complete architecture diagram is included in this repository.

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

## Repository Includes

- Kubernetes manifests for DVWA deployment
- Service and networking configuration files
- Architecture diagram
- Documentation and setup references

---

## Learning Outcomes

- Practical experience with Kubernetes deployments
- Exposure to cloud-native security challenges
- Understanding of containerized application security
- Hands-on DevSecOps fundamentals
- Kubernetes networking and service management

---

## Disclaimer

This project uses intentionally vulnerable software for **educational and testing purposes only**.  
Do **NOT** deploy this setup in a production environment.

---

## Author

**Satyam Tiwari**  
GitHub: https://github.com/satyamtiwari06

