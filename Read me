# 🍊 Swiggy Menu Market Analysis | Power BI

> An end-to-end Power BI data analytics project analyzing the Swiggy menu market across cities, restaurants, food categories, pricing, ratings, and rating-count engagement.

---

## 📊 Project Overview

This project analyzes a Swiggy menu-level dataset using **Microsoft Power BI** to understand the structure of the food menu market, pricing patterns, category performance, customer rating engagement, and the relationship between price and observed engagement.

The project follows a complete Data Analyst workflow:

**Data Understanding → Data Cleaning → Data Transformation → DAX → Exploratory Analysis → Segmentation → Dashboard → Business Insights**

The final output is an interactive Power BI dashboard designed to help stakeholders explore menu pricing, category performance, and price–engagement positioning.

---

## 🎯 Business Goal

The primary goal of this project is to transform a large and complex Swiggy menu dataset into an interactive business intelligence solution that answers:

- How large is the analyzed menu market?
- How are menu items distributed across price ranges?
- Which food categories have stronger rating-count engagement?
- Does price influence average rating?
- Does price have a consistent relationship with popularity/engagement?
- Which categories offer strong value with high engagement?
- Which premium categories have relatively low engagement?
- How do these patterns vary across cities and price segments?

---

# ❓ Business Questions

### Market Structure
1. How many cities and restaurants are represented in the dataset?
2. How many menu items and dishes are available?
3. What is the average menu price?
4. What is the overall average rating?

### Pricing
5. Which price bands contain the largest share of menu items?
6. How is the menu distributed between affordable, mid-range and premium pricing?

### Category Performance
7. Which food categories have higher rating-count engagement?
8. Which categories have higher or lower median prices?
9. Which categories have larger menu assortments?

### Price & Engagement
10. Does higher menu price result in higher ratings?
11. Does higher menu price result in stronger rating-count engagement?

### Strategic Segmentation
12. Which categories are **High Value / Popular**?
13. Which categories are **Premium / Popular**?
14. Which categories are **Affordable / Low Engagement**?
15. Which categories are **Premium / Low Engagement**?

---

# 📁 Dataset

The project uses a **Swiggy menu-level dataset for India**.

### Data Grain

The primary analytical grain is:

> **Menu / Food-Item Level**

### Main Fields

| Field | Purpose |
|---|---|
| City | Geographic analysis |
| Restaurant Name | Restaurant analysis |
| Food Category | Category analysis |
| Price (INR) | Pricing analysis |
| Rating | Customer rating analysis |
| Rating Count | Engagement analysis |
| Dish/Menu Information | Menu assortment analysis |
| Location Fields | Geographic context |

---

# 📈 Dataset Snapshot

| Metric | Result |
|---|---:|
| **Cities** | **28** |
| **Restaurants** | **938** |
| **Average Rating** | **4.31** |
| **Average Price** | **₹261.22** |
| **Total Menu Items** | **≈122K** |
| **Total Dishes** | **≈40K** |
| **Category Analysis Menu Items** | **121,619** |

### Market Interpretation

The dataset represents a sizeable menu ecosystem across **28 cities and 938 restaurants**, providing enough variation to analyze pricing, food categories, ratings, and observed engagement.

> **Important:** This is menu-level data. It does not contain transaction-level sales, revenue, order quantity, or customer-level purchasing information.

Therefore, **Rating Count is used as an observed engagement proxy and not as actual sales or order volume.**

---

# 🔄 Data Cleaning & ETL

The raw dataset was prepared before performing analysis.

## 1. Data Quality Review

The following areas were reviewed:

- Data types
- Numerical fields
- Categorical fields
- Price values
- Rating values
- Rating Count
- Category consistency
- Duplicate or fragmented category concepts

---

## 2. Numerical Field Preparation

The main numerical fields used for analysis were:

- `Price (INR)`
- `Rating`
- `Rating Count`

These fields were used to calculate:

- Average
- Median
- Count
- Distinct Count
- Category-level comparisons
- Price–engagement relationships

---

# 🧹 Food Category Standardization

One of the major challenges in the raw dataset was **category fragmentation**.

The original data contained many granular or inconsistent food-category labels.

Similar food concepts were consolidated into standardized analytical categories.

### Standardized Categories Include

- Bakery
- Beverages
- Biryani
- Breads
- Breakfast
- Burgers
- Chinese / Asian
- Combo / Meal
- Desserts / Sweets
- Indian
- International
- Momos
- Non-Veg
- Noodles
- Pasta
- Pizza
- Rice
- Rolls / Wraps
- Salads
- Sandwiches
- Snacks / Sides
- Soup
- South Indian
- Starters / Kebabs

### Why Standardization Was Required

Without standardization:

```text
Multiple Similar Labels
        ↓
Category Fragmentation
        ↓
Inconsistent Analysis
