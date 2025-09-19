# 🏡 Magicbricks - Ready to Move Flats Data Analysis

Welcome to the **Magicbricks Ready to Move Flats** data analysis repository!  
This project dives into real estate listings sourced from [Magicbricks.com](https://www.magicbricks.com/), focusing on **ready-to-move properties** across various Indian cities.

We explore trends, visualize key metrics, and generate actionable insights to understand the real estate market better.

---

## 📂 Project Structure


---

## 🔍 Objectives

- Perform **Exploratory Data Analysis (EDA)**.
- Visualize distribution of:
  - 📍 Locations
  - 🛏️ BHK Types
  - 💸 Prices
  - 🛋️ Furnishing Status
  - 🏢 Property Types
- Export findings into a detailed Excel report.

---

## 🧪 Tools & Libraries

- `Python 3.x`
- `pandas`
- `matplotlib`, `seaborn`
- `Jupyter Notebook`
- `openpyxl` / `xlsxwriter`

---

## 📊 Dataset Overview

| Feature         | Description                                        |
|-----------------|----------------------------------------------------|
| `BHK`           | Number of bedrooms                                 |
| `Price`         | Price of the property in INR                       |
| `Location`      | Area/Locality of the listing                       |
| `Furnishing`    | Furnishing status (Furnished, Semi, Unfurnished)   |
| `Area`          | Property size in sq.ft                             |
| `Property Type` | Type of listing (Apartment, Villa, etc.)           |

> 📎 *Note:* Data was scraped from Magicbricks.com (public listings)

---

## 📈 Key Insights

✔️ Most popular configuration: **2BHK & 3BHK**  
✔️ Furnishing status: Majority are **semi-furnished**  
✔️ Location clusters have significant price variation  
✔️ Outlier prices exist — **median** is often more useful than average

📌 All insights are visualized and exported in the `graphs/` and `summary/` folders.

---

## 📁 Outputs

- 📊 Visual Graphs: `graphs/`
- 📒 EDA Notebook: `notebooks/eda_analysis.ipynb`
- 📄 Excel Report: `summary/property_summary.xlsx`

---

## 🚀 Future Enhancements

- Integrate **price prediction model** (Linear Regression, XGBoost, etc.)
- Add **interactive dashboards** using Plotly or Streamlit
- Include **map-based visualizations** (using Folium)

---

## 🙋‍♂️ Author

**Prashant Mhaske**  
🔗 [LinkedIn](https://www.linkedin.com/in/prashant-mhaske-715b24207)
