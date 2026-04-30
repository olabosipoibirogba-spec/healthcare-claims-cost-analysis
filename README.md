#    Healthcare Cost Drivers & Claims Analytics
### End-to-End Insurance-Focused Data Analysis Project

---

##  Overview
Healthcare costs are rising rapidly, making it critical for insurance providers to understand what drives high-cost claims.

This project analyzes large-scale healthcare claims data to identify **cost drivers, high-risk providers, and regional inefficiencies**, with the goal of supporting **cost optimization and better financial decision-making**.

---

##  Business Objective
To identify **what is driving high healthcare costs** across:
- Diagnosis groups (DRGs)
- Providers
- Regions
- Patient utilization patterns

---

##  Dataset
- 163,000+ healthcare claims records  
- Includes:
  - DRG Definition  
  - Provider details  
  - Patients Charges & Out-of-Pocket (OOP)  
  - Admission & Discharge Dates  
  - Length of Stay  
  - Hospital Referral Region  
  - State & Zipcode  

---

##  Tools & Technologies
- Python (Pandas, NumPy)
- SQL
- Power BI

---

##  Key Analysis
- Cost driver identification (DRG-level)
- Provider performance analysis
- Geographic cost variation (leakage)
- Length of stay vs cost relationship
- Monthly trend & revenue analysis
- Key Influencers (root cause analysis)



##  Key Insights
- Total healthcare spend reached **$5.9B** across ~163K admissions, indicating a high overall cost burden driven primarily by utilization.
- Certain procedures such as **Major Small & Large Bowel Procedures with MCC**, increase the likelihood of high-cost claims by **5.2x**, identifying diagnosis complexity as a primary cost driver.
- **Top 5 providers contribute disproportionately to total costs with the highest provider generating approximately $28M in charges**. This highlights key targets for contract review and cost control.
- The state-level map shows clear **clustering of high-cost regions, particularly in certain states, indicating potential geographic inefficiencies and variation in pricing or care intensity**.
- The monthly trend shows noticeable fluctuations, with peaks around March and September–October, and dips in June and November. This indicates that cost increases are driven by specific high-spend periods rather than consistent growth.
- The **average length of stay is 19 days**, which is relatively high and suggests that prolonged hospital stays may be contributing significantly to increased costs.
- **Average patient out-of-pocket cost is approximately $9K**, indicating a substantial financial burden on patients, especially for high-cost procedures.  



##  Business Recommendations
- Focus cost control on high-impact DRGs
- Review contracts with high-cost providers
- Reduce long hospital stays through care management
- Investigate high-cost regions for inefficiencies
- Improve financial forecasting using monthly trends


##  Dashboard
The Power BI dashboard provides:
- Cost overview (KPIs)
- Trend analysis
- Provider cost distribution
- Geographic cost insights
- Root cause analysis (Key Influencers)

[medical_claims_dashboard.pdf](https://github.com/user-attachments/files/27253356/medical_claims_dashboard.pdf)





