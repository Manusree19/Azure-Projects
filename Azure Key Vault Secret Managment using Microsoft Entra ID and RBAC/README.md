# Azure Key Vault Secret Management Using Microsoft Entra ID and RBAC

## 🎯 Objective
To design and implement secure secret management on Microsoft Azure using Azure Key Vault integrated with Microsoft Entra ID and Role-Based Access Control (RBAC), ensuring controlled and secure access to sensitive information such as passwords and application secrets.

---

## 🛠️ Azure Services Used

- Azure Resource Group  
- Azure Key Vault  
- Microsoft Entra ID  
- Azure Role-Based Access Control (RBAC)  
- Azure Identity and Access Management (IAM)  

---

## 🧱 Architecture Overview

Azure Key Vault is used to securely store sensitive data such as passwords and application secrets.

Access to secrets is controlled using Microsoft Entra ID identities and RBAC roles, ensuring that only authorized users can access sensitive information.

This architecture provides centralized secret management, enhanced security, and secure access control without exposing secrets in application code.

---

## 🪜 Steps

- Created a Resource Group to organize Azure resources  
- Created an Azure Key Vault using Standard pricing tier  
- Configured Key Vault security and encryption settings  
- Created a secret named `db-password` in Azure Key Vault  
- Assigned **Key Vault Secrets User** role to authorized user using RBAC  
- Verified secret creation and secure access through Azure Portal  

---

## 🔐 Security Implementation

- Secrets securely stored using Azure-managed encryption  
- Access controlled using Microsoft Entra ID authentication  
- RBAC roles implemented to restrict unauthorized access  
- No sensitive data exposed publicly  
- Azure-managed infrastructure ensures secure secret storage  

---

## 📈 Scalability

- Azure Key Vault automatically scales based on usage  
- Supports enterprise-level applications and automation workflows  
- Can integrate with Azure services, DevOps tools, and applications  

---

## ✅ Output

- Azure Key Vault successfully deployed  
- Secret securely stored and managed  
- RBAC access control successfully implemented  
- Secure secret management verified  

---

## 📸 Screenshots

Screenshots included in the `screenshots` folder demonstrate:

- Azure Key Vault overview page  
- Secret creation and configuration  
- RBAC role assignment in Access Control (IAM)  
- Secret successfully stored in Key Vault  

---

## 📚 Key Learning

- Learned secure secret management using Azure Key Vault  
- Implemented access control using Microsoft Entra ID and RBAC  
- Understood cloud security best practices for managing sensitive information  
- Gained hands-on experience with Azure IAM and security services  

---

