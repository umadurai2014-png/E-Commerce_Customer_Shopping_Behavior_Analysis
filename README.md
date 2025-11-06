# 🛍️ E-Commerce Customer Behavior Analysis

## 📘 1. Project Overview
This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across various product categories.  
The goal is to uncover insights into **spending patterns**, **customer segments**, **product preferences**, and **subscription behavior** to guide strategic business decisions.

---

## 📊 2. Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  

**Key Features:**
- 👤 **Customer demographics:** Age, Gender, Location, Subscription Status  
- 🛒 **Purchase details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- 💳 **Shopping behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type  

**Missing Data:**  
- 37 missing values in the `Review Rating` column  

---

<img width="630" height="430" alt="image" src="https://github.com/user-attachments/assets/d978828c-5ec8-4d3c-add9-aa930f1a41f3" />


## 🐍 3. Exploratory Data Analysis using Python
Performed data cleaning, preprocessing, and feature engineering using **Python (Pandas, NumPy)**.

**Steps:**
1. **Data Loading:** Imported dataset using Pandas.  
2. **Initial Exploration:** Used `df.info()` and `.describe()` for data summary.  
3. **Missing Data Handling:** Imputed missing values in `review_rating` with median per product category.  
4. **Column Standardization:** Converted column names to `snake_case`.  
5. **Feature Engineering:**
   - Created `age_group` by binning customer ages.
   - Added `purchase_frequency_days` based on frequency mapping.  
6. **Data Consistency Check:** Dropped redundant column `promo_code_used`.  
7. **Database Integration:** Exported cleaned data to **MySQL** for SQL-based business analysis.  

---

## 🧮 4. Data Analysis using SQL
SQL was used to derive key **business insights** from the cleaned dataset.

**Key Queries & Insights:**
- 💰 **Revenue by Gender:** Compared total revenue by male vs. female customers.  
- 🧾 **High-Spending Discount Users:** Found discount users who spent above average.  
- ⭐ **Top 5 Products by Rating:** Identified highest-rated products.  
- 🚚 **Shipping Type Comparison:** Compared purchase amounts by shipping type.  
- 🔁 **Subscribers vs. Non-Subscribers:** Analyzed average spend and revenue differences.  
- 💵 **Discount-Dependent Products:** Found products most reliant on discounts.  
- 👥 **Customer Segmentation:** Classified customers as *New*, *Returning*, and *Loyal*.  
- 🧢 **Top 3 Products per Category:** Found most-purchased items in each category.  
- 🔂 **Repeat Buyers & Subscriptions:** Checked if frequent buyers tend to subscribe.  
- 📈 **Revenue by Age Group:** Calculated total revenue per age group.  

---

## 📊 5. Power BI Dashboard
An **interactive Power BI dashboard** was designed for visual storytelling.

**Key Visuals:**  
- 📦 Sales by Category, Size, and Item Purchased  
- 🎨 Top 5 Colors by Total Sales  
- 👥 Sales by Age Group and Gender  
- 🗺️ Sales Distribution by State  
- 💰 Sales Trends by Category and Size  
- 🏆 Top Performing Products and Categories  

---

## 💡 6. Business Recommendations
- **Boost Subscriptions:** Offer exclusive benefits for subscribers.  
- **Customer Loyalty Programs:** Reward repeat buyers to nurture loyalty.  
- **Review Discount Policy:** Optimize discounts to maintain profit margins.  
- **Product Positioning:** Promote top-rated and best-selling products.  
- **Targeted Marketing:** Focus campaigns on high-value customers and express shipping users.  

---

## 🧰 7. Tools & Technologies Used

| Tool / Technology | Purpose |
|--------------------|----------|
| 🐍 **Python** | Data cleaning, preprocessing, and feature engineering |
| 🗃️ **MySQL** | Query-based business analysis |
| 📊 **Power BI** | Data visualization and dashboard creation |
| 💻 **GitHub** | Project documentation and version control |

---

## 📬 Contact
**Author:** Your Name  
**Email:** your.email@example.com  
**GitHub:** [@yourusername](https://github.com/yourusername)



