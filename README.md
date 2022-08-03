# Kickstarting with Excel

## Overview of Project

Our client Louise’s project came close to its Kickstarter fundraising goal. Our Clients Louise now wants an analysis of similar Kickstarter campaigns with launch dates and funding goals.I organized the available data to share insights on similar projects for the client by using Excel.

### Purpose

To purpose of this project is to help our Client Louise to figure out how different compaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

Analysis was done by using Excel, and two table and charts were created to answer Client’s question.

### Analysis of Outcomes Based on Launch Date

To be able to get the correct information for outcome based on launch date. I had to creat a new column and called it ‘date created’. Then I had to coverted the ‘launch date data’ under the ‘date created’ colum with following formula. =(((J2/60)/60)/24)+DATE(1970,1,1)

In the following step I created another colum and called it ‘years’ and using the =YEAR()formula I gathered the launch year data from ‘date created’ column. After that I created a pivot table  to display the launch mont, agains the amount of successful, failed and canceled theather projects. To visualize it, I used line chart. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104239978/182502107-f6be0f73-82b4-4234-97af-6c8138c8d52c.png)

### Analysis of Outcomes Based on Goals

I created a new table and checked different goal amounts to see if there any effect on percentage of failed, canceled or succeesful projects. I used line chart.

![outcomes based on goals](https://user-images.githubusercontent.com/104239978/182502058-78785c99-7297-4436-9040-18765317cbf2.png)

### Challenges and Difficulties Encountered

The only challenge that I had was with countif formula, because of my poor attention I used deficient information in the formula, which gave me wrong numbers, as soon as I noticed and corrected that everything came together quickly.

## Results

Based on the analysis of Outcomes Based on Launch Date we can easily say that from May to July is the best time to launch a campagin. The worst month to launch is December. It seems that campaigns with goals of $5,000 and under are much more successful than others. Also I should add even though May seems to be the best time to launch we still do not know how long is the launching period. 
