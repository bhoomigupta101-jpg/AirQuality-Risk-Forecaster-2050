# AirQuality-Risk-Forecaster-2050
End-to-end data engineering and predictive modeling project. Features a rigorous sanitization pipeline that resolved 3,900+ metadata duplicates and leveraged regional mean imputation for dataset continuity. Includes an interactive executive dashboard for visualizing long-term AQI trajectories and systemic carbon transition risks.

# Global Carbon Transition Engine: 2050 Air Quality Risk Projections

## 📊 Executive Summary
A quantitative risk assessment analyzing **40,000+ data points** from the 2024 WHO Ambient Air Quality Database. This engine projects a **67% escalation** in global pollution by 2050, identifying **2,031 cities** as high-risk assets.

## 🛠 Methodology (The Technical "How")
The analysis followed a rigorous data engineering pipeline:
1. **Data Sanitization:** Executed cross-field deduplication to remove **3,900+ redundant entries** in the WHO V6.1 (2024) metadata.
2. **Missing Value Imputation:** Utilized **Regional Mean Imputation** to handle data gaps across PM10 and NO2 variables, ensuring statistical continuity.
3. **Predictive Modeling:** Applied a **Linear Growth Projection** based on historical CAGR (2010–2024) to forecast air quality trajectories through 2050.
4. **Risk Scoring:** Developed a custom **AQI Threshold Algorithm** to categorize cities into four distinct risk tiers.

## 📈 Key Findings
* **The 2050 Risk Delta:** Forecasts indicate a systemic shift from a global mean AQI of 63 to a projected 67% increase in severity by mid-century.
* **Asset Exposure:** 2,031 urban centers are classified as "Critical Risk," where AQI levels are projected to consistently exceed safety thresholds.

## 💻 Tech Stack
* **Excel:** Advanced Scenario Modeling, Pivot Engine, and UI/UX Dashboard.
* **Data Source:** WHO Ambient Air Quality Database - Update Jan 2024.
