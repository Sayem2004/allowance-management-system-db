#  Allowance Management System (Database Project)

##  Overview

The **Allowance Management System** is a database-driven project built using **Oracle SQL**.
It is designed to manage the collection of funds from multiple sources and distribute them efficiently through NGOs and relief organizations.

This project was developed during the **Spring 2022-23 semester** as part of the **Introduction to Database (CSC 2107)** course.



##  Objectives

* Manage funds from multiple sources (International, Government, Individuals, Fundraisers)
* Maintain NGO and Relief Organization data
* Distribute funds to different beneficiary groups
* Design a structured and normalized relational database



##  System Features

### 🔹 Fund Sources

* International Funds
* Individual Persons
* Government Funds
* Fundraisers

### 🔹 Organizations

* NGO (Non-Governmental Organization)
* Relief Organizations

### 🔹 Beneficiaries

* Farmers
* Natural Disaster Affected People
* Orphans
* Widows
* Disabled People
* Maternity Support


##  Database Concepts Used

* Entity Relationship (ER) Diagram
* Database Normalization (1NF, 2NF, 3NF)
* Relational Database Design
* Primary Key & Foreign Key Constraints
* SQL Queries and Data Manipulation



##  Technologies Used

* Oracle Database
* SQL (DDL & DML)
* Oracle SQL Developer



##  Project Structure

/project-files
├── ER Diagram
├── Normalization
├── Table Design
├── SQL Scripts
│    ├── CREATE TABLE
│    ├── INSERT VALUES
│    ├── Queries
└── Documentation (DOCX/PDF)



##  Example Query

```sql
SELECT MAX(GF_AMOUNT) AS "MAXIMUM",
       MIN(GF_AMOUNT) AS "MINIMUM",
       ROUND(AVG(GF_AMOUNT)) AS "AVERAGE"
FROM GOVT_AMOUNT;




##  How to Run

1. Install **Oracle SQL Developer**
2. Open the SQL script files
3. Execute the `CREATE TABLE` queries
4. Run `INSERT` statements to populate data
5. Execute queries to test the system



##  Authors

* **MD. Al-Imran Sayem** 
* MD. Ferdouse Ahmed Oli
* Ahsanul Ekram Patwary
* MD. Raihan Kabir

 BSc in Computer Science & Engineering
 American International University-Bangladesh (AIUB)


##  Project Timeline

* Developed in: **Spring 2022-23**
* Type: Academic Project (University Coursework)
* Purpose: Learning Database Design & SQL Implementation


##  Notes

This project is developed for academic purposes and demonstrates fundamental database concepts including ER modeling, normalization, and SQL operations.



