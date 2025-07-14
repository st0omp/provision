# Machine Provisioning Automation

This repository contains my personal infrastructure-as-code setup to automate the provisioning, configuration, and maintenance of my development and production machines.

## 🛠️ Features

- Automated machine setup (packages, services, users)
- Reproducible and consistent environments
- Support for multiple operating systems (Ubuntu, Debian, Arch…)
- Dotfiles deployment and system personalization
- Secure SSH configuration and hardening
- Optional: Docker, Git, and development tools installation

## 🚀 Getting Started

### Requirements

- [Ansible](https://docs.ansible.com/)
- `ssh` access to the target machines
- (Optional) Terraform, Git, Docker, etc.

### Quick Start

```bash
# Clone the repository
git clone git@github.com:st0omp/provision.git
cd provision

# Run provisioning on a target host
ansible-playbook -i <your host file> playbooks-tools.yaml