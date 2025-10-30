# Aviation Risk Strategy: Quantifying Safety for New Fleet Procurement

## Overview

This project provides a **data-driven risk framework** using 60+ years of NTSB accident data to establish the optimal safety foundation for a new aviation division. The analysis segments risk into three measurable scores to deliver **concrete, actionable policies** for fleet procurement and operational deployment, minimizing liability and catastrophic loss.

* **Final Notebook:** [Link to your final Aviation.ipynb file here]
* **Stakeholder Presentation:** [Link to your Final Presentation PDF here]

---

## Business Understanding

### Stakeholder and Key Business Questions

* **Primary Stakeholder:** Head of the Aviation Division.
* **Goal:** To establish the lowest-risk operational and equipment profile possible at launch.

### Key Business Questions

1.  **Procurement (R2):** Which manufacturer offers the lowest **inherent fatal risk**?
2.  **Operations (R3 - Frequency):** Where do we focus training to prevent the most **common accidents**?
3.  **Safety Policy (R1 - Severity):** Where do we focus specialized training to mitigate the most **catastrophic consequences**?

---

## Data Understanding and Analysis

### Source of Data

The analysis uses historical civil aviation accident data from the **NTSB (National Transportation Safety Board)**, covering the period from **1962–2023**.

### Description of Data

Data was cleaned and segmented using Python/Pandas to create three distinct risk metrics:

| Risk Score | Metric | Strategic Focus |
| :--- | :--- | :--- |
| **R2 (Equipment)** | **Fatal Accident Rate (%)** by Manufacturer. | **Procurement** |
| **R3 (Frequency)** | **Total Count** of Accidents by Phase. | **High-Volume** Mitigation |
| **R1 (Severity)** | **Average Total Injuries** per Accident by Phase. | **Consequence** Mitigation |

### Three Visualizations

The three core charts visually confirm the risk profile:

1.  **Equipment Risk (R2) Chart:** Highlights **BOEING** as the safest manufacturer (lowest Fatal Rate).
2.  **Operational Frequency (R3) Chart:** Identifies **LANDING** and **TAKEOFF** as the most frequent accident phases (highest count).
3.  **Operational Severity (R1) Chart:** Identifies **CLIMB** and **MANEUVERING** as the phases with the highest average injuries (highest severity).

---

## Conclusion

### Summary of Conclusions (Three Relevant Findings)

1.  **Procurement Policy:** **BOEING** is confirmed as the low-risk choice, exhibiting a Fatal Accident Rate of only **6.08%**.
2.  **High-Frequency Priority:** **LANDING** and **TAKEOFF** require the highest resource allocation for **SOP development** and supervision to reduce the sheer **number** of incidents.
3.  **High-Severity Priority:** **CLIMB** and **MANEUVERING** require specialized **Advanced Scenario Training** to mitigate the severe, catastrophic outcomes of rare failures.