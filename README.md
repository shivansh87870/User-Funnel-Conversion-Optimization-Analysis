#  The Conversion Gap: E-commerce User Behavior Analysis

##  Overview
This project focuses on analyzing user behavior in an e-commerce environment to understand why a large number of users browse products but fail to convert into buyers.  

Using SQL and Power BI, the analysis explores the complete user journey — from product view to purchase — to identify drop-off points, behavioral patterns, and opportunities for improving conversion.

---

##  Objectives
- Analyze user interaction across the funnel (view → cart → purchase)  
- Identify key drop-off points and conversion bottlenecks  
- Understand user engagement and behavior patterns  
- Provide actionable recommendations to improve conversion rates  

---

##  Tools & Technologies
- **SQL (Databricks)** – Data extraction and analysis  
- **Power BI** – Data visualization and dashboard creation  
- **Python (Pandas)** – Data preprocessing (sampling 100K records)  

---

##  Dataset
- Source: Kaggle (E-commerce behavior dataset)  
- Size: ~5GB (sampled to 100K records for analysis)  
- Fields used:
  - `event_time`
  - `event_type` (view, cart, purchase)
  - `user_id`

---

##  Key Analysis Performed

### 1. Funnel Analysis
- Tracked user progression from view → cart → purchase  
- Calculated conversion rates and identified drop-offs  

### 2. Drop-off Analysis
- Measured where users leave the funnel  
- Identified major drop at the initial stage (view → cart)

### 3. User Segmentation
- Classified users into buyers and non-buyers  
- Analyzed conversion distribution  

### 4. Time to Purchase
- Measured average time taken from first interaction to purchase  

### 5. Event Path Analysis
- Studied real user journeys  
- Identified non-linear behavior and repeated browsing  

### 6. Engagement Analysis
- Segmented users based on interaction levels (1, 2–5, 6+ events)  

---

##  Key Findings

- Only ~4% of users move from view to cart  
- ~93% of users do not convert into buyers  
- Majority of users drop off at the initial stage  
- Users who convert tend to do so quickly (~9 minutes)  
- User journeys are non-linear with repeated browsing behavior  
- High engagement does not necessarily lead to conversion  

---

##  Recommendations

- Improve product pages (better visuals, reviews, clear pricing)  
- Add personalized recommendations and nudges  
- Target high-intent users with offers  
- Reduce friction in decision-making  
- Improve tracking of cart and purchase events  

---

##  Dashboard

An interactive Power BI dashboard was created to visualize:
- Funnel conversion  
- User engagement distribution  
- Event-level behavior  
- Key insights and business recommendations  

---

##  Limitations

- Dataset represents a single-day sample  
- Cannot analyze long-term trends like retention  
- Possible inconsistencies in event tracking  

---

## Conclusion

The analysis highlights a clear gap between user activity and conversion. While the platform attracts significant traffic, most users drop off before showing purchase intent. Improving early-stage engagement and guiding users through the decision-making process can significantly enhance conversion rates.

---

## 📬 Contact

If you’d like to discuss this project or collaborate, feel free to connect.
