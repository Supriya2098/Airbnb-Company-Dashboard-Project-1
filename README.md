# 🏠 Airbnb Company Dashboard Project

## 🎯 Project Objective
To analyze Airbnb booking data across New York City neighbourhood groups and room types, and design an **interactive Tableau dashboard** that helps understand:
- Booking and pricing trends  
- Neighbourhood and host performance  
- Seasonal variations in demand  
- Review patterns across room types  

The goal is to provide **data-driven insights** that help optimize pricing, improve marketing strategy, and enhance the guest/host experience.

---

## 📘 Project Overview
This project explores Airbnb listings and review data to uncover pricing, booking, and review trends by location and room type.  
It uses Tableau for visual exploration and storytelling, integrating data from multiple sources to present a unified view of Airbnb’s performance across boroughs.

**Key focus areas:**
- Total bookings by neighbourhood group and room type  
- Average prices across neighbourhoods  
- Average reviews per month  
- Top 10 hosts by total reviews  
- Yearly booking growth and trends  
- Geospatial distribution of listings  

---

## 💼 Business Tasks / Questions
1. Which neighbourhoods and room types contribute most to total bookings?  
2. What are the average prices and review patterns by neighbourhood?  
3. Who are the top-performing hosts based on reviews?  
4. How do bookings fluctuate over time (month/year)?  
5. What opportunities exist for pricing and location optimization?

---
**Sample Screenshot:**
### Dashboard <img width="1204" height="666" alt="Airbnb Company Dashboard Project" src="https://github.com/user-attachments/assets/24ffd859-e0c1-40c4-8daf-b43c5acc46b0" />

## 🛠️ Tools & Technologies Used
| Category | Tools |
|-----------|-------|
| Data Cleaning & Analysis | Python (pandas, numpy, matplotlib) |
| Data Visualization | Tableau Desktop / Tableau Public |
| Mapping | Tableau Maps (Mapbox integration) |
| Reporting | Google Slides / PowerPoint |
| Version Control | Git & GitHub |

---

## ⚙️ Process Summary

### Data Collection
- Source: Airbnb dataset containing listing details, prices, reviews, and host data.
- Format: CSV (listings, reviews).

### Data Cleaning
- Removed duplicates and nulls.  
- Converted price fields to numeric.  
- Standardized neighbourhood names and room types.  
- Extracted review month/year for trend analysis.

### Data Transformation
- Aggregated metrics by `Neighbourhood Group`, `Room Type`, and `Host`.  
- Created derived measures: `Total Bookings`, `Average Price`, and `Average Monthly Reviews`.

### Exploratory Data Analysis
- Identified booking and pricing trends by borough.  
- Visualized host activity and neighbourhood performance.  
- Mapped geospatial listing density.

###  Dashboard Development (in Tableau)
- Built individual charts (bar, tree map, donut, heat map, line chart).  
- Combined all visuals into an interactive **Airbnb Company Dashboard**.  
- Added filters, legends, and tooltips for easy data exploration.

### Publishing
- Published to Tableau Public for sharing and embedding.  
- Exported supporting presentation slides for business reporting.

---

## 📊 Key Insights

| Insight | Description |
|----------|-------------|
| **1. High-value Neighbourhoods** | Manhattan has the highest average price  |
| **2. Dominant Booking Areas** | Brooklyn and Manhattan together account for ~85% of total bookings. |
| **3. Seasonal Peak** | Booking volume peaks during June–July, indicating summer travel demand. |
| **4. Room Type Preferences** | “Entire home/apartment” listings attract the most bookings and revenue. |
| **5. Top Hosts** | A few high-performing hosts gather the majority of reviews (>2000 reviews), showing concentrated success. |
| **6. Underperforming Regions** | Staten Island and Bronx show lower booking activity, potential areas for marketing or pricing strategy. |

---

## 💡 Recommendations

1. **Dynamic Pricing:**  
   Increase prices during the summer peak season in high-demand boroughs.

2. **Expand in Low-Competition Areas:**  
   Encourage new listings and promotions in Staten Island and Bronx to boost supply and awareness.

3. **Host Engagement:**  
   Develop incentive programs for top hosts to retain and scale their operations.

4. **Customer Retention Strategies:**  
   Promote repeat stays and offer discounts in off-peak months.

5. **Data Monitoring:**  
   Continue tracking trends quarterly to adjust marketing and pricing strategies dynamically.
 **Dashboard:** [View on Tableau Public →](https://public.tableau.com/views/airbnbcompanydashboardproject/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


---

## 📦 Project Deliverables

| File / Folder | Description |
|----------------|-------------|
| `data/` | Raw and cleaned datasets used in analysis |
| `notebooks/` | Jupyter notebooks for preprocessing and analysis |
| `dashboard/` | Tableau workbook and dashboard screenshots |
| `reports/` | Presentation slides and executive summary |
| `src/` | Python scripts for data handling |
| `README.md` | Project overview and documentation |

---

## 🔗 Output & Live Dashboard

**Interactive Dashboard (Tableau Public):**  
👉 [Click here to view the live dashboard](https://public.tableau.com/views/airbnbcompanydashboardproject/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

  
**Author:** Supriya Kusuma 
**gmail:** supriyakusuma0905@gmail.com
**linkedln id:** https://www.linkedin.com/in/supriya-kusuma09/



---
