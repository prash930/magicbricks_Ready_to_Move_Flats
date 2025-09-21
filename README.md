# 🏡 Magicbricks — Ready to Move Flats Data Analysis

## 🚩 Overview

This project analyzes ready-to-move residential listings from Magicbricks.com. The analysis is done using cleaned data, with trends visualized and a Power BI dashboard created to present the key insights.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) on ready-to-move property listings.
* Visualize distributions of: Locations, BHK types, Prices, Furnishing status, Bathrooms, Floor metrics, etc.
* Create a Power BI dashboard for interactive exploration.

---

## 📊 Dataset Overview

Cleaned data is stored as **`data_.csv`**. All EDA and dashboard work is done using this file.

| Feature            | Description                                                         |
| ------------------ | ------------------------------------------------------------------- |
| `Area_sqft`        | Carpet/built-up area of the property in square feet                 |
| `Property_BHK`     | Number of bedrooms (standardized from raw BHK text)                 |
| `Furnished_Status` | Furnishing status → `Furnished`, `Semi-Furnished`, `Unfurnished`    |
| `Bathroom`         | Number of bathrooms                                                 |
| `Society`          | Society / Housing complex name (if available, else `NaN`)           |
| `Price_(lacks)`    | Price of the property in lakhs (numeric, cleaned from raw INR text) |
| `House_floor`      | The floor on which the flat/house is located                        |
| `Building_floor`   | Total number of floors in the building                              |
| `Floor_Category`   | Categorized floor level → `Low-rise`, `Mid-rise`, `High-rise`       |

---

## 🧰 Dependencies

* Python 3.x
* pandas
* matplotlib
* seaborn
* Jupyter Notebook / Lab

Install via:

```bash
pip install pandas matplotlib seaborn jupyterlab
```

---

## 🛠 Usage

1. Clone the repo:

   ```bash
   git clone https://github.com/prash930/magicbricks_Ready_to_Move_Flats.git
   cd magicbricks_Ready_to_Move_Flats
   ```

2. Load cleaned data:

   ```python
   import pandas as pd

   df = pd.read_csv("data_.csv")
   print(df.head())
   ```

3. Run notebooks (`magicbricks_Ready_to_Move_Flats.ipynb`, etc.) to see EDA.

4. Open and use the Power BI file: `MagicBricks_ready_to_move_falts_dashboard.pbix` for interactive dashboard view.

---

## 🗂 Project Structure

```
.
├── data_.csv                            # Cleaned dataset
├── magicbricks_Ready_to_Move_Flats_50_Pages.csv  # Raw scraped dataset
├── notebooks/
│   ├── magicbricks_Ready_to_Move_Flats.ipynb     # EDA analyses
│   └── anysis (1).ipynb                            # Other notebook(s)
├── dashboard/
│   └── MagicBricks_ready_to_move_falts_dashboard.pbix  # Power BI dashboard
├── README.md
```

---

## 📈 Key Insights

* 2BHK & 3BHK are the most common property types
* Most flats are **semi-furnished**
* Properties are mostly in **low-rise** and **mid-rise** categories
* Large price variation across different localities
* Median price is more meaningful than the mean due to presence of outliers

---

## 📁 Outputs

* Power BI dashboard: `dashboard/MagicBricks_ready_to_move_falts_dashboard.pbix`
* Clean dataset: `data_.csv`
* Raw dataset: `magicbricks_Ready_to_Move_Flats_50_Pages.csv`
* Jupyter notebooks with EDA: in `notebooks/`
---

## 📝 Conclusion

From the EDA and Power BI dashboard, several clear patterns emerge in the ready-to-move flats dataset:

* **2BHK and 3BHK flats dominate** the listings, indicating strong buyer and seller interest in mid-sized homes.
* **Semi-furnished flats** form the majority, showing that buyers prefer some level of furnishing while keeping flexibility for customization.
* **Floor distribution** highlights that most properties are concentrated in **low-rise and mid-rise categories**, making them more accessible and affordable compared to high-rise options.
* **Price variation is highly location-dependent** — the same BHK type can have drastically different prices depending on the locality, confirming the importance of geography in real estate decisions.
* **Outliers in price** are present, and thus **median values** provide a more reliable representation of market trends compared to averages.

Overall, the cleaned dataset and dashboard provide a **clear snapshot of the Indian real estate market for ready-to-move flats**. These insights can help both buyers and sellers understand prevailing trends, while also laying the foundation for predictive modeling and deeper market intelligence in future work.

---

## 👨‍💻 Author

**Prashant Mhaske**
LinkedIn: [https://www.linkedin.com/in/prashant-mhaske-715b24207](https://www.linkedin.com/in/prashant-mhaske-715b24207)
