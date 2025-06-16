
# 🛒 Retail Sales Analysis | Excel Project

Welcome to the Retail Sales Analysis Dashboard! This project explores customer behavior, product trends, and payment preferences in a retail environment. The goal is to extract actionable insights from structured transaction data using Excel (and optionally Power BI).

---

## 🎯 Project Objective

The aim of this analysis is to uncover key metrics in retail operations by answering:

- Which product lines generate the highest revenue?
- What are the patterns in customer demographics (e.g., gender, location)?
- How do different payment methods perform?
- What are the peak sales periods?
- How does membership type affect spending?

---

## 🧾 Dataset Description

The dataset is based on real-world retail transactions with a sample size of several hundred entries, covering:

### Key Tables & Fields:

**Sheet1 – Transactions:**
- `Invoice ID`: Unique transaction code
- `Branch`: Branch code (A, B, C)
- `City`: City of transaction
- `Customer type`: Member or Normal
- `Gender`: Male or Female
- `Product line`: Product category
- `Unit price`: Price per unit
- `Quantity`: Number of units sold
- `Total`: Total transaction value (incl. tax)
- `Date` & `Time`: Timestamp of transaction
- `Payment`: Cash, Ewallet, or Credit Card
- `Gross income`, `COGS`, `Tax 5%`, `Rating`

**Sheet5 – Summary Analysis:**
- Aggregated views by:
  - Gender & Branch
  - City-wise performance
  - Payment method distribution
  - Product line popularity
  - Membership insights

---
![image](https://github.com/user-attachments/assets/d06f33cb-a446-487e-ab99-7f1e761a1aea)
---

## 📊 Dashboard Features (for Power BI or Excel Pivot)

- **Bar & Column Charts**
  - Product line revenue
  - Branch-wise sales
- **Pie Charts**
  - Gender distribution
  - Payment method breakdown
- **Matrix Table**
  - Customer type vs revenue
- **Slicers/Filters**
  - City, gender, branch, product line

---

## 🔍 Key Insights

1. **Branch Performance**
   - Branch A and B had nearly identical total revenue (~106,000 each).
2. **Gender Trends**
   - Spending is balanced across genders with slight variations across branches.
3. **Top Product Lines**
   - Categories like "Health and Beauty", "Electronic Accessories", and "Home and Lifestyle" appear frequently.
4. **Payment Behavior**
   - Ewallet and Credit Card are widely used, with Cash trailing in some regions.
5. **Membership Value**
   - Members and Normal customers show similar purchase behavior, warranting further segmentation.

---

## 🧠 Methodology

### Data Cleaning
- Removed duplicates
- Parsed mixed date formats
- Normalized category names
- Checked missing values

### Analysis Tools
- **Excel Pivot Tables**
- **Conditional Formatting**
- **Manual Aggregation for Insight Building**

(Optional)
- **Power BI Desktop** for advanced visualizations
- **DAX Measures** for dynamic KPIs

---

## 🛠 Tools & Technologies

- **Microsoft Excel** – Primary tool for cleaning and analysis
- **Power BI (Optional)** – For interactive dashboarding
- **CSV/XLSX** – Base data format
- **GitHub** – For sharing documentation (optional)

---

## 🚀 How to Use This Project

1. Open `Work.xlsx` in Excel.
2. Navigate to `Sheet1` for raw data or `Sheet5` for summaries.
3. Use built-in filters or pivot tables to explore.
4. Import into Power BI if you want interactive dashboards.
5. Insights can be used for retail strategy, marketing, or supply chain planning.

---

## 🙏 Acknowledgments

Thanks to open-source data communities and Microsoft Office resources for making self-service analytics accessible to all.

