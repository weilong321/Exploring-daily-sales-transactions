# Exploring-daily-sales-transcations
Here is a dataset of daily sales transactions of a particular product on the market. A tableau dashboard is used to answer some questions.

### 1. Describe the data set in broad strokes. Note down any data anomalies, outliers, or anything you think is unusual in the data set.

From the first dashboard, we have analysed some major categorical variables as well as the numerical data. 

Some insights into the categorical data suggests that all regions (except Unknown) purchasing the ‘Timesheet Addon’ product is mostly for their cloud platform whilst a smaller percentage is purchased for their physical servers. We can also see that the highest proportion of sales is through ‘Renewal’ for all regions’ cloud platforms. In regard to the quantity of sales be each region, we can clearly see that EMEA purchased the most, followed by the Americas and lastly APAC. By comparing the time series between the license start and end date, we can see that the time delay between the license ending and the license starting is around one months’ time. This makes sense as most companies would need some time for advisors to suggest whether to continue using/stopping the product usage. 

For the distribution of numerical data, we have chosen to use boxplots to demonstrate the ranges of each variable. In the ‘Amount’ and ‘List Price’ variable, there seem to be plenty of outliers outside the normal range of the boxplot quantiles. Despite this, these outliers should not be ignored as some purchasers may indeed buy a large amount for a small price or a small amount for a large price. In some cases, some buyers may even choose to buy a large amount for a large price as shown in the ‘List Price’ distribution. We can see that each buyer may only purchase, or refund one unit of the product as shown in the ‘Quantity’ plot. As for the User Limit boxplot, we can see that most of the values fall between 10 and 2000 whilst there is an extreme outlier of 987654321. This value may be indicated as a placeholder for the maximum number of users. As we explore the data further (question 4), we can see that this placeholder is used early on. One reason could be that the seller may not be established enough to put user limits on the products.

2.	Plot a trend of monthly bookings and units by region. What jumps out at you from this trend?
As time goes on, we can see that each region’s (except Unknown) quantity increases generally. If we were to investigate further, there are definitely seasonal trends worth looking at. Looking between the months of October and November, we can see that there is a slight decrease in quantity in each region (except for 2013 EMEA). One reason for this could potentially be due to year-end rebalancing and tax optimisation which in turn may decrease sales for the product as well as the increase of refunds. On the other hand, between the months of January and February, there always seem to an increase in quantity purchased. This is probably due to the reverse of what happens during October and November where more buyers will be willing to expend on this product.

3.	Average Sale Price (ASP) is defined as bookings divided by units.  Find the top 10 countries with the highest Renewal ASP, and conversely which country has the lowest Renewal ASP?
Top 10 countries with highest Renewal ASP: 
  - United States of America
	- Germany
	- United Kingdom
	- Australia
	- Canada
	- Switzerland
	- Netherlands
	- France
	- Belgium
	- Denmark
Country with lowest Renewal ASP:
	- Reunion
