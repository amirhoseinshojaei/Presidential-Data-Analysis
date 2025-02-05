# US Presidents Data Analysis Project

This project is focused on cleaning, transforming, and analyzing a dataset of US Presidents to extract meaningful insights and build an interactive dashboard.

## Tasks Completed:

### 1. Data Cleaning:
- **Removed unnecessary columns**: Deleted columns that were not relevant to the analysis.
- **Applied `TRIM` and `PROPER` functions**: Cleaned and standardized the text data in the `president`, `prior`, `party`, and `vice` columns.
  
### 2. Data Transformation:
- **Converted `salary` column to numeric**: The salary column was converted into a numeric format for database compatibility.
- **Fixed data types in `date updated` and `date created` columns**: Identified different data types and standardized them as short date formats using the `TEXT` formula.

### 3. New Columns Created:
- **Networking Days**: Used the `NETWORKDAYS` formula to calculate the number of working days between two dates for each entry.

### 4. Removed Duplicates:
- **Deleted duplicate entries**: Ensured that there were no duplicate rows in the dataset.

### 5. Pivot Tables & Pivot Charts:
- **Created Pivot Tables**: 
  - Sum of salary per party
  - Sum of salary per vice
  - Sum of networking days per president
  - Count of presidents per party
  - Count of vice presidents per party
- **Generated Pivot Charts**: Visualized the above Pivot Tables in dynamic charts.

### 6. Dashboard Creation:
- **Created a professional and dynamic dashboard**: The dashboard provides an interactive overview of key metrics, including salaries, networking days, and party statistics. This dashboard is stored as an image and will be included in this repository.

## Technologies Used:
- Microsoft Excel
- Pivot Tables & Pivot Charts
- Excel Formulas: `TRIM`, `PROPER`, `TEXT`, `NETWORKDAYS`
  
## Dashboard Preview:
![Dashboard Preview](path_to_dashboard_image.jpg)

## Conclusion:
This project demonstrates how data cleaning, transformation, and analysis can be applied to a dataset to extract valuable insights. The final result is a dynamic dashboard that presents the data in a meaningful and easily accessible format.

---

### **Run the project:**
1. Download the dataset from Kaggle (US Presidents dataset).
2. Open the dataset in Excel.
3. Apply the steps outlined above to replicate the process.
4. Customize the dashboard for further analysis.

