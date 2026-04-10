# Social Media Sentiment & Engagement Analysis Dashboard

## 📊 Project Overview
This project focuses on the end-to-end analysis of social media sentiment and user engagement across three major platforms: **Facebook, Instagram, and Twitter**. As part of a data analytics initiative, I cleaned and processed a complex dataset of 732 entries to identify how emotional sentiments drive audience interaction globally.

The final output is an interactive Excel Dashboard that provides real-time KPIs and visual insights into emotional trends, geographical hotspots, and platform performance.

![Codveda Project Dashboard Screenshot](https://github.com/user-attachments/assets/58d3ee7d-43b1-4685-880a-8c4a4ea3db21)


## 🛠️ Technical Workflow
### 1. Data Cleaning & Pre-processing
* **Encoding Fixes:** Resolved UTF-8 artifacts and standardized emoji-based sentiment data.
* **Data Standardization:** Cleaned 'Platform' and 'Country' columns to remove trailing spaces and inconsistencies.
* **Feature Engineering:** Extracted `Day_Name`, `Month`, and `Hour` from timestamps to perform temporal analysis.
* **Categorization:** Mapped over 50 unique emotional labels into high-level sentiment buckets for clearer reporting.

### 2. Statistical Analysis
* **Cross-Tabulation:** Used Pivot Tables to correlate qualitative emotions with quantitative engagement metrics (Likes/Retweets).
* **Data Modeling:** Implemented Excel’s Data Model to calculate **Distinct Counts** for the Emotional Diversity Score.
* **KPI Calculation:** Developed formulas for the **Amplification Ratio** and **Net Sentiment Rate**.

## 📈 Key Insights
* **High Virality:** The project identified an **Amplification Ratio of 50%**, meaning every two likes resulted in one share, indicating highly resonant content.
* **Instagram Superiority:** Instagram emerged as the leader in total engagement ($17,464$ points), despite having a similar post volume to other platforms.
* **Mid-Week Peak:** Data shows that engagement peaks on **Wednesdays** ($110$ posts), suggesting a mid-week surge in social media activity.
* **Emotional Diversity:** The audience expressed **59 unique sentiments**, proving that the conversation is highly nuanced and multi-dimensional.

## 🚀 Recommendations
* **Regional Targeting:** Capitalize on "Adventure" and "Acceptance" content in the **UK and Belgium** markets where engagement hotspots were identified.
* **Content Scheduling:** Align major brand announcements with **February and August** (peak volume months) and post specifically on **Wednesdays** to maximize reach.

## 📂 Repository Structure
* `Analysis_Dashboard.xlsx`: The interactive Excel file containing the dataset, Pivot Tables, and Visualization.
* `Data/`: Folder containing the raw and cleaned CSV files.
* `Images/`: Screenshots of the final Dashboard.

## 👤 Author
**Agboola Emmanuel Ayodele** *Final-Year Statistics Student | Data Analyst Intern*

---
*Developed as part of the Codeveda Project and Industrial Training at UI-LISA.*
