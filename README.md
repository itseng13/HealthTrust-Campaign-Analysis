# HealthTrust-Campaign-Analysis
Founded in 2016, HealthTrust is a medical insurance company serving thousands of customers across the United States. In 2019, they introduced a new suite of marketing campaign categories, covering topics such as wellness tips, the affordability of their plans, and preventative care. Customers can choose from four different plans—Bronze, Silver, Gold, and Platinum—each offering varied premiums and claim coverage rates.

With a new data team now in place and a strategic focus on optimizing the marketing budget for the year, HealthTrust is committed to enhancing its understanding of the effectiveness of these campaign categories and their impact on signups and subsequent patient claims. As a data analyst at HealthTrust, this project is dedicated to developing interactive visualizations and an interactive dashboard that enable the marketing team to independently access insights and produce regular reports.

[Access the dynamic dashboard here.](https://public.tableau.com/views/HealthTrustCampaign/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![image](https://cdn.discordapp.com/attachments/697171631596109875/1260723875520581693/image.png?ex=66905c1b&is=668f0a9b&hm=a42b20fb134c166e2b29b5f148008908c6c7ccac946a86be258836224870b70d&)

# Insights
### Marketing Metrics
- The average metrics for all campaigns were a **click-through rate (CTR) of 9.46%**, **cost per click (CPC) of $0.04**, **cost per impression (CPI) of $0.0087**, and **impressions totaling 0.70 million**.
- *Tailored Health Plans* had the **highest impressions (1.36 million)** and a low CPI ($0.0037), while *Health for All* had the **highest CTR (36.1%)** but the lowest impressions (0.12 million).
- *Golden Years Security* was an outlier with the **highest CPC ($0.48)** and the lowest CTR (1.7%).

### Signup Metrics and Trends
- *#HealthyLiving* had the **highest clicks (127,000)**, a high signup rate (2.9%), and a low cost per signup ($1.25), while *Health for All* had the **highest signup rate (8.2%)** and the **lowest cost per signup ($0.57)**.
- During the pandemic, **signups increased significantly in 2020** for *#CoverageMatters, #HealthyLiving, HealthForAll, and Compare Health Coverage*, but have since returned to or dropped below pre-pandemic levels.
- Historically, *#HealthyLiving, HealthForAll, and #CoverageMatters* have been the top performers, accounting for approximately **70% of total signups**. The *Family Coverage Plan* had high impressions (1.11 million) but no clicks or signups, indicating a possible data integrity issue.

### Claims Metrics
- The campaigns *Health For All, #CoverageMatters, #HealthyLiving, and Compare Health Coverage* accounted for **87% of all claims**, with average claim amounts of $231, $228, $244, and $410, respectively.
- There are **132 claims totaling $0.02 million with no campaign category listed**, indicating a possible data quality issue.

# Recommendations 
1. **Optimize High-Performing Campaigns**:
   - *#HealthyLiving* and *Health for All* demonstrate high signup rates and low costs per signup. Allocate more budget and resources to these campaigns to maximize their effectiveness and reach.

2. **Improve Low-Performing Campaigns**:
   - *Golden Years Security* has the highest CPC ($0.48) and the lowest CTR (1.7%), making it cost-inefficient. Review and revise the campaign’s content, targeting, and strategy to identify areas for improvement or consider discontinuing it if no significant improvements can be made.

3. **Revise Campaigns with High Impressions but Low CTR**:
   - *Tailored Health Plans* had the highest impressions (1.36 million) but a relatively low CTR (6.7%). Revise the campaign’s content, call-to-action, and targeting to improve engagement and conversion rates.
