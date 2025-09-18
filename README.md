#  Hotel Booking Analysis

##  Project Overview & Business Problem
In recent years, **City Hotel** and **Resort Hotel** have experienced **high cancellation rates**, leading to reduced revenues and inefficient room utilization.  
This issue directly impacts the hotels’ **profitability** and **operational efficiency**.  
Therefore, reducing cancellations is a primary goal to maximize revenue and optimize resource utilization.

This project analyzes a hotel booking dataset to uncover **patterns, trends, and insights** related to reservation behavior, cancellations, customer segments, and pricing strategies.  
The dataset includes bookings for both hotel types with details like **booking status, customer demographics, market segments, special requests, and financial metrics such as Average Daily Rate (ADR).**

---

##  Purpose of the Analysis
- Analyze booking data from **City Hotel** and **Resort Hotel**.  
- Identify the **scale and patterns of cancellations** and their impact on revenue.  
- Uncover **key drivers of cancellations** across segments, seasons, and customer types.  
- Compare **ADR trends** between City and Resort Hotels.  
- Provide **data-driven recommendations** for reducing cancellations and improving revenue.  

---

##  Dataset
The dataset used is the **Hotel Booking Demand Dataset**, covering **2015–2017** with:  
- **119,390 observations** and **32 features**  
- Booking info: hotel type, lead time, reserved nights, market segment, distribution channel, deposit type, etc.  
- Customer info: country of origin, adults, children.  
- Financials: ADR, deposits, special requests.  
- Reservation status: cancelled, checked-out, no-show.  

---

##  Exploratory Data Analysis

### Key Research Questions & Findings

#### 1️⃣ Cancellation Rate  
- **37.1% of bookings were cancelled** vs **62.9% retained**.  
- City Hotels recorded more bookings overall, but Resort Hotels had **higher cancellation volatility**.  

#### 2️⃣ Time-Series of ADR by Hotel Type  
- Resort Hotels: **€40–€50 higher ADR**, but **sharper seasonal spikes & cancellations**.  
- City Hotels: More **stable & predictable ADR** due to business travel demand.  

#### 3️⃣ Monthly Reservation Patterns  
- **Peak bookings:** July (7,714) & August (8,139).  
- **Peak cancellations:** January (4,532) & February (4,351).  
- Cancellations in summer months were **~30% higher** than off-season.  

#### 4️⃣ Impact of Pricing on Cancellations  
- Higher ADRs strongly correlated with **higher cancellation risk**.  
- Customers likely cancel premium bookings if cheaper alternatives appear.  

#### 5️⃣ Cancellations by Country  
- Top 10 countries contribute to **~60% of cancellations**.  
- Portugal ranked highest.  

#### 6️⃣ Market Segment Analysis  
- **OTA (47%)** and **Group bookings (27%)** drive **74% of cancellations**.  
- Heavy reliance on OTAs = higher commission fees & less customer control.  

#### 7️⃣ Deposit Type Distribution  
- **No deposit:** 86% of bookings (high cancellation risk).  
- **Non-refundable deposits:** Only 12% (much more reliable).  

---

##  Recommendations
1. **Target OTA & Group Bookings** – Together they cause **74% of cancellations**. A 5% reduction could save **$1.2M+ annually**.  
2. **Strengthen Deposit Policies** – Introduce partial/flexible deposits; reduce cancellations from “no-deposit” bookings.  
3. **Seasonal Pricing & Promotions** – Focus on summer months (July–August) where cancellations spike ~30% higher.  
4. **Resort Hotel Retention Focus** – Higher ADR but also higher cancellations; targeted policies here yield biggest revenue gain.  
5. **Country-Specific Strategies** – Tailored policies for top 10 cancellation-heavy countries (~60% of total cancellations).  

---

##  Conclusion
This analysis demonstrates that **cancellations are a major revenue leakage**, with **37% of all bookings cancelled**.  
Key findings highlight that **OTA (47%)** and **Group bookings (27%)** dominate cancellations, while **Resort Hotels**, despite higher ADR, are more vulnerable to losses due to seasonality.  

Moreover, the fact that **86% of bookings had no deposit** explains the high flexibility customers enjoy, resulting in higher cancellation rates.  
If hotels reduce OTA & Group cancellations by just **5%**, they could recover **$1.2M+ annually** in lost ADR revenue.  

This project shows how **data analytics can convert raw booking data into actionable insights** with measurable financial impact.  
Effective cancellation management is not just operational efficiency — it is a **key driver of revenue growth** for hotels.  

---
