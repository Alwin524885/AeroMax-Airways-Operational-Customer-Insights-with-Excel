# ✈️ Airline Data Analysis with Excel

This project demonstrates a complete workflow of **data cleaning, processing, and analytics** using Microsoft Excel on airline operational and customer datasets.  

---

## 📂 Project Structure

1. **Data Cleaning**
   - Remove duplicates based on keys (Passenger_ID, Flight_Number, Date).
   - Handle missing data:
     - Numerical fields → mean/median replacement or flagged for removal.
     - Categorical fields → most frequent value or "Unknown".
   - Ensure consistent formats:
     - Dates → Date format.
     - Times → Time format.
     - Numbers → Ticket Price, Revenue, Flight Distance, Flight Delay Minutes.
     - Text → standardized spelling/case (airport names, codes, cabin classes).
   - Validate ranges & anomalies:
     - Outliers flagged (e.g., distance > 20,000 km).
     - Manual review for abnormal records.

2. **Data Processing**
   - **Age Groups**: 18–29, 30–39, 40–49, 50+.
   - **Delay Categories**:
     - On-Time: ≤ 30 min  
     - Moderate: 31–120 min  
     - Severe: > 120 min
   - **Revenue Metrics**:
     - Revenue-to-Cost Ratio.
     - Profit = Revenue − Cost.
   - **Flight Distance Categories**:
     - Short-haul, Medium-haul, Long-haul.
   - **Passenger Feedback Summaries**:
     - PivotTables by Age Group, Ticket Class, Frequent Flyer Status.

3. **Data Analytics**
   - **Flight Delay Analysis**:
     - Avg, median, and max delays per flight/route.
     - Airport rankings by delay.
     - Visualizations: histograms, boxplots, heatmaps.
   - **Customer Satisfaction**:
     - Avg scores by demographics & ticket class.
     - Identify low-satisfaction groups.
     - Visuals: bar & line charts.
   - **Revenue vs Cost**:
     - Profitability analysis by flight.
     - Cost-to-Revenue ratios.
     - Pivots by route, aircraft type, time.
   - **Fuel Efficiency**:
     - Compare fuel cost across distances.
     - Scatter plots: distance vs. cost per seat.

---





## 📖 Author
👤 **Alwin Davis Babu**  
📚 Shipping & Logistics Management Student | Excel Data Analytics Enthusiast  

---
