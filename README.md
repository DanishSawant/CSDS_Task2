# CSDS Task 2: Methodological Deliberation and Fairness Audit

**Student Name:** Danish Sawant
**Student ID:** s4205801
**Institution:** RMIT University
**Repository:** [https://github.com/DanishSawant/CSDS_Task2.git](https://github.com/DanishSawant/CSDS_Task2.git)

---

## Overview

This repository hosts the empirical code, evaluation routines, and generated visual artifacts supporting **Individual Task 2 (Part 2: Methodological Deliberation)**. 

The analysis evaluates the Telco Customer Churn pipeline using:
- **5-Fold Stratified Cross-Validation** to eliminate single-partitioning split variance.
- **Learning Curve Analysis** evaluated across training sample sizes ($N = 400$ to $4,500$) on Recall.
- **Fairness & Demographic Disparity Audit** using Microsoft Fairlearn evaluated across the protected attribute `SeniorCitizen`.
