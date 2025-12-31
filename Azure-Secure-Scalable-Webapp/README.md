# Secure and Scalable Web Application on Azure

## 🎯 Objective
To design and deploy a secure and scalable web application on Microsoft Azure using Azure App Service, Virtual Network, and Network Security Groups.

---

## 🛠️ Azure Services Used
- Azure Resource Group
- Azure App Service
- App Service Plan (Basic B1)
- Azure Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)

---

## 🧱 Architecture Overview
The web application is hosted on Azure App Service and secured using Network Security Groups.  
The application is deployed within a Virtual Network to ensure controlled and secure network access.  
Manual scaling is enabled through the App Service Plan to support increased traffic.

---

## 🪜 Steps
1. Created a Resource Group to organize Azure resources
2. Created a Virtual Network and subnet
3. Created and configured a Network Security Group (NSG)
4. Attached the NSG to the subnet
5. Created an Azure App Service and App Service Plan
6. Enabled manual scaling using the Basic (B1) plan
7. Verified application accessibility via browser

---

## 🔐 Security Implementation
- Network Security Group used as a firewall
- Default inbound rules applied to deny unnecessary traffic
- Secure communication enforced within the virtual network

---

## 📈 Scalability
- App Service Plan upgraded to Basic (B1)
- Manual scale-out supported
- Improved availability through scalable infrastructure

---

## ✅ Output
- Web application successfully deployed on Azure App Service
- Application accessible via default Azure App Service URL
- Secure and scalable architecture verified

---

## 📸 Screenshots
Screenshots demonstrating application deployment, networking, security configuration, and scalability are included in the `screenshots` folder.

---
