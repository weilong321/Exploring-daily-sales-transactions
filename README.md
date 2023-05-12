# Exploring-daily-sales-transcations
Here is a dataset of daily sales transactions of a particular product on the market. A tableau dashboard is used to answer some questions.

### 1. Describe the data set in broad strokes. Note down any data anomalies, outliers, or anything you think is unusual in the data set.

From the first dashboard, we have analysed some major categorical variables as well as the numerical data. 

Some insights into the categorical data suggests that all regions (except Unknown) purchasing the ‘Timesheet Addon’ product is mostly for their cloud platform whilst a smaller percentage is purchased for their physical servers. We can also see that the highest proportion of sales is through ‘Renewal’ for all regions’ cloud platforms. In regard to the quantity of sales be each region, we can clearly see that EMEA purchased the most, followed by the Americas and lastly APAC. By comparing the time series between the license start and end date, we can see that the time delay between the license ending and the license starting is around one months’ time. This makes sense as most companies would need some time for advisors to suggest whether to continue using/stopping the product usage. 

For the distribution of numerical data, we have chosen to use boxplots to demonstrate the ranges of each variable. In the ‘Amount’ and ‘List Price’ variable, there seem to be plenty of outliers outside the normal range of the boxplot quantiles. Despite this, these outliers should not be ignored as some purchasers may indeed buy a large amount for a small price or a small amount for a large price. In some cases, some buyers may even choose to buy a large amount for a large price as shown in the ‘List Price’ distribution. We can see that each buyer may only purchase, or refund one unit of the product as shown in the ‘Quantity’ plot. As for the User Limit boxplot, we can see that most of the values fall between 10 and 2000 whilst there is an extreme outlier of 987654321. This value may be indicated as a placeholder for the maximum number of users. As we explore the data further (question 4), we can see that this placeholder is used early on. One reason could be that the seller may not be established enough to put user limits on the products.

### 2.	Plot a trend of monthly bookings and units by region. What jumps out at you from this trend?
As time goes on, we can see that each region’s (except Unknown) quantity increases generally. If we were to investigate further, there are definitely seasonal trends worth looking at. Looking between the months of October and November, we can see that there is a slight decrease in quantity in each region (except for 2013 EMEA). One reason for this could potentially be due to year-end rebalancing and tax optimisation which in turn may decrease sales for the product as well as the increase of refunds. On the other hand, between the months of January and February, there always seem to an increase in quantity purchased. This is probably due to the reverse of what happens during October and November where more buyers will be willing to expend on this product.

### 3.	Average Sale Price (ASP) is defined as bookings divided by units.  Find the top 10 countries with the highest Renewal ASP, and conversely which country has the lowest Renewal ASP?
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

### 4.	Produce a plot that best illustrates the distribution of units by User Limit over time.  Is there anything you find interesting that you’d like to call out?
Through the usage of a bar plot and scatter plot, we can see that the User Limit decreases over time. We see that there is a shift towards smaller User Limits which may suggest that the seller is targeting smaller organisations or specific teams within larger organisations. As we can see that the quantity being sold is increasing over time, we can also conclude that the product has been purchased continuously. 

Another interesting observation is what months are present above and below the trend line in the scatter plot. In regard to the observation made in question 2, we could see that early months had an increase in quantity sales whereas later months had a decrease in quantity sales. This theory is strengthened by the presence of early months being above the trend line and later months being below the trend line. 

### 5.	What are some of the key drivers that are fuelling business growth? Are there particular segments we should dive deeper on? Are there any data that isn’t captured here that we should consider?
We can confirm that a main driver of business growth for this seller is the increase of sales through lowering User Limit. This is shown especially well from the plots of question 4 where lowering the User Limit allowed for more quantity of product sold. Another solid driver of growth would be the impact a region has on the amount of product sold. From question 2, we can see that EMEA was sold the most amount, followed by the Americas and finally APAC. 

There are also a number of key drivers that may generally increase business growth:
	- Market demand: It is possible that there is a growing market demand for the type of products or services offered by the business, which is driving growth. It would be useful to conduct market research to understand the current and future demand for the products or services and whether the business is well-positioned to capture this demand. 
	- Marketing and sales efforts: Effective marketing and sales efforts can play a significant role in driving business growth. It would be useful to analyse the sales and marketing data to understand which channels are most effective in generating sales and which customer segments are most responsive to the messaging. 
	- Product innovation: Continuous product innovation can help a business stay competitive and drive growth. It would be useful to understand the level of investment in research and development and the frequency of new product releases. 
	- Partnerships and collaborations: Collaborations with complementary businesses or industry partners can help a business expand its reach and access new markets. It would be useful to understand the level of investment in partnerships and collaborations and the impact they have had on business growth.
	
In terms of specific segments to dive deeper on, it would be useful to analyse the data by region, license type, license level and sale type to understand which segments are driving growth and which may require additional attention. 

In terms of data that is not captured in the provided data, it would be useful to collect data on customer satisfaction, customer retention rates, and customer feedback to understand the level of customer loyalty and whether there are opportunities to improve the customer experience. Additionally, collecting data on competitors, market trends, and emerging technologies can help a business stay ahead of the curve and capitalize on new opportunities for growth.

