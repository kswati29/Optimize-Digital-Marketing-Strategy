# Optimize-Digital-Marketing-Strategy with Linear Programming
Optimization with Linear Programming for Budget Allocation- Digital Display Ads Inventory

### Purpose and Objective
Generically, the ad related KPIs are missed by a margin due to a weak budget allocation strategy in digital marketing. We intend to model this issue and utilize Linear Programming approach to produce an optimized solution for budget allocation of digital ads that satisfies thresholds for several campaign key performance indicators based on criterias and constraints towards acheiving the target.
Therefore, through this project we analyze and illustrate how to optimally allocate digital marketing budgets to specific ad publishers for brand awareness campaigns.
The project is based on real-time business data(Oscar Mayer, a subsidiary of Kraft Heinz) and the aim is to gain higher conversions from the ad publishers. The data is procured from the organization and somewhat manipulated (due to privacy concerns) based on past three year performance with respect to impressions, clicks, conversions, cost and click-through rate (CTR). 

The Linear Programming model (in Excel) provides an optimized budget distribution to the publishers based on return on ad spend (ROAS) through data analysis and linear programming. By publishing sites, we mean the websites where the company's digital ad is displayed. For the purpose of this project,  the sites include Facebook, Pandora and Twitter.  We also present sensitivity analyses that could be leveraged by managers to set the parameters of their campaigns.

### Result
Through our approach (Influence chart), our model results (Excel file) show a 3.67% increase in expected clicks and thereby an 8.12% increase in conversions assuming no change in the content of the ad campaign. 

Observing the trends of the previous three years, we noticed that Facebook’s CPM had consistently increased given its high CTR but simultaneously, Pandora’s CPM increased every year even though its clicks were only a fraction compared to Facebook’s clicks. We believe that this is because Pandora’s audience segment is different from Facebook’s and there is a higher conversion occurring from Pandora’s users despite having the lowest CTR. Comparably, we observed that Twitter’s CPM was consistently reduced throughout the three years. However, in 2019, it generated nearly 3x more clicks than Pandora with only 1.5x the impressions. We also noticed in our model that the maximum budget allocated was to Twitter, achieving approximately 4% higher CTRs than the average of the last three years.

### Conclusion
Our model gave optimized results successfully and is a useful tool to develop advertising inventory mixes based on actual performance data.
It is good to diversify between publishing sites by distributing the allocated budget to reach a wider audience. That said, the rates for every publishing site (e.g. Facebook, Pandora, Twitter) are nonlinear and dynamic. The quality and content of an ad displayed, as well as the audience segment it is reaching, will dictate the CTR (click-through-rate). However, at one point, for every dollar invested, there will be a lesser and lesser return. Once this occurs, the more beneficial thing to do is to invest in different publishers given that every site's reach composition, audience type, search volume etc. differs extensively. Since every site has a different pool of users, investing in a mix of sites increases the ad exposure to a variety of audiences.
Given the variation of rates in the advertising market, this model is scalable and upgradable. That said, new rate values can be fed to the model and/or even expanded to add more website publishers. Further, an extension to the current model could be designed to select an optimal inventory mix by device that includes different device types.
