# NYC Air Quality Analysis (2008-2023)

🚧 **Work in Progress** - This project is actively being developed

## Project Overview
This project analyzes 15+ years of New York City air quality data to identify pollution trends, examine the COVID-19 pandemic's impact on air quality, and compare pollution levels across different neighborhoods.

## Key Findings

### 1. Long-Term Trends (2008-2023)

![NYC Air Quality Trends](pollution_trends_2008_2023..png)

- **Nitrogen Dioxide (NO2)**: Decreased **47.1%** (28.29 → 14.96 ppb)
  - Major improvement driven by cleaner vehicles and stricter emissions regulations
- **Fine Particles (PM 2.5)**: Decreased **35.4%** (12.27 → 7.92 mcg/m³)
  - Significant air quality improvement from environmental policies
- **Ozone (O3)**: Increased **39.1%** (24.76 → 34.44 ppb)
  - Rising levels likely connected to climate change and warmer temperatures

### 2. COVID-19 Impact (2019-2021)

![COVID-19 Impact on Air Quality](covid_impact_2019_2021.png)

- **NO2 dropped 11%** during 2020 lockdown (reduced traffic and economic activity)
- **PM 2.5 dropped 11.8%** during 2020 lockdown (minimal construction and commuting)
- **Ozone remained stable** (complex atmospheric chemistry unaffected by reduced emissions)
- Pollution levels began returning toward pre-pandemic baselines in 2021 as NYC reopened

### 3. Seasonal Patterns

![Seasonal Air Quality Patterns](seasonal_patterns.png)

**Nitrogen Dioxide (NO2):**
- **41% higher in winter** (22.60 ppb) compared to summer (15.98 ppb)
- Winter increase driven by building heating systems and reduced air circulation

**Fine Particles (PM 2.5):**
- **6.5% higher in summer** (9.43 mcg/m³) compared to winter (8.85 mcg/m³)
- Summer increase likely from construction activity and dry conditions

**Ozone (O3):**
- Only measured during summer months (requires sunlight and heat to form)
- No winter baseline for comparison
### 4. Borough Comparison

![Borough Air Quality Comparison](borough_comparison.png)

**Key Findings:**

**Manhattan:** Consistently worst air quality across most pollutants
- NO2: 25.43 ppb (**80% higher** than Staten Island)
- PM 2.5: 10.20 mcg/m³ (**27% higher** than Staten Island)
- Driven by dense traffic, construction, and limited green space

**Staten Island:** Cleanest air quality in NYC
- Lowest NO2 (14.10 ppb) and PM 2.5 (8.05 mcg/m³)
- Benefits from less density, more vegetation, and ocean breezes

**Outer Boroughs (Queens, Bronx, Brooklyn):**
- Mid-range pollution levels
- Queens has highest ozone (32.46 ppb) due to suburban sun exposure

**Urban Density Impact:** Clear correlation between population density and air pollution—Manhattan's compact development results in significantly worse air quality compared to less dense boroughs.

### 5. Neighborhood Disparities

**Cleanest Areas:**
- Rockaways and coastal neighborhoods benefit from ocean breezes that disperse pollutants
- Lowest NO2 and PM 2.5 levels in the city

**Most Polluted Areas:**
- Midtown Manhattan and Chelsea experience highest pollution from heavy traffic and urban density
- Up to 50% higher pollution levels compared to coastal areas

**Key Insight:** Geographic location and proximity to traffic corridors are major determinants of air quality exposure.

## Technologies Used
- **Python** (pandas, matplotlib) for data analysis and visualization
- **Google Colab** for development environment
- **Data Source**: NYC Open Data - Air Quality Dataset (18,000+ records)

## Dataset Details
- **Time Period**: 2008-2023 (15+ years)
- **Records**: 14,805 measurements across three main pollutants
- **Geographic Coverage**: All five NYC boroughs and 40+ neighborhoods

## What's Next
- [ ] Power BI dashboard for interactive visualizations
- [ ] Seasonal pattern analysis (Summer vs Winter)
- [ ] Time series forecasting for future trends
- [ ] Expanded neighborhood-level deep dive

## About This Project
This is an independent portfolio project demonstrating data cleaning, exploratory data analysis, statistical analysis, and data visualization skills. The project showcases my ability to transform raw data into actionable environmental insights.

**Created by Justin Martinez**  
Data Analytics Student, Syracuse University  
[LinkedIn](https://www.linkedin.com/in/justin-martinez556/) | [GitHub](https://github.com/justinmartinez4040)

---

*Last updated: January 2026*
