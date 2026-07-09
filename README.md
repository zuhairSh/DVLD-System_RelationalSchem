# DVLD System (Driving & Vehicle License Department) 🚗🗄️

A comprehensive Database Schema Design for an integrated system managing driving license applications, test appointments, and the full license lifecycle.

---

## 🏗️ Database Architecture
The system is built on a normalized relational database model designed to ensure data integrity and scalable workflow management.

### Entity Relationship Diagram (ERD)
![DVLD Database Schema](DVDL_Diagram.png)

> **📥 High-Resolution Resource:** For detailed analysis, you can download the full-scale [Database Schema (PDF)](DVDL_Diagram.drawio.pdf).

---

## 🔑 Key Schema Features

* **Centralized Person Entity:** A core `Persons` table serving as the foundation for both `Users` and `Drivers` to maintain data consistency.
* **License Application Lifecycle:** Robust handling of application types, status tracking, and associated fees.
* **Testing & Certification:** Detailed tracking for test types, appointment scheduling, and individual test results.
* **License Management:** Manages issued licenses, renewals, and detention/release records with a full audit trail capability.

## 🛠️ Technologies Used

* **Design Model:** Relational Database Design (ERD).
* **Core Concepts:** Normalization, Foreign Key Constraints, and State Management.

---
*This database schema was designed to support a full-featured Windows Forms application.*
