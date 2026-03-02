# Temporal Clinical Reasoning for Medical Coding  
CSCI 5541 – Natural Language Processing (Team Project)

---

## Team Members
- Woochang Shin  
- Jisun Kim  
- Steven Hu  
- Samarth Kumar Samal  

---

## Project Overview

This project develops a temporal clinical reasoning framework for automated ICD and CPT medical coding. 

Unlike traditional NLP-based coding systems that treat each clinical note independently, our approach models diagnostic changes over time, integrates structured clinical data with free-text notes, and aims to provide more consistent and explainable predictions.

---

## Data Access

Access to **MIMIC-IV** requires completion of the official data use training and credentialing process.

For this project, dataset access was obtained through Steven Hu, who has completed the required training and certification to access MIMIC-IV.

- Clinical notes  
- ICD diagnosis codes  
- CPT procedure codes  
- Laboratory results  
- Medication records  

---

## Objective

To build a time-aware and context-aware auto-coding system that:

- Tracks diagnostic evolution across admissions  
- Detects documentation inconsistencies  
- Produces interpretable, evidence-based outputs  

