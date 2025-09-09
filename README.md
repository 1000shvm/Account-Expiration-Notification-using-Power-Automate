# Account Expiration Notification using Power Automate

This repository contains documentation (`Account_Expiration_Notification.docx`) that explains how to **send account expiration notifications to contractors** using **Power Automate**.

## 📄 Document Overview
The provided Word document includes:
- **Purpose**: Automating email notifications when contractor accounts are about to expire.  
- **Plan**:  
  - A scheduled Power Automate flow is created to run daily or weekly.  
  - Contractor details are imported through a file.  
  - Variables and conditions are used to check account expiration.  
  - If the extension attribute indicates less than 20 days remaining, an email notification is sent.  
- **Key Notes**:  
  - Flow runs under a service account (e.g., `###-FlowAdmin@domain.onmicrosoft.com`).  
  - Uses the **HTTP function** (a Power Automate premium feature).  

## 🛠️ Requirements
- **Microsoft 365 tenant with Power Automate**  
- **Premium Power Automate license** (for HTTP function)  
- **Contractor details file** (for importing into the flow)  
- **Service account** to run the flow  

## 🚀 Usage
1. Open the `Account_Expiration_Notification.docx` file in this repository.  
2. Follow the guide to:  
   - Create a scheduled flow in Power Automate (weekly/daily).  
   - Import contractor account details.  
   - Initialize variables and apply conditions.  
   - Configure email alerts for accounts with <20 days until expiration.  

## 📂 Repository Structure
.
├── Account_Expiration_Notification.docx
└── README.md


## 📧 Support
If you encounter issues while setting up, refer to Microsoft Docs:  
- [Power Automate Documentation](https://learn.microsoft.com/power-automate/)  

---

✨ This repo serves as a **reference guide** for IT admins to proactively manage contractor account expirations.


## 📜 License
This project is licensed under the **MIT License**.
