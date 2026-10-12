#  Egypt GDP — Economic Intelligence Platform

<p align="center">
  <strong>Masr Economic Pulse</strong>
  <br />
  <em>An Economic Intelligence Platform for GDP Nowcasting in Egypt</em>
</p>

---

## 👥 Team Members

| Role | Name |
|:---|:---|
| **Team Leader** | Mohammed Saber Salama Radwan |
| Team Member | Ziad amr abdelmageed |
| Team Member | Elsayed ibrahem elbdwy |
| Team Member | Islam Mohammed Hassan |
| Team Member | Ali Ahmed AbdelAziz |

---

## 🎓 Instructor

**Dr. Amal Mahmoud**

---

## 📑 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Project Objectives](#-project-objectives)
- [🧭 Project Scope](#-project-scope)
- [📦 Final Deliverable](#-final-deliverable)
- [🗓️ Project Plan (5 Weeks)](#️-project-plan-5-weeks)

---

## 📌 Project Overview

**Masr Economic Pulse** is an economic intelligence platform designed to estimate Egypt's economic growth before official GDP figures become available. The project combines conventional economic indicators with alternative data sources, including Google Trends, satellite nighttime lights, and selected trade and maritime activity indicators, to investigate whether these sources can improve the timeliness and accuracy of GDP nowcasting.

Using Python and SQL, the team will collect, clean, validate, and organize historical data, then analyze economic patterns and develop baseline and machine learning models. The results will be presented through interactive Power BI and Tableau dashboards and a research report.

The platform is intended to support economic analysis and decision-making; its estimates will complement, not replace, official statistics.

---

## 🎯 Project Objectives

- Collect and prepare historical Egyptian GDP data and selected conventional and alternative economic indicators from accessible, documented sources.
- Explore economic trends, data quality, and relationships between GDP growth and indicators such as Google search interest and satellite nighttime lights.
- Develop and compare baseline and machine learning models for GDP nowcasting using chronological backtesting and appropriate error metrics such as MAE and RMSE.
- Communicate findings, model performance, data limitations, and the usefulness of alternative indicators through interactive dashboards and a documented research report.

---

## 🧭 Project Scope

### 1. 📥 Data Acquisition

Gather quarterly GDP figures and relevant economic indicators, Google Trends indices, satellite nighttime-light measurements, and suitable public trade or maritime activity indicators where data access permits.

### 2. 🗄️ Data Engineering and Database

Clean and standardize records, handle missing values and duplicates, document sources and observation dates, and store processed data and model results in SQL/PostgreSQL.

### 3. 📊 Economic and Exploratory Analysis

Examine economic trends, seasonality, indicator relationships, unusual observations, data coverage, and limitations, distinguishing correlation from causation.

### 4. 🤖 GDP Nowcasting and Evaluation

Create predictive features; establish baseline models; compare suitable regression, time-series, Random Forest, or gradient-boosting approaches where supported by the data; and evaluate them through chronological out-of-sample testing.

### 5. 📈 Business Intelligence and Reporting

Build interactive dashboards in Power BI and Tableau to display historical and estimated GDP growth, alternative indicators, model performance, and data quality, with findings and technical decisions documented.

---

## 📦 Final Deliverable

> A documented economic intelligence project containing a reproducible Python data workflow, a structured SQL database, an evidence-based comparison of baseline and alternative-data GDP nowcasting models, interactive Power BI/Tableau dashboards, a research and model-evaluation report, and technical documentation. Results will clearly communicate uncertainty and limitations, including the distinction between official quarterly GDP and any derived monthly series.

---

## 🗓️ Project Plan (5 Weeks)

### 🔹 Week 1 — Research, Data Sources & Project Setup

- Define the analysis questions and target GDP measure, review relevant economic indicators, and assess the accessibility, historical coverage, costs where applicable, and limitations of priority data sources.
- Identify available official GDP statistics and suitable alternative datasets; set up the Python environment and project structure.

### 🔹 Week 2 — Data Collection, Cleaning & Exploratory Analysis

- Collect available data, clean missing or duplicated records, standardize dates and units, record source metadata, and store the structured data in SQL/PostgreSQL.
- Perform exploratory data analysis to inspect trends, seasonality, relationships, data gaps, and potential anomalies.

### 🔹 Week 3 — Feature Engineering & Baseline Models

- Create relevant predictive features, such as growth rates, lagged indicators, and rolling statistics, while avoiding information from future periods.
- Establish suitable baseline models and develop initial GDP nowcasting models using the data available and the size of the dataset.

### 🔹 Week 4 — Model Testing, Comparison & Interpretation

- Compare candidate models using chronological training and testing periods that reflect realistic data publication delays and availability.
- Evaluate results using metrics such as MAE and RMSE, assess the contribution of alternative indicators, and document errors, limitations, and whether improvements are reproducible.

### 🔹 Week 5 — Dashboards, Reporting & Final Presentation

- Build and refine Power BI and Tableau dashboards covering economic activity, alternative data, indicator relationships, model performance, and data quality.
- Complete the research report, technical documentation, and final presentation, clearly stating the findings and limitations of the estimates.

---

<p align="center">
  <strong>Masr Economic Pulse</strong>
  <br />
  <em>Turning Economic Data into Timely Insights.</em>
</p>
