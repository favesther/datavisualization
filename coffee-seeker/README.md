# coffee-seeker

In this Coffee Seeker data visualization, our goal is to help coffee dealers to find the coffee that meets their expectations. Some of the questions we want to help them answer are which countries have the coffee they want (i.e., coffee with different levels of flavor, aftertaste, aroma, body, and acidity), and within the filtered countries, what information they need to know about the coffee and the coffee owners. 
	
From coffee dealers’ perspective, they might hope to use sliders to filter the qualities of coffee beans to meet their arbitrary needs. They would use the geological map to select the coffee origin, maybe they already have a choice in their mind or just the closest country so that it would be more convenient. The color-coding on the map represents the overall balance of the coffee qualities which would be apparent while choosing the best. We used bar charts to single out some of the best coffees instead of just showing the best one because we want the dealers to have options while considering cost factors, etc.
We adopted filter bars since it would be more intuitive for people to adjust with the slider nodes. Also, a range slider would be more suitable when people do not have an exact value in mind so that a range could be the ideal choosing filter. Clicking on the map to see the coffee owners is also an intuitive step for people to view further choices. Hovering for tooltips is a conventional way to show people details while not so intruding to fluent viewing.

We considered plenty of alternatives. At first, we wanted to use scatter plots to show different coffee quality factors and producers, yet we believed that a map serves as a better way to demonstrate coffee balances and qualities because it is easier to locate where the ideal coffee owners are. We also wanted to use altitudes from the dataset and build a mountain visualization that has multiple dots indicating the altitude of coffee grown, yet at last, we deemed that as unnecessary since we already got 5 of the qualities and that should be enough for coffee dealers to make judgments.

# Collaborators
Fengwei Han: Clean data, Map, solve interaction issues
Julie Zhu: slider, CSS, connect the filter to map, map-bar chart scroll, write up
Xinyi Yang: Manually cleaned the excel data, drew the  bar chart, connect map data to the bar chart

# Time spent
Fengwei Han: approximately 15 hrs  
Julie Zhu: approximately 15 hrs  
Xinyi Yang: approximately 15 hrs  

# Challenges
Data cleaning is time-consuming. Data is in inconsistent formats. There are many null values that exist in different columns and rows. We were trying to get rid of the rows with null values without losing too much data. The most difficult problem of this assignment is connecting the pieces together. Everyone has different understandings of the information infrastructure.  When developing our own pieces at first, it is hard for us to be clear about what kind of data structure would be appropriate and effective when applying it to the whole visualization. Thus, it takes a long time for us to understand each other’s lines of code and to connect the pieces based on our interpretations. Moreover, debugging takes a lot of time. There are many issues related to javascript and d3, for example, data are all read and stored as strings,  the scope of the variables are different, etc. We spent quite a while identifying the minor errors in the code. 
