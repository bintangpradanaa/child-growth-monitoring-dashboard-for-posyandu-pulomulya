# Child Growth Monitoring Dashboard (Posyandu Desa Pulomulya)

## Resource
- 📈 [Dashboard Looker Studio](https://lookerstudio.google.com/reporting/7dcb70ff-8547-466c-adf0-27753bba7151)
- 🔗 [Presentation Deck](https://drive.google.com/file/d/1APzV2n7Fyn8uCUfeULRrUg9jF6xzpzt2)

## Project Overview
Posyandu Desa Pulomulya previously relied on manual recording for monitoring toddler (balita) health data. This caused delays in reporting, increased risk of data errors, and limited the ability to quickly identify at-risk children (such as malnutrition or stunting risk).

We developed a digital dashboard system to transform manual data recording into a structured, automated, and visualized monitoring system for child growth tracking. The system supports real-time monitoring of child development indicators and improves reporting efficiency for health workers (kader Posyandu).

## Objective
- Digitize manual Posyandu data recording into a structured system  
- Provide fast and clear visualization of toddler health conditions  
- Improve early detection of at-risk children (stunting, malnutrition, underweight)  
- Accelerate and simplify reporting to higher administrative levels  
- Support data-driven decision making for community health monitoring  

## System Workflow
### 1. Data Input (Form System)
- User (Kader) inputs child data (name, gender, birth date, weight, height, etc.)
- System automatically calculates:
  - Age (months)
  - Weight-for-Age (BB/U)
  - Height-for-Age (TB/U)
  - WHO-based nutritional category
  - Age group classification

### 2. Automated Data Processing
After input submission:
- Data is automatically enriched with calculated indicators
- Stored into structured dataset ("Data Sheet")
- Ensures consistency, accuracy, and standardized classification

### 3. Dashboard Visualization
- Uses processed dataset as the main source
- Provides real-time monitoring of child health conditions
- Updates automatically when new data is added

## Key Dashboard Components
### KPI Metrics
- Total Number of Toddlers
- Male vs Female Distribution
- Number of Stunting Risk Cases
- Number of Underweight & Malnutrition Cases

### Visual Analytics
- Child population trend
- Distribution by village/dusun
- Age group distribution
- Nutritional status distribution (BB/U & TB/U)

### Detail View
- Individual child health records
- Growth tracking per child

## Key Insights
- Successfully digitized the data recording process, enabling 100% of child health data to be captured through a digital form and automatically stored in a centralized database.
- Automated key health indicator calculations, including TB/U (Height-for-Age) and BB/U (Weight-for-Age) Z-score analysis, reducing manual errors and accelerating growth assessment.
- Delivered a real-time monitoring dashboard in Looker Studio with 10+ visualizations, covering key indicators, trends, distribution, age groups, and nutritional status.
- Achieved 100% automated data updates, ensuring every new input is instantly reflected in the dashboard without manual refresh.
- Improved monitoring and reporting efficiency by providing filterable, detailed child-level data for users.

## Impact
- Faster and more accurate reporting for Posyandu cadres  
- Improved early detection of stunting and malnutrition risk  
- Reduced manual workload in data processing  
- Better communication between Posyandu and higher health authorities  
- Data-driven decision support for child health programs  
