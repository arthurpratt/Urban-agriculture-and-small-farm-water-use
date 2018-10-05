# Purpose
This respository contains the excel and matlab files used in our analysis for the manuscript titled "Urban agriculture and small farm water use: Case studies and trends from Cache Valley, Utah", published in Elsevier's Agricultural Water Management (AGWAT) Journal. 

# Figures
I used these files to calculate the time series water balances for the different fields in our manuscript, as well as the various figures in Section 3.3 Summary Observations. 

# Time Series Water Balance Example
This excel file is a template for calculating a time series irrigation water balance. It requires the user to be familiar with spreadsheets, water balances, and to input weather data.  

# Matlab Uniformity Example 
This matlab script takes an excel input file of sprinkler catch can data and propagates it across a field to simulate overlapping of sprinkler laterals. The resulting array is used to calculate a Distribution Uniformity (DU), a Coefficient of Uniformity (CU), and generates a 3D plot of irrigation depth. The script is not trivial and requires the user to understand polynomial regressions, the concept of sprinkler uniformity, and how to conduct the catch can test.  
