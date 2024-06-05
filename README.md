# Data Visualization - Air Quality Data (Tableau) 

My Tableau Dashboard for this project:

[https://public.tableau.com/app/profile/krishnamoorthy.juttoo.chandrasekaran/viz/SolutionWeek7/Dashboard1](https://public.tableau.com/views/IndiaAirQualityData-Dashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)https://public.tableau.com/views/IndiaAirQualityData-Dashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link


Context
Since industrialization, there has been an increasing concern about environmental pollution. As mentioned in the WHO report 7 million premature deaths annually are linked to air pollution, air pollution is the world's largest single environmental risk. Moreover as reported in the NY Times article, India’s Air Pollution Rivals China’s as World’s Deadliest it has been found that India's air pollution is deadlier than China's.
You can explore India’s air pollution levels more granularly using this dataset.
Content
This data is combined(across the years and states) and is largely a clean version of the Historical Daily Ambient Air Quality Data released by the Ministry of Environment and Forests and Central Pollution Control Board of India under the National Data Sharing and Accessibility Policy (NDSAP).
Building a Tableau Dashboard for the India Air Pollution dataset involves several steps. Below are the key components and steps that you can follow: Can we relate the air quality changes to changes in Environmental policy in India?
Dashboard Components:
1. Map Visualization:
-	Use geographical maps to visualize air quality levels across different states or regions in India.
-	Color code the map markers based on the air quality index (AQI) or other relevant metrics.
2. Time Series Charts:
-	Create time series line charts to depict changes in air quality over the years.
-	Group the data by months or years to identify patterns and trends.
3. Policy Change Timeline:
-	Integrate a timeline component to showcase key environmental policy changes in India.
-	Highlight these policy change events on the timeline to observe correlations with air quality variations.

4. Filter Options:
-	Implement filters for users to select specific states, periods, or pollutant types.
-	Allow users to customize their views based on their interests or research questions.
5. Comparative Analysis:
-	Include comparative charts to showcase air quality comparisons between different states or regions.
-	Utilize bar charts or line charts to illustrate variations in air quality metrics.
6. Top Pollutant Analysis:
-	Identify and display the top pollutants contributing to poor air quality.
-	Utilize bar charts or pie charts to represent the proportion of each pollutant.

7. Insightful Annotations:
-	Use annotations to highlight specific data points, events, or trends that stand out in the analysis.
-	Provide context and explanations for these annotations.
Brief About Dataset:
This data is combined (across the years and states) and is largely a clean version of the Historical Daily Ambient Air Quality Data released by the Ministry of Environment and Forests and Central Pollution Control Board of India under the National Data Sharing and Accessibility Policy (NDSAP).
1.	Stn_code (Dimension): Stores Particular Station Code for states or cities.
2.	Sampling_Date (Dimension): Stores particular month and air quality report code.
3.	State (Dimension): Stores Name of States.
4.	Location (Dimension): Stores Name of Cities.
5.	Agency (Dimension): Local Authority name which collected report.
6.	So2 (Measure): Level of Sulphur dioxide.
7.	No2 (Measure): Level of Nitrogen dioxide.
8.	Rspm (Measure): Level of Respirable Suspended Particulate Matter.
9.	Spm (Measure): Level of Suspended Particulate Matter.
10.	location_monitoring_station (Dimension): Place from Air quality measured.
11.	pm2_5 (Dimension): Level between 2 and 5.
12.	Date (Dimension): Stores date monthly from 1987 to 2000.
13.	Type (Dimension): Stores zone in which air quality measures like industrial, residential.
Basic Knowledge About Air Quality Measurements:
1.	(So2)-Sulfur dioxide,(No2)-Nitrogen dioxide Are One of the Most Dangerous Outdoor Air Pollutants. Outdoor NO2 exposure may increase the risk of respiratory tract infections through the pollutant's interaction with the immune system. Sulfur dioxide (SO2) contributes to respiratory symptoms in both healthy patients and those with underlying pulmonary disease.
2.	Respirable Suspended particulate(RSPM) matters are produced from combustion processes, vehicles, and industrial sources.
3.	Respirable Suspended particulate(RSPM) matters are produced from combustion processes, vehicles, and industrial sources.
Steps to Build the Dashboard:
1.	Connect to Data
2.	Design Dashboard Layout
3.	Create Worksheets
4.	Apply Filters
5.	Implement Interactivity
6.	Timeline Integration
7.	Map Integration
8.	Test and Refine
9.	Document Insights
10.	Publish and Share

Following these steps, you can create a comprehensive Tableau Dashboard that enables users to explore India's air pollution levels and environmental policy changes.

