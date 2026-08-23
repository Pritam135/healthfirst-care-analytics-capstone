# HealthFirst Care - Data Analytics & Business Analysis Capstone Project

* **Author / Analyst:** Pritam Kar
* **Course:** IBM - Introduction to Business Analysis
* **Status:** In Progress (Modules 1 & 2 Completed | Module 3 In Progress)

---

## Executive Summary

The **HealthFirst Care Initiative** addresses critical operational bottlenecks impacting patient experience and hospital efficiency. By synthesizing empirical data across **216 appointment records**, **217 patient feedback logs**, and **213 resource records**, this repository houses the end-to-end data analysis, process models, business requirements, and operational dashboards.

---

## Key Performance Drivers & Target Metrics

| Operational Metric | Baseline State (As-Is) | Target State (To-Be) | Key Business Impact & Solution |
| :--- | :--- | :--- | :--- |
| **Average Patient Wait Time** | 41.4 minutes | ≤ 33.1 minutes | **AC-01:** 20%+ reduction via self-service kiosks & QR check-in. |
| **Double-Booking Incidents** | 32 incidents | 0 incidents | **AC-02:** 100% elimination using real-time conflict prevention engine. |
| **Patient Satisfaction Rating** | 6.3 / 10 rating | ≥ 8.0 / 10 rating | **AC-03:** Boosted satisfaction via automated SMS/Email queue alerts. |
| **Peak Resource Availability** | 45.1% available | ≥ 70.0% available | **AC-04:** Live interdepartmental tracking to balance doctor workload. |

---

## Repository Structure

```text
├── docs/
│   ├── Capstone_Project_M01L01_BRD.doc                  # Business Requirements Document (BRD)
│   ├── Capstone_Project_M01L02_RTM.doc                  # Requirements Traceability Matrix (RTM)
│   ├── Capstone_Project_M02L01_Stakeholder_Analysis.doc # Stakeholder Engagement Plan
│   ├── Capstone_Project_M02L02_Scope_Management.doc     # Scope Management & Work Breakdown
│   ├── Capstone_Project_M03L01_Process_Model.docx       # As-Is & To-Be Process Analysis
│   ├── As_Is_Process_Model.pdf                          # Current State Process Flow Diagram
│   └── To_Be_Process_Model.pdf                          # Future Optimized Process Flow Diagram
├── scripts/
│   ├── data_cleaning.py                                 # Python data cleaning script
│   └── analysis.sql                                     # SQL scripts for aggregations & joins
├── dashboards/
│   └── dashboard_preview.png                            # Tableau & visual dashboards
└── README.md                                            # Repository Documentation       
