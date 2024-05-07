# Customer-Service-Dashboard-
 


DATASET 
1: Introduction to dataset
The dataset captures customer satisfaction scores (CSAT) for a one-month period at an e-commerce platform called Shopzilla .It includes various features such as category and sub-category of interaction, customer remarks, survey response date, category, item price, agent details (name, supervisor, manager), and CSAT score etc.
Dataset Information:

Rows: 85,907

Columns: 20
DATA DESCRIPTION:
(the columns we used)
Column Name	Description

Unique id:	Unique identifier for each record
Channel name	:Name of the customer service channel
Category	:Category of the interaction
Sub-category	:Sub-category of the interaction
Customer Remarks	:Feedback provided by the customer
Product category	:Category of the product
Agent name:	Name of the customer service agent
Tenure Bucket	:Bucket categorizing agent tenure
Agent Shift	Shift timing of the agent
CSAT Score	:Customer Satisfaction (CSAT) score


2: Objective of dashboard
a) Overall Customer Satisfaction Trends:
Create visualizations that show the overall trend of customer satisfaction scores over the one-month period. This could be a line chart or bar graph, allowing stakeholders to quickly assess whether satisfaction is improving, declining, or stable.
b) Segmentation by Category and Sub-Category:
Group interactions by category (e.g., electronics, clothing, home goods) and sub-category (e.g., smartphones, dresses, kitchen appliances).
Visualize average CSAT scores for each category and sub-category. Identify which areas have the highest and lowest satisfaction levels.
Consider using heatmaps or stacked bar charts to show satisfaction scores across different categories.
c)Agent Performance Analysis:
Investigate agent details (name, supervisor, manager) and their impact on customer satisfaction.
Create a scatter plot or bar chart showing CSAT scores for each agent. Identify top-performing agents and those who may need additional support.
Explore correlations between agent performance and other features (e.g., response time, resolution rate).

3:  Steps for designing:
-	Created a bar chart for agent shift and CSAT score. Where CSAT score was on y axis. Later the graph was sorted in descending order.
-	The next Graph created was the manager VS CSAT score. A reference line was created at two stages so that we can identify which manager outstands. One Reference Line was created at 10K Counts and other was created at 20K count.
-	Another bar chart where the y axis (columns)comprised of the channel name was created.
-	A pie chart comprising of tenure was created with tenure on color and CSAT score on the angle mark  
-	Tree map was created where color and size were based on the SUM of CSAT SCORE.
-	And the category wise it was labelled.
-	For Sunburst Chart Category was portrayed as color and the angle was based on the count of the category. 
-	Created 4 blocks where placeholder was there in order to create a sunburst chart.
-	In the Sunburst chart the subcategory was placed at 2 repetitions of placeholder.
-	 Three different Sheets with the text of agent count, Manager Count and Supervisor Count was created .
-	All these sheets were then bought into a single sheet i.e. the DASHBOARD. 
-	With a bit of Formatting the Dashboard is created 😊
4: Interpretation:
	BAR CHART:
Manger Vs CSAT Score: John Smith has the highest count of CSAT SCORE. Who is crossing 10k and 20k mark .
Whereas Olvia Tan has the lowest 
Agent Shift vs CSAT Score: Company contacting the customers during the Morning time results in highest CSAT Score.
Channel Name VS CSAT Score: Maximum score is achieved through the channel of incoming calls (Inbound).

	PIE CHART: 
  Maximum CSAT Score is observed for the people who have a tenure bucket of greater than 90 days[.

	TREE MAP: 
For a product not delivered accurately or correctly the returns help the company for a positive customer satisfaction leading to a great CSAT Score. And the areas that the company needs to work on is with the Payment method, because Payment related issues are resulting in lowest CSAT SCORE.
 
	SUNBURST CHART:
Returns hold the Maximum CSAT SCORE.(44095)


5: Suggestion:
 For the upcoming companies this point can be kept in mind that the customer contact should be done during morning times and the agent attending the call should have their tenure greater than 90 days.
The company should work on the payment issue as its giving the least Customer Satisfaction Score .


