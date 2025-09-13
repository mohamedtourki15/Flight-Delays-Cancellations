# Flight Delays & Cancellations Analysis

**Project Goal:**  
Analyze US domestic flights in 2015 to identify patterns in delays and cancellations, and provide actionable insights to improve operations and reduce passenger disruption.

**Dataset:**  
- `flights.csv` (US domestic flights operated by large carriers, 2015)  
- Additional files available in the dataset can be used alongside `flights.csv`.

**Methodology:**  
1. Data cleaning and validation (handling missing values, creating derived columns).  
2. Exploratory Data Analysis (EDA) to identify trends in delays and cancellations.  
3. Feature engineering: calculated metrics like `total_delay`, `delay_type`, `is_cancelled`, `month`, `weekday`, `flight_hour`.  
4. Built three interactive Tableau visualizations to uncover insights.  

**Key Visualizations:**  
1. **Airlines & Airports Comparison** – ranked bar charts showing average arrival/departure delay and cancellation rate.  
2. **Delay Causes Heatmap** – stacked bar/heatmap of delay reasons (carrier, weather, NAS, security, late aircraft) by month and airport.  
3. **Route-Level Impact** – scatter/bubble chart showing origin-destination pairs, flight volume, and average delays.

**Key Insights:**  
- Top 3 airlines by average arrival delay: Airline A, B, C.  
- Worst airports by cancellation rate: Airport X, Y.  
- Late aircraft is the dominant cause at major hubs during peak months.  

**Deliverables:**  
- Cleaned dataset (`flights_cleaned.csv`)  
- Tableau workbook (`Flight_Delays_Cancellation.twbx`)  
- Dashboard screenshots (`dashboard_screenshots/`)  
- Optional walkthrough video (`walkthrough.mp4`)  
- Executive summary of findings and recommendations  

**Skills & Tools:**  
- Data Analysis & Cleaning (Python, pandas)  
- Tableau Visualization & Dashboarding  
- EDA & Metrics Analysis  
- Geospatial Aggregation & Mapping  
- Insight Communication & Storytelling
