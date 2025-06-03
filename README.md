# Vrinda-Store-Analysis-Report
Comprehensive data analysis of Vrinda Store sales and customer behavior using Excel datasets.   Includes insights on sales trends, demographics, order status, and channel performance.

# Create a README file content
readme_content = """
# Vrinda Store Data Analysis

## 📁 Project Overview
This project involves comprehensive data analysis of the Vrinda Store's sales and customer behavior using provided Excel datasets. The goal is to extract actionable insights from sales, orders, customer demographics, and channel performance.

---

## 📊 Datasets Included
The Excel file `Vrinda Store Data Analysis.xlsx` contains the following sheets:

1. **sales VS orders** - Monthly breakdown of sales amount and order counts.
2. **men VS women data** - Gender-based order distribution.
3. **order status** - Distribution of order statuses (Delivered, Cancelled, Refunded).
4. **top sales in states** - Number of sales across different Indian states.
5. **Age VS Gender** - Proportional analysis of gender vs age groups.
6. **channel** - Sales channel distribution (Amazon, Ajio, etc.).
7. **Vrinda Store** - Detailed order-level data (Customer ID, Age, Channel, Product details).
8. **vrinda store reports 2025** - Reserved for future summaries or dashboards.

---

## 📝 Report Summary
A detailed analysis report has been generated based on the data, which includes:
- Sales trends over months
- Gender-based buying behavior
- Customer age group analysis
- Sales performance by state
- Channel-wise sales distribution
- Order fulfillment efficiency

📄 The analysis report can be found in `Vrinda_Store_Data_Analysis_Report.docx`.

---

## 🛠️ Tools Used
- Python
- pandas
- openpyxl
- python-docx

---

## 📌 Key Insights
- Sales and orders show month-over-month growth.
- Adult women are the largest customer segment.
- Amazon dominates as the top sales channel.
- North Indian states like Delhi and Haryana are major markets.

---

## 📂 How to Use
1. Open `Vrinda Store Data Analysis.xlsx` in Excel or your preferred spreadsheet tool.
2. Review the `Vrinda_Store_Data_Analysis_Report.docx` for key business insights.
3. Use the data and report for strategic planning, marketing insights, and performance reviews.

---

## 🔍 Notes
- Data cleaning is advised for channel names (e.g., "AMaleazon" appears to be a typo).
- The sheet `vrinda store reports 2025` is currently empty and may be used in the future.

"""

# Save the README content to a text file
readme_path = "/mnt/data/README_Vrinda_Store.txt"
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path
