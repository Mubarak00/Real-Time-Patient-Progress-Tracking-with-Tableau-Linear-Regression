# Real-Time Patient Progress Tracking with Tableau & Linear Regression

## Project Summary
Integrated real-time patient progress analytics into the hospital’s EMR system using linear regression outputs visualized through Tableau dashboards, enhancing clinical oversight and recovery monitoring.

## Problem Statement
Clinicians lacked live feedback loops on patient recovery progress, especially for post-operative and chronic care. Manual tracking delayed interventions and lacked visual interpretation.

## Tools & Technologies Used
- **Analytics Tools**: Tableau, Tableau Embedded  
- **ML Model**: Linear Regression  
- **Languages**: Python, SQL  
- **Data Sources**: Vital signs, lab results, treatment logs (EMR export)  
- **Deployment Context**: Internal Tableau dashboards linked to EMR via API

## Implementation Details
- Trained linear regression models to predict patient outcome trends over time  
- Integrated model outputs as real-time data streams into Tableau dashboards  
- Used calculated fields and triggers to flag abnormal trajectories  
- Embedded dashboards directly into the EMR interface used by clinicians

## Architecture Overview
```
EMR Data ─▶ Regression Model ─▶ Tableau Data Pipeline ─▶ Embedded Dashboard in EMR
```

## Results & Impact
- Enabled real-time tracking of patient recovery scores and health KPIs  
- Improved clinician response time for deteriorating conditions  
- Empowered medical staff with visual and predictive insights during rounds

## Monitoring & Maintenance
- Regression models retrained weekly using new EMR data  
- Tableau usage analytics monitored for dashboard engagement

## Challenges & Learnings
- Alignment between clinical definitions and model inputs was crucial  
- Dashboard simplicity drove higher adoption by non-technical users  
- Visual alert design required iterative testing with nurse practitioners

## Team Collaboration
- Joint work with data scientists, nurses, and EMR software integrators  
- Weekly feedback sessions with care teams for continuous improvement

## Code Availability
Due to integration with a live EMR system, the project code is not publicly available.
