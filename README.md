# Excel challenge-University-of-Toronto 
# Background for Analysis 
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success. To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. need to organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

# Excel file and Report file are attached for More details

# Work includes:
1.  Used the Excel workbook, modified and analyzed the sample-project data and tried to uncover market trends.
Used conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
2. Created a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
3. Used conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
4. Created a new column called Average Donation that uses a formula to find how much each project backer paid on average.
5. Created two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
6. Created a new sheet with a pivot table that analyzes initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
7. Created a stacked-column pivot chart that can be filtered by country based on the table which is created.
8. Created a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
9. Created a stacked-column pivot chart that can be filtered by country and parent category based on the table which is created.
10. The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site. that can be used to convert these timestamps to a normal date.
11. Created a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.
12. Created a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.
13. Created a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.
14. Now, created a pivot-chart line graph that visualizes this new table.
15. Created a report in Microsoft Word, and for answering the required questions:(PDF file is included)
16. For Crowdfunding Goal Analysis, Created a new sheet with 8 columns with required column and row headers.
17. Used the COUNTIFS() formula, for counting how many successful, failed, and canceled projects were created with goals within the ranges listed as per table sheet created. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.
18. Added each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, found out the 19. percentage of projects that were successful, failed, or canceled per goal range.
20. Created a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.
21. For Statistical Analysis, Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.
22. For gaining an in-depth understanding of campaign backers, evaluated the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.
23. Created a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.
24. Used Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:
 The mean number of backers, The median number of backers, The minimum number of backers, The maximum number of backers, The variance of the number of backers, The standard deviation of the number of backers
25. Used data to determine whether the mean or the median better summarizes the data.
26. Used data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?

# Presented report includes answers of the following questions:
1.	Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
2.	What are some limitations of this dataset?
3.	What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

# Before creating a report using the data that was provided, let's examine the information and make some deductions:
# Conclusions about Crowdfunding Campaigns:
1.	Campaigns That Are Successful: Most of the dataset's crowdsourcing initiatives are profitable. In a variety of areas, including Theater, Music, and Film & Video, successful campaigns outweigh canceled, unsuccessful, or in-progress ones. This implies that raising money for different initiatives through crowdfunding can be successful.

2.	Campaign Success Rate by Category: Some categories have higher campaign success rates than others. For instance, compared to journalism, which has very few effective campaigns, theater has many. This suggests that depending on the project's categorization, crowdfunding campaigns may or may not be successful. 

3.	Temporal Trends: The data reveals variations in the monthly total number of campaigns. Crowdfunding campaigns, for example, peak in the summer (June, July) and decline towards the end of the year (November, December). This implies that a crowdfunding campaign's success could be impacted by when it is launched.

# Dataset Restrictions: (Limitations of the dataset)
1.	Absence of Context: The dataset does not provide campaign details, financing targets, or campaign duration, although it does include counts of outcomes for various categories and months. Without this knowledge, it is difficult to comprehend the variables affecting the success or failure of a campaign. 

2.	Missing Data: The analysis as a whole may be impacted by the absence of information for a few categories or months. Results for several parent categories, such "audio" and "world music," are absent from the dataset, for example. 

3.	Aggregate Data: You can't undertake in-depth research or pinpoint specific trends within subcategories since the data is aggregated at a high level (e.g., counts of outcomes by category or month).

# Additional Tables and Graphs for Analysis:
1.	Success Rate by Category: Make a table or bar graph that displays the proportion of campaigns that are successful for each category. This would reveal which categories have the highest rates of success. 

2.	Trend Analysis Over Time: For each outcome category, create line graphs that display the number of campaigns over time (e.g., by month or year). This would make temporal trends easier to see and patterns in campaign activity easier to spot. 

3.	Geographical Analysis: Examine the distribution of results by nation or region and, if possible, incorporate data on the geographic locations of campaigns. This may shed light on geographical variations in the success of crowdsourcing.

4.	Analyze the relationship between the length of the campaign and its result (success, failure, etc.). Make a box plot or histogram that displays the distribution of campaign durations for campaigns that were successful and unsuccessful. 

# By incorporating these additional tables and graphs into the analysis, We may obtain a deeper comprehension of the dynamics of crowdfunding and pinpoint the elements that influence a campaign's success or failure
