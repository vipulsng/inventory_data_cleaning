# Inventory Data Cleaning

This project showcases inventory data cleaning and analysis using SQL-like queries in Python, all inside a Google Colab notebook.

## 🗂 Project Structure

- `notebook/` – Google Colab notebook with step-by-step cleaning & querying
- `Data/` – Raw product CSV file
- `Pdf/` – PDF version of the final notebook for quick viewing

---
## 📌 Project Summary

The dataset used in this project had several issues:
- Inconsistent product names (e.g., multiple variants of "Coca-Cola").
- Price inconsistencies.
- SKU mismatches.
- Repeated or disorganized records across multiple locations.

### ✅ Key Steps Performed:
1. **Loaded CSV data** using pandas.
2. **Standardized product names** (e.g., "Coke", "Cola" → "Coca-Cola 500ml").
3. **Standardized prices** (set all Coca-Cola 500ml prices to €2.5).
4. **Created a cleaned view** with standardized SKUs and product names.
5. **Visualized inventory stock** across hubs (locations).
6. **Identified top and bottom performing hubs** using automation.
7. **Exported cleaned dataset.**

---

## ▶️ How to Run the Notebook on Google Colab

To run the notebook yourself:

1. Download the following two files from this repository:
   - `notebook/inventory_data_cleaning.ipynb`
   - `Data/product.csv`

2. Go to [Google Colab](https://colab.research.google.com/).

3. Upload the notebook file.

4. Upload the CSV (`product.csv`) when prompted or use the upload button in Colab.

5. Run all the cells to follow along with the full cleaning and analysis process.

---

## 📄 View Without Running

If you just want to **view the analysis**, check out the PDF version in the Pdf folder.


## 🔧 Tools Used

- Python (pandas, pandasql)
- Google Colab
- Matplotlib/pandas built in plotting

---

## 👤 Author

Created by Vipul — feel free to fork or reuse this structure for similar data cleaning tasks!
