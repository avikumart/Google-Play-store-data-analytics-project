# Google-Play-store-data-analytics-project
This repo contains google play store data analytics project notebook with 12 interesting insights. it is data analysis project using pandas, matplotlib and seaborn libraries of python

## Techniques and insights:

1. What is the distribution of Rating of apps?? 
- using seaborn's distplot method
2. What are the number of apps are there in each category?? 
- using pandas value_counts and reset_index method
3. What percentage of apps are free?? 
- using value_counts and plotting using matplotib's pie plot
4. Number of apps in Racing categories using dataframe slicing
5. Time between released and last updation of the apps? 
- using pandas to_datetime method
6. Number of app installations and their categories? 
- using unique() and slicing of dataframe with matplotlib barplot
7. How many apps per rating given to apps? 
- using groupby() method of pandas
8. Median rating and rating count of each app given per category 
- using groupby() and sort_values() method
9. Top 5 size of apps 
- using value_counts method
10. What are the number of apps in content rating? 
- using map() method of pandas with lambda function
11. What about Ad supported or not and in app purchase status?
12. What's distribution of price of apps and its relation with ad supported? 
- using seaborn's kdeplot
