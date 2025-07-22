# 🧵 HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

A Salesforce-based CRM solution tailored for the fashion industry to streamline customer relationships, inventory management, and automated workflows.

---

## 📌 Project Overview

**HandsMen Threads** is a dynamic fashion brand aiming to improve customer engagement and data management. This Salesforce implementation focuses on creating a centralized, intelligent CRM platform with automation and real-time insights.

---

## 🚩 Problem Statement

Challenges faced by the organization:
- Manual tracking of customer data and orders
- No automation for stock alerts or order processing
- No personalized loyalty management system
- Difficulty maintaining data consistency and communication

---

## ✅ Solution Highlights

- **Custom Objects**: Customers, Orders, Products, Inventory, Loyalty
- **Automated Order Confirmations**: Email alerts post-order creation
- **Dynamic Loyalty Program**: Based on customer purchase history
- **Proactive Stock Alerts**: Emails triggered when inventory < 5
- **Batch Apex**: Scheduled bulk updates at midnight for inventory and finance

---

## 🔨 Project Phases

### 📐 Phase 1: Architecture & Planning
- Defined objects, fields, and relationships
- Created formula fields and validation rules
- Planned flows, Apex triggers, batch jobs
- Designed email templates and alerts

### 🏗️ Phase 2: Development
- Built custom objects, fields, tabs, and Lightning App
- Created validation rules, automation (flows & triggers)
- Implemented email alerts and templates
- Developed Batch Apex classes
- Configured user roles, profiles, permission sets

### 🧪 Phase 3: Testing & QA
- Unit testing of Apex classes and flows
- End-to-end scenario testing
- Security and data integrity testing

### 🚀 Phase 4: Deployment & Training
- Deployed to production-ready org
- Recorded video walkthrough demo
- Prepared documentation for user understanding

---

## 📊 Key Features

| Feature                   | Description                                              |
|---------------------------|----------------------------------------------------------|
| 🛍️ Custom Objects         | Orders, Inventory, Customers, Products, Loyalty          |
| 📨 Email Notifications     | Order confirmations & stock alerts                       |
| 🔁 Automation             | Flows, validation rules, triggers                         |
| 🧠 Loyalty Management     | Dynamic updates based on purchase data                   |
| ⏱️ Batch Apex             | Daily updates for bulk orders and inventory management   |
| 🔐 User Security          | Profiles, Roles, Permission Sets                         |

---

## 📂 Tech Stack

- Salesforce Lightning Platform
- Apex Triggers and Batch Apex
- Lightning App Builder
- Flows and Process Builder
- Email Templates and Alerts

---

## 📥 How to Deploy

1. Authenticate your Salesforce org:
    ```bash
    sfdx auth:web:login --setalias handsmen-org
    ```

2. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/handsmen-threads-salesforce.git
    cd handsmen-threads-salesforce
    ```

3. Push code to your org:
    ```bash
    sfdx force:source:push
    ```

4. Assign permission sets (if created):
    ```bash
    sfdx force:user:permset:assign -n Handsmen_Customer_Access
    ```

---

## 🎥 Demo Video

👉 [Click here to watch the project demo](https://drive.google.com/drive/folders/1K8FdpvXYZt5O63TlbZy8G26TlXWLv9DF?usp=drive_link)

---

## 👨‍💻 Author

**Shyam Kumar**  
Salesforce Developer Intern  
📫 shyamkumar_tentu@srmap.edu.in

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
