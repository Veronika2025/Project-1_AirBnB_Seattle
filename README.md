# Project-1_AirBnB_Seattle

Table of Contents
	1. Installation
	2. Project Motivation
	3. File Descriptions
	4. Results
	5. Licensing, Authors, and Acknowledgements


Installation
The could should run with Python Version 3. The following libraries were used: pandas, numby, seaborn, sklearn and the Matplotlib. 

Project Motivation
Based on the Seattle AirBnB open data available via kaggle.com I analysed following questions:
	1) In which neighbourhoods are the most listings?
	2) How high the average availability in the different neighbourhoods?
	3) How are the different variables correlated with the price variable? 
	

File Descriptions
Markdown cells were used to assist in walking through the thought process for individual steps.

Results
The neighbourhoods with the most listings are Capitol Hil, Downtown and Central Area. However, more than 20% of listings were categorized to other neighbourhoods.

Looking at the average availability per neighbourhood, we can see that there the average is above 200 days in each neighborhood. The lowest availability is in Cascade, while the highest is in Interbay. 

When it comes to the correlation between the variable price and other selected variables, a high correlation can be seen when it comes to the number of bathrooms, number of beds/bedrooms, cancellation policy and room type. However, if we try to explain the price variable via a linear regression based on this variables the R square is at 0.45, telling us that we can only explain 50% of the variance with this model, which is not a good fit. 


