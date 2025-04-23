# DevOps Project Collection

This repository contains a series of DevOps-focused exercises, each addressing different tools and workflows in the ecosystem — including Ansible, Jenkins, Vault, Docker, and AWS EC2.

---

## Exercises Overview

### Ex1 - OpenVPN Server (Ansible Role)
An Ansible role to set up an OpenVPN server for secure communication.

### Ex2 - EC2 Nameserver Boot Update
Cloud-init script that updates the EC2 instance’s nameserver to match its IP on boot.

### Ex3 - Nginx Deployment via Jenkins & Consul
A Jenkins pipeline that deploys an Nginx server on a port dynamically delivered by Consul.

### Ex4 - Vault-Jenkins AWS Credential Integration
Integration of HashiCorp Vault with Jenkins for secure storage and use of AWS credentials — demonstrated via a pipeline that fetches EC2 instance data.

### Ex5 - Artifactory Installation with Ansible
Automated installation of JFrog Artifactory using an Ansible playbook.

### Ex5 (alt) - Docker Compose for Artifactory
Docker-based deployment of Artifactory using a `docker-compose.yml` file.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/devops-project.git
cd devops-project

