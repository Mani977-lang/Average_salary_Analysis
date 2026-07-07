# 💼 Data & AI Jobs Salary Dashboard

An interactive Tableau dashboard analyzing global salaries across data, AI, and machine learning roles — exploring how compensation varies by experience level, employment type, company size, location, and job title.

![Dashboard Preview](dashboard_preview.png)

## 📊 Overview

This dashboard provides a comprehensive view of the global data & AI job market, helping job seekers, recruiters, and analysts understand salary trends across different dimensions such as:

- Experience level (Entry, Intermediate, Senior, Expert)
- Employment type (Full-Time, Part-Time, Contract, Freelance)
- Company size and location
- Country-wise average compensation
- Job title-specific salary breakdowns

## 🖼️ Dashboard Features

| Visual | Description |
|---|---|
| **Average Salary by Experience & Employment Type** | Scatter plot comparing salary ranges across experience levels and contract types |
| **Total Companies by Size & Location** | Donut chart showing company distribution (Small, Medium, Large) |
| **Map: Average Salary by Country** | Choropleth map visualizing average USD salary across countries |
| **Experience Level** | Donut chart of workforce distribution by seniority |
| **Employment Type** | Donut chart showing Full-Time vs. Part-Time vs. Freelance vs. Contract split |
| **Top 10 Employee Residence** | Bar chart of top countries by employee count |
| **Average Salary by Job Title & Experience Level** | Detailed table with color-coded salary heatmap per role |

## 🎛️ Filters

- **Company Location** — filter all visuals by country
- **Job Title** — filter all visuals by specific role

## 🛠️ Tools & Technologies

- **Tableau Desktop** — dashboard design and data visualization
- **Tableau Calculated Fields** — measures (average salary, percentages, aggregations)
- **Tableau Prep / manual cleaning** — data preparation and transformation
- **Mapbox / OpenStreetMap** — geographic map visualization

## 📁 Repository Structure

```
├── data/
│   └── salaries.csv              # Source dataset
├── dashboard/
│   └── salary_dashboard.twbx      # Tableau packaged workbook
├── images/
│   └── dashboard_preview.png      # Dashboard screenshot
└── README.md
```

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `dashboard/salary_dashboard.twbx` in **Tableau Desktop** (or view it on Tableau Public if published)
3. Refresh the data source if prompted
4. Explore the dashboard using the filters at the top

## 📌 Key Insights

- The majority of employees work **Full-Time** roles (~97%)
- **Medium and Large** companies dominate the dataset (~86% combined)
- The **US** has by far the highest number of employees represented
- **Senior-level** professionals make up the largest experience segment
- Salaries vary significantly by country, ranging from **$4,000 to $157,500** on average

## 📄 Dataset

The dataset includes job title, experience level, employment type, salary (in USD), company location, company size, and employee residence for data & AI roles.

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome! Feel free to open an issue or submit a pull request.

## 📃 License

This project is licensed under the [MIT License](LICENSE).
