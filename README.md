# Data-Analysis-using-Excel
# 🏡 Kildare House Prices Analysis (2010–2020)

This project analyzes the residential property transactions in **County Kildare, Ireland**, from 2010 to 2020 using **Excel** and **Power Query**. The data was sourced from the official Irish Residential Property Price Register.

---

## 📊 Tools & Technologies

- Microsoft Excel (Power Query, Pivot Table, Dashboard)
- VBA (for data cleaning and transformation)
- Fuzzy Matching for town name correction
- Data Visualization (Pivot Charts & Dashboard)

---

## 📁 Project Structure

| Folder/File            | Description                                      |
|------------------------|--------------------------------------------------|
| `data/raw/`            | Original CSV files (2010–2020)                   |
| `data/cleaned/`        | Cleaned dataset with extracted town names        |
| `dashboard/`           | Final Excel dashboard showing trends and stats   |
| `README.md`            | Project documentation                            |

---

## 🧹 Data Cleaning Steps

1. Combined multiple CSVs using **Power Query**
2. Removed duplicates and irrelevant columns
3. Extracted **Year** from the sale date
4. Cleaned and standardized **Price** fields
5. Extracted **Town** from address using **VBA**
6. Applied **Fuzzy Matching** to correct town names

---

## 📈 Dashboard Insights

The dashboard includes:

- Year-wise trend of average house prices
- Most expensive and affordable towns
- Volume of transactions over time

📸 *![image](https://github.com/user-attachments/assets/6b2b5186-9ab3-4e13-89ed-5a35a6ca8eb4)
*

---

## 🚀 How to Use

1. Open the Excel file in `dashboard/`
2. Use slicers to filter by year or town
3. Explore the Pivot Tables and Charts for insights

---

## 💡 Future Improvements

- Use Power BI/Tableau for interactive dashboards
- Integrate SQL/PostgreSQL for storing data
- Automate the process fully using Python + Excel + Power BI

---

## 📜 License

This project is open-source and free to use for educational purposes.
