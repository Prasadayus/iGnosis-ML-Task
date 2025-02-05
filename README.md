# iGnosis-ML-Task

# Customer and Product Analysis for Sales Optimization

## Overview

This project analyzes transaction data to uncover insights about **customer behavior** and **product performance**. The goal is to help the marketing team identify the most **profitable customer segments** and the **best-selling products**, allowing for targeted marketing strategies and optimized product positioning.

## Datasets

1. **purchase.csv**: Contains customer demographics, including their lifestage and premium customer status.
   - Columns: `LYLTY_CARD_NBR`, `LIFESTAGE`, `PREMIUM_CUSTOMER`

2. **transaction_data.csv**: Contains transaction details, including product names, quantities, and total sales.
   - Columns: `DATE`, `STORE_NBR`, `LYLTY_CARD_NBR`, `TXN_ID`, `PROD_NBR`, `PROD_NAME`, `PROD_QTY`, `TOT_SALES`

Both datasets are merged to link customer profiles with transaction data, enabling deeper insights.

## Key Findings

### 1. **Total Sales by Lifestage**
We analyzed total sales by customer lifestage and identified the following:
- **Older demographics** (e.g., **Older Singles/Couples**, **Retirees**, **Older Families**) are the **highest spenders**. This suggests they have higher disposable incomes and prefer convenience-oriented products or premium offerings.
- **Younger demographics** (e.g., **Young Families**, **Young Singles/Couples**) spend less, which may be due to a focus on essential or budget-friendly products.
- **New Families** have the lowest sales, potentially reflecting their early stage of brand loyalty or preference for lower-cost products.

**Top Sales by Lifestage**:
- **Older Singles/Couples**: $402,426.75
- **Retirees**: $366,470.90
- **Older Families**: $353,767.20
- **Young Families**: $316,160.10
- **Young Singles/Couples**: $260,405.30
- **Mid-Age Singles/Couples**: $184,751.30
- **New Families**: $50,433.45

### 2. **Total Sales by Premium Customer Status**
The analysis of premium customer segments reveals:
- **Mainstream customers** account for the highest total sales, followed by **Budget customers**. These segments likely represent a larger portion of the overall market, purchasing value-driven products.
- **Premium customers**, although typically associated with higher-end products, contribute **lower total sales**. This may be due to their **selective purchasing behavior**, choosing fewer but more expensive products.

**Top Sales by Premium Customer**:
- **Mainstream**: $750,744.50
- **Budget**: $676,211.55
- **Premium**: $507,458.95

### 3. **Most Popular Products by Lifestage**
We examined the best-selling products for each lifestage and identified the top products:
- The most popular products among **Mid-Age Singles/Couples** include **Smiths Crinkle Chips** and **Kettle Sweet Chilli & Sour Cream**.
- These products could be favored for their combination of quality and affordability, aligning with the lifestyle preferences of this group.

**Top Products by Lifestage**:
- **Smiths Crinkle Chip Original Big Bag 380g** (Mid-Age Singles/Couples)
- **Cheezels Cheese 330g** (Mid-Age Singles/Couples)
- **Dorito Corn Chips Supreme 380g** (Mid-Age Singles/Couples)

### 4. **Most Popular Products by Premium Customer Status**
When analyzing product sales by premium customer status:
- **Budget customers** dominate the top sales list, with products like **Dorito Corn Chips Supreme 380g** and **Smiths Crinkle Chips Original Big Bag 380g** leading.
- This suggests that even customers labeled as "Budget" still prefer higher-quality, larger-sized products, often in bulk.

**Top Products by Premium Customer**:
- **Dorito Corn Chips Supreme 380g** (Budget)
- **Smiths Crinkle Chip Original Big Bag 380g** (Budget)
- **Kettle Mozzarella Basil & Pesto 175g** (Budget)

### 5. **Repeat Customer Analysis**
We identified customers who make frequent purchases and categorized them as **repeat customers**:
- The top repeat customers are those who have made **17-18 purchases**, indicating strong **brand loyalty** and **consistent buying behavior**.
- Targeting these repeat customers with **exclusive offers or loyalty rewards** could increase customer retention and maximize sales.

**Top Repeat Customers**:
- **Customer 162039**: 18 purchases
- **Customer 172032**: 18 purchases
- **Customer 128178**: 17 purchases

### **Hypothesis on Loyal Customer Segments**
Based on the analysis, we hypothesize:
- **Older customers** (e.g., **Older Singles/Couples**, **Retirees**, **Older Families**) are likely to have **higher disposable incomes** and **prefer premium products** or those offering convenience.
- **Younger customers** (e.g., **Young Families**, **Young Singles/Couples**) may be more price-sensitive and respond well to **targeted marketing** or discounts.
- **Mainstream customers** are likely to be the **most frequent shoppers**, purchasing **value-for-money products** in higher quantities.
- **Premium customers** could be a **niche but profitable segment** if targeted with personalized or high-end offerings.


## Conclusion

This analysis provides valuable insights into **customer behavior**, **product preferences**, and **sales trends**. By leveraging these findings, the marketing team can refine its strategies, focus on the most profitable segments, and tailor product offerings to better meet customer needs.
