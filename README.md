# Road Crash Reporting — Exploratory Data Analysis

An end-to-end data analysis project on the Montgomery County Crash Reporting Drivers Dataset, a public dataset capturing road crash details including weather, road conditions, vehicle behavior, driver fault, and injury severity.


# Tech Stack
# Python · Pandas · NumPy · Matplotlib · Seaborn · Plotly · Scikit-learn (KMeans)


# Project Structure
- Data Cleaning & Preprocessing: Handled missing values by filling nulls with 'UNKNOWN', standardized text to uppercase for consistency, and converted the Crash Date/Time column to datetime format to enable time-based analysis.

- Exploratory Data Analysis: Analyzed 39 features across crash records to surface patterns in collision types, driver behavior, road conditions, and injury severity through statistical summaries and visual distributions.

- KMeans Clustering for pattern identification: Applied KMeans clustering on weather, surface, and lighting conditions to group crash scenarios and identify that 50% of crashes cluster around conditions typically considered safe — clear weather, dry roads, and daylight.

- Interactive visualizations (Plotly): Built interactive charts using Plotly to allow dynamic exploration of crash distributions across weather conditions, collision types, fault rates, and traffic control presence.

- Managerial Insights per finding: Translated each analytical finding into actionable policy recommendations, such as dynamic speed limits based on real-time conditions, ADAS adoption incentives, and replacing traditional intersections with roundabouts.


# Key Findings
- Weather & Environment: Counterintuitively, 50% of crashes occur under clear weather, dry surfaces, and daylight — disproving the assumption that optimal conditions prevent accidents. Validated using KMeans clustering.
- Driver Fault in Solo Crashes: Single-vehicle crashes show the highest driver fault rate (~70%), while multi-vehicle scenarios like sideswipes show lower individual fault attribution.
- Traffic Control Effectiveness: Crash severity remains nearly equal with or without traffic controls present, suggesting infrastructure alone is insufficient to reduce accident risk.


Data Source: data.gov — Crash Reporting Drivers Data 
Group project — MS Information Systems, Santa Clara University
