# Hospitality-Data-Analysis-for-AtliQ-Grands.

### OverView of project 
-	Background of AtliQ Grands: A distinguished brand with two decades of industry presence, currently navigatin challenges posed by competition and managerial decisions.
-	Business and Data Intelligence Initiative: To counteract diminishing market share and revenue, the managing director seeks to integrate Business and Data Intelligence strategies.

<img width="632" alt="DashBoard " src="https://github.com/AxmedGabtan/Hospitality-Data-Analysis-for-AtliQ-Grands./assets/121066015/797580bb-c260-438b-81df-0e7a2f2e3e4a">

### Data Source 
The dataset was downloaded from Codebasics challenge #1 as CSV files, containing detailed information about Atliq Grands' hospitality in India

### Task Overview
🎯 Engaged as a data analyst to scrutinize sample data and generate insights using Power BI 

### Key Responsibilities:
 	Formulate metrics based on the provided list.
 	Craft a dashboard in alignment 📊. 
 	Unearth additional insights beyond the initial requirements.
  
  ### Tools Utilized🛠️: 
  Harnessing the capabilities of Power BI for streamlined data analysis.

### Data Aanlysis 
Includes an interesting column in Power BI
```  
WG = 
 Switch (
         True(),
             WEEKNUM(dim_date[date]) <= 19,
              "Week x ",
             WEEKNUM(dim_date[date]) <= 22, "Week x+1",
             WEEKNUM(dim_date[date]) <= 27, "Week x+2",
             WEEKNUM(dim_date[date]) <= 31, "Week x+3",
             WEEKNUM(dim_date[date]) <= 35, "Week x+4",
             WEEKNUM(dim_date[date]) <= 39, "Week x+5",

                          Blank()
            )
```

### Results 
1. Over 14 weeks, Altiq Grands amassed 1.71 billion in total revenue across four cities,
2. Mumbai and Banglore has best-performce interms of revenue with ₹668.64 million and ₹420 million respectiveley where Delhis has lowest performance with revenue ₹294 million 
3. Week 29 saw a revenue peak of ₹139.73 million, contrasting sharply with the lowest revenue of ₹21 million in Week 32, despite its highest occupancy rate of 65.31%

### Recommandation 
 - Atliq Grands can boost revenue by maximizing peak period earnings through targeted marketing and exclusive offers
 - Focus on enhancing occupancy rates during slower periods with special promotions involves implementing targeted marketing campaigns and exclusive deals
 - Improving staffing levels and ensuring excellent customer service will further elevate guest experiences and revenue.
 - Given the positive correlation between Booking and revenue, focus on driving more bookings to naturally increase total revenue.

### limitations 
- Further analyses of customer feedback required to identify areas for improvement and enhance overall customer satisfaction build trust and attract more bookings during off-peak weeks.


