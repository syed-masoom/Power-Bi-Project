# Power Bi RTO & Customers RFM Analysis Project

### About The Business
Glow Mantra is an Indian Direct-to-Consumer (D2C) beauty and personal care brand that offers a wide range of skincare, haircare, and wellness products to consumers across India. The company primarily sells its products through its own online store, allowing it to build direct relationships with customers and deliver a seamless shopping experience.
-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
# Motive of this Analysis
### RTO Analysis Motive
In Indian D2C and E Commerce space, Cash on Delivery (COD) remains an important payment option because it helps build trust among customers, especially first-time buyers, But it contributes to high Return to Origin (RTO) rates. When a COD order is placed but the customer refuses to accept it at the doorstep, the product is returned. We lose money on two-way shipping, packaging, and the product often gets damaged in transit.

Furthermore, our customer acquisition costs (CAC) on Meta and Google are rising, and we need to ensure we are heavily pushing product lines that actually yield a strong gross margin after aggressive couponing.

The primary objective of this RTO Analysis is to understand the key drivers behind RTO orders, identify high-risk products and customer segments, measure their impact on profitability, and uncover actionable insights to reduce RTO rates, improve operational efficiency, and maximize business profitability.

### Customer RFM Analysis Motive
In the D2C and eCommerce industry, acquiring a new customer is significantly more expensive than retaining an existing one. Due to intense market competition, attracting customers is only the first challenge. After a customer's first purchase, there is no guarantee that they will return and buy again. At the same time, businesses also face the risk of losing their loyal and high-value customers to competitors.

Customer behavior is often uncertain and difficult to predict, making it challenging for businesses to identify which customers are likely to repurchase, become inactive, or generate the highest lifetime value.

The primary objective of this RFM (Recency, Frequency, Monetary) Analysis is to understand customer purchasing behavior, identify valuable customer segments, detect at-risk customers, and uncover opportunities to improve customer retention and revenue growth. This analysis will help diagnose and evaluate the sales performance of Glow Mantra Beauty and support data-driven customer engagement strategies.
-- ---------------------------------------------------------------------------------------------------------------------------------------------------------------
<!-- Skill Used in This Analysis -->
<h2 align="center" style="color: #06B6D4;">✦ Skill Used In This Analysis ✦</h2>

<p align="center">
  
  <kbd style="background-color:#111827; color:#06B6D4; padding:10px; border-radius:5px;">Data Collection</kbd> ➔
  <kbd style="background-color:#111827; color:#3B82F6; padding:10px; border-radius:5px;">Power Bi</kbd> ➔
  <kbd style="background-color:#111827; color:#3B82F6; padding:10px; border-radius:5px;">DAX</kbd> ➔
  <kbd style="background-color:#111827; color:#3B82F6; padding:10px; border-radius:5px;">Data Modelling</kbd> ➔
  <kbd style="background-color:#111827; color:#10B981; padding:10px; border-radius:5px;">Data Cleaning</kbd> ➔
  <kbd style="background-color:#111827; color:#7C3AED; padding:10px; border-radius:5px;">Data Analysis</kbd> <br><br>➔
  <kbd style="background-color:#111827; color:#3B82F6; padding:10px; border-radius:5px;">Visualization</kbd> ➔
  <kbd style="background-color:#111827; color:#06B6D4; padding:10px; border-radius:5px;">Business Insights</kbd> ➔
  <kbd style="background-color:#111827; color:#10B981; padding:10px; border-radius:5px;">Decision Making</kbd>
</p>

<br><br id="projects-section">

### Sales RTO Dashboard
![RTO Dashboard](https://github.com/syed-masoom/Power-Bi-Project/blob/main/Sales%20RTO%20Dashboard.png?raw=true)

### Brakdown of Sales RTO Analysis
RTO KPIs
Total RTO Orders | Lost Revenue | Lost Profit | AoV | RTO Rate
| :--- | :--- | :--- | :--- | ---: |
| 625 | ₹426k | ₹310k | ₹682 | 14% |

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
### Customer RFM Dashboard
![Customer RFM Dashboard](https://github.com/syed-masoom/Power-Bi-Project/blob/main/14.%20Customer%20Cohort%20Dashboard.png?raw=true)

