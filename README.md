# Olist Marketing Funnel Performance & Conversion Analysis  

## 1. Project Overview  

**Scenario:**  
An analytics engagement for **Olist**, a Brazil-based e-commerce marketplace, evaluating its marketing funnel performance and lead quality.  

**Goal:**  
Identify which marketing channels bring in the most qualified sellers, how effectively they convert into deals, and how long the sales cycle takes.  
This project simulates a **Marketing Operations Analyst** engagement for Olist’s leadership team.  

---

## 2. Executive Summary  

**Context:**  
This analysis, prepared for the Head of Marketing Operations, examines Olist’s lead-to-deal funnel from mid-2017 to mid-2018.  
The objective was to guide investment decisions, improve funnel efficiency, and shorten time to close.  

**Focus Areas**  
1. Funnel Overview – Lead generation, conversion rate, and efficiency by channel  
2. Deal Quality & Revenue – Seller quality and declared revenue by business segment  
3. Sales Cycle Speed – Funnel velocity and time-to-close performance  

**Key Findings**  
- Only **10.4%** of marketing-qualified leads converted into closed deals.  
- **Organic and referral channels** generated sellers with roughly **2× higher average revenue** than paid sources.  
- Average deal cycle shortened from **~370 days to ~30 days**, reflecting major process improvements.  

**Recommendations**  
- Reallocate marketing spend toward high-ROI organic and referral channels.  
- Focus sales efforts on manufacturer-type sellers in high-revenue verticals.  
- Continue process optimizations that reduced time to close and improved cash flow.  

---

## 3. Deep-Dive Insights  

### Page 1 – Funnel Overview  
**Headline:**  
Marketing-qualified leads are strong in volume but differ widely in conversion quality by channel.  

![Funnel Overview](images/funnel%20overview.png)  

**Insights:**  
- Generated **7,940 leads**, closing **828 deals** (10.43% conversion).  
- Lead inflow peaked in Q1 2018 with consistent scaling in closed deals.  
- Organic search and referral sources delivered the highest-quality leads.  

**Interpretation:**  
Marketing should emphasize high-intent channels rather than focusing solely on lead volume.  

---

### Page 2 – Deal Quality & Revenue  
**Headline:**  
Organic search delivers the highest-value sellers; key business segments drive larger catalog sizes and stronger revenue potential.  

![Deal Quality & Revenue](images/Deal%20Quality%20&%20Revenue.png)  

**Insights:**  
- **Organic search sellers** reported an average declared monthly revenue of **≈ $190K**, nearly **4× higher** than social channels.  
- **Construction Tools & Home Garden** and **Mobile Phone** segments had the largest product catalogs.  
- Manufacturer-type sellers demonstrated faster close times and more consistent revenue.  

**Interpretation:**  
Prioritize high-value verticals and manufacturer partnerships acquired through organic channels to maximize deal quality and lifetime value.  

---

### Page 3 – Sales Cycle Speed  
**Headline:**  
Sales cycle efficiency improved sharply, strengthening forecasting accuracy and funnel velocity.  

![Sales Cycle Speed](images/Sales%20Cycle%20Speed.png)  

**Insights:**  
- Average days-to-close dropped from **~369 to 33 days** over the analysis period.  
- Most deals now close within **50–150 days**, with fewer long-tail outliers.  
- Shorter cycles correlate with organic and referral leads, validating their higher qualification.  

**Interpretation:**  
Monitor cycle-time KPIs monthly and recognize fast-closing segments to sustain operational momentum.  

---

## 4. Actionable Recommendations  

| Stakeholder | Recommendation | Supporting Metric |
|--------------|----------------|------------------|
| **Marketing** | Shift 25–30% of paid search budget to organic and referral channels | Organic search yields ≈ 2× higher average revenue per deal |
| **Sales** | Target manufacturer leads in high-revenue segments | Manufacturer leads close ≈ 48 days faster and average $74K monthly revenue |
| **Revenue Ops** | Track `days_to_close` trend monthly | Funnel velocity improved ~90% year over year |

---

## 5. Technical Overview  

**Repository:** [Olist-Marketing-Funnel-Analysis](https://github.com/Kevinm360/Olist-Marketing-Funnel-Analysis)  

**Files:**  
- `/images/` – dashboard screenshots  
- `Funnel Overview.pbix` – Power BI project file  
- `olist_mql_clean.csv`, `olist_deals_merged.csv` – cleaned datasets  

**Tools:**  
Power BI (DAX measures & visualization), Python (pandas cleaning), Excel (data validation)  

**Summary Metrics:**  
- Total Leads: 7,940  
- Closed Deals: 828  
- Conversion Rate: 10.43%  
- Avg Days to Close: 48  
- Avg Declared Monthly Revenue: $74K  
