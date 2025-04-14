# 🔐 Azure Managed Identity: VM Accessing Blob Storage Securely

This mini-project demonstrates how to use **Azure Managed Identity** to securely access a blob stored in Azure Storage Account from an Azure Virtual Machine — without using any secrets or connection strings.

## 🚀 What I Did

- Created a Storage Account & uploaded an HTML blob
- Set up a Virtual Machine and enabled **System-assigned Managed Identity**
- Used **RBAC (IAM)** to assign `Storage Blob Data Reader` role to the VM's identity
- Logged into the VM and used **access tokens & shell scripting** to fetch the blob
- All access done securely without any keys

## 📸 Screenshots

- IAM Role Assignment  
- Terminal blob fetch  
- Personal handwritten setup notes  

## 📂 Files Included

- `script.sh` → Script run inside the VM to fetch blob
- `arm-template.json` → Exported template of the Azure resource group
- `screenshots/` → All supporting images

## 📚 Concepts Used

- Azure Managed Identity (System-assigned)
- IAM & Role-Based Access Control (RBAC)
- Azure CLI & Access Tokens
- Secure access without secrets

---

