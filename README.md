# Azure Secure Landing Zone - Monolithic Architecture

## 📌 Project Overview

This project demonstrates the implementation of a secure and scalable Azure Landing Zone using Terraform.

The infrastructure is designed using a modular Terraform approach, where reusable Terraform modules are used to provision and manage Azure resources.

The main objective of this project is to create a standardized, secure, and automated Azure infrastructure that can be used as a foundation for deploying applications.

---

## 🏗️ Architecture

The project follows a Monolithic Landing Zone architecture.

The infrastructure includes:

- Azure Resource Groups
- Azure Virtual Network
- Azure Subnets
- Network Security Groups
- Public IP
- Virtual Machines
- Load Balancer
- Application Gateway
- Azure Bastion
- Azure Key Vault

---

## 📂 Project Structure

```text
.
├── environments/
│
├── modules/
│   ├── azurerm_application_gateway/
│   ├── azurerm_bastion/
│   ├── azurerm_key_vault/
│   ├── azurerm_load_balancer/
│   ├── azurerm_public_ip/
│   ├── azurerm_resource_group/
│   ├── azurerm_subnet/
│   ├── azurerm_virtual_machine/
│   └── azurerm_virtual_network/
│
├── .gitignore
└── README.md
