# Student-Support-Service-Management-System-SSSMS-
Student Support &amp; Service Management System (SSSMS) is a Salesforce app that manages student queries efficiently. It allows students to raise requests, assigns them to the right department, tracks case status, and uses automation, security, and dashboards to improve support and provide real-time insights.

# 📘 Student Support & Service Management System (SSSMS)

## 🚀 Project Overview

The **Student Support & Service Management System (SSSMS)** is a Salesforce-based application designed to efficiently manage student queries related to academics, fees, IT support, and placements.

This system leverages **Salesforce Admin (declarative) features** such as objects, flows, security, reports, and dashboards to automate and streamline support processes.

---

## 🎯 Project Objective

* Capture student requests centrally
* Assign requests to appropriate departments
* Track the lifecycle of support cases
* Provide real-time insights using reports and dashboards

---

## 👥 User Roles

* **Student** → Raises support requests and tracks status
* **Support Executive** → Handles assigned cases
* **Support Manager** → Monitors performance and workload

---

## 🏗️ Data Model

### Standard Objects

* **Account** → Departments
* **Contact** → Students
* **Case** → Support Tickets

### Custom Object

* **Student_Request__c**

  * Request Type
  * Priority
  * Status
  * Description
  * Department
  * Student (Lookup to Contact)

---

## ⚙️ Key Features

### 🔹 Case Management

* Record Types:

  * Academic
  * Fee
  * IT
  * Placement
* Queues for each department
* Web-to-Case integration

---

### 🔹 Automation (Flows)

* Auto-assign cases to queues based on department
* Default priority setting
* Email alerts on case status change
* Scheduled flow for overdue cases

---

### 🔹 Security

* Org-Wide Defaults set to **Private**
* Role Hierarchy:

  * Student → Support Executive → Support Manager
* Sharing Rules for managerial access
* Field-Level Security:

  * Priority hidden from Students

---

### 🔹 UI Customization

* Custom Lightning App: **Student Support App**
* Dynamic Forms for Case object
* Conditional field visibility
* Customized Home Page with:

  * Open Cases Report
  * Today’s Tasks

---

### 🔹 Data Management

* Data Import Wizard used to import student records
* Duplicate Rules to prevent duplicate emails
* Data Export for backup and reporting

---

### 🔹 Reports Created

* Cases by Status
* Cases by Department
* Average Resolution Time

---

### 📊 Dashboard

**Student Support Dashboard**

* Cases by Status (Donut/Bar Chart)
* Cases by Department (Bar Chart)
* Average Resolution Time (Metric)

---

## 📸 Screenshots Included

* Objects & Fields
* Flows
* Security Settings
* Reports & Dashboard

---

## 🧠 Key Learnings

* Salesforce Admin configuration
* Process automation using Flows
* Data security implementation
* Report and dashboard creation

---

## 🏁 Conclusion

This project demonstrates how Salesforce can be used to build a **scalable, automated, and secure support management system** using only declarative tools.

---

## 👨‍💻 Author

**Neeladri Yogendra (Yogi)**
B.Tech CSE | Full Stack Developer | Salesforce Learner

---
