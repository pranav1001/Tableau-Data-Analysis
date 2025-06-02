# Tableau-Data-Analysis
This Repo contains my Data Analysis and Visualization Projects.

Dashboard Link: https://public.tableau.com/app/profile/pranav.nayak/vizzes

The datasets are extracted from multiple sources and are extremely large; therefore, they are not uploaded to GitHub due to file size limitations.

# PROJECT 1 - INSTACART DATA ANALYTICS
## Detailed Analysis
For in-depth analysis and findings, please refer to [Instacart_Data_Analysis.pdf](./Instacart_Data_Analysis.pdf)


Project Overview
This project analyzes grocery shopping patterns using a comprehensive Instacart dataset containing over 3 million grocery orders from more than 200,000 users. The analysis leverages Tableau to create interactive visualizations and uncover insights about customer behavior, product preferences, and operational patterns.

Key Analysis Areas
Service Analysis

Identified the busiest days of the week and peak shopping hours

Analyzed customer reorder frequency and timing patterns

Examined the relationship between order timing and customer behavior

Product Analysis

Determined top-selling products and bestsellers

Analyzed first-time purchase patterns and customer preferences

Calculated reorder probabilities for different products

Studied typical order sizes and item quantities per transaction

Category Analysis

Created treemap visualizations of the most popular aisles and product categories

Analyzed department-level sales frequency and performance

Grouped time periods to identify distinct shopping patterns (weekend rush, evening hours, early birds, etc.)

Methodology
The project employed Tableau's relationship modeling to connect six different data tables (orders, products, aisles, departments, and order-product mappings). Advanced Tableau features were used including calculated fields, filters, groupings, and various chart types to create a comprehensive data story.

Business Value
This analysis provides actionable insights for inventory management, staffing optimization, marketing campaigns, and customer experience improvements by understanding when customers shop, what they buy, and how their purchasing behaviors evolve over time.


# PROJECT 2 – NATURAL DISASTER IMPACT ANALYSIS ON ENERGY REFINERIES

## Project Overview

This project leverages Tableau to analyze the impact of natural disasters on energy company refineries in the United States, using FEMA disaster data from 2004–2015. The analysis integrates disaster occurrence data with refinery locations to identify risk patterns, visualize geographic vulnerabilities, and inform business continuity planning for the energy sector.

## Key Analysis Areas

**Natural Disaster Mapping**

- Visualized a decade of natural disaster incidents across the contiguous U.S. using Tableau map visualizations.
- Applied color encoding to distinguish disaster types (e.g., Hurricane, Flood, Fire).
- Incorporated size encoding to represent the frequency of incidents per county.
- Enabled interactive filtering by state and disaster type for granular analysis.

**Refinery Location Analysis**

- Selected a major energy company with at least five U.S. refineries (excluding Alaska, Hawaii, and territories).
- Mapped refinery locations alongside disaster data to assess geographic exposure.
- Used shape and color encoding to differentiate refineries from disaster incidents (e.g., refineries marked as red stars).

**Disaster Impact on Refinery States**

- Filtered disaster maps to only states with company refineries.
- Annotated refinery locations for clarity and labeled each with refinery names.
- Identified and listed disaster types impacting each refinery state (e.g., Fire and Hurricane in New Jersey; Flood, Coastal Storm, and Hurricane in Louisiana).

**Top 4 Disaster Types at Refinery Locations**

- Created calculated fields in Tableau to:
  - Count disaster occurrences (Number of Incidents)
  - Rank disaster types by frequency
  - Segment maps into a 2x2 grid (multi-map) for side-by-side comparison of the top four disaster types.
- Labeled each map with the disaster name and incident count.
- Determined that the most frequent disaster impacting refinery areas is Severe Storm.

**Storytelling and Business Value**

- Compiled all visualizations into a Tableau Story, using logical rhetoric.
- The story enables stakeholders to:
  - Identify which disasters most frequently threaten refinery operations.
  - Prepare targeted disaster response and mitigation strategies.
  - Optimize resource allocation for safety and operational continuity.

## Methodology

- Data preparation included merging FEMA disaster records with refinery site data.
- Tableau was used for all visualizations, employing calculated fields, filters, color/size/shape encoding, and annotation features.
- Multi-map (trellis chart) techniques enabled comparative analysis of disaster types across refinery locations.

## Business Value

This analysis provides energy companies with actionable insights to:
- Prioritize disaster preparedness in high-risk refinery locations.
- Inform insurance, infrastructure investment, and emergency planning.
- Enhance operational resilience by understanding historical disaster patterns and their impact on critical assets.

---



# PROJECT 3 – INTEGRATED ANALYSIS: K-MEANS CLUSTERING USING TABLEAU & R
## Project Overview
This project demonstrates an integrated data analysis workflow by applying K-means clustering to the Titanic dataset using R, and visualizing the resulting clusters in Tableau through R integration. The objective is to uncover passenger survival patterns by segmenting the dataset into meaningful clusters and profiling the characteristics associated with high survivability.




---
*For detailed visualizations and findings, refer to the Tableau workbook and accompanying documentation.*

