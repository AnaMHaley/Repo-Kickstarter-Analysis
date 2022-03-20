# Successful Kickstart Crowdfunding Campaign Data Analysis

##Purpose

My client, a talented playwright, is interested in starting a crowdfunding campaign to fund her play.  She has requested an analysis of crowdfunding data from other various campaigns to determine if there are certain factors that help make a campaign become successful.  By evaluating and interpreting the data, my client will have a better understanding of what components are necessary and helpful in achieving success, and what aspects and circumstances to try to avoid. 

##Analysis & Challenges

I received data from over 4100 crowdfunding campaigns worldwide.  Campaigns ranging from animation and video games to documentaries and rock music.  However, my focus was analyzing data from campaigns for plays. There were approximately 1066 play campaigns, whose data I had to sort through and analyze.  During my analysis, the only challenge I encountered were the Unix timestamps, which were provided in the Deadline and Launch columns.  Although Unix timestamps are unique, they are not helpful when collecting data.  In order to resolve this issue, I converted the Unix timestamps (using a formula) into a day-month-year format.  After the conversion, I formatted the columns into date format and continued my analysis.


![Unix Timestamps](https://user-images.githubusercontent.com/101373142/159147632-418d221c-1ad2-4276-bfb7-a66cb1838c58.png)
![Date Conversion](https://user-images.githubusercontent.com/101373142/159147633-96191055-86e3-4a1c-9912-5afa26ba0eb8.png)

##Results

In conclusion, when analyzing theater outcomes by their launch date, it was determined that campaigns had a greater success when begun during the spring, peaking during the month of May.  Campaigns were much less successful when begun at the end of the year, specifically during the months of November and December.  


![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101373142/159147681-11621858-3fa4-441a-84d6-f86996555079.png)


The data also revealed campaigns with goals of $5000 or less were most successful and had the lowest failure rate.  Analysis of this data was somewhat limited due to not having any campaigns being canceled.  However, the absence of this data may not have any bearings on the current findings.


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101373142/159147695-c6819bdc-0c47-4436-967e-30732322137c.png)


I recommend addition analysis to determine which countries had the most successful campaigns.  I also recommend analyzing the length of time (from launch to deadline) of each successful campaign.
