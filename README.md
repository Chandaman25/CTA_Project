# CTA_Project
Understanding access to CTA using Chicago Community Area socioeconomic information
We are trying to if certain areas within the City of Chicago are underserved by public transportation by trying to identify the factors that coontribute to having 
access to public transportation
Plan:
Create a dataframe with each column representing the amount of transportation stops in each community area:
  Each row represents a community area and each column represents a route (bus/train)
  The values in each space represent the number of stops for that specific route in that community area
Run a Cluster Analysis to identify which areas have the greatest access to public transportation
Map the clusters to see if there any trends in terms of geography of the access
Use those clusters as target variables for a regression model with socioeconomic factors for each community area as features to identify most important features
  We area using Data from Chicago Community Survery 20162-2020
  Also would like to engineer features such as distance to downtown
  Get size of community area
