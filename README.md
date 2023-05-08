# Kickstarter Analysis

## Overview
### Purpose
This project analyzes Kaggle spreadsheet data containing details about past crowd-funded projects on the major platform, Kickstarter (https://www.kickstarter.com/). Understanding these trends will allow for more informed business decisions and production scheduling for entrepeneurs or small businesses looking to source their projects through fan crowd-sourcing. 

### Background
<b>What is crowdfunding?</b> Crowdfunding refers to the method of collecting capital for a business or endeavor through a large number of individuals beyond friends, family, or customers. 

<b>Types of crowdfunding</b> There are many ways funds can be crowd-sourced. The following outline the main forms of crowdfunding:

- Reward Based: Involves individuals contributing (comparatively) small amounts of money to projects in return for a small type of reward. This is the method that Kickstarter utilizes.
- Donation Based: Involves a large number of contributors individually donating a small amount to source money for a project.
- Peer to Peer: This practice of lending utilizes online services to match lenders with borrowers

## Analysis
### ... by category
The following graph visualizes Kickstarter projects by parent category (e.g. technology) and project outcome (e.g. successful).

![parentcategory_outcomes](https://user-images.githubusercontent.com/31219195/163734824-cdc2ddaa-e5eb-4ddf-b533-aebcda3c11cf.png)

The following graph visualizes Kickstarter projects by sub-category (e.g. technology) and project outcome (e.g. successful).

![subcategory_outcomes](https://user-images.githubusercontent.com/31219195/163734840-4b8101c0-e2e3-4e89-889b-3c1319c92184.png)

According to the spreadsheet and the visualizations above: 

- There was a total of 604 Kickstarter campaigns in the available dataset, the "theater" category being the most successful.
- There were 525 successful theater Kickstarters in the US on record.
- The "play" subcategory was the most common Kickstarter project type.


### ... by launch date

Based on the sample, theater (specifically, plays) projects are one of the most common on the Kickstarter platform. Zooming in on this category, the following graph visualizes Kickstart projects by the month the project was launched. 

![outcomes_bydate](https://user-images.githubusercontent.com/31219195/163734927-902c4631-5d4e-41a5-850b-bb74e55cf997.png)

Per the spreadsheet data and the visualization above:
- May had the most number of successful Theater Kickstarter campaigns.
- January, June, July and October all had roughly the same number of failed campaigns launched.

### ... by revenue goal & outcomes

Further diving into play kickstarters, the following visualizes the projected vs actual revenue for play projects on Kickstarter.

![outcomes_vs_goals](https://user-images.githubusercontent.com/31219195/163734933-9aec589e-22b5-4f9d-8b5c-247dc9086631.png)

- The most 'successful' plays have had a goal of $20,000 or less.
- The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. Knowing this allows us to see that there were some failed Kickstarters with very high goals.
- There were some outlier instances of plays with high goals of more than $40,000 that still succeeded. However, the data shows us that this is not a statistically commonly occuring incidence.


## Results

- Theater productions, namely plays, have the highest success rate across kickstarters.
- Our data on Outcomes based on Launch Date shows us that theater kickstarters tend to consistently carry through to completion without cancellation.
- Furthermore, it shows us that the month of May is when the most successful theater kickstarters launch. 
- Based on the data on Outcomes based on Goals, we can conclude that a realistic goal of $20,000 or less will yield the highest chance of success for Theater kickstarters.

NOTE: The focus of the analysis stayed primarily on theater and play kickstarters and does not include in-depth views of other Categories or Subcategories. Additional category analyses such as descriptive statistics and outcome trend lines may be added for a more robust comparison. 

The dataset also originates from a single database of kickstarters and isn't an all-inclusive global table. The database appears to not have been updated in a number of years and an updated analysis may be needed for futher decision making.
