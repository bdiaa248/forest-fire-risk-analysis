# Forest Fire Risk Analysis – Montesinho Natural Park

## Project Overview
Wildfires represent a significant environmental and economic threat, particularly in protected natural areas.  
This project analyzes historical wildfire data from **Montesinho Natural Park (Portugal)** to identify high-risk environmental conditions and geographic zones associated with increased fire frequency and severity.

**Goal:** Transform raw wildfire records into actionable insights that support wildfire prevention, monitoring, and resource allocation strategies.

![Project Overview](screenshots/Project Overview.png)

---

## Business / Environmental Context
The analysis is conducted from the perspective of a data analyst supporting wildfire prevention efforts for a public environmental agency.

**Key Objectives:**
- Identify high-risk geographic regions within the park.
- Understand weather and drought conditions associated with increased fire spread.
- Support proactive, data-driven wildfire prevention strategies.

---

## Dataset Summary
- **Source:** Historical wildfire records from Montesinho Natural Park
- **Time Period:** 2000 – 2003
- **Granularity:** Each row represents a single fire event
- **Key Features:**
  - Spatial coordinates (X, Y)
  - Weather conditions (temperature, relative humidity, wind, rainfall)
  - Fire Weather Index components (FFMC, DMC, DC, ISI)
  - Burned area (hectares)

---

## Exploratory Data Analysis (EDA)
Initial exploration focuses on understanding distributions and patterns in key wildfire-related variables.

**Key Observations:**
- Most fire events result in very small burned areas.
- The burned area distribution is highly right-skewed, with rare but extreme fire events.
- Temperature shows a relatively symmetric distribution.
- ISI is right-skewed, indicating that most fires have low spread potential, with a few high-risk cases.

![EDA](screenshots/EDA.png)

---

## Correlation Analysis
Scatter plots and correlation metrics were used to examine relationships between weather conditions and fire spread indicators.

**Findings:**
- **Temperature vs Initial Spread Index (ISI):** Moderate positive correlation.
- **Temperature vs Relative Humidity (RH):** Moderate negative correlation.

These relationships suggest that higher temperatures are associated with drier conditions and increased wildfire risk, though temperature alone does not fully explain extreme fire behavior.

![Correlation Analysis](screenshots/Correlation Analysis.png)

---

## Geographic Risk Segmentation
Geographic segmentation was performed using spatial coordinates to identify regions with elevated wildfire risk.

**Key Findings:**
- Fire events are not evenly distributed across the park.
- Certain regions experience significantly higher fire frequency and drought severity.
- Distinct geographic zones can be classified into different fire risk levels (High, Moderate, Low).

![Geographic Risk Segmentation](screenshots/Geographic Risk Segmentation.png)

---

## Executive Summary
A consolidated summary of key insights and recommendations derived from the analysis.

**Highlights:**
- Rare extreme fires drive most of the total burned area.
- Temperature and drought indicators (DC, ISI) are critical early warning signals.
- Geographic risk-based resource allocation is more effective than uniform distribution.

![Executive Summary](screenshots/executive_summary.png)

---

## Business / Operational Recommendations
1. Prioritize monitoring, patrols, and early warning systems in high-risk geographic zones.
2. Allocate wildfire prevention resources based on spatial risk segmentation.
3. Use drought severity (DC) and fire spread indicators (ISI) as early signals for intervention.
4. Focus on proactive prevention rather than reactive fire suppression.

---

## Tools Used
- Microsoft Excel
- Pivot Tables
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Geographic Risk Segmentation
- Data Visualization

---

*Created by Abdelrahman Diaa*
