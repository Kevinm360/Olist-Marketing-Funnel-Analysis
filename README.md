# Olist Marketing Funnel Performance & Conversion Analysis  

## 1️⃣ Project Title & Framing (Analyst Focus)  
**Scenario:**  
An analytics engagement was conducted for **Olist**, a Brazil-based e-commerce marketplace platform, to evaluate the effectiveness of its lead generation and sales funnel performance.  

**Project Goal:**  
To understand which marketing channels deliver the most qualified sellers, how effectively they convert into closed deals, and how long the conversion process takes.  
This project simulates a **Marketing Operations Analyst** engagement for Olist’s leadership team.  

---

## 2️⃣ Executive Summary & Context (The High-Level Story)  

**Client Context:**  
Reporting to the Head of Marketing Operations, this analysis evaluated performance of Olist’s lead-to-deal funnel from mid-2017 to mid-2018.  
The goal was to help executives identify where to reinvest marketing spend and shorten the sales cycle.  

**Key Project Areas (3 Dashboard Pages):**  
1. Funnel Overview – Lead generation, conversions, and efficiency by channel  
2. Deal Quality & Revenue – Seller quality and revenue potential by business segment  
3. Sales Cycle Speed – Funnel velocity and time-to-close performance  

**Key Takeaways / Newsflash:**  
- Only **10.4 %** of all marketing-qualified leads converted into closed deals.  
- **Organic and referral channels** produced **2× higher revenue sellers** compared to paid ads.  
- Average deal cycle shortened from **~370 days to ~30 days** within a year.  

**Main Recommendations:**  
- Reallocate paid search budget toward high-ROI organic and referral channels.  
- Prioritize manufacturer-type sellers in high-revenue segments.  
- Continue process improvements that shortened close times and improved cash-flow velocity.  

---

## 3️⃣ Deep-Dive Insights (Organized by Dashboard Pages)  

### 📊 **Page 1: Funnel Overview**  
**Headline / Newsflash:**  
*Marketing-qualified leads are strong in volume but vary widely in conversion quality by channel.*  

**Featured Visualization:**  
![Funnel Overview](images/funnel%20overview.png)  

**Detailed Insights:**  
- Generated **7 940 leads**, of which **828 deals** were closed → **10.43 % conversion**.  
- Lead inflow peaked in Q1 2018; conversions scaled proportionally, showing consistent funnel health.  
- Organic search and referrals outperform paid search and social in conversion rate, confirming higher-intent lead behavior.  

**Implication:**  
Marketing should refine acquisition toward organic and referral channels that yield higher quality leads instead of maximizing top-of-funnel volume alone.  

---

### 💰 **Page 2: Deal Quality & Revenue**  
**Headline / Newsflash:**  
*Organic search delivers the most valuable sellers, while certain segments dominate catalog size and declared revenue.*  

**Featured Visualization:**  
![Deal Quality & Revenue](images/Deal%20Quality%20&%20Revenue.png)  

**Detailed Insights:**  
- **Organic search sellers** reported an average declared monthly revenue of **≈ $190 K**, **4× higher** than social channels.  
- **Construction Tools & Home Garden** and **Mobile Phone** segments lead in product catalog size, indicating strong business potential.  
- Manufacturer-type sellers show shorter deal cycles and higher revenue consistency than resellers.  

**Implication:**  
Target high-value verticals (construction, mobile) and manufacturer partnerships through organic outreach to maximize revenue yield.  

---

### ⚡ **Page 3: Sales Cycle Speed**  
**Headline / Newsflash:**  
*Sales cycle efficiency improved dramatically, enhancing forecasting accuracy and revenue timing.*  

**Featured Visualization:**  
![Sales Cycle Speed](images/Sales%20Cycle%20Speed.png)  

**Detailed Insights:**  
- Average **days-to-close dropped from ~369 to 33 days**, reflecting major process optimization.  
- Most deals now close within **50–150 days**; long-tail outliers reduced substantially.  
- Faster cycles correlate with organic and referral channels, validating their higher qualification level.  

**Implication:**  
Sustain operational improvements by monitoring cycle-time KPIs monthly and rewarding fast-close segments.  

---

## 4️⃣ Actionable Recommendations  

| Stakeholder | Recommendation | Rationale / Supporting Metric |
|--------------|----------------|-------------------------------|
| **Marketing Team** | Shift 25–30 % of paid search budget to organic growth & referral campaigns | Organic search yields **2× higher average revenue** per deal |
| **Sales Leadership** | Focus on manufacturer leads in high-revenue segments | Manufacturer leads close faster (≈ 48 days) and average >$74 K monthly revenue |
| **Revenue Operations** | Maintain monthly monitoring of `days_to_close` trend | Funnel velocity improved ~90 % YoY; continued visibility ensures sustainment |

---

## 5️⃣ Technical Documentation & Access  

**Repository:** [Olist-Marketing-Funnel-Analysis](https://github.com/Kevinm360/Olist-Marketing-Funnel-Analysis)  

**Files:**  
- `/images/` – dashboard screenshots  
- `Funnel Overview.pbix` – Power BI project file  
- `olist_mql_clean.csv`, `olist_deals_merged.csv` – cleaned datasets  

**Tools Used:**  
Power BI (DAX measures & visualization) | Python (pandas cleaning) | Excel (data validation)  

**Live Metrics Summary:**  
- Total Leads = 7 940  
- Closed Deals = 828  
- Conversion Rate = 10.43 %  
- Avg Days to Close = 48 days  
- Avg Declared Revenue = \$74 K  

---

### ✅ Technical Summary (Optional)  
Data were cleaned in Python, standardized for consistent text casing and date formats, numeric fields cast to proper types, and merged on `mql_id` to create a unified marketing-to-sales funnel dataset ready for Power BI modeling.  

---

