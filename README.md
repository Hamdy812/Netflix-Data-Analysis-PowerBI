````markdown
# 🎬 Netflix Data Analysis Dashboard

## 📌 Project Overview

This project presents an interactive **Netflix Content Analysis Dashboard** built using **Microsoft Power BI**.

The main goal is to analyze Netflix's content library and provide insights into content distribution, production countries, genres, content types, and release trends.

---

## 🎯 Project Objectives

The dashboard aims to answer key business questions such as:

- How large is Netflix's content library?
- What is the distribution between Movies and TV Shows?
- Which countries produce the most Netflix content?
- What are the most common genres?
- How has Netflix's content evolved over the years?
- How is Netflix's content distributed across different categories?

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **Microsoft Excel**
- **DAX**
- **Star Schema**
- **Data Cleaning & Transformation**
- **Data Visualization**

---

## 🧹 Data Preparation

The dataset was cleaned and transformed using **Power Query**.

The main preprocessing steps included:

- Handling missing values
- Removing duplicate records
- Cleaning text fields
- Splitting and transforming columns
- Formatting data types
- Extracting useful information from existing columns
- Creating calculated columns required for analysis

---

## ⭐ Data Modeling

A **Star Schema** was designed to improve the structure and performance of the Power BI model.

### Fact Table

- `FactNetflix`

### Dimension Tables

- `DimDate`
- `DimCountry`
- `DimGenre`

The model enables efficient analysis across different dimensions such as time, country, and genre.

---

## 📊 Dashboard

The dashboard provides interactive visualizations and KPIs covering:

### Netflix Overview

- Total Titles
- Total Countries
- Movie Percentage
- TV Show Percentage
- Content Growth Over Time

### Content Analysis

- Movies vs TV Shows
- Top Genres
- Content Distribution
- Release Trends

### Geographic Analysis

- Content by Country
- Top Content-Producing Countries
- Geographic Distribution of Netflix Titles

---

## 📈 Key Insights

The dashboard helps identify:

- The overall growth of Netflix's content library.
- The balance between Movies and TV Shows.
- Countries with the highest contribution to Netflix's catalog.
- The most popular content genres.
- Changes in content production and additions over time.

---

## 📷 Dashboard Preview

![Netflix Overview](Screenshots/dashboard_one.jpg)
![Content Analysis](Screenshots/dashboard_two.jpg)
![Geographic Analysis](Screenshots/Screenshot%202026-08-14%20002127.png)

---

## 📂 Project Structure

```text
Netflix-Data-Analysis-PowerBI/
│
├── Netflix_Dashboard.pbix
├── Netflix_Dataset.xlsx
├── README.md
│
└── Screenshots/
    ├── Netflix_Overview.png
    ├── Content_Analysis.png
    └── Geographic_Analysis.png
````

---

## 👨‍💻 Author

**Hamdy Osama**

Computer Science Student | Backend Development | Data Analysis | AI

* GitHub: [Hamdy812](https://github.com/Hamdy812)
* LinkedIn: [Hamdy Osama](https://www.linkedin.com/in/hamdy-osama)
* Portfolio: [hamdyportfolio.netlify.app](https://hamdyportfolio.netlify.app/)

---

## 📌 Note

This project was developed as part of my learning journey in **Data Analysis, Power BI, and Artificial Intelligence**.

```
```
