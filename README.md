# CODSOFT_TASK4
# CodSoft Internship - Task 4: Customer Data Analysis

## About this task
This is Task 4 of my Data Analytics internship with CodSoft. I analyzed the 
Zomato dataset from a customer behavior angle - looking at spending patterns, 
segments, and what drives engagement.

## Dataset
Used the cleaned dataset from Task 1 - zomato_cleaned.csv 
(51,588 restaurants across Bangalore).

## What I did
- Grouped restaurants by location to see which areas have the highest customer 
  engagement (using votes as a proxy for engagement)
- Segmented restaurants into 4 spend tiers - Budget, Mid-range, Premium, and 
  Luxury - based on cost for two
- Looked at which restaurants have the most customer engagement overall
- Compared online ordering vs table booking behavior across the different 
  spend tiers
- Made two charts to visualize the location engagement and spend tier distribution

## Key findings
- Koramangala 5th Block has by far the highest customer engagement of any area
- There's a clear pattern by spend tier - as price goes up, both average rating 
  AND average engagement go up. Luxury tier restaurants get about 26x more 
  engagement than Budget tier ones
- Customer behavior flips depending on spend tier - Budget and Mid-range 
  customers order online more often, while Luxury customers almost always 
  book a table instead (73% vs under 1% for Budget)
- Most of the highest-engagement restaurants are breweries/pubs, which lines 
  up with what I found in Task 2 about that category having the best ratings

## Marketing takeaway
New restaurants entering the market should prioritize Koramangala/BTM for 
visibility, and should invest in table booking systems if they're targeting 
a premium audience, since that's clearly what higher-spend customers prefer.

## Tools
Python, Pandas, Matplotlib, Google Colab

## Files in this repo
- CodSoft_Task4_CustomerAnalysis.ipynb - all the code
- task4_chart1_location_engagement.png
- task4_chart2_spend_tier.png

#codsoft #dataanalytics
