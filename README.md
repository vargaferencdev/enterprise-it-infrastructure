# Bentley Debrecen – IT Infrastructure & Services Project

## 📈 Project Status

**🚧 In Development**

The project is currently under development. Details may change as the project progresses.

## 📌 Project Overview

This project was developed as part of the **DT-ITS – IT Services in a Large Enterprise Environment** course.

The project focuses on designing a complete **IT infrastructure and service portfolio for a fictional Bentley manufacturing plant in Debrecen, Hungary**.

The goal is to transform the customer's business and technical requirements into a coherent enterprise IT solution covering:

- Network infrastructure
- Physical and logical network topology
- Server and virtualization infrastructure
- Storage and backup
- Active Directory and Exchange
- IT security and access control
- Mobile device management
- Web and DMZ services
- High availability and business continuity
- Project planning
- Cost estimation

The final solution is presented as a professional project proposal to the customer.

---

## 🏭 Customer Background

Bentley is planning a new manufacturing facility in **Debrecen, Hungary**, near the airport.

The factory combines several different business areas:

- Vehicle body manufacturing
- Assembly
- Warehouse operations
- Logistics
- Quality assurance
- Engineering
- Administration
- HR
- IT operations
- Sales and dealer-related services

The IT infrastructure therefore has to support both **office users and industrial/manufacturing operations**, while maintaining appropriate security, availability and network separation.

---

## 👥 Workforce

The planned organization consists of approximately **350 employees**:

| Area | Employees | Working model |
|---|---:|---|
| Office staff | 30 | Daytime, 40 hours/week |
| Other personnel | 30 | Security and cleaning |
| Production | 290 | 3-shift operation, 7×24 |
| **Total** | **350** | |

The production environment is particularly important because the IT infrastructure must support continuous operation.

---

# 🎯 Customer Requirements

## User & Enterprise Services

The customer requires an enterprise IT environment providing:

- Centralized user management
- Active Directory
- Microsoft Exchange
- Software distribution
- Mobile device management
- Centralized configuration of company devices
- Organizational separation using dedicated Active Directory OUs

---

## 🌐 Internet & Web Access

Internet access must be controlled according to the employee's role.

### Internet access

Internet access is available to **office employees**.

### Social media

Access to Facebook and other social media platforms is restricted to:

- Plant Director
- HR personnel

The proposed solution must therefore support **user- and group-based access control**.

---

## 🔐 Security Requirements

Several security restrictions must be enforced throughout the organization.

### Application installation

Employees must not be able to install applications on company-owned devices.

### Photography & audio recording

Photography and audio/video recording are prohibited inside the factory using:

- Mobile phones
- Cameras
- Similar devices

### Mobile device configuration

Company mobile devices must receive their required configurations automatically, including:

- Wi-Fi configuration
- Exchange account configuration
- Security restrictions
- Other centrally managed policies

---

# 🖥️ Server & Infrastructure Requirements

The customer requires **Dell hardware** for the infrastructure.

The proposed server environment includes:

| Service | Quantity | Requirement |
|---|---:|---|
| Active Directory + Exchange | 3 × 2 | Virtual machines |
| Storage | 3 × 1 | RAID 10 |
| Proxy servers | 2 | Redundant proxy infrastructure |
| Web servers | 2 | Online configurator and dealer ordering |
| Local backup server | 1 | Local backup infrastructure |
| Remote backup server | 1 | Off-site backup |

The Active Directory and Exchange services must run as **virtual machines**.

The storage infrastructure must use **RAID 10**.

---

# 🏢 Site Architecture

The factory consists of three main buildings:

### Building 1 – Production

Includes areas such as:

- Body manufacturing
- Assembly line 1
- Assembly line 2
- Engineering / support areas
- Quality-related functions

### Building 2 – Warehouse & Logistics

Includes:

- Raw material warehouse
- Finished goods warehouse
- Logistics operations

### Building 3 – Office & IT

Includes:

- Management
- HR
- Finance
- Engineering
- Administration
- IT infrastructure

---

## 🌐 Network Backbone

The proposed site design uses a **redundant optical backbone connecting the three buildings**.

The current conceptual network design includes:

- **MDF-C** – core / firewall location
- **IDF-A** – Building 1
- **IDF-B** – Building 2
- **IDF-C** – Building 3
- Dual optical backbone connections

The physical network design is conceptual and is not intended to be a construction-ready blueprint. Final deployment would require detailed architectural information and an on-site radio survey.

---

## 📶 Wi-Fi Design

The current conceptual design uses **30 wireless access points**:

| Area | Proposed APs |
|---|---:|
| Production | 16 |
| Warehouse & Logistics | 8 |
| Office / shared areas | 6 |
| **Total** | **30** |

The final number and exact placement of access points would need to be validated through an on-site RF survey.

---

# 📨 High Availability & Business Continuity

The customer requires the email infrastructure to remain operational even if an entire building becomes unavailable.

Therefore, the architecture must avoid relying on a single building as a critical point of failure.

