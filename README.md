# Project1-group5
Repository for class project

# See "Austin Area 5yr Development" presentation slides

Objective:
An exploration of Austin real estate development over the past 5 years, to see how the city has been changing in response to the increasing population.

# Data: https://data.austintexas.gov/Building-and-Development/Construction-Permits-Issued-since-2010/d792-2sc3

Data clean up and exploration:
1. Filter 'Since 2010' dataset to >= 2013 to represent work over past 5 years.
2. Total number of permits by status
3. Filter to only 'Final' (completed) permitted projects
4. Reduce DF to only relevant data fields
5. Standardize 'Commercial'/'Residential' field values

Analyses:
1. Scatter plot of number of permits (residential vs commercial) over time
2. Bar chart of which zip codes has the highest number of permits (residential and commercial)
3. heat map of permit counts
4. bar chart comparison of new construction vs remodel residential properties in a particular area (by permit count)
5. the rate of new condominiums being built in different areas
