# RFM-analysis-PythoN
#STEPS TO STEPS TO TAKE BEFORE STARTING ANY ANALYSIS:
#The first step in data analysis is to clearly define your questions and goals,
Similar to creating a hypothesis before an experiment, you should be asking a targeted question before searching the data for an answer. What problems are you trying to solve? Which parts of your business do you want more information about? Are you trying to solve an existing problem or predict how your company will perform based on determined factors? Clearly defining your goals will help guide the rest of the analysis process. For example, questions about overall performance can be open-ended and it can be hard to pinpoint which metrics are needed for analysis. Instead, it is more advantageous to ask questions such as “How have certain metrics changed over time?” and “Do these metrics correlate with others, and if so, how strongly?” These types of questions have a specific focus which will help determine the type of analysis needed and what data is the most relevant to include.
#Now we need to COLLECT DATA as per our requirements
Before you can start analyzing, there needs to be data available for use. Data can include sales records, customer demographics, lead tracking, net promoter scores, and more. When using a business intelligence tool, it is important to make sure that all of the data is accessible and the proper connections are set between your data warehouse and your BI tool of choice. Ultimately the volume of data required will depend on the question you wish to answer. Though you may only need a subset of the data collected, not having enough data can skew the results of your analysis
#Cleaning the data or in terms DATA WRANGLING
Now that you have all of your data in one place, it is important to clean the data before beginning the analysis portion of this process. A large part of the cleansing process includes making sure that the data is in a usable format. This entails searching for outliers, dealing with null values, and looking for data that may have been incorrectly input. Often this can be a lengthy and arduous process. A recent survey among Data Science professionals indicated that Data Analysts spend approximately 27% of their time cleansing data. While it may not be glamorous or the most enjoyable portion of the data analysis process, data cleansing is crucial to optimize the accuracy of your analysis.
WHAT WE NEED TO MAKE SURE OF BEFORE STARTING ANY ANALYSIS:
Before starting any analysis we need to be sure of few things first of all we need to make sure that our data is corrected properly that we have got rid of all the redundant variables after getting rid of all the redundant variables and making sure that our data is in correct format we need to translate our data into readable format and you need to make sure of the inclusion and exclusion criteria .in basic terms we need to be sure of the term to include in analysis and terms which we need to exclude from analysis and this is a crucial step because we are defining the most important things in our data which are useful in defining the analysis and can provide us with useful insights. Based on the type of analysis which we are going to perform we need to make sure of the metrics. Well in this case since we are performing rfm analysis we need to be sure of how we need to calculate recency or frequency score and what is a good monetization threshold for our data.
WHAT COULD ENRICH OUR DATASET
If we have age of each customer provided in the dataset we could perform an analysis based on age group and find out which age group is our strongest customer base and plan an action accordingly , for example launching new product specifically targeted for certain age group or planning our advertisement to attract certain age group.
RFM Analysis
Before starting with RFM we should know something about Customer Segmentation,

Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. A company might segment customers according to a wide range of factors, including but not limited to:

Customer Demographics
Transaction history
Location
Why Segment Customers?

Segmentation allows marketers to better tailor their marketing efforts to various audience subsets. Those efforts can relate to both communications and product development. Specifically, segmentation helps a company,

Select the best communication channel for the segment, which might be email, social media posts, radio advertising, or another approach, depending on the segment.
Identify ways to improve products or new product or service opportunities.
Establish better customer relationships.
Test pricing options.
Upsell and cross-sell other products and services.
How to Segment Customers?

Customer segmentation requires a company to gather specific information about customers and analyze it to identify patterns that can be used to create segments.Some of that can be gathered from the customers purchasing information such as Date of Purchase, geography, products purchased, etc. Some of it might be gleaned from how the customer entered your system. An online marketer working from an opt-in email list might segment marketing messages according to the opt-in offer that attracted the customer, Other information, however, including consumer demographics such as age and marital status, will need to be acquired in other ways.

For my analysis I have to used techinque called RFM analysis, where:

R - Recency: Recency is how recently for the date of analysis did the customer make a purchase. Customers who have purchased recently are more likely to purchase again when compared to those who did not purchase recently.

F - Frequency: Frequency is how often did the customer made purchases. The higher the frequency, the higher is the chances of these responding to the offers.

M - Monetary: Monetary is the total revenue generated by the customer through thier purchases. Customers who have spent higher contribute more value to the business as compared to those who have spent less
