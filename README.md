# ERPTEST-V-1-Intelligent-Human-Resource-Management-Platform
ERPTEST-V-1 is a comprehensive HR management solution designed to modernize, automate, and digitize the internal processes of a growing company. Built as an internal ERP, it centralizes employee management, contract tracking, performance indicators (KPIs), and internal communication.



# 🚀 ERPTEST-V-1 – Intelligent Human Resource Management Platform

![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![Angular](https://img.shields.io/badge/Frontend-Angular-red)
![Docker](https://img.shields.io/badge/Deployment-Docker-blue)
![Status](https://img.shields.io/badge/Code-Private-lightgrey)

> **ERPTEST-V-1** is a comprehensive HR management solution designed to modernize, automate, and digitize a company’s internal processes.  
> Built as an **internal ERP**, it centralizes employee management, contracts, performance indicators (KPIs), and internal communication.

---

##  Vision & Objectives

Before ERPTEST-V-1, the company faced multiple HR challenges:

- **Manual and fragmented processes** (Excel sheets, emails, local files)  
- Difficulty in **tracking contracts, attendance, and performance**  
- Lack of **internal communication and corporate culture**

**Goal:** unify all HR functions into a single platform, accessible to HR managers, engineers, and executives.

**Key objectives:**

- Automate administrative tasks  
- Centralize employee data  
- Monitor performance and attendance in real time  
- Foster internal communication via a corporate blog  

---

##  Impact on the Organization

### 1. Administrative Efficiency
- Reduced **HR document management time by 40%**  
- Fewer manual errors from data entry and email exchanges  
- Simplified contract tracking (CDD, CDI, CIVP) through automatic PDF generation  

### 2. Improved Internal Communication
- Created a **corporate blog** for announcements, team successes, and HR posts  
- Automated **birthday posts** via a cron job 🎉  
- Strengthened team cohesion and engagement  

### 3. Time Saving & Traceability
- Centralized all HR information in one interface  
- Retrieve employee documents in seconds  
- Automatic history logging for all HR actions (add, delete, update)  

### 4. Performance Monitoring
- Integrated **KPI module** to track individual performance  
- Automatic weighted score calculations per role  
- Visual HR analytics (age, department, seniority, gender, etc.)  

### 5. Compliance & Security
- Role-based access control (`ADMIN`, `HR`, `ENGINEER`, `PF`, `SI`)  
- JWT authentication with `.env` environment isolation  
- Automated database backups via XAMPP / Docker  

---

## ⚙️ Digital Transformation Highlights

| Before ERPTEST-V-1                 | After ERPTEST-V-1                     |
| ---------------------------------- | ------------------------------------ |
| Multiple Excel files & emails      | Unified web interface                |
| Manually written contracts         | Automatic PDF generation             |
| Minimal internal communication     | Collaborative company blog           |
| Manual attendance entry            | Automated CSV import                 |
| Paper-based KPI tracking           | Real-time dashboards                 |

---

##  Key Innovations

- Automated **cron jobs** for HR publications (birthdays, events)  
- **PDF generation** with secure signing & archiving  
- Intelligent data import for attendance tracking  
- **Dynamic KPI module** stored in MongoDB  
- **Dockerized backend & frontend** for seamless deployment  
- **Modular architecture** for future scalability  

---

##  Role & Personal Contributions

**Bayrem Boussaidi – Full-Stack Developer**

Responsible for the **complete backend (Node.js / Express.js)** and **frontend (Angular)** development, including database design, route security, and automation workflows.

**Main contributions:**

- Designed backend architecture (`routes`, `services`, `uploads`)  
- Developed **Blog module** (CRUD + cron automation)  
- Integrated **KPI module** (performance computation + MongoDB)  
- Automated **contract PDF generation** by contract type (CDD/CDI/CIVP)  
- Implemented **JWT-based role & permission control**  
- Built Angular UI components for HR dashboard  
- Dockerized project and authored full technical documentation  

---

## 🧩 Tech Stack

| Area                | Technologies                       |
| ------------------- | ---------------------------------- |
| **Frontend**        | Angular, TypeScript, SCSS, PrimeNG |
| **Backend**         | Node.js, Express.js                |
| **Database**        | MySQL (XAMPP), MongoDB (KPI)       |
| **Security**        | JWT, dotenv, checkRole middleware  |
| **Automation**      | node-cron, multer                  |
| **PDF / Docs**      | pdfkit                             |
| **Deployment**      | Docker, docker-compose             |

---

## Achieved Results

- 📉 40% reduction in HR administrative time  
- 📂 Centralization of over **10,000 internal documents**  
- 🔄 Full automation of 4 major HR processes  
- 🧾 100% of employee contracts digitally archived  
- 💬 **+25% increase in employee engagement** via blog & auto-posts  

---

##  Future Enhancements

- Internal **HR ↔ Employee chat system**  
- Advanced **AI-based analytics** for predictive performance insights  
- Integration with external APIs (payroll, leave management, etc.)  
- Unified access management via **Keycloak dashboard**  

---

##  Author

**Bayrem Boussaidi**  
Software Developer — DevOps | Node.js | Angular | Docker  
📍 Tunisia  
📧 [bayrem.boussaidi@example.com](mailto:bayremboussaidi187@gmail.com )  
🔗 [LinkedIn](https://linkedin.com/in/bayrem-boussaidi)  
🖥️ [Portfolio](https://your-portfolio-link.com)

---

## 🔒 Confidentiality Notice

> **Source Code Privacy**  
> The full source code of **ERPTEST-V-1** is **private and confidential**.  
> This project was developed during a professional internship and is protected under the company’s **intellectual property and data protection policies**.  
>  
> Repository access is **restricted** and available **only upon formal professional request**.  
>  
> © 2025 — All rights reserved to the company and the author, *Bayrem Boussaidi*.
