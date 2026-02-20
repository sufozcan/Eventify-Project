# Eventify: Relational Event Management Database System

Eventify is a robust, normalized relational database system designed to manage large-scale events, including venues, sessions, participants, ticketing, and financial analysis.

## Project Overview
Developed for the **STAT 311 - Modern Database Systems** course at **METU**, this project aims to model real-world event operations while ensuring data integrity, scalability, and efficient retrieval.

## Tech Stack & Implementation
* **Database Engine:** PostgreSQL.
* **Design Tools:** Figma for Conceptual ER Modeling.
* **Frontend Visualization:** JavaScript & HTML/CSS (Live version available at [Eventify Frontend](https://kemalcanyologlu.github.io/eventify-frontend/)).
* **Data Flow:** PostgreSQL (SQL Queries) → CSV Export → JavaScript Objects → User Interface.

## Database Architecture
* **Conceptual Design:** Detailed ER Diagram covering entities like Events, Sessions, Speakers, Tickets, and Sponsors.
* **Relational Schema:** Fully normalized database structure (3NF) utilizing Primary Keys, Foreign Keys, and many-to-many junction tables.
* **Integrity Constraints:** Implemented `UNIQUE`, `CHECK`, and referential integrity rules to prevent data redundancy and inconsistencies.

## SQL Analytics & Features
The project demonstrates advanced SQL capabilities through several complex query scenarios:
* **Revenue Analysis:** Aggregated financial reporting per event to analyze total income.
* **Capacity Tracking:** Real-time monitoring of ticket utilization and remaining seat capacity per hall.
* **Attendance Metrics:** Calculation of session participation rates using attendance logs and common table expressions (CTEs).
* **Conflict Detection:** Algorithmic validation to prevent scheduling conflicts within the same venue/hall.
* **Sponsor Management:** Tracking multi-level sponsorship contributions (Platinum, Gold, Silver) and distribution.

## The Team
This project was a collaborative effort by:
* **Yusuf Özcan**
* **Dilara Yıldırım**
* **Kemal Can Yoloğlu**
* **Rabia Demircan**
* **Timuçin Eke**

---
*Developed as a Final Project for the Department of Statistics, METU (Jan 2026).*
