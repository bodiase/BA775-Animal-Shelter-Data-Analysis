# BA775-Animal-Shelter-Data-Analysis
This project explores multi-year intake and outcome trends from the Austin Animal Center using BigQuery SQL, Jupyter, and Tableau. Leveraging Google Cloud, the analysis examines intake reasons, adoption patterns, and operational inefficiencies to produce data-driven insights and recommendations for improving shelter performance.

---

## 📌 Project Overview

Using cloud-based tools and SQL-driven analysis, this project investigates:

- Trends in animal intakes and outcomes across multiple years  
- The most common intake reasons by animal type  
- Adoption rates and changes in outcome behaviors over time  
- Intake vs. outcome balancing and operational bottlenecks  
- Geographic and species-level patterns influencing shelter outcomes  
- Recommendations to support adoptions, reduce repeat intakes, and improve resource planning  

The project includes a comprehensive SQL notebook in BigQuery, an interactive Tableau dashboard, a final slide deck, and a concise summary of actionable insights.

---

## 🚀 Features

- Full SQL-based data cleaning and transformation  
- Exploratory Data Analysis (EDA) covering trends, distributions, and species behaviors  
- Advanced SQL techniques including joins, window functions, aggregation, and CTEs  
- Interactive Tableau dashboard visualizing KPIs and trends  
- Executive summary, recommendations, and limitations  
- Cloud-native workflow using Google BigQuery and Jupyter  

---

## 📁 Repository Structure
/
├── BA775_teamA02.ipynb # Final notebook with SQL queries and analysis
├── A02-Presentation.pdf # Final project slide deck
├── dashboard_screenshots/ # Tableau dashboard images
└── README.md # Project documentation

---

## ▶️ How to Run the Notebook

1. Open the `.ipynb` file in **JupyterLab** or **Google Colab**.  
2. Ensure access to **Google BigQuery**.  
3. Update the project and dataset names in the notebook setup cell:

   ```python
   project_id = "YOUR_PROJECT_ID"
   dataset_id = "animal_shelter"
4. Run all cells in order.
The notebook is fully SQL-based—no local data files required.

📦 Dependencies
Cloud Tools
Google BigQuery
Google Cloud Platform (GCP)
Jupyter Notebook / Google Colab
Optional Python packages (if running locally):
google-cloud-bigquery  
pandas  
matplotlib  

🙌 Contributors
This project was completed by Team A02 for BA775 – Business Analytics Toolbox at Boston University.
Contributors
Bill Odiase
Erin Zhai (Project Manager)
Angela Liou
Allen Chiu
Shon Shaju
Special thanks to Professor Mohammad Soltanieh-ha for guidance and course instruction.
Data Source: Austin Animal Center Open Data Portal
Tools: BigQuery, Google Cloud, Jupyter, Tableau

📄 License
This project may be shared under the MIT License, or another license of your choice.
If you would like a license file generated, I can create it for you.

💬 Acknowledgments
Austin Animal Center Open Data Portal
Google Cloud Platform
Tableau Public
BA775 Teaching Team
