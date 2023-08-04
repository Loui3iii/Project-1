# Project-1
BANK LOAN CREDIT RISK
Group 6 Project for UNC Charlotte--Data Visualization Boot Camp

ANALYSIS OF INCOMES AND LOANS OF INDIVIDUALS ALONG WITH THEIR AGES

This Notebook is a comprehensive data analysis of a bank loan dataset. The dataset includes various attributes such as age, education level, years of employment, address, income, debt-to-income ratio, credit debt, other debt, and a default indicator. The primary goal of the Notebook is to understand the characteristics of the individuals who default on their loans and identify any patterns or correlations that might exist within the data.

The Notebook begins by installing the necessary Python libraries for the analysis, including pandas for data manipulation, matplotlib for basic plotting, and seaborn for more advanced statistical visualizations. It then reads the data from a CSV file into a pandas DataFrame, a two-dimensional, size-mutable, and heterogeneous tabular data structure that allows for flexible data manipulation.

Next, the Notebook performs data cleaning to ensure the quality and reliability of the analysis. This includes removing duplicate rows and rows with missing values, changing the data types of some columns for appropriate analysis, and recoding the 'default' column to binary values to simplify the interpretation of results.

The Notebook then describes the data by providing descriptive statistics for the 'age,' 'income,' and 'default' columns. It calculates the mean and median 'age' and 'income' for each 'default' group, providing a clear picture of these variables' central tendency and dispersion. It also calculates the correlation between 'default' and 'income,' indicating the linear relationship between these two variables.

KEY QUESTIONS ANSWERED
Who is most likely to get approved for a loan?
How does income effect ability to repay a loan?
What age is most likely to default on a loan?

THE NOTEBOOK CULMINATES IN THE CREATION OF FOUR VISUALIZATION TYPES TO ANALYZE DATA:

Several line and bar graphs were created to structurally display the CSV data to more effectively analyze the dataset to answer the primary questions of this project. These charts were instrumental in clearly reviewing and documenting the information contained in the dataset.

Histogram of Average Income and Count of Defaults for Different Age Groups: This chart visually represents the average income and count of defaults across different age groups. The age groups are created by dividing the 'age' column into five equal intervals. The chart uses a bar plot to show the average income in each age group and a line plot to show the count of defaults. This allows for comparing income levels and default rates across different age groups, which can reveal whether age impacts the likelihood of defaulting.

Boxplot of Age Distribution for Default and Non-Default Cases: This chart uses a boxplot to compare the age distribution for default and non-default cases. A boxplot is a standardized way of displaying the distribution of data based on a five-number summary (minimum, first quartile (Q1), median, third quartile (Q3), and maximum). It can provide valuable insights about age variability in default and non-default cases and whether age is a significant factor in loan default. Bar Chart of Mean Default Rate and Count for Different Income Bins: This chart shows the mean default rate and count for different income bins. The income bins are created by dividing the 'income' column into five equal intervals. The chart uses a bar plot to show the mean default rate in each income bin and a line plot to show the count of individuals. This visualization can help identify if there's a pattern between income levels and default rates.

THE BOTTOMLINE
Credit risk is a lender’s potential for financial loss to a creditor or the risk that the creditor will default on a loan. Lenders consider several factors when assessing a borrower’s risk, including their income, debt, and repayment history. When a lender sees you as having a greater credit risk, they are less likely to approve you for a loan and more likely to charge you higher interest rates if you do get approved. 

Overall, our analysis revealed the following:
Ages 48-56 are the least likely to default on a loan.
The higher a person’s income, the more likely they are to repay a loan.
People under the Gen X umbrella have the lowest debt-to-income ratio.
The riskiest group to loan money to is the group with the most extended accumulated debt: Baby Boomers.
There is an inverse relationship between income and default rate. Generally, as income increases, the default rate decreases. This can be observed by comparing the default rates in different income b

This presentation thoroughly analyzes a bank loan dataset, exploring the characteristics of individuals who default on their loans. The combination of descriptive statistics and visualizations offers a comprehensive understanding of the data, revealing patterns and correlations that could be instrumental in predicting loan defaults.

GROUP 6 PRESENTATION
<img width="1233" alt="SLIDE 1" src="https://github.com/Loui3iii/Project-1/assets/135518113/a3b47262-8f9c-4a69-a809-6c70e83a0859">
<img width="1221" alt="SLIDE 2" src="https://github.com/Loui3iii/Project-1/assets/135518113/024033c4-750d-4a20-846c-5a15d907ae15">
<img width="1228" alt="SLIDE 3" src="https://github.com/Loui3iii/Project-1/assets/135518113/3d7a9149-0824-46e6-bdea-2760570b8027">
<img width="1221" alt="SLIDE 4" src="https://github.com/Loui3iii/Project-1/assets/135518113/db5df3d3-1f55-4b39-acaf-dbe04b81df88">
<img width="1214" alt="SLIDE 5" src="https://github.com/Loui3iii/Project-1/assets/135518113/21ecefe7-7afd-41be-b834-4b6d45b10cc5">
<img width="1233" alt="SLIDE 6" src="https://github.com/Loui3iii/Project-1/assets/135518113/5511da79-b5e1-46de-8c4d-772b5482fe3f">
<img width="1232" alt="SLIDE 7" src="https://github.com/Loui3iii/Project-1/assets/135518113/8b800508-cc75-4ea4-9b5b-4b08207ca98f">
<img width="1224" alt="SLIDE 8" src="https://github.com/Loui3iii/Project-1/assets/135518113/632246bd-542d-47f0-ae8d-698669ecf5fb">
<img width="1228" alt="SLIDE 9" src="https://github.com/Loui3iii/Project-1/assets/135518113/be9c8f77-183e-419d-813b-06071ad45b8a">
<img width="1229" alt="SLIDE 10" src="https://github.com/Loui3iii/Project-1/assets/135518113/87cc67e6-3405-4540-a08b-148a6a30fccf">
<img width="1228" alt="SLIDE 11" src="https://github.com/Loui3iii/Project-1/assets/135518113/3ecdcaab-7004-4090-98a3-aedf23ea8194">
[GROUP 6 FULL SLIDE PRESENTATION.pdf](https://github.com/Loui3iii/Project-1/files/12256896/GROUP.6.FULL.SLIDE.PRESENTATION.pdf)

Resources

Sample Code take from Course/Zoom Meetings
Code reused from previous data visualization projects
Share code, collaberation  with team mates

https://www.statology.org/pandas-dropna-specific-column/

https://stackoverflow.com/questions/45416684/python-pandas-replace-multiple-columns-zero-to-nan

https://www.geeksforgeeks.org/python-pandas-dataframe-dropna/

line chart
https://stackoverflow.com/questions/43941245/line-plot-with-data-points-in-pandas

save charts to jpeg
https://stackoverflow.com/questions/8827016/matplotlib-savefig-in-jpeg-format
https://www.lifewire.com/convert-jpg-to-png-5072559
