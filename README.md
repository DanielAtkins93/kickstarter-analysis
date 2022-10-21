# Analysis-of-Theater-Outcomes

## Overview
  I conducted an analysis of theater outcomes by launch date and an analysis of play (theater) outcomes based on funding goals. The purpose of this analysis was to gain meaningful insight into kickstarter trends so that I could provide Louise with comparisons to her own production. I expect this information to assist Louise in making improved decisions in the future. 
    
## Analysis and Challenges
  ### Analysis
   I ran two separate types of analysis for Louise. 
   
   The first analysis gathered theater outcomes and categorized them by month across multiple years: 
   ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/115741212/197276212-e315829c-9b7a-429d-a0c3-4cac21daaedf.png)

   My second analysis examined the correlation between play outcomes and funding goals:
   ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/115741212/197276195-e52a9cb0-6074-4aeb-80a2-73cb64d11d6b.png)

  ### Challenges
   One challenge I discovered was that my analysis titled "Theater Outcomes Based on Launch Date" displays absolute numbers of theater productions, rather than which months had the highest proportion of successful theater productions. While it is still true that May and June have the highest proportions of successful productions, they are only ~2% higher than the months of Feb, Apr, and Jul. This may lead someone to overestimate the benefits that May and June have over these months. 
   
   A challenge that was discovered in my "Outcomes Based on Goal" analysis was the small sample size for plays with a budget >= $25,000. Out of a population of 1,047, only 42 projects are represented across these 6 different categories. Given this small sample size, the data is susceptible to being skewed by outliers (for example, plays with a funding goal of $35,000 to $44,999 appear to be more likely to succeed than fail, in defiance of the trend). 
    
## Results
  ### Theater Outcomes vs Launch
   Due to this analysis, I was able to conclude that the highest absolute number of successful theater productions took place in May and June. It can also be concluded that these months have the highest proportion of successful projects, although the lead is smaller than the absolute figures might suggest.
    
  ### Play Outcomes vs Goals
   From this analysis, I can conclude that lower funding goals generally result in a greater percentage of successful plays (note the outlier from goal = $35,000 - $44,999).

## Summary      
  In summary, the data set had a few limitations, as discussed. Among them include 1). using absolute numbers rather than a proportion when examining the best-performing months for theater productions, and 2). small sample sizes for plays with a funding budget >= $25,000. 
  
  For future analysis, I would review which theater productions had problems meeting their funding goals and examine the correlation between this variance and a given project's outcome. I suspect this would be the single largest explanatory variable for failed project - budgets that did not receive sufficient funding. Further analysis could explain which projects fail to meet their budget and why.
