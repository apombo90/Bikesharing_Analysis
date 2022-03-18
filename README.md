# Bikesharing_Analysis

## Project Overview
Using Tableau, build a dashboard to convince investors that a bike-sharing program is a solid business proposal. The purpose of the presentation is to show a deep analysis that is visually appealing and provides insightful information to the investors. Using NYC Citibike data from august 2019, the project answers the questions that are most important for the analysis. 


## Resources
- Data source: `201908-citibike-tripdata.csv`, `citibike_clean.csv`
- Software: `Python`, `Pandas` and `Tableau`.
- Tableau Public Dashboard: [NYC Citi Bikers Dashboard](https://public.tableau.com/app/profile/andres.pombo/viz/NYCCitiBikersAnalysis/NYCCitiBikeAnalysis "link to dashboard")
 
## Results

![image](https://user-images.githubusercontent.com/91766276/153793911-1c6d850c-b70f-4176-a136-b3bb80ff737d.png)

There are a total of 2,344,224 riders, most of the riders are males (65.3%), 25.1% are females and 9.6% have an unknown gender.

![image](https://user-images.githubusercontent.com/91766276/153794684-c6b59946-f8e6-4390-9154-e36f02f2efe4.png)

The majority of the users checkout their bike after 5 minutes, and the graph shows that riders checkout their bikes within the hour. Only a few riders keep their bike for more than 60 minutes.

![image](https://user-images.githubusercontent.com/91766276/153795239-7e8c2994-bfda-42c6-a3b1-d291f039308b.png)

The checkout time by gender shows the same tendency for males and females, both checkout their bikes within the hour and the highest peak for both genders is at 5 minutes.

![image](https://user-images.githubusercontent.com/91766276/153796410-b617f99e-26cf-47e3-9a70-1622fb9e1e47.png)

When we analyze which hour of each day of the week is when there are a greater number of trips, we can visualize that the peak hours are 'rush hours' (7-8AM and 5-7PM) during weekdays. Weekends peak hours are different, 10AM to 6PM is when there are more trips.

![image](https://user-images.githubusercontent.com/91766276/153797070-b299c9b9-a555-4554-b186-7e672c342ab4.png)

There is no difference between genders when we analyze the peak hours. Both have the same tendency of using the citibikes during 'rush hours'.

![image](https://user-images.githubusercontent.com/91766276/153795592-42e8fb75-ac53-430e-b922-d14f1647f8c4.png)

When we analyze which day of the week is when there are a greater number of trips, looking at the heatmap we can conclude that weekdays are busiest than weekends for both males and females. Also, many of the users are subscribers for both genders.

![image](https://user-images.githubusercontent.com/91766276/153797246-f2c7f990-38c7-40da-bd9f-45855b943c8a.png)

The map illustrates the Top Starting Locations to identify what are the hot spots. The majority of the trips start down town New York.

![image](https://user-images.githubusercontent.com/91766276/153797734-c752f106-739c-4617-8689-460c93ffa3d7.png)

This graph illustrates the bikes that had more than 400 trips. The most used bike was used 479 times in the month of august. 

## Summary:

The NCY Citi Bikers Dashboard provides insightful information to understand how the model functions and to recognize key patterns and important information. The gender distribution is one of the key findings, knowing that most of the people who use this transportation are males could lead into a deeper analysis to understand why females are not using Citi bikes, e.g. We could analyze if security is one of the reasons why females don't like to use this transportation. Also, knowing the peak hours allows us to determine the bike demand so that there are always bikes available for customers. Understanding how riders use the bikes is also important for the analysis, that is why the checkout times graphs allowed us to determine that most riders use the bikes for short rides. Finally with all the appealing visualizations it is possible for the investors to conclude that the citibike model is a solid business proposal.

On the other hand, I would suggest adding two visualizations that contain profit margins or costs. For the investors it is also important to understand the financial aspect of the model. Customer profitability, bikes repair costs are some examples of visualization that I would include in the dashboard.




