# Excel Data Cleaning & Analysis Project

## 📌 Project Overview

This project demonstrates the end-to-end process of transforming a "messy" corporate dataset into a clean, actionable reporting tool. The goal was to take 100 rows of inconsistent employee data and perform deep cleaning to provide a company manager with accurate insights regarding payroll, departmental performance, and hiring trends.

## 📊 The Data Challenge

The raw data (`Data Before`) simulated real-world data entry errors, including:

* **Inconsistent Naming:** Mixed casing (e.g., `jane doe`) and trailing spaces.
* **Departmental Chaos:** Multiple names for the same department (e.g., `SALS`, `Sales Dept`, `Sales`).
* **Date Formatting:** A mix of `YYYY-MM-DD`, `MM/DD/YY`, and text-based dates like `Jan 12 2023`.
* **Non-Numeric Values:** Salaries written as `"$65,000"` or `"62k"`, making math impossible.
* **Messy Categorization:** Performance scores with typos (`Excllent`) and Remote Status using mixed indicators (`1`, `0`, `Yes`, `No`).

---

## 🛠️ Data Cleaning Process

The following steps were taken to ensure the data was "Boardroom Ready":

1. **Standardization:** Normalized all Department names to four core categories: `Sales`, `Marketing`, `IT`, and `HR`.
2. **Name Scrubbing:** Applied proper casing and removed leading/trailing whitespace.
3. **Numerical Conversion:** * Removed `$` and `,` symbols.
* Converted "k" suffixes to thousands (e.g., `62k`  `62000`).


4. **Date Uniformity:** Converted all variations of hire dates into a standard `MM/DD/YYYY` format.
5. **Boolean Cleanup:** Simplified `Remote_Status` into two distinct categories: `Remote` and `Office`.
6. **Performance Mapping:** Fixed typos and standardized ratings into a consistent scale.

---

## 📈 Key Insights & Analysis

Using the cleaned data (`Data After`), I performed a comprehensive analysis to answer critical business questions:

### Company Snapshot

| Metric | Result |
| --- | --- |
| **Total Headcount** | 100 Employees |
| **Total Salary Expenditure** | $9,696,000 |
| **Average Company Salary** | $96,960 |
| **Total Sales Generated (2025)** | $894,800 |

### Top Performers

* **Highest Paid Employee:** Robert De Niro (Marketing) at **$180,000**.
* **Top Sales Contributor:** Robert De Niro (Marketing) with **$40,000** in sales.
* **Largest Department:** **Sales** (32 employees).

### Departmental Salary Averages

1. **HR:** $126,388
2. **IT:** $102,818
3. **Marketing:** $95,642
4. **Sales:** $77,531

---

## 📂 File Structure

* `Excel Project - Data Before`: The original messy raw data.
* `Excel Project - Data After`: The finalized, cleaned dataset.
* `Excel Project - Analysis`: The summary tables and pivot analysis.
* `README.md`: Project documentation.

## 🚀 How to Use

1. **View Raw Data:** Open `Data Before` to see the initial state of the data.
2. **Review Cleaning:** Compare it with `Data After` to see how formatting was standardized.
3. **Check Results:** Open the `Analysis` file to see the pivot tables and summary statistics used for the final report.