The solution considers:

- Redundant network connectivity
- Distributed services
- Redundant email infrastructure
- Multiple storage systems
- Local backup
- Off-site remote backup
- Building-level failure scenarios

The **remote backup infrastructure must be located outside the primary site**.

---

# 📊 Project Deliverables

The student team is responsible for designing a complete IT solution based on the customer's requirements.

The main deliverables include:

### Network

- Logical network topology
- Physical network topology
- Structured cabling concept
- Optical backbone
- Network rack locations
- Wi-Fi design
- Network segmentation
- Firewall concept

### Server & Infrastructure

- Server architecture
- Virtualization architecture
- Active Directory
- Exchange
- Proxy infrastructure
- Web infrastructure
- Storage
- RAID 10
- Backup infrastructure
- Remote backup

### Security

- Active Directory OU structure
- User and group management
- Access control
- Security policies
- Internet filtering
- Social media restrictions
- Application installation restrictions
- Mobile device management
- Factory device restrictions

### Project Management

- Project schedule
- Tasks
- Responsibilities
- Deadlines
- Milestones
- Cost estimation
- Operational costs

---

# 💰 Cost Estimation

The project includes both **initial investment costs and operational costs**.

The financial model must account for:

- Hardware
- Server infrastructure
- Storage
- Network infrastructure
- Software/services
- Implementation
- Operation and maintenance

The project also requires the proposed contract value to cover the total relevant implementation and operational costs.

The project materials specify the following exchange rates for cost calculations:

| Currency | Exchange rate |
|---|---:|
| USD | 1 USD = 315 HUF |
| GBP | 1 GBP = 430 HUF |
| EUR | 1 EUR = 360 HUF |

---

# 👨‍💻 Student Team

The project is developed by a **3–4 person student team**.

Each team member is expected to:

- Participate in the project work
- Take responsibility for a specific area
- Present their area during the final presentation
- Understand the overall architecture

A recommended division of responsibilities is:

| Area | Responsibilities |
|---|---|
| **Network** | Topology, VLAN/IP design, cabling, Wi-Fi, MDF/IDF, firewall |
| **Server & Storage** | AD, Exchange, VMs, storage, RAID 10, proxy, web, backup |
| **Security & Enterprise** | OU structure, permissions, policies, MDM, access control |
| **Project Management & Finance** | Schedule, responsibilities, budget, CAPEX/OPEX, presentation coordination |

This division is a project-management recommendation rather than a formal customer requirement.

---

# 📋 Final Presentation

The final result of the project is a **professional project presentation**.

The presentation must demonstrate how the team translated the customer's requirements into a complete technical solution.

The presentation covers:

1. Customer and business requirements
2. Proposed IT architecture
3. Logical network topology
4. Physical network / cabling design
5. Server and virtualization architecture
6. Storage and backup
7. Active Directory and Exchange
8. Security architecture
9. Mobile device management
10. High availability and business continuity
11. Project schedule
12. Responsibilities
13. Cost estimation
14. Requirement-to-solution mapping

The presentation is limited to **20 minutes per team**.

Every team member participates in the presentation.

---

# 📁 Repository Structure

The repository is organized around the main areas of the project:

```text
/
├── README.md
│
├── docs/
│   ├── project-description/
│   ├── requirements/
│   └── architecture/
│
├── network/
│   ├── logical-topology/
│   ├── physical-topology/
│   ├── cabling/
│   └── wifi/
│
├── server-storage/
│   ├── virtualization/
│   ├── active-directory/
│   ├── exchange/
│   ├── storage/
│   └── backup/
│
├── security/
│   ├── access-control/
│   ├── policies/
│   └── mobile-management/
│
├── project-management/
│   ├── schedule/
│   ├── responsibilities/
│   └── milestones/
│
├── budget/
│   ├── hardware/
│   ├── services/
│   └── capex-opex/
│
└── presentation/
```

---

# 🧩 Project Scope

This repository documents the **design and planning phase** of the Bentley Debrecen IT infrastructure project.

The project focuses on producing a technically justified enterprise architecture and project proposal based on the supplied customer requirements and project materials.

It is **not intended to represent a production deployment of Bentley's real infrastructure**.

---

# 🎓 Academic Context

**Course:** DT-ITS – IT Services in a Large Enterprise Environment  
**Project:** Bentley Debrecen Manufacturing Plant  
**Project Type:** Enterprise IT infrastructure and service design  
**Team Size:** 3–4 students  
**Final Deliverable:** Professional project presentation  
**Presentation Duration:** Maximum 20 minutes

---

## 📌 Summary

The Bentley Debrecen project demonstrates how a large manufacturing company's business requirements can be translated into a complete enterprise IT solution.

The project combines:

**Business requirements → IT architecture → Network → Servers → Security → Availability → Costs → Project management**

The objective is to create a realistic, scalable and secure IT environment capable of supporting both the **manufacturing operations** and the **corporate side of the organization**.
