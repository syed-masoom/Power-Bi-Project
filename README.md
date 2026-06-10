# Power Bi D2C Beauty Brand RTO Analysis Project

### About The Business
Glow Mantra is an Indian Direct-to-Consumer (D2C) beauty and personal care brand that offers a wide range of skincare, haircare, and wellness products to consumers across India. The company primarily sells its products through its own online store, allowing it to build direct relationships with customers and deliver a seamless shopping experience.
-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
# Motive of this Analysis
### RTO Analysis Motive
In Indian D2C and E Commerce space, Cash on Delivery (COD) remains an important payment option because it helps build trust among customers, especially first-time buyers, But it contributes to high Return to Origin (RTO) rates. When a COD order is placed but the customer refuses to accept it at the doorstep, the product is returned. We lose money on two-way shipping, packaging, and the product often gets damaged in transit.

Furthermore, our customer acquisition costs (CAC) on Meta and Google are rising, and we need to ensure we are heavily pushing product lines that actually yield a strong gross margin after aggressive couponing.

The primary objective of this RTO Analysis is to understand the key drivers behind RTO orders, identify high-risk products and customer segments, measure their impact on profitability, and uncover actionable insights to reduce RTO rates, improve operational efficiency, and maximize business profitability.

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
<!-- Skill Used in This Analysis -->

<h2 align="center" style="color: #06B6D4;">✦ Skill Used In This Analysis ✦</h2>

