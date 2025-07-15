# Optimising NHS GP Appointments: Utilisation, Capacity & Attendance

**Author: Suleiman Chun Lum Andy Ho**  
LSE – Career Accelerator Data Analytics

This project investigates patterns in General Practitioner (GP) appointments across the UK’s National Health Service (NHS), with a focus on appointment attendance, capacity strain, and strategic recommendations for better resource utilisation.

---

## Objectives

- Understand how GP appointment usage varies over time and across regions.
- Analyse how appointment mode, wait times, and regional differences affect attendance.
- Quantify NHS staff-to-patient capacity using GP-FTE (full-time equivalent) data.
- Provide actionable recommendations to boost utilisation and service efficiency.

---

## Key Insights

- **Appointments peak on Mondays** and steadily decline through the week.
- **Telephone appointments** rose during COVID and have consistently higher attendance rates than face-to-face appointments.
- **Patient-to-GP-FTE ratios are rising**, exceeding the ideal 1000:1 standard in most regions.
- Longer wait times **negatively affect attendance**, especially for in-person visits.

---

## Data Sources

- NHS Digital: [General and Personal Medical Services](https://digital.nhs.uk/data-and-information/publications/statistical/general-and-personal-medical-services)
- NHS region code mapping: [ONS Geoportal](https://geoportal.statistics.gov.uk/)
- Booster campaign reference: [NHS News](https://www.england.nhs.uk/2021/09/nhs-begins-covid-19-booster-vaccination-campaign/)
- BMA workforce benchmark: [Pulse Today](https://www.pulsetoday.co.uk/news/workload/gpc-england-vision-sets-goal-of-one-gp-per-1000-patients-by-2050/)

---

## Project Structure

/data/ # Cleaned NHS appointment and GP workforce data
/scripts/ # Python scripts for cleaning, validation, and visualisation
/visualisations/ # PNGs and charts (e.g., appointment trends, attendance rates)
/report/ # PDF technical report
README.md

---

## Tools Used

- **Python** (pandas, matplotlib, seaborn)
- Excel (for early exploration and inspection)
- Jupyter notebooks
- NHS public data sources

---

## Sample Visualisations

> (After uploading, use: `![Figure description](images/filename.png)`)

- Appointments by Day of Week  
- Mode of Appointment (Face-to-Face vs Telephone)  
- Attendance by Wait Time and Region  
- GP-FTE Capacity Analysis (Patients per GP)  

---

## Recommendations

| Recommendation                                                | Impact        |
|---------------------------------------------------------------|---------------|
| Prioritise staff coverage early in the week                   | High          |
| Promote telephone appointments where appropriate              | High          |
| Minimise time between booking and appointments                | High          |
| Enable patient load sharing across GP practices by region     | Medium        |
| Explore satisfaction and appointment length vs. quality       | Medium        |
| Further investigate social media indicators (e.g. Twitter)    | Low           |

---

## Author

**Suleiman Chun Lum Andy Ho**  
[LinkedIn](https://www.linkedin.com/in/scla-ho/) | `@CLAHO` on GitHub

---

## References

- NHS Digital
- ONS Geoportal
- England NHS Booster Campaign
- Pulse Today / British Medical Association (BMA)

