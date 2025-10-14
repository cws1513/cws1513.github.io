---
title: 'Project 2: Soccer/Futsal Matching Database System Design using Oracle'
date: 2025-10-13
draft: false 
summary: 'Designed and implemented a database for a match-making and information management system for soccer and futsal enthusiasts using Oracle DB. The process covered everything from requirements analysis to physical design and SQL scripting.'
tags: ["Database", "Oracle", "SQL", "DB Design", "Project"]

image:
  filename: database.png
  caption: 'Project ER Diagram'
  focal_point: Smart
---

As a team project for my database course, I designed and implemented a database for an efficient match-making and information management system for soccer and futsal enthusiasts. The goal was to solve the problems of the inefficient existing matching methods and maximize user convenience.

### 1. Project Overview

This project aims to build a database system that provides features such as personalized match recommendations, easy match applications and team formation, stadium information, and connections to expert lessons. The system is designed to resolve issues like difficulty in information retrieval, frequent match cancellations, and skill imbalances, thereby contributing to the vitalization of sports activities.

### 2. Requirements Analysis & Design

-   **Requirements Analysis**: We defined functional and non-functional requirements by analyzing similar services and considering user convenience. This included core functions like user management, match search, and information management, as well as non-functional aspects like data integrity, security, and performance.

-   **Conceptual Design**: Based on the analysis, we identified 12 core entities such as User, Match, Stadium, and Expert. We defined their attributes and relationships, visualizing them with an **ER Diagram (ERD)**.

-   **Logical Design**: We converted the conceptual design into a relational schema and performed normalization to satisfy at least the **Third Normal Form (3NF)**, minimizing data redundancy and ensuring integrity. Strict integrity constraints like Primary Keys (PK) and Foreign Keys (FK) were defined for each relation.

-   **Physical Design**: The logical schema was translated into an internal schema optimized for the **Oracle** database environment, with appropriate data types and lengths assigned to each column.

### 3. Database Script Implementation

The entire database for the project was implemented with **four SQL scripts**:
1.  `DropTables.sql`: For environment initialization.
2.  `CreateTables.sql`: To create all table schemas with constraints.
3.  `InsertInitialData.sql`: To insert basic data for system operation.
4.  `DataManipulationAndQuery.sql`: To demonstrate DML operations and over five different `SELECT` queries, including joins and subqueries.

These scripts were executed sequentially in Oracle SQL Developer to confirm the successful construction and operation of the database.
