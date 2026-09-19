<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00F2FE&center=true&vCenter=true&width=750&lines=Secure+Data+Transfer+%26+Deletion;Counting+Bloom+Filter+in+Cloud+Computing;Publicly+Verifiable+%7C+No+Trusted+Third+Party" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black" />
  <img src="https://img.shields.io/badge/Cloud_Security-0052CC?style=for-the-badge&logo=icloud&logoColor=white" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />
</p>

## <img src="https://user-images.githubusercontent.com/74038190/212284100-561b973f-3211-4f2f-9bda-723210642fdb.gif" width="32"> Project Overview
With the rapid growth of cloud computing, outsourcing data storage to cloud service providers (CSPs) has become standard practice. However, migrating data securely between distinct cloud providers and ensuring permanent, verifiable data deletion from the source cloud remain critical concerns.

This project implements a novel **Counting Bloom Filter (CBF)** scheme designed for **secure cloud-to-cloud data transfer** and **publicly verifiable data deletion** without relying on any Trusted Third Party (TTP).

---

## <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="32"> Key Features
* 🔒 **Data Confidentiality:** Secure cryptographic algorithms encrypt data prior to cloud deployment.
* 🛡️ **Data Integrity Verification:** Guarantees that transferred data between Cloud A and Cloud B remains intact and uncorrupted.
* 🌐 **Public Verifiability:** Data owners and target clouds can independently verify transfer and deletion proofs without third-party reliance.
* 🗑️ **Assured Data Deletion:** Utilizes Counting Bloom Filters (CBF) for dynamic element removal and guaranteed permanent deletion from source storage.
* ⚡ **Threat Mitigation:** Detects malicious server operations, altered transfer attempts, and unauthorized data retention.

---

## <img src="https://user-images.githubusercontent.com/74038190/212284087-822ff70c-2e97-4923-9a30-02f2206e5281.gif" width="32"> Tech Stack & Architecture
<p left>
  <img src="https://skillicons.dev/icons?i=java,mysql,html,css,js" />
</p>

* **Middleware:** JSP, Servlets
* **Server:** Apache Tomcat
* **Design & Modelling:** Rational Rose (UML, Data Flow Diagrams)

---

## <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e215-52b2-409b-9800-477872288331.gif" width="32"> System Roles & Modules
1. 👤 **Data Owner:** Encrypts files, uploads to primary cloud, triggers migration requests, and verifies deletion evidences.
2. ☁️ **Cloud Server A (Source Cloud):** Stores initial data and performs migration/deletion operations upon request.
3. ☁️ **Cloud Server B (Target Cloud):** Receives transferred data and validates initial integrity.
4. 🔑 **Proxy / Verifier:** Assists in public verifiability checks and cryptographic evidence validation.
5. 💻 **End User:** Requests access and securely downloads authorized cloud files.

---

## <img src="https://user-images.githubusercontent.com/74038190/212284105-021b191c-76e9-4e08-9f33-1463e26fef09.gif" width="32"> Setup & Installation
1. **Database Configuration:**
   * Import the SQL schema located in the `/database` directory into your local MySQL instance.
   * Update database connection credentials in `connect.jsp` / DB handler files.

2. **Server Deployment:**
   * Deploy the source code on **Apache Tomcat**.
   * Launch the application via `index.html` on your web browser (`http://localhost:8080/<project-name>`).

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />
</p>
