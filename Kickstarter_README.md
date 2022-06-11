# An Analysis of Kickstarter Campaigns

## Overview of Project
Performing an analysis of crowdfunding campaigns on Kickstarter to uncover fundraising trends. 

### Purpose
This analysis is for the client, Louise, who launched a crowdfunding campaign on Kickstarter to raise $10,000 to fund her play *Fever* which will debut in the United States. Louise came close to her goal within a short timeframe and wanted to know how different campaigns fared in relation to their launch dates and fundraising goals.

## Analysis and Challenges
I analyzed the data from 4,113 Kickstarter campaigns to determine what factors lead to each achieving it's goal and specifically focused on campaigns classified under the theater category and play subcategory as they more closely related to the client's campaign. I created a pivot table in Excel to filter campaigns' success rate in relation to launch dates and used the COUNTIFS function to determine the success rate of plays in relation to their funding goals. Overall, theater fundraising campaigns were more successful if they were launched in May, and plays with smaller fundraising goals were more likely to succeed. 

### Analysis of Outcomes Based on Launch Date
While theater campaigns were more likely to meet their funding goal regardless of their launch date, campaigns were more successful if they were launched in May. Additionally, theater campaigns launched in December were more least likely to succeed in relation to other months, as 35 out of the the 75 launched did not meet their funding goals.
![Theater Outcomes vs. Launch Date](/assets/images/Theater_Outcomes_vs_Launch.png)
Additionally, in 2016 and 2017, theater campaigns were more successful if they were launched in January, February, March, April, and May, but there is a sharp drop off in June. 
![Theater Outcomes vs. Launch Date in 2016 & 2017](/assets/images/Theater_Outcomes_vs_Launch_2016_2017)

### Analysis of Outcomes Based on Goals
Crowdfunding Kickstarter campaigns for plays were more successful with smaller fundraising goals. Goals that were under $5,000 were about 75% successful, and goals between $5,000 and $25,000 were roughly 50% successful. 
![Outcomes Based on Goal](/assets/images/Outcomes_vs_Goals.png)
This is also true for plays that were launched in the United States. Successful play campaigns in the U.S. had a mean goal of $5,049 and failed campaigns had a mean goal of $10,554.
![Descriptive Statistics of Campaigns for Plays in the U.S.](/assets/images/Descriptive_Statistics_US_Plays.png)

### Challenges and Difficulties Encountered
I ran into challenges with the COUNTIFS function to filter plays, outcomes, goal ranges but reviewed [this](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842) documentation to properly format the function.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. Theater campaigns were more successful if they were launched in May. In the most recent data, campaigns that were launched in January through May were more likely to be successful than if they were launched later in the year.
    2. Theater campaigns launched in December failed at a higher rate, with approximately 47% of campaigns not reaching their funding goals.

- What can you conclude about the Outcomes based on Goals? 
Crowdfunding Kickstarter campaigns for plays were more successful with fundraising goals at $5,000 or under. 

- What are some limitations of this dataset?
    - Because this dataset only includes Kickstarter campaigns from 2010 through 2017, it may not reflect more recent funding trends.
    - This dataset includes 4,113 Kickstarter campaigns for a variety of categories all over the world. But, the sample size for plays in the U.S. is small at only 412. With the smaller sample size, the analysis may not be complete.

- What are some other possible tables and/or graphs that we could create?
In addition to looking at the launch date, we could also create a pivot chart comparing duration of the theater campaign using the [DATEIF](https://support.microsoft.com/en-us/office/calculate-the-difference-between-two-dates-8235e7c9-b430-44ca-9425-46100a162f38) function. 
