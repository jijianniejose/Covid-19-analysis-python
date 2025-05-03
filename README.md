# 🦠 COVID-19 Data Analysis & Forecasting

A complete data science project analyzing the global and India-specific impact of COVID-19 using real-world data. This project explores infection and recovery trends, builds predictive models, and visualizes insights with interactive charts.

![COVID-19 Trend](https://i.snipboard.io/35Qpij.jpg)

---

## 🚩 **Problem Statement**

Given COVID-19 data on confirmed cases, deaths, and recoveries:

✅ Analyze the trend of infection and recovery rates  
✅ Visualize the global and India-specific impact  
✅ Build a predictive model to forecast cases **1 week into the future**  
✅ Present insights with interactive, dynamic visualizations

---

## 📁 **Dataset**

The dataset includes multiple **CSV** and **Excel** files containing:

- Daily confirmed COVID-19 cases
- Death counts
- Recovery counts
- Global and India-specific data

(Data sourced from Johns Hopkins University and Ministry of Health & Family Welfare)

---

## 💻 **Project Workflow**

### 1️⃣ Data Collection & Preparation
- Load and combine multiple data files using **pandas**
- Handle missing values and inconsistencies
- Aggregate data by date and country/region

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualize daily trends in:
  - Confirmed cases
  - Death counts
  - Recovery counts
- Analyze **infection rate** and **recovery rate** over time
- Use **Plotly** to create interactive graphs

### 3️⃣ Predictive Modeling
- Build **time series forecasting models using Facebook Prophet**
- Forecast:
  - Confirmed cases
  - Deaths
  - Recoveries
- Generate **7-day future predictions**

### 4️⃣ Visualization of Predictions
- Overlay actual vs forecasted data
- Add confidence intervals to predictions
- Create interactive **forecast plots** combining **Plotly + Prophet**

---

## 🎯 **Key Insights**

✔️ Significant seasonal trend in global case rise  
✔️ Recovery rates lag infection rates by 2-3 weeks  
✔️ Forecast shows continued growth trend in absence of interventions  
✔️ Interactive visualizations provide actionable insights for policymakers

---

## 🖥️ **Technologies Used**

| Tools        | Purpose                     |
|--------------|-----------------------------|
| Python 3.x    | Programming language        |
| Pandas        | Data handling & cleaning    |
| Plotly        | Interactive visualizations   |
| Prophet       | Time series forecasting     |
| Jupyter       | Development environment     |

---

## 📊 **Visualizations**

![COVID-19 Forecast](https://i.snipboard.io/Fu1BIl.jpg)

*COVID-19 predicted confirmed cases for the next 7 days*

---
