# NGO Website Hosting Using Azure Storage Static Website

## 🎯 Objective
To design and deploy a **static NGO website** on Microsoft Azure using **Azure Storage Static Website**, providing a cost-effective, scalable, and publicly accessible web solution for a non-profit organization.

---

## 🛠️ Azure Services Used
- Azure Resource Group  
- Azure Storage Account (StorageV2)  
- Azure Blob Storage  
- Azure Static Website  

---

## 🧱 Architecture Overview
The NGO website is hosted as a **static website** using **Azure Blob Storage**.  
Static website hosting is enabled within the storage account, allowing public access to HTML content without the need for server management.  
This architecture provides high availability, scalability, and minimal operational cost.

---

## 🪜 Steps
1. Created a **Resource Group** to organize project resources  
2. Created an **Azure Storage Account (General-purpose v2)**  
3. Enabled the **Static Website** feature  
4. Configured:
   - Index document: `index.html`  
   - Error document: `index.html`  
5. Uploaded the NGO website HTML file to the **$web container**  
6. Accessed the website using the **Primary Endpoint URL**  

---

## 🔐 Security Implementation
- Public read-only access enabled for static content  
- No backend services or databases exposed  
- Azure-managed infrastructure ensures secure content delivery  

---

## 📈 Scalability
- Azure Storage automatically scales to handle traffic  
- High availability without manual scaling  
- Suitable for small to large audiences  

---

## ✅ Output
- NGO static website successfully deployed on Azure  
- Website accessible via Azure Static Website URL  
- Cost-efficient and scalable hosting verified  

---

## 📸 Screenshots
Screenshots included in the `screenshots` folder demonstrate:
- Live NGO website output in browser  
- Static website configuration in Azure  
- `$web` container with uploaded HTML files  

---
