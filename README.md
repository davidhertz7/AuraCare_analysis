# AuraCare Marketing Insights – Project Overview


## The goal of this project is to evaluate the performance of Row Health’s marketing campaigns and surface recommendations for allocating marketing budgets across different campaign categories in the future.

Founded in 2016, Row Health is a medical insurance company serving thousands of customers across the United States. In 2019, the company introduced several marketing campaign categories focused on topics such as wellness, plan affordability, and preventative care. Customers can choose from four insurance plans — Bronze, Silver, Gold, and Platinum — each offering different premium levels and claim coverage rates.

With the addition of a new data team and the need to plan its marketing budget for the upcoming year, Row Health aims to gain a deeper understanding of how its marketing campaigns influence customer signups and subsequent insurance claims. By analyzing campaign performance alongside customer and claims data, the company hopes to identify which campaign categories deliver the greatest value and inform more effective budget allocation decisions.

The marketing strategy focuses on two primary objectives:

1. Increase customer signups by identifying the campaign categories that are most effective at attracting new customers.

2. Increase brand awareness across the United States by understanding how different marketing campaigns contribute to the company’s broader marketing goals.


## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.


## Insights Summary
**In order to evaluate campaign performance, we focused on the following key metrics:**
* **Signup Rate**: The percent of people who take action and clicks on a campaign and subsequently sign up for a Row Health plan.
* **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.
* **Click through Rate**: The percent of people who see a campaign and click on the associated link.

#### **Signup Rate**
- **Overall Trends:** Total Signups from 2019 - 2023 was 16,338 ranging in yearly sinups 865 to 5,154.  Overall average across all years 3267. While AuraCare peaked in signups 2020(5K) notable is that 2021 had both a 0.3% higher signup_rate and a $0.6 lower cost per signup

* Top performing campaign categories are Health For All that had the best performing signup rate of 8.16% more then 4x better then overall average and  the second highest sign up count of 3,545 and #CoverageMatters with an signup rate of 4.76% and a signup count of 3,536
  
* This high signup rate is due to the Campaign Types Product Promotion(5.3%) and Health Awareness(2.7%), which had by far the highest signup rate across all campaign types.
  
* Interestingly the campaign category with the highest signups #HealthyLiving had comparably a low signup rate 2.8% - Health For All had a 3x higher signup rate 





#### **Click through Rate**
* Health For All and Benefit Updates had across all campaign categories the highest click through rate 25.48% and 22.17% respectively - almost 3x more then average

* Golden Years Security had both the worst performance when it comes to CTR(Click Through Rate)(1.4%) and the highest CPC(Cost Per Click)($0.68) - Way under average at 9.39%

* Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.



#### **Cost per Signup**

* #CoverageMatters  had the lowest  cost per signup $0.7 out of all campaigns $3 cheaper then the average. Campaign type Product Information drove this low cost which #CoveragMatters only recorded a cost per signup of $0.3.

* Across all campaign categories, Golden Years Security had by far the highest cost per signup ($176) aswell as the lowest signup count 23. compared to an average of $3.7 

* Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup

## Recommendations

* **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
  
* **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.

* **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
  
* **#HealthyLiving**: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.
