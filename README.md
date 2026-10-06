# Tableau Complete Project End-to-End (Tutorial Project)

Welcome to the **Tableau Complete Project End-to-End** repository!<br>
This project walks through the complete process of data analysis and visualization in Tableau, starting with requirements analysis and ending with fully built dashboards that answer real business questions. It introduces core Tableau functions and tools through the process of building charts and dashboards.

---
## Tools
Tableau Public

---
## ⚙️Project Workflow
The project workflow for this project follows these steps:

![Tableau Project Workflow](docs/diagrams/tableau_project_workflow.png)

---
## 🗠Dashboard Preview
This project includes two connected dashboards: the **Sales Dashboard** and the **Customer Dashboard**. **Navigation icons** allow users to move seamlessly between the two views, while a **Filter icon** enables filtering by **year**, **product**, and **location**. Each dashboard compares **current year** performance against the **previous year**, with color-coded indicators highlighting **peak points**, **low points**, and underperforming areas.

Below are the dashboards built as part of this project.
View live dashboard by clicking on the image
### Sales Dashboard
[![Sales Dashboard](https://github.com/TheDataCubator/tableau_complete_project_e2e/blob/0b39ad81fdb60cfd2c300b7febb5a029aa9dc26e/docs/diagrams/Sales%20Dashboard.png)](https://public.tableau.com/shared/TWF5PPXX9?:display_count=n&:origin=viz_share_link)

### Customer Dashboard
[![Customer Dashboard](https://github.com/TheDataCubator/tableau_complete_project_e2e/blob/0b39ad81fdb60cfd2c300b7febb5a029aa9dc26e/docs/diagrams/Customer%20Dashboard.png)](https://public.tableau.com/shared/XWX7F8SWZ?:display_count=n&:origin=viz_share_link)

---
## 🗝️Key Insights

- **Total sales reached $733K in 2023**, up 20.36% year-over-year, while total quantity sold grew even faster at 26.83%, suggesting growth was driven more by volume than price increases.
- **Profit growth (14.24%) lagged behind sales growth (20.36%)**, indicating margins may be getting squeezed as the business scales.
- **Copiers generated the highest profit margin** among all subcategories, while **Tables, Machines, Bookcases, and Supplies all recorded losses** despite reasonable sales volume — a potential pricing or cost issue worth investigating further.
- **Phones led all subcategories by total sales volume**, making it the top revenue driver in 2023.
- **Customer base grew 8.62% to 693 customers**, but total orders grew faster at 28.29%, showing existing customers are ordering more frequently rather than growth being driven purely by new customer acquisition.
- **Nearly 58% of customers placed only 1–2 orders** in 2023 (400 out of 693), highlighting a potential opportunity to improve customer retention and repeat purchase rates.
- **Top customer Raymond Buch generated $6,781 in profit from just 3 orders** — the highest profit efficiency in the Top 10 list, compared to customers with more orders but lower profit per order.

---

## 💎Business Value

- Supports the Sales & Merchandising team in making pricing and inventory decisions by identifying underperforming subcategories.
- Helps the Marketing team improve customer retention strategies by highlighting low-frequency buyers.
- Strengthens account management efforts by helping the Sales team identify high-value customers to prioritize.
- Enables the Management/Executive team to proactively monitor performance through year-over-year and trend comparisons.
- Reduces manual reporting effort for the Operations/Analytics team through a centralized, interactive dashboard.

## Repository Structure
```
tableau_complete_project_e2e/
│
├── datasets/                    # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                        # Project documentation and architecture details
│   ├── diagrams/                # Dashboard images and project workflow diagrams
│   └── icons/                   # Icons used in the dashboards
│
├── analyze_requirements/        # Business requirements, color scheme, and project workflow
│
├── building_charts/             # Calculated field and tooltip formulas, organized by chart
│
├── building_dashboard/          # Information on assembling the final dashboards
│
├── README.md                    # Project overview and instructions
└── LICENSE                      # License information for the repository
```
---
## ✨Tip
### Saving File
For those using Tableau Public, it's recommended to change the data source connection from Live to Extract before saving, to avoid issues when reopening the file.

---
## 🔗Important Links & Tools:

- **[Clipchamp](https://clipchamp.com/en/windows-video-editor)**: video editor
- **[Datasets](datasets/sales-dashboard-project/datasets)**: Access to the project dataset(csv files).
- **[DrawIO](https://www.drawio.com/)**: Design data architecture, models, flows, and diagrams.
- **[Emojipedia](https://emojipedia.org/en)**: emoji and icon collections
- **[Git Repository](https://github.com/)**: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **[Tableau Public](https://www.tableau.com/access/download/public)**: Free tool for creating and publishing interactive data visualizations.

---
## Acknowledgements

This project was built following a Tableau Complete Project End-to-End tutorial by [Data With Baraa](https://www.youtube.com/@DataWithBaraa). I customized the color scheme for the Customer Dashboard(Green & Pink) versus Sales Dashboard (Blue & Orange), so users immediately notice the context shift when switching between the two views.

Another customization made on this dashboard was setting the sub-parameter to **Only Relevant Values** rather than All Values in Database, making the sub-filter dependent on the previous filter.

---
## License

This project is licensed under the [MIT LICENSE](LICENSE). You are free to use, modify, and share this project with proper attribution.

## About Me

Thanks for visiting! I'm **Mustafa**, an insurance operations professional on a mission to master data analytics and turn raw data into real insights.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mustafa-muntak)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/mustafa.muntak)
