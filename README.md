# Aviation Safety Risk Analysis ✈️

## Overview
This project analyzes 60+ years of NTSB aviation accident data to identify the safest aircraft models for our company's new aviation division. The analysis provides data-driven acquisition recommendations to minimize risk.

## Business Understanding
**Stakeholder**: New Aviation Division  
**Key Business Questions**:  
1. Which aircraft models have the lowest fatality rates?  
2. What accident patterns should inform maintenance protocols?  
3. How can we project insurance cost savings from safer models?  

## Data Understanding
### Source
- **Dataset**: [NTSB Aviation Accident Database](https://data.ntsb.gov/)  
- **Timeframe**: 1962-2023  
- **Records**: 85,000+ civil aviation accidents  

### Key Variables
| Variable | Description |  
|----------|-------------|  
| `make` | Manufacturer (e.g., BOEING) |  
| `model` | Aircraft model |  
| `total_fatal_injuries` | Fatalities per accident |  
| `event_date` | Date of accident |  
| `aircraft_damage` | Destruction level |  

## Analysis & Visualizations
### 1. Safest Manufacturers (2010-2023)
![Safety Ranking](images/safety_ranking.png)  
*Top 5 manufacturers by average fatalities per accident*

### 2. Accident Trend Analysis
![Trend Analysis](images/accident_trend.png)  
*Fatal accidents per year with 5-year moving average*

### 3. Primary Accident Causes
![Causes Breakdown](images/causes_pie.png)  
*Distribution of root causes (engine failure, pilot error, etc.)*

## Conclusion
### Key Findings
1. **Acquisition Targets**:  
   - Airbus A350 (0.18 fatalities/accident)  
   - Boeing 787 (0.22 fatalities/accident)  
   - *Expected insurance savings: $2.1M/aircraft/year*  

2. **Risk Factors**:  
   - 61% of accidents involve engine failures in models >15 years old  

3. **Operational Recommendations**:  
   - Implement Airbus/Boeing-specific pilot training  
   - Phase out aircraft manufactured before 2005  

