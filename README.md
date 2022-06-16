# kickstarter-analysis

Performing analysis on kickstarter data to uncover trends

## Overview of Project: 

#### Background

Louise needs to fundraising for her play *Fever*.  She wants to know how different campaigns fared in relation to their launch dates and their funding goals.  So she can best prepare for her fundraising activity.

#### Purpose

Using the Kickstarter dataset, we can visualize campaign outcomes based on their launch dates and their funding goals.  A report will be submitted based on the analysis and the visualizations.



## Analysis and Challenges: 

#### Analysis

For the outcomes based on launch dates,  a pivot table was created using a YEAR() function to have the month information and a chart was generated to illustrate the relationship between the outcomes and the launch dates, as shown in the following chart.  We can see from the chart that the most successful launch date is in May.

![Chart 1](resources\Theater_Outcomes_vs_Launch.png)



For the outcomes based on goals, we generated a table and used the CONTIFS command to obtain the accumulated outcomes of successful, failed and canceled.  And then, we used the math formula to calculate the percentage and drew a chart based on the results, as shown in the following chart.  From the chart, we can see the two highest successful goals are “less than 1000” and “1000 to 4999.”  This makes sense because the smaller the goal is, the easier to reach.  The high successful rates at the goal ranges of “35000 to 39999” and “40000 to 44999” look strange at the first glance.  But after a deeper analysis, we found that there were only single digit fundraising activities in those two goal ranges, compared to hundreds fundraising activities in the goal ranges of “less than 1000” and “1000 to 4999.”   This small sample size makes the successful rate statistically unreliable.



​                    ![Chart 2](resources\Outcomes_vs_Goals.png)



#### Challenges

We had two challenges.  One was a technical challenge to get the outcomes based on Months.  We overcome it by trying different filters in pivot chart options.  The other challenge was to explain the abnormal successful rate in the “outcomes vs. goals” chart.    We found a self-consistent explanation by looking deeper into the data.

## Results: 

We can draw two conclusion about Theater Outcomes by Launch Date.  The highest outcomes were launched in May and the lowest outcomes were launched in December.

We can also draw the conclusion that the two highest successful rate are “less than 1000” and “1000 to 4999” from the Outcomes based on Goals.

The limitations of this dataset is the small sample size for some of the goals. 

We may generate tables and/or graphs that show the contributors of each fundraising activities.



