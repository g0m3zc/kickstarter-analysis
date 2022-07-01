# Kickstarter Analysis

## Overview of Project
This project leveraged kickstarter data for insights.  The dataset contained information around kickstarters such as their pledges, goals, and outcomes.  The data also contained information regarding the type of projects and location.

### Purpose
The purpose of the project was to review various factors of kickstarters.  These were reviewed for any underlying trends against their individual outcomes.  By better understanding these historical examples, we might be able to set up new projects that are also successful.

## Analysis and Challenges
In this analysis we used pivot tables, filtering, and formulas.  The challenges in this example were related to the large number of rows of data.  This required us to leverage excel functionality to make sense of the trends.

### Analysis of Outcomes Based on Launch Date
![Outcomes_vs_Goals](https://github.com/g0m3zc/kickstarter-analysis/blob/33d2cff4367c29ccb06df6d21cef4a0073baf22e/Theater_Outcomes_vs_Launch.png)
The review of outcome based on launch date revealed that kickstarters that launched in the summer months also saw more sucess in meeting their goals.  The month of May had the highest success date, with the percentage declining monthly after that.

### Analysis of Outcomes Based on Goals
![Outcomes Over Time](https://user-images.githubusercontent.com/106936638/176804927-1ff2a3a4-2aca-4484-8fc5-dad4a8e90917.png)


In general, a greater proportion of crowdfunding projects were successful if they had a lower goal.  As the goal increased, the success rate decreased.  It was an inverse relationship.

### Challenges and Difficulties Encountered
One of the challenges encountered in the assignment was creating a formula multiple times.  One way to overcome this obstacle more efficiently is to create the formula with fixed references, and then copy/paste it into the next cell where the formula is needed.  I also used the replace feature when creating formulas to be more effiecent.


## Results

We can expect that launching a kickstarter in May or one of the other summer months might give us an advantage when planning a new campaign.

We can expect to have a higher likelyhood of success if we launch a kickstarter with a lower goal.  In general, the cancelation rate didn't change based on the goal amount.  

One of the limitations of the dataset is that it contains the goal amounts for different countries in various currencies.  Because of this, we would need to do a converstion to be able to analyze data from different locations together.

Another limitation is that there wasn't a definitions list included with the dataset.  There was a column for "spotlight".  As it wasn't defined, we couldn't include it as a variable in our analysis.

There are some additional analysis that could be prepared on this dataset.  We could calculate the length of the kickstarter and use a pivot table to look for trends when comparing the length of a kickstarter with its outcome.  We could group the lengths so to see the overall trends.

We could also compare outcomes of a kickstarter compared to the number of backers.  This would suggest whether have a lot of pledges is a positive for a kickstarter.
