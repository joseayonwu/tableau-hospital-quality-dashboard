# Hospital Quality Intelligence Dashboard  
*Interactive Tableau project analyzing U.S. hospital performance*

---

## Objective
This project delivers an executive-ready Tableau dashboard that analyzes hospital quality metrics across the United States.  
It applies advanced visualization techniques — **data blending, LOD expressions, forecasting, and parameter-driven sensitivity analysis** — to explore how **ownership, staffing, and geography** affect healthcare outcomes.

---

## Data Preparation
The dataset is based on the **CMS Hospital General Information** database, complemented with two synthetic variables:
- **Staff-to-Patient Ratio**
- **Average Readmission Cost per Provider ID**

Data was cleaned and transformed in **Tableau Prep**:
- Removed non-analytic fields and standardized data types  
- Mapped text ratings into numeric scales (Overall 1–5; Quality 1–3)  
- Corrected Latitude/Longitude for mapping  
- Joined and exported as a single `.hyper` extract powering all dashboards  

---

## Key Insights
- **Voluntary (non-profit)** hospitals lead overall quality metrics.  
- **Private (for-profit)** hospitals perform strongly in Safety & Timeliness but underperform in Readmission.  
- **Government** hospitals align near the national average, with Mortality below benchmark.  
- **Geography** alone does not explain quality differences — operational management matters more.  
- **Staff-to-patient ratio** shows limited predictive power; process design and efficiency matter more than staffing quantity.  

---

## Dashboard Features
- KPI panel comparing **State vs National averages**
- Ownership performance benchmarking  
- Trend analysis of **Staff Ratio → Quality metrics**  
- Parameter-based **Sensitivity (What-If) Simulator**  
- Clean storytelling structure: *Hospital Quality → Ownership → Trends → Sensitivity*

---

## Project Preview
| Section | Screenshot |
|----------|-------------|
| Overview | ![Overview](images/overview.png) |
| Metrics by Ownership | ![Ownership](images/ownership.png) |
| Trends Analysis | ![Trends](images/trends.png) |
| Sensitivity Analysis | ![Sensitivity](images/sensitivity.png) |

---

## Tools & Skills
**Tableau Desktop** • **Tableau Prep** • Data Blending • LOD Expressions • KPI Design • Sensitivity Analysis • Storytelling with Data • Healthcare Analytics

---

## Quick Links
- **Interactive Dashboard (Tableau Public)** → [View Dashboard](https://public.tableau.com/app/profile/jose.ayon3486/viz/HospitalQualityDashboardU_S_HospitalPerformanceInsights/MainInsights)  
- **Full Report (PDF)** → [Download Report](Hospital_Quality_Analysis_Report_JoseAyonWu.pdf)  
- **Author LinkedIn** → [Jose Ayon Wu](https://www.linkedin.com/in/joseayonwu)  

---

### License
Released under the [MIT License](https://opensource.org/licenses/MIT).  
© 2025 Jose Ayon Wu | Data Analytics Portfolio

---

*This project is for analytical and educational purposes only. Data and interpretations are illustrative and do not represent actual hospital outcomes.*
