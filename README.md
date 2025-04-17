# 🏠 Airbnb Data Analysis 📈

This repository presents a detailed Exploratory Data Analysis (EDA) of Airbnb listing data in New York City. The goal is to uncover patterns in pricing, room types, host verification, neighborhood trends, and review behavior.

## 📁 Project Structure

- `Airbnb_Data_Analysis.ipynb`: Main Jupyter Notebook containing code and visualizations.
- `README.md`: Project overview and usage instructions.

## 📌 Objective

To explore and visualize Airbnb data to answer key business questions such as:
- What room types are most common?
- Which neighborhoods have the most listings?
- How does pricing vary with room type?
- How have reviews changed over time?

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Seaborn 🎨

## 🔍 Key Insights

- **Room Types**:
  - *Entire home/apt* is the most common, followed by *private rooms*.
  - *Shared rooms* and *hotel rooms* are least common.

- **Neighborhoods**:
  - Most listings are in *Manhattan* and *Brooklyn*.
  - *Queens* has moderate activity, while *Bronx* and *Staten Island* have the least.

- **Pricing**:
  - *Entire homes* have the highest price variation and outliers.
  - *Shared rooms* are the most affordable and consistent.
  
- **Review Trends**:
  - Reviews steadily grew till 2019, dropped sharply in 2020 (COVID-19), and show signs of recovery in 2022.

## 📉 Visualizations

- Histograms for price and room type distribution
- Count plots for neighborhood groupings
- Boxplots showing price variation by room type
- Line chart tracking reviews over time

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airbnb-data-analysis.git
   cd airbnb-data-analysis
