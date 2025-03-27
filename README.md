# Aircraft-Analysis-Project
# Overview
Our company choosing to expand its portfolio to include aircraft, marks a significant move into the aviation sector. To ensure this venture aligns with our strategic objectives, we will leverage data-driven insights to guide our decision-making. A comprehensive risk analysis will be conducted using a database of aviation accidents from 1993 to 2023. This data will help identify trends, potential risks, and safety considerations for different aircraft types, enabling us to select the most suitable options to support our company's goals.
# Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
# Data Understanding
The dataset we are using is from Kaggle. It contains information from the National Transport Safety Board(NTSB), which includes data from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, as well as in interanational waters. This dataset provides insights on various factors involved in aircraft accidents such as weather conditions, aircraft make and model and more.
# Data Preparation
This data was cleaned using Jupyter Notebook. The python pandas library and numpy library were also imported for analysis. These are the steps taken to clean the data:

1. Importing relevant python libraries
2. Loading and reading the CSV file.
3. Inspecting and understanding the data.
4. Data cleaning.
5. In data cleaning, we checked for missing values and dropped some columns and rows with missing values.
6.We also filled in all the numerical columns with missing values with 0 and the categorical columns with 'Unknown'.
# Conclusion
Based on the analysis we can conclude as follows:

1. Weather Condition: The weather conditions with the most accidents is VMC followed by IMC
2. Location: We can note that most accidents occur in Anchorage, Miami and Houston as compared to the other regions.
3. Aircraft make and model: We can conclude that most fatal injuries were caused by Cessna and model 172N.
4. Aircraft damage: We can see that substanial damage has the highest number of uninjured people.
Number of engines: The aircrafts with 4 or less engines had the most accidents
# Recommendations
1. Its notable that the weather conditionS more prone to accidents are VMC. Ensure the aircraft is equipped to handle all conditions for added safety.
2. Avoid high risk locations such as Anchorage, Miami and Houston and consider low risk routes.
3. Consider aircrafts with more than 4 engines if possible.
4. Avoid aircraft makes and models with high accident rates such as Cessna and Piper and 172N and 152.
# Tableau link for visualization of analysis
https://public.tableau.com/app/profile/julia.nyawira/viz/AircraftAnalysis_17430235063620/Dashboard1?publish=yes