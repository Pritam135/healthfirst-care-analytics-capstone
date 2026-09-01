# HealthFirst Care - Data Analytics & Business Analysis Capstone Project

- **Author / Analyst:** Pritam Kar
- **Course:** IBM - Introduction to Business Analysis (Coursera Capstone)
- **Status:** Modules 1, 2, 3, 4, & 5 Completed

---

## Executive Summary

The **HealthFirst Care Initiative** addresses critical operational bottlenecks impacting patient experience and hospital efficiency. By synthesizing empirical data across **216 appointment records**, **217 patient feedback logs**, and **213 resource records**, this repository houses the end-to-end data analysis, BPMN process models, swimlane workflow diagrams, business requirements, operational dashboards, and risk management planning.

---

## Key Performance Drivers & Target Metrics

| Operational Metric | Baseline State (As-Is) | Target State (To-Be) | Key Business Impact & Solution |
|:---|:---|:---|:---|
| **Average Patient Wait Time** | 41.4 minutes | ≤ 33.1 minutes | **AC-01:** 20%+ reduction via self-service kiosks & QR check-in. |
| **Double-Booking Incidents** | 32 incidents | 0 incidents | **AC-02:** 100% elimination using real-time conflict prevention engine. |
| **Patient Satisfaction Rating** | 6.3 / 10 rating | ≥ 8.0 / 10 rating | **AC-03:** Boosted satisfaction via automated SMS/Email queue alerts. |
| **Peak Resource Availability** | 45.1% available | ≥ 70.0% available | **AC-04:** Live interdepartmental tracking to balance doctor workload. |

---

## Project Structure & Module Progress

- **Module 1: Requirements Engineering (Completed)**
  - Business Requirements Document (BRD) & Requirements Traceability Matrix (RTM).
- **Module 2: Stakeholder & Scope Management (Completed)**
  - Stakeholder Analysis & Engagement Plan, Work Breakdown Structure (WBS), and Scope Management Plan.
- **Module 3: Advanced Business Process Modeling & Swimlane Workflows (Completed)**
  - High-level As-Is and To-Be process models.
  - Advanced BPMN swimlane workflow diagrams covering cross-functional operations (Appointment Scheduling, Patient Check-In & Triage, and Discharge Planning).
  - Bottleneck identification and efficiency impact analysis.
- **Module 4: Data Analysis & Visualization Dashboard (Completed)**
  - **Part 1 (Completed):** Data cleaning, missing value imputation, duplicate elimination, and exploratory data analysis (EDA) across appointment, feedback, and resource datasets (`appointment_data_task2.xlsx` & `Capstone_Project_M04L01_Data_Analysis.docx`).
  - **Part 2 (Completed):** Interactive dashboard built in Looker Studio – line chart (wait time trends), bar chart (resource utilization by department), heatmap table (usage by department x resource type), and pie chart (satisfaction levels), with Department, Satisfaction Level, and date-range filters (`HealthFirst_Care_Dashboard.pdf.pdf` & `Capstone_Project_M04L02_Dashboard_Insights.docx`).
- **Module 5: Risk Management & SWOT Analysis (Completed)**
  - **Part 1 (Completed):** Risk Register documenting 15 Operational, Technical, and Stakeholder risks with Likelihood x Impact severity scoring, mitigation strategies, and a color-coded 3x3 Risk Assessment Matrix (`HealthFirst_Care_Risk_Register.xlsx`); Risk Management Plan combining the Risk Register, Risk Assessment Matrix, and a SWOT Analysis (`Capstone_Project_M05L01_Risk_Register_SWOT.docx`).
  - **Part 2 (Completed):** Updated Risk Matrix with mitigation strategies for all 15 risks, plus detailed contingency plans for the 7 High-severity risks (OP-01, OP-03, OP-04, OP-05, TE-02, TE-04, ST-05), consolidated into a Risk Mitigation Plan (`Capstone_Project_M05L02_Risk_Matrix_Mitigation.docx`).

---

## Repository Structure

```text
docs/
├── As_Is_Process_Model.pdf.pdf                          # Current-state BPMN process model
├── Capstone_Project_M01L01_BRD.doc.docx                  # Business Requirements Document (BRD)
├── Capstone_Project_M01L02_RTM.docx                      # Requirements Traceability Matrix (RTM)
├── Capstone_Project_M02L01_Stakeholder_Analysis.docx     # Stakeholder Engagement Plan
├── Capstone_Project_M02L02_Scope_Management.doc          # WBS & Scope Management Plan
├── Capstone_Project_M03L01_Process_Model.docx            # As-Is / To-Be process model analysis
├── Capstone_Project_M03L02_Swimlane_Diagrams.docx        # BPMN swimlane workflow diagrams
├── Capstone_Project_M04L01_Data_Analysis.docx            # Data cleaning & EDA report
├── Capstone_Project_M04L02_Dashboard_Insights.docx       # Dashboard design & insights report
├── Capstone_Project_M05L01_Risk_Register_SWOT.docx       # Risk Management Plan & SWOT Analysis
├── Capstone_Project_M05L02_Risk_Matrix_Mitigation.docx   # Updated Risk Matrix & Contingency Plans
├── HealthFirst_Care_Dashboard.pdf.pdf                    # Exported Looker Studio dashboard
├── HealthFirst_Care_Risk_Register.xlsx                   # Risk Register & Risk Assessment Matrix
├── To_Be_Process_Model.pdf.pdf                           # Future-state BPMN process model
└── appointment_data_task2 (1).xlsx                       # Cleaned datasets & pivot analysis
```
