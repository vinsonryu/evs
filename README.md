**"Forecasting Urban EV Charging Station Demand Using Time Series and Weather Data"**

---

### 🧠 Problem Statement:

> With the rise of electric vehicles (EVs), cities are rapidly expanding their charging infrastructure. However, demand at EV charging stations varies by time, location, and weather. This project aims to forecast charging station usage to help optimize placement, maintenance, and load management.
>

📌 Project Overview
Analyzed 10+ years of EV charging sessions (100,000+ records) to understand the relationship between EV sales, weather, charging demand, cost savings, and environmental impact. Built a forecasting model and data-driven insights to support infrastructure planning and sustainability analysis.

🔑 Key Questions Answered
📈 EV Sales Growth: How has EV adoption evolved over the years?

🔋 Charging Demand: How does EV sales growth drive charging demand?

🌦 Weather Correlation: Is there a link between weather patterns and charging usage?

💰 Cost Comparison: Are EVs cheaper to operate than gasoline vehicles?

🌍 Environmental Impact: How much CO₂ has been reduced, and what are the real-world equivalents?

🗺 Infrastructure Gaps: Are charging stations well-distributed across regions?

🛠 Tools & Technologies
Python: Pandas, NumPy, Matplotlib, Seaborn, Folium

Forecasting: Facebook Prophet

Data Visualization: Interactive maps (Folium), correlation heatmaps, rolling averages

Data Sources: EV charging sessions, EV sales data, historical weather data (Open-Meteo API)

📊 Key Findings
1. EV Sales vs. Charging Demand
EV sales increased steadily, driving a consistent rise in charging demand, especially post-2018.

Top 5 manufacturers accounted for the majority of sales.

2. Weather Impact on Charging
Mild correlation with temperature; charging demand peaks in colder months.

Precipitation showed minimal impact on demand.

3. Cost Savings vs. Gasoline
93–100% of sessions in analyzed years were cheaper than gasoline.

Average savings per session ranged from $0.21 to $2.29.

4. Environmental Benefits
930,936 kg CO₂ saved, equivalent to:

🌳 42,762 trees planted

🚗 6.7M gasoline miles offset

5. Infrastructure Insights
47 unique charging stations mapped using Folium revealed underserved suburban areas with expansion potential.

📈 Forecasting Results
Built a Prophet model integrating temperature, precipitation, and COVID-19 impact.

Achieved R² = 0.82 and reduced RMSE to 5,858 kWh, enabling accurate monthly demand forecasting.

🖼 Visual Highlights
EV Sales Trends (quarterly)

Charging Demand vs. Rolling Average

Weather Correlation Heatmap

Cost Savings KDE Distribution

Environmental Impact (CO₂ savings → trees + miles)

Interactive Charging Station Map (Folium)

🚀 Skills Demonstrated
Data wrangling & feature engineering

Time-series forecasting

Cost-benefit analysis & sustainability metrics

Data visualization & geospatial analysis

Business-driven storytelling

