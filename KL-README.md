# Project-1
*My work was merged into:
Project1_Group6_OldMain.ipynb

Group Project for UNC Charlotte 

This project stemmed from my team and my own interest in the banking and credit idustry and how credit risk is looked at and how decisions are made.

The questions we wanted to answer:
1. Who is most likely to get approved for a loan?
2. How does income effect ability to pay back a loan?
3. What age is most likely to default?
4. What age is most likely to not default?

Our data was sourced by looking for banking loan data in cvs form to import into jupyter notebook.
We found our source on Kaggle, the cvs found had all the information we needed to study in order to create the visual data analysis for our project.
The data from Kaggle was compiled from online survey and email survey, (per kaggle.com).

As a team, we worked together to find the answers.  My focus was to find which age group would have the most loan defaults.
I expected Gen Z to have the most debt, to be the most at risk, however that is not what the data showed.
In order to separate total debt per age, I created a dataframe with the sum of all debt per age group.
This dataframe (all_debt) was used to create a bar chart and line chart, which show that millenials default more than any other age group.
The bar chart and line chart show the extreme difference in total debt between the different age groups, these charts clearly show what was in the data.

Overall, ages 48 through 56 are least likely to default on a loan, this was discovered through our analysis. 
Our analysis of income show that the higher the salary income, the more likely to repay debt.
The oldest age group has the highest salary, they are less likely to default.

Resources
Examples of credit risk data Bankloans csv file obtained from Kaggle, "Credit Risk for extending Bank Loans"
Sample Code take from Course/Zoom Meetings
Code reused from my previous data visualization projects
Share code, collaberation  with team mates

CSV source: https://www.kaggle.com/datasets/atulmittal199174/credit-risk-analysis-for-extending-bank-loans

drop nulls
https://www.statology.org/pandas-dropna-specific-column/

https://stackoverflow.com/questions/45416684/python-pandas-replace-multiple-columns-zero-to-nan

https://www.geeksforgeeks.org/python-pandas-dataframe-dropna/

line chart
https://stackoverflow.com/questions/43941245/line-plot-with-data-points-in-pandas

save charts to jpeg
https://stackoverflow.com/questions/8827016/matplotlib-savefig-in-jpeg-format
https://www.lifewire.com/convert-jpg-to-png-5072559