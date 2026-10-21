# data-science-project
CISC7204 Data Science Project
# Spatiotemporal Dynamics and Per Capita Distribution of 311 Noise Complaints Across New York City Boroughs in 2024

## 1. The Problem or Research Question
This project investigates urban quality-of-life dynamics in New York City by analyzing citizen-reported noise complaints submitted through the NYC 311 non-emergency service platform during the calendar year 2024. 
* **Core Research Question**: How do 311 noise complaint volumes, temporal patterns (hourly and day-of-week distributions), and per capita reporting rates differ across the five boroughs of New York City in 2024?

## 2. Dataset Source and Usage Permissions
* **Dataset 1**: NYC Open Data - 311 Service Requests from 2010 to Present (Accessed via Socrata Open Data REST API). Public domain open data for civic research.
* **Dataset 2**: U.S. Census Bureau - 2023 ACS 5-Year Population Estimates (Table B01003). Public domain demographic data used for per capita normalization.

## 3. Methods and Tools Used
* **Programming Language**: Python 3
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
* **Methods**: 
  - Data wrangling and API integration (merging 311 logs with Census population metrics).
  - Demographic normalization (computing complaints per 10,000 residents to eliminate population scale bias).
  - Temporal feature engineering (extracting hour of day and day of week).
  - Multi-panel visual encoding using Color Universal Design (CUD) principles.

## 4. Key Findings and One Limitation
* **Key Findings**: 
  - While absolute complaint counts are highest in densely populated boroughs (e.g., Brooklyn and Manhattan), per capita rates reveal unique suburban/urban environmental exposure differences.
  - Temporal heatmaps demonstrate distinct behavioral signatures, such as late-night weekend party spikes in commercial entertainment corridors versus early-morning weekday construction noise in residential zones.
* **Limitation**: 311 complaint records rely on voluntary citizen reporting, which can introduce reporting bias depending on civic engagement levels and digital literacy across different neighborhoods.

## 5. Instructions for Running the Analysis
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/liu0417hy-code/.data-science-project.git](https://github.com/liu0417hy-code/.data-science-project.git)