### 📊 Data Analytics & Business Intelligence

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Modeling-blue?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Insights-success?style=for-the-badge)
![Business Analysis](https://img.shields.io/badge/Business_Analysis-Decision_Making-orange?style=for-the-badge)

### 🧹 Data Preparation

![Data Collection](https://img.shields.io/badge/Data_Collection-Data_Gathering-blue?style=for-the-badge)
![Data Cleaning](https://img.shields.io/badge/Data_Cleaning-Data_Quality-success?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-Star_Schema-orange?style=for-the-badge)

### 📈 eCommerce Analysis

![Sales Analytics](https://img.shields.io/badge/Sales_Analytics-Revenue_Insights-green?style=for-the-badge)
![eCommerce Analytics](https://img.shields.io/badge/eCommerce_Analytics-Business_Performance-blue?style=for-the-badge)
![Sales RTO Analysis](https://img.shields.io/badge/Sales_RTO_Analysis-Returned_Orders-purple?style=for-the-badge)

### 📊 Dashboard Development

![Dashboard Development](https://img.shields.io/badge/Dashboard_Development-Power_BI-yellow?style=for-the-badge)
![Business Insights](https://img.shields.io/badge/Business_Insights-Actionable_Insights-success?style=for-the-badge)
![Data Storytelling](https://img.shields.io/badge/Data_Storytelling-Visualization-blueviolet?style=for-the-badge)

### 🎯 Business Impact

![Decision Making](https://img.shields.io/badge/Decision_Making-Data_Driven-red?style=for-the-badge)
![Profitability Analysis](https://img.shields.io/badge/Profitability_Analysis-RTO_Insights-orange?style=for-the-badge)
![Customer Retention](https://img.shields.io/badge/Customer_Retention-RFM_Strategy-green?style=for-the-badge)

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🚚 Sales RTO Dashboard
![RTO Dashboard](https://github.com/syed-masoom/Power-Bi-Project/blob/main/Sales%20RTO%20Dashboard.png?raw=true)

### Brakdown of Sales RTO Analysis
### Sales RTO KPIs
Total RTO Orders | Lost Revenue | Lost Profit | AoV | RTO Rate
| :--- | :--- | :--- | :--- | ---: |
| 625 | ₹426k | ₹310k | ₹682 | 14% |

### 📊 RTO Dashboard KPIs – Breakdown

* **🚚 Total RTO Orders: 625**
* **Insight:** A total of **625 orders** and **14%** Of total were returned, contributing directly to revenue and profit losses.
  
* **💸 Lost Revenue: ₹426K**
* **Insight:** The business lost approximately **₹426,000 in revenue** and **17.06%** of total from orders that were shipped but ultimately returned.


* **📉 Lost Profit: ₹310K**
* **Insight:** RTO orders resulted in an estimated **₹310,000 profit loss**, and **17.08%** of total significantly impacting overall business profitability.


* **🛒 Average Order Value (AOV): ₹682**
* **Insight:** On average, each returned order was worth **₹682**, indicating that high-value orders are also contributing to RTO losses.


* **📦 RTO Rate: 14%**
* **Insight:** Approximately **14 out of every 100 orders** placed were returned, highlighting a significant operational and profitability challenge.

### 📌 Business Summary
* The dashboard shows that **625 RTO orders** resulted in approximately **₹426K revenue loss** and **₹310K profit loss**. With an overall **RTO rate of 14%** and an average order value of **₹682**, reducing RTO orders can have a substantial positive impact on business profitability and operational efficiency.

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### RTO Order By Acquisition channel and Payment Mode
![Image Alt](https://github.com/syed-masoom/Power-Bi-Project/blob/main/RTO%20Order%20By%20Acquisition%20Channel%20&%20Pay%20Mode.png?raw=true)

* ### Key Insights
* This chart shows the distribution of RTO orders across acquisition channels and payment methods.
* Cash on Delivery (COD) is the major contributor to RTO orders across all channels, accounting for approximately **88%–94%** of total RTOs.
* Facebook Ads has the highest COD-related RTO contribution (**94.12%**), followed by Google Search (**92.44%**).
* Prepaid payment methods such as **UPI, Credit/Debit Cards, and Wallets** contribute only a small share of RTO orders.

  ### 📌 Business Conclusion
* The analysis indicates that encouraging prepaid payments and reducing dependency on COD can significantly lower RTO losses and improve profitability.


-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 💰 Discount Cannibalization Analysis
![Image Alt](https://github.com/syed-masoom/Power-Bi-Project/blob/main/RTO%20Discount%20Cannibalization.png?raw=true)

| Coupon Code | AoV | Gross Margin | Total Orders |
| :--- | :--- | :--- | ---: |
| NONE | ₹783.47 | 96.09% | 177 |
| FESTIVE15 | ₹598.18 | 95.43% | 122 |
| NEW20 | ₹620.43 | 94.41% | 120 |
| GLOW10 | ₹681.35 | 94.91% | 206 |

### Key Insights

* This visual evaluates the impact of different coupon codes on **Average Order Value (AOV)**, **Gross Margin**, and **Order Volume**.
* Orders without any discount (**NONE**) generated the highest **AOV (₹783)** and **Gross Margin (96.09%)**, making them the most profitable.
* **GLOW10** drove the highest number of orders (**206 orders**) while maintaining a relatively strong AOV (**₹681**), indicating it is the most effective coupon for driving sales volume.
* **FESTIVE15** and **NEW20** reduced AOV to around **₹600–₹620** without delivering a significant increase in order volume.
* Customers are frequently applying discount coupons to products that already have high margins and high order values, which can reduce overall profitability.
* The analysis suggests that some discount campaigns may be cannibalizing revenue rather than generating additional incremental sales.

### 📌 Business Conclusion

* The **NONE** segment delivers the highest profitability, while **GLOW10** generates the highest sales volume. Discounts should be used strategically because excessive couponing can lower Average Order Value and squeeze profit margins without creating substantial business growth. Optimizing coupon usage can help improve both revenue and profitability.


-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📦 Top Products by RTO
![Image Alt](https://github.com/syed-masoom/Power-Bi-Project/blob/main/Top%20RTO%20Products.png?raw=true)

### Key Insights

* This chart highlights the products with the highest Return-to-Origin (RTO) rates, ranging from **12.7% to 16.0%**.
* **Keratin Smoothing Hair Mask** has the highest RTO rate (**16.03%**), followed closely by **Red Onion Seed Hair Oil 200ml (15.94%)** and **Kumkumadi Tailam Night Drops (15.51%)**.
* The top 10 products all have RTO rates above the overall business average (**14% RTO Rate**), making them major contributors to revenue and profit loss.
* Both **Hair Care** and **Skincare** products appear frequently in the list, indicating that these categories require closer monitoring.
* High-demand products with consistently high RTO rates can significantly increase shipping, packaging, and operational costs.

📌 Business Conclusion

A small group of products is responsible for a large share of RTO losses. These products should be prioritized for deeper investigation to identify potential issues related to customer expectations, pricing, delivery experience, or product communication. Reducing RTO rates for these products can have a direct positive impact on revenue, profitability, and operational efficiency.

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📍 State-wise Delivery, Cancellation & RTO Performance

| State | Delivered Rate | Cancelled Rate | RTO Rate |
|---------|--------------:|---------------:|----------:|
| Karnataka | 79.18% | 5.87% | 14.95% |
| Tamil Nadu | 77.46% | 7.85% | 14.69% |
| Haryana | 79.25% | 6.23% | 14.53% |
| Gujarat | 78.54% | 7.08% | 14.38% |
| Uttar Pradesh | 78.99% | 7.00% | 14.01% |
| West Bengal | 77.80% | 8.43% | 13.78% |
| Delhi | 79.71% | 7.00% | 13.29% |
| Telangana | 81.68% | 5.61% | 12.71% |
| Maharashtra | 81.37% | 5.99% | 12.64% |
| **Overall Average** | **79.33%** | **6.78%** | **13.89%** |

### 📊 Key Insights
* The overall business achieved a 79.33% delivery rate, while 13.89% of orders were returned (RTO) and 6.78% were cancelled.
* Karnataka (14.95%), Tamil Nadu (14.69%), and Haryana (14.53%) recorded the highest RTO rates, making them the largest contributors to RTO losses.
* Telangana (12.71%) and Maharashtra (12.64%) showed the lowest RTO rates and the highest delivery success rates, indicating better order fulfillment performance.
* West Bengal (8.43%) has the highest cancellation rate among all states, suggesting potential issues related to customer intent, delivery expectations, or order verification.
* States with higher RTO rates should be prioritized for deeper investigation to identify possible causes such as COD dependency, delivery challenges, customer behavior, or regional operational issues.

### 📌 Business Conclusion

* The analysis reveals significant variation in delivery and RTO performance across states. While Telangana and Maharashtra demonstrate strong fulfillment efficiency, Karnataka, Tamil Nadu, and Haryana experience relatively higher return rates. Focusing on high-RTO states through better COD verification, customer communication, and logistics optimization can help reduce losses and improve overall profitability.

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📈 RTO Order Trend Analysis
![Image Alt](https://github.com/syed-masoom/Power-Bi-Project/blob/main/RTO%20Trend.png?raw=true)

### Key Insights

* This visual shows the monthly trend of the **RTO Rate (%)** throughout the year.
* The overall RTO rate fluctuates between **12.57% and 15.62%**, indicating a relatively consistent level of returns across the year.
* **January (15.62%)** recorded the highest RTO rate, followed by **October (14.94%)** and **April (14.93%)**.
* The lowest RTO rates were observed in **July (12.57%)**, **May (12.66%)**, and **March (12.70%)**.
* RTO rates tend to increase during certain months, suggesting possible impacts from seasonal demand, promotional campaigns, or changes in customer purchasing behavior.
* Despite monthly fluctuations, the RTO rate remains above 12% throughout the year, highlighting an ongoing operational challenge.

### 📌 Business Conclusion

The RTO trend remains consistently high across all months, with noticeable spikes in January, April, and October. These peak periods should be investigated further to identify potential causes such as increased COD orders, promotional campaigns, or delivery-related issues. Reducing RTO during these high-risk months can significantly improve revenue retention and profitability.

-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📌 Overall Business Conclusion

The analysis shows that Glow Mantra is losing a significant amount of revenue and profit due to a high **RTO rate of 14%**. Most RTO orders come from **Cash on Delivery (COD)** payments, making COD the biggest contributor to business losses.

Several high-selling and high-margin products also have high RTO rates, increasing the financial impact. In addition, some discount campaigns are reducing profit margins without generating substantial business growth.

States such as **Karnataka, Tamil Nadu, and Haryana** have higher-than-average RTO rates and require special attention.

### 🚀 Recommended Action Plan

* Encourage customers to use **prepaid payment methods** instead of COD.
* Implement **OTP or WhatsApp verification** for COD orders.
* Monitor and reduce RTO rates for high-risk products.
* Improve targeting for Facebook and Instagram ad campaigns to attract higher-quality customers.
* Review discount campaigns and avoid unnecessary discounts on high-demand products.
* Focus on high-RTO states and improve delivery and verification processes.

### 🎯 Final Recommendation

Reducing COD-related RTO orders should be the top priority. Lowering the RTO rate will help recover lost revenue, improve profit margins, and increase overall business efficiency.
