# 🚲 Cyclistic Bike-Share Case Study  

## 📌 Project Overview  
This project analyzes **bike-share data (Q1 2019 & Q1 2020)** from **Cyclistic**, a fictional bike-share company in Chicago. The goal is to understand usage patterns between **casual riders** and **annual members**, and provide insights that can help the marketing team convert casual users into paying members.  

The analysis was completed in **R** using an **RMarkdown report** that combines data cleaning, exploratory analysis, and visualization.  

---

## 🎯 Business Task  
Identify key differences in how **casual riders** and **members** use Cyclistic bikes, and recommend strategies to convert more casual riders into annual members.  

---

## 🛠 Tools & Libraries  
- **R / RStudio**  
- **tidyverse** – data wrangling & visualization  
- **lubridate** – date-time manipulation  
- **scales** – formatting chart labels  
- **ggplot2** – creating charts  

---

## 📊 Key Visualizations  
1. **Rides by Day of Week** – members ride more on weekdays; casuals ride more on weekends.  
2. **Average Ride Length by Day** – casuals take longer rides, members take shorter commuter trips.  
3. **Monthly Ride Volume** – member rides are steady, casual rides fluctuate seasonally.  
4. **Top 10 Start Stations** – members use commuter-heavy stations, casuals use touristy areas.  

---

## 🔑 Insights  
- **Members** → consistent weekday usage, shorter rides, commuter-oriented.  
- **Casual riders** → weekend spikes, longer trips, tourist/recreational behavior.  
- **Spatial patterns** → members start at transit hubs, casuals at parks/waterfronts.  

---

## ✅ Recommendations  
- Offer **weekend promotions** targeted at casual riders.  
- Build **employer partnerships** to push memberships for daily commuters.  
- Place **QR-code ads at tourist stations** to encourage casual-to-member conversion.  

---

## 📂 Project Structure  
- `Cyclistic_Case_Study_With_Insights.Rmd` → RMarkdown analysis with code, plots, and insights  
- `Divvy_Trips_2019_Q1.csv` → Q1 2019 trip data  
- `Divvy_Trips_2020_Q1.csv` → Q1 2020 trip data  
- `Cyclistic_Case_Study.html` → Knitted HTML report (visual & narrative output)  

---

## 🚀 How to Run  
1. Clone this repo and open `Cyclistic_Case_Study_With_Insights.Rmd` in **RStudio**.  
2. Install required libraries:  
   ```r
   install.packages(c("tidyverse", "lubridate", "scales"))
