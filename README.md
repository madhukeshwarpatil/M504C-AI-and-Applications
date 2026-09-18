# M504C-AI-and-Applications

Individual project for **M504 AI and Applications**: exploratory data analysis of a US multi-city retail extract.

The main deliverable is the Jupyter notebook `M504_Retail_EDA.ipynb`. An HTML export (`M504_Retail_EDA.html`) is included for reading without running the notebook.

## Files

| File | Purpose |
| --- | --- |
| `M504_Retail_EDA.ipynb` | Analysis notebook (open this in Jupyter, VS Code, or Cursor) |
| `M504_Retail_EDA.html` | Static browser view of the executed notebook |
| `retail_data.csv` | Dataset used by the notebook (200,000 rows × 19 columns) |

## Dataset

- **File:** `retail_data.csv` (200,000 rows × 19 columns)
- **Source:** [Kaggle — Retail Data](https://www.kaggle.com/datasets/abdurraziq01/retail-data) (Abdur Raziq Khan)
- Each row is treated as one purchase. The extract covers 10 US cities from 14 July 2020 to 14 July 2023.
- This is a public Kaggle extract used as a case study, not audited company accounts.

## How to view

1. Open `M504_Retail_EDA.ipynb` in Jupyter, VS Code, or Cursor.
2. Or open `M504_Retail_EDA.html` in a browser for a static copy.

The notebook expects `retail_data.csv` in the same folder.

## Analysis scope

The notebook covers data quality, preprocessing, and eight business questions:

1. Category margin, price positioning, and assortment
2. Discounting and recorded profitability
3. City-market profitability and foot traffic
4. Purchasing activity and recorded profit over time
5. Income groups and spending score
6. City-market marketing spend and recorded profit
7. Competitive pricing and recorded profit
8. Inventory, foot traffic, and recorded profit

Findings, caveats, and references are in the notebook.
