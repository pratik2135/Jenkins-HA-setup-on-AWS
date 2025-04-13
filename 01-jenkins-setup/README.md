## Project Course

**Detailed Video/Walkthrough Course (Free):** [techiescamp.com/courses/deploying-jenkins-aws/](https://techiescamp.com/p/project-jenkins-ha-setup-on-aws-terraform-ansible-packer)

## Setup Architecture 

![jenkins-ha](https://user-images.githubusercontent.com/106984297/226690774-66731923-a2cd-45cc-b387-c959e5b713c1.png)


## Project Documentation.

Refer [Jenkins Setup Using AWS Autoscaling Group](https://devopscube.com/jenkins-autoscaling-setup/) for the entire setup walkthrough.
# 🧪 Jenkins HA Setup on AWS (Adapted for GitHub Codespaces)

## 📌 About This Fork

This fork of the original Jenkins HA project has been modified to run effectively within **GitHub Codespaces**. It is tailored for learners or DevOps practitioners looking to simulate infrastructure scenarios in a lightweight, cloud IDE environment.

While not a full production-grade deployment, it replicates common DevOps challenges in infrastructure automation using Jenkins, Packer, Terraform, and Ansible.

## 🔄 Key Enhancements in This Fork

- Fixed broken Packer AMI configurations for Jenkins Controller/Agent setup
- Modified Ansible playbooks to resolve dependency and path-related issues
- Improved Terraform scripts for smoother resource provisioning in AWS
- Added support for remote EFS setup within the constrained Codespaces environment
- Added logs and error snapshots for educational purposes

## 🧰 Stack Used

- Jenkins (HA simulated)
- AWS (via Terraform)
- Packer for AMI creation
- Ansible for provisioning
- GitHub Codespaces as the development environment

> **Note:** This README is customized for this fork. It is intended for educational purposes

---

## 📊 Architecture Diagram

![Architecture Diagram](./architecture.png)

---

## 🧠 Learnings & Real-World Relevance

Although implemented in a sandbox environment, the project involved hands-on experience with real DevOps tools, debugging common infrastructure issues, and adapting automation scripts under practical constraints.
