# Campaign Performance Analysis - Feb 2021

## Project Overview

This project analyzes the performance of multiple marketing campaigns to evaluate their cost efficiency, profitability, and overall impact on return on marketing investment (ROMI). Utilizing data from various campaign types, including influencer, social, search, and media channels, the goal is to uncover patterns that can help optimize marketing spending and increase returns.

Key metrics such as ROMI, cost per click (CPC), cost per lead (CPL), customer acquisition cost (CAC), and conversion rates are assessed to determine the most effective strategies.

## Core Research Questions

- **What is the overall ROMI for all campaigns?**
- **What are the ROMI values for each campaign?**
- **Which campaigns generated the most revenue and which had the highest costs?**
- **What was the performance of campaigns on specific dates (high spending, revenue, and conversion rates)?**
- **When are buyers more active? What is the average revenue on weekdays and weekends?**
- **Which campaign types work best: social, banner, influencer, or search?**
- **Which geographic locations are better for targeting: tier 1 or tier 2 cities?**

## Data Structure

<div align="center">

[Click here to download the dataset](https://github.com/srishupadhyay/Campaign-Performance-Analysis-Feb-2021/blob/9741be5355c4fd10dcd0b76a01c6acd247aaabf8/DATA/Digital%20Marketing.csv)

</div>

<div align="center">

| **Column**         | **Description**                                                               |
|---------------------|-------------------------------------------------------------------------------|
| **Date**           | The date on which the marketing budget was spent.                             |
| **Campaign Name**  | A brief description of the campaign.                                          |
| **Category**       | The type of marketing source or channel used for the campaign.                |
| **Campaign ID**    | A unique identifier assigned to each campaign.                                |
| **Impressions**    | The number of times the ad was displayed to users.                            |
| **Marketing Budget**   | The amount of money spent on the campaign on the given date.                  |
| **Clicks**         | The number of people who clicked on the ad banner and visited the website.    |
| **Leads**          | The number of people who signed up and provided their credentials.            |
| **Orders**         | The number of people who purchased a product through the campaign.            |
| **Revenue**        | The total amount of money earned from the campaign.                           |

</div>

---

## Key Insights

• Top Performer: The YouTube Blogger campaign delivered the highest ROMI (306.87%) and revenue ($15.3M).

• Underperformers: Facebook LAL campaigns had a negative ROMI (-87.65%), showcasing inefficiencies in spending.

• Cost Metrics: Influencer campaigns had the highest CPL ($501.98), while Media campaigns were the most cost-effective ($456.06).

• Conversion Issues: Social campaigns converted only 3K orders from 31K leads, indicating a need for better lead nurturing.

• Budget Allocation: Redirecting funds from underperforming campaigns like Facebook LAL to high performers like YouTube Blogger could enhance profitability.

## Executive Summary

This project analyzed the performance of multiple marketing campaigns across various channels, emphasizing cost efficiency and profitability. The average Return on Marketing Investment (ROMI) across all campaigns was 42.61%, ranging from a high of 559.40% to a low of -100.00%. The YouTube Blogger campaign emerged as the top revenue generator, earning $15.3M in revenue with a budget of $4.1M and achieving an impressive ROMI of 306.87%. On the other hand, the Banner Partner campaign exhibited inefficiencies, spending $5M to generate only $6.2M in revenue. Social campaigns struggled with low conversion rates, converting just 3K orders from 31K leads. In terms of cost metrics, Influencer campaigns had the highest Cost per Lead (CPL) at $501.98, while Media campaigns were the most cost-effective at $456.06. Lastly, buyer behavior analysis revealed higher revenue activity on weekdays compared to weekends, providing insights into optimal campaign timing.

## Dashboard Analysis

<div align="center">
  <a href="https://github.com/srishupadhyay/Campaign-Performance-Analysis-Feb-2021/blob/a1287f8fecb3678321919a63dfdcfd71abf402a2/SOLUTION%20FILE/Digital%20Marketing%20Dashboard.pbix">
    <strong>Click here to download the dashboard file</strong>
  </a>
</div>

<br>



<div align="center">
  <img src="https://github.com/srishupadhyay/Campaign-Performance-Analysis-Feb-2021/blob/9741be5355c4fd10dcd0b76a01c6acd247aaabf8/PICS/Campaign%20Performance%20Dashboard%201.png" alt="Campaign Performance Dashboard">
</div>

<br><br>

<div align="center">
  <img src="https://github.com/srishupadhyay/Campaign-Performance-Analysis-Feb-2021/blob/9741be5355c4fd10dcd0b76a01c6acd247aaabf8/PICS/Cost%20Efficiency%20and%20ROMI%20Dashboard%202.png" alt="Cost Efficiency and ROMI Dashboard">
</div>




1. What is the overall ROMI for all campaigns?

The overall ROMI metric serves as the primary measure of campaign success. In this analysis, the average ROMI is 42.61%, with a maximum of 559.40% and a minimum of -100.00%. These values help gauge the effectiveness of various campaigns, highlighting both high performers and areas for improvement.

2. What are the ROMI values for each campaign?

The YouTube Blogger campaign stands out with an average ROMI of 306.87%, demonstrating significant efficiency in turning marketing spending into revenue. On the contrary, the Facebook LAL campaign has a highly negative ROMI of -87.65%, indicating ineffective use of the budget. Other campaigns, such as Facebook Retargeting (174.43%) and Google Hot (70.87%), also performed well in terms of returns.

3. Which campaigns generated the most revenue and which had the highest costs?

The YouTube Blogger campaign was the highest revenue generator, bringing in $15.3M with a budget of $4.1M. In contrast, Banner Partner had a marketing budget of $5M but only generated $6.2M, highlighting inefficiencies. The Facebook LAL campaign, despite spending $2.6M, earned only $0.3M, further showing negative results.

4. What was the performance of campaigns on specific dates (high spending, revenue, and conversion rates)?

On 20/02/2021, the YouTube Blogger campaign generated significant revenue of $1,452,540 with a ROMI of 378.03%, despite a budget of only $303,860. Similarly, on 17/02/2021, the same campaign achieved a ROMI of 226.86% with a budget of $363,811.

5. When are buyers more active? What is the average revenue on weekdays and weekends?

The dataset suggests that campaigns are most effective during specific dates, with certain campaigns like YouTube Blogger consistently showing high ROMI values. Further breakdown of daily activity could provide insights into buyer behavior on weekdays versus weekends.

6. Which campaign types work best: social, banner, influencer, or search?

Influencer campaigns such as YouTube Blogger have performed exceptionally well, with the highest gross profit of $12.81M. Social campaigns, despite generating high numbers of clicks (1.49M), had lower conversion rates, with only 3K of 31K leads converting into orders.

7. Which geographic locations are better for targeting: tier 1 or tier 2 cities?

The dataset could provide further insights into campaign effectiveness in tier 1 versus tier 2 cities by comparing conversion rates and revenue metrics based on geographic segmentation.






## Recommendations

• Reallocate Budget: Shift funds from underperforming campaigns such as Facebook LAL to more effective campaigns like YouTube Blogger to maximize returns.

• Optimize Social Campaigns: Improve the conversion process for social campaigns by refining landing pages and lead nurturing strategies, potentially increasing the order conversion rate from 3K.

• Focus on Cost Efficiency: While influencer campaigns bring in high returns, optimizing their CPC and CPL can lead to even higher profitability. Exploring creative variations or better targeting can help lower costs.

• Seasonal and Geographic Targeting: Use insights from the dataset to focus on specific time periods and geographies, such as focusing more efforts on campaigns during high-conversion months or better-performing locations.

## Conclusion

This analysis provides a detailed understanding of the effectiveness of different marketing campaigns based on key metrics such as ROMI, CPC, and CPL. By focusing on the top-performing campaigns and reallocating resources from underperforming ones, stakeholders can make data-driven decisions to maximize marketing efficiency and profitability. Further improvements in the conversion process and cost optimization are key to enhancing overall marketing performance.

