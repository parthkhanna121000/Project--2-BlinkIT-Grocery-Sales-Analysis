# BlinkIT Grocery Sales Analysis & Strategic Recommendations

**Author:** Parth Khanna  
**Domain:** Retail & Grocery Analytics  
**Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn), Google Colab, Data Visualization  

---

## 📌 Project Overview
This project provides an end-to-end data analytics lifecycle evaluation for **BlinkIT Grocery Sales**. The objective is to analyze customer purchase patterns, evaluate outlet-level performance across location tiers, conduct data integrity and cleaning audits, and deliver executive-level strategic recommendations to optimize revenue.

---

## 📊 Key Business Performance Metrics
* **Total Revenue:** ₹1,201,681.49
* **Average Transaction Value:** ₹140.99
* **Highest Single Sale:** ₹266.89
* **Lowest Single Sale:** ₹31.29
* **Average Customer Rating:** 3.97 / 5.0
* **Total Records Analyzed:** 8,524 rows

---

## 🔍 Key Findings & Lifecycle Analysis

### 1. Product Performance
* **Top Revenue Generators:** *Fruits & Vegetables* (₹178.1K) and *Snack Foods* (₹175.4K) drive the largest transaction volume and gross revenue.
* **Underperforming Categories:** *Seafood* (₹9.0K) and *Breakfast* (₹15.5K) contribute minimally to overall revenue.

### 2. Outlet & Location Dynamics
* **Top Outlet Format:** `Supermarket Type1` across Tier 2 and Tier 1 locations accounts for the highest cumulative revenue (~₹133K per top store).
* **Lowest Store Formats:** `Grocery Store` formats (e.g., OUT019, OUT010) generate significantly lower sales (~₹73.8K - ₹78.1K), indicating inventory limits or local demand bottlenecks.

### 3. Data Integrity & Cleaning Audit
* **Missing Data:** Identified 1,463 missing entries in `Item Weight`.
* **Duplicates & Outliers:** 0 duplicate rows found; numerical distributions verified for standard bounds.
* **Standardization:** Categorical whitespace stripped and normalized across store formats and item types.

---

## 💡 Strategic Recommendations
1. **Stock Optimization:** Expand warehouse capacity and shelf allocation for top-selling categories (*Fruits & Veggies*, *Snacks*) while liquidating slow-moving stock.
2. **Replicate Store Blueprints:** Standardize layout, product mix, and logistics in lower-performing grocery outlets to mirror successful `Supermarket Type1` locations.
3. **Product Placement & Visibility:** Move high-margin items with high customer ratings to eye-level shelves and prime displays to drive conversion.
4. **Targeted Product Bundling:** Package low-volume items (*Seafood*, *Breakfast*) with top-selling staples to improve cross-purchasing and clear inventory.

---

## 📁 Repository Contents
* `project_2_blinkit_sales_analysis.py`: Full Python notebook implementation covering Data Cleaning, Exploratory Data Analysis (EDA), and Visualizations.
* `BlinkIT Grocery Sales Analysis (Parth Khanna).pptx`: Executive presentation deck summarizing the analysis and recommendations.
* `README.md`: Project summary and findings overview.