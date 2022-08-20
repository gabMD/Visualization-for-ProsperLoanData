# (PROSPER LOAN DATA EXPLORATION)
## by (Gabriel Chidera Edeh)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Some wrangling efforts were made to put the dataset in a form suitable for visualization. The wrangling effort made were;
a. Getting rid of low information variables (i.e, columns with null values > 50%)
b. Converting LoanOriginationDate to datetime
c. Extracting the quarter of the year and the year from the LoanOriginationQuarter
d. Converting ListingCategory to alpha from numeric listing
e. droppig some columns that will not contirbute to the analysis ['ListingKey', 'ListingCreationDate', 'DateCreditPulled', 'FirstRecordedCreditLine', 'LoanKey', 'MemberKey']
f. Dropping rows without Prosper rating numeric
 Initially, there were 113937 loan records with 81 features in the dataset, of which only 84853 records remained after the wrangling process and was considered for this analysis because of their relevance in determining the amount of loan to be collected and prosper rating.


## Summary of Findings
Univariate, bivariate and multivariate visualization processed were subsequently carried out on the dataset and the following findings were noted:

> Retired, Partime and Not-employed had relatively low number of loan listing compared to employed and full time workers

> majority of the listing are coming from Carlifonia,New York,Texas, Florida with Washington, D.C topping the average loan amount recorded

> high income earners constitute majority in the loan listing with 100,000+ dollars topping the average loan original amount as expected

> The year 2013 recorded the highest loan listing with 2014 topping the chart for average loan amount requested for.

> Majority of the listing and average loan requested for was for debt consolidation.

> More than half of the borrower were home owners and this set of people also topped the average loan original amount

> Highest percentage of the loan listing was carried out in the 4th quarter, followed by the 1st quarter

> There were lot of loan listing on the low LoanOriginalAmount end and few on the high LoanOriginalAmount end.

> borrower rate and borrower APR showed strong positive correlation

>The employed, middle class earners and homeowners dominated the survey

>Prosper rating AA which is the best rating is closly associated with low borrower rate between 0.05 and 0.10 while 25000 above loan original amount is associated with AA, A,B


## Key Insights for Presentation

> High income earners constitute majority in the loan listing with 100,000+ dollars topping the average loan original amount as expected

> Majority of the listing and average loan requested for was for debt consolidation.

> Highest percentage of the loan listing was carried out in the 4th quarter, followed by the 1st quarter

> More than half of the borrower were home owners and this set of people also topped the average loan original amount

>Prosper rating AA which is the best rating is closly associated with low borrower rate between 0.05 and 0.10 while 25000 above loan original amount is associated with AA, A,B