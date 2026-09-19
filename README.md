# Secure Data Transfer and Verifiable Deletion from Counting Bloom Filter in Cloud Computing

## 📌 Project Overview
With the rapid growth of cloud computing, outsourcing data storage to cloud service providers (CSPs) has become standard practice. However, migrating data securely between distinct cloud providers and ensuring permanent, verifiable data deletion from the source cloud remain critical concerns. 

This project implements a novel **Counting Bloom Filter (CBF)** scheme designed for **secure cloud-to-cloud data transfer** and **publicly verifiable data deletion** without relying on any Trusted Third Party (TTP).

---

## ✨ Key Features
* **🔒 Data Confidentiality:** Secure cryptographic algorithms encrypt data prior to cloud deployment.
* **🛡️ Data Integrity Verification:** Guarantees that transferred data between Cloud A and Cloud B remains intact and uncorrupted.
* **🌐 Public Verifiability:** Data owners and target clouds can independently verify transfer and deletion proofs without third-party reliance.
* **🗑️ Assured Data Deletion:** Utilizes Counting Bloom Filters (CBF) for dynamic element removal and guaranteed permanent deletion from source storage.
* **⚡ Threat Mitigation:** Detects malicious server operations, altered transfer attempts, and unauthorized data retention.

---

## 🛠️ Tech Stack & Architecture
* **Language:** Java (JDK 8+)
* **Web & Middleware:** JSP, Servlets, HTML5, CSS3, JavaScript
* **Database:** MySQL Server
* **Server:** Apache Tomcat
* **Design & Modelling:** Rational Rose (UML, Data Flow Diagrams)

---

## 👥 System Roles & Modules
1. **Data Owner:** Encrypts files, uploads to primary cloud, triggers migration requests, and verifies deletion evidences.
2. **Cloud Server A (Source Cloud):** Stores initial data and performs migration/deletion operations upon request.
3. **Cloud Server B (Target Cloud):** Receives transferred data and validates initial integrity.
4. **Proxy / Verifier:** Assists in public verifiability checks and cryptographic evidence validation.
5. **End User:** Requests access and securely downloads authorized cloud files.

---

## 🚀 Setup & Installation
1. **Database Configuration:**
   * Import the SQL schema located in the `/database` directory into your local MySQL instance.
   * Update database connection credentials in `connect.jsp` / DB handler files.

2. **Server Deployment:**
   * Deploy the source code on **Apache Tomcat**.
   * Launch the application via `index.html` on your web browser (`http://localhost:8080/<project-name>`).
