# BA775-Animal-Shelter-Data-Analysis

This project explores multi-year intake and outcome trends from the Austin Animal Center using BigQuery SQL, Jupyter, and Tableau. Leveraging Google Cloud, the analysis examines intake reasons, adoption patterns, and operational inefficiencies to produce data-driven insights and recommendations for improving shelter performance.

---

## Project Overview

Using cloud-based tools and SQL-driven analysis, this project investigates:

- Trends in animal intakes and outcomes across multiple years  
- The most common intake reasons by animal type  
- Adoption rates and changes in outcome behaviors over time  
- Intake vs. outcome balancing and operational bottlenecks  
- Geographic and species-level patterns influencing shelter outcomes  
- Recommendations to support adoptions, reduce repeat intakes, and improve resource planning  

The project includes a comprehensive SQL notebook in BigQuery, an interactive Tableau dashboard, a final slide deck, and a concise summary of actionable insights.

---

## Features

- Full SQL-based data cleaning and transformation  
- Exploratory Data Analysis (EDA) covering trends, distributions, and species behaviors  
- Advanced SQL techniques including joins, window functions, aggregation, and CTEs  
- Interactive Tableau dashboard visualizing KPIs and trends  
- Executive summary, recommendations, and limitations  
- Cloud-native workflow using Google BigQuery and Jupyter  

---

## Repository Structure

```
├── README.md # Project documentation
├── BA775_teamA02.ipynb # Final notebook with SQL queries and analysis
├── dashboard_screenshots/ # Tableau dashboard images
└── A02-Presentation.pdf # Final project slide deck
```

---

## Key Insights

- Dog intakes show higher repeat rates, suggesting a need for stronger post-adoption support.  
- Stray intakes—especially in areas like Levander Loop—drive significant operational load.  
- Adoption rates improved over time, with outcomes increasingly outpacing intakes in several years.  
- Intake reasons vary by species, with dogs most often entering as strays and cats more frequently surrendered.  
- Seasonal and species-level patterns highlight opportunities for targeted outreach and resource planning.

---

## How to Run the Notebook

1. Open the `.ipynb` file in **JupyterLab** or **Google Colab**.  
2. Ensure access to **Google BigQuery**.  
3. Update the project and dataset names in the notebook setup cell:

   ```python
   project_id = "YOUR_PROJECT_ID"
   dataset_id = "animal_shelter"
4. Run all cells in order.
The notebook is fully SQL-based—no local data files required.

---

## Tableau Dashboard

You can view the interactive dashboards here:  
🔗 **Tableau Public:** 
1) https://public.tableau.com/app/profile/yuyang.zhai6198/viz/TeamA02/dataoverview?publish=yes
2) https://public.tableau.com/app/profile/yuyang.zhai6198/viz/TeamA02-dashboard2/IntakeOutcomeBehaviorAnalytics

Screenshots of the dashboard are included in the `dashboard_screenshots/` folder.

---

## Dependencies
- Cloud Tools  
- Google BigQuery  
- Google Cloud Platform (GCP)  
- Jupyter Notebook / Google Colab  
- Optional Python packages (if running locally):  
  - google-cloud-bigquery  
  - pandas  
  - matplotlib

---

### Contributors

Erin Zhai (Project Manager), Bill Odiase, Angela Liou, Shon Shaju, Allen Chiu  
This project was completed by Team A02 for BA775 – Business Analytics Toolbox

---

## License

This project may be shared under the MIT License, or another license of your choice.
If you would like a license file generated, I can create it for you.

---

## Generative AI Disclosure

We used Generative AI tools (including ChatGPT) to support non-analytical tasks such as refining markdown text, improving clarity in explanations, and assisting with formatting. AI was also used to help debug minor SQL syntax issues and suggest clearer narrative structure for summaries and recommendations. All analysis, SQL queries, interpretations, and final decisions were independently reviewed and validated by the team.

---

## Acknowledgments

Boston University MSBA BA775 - Business Analytics Toolbox  
Special thanks to Professor Mohammad Soltanieh-ha for guidance and course instruction  
Data Source: Austin Animal Center Open Data Portal  
Tools: BigQuery, Google Cloud, Jupyter, Tableau  
