# Kickstarting with Excel

## Overview of Project

### Background

    After providing the client, Louise, with the an analysis of a series of crowdfunding data, her play "Fever" came close to its fundraising goal in a short amount of time.  Louise is now looking to further her analysis for future campaigns.

### Purpose
    The purpose of this project is to provide the client, Louise, with the supporting analysis in this written report to answer the following two questions:

    1.  Are there any trends in "Theater" kickstarter campaign outcomes (successful, failed, or canceled) based upon what month that the kickstarter campaign was launched?

    2.  Are there any meaninful trends in "Play" kickstarter campaign outcomes (successful, failed, or canceled) based upon the original campaign financial goal?


## Analysis and Challenges

### Analysis of "Theater" Outcomes Based on Launch Date
    To analyze the crowdfunding data for outcomes based on the campaigns launch date, a pivot table (wkst:Theater Outcomes by Launch Date) was created to summarize the outcomes of all "Theater" kickstarters based upon the month that the campaign was launched (See Kickstarter_Challenge.xlsx link below).  
    
    In addition, the pivot table results were graphically represented in a line graph showing the # of theater outcomes (successful, failed, or canceled) for each category based upon the launch date month, as seen below:

![image](https://user-images.githubusercontent.com/114360511/195754257-8c2c0634-d8a5-46cb-847a-67d20dbf4a7d.png)


### Analysis of "Play" Outcomes Based on Goals
    To analyze the crowdfunding data for outcomes based on the campaigns financial goals, a pivot table (wkst:Outcomes Based on Goals) was created to summarize the outcomes of all "Play" kickstarters based upon the the amount of money the campaign set as their goal (See Kickstarter_Challenge.xlsx link below).  
    
    In addition, the pivot table results were graphically represented in a line graph showing the percent of each outcome (successful, failed, or canceled) for each category of financial goal money set initially, as seen below:

![image](https://user-images.githubusercontent.com/114360511/195754396-8611628e-3ed1-4e21-ac6b-e01da0691526.png)


### Challenges and Difficulties Encountered
    No challenges or difficulties in this analysis were encountered for the provided crowdfunding data, but one possible challenge is the subcategorization of the different kickstarter campaigns.  Each campaign was placed in to one parent and one subcategory, but the categories were not all mutually exclusive.  For example, is there a clear line between what is a "drama" vs. a "play", vs. "theater", vs. "musical".  The clients future campaigns may not neatly fit into just one of the available subcategories


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    From the analysis on outcomes based on launch date, it can be concluded that the highest number of successful campaigns launch for a theater kickstart in the months of May, June, and July, as those months showed a clear separation in number of successful outcomes over all other months

    In addition, the number of both failed and canceled campaigns for theater kickstarts remained steady for all months of the year, showing no clear period where campaigns are not successful. 

- What can you conclude about the Outcomes based on Goals?

    From the analysis on outcomes based on financial goals, it can be concluded that play campaigns that set low goals (under $5,000) have a roughly 3/4 chance of successfully meeting those goals, while play campaigns that set very high goals (above $45,000) have a very small chance of successfully meeting those goals.  Between those bookends, the chances fluctuate dramatically, but with no definitive cause assertained in this analysis

- What are some limitations of this dataset?

    The dataset has its limitations.  As discussed prior, the subcategories do not all seem to be mutually exclusive, allowing for some error analysis based upon where a campaign was slotted.  In addition, one is limited to analyzing the success of outcomes on only those few fields provided, but there are many other criteria responsible for the outcome of a kickstarter campaign.  For example, where within each country was the campaign launched?  How was it marketed to potential investors?  How were pledges collected from patrons?

- What are some other possible tables and/or graphs that we could create?

    With the given dataset, one could have focused within a subcategory on relating outcome to average donation sizes, number of backers, or country of origin.  In addition rather than just basic outcome, we could have used the percent funded to dissect levels of success within the each outcome.  A graph that plotted percentage funded within the successful outcome vs. the length of the campaign might have helped establish timeframes for success.
