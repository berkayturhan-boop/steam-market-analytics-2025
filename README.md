# 🎮 Steam Market Analytics & Price Prediction 2025

![Project Banner](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python) ![BigQuery](https://img.shields.io/badge/Google_Cloud-BigQuery-yellow?style=for-the-badge&logo=googlecloud) ![dbt](https://img.shields.io/badge/dbt-Data_Modeling-orange?style=for-the-badge)

<p align="center">
  <img src="header_image.png" alt="Steam Price Prediction AI Interface" width="100%">
</p>

This project is an **End-to-End Data Science & Engineering** study conducted by **Team 6**, utilizing the Steam 2025 dataset (240,000+ games) to analyze market trends and predict optimal game pricing.

## 🔗 Quick Access (Live Demo & Docs)

Explore the interactive dashboards, project management, and data architecture directly via the links below:

| Platform | Content | Access Link |
|----------|--------|------|
| 📊 **Dashboard** | Live Report (Looker Studio) | [👉 View Dashboard](https://lookerstudio.google.com/reporting/14eafbaa-cbb1-4a15-baf2-8e5f128a12e3) |
| 📝 **Notion** | Task Management & Process | [👉 View Notion Workspace](https://amazing-journey-b60.notion.site/2bdcf832f671801bbc18fc2105b09106?v=2bdcf832f67181ce8d3b000c2d86aca0&source=copy_link) |
| 🗺️ **Schema** | Data Architecture (tldraw) | [👉 View Architecture](https://www.tldraw.com/f/A1G0ucpf2pwONYo6cEshK?d=v-660.343.2143.1220.page) |

---

## 📌 Project Overview

**Objective:** To decode pricing dynamics in the gaming industry, analyze historical market trends, and develop Machine Learning models that predict the "ideal market price" of a game based on its technical and categorical features.

### 🛠️ Tech Stack
The project follows **Modern Data Stack** principles within a cloud-based architecture:

* **Data Engineering & Storage:**
    * 🔵 **Google BigQuery:** Data Warehouse (Centralized storage for raw and processed data).
    * 🛠 **dbt Cloud:** Data Modeling (Transformation flow: Staging → Intermediate → Mart).
* **Data Science & Analytics:**
    * 🐍 **Python & SQL:** EDA (Exploratory Data Analysis), Data Cleaning, Feature Engineering.
    * 📓 **Google Colab:** Cloud-based development environment.
* **Visualization & Management:**
    * 📊 **Looker Studio:** Interactive dashboards for end-users.
    * 📅 **Notion & Slack:** Agile project management and sprint tracking.

---

## 💻 Development & Code

You can access the source code and development notebooks directly in this repository:

* [📍 **Market Trends Analysis (Time Series)**](./Model_1_Pazar_Tahmini.ipynb)
    * *Analysis of market growth, release frequency, and indie developer trends.*
* [📍 **Price Prediction Model (ML)**](./Steam_Oyun_Fiyatı_Tahminlemesi_Modeli.ipynb)
    * *Regression model predicting game prices based on hardware requirements and genre.*

*(Original Development Environment: [Colab Notebook - Atakan](https://colab.research.google.com/drive/1aIPNEOXNLj3kggDIEiEE3CWWAM_HHg_3?usp=sharing))*

---

## 📊 Key Data Insights

Based on EDA and ML modeling performed on 240k+ games:

1.  **💰 Inflationary Pressure:** Between 2021-2025, the average game price increased by over **22%**.
2.  **🖥️ Hardware Costs:** Games requiring "High" system specs are priced **~60% higher** than the market average.
3.  **📉 Price-Quality Paradox:** There is a weak positive correlation (**0.23**) between Price and Metacritic scores. *Higher price does not guarantee higher player satisfaction.*
4.  **🚀 Exponential Saturation:** The market is growing exponentially, making "discoverability" the primary challenge for Indie developers.

---

## 👥 The Team (Team 6)

This project was developed during the **Workintech Data Science Bootcamp**:

* **Atakan Can** (EDA, BigQuery Integration, ML Modeling) - [LinkedIn](YOUR_LINKEDIN_LINK_HERE)
* **Berkay Turhan** - [LinkedIn](https://www.linkedin.com/in/rberkayturhan/)
* **Tümay Turhan**
* **D. Hazal Tuncay**

---
