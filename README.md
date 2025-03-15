Conflict Analysis Project

Project Overview

This project analyzes conflict events from 1997 to 2024, exploring their distribution across different regions, time periods, and population densities. Through data cleaning, statistical analysis, and visualization, we identify conflict hotspots, temporal trends, and the relationship between conflict events and population density.

Data Source

The dataset used in this analysis is sourced from [your data source, e.g., ACLED or other], containing 52,463 conflict event records with the following key attributes:
	•	Event Type (e.g., riots, protests, armed conflicts)
	•	Timestamp (date and time of the event)
	•	Fatalities (number of casualties)
	•	Geographic Location (latitude, longitude)
	•	Population Density (population of the affected area)

Analysis Topics

This project focuses on four key questions, using ggplot2 for visualization:

1. Fatalities by Event Type
	•	Question: How do different types of conflict events impact fatalities?
	•	Method: Boxplot (geom_boxplot) in ggplot2
	•	Findings:
	•	Some event types are associated with significantly higher casualties
	•	Outliers were removed to provide a clearer view of the distribution

2. Conflict Events vs. Population Density
	•	Question: Is there a correlation between population density and the number of conflict events?
	•	Method: Scatter plot (geom_point) + Regression line (geom_smooth)
	•	Findings:
	•	Areas with higher population density tend to have more conflict events
	•	After applying a logarithmic transformation, the relationship is clearer

3. Conflict Trends Over Time
	•	Question: How has the number of conflict events changed over time?
	•	Method: Line chart (geom_line) using time-series data
	•	Findings:
	•	Significant increase in conflict events in recent years
	•	Some seasonal patterns can be observed

4. Top Conflict Hotspots
	•	Question: Which locations experience the highest number of conflicts?
	•	Method: Bar chart (geom_bar)
	•	Findings:
	•	Abuja, Maiduguri, Lagos, and other cities emerge as major conflict hotspots
	•	These cities have a significantly higher number of conflict events compared to others
