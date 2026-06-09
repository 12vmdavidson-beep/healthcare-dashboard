# Healthcare DashBoard

This project contains a Power BI healthcare analytics dashboard along with the supporting CSV datasets.

It includes patient, visit, and diagnosis data used to build visual insights.

## Files Included
- HealthcareDB.pbix
- patients.csv
- visits.csv
- diagnoses.csv

## Purpose

To analyze healthcare trends, patient activity, and clinical metrics using Power BI.

## Data Dictionary
**patients.csv**
- patient_id - Unique identifier for each patient
- age - Patient age
- gender - Patient Gender

**visits.csv**
- visit_id - Unique identifier for each visit
- patient_id - Links to patient.csv
- visit_date - Date of the visit
- visit_type - Reason or category of visit

  **diagnoses.csv**
  - diagnosis_id - Unique identifier for each diagnosis
  - visit_id - Links to visits.csv
  - diagnosis_code - ICD or internal code
  - diagnosis_description - Description of the diagnoses
 
    ## How to Use
    1. Download all CSV files and the PBIX file.
    2. Open **HealthcareDB.pbix** in power BI Desktop.
    3. Ensure the CSV files are in the same folder as the PBIX file.
    4. Refresh the data model to load the latest data.
    5. Explore the dashboard visuals to analyze trends and metrics.

    ## Project Overview
    This dashboard provides insights into:
    - Patient demographics
    - Visit frequency and patterns
    - Diagnosis distribution
    - Clinical activity trends

    It is a designed for healthcare analytics practice, data modeling, and visualization skill building.
