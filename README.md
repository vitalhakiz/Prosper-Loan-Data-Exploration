# Prosper Loan Data Exploration

## Dataset

The dataset comes from Prosper Marketplace Inc., a company that makes loans to people. The data set consisted of 113,937 loans obeservations and 81 features during the starting. I selected the 17 best important features such as monthly loan payment, stated monthly income, term, employment status, occupation and more that are sensitive to the loan status and dropped all the missing values in the data set. Then I remained with 103244 loans observations and 17 features.


## Summary of Findings

In univariate exploratory data analysis, bar charts and histograms were used to grab some insights from the analysis. In this view, with the help of bar chart, I observe that most of the loan statuses are (current, completed, chargedoff,Defaulted and pastDue(1-15days). Therefore, other loan statuses have very small percentages compared to those ones. The bar graph also showed the most states with more people requesting the loans. here are the states arranged in their ascending order of more people requesting for loan CA,NY,FL,TX,IL,GA,OH and more others. Then also, The bar graph showed how occupation affect the loan status. From the data we have, we saw that Professionals, Computer programmers, Executives, Teachers, Admistrative Assistants, Analyts.... are the ones with largest percentage of people requesting the loan. It also showed how the employment status affect loan. We saw that people who are employed, full-time and self-employed are the most ones requesting for loan than others. Furthermore, I used histogram to generate distribution of monthly income and it showed that the monthly incomes are distributed in a multimodal shape. 


In Bivariate analysis, we are able to analyse data using two variables or two featues either numerical or categorical or the combination of both features. In this exploration, I used five kinds of plots to obtain insights which are scatterplot, violinplot, heatmap, pie charts adn bar charts plots. I obtained many insights for the variables I was using in my plots. For instance, I found that there is a very strong positive correlation between BorrowerAPR and BorrowerRate, and also there is a good positive correlation between LoanOriginalAmount and MonthlyLoanPayment from the scatter plots. In addition, from the bar plots, we found that the most people whose their loan status is completed comes from CA region followed by FL and moreover, in the Completed loan status, data shows that the professional are the best followed by Computer Programmers and the least ones are the Teachers from the people's occupation.


In multivariate exploration, I used three features in the same graph to grab some insights between their relationships. I used two kinds of graphs Pointplots and Facetgrid plots to grab some insights. From there, I found that Executive, computer programmers and professionals have generally high monthly income compared to others. And therefore, the pointplot indicates that those Occupation with highly monthly income also pay highly monthly loan payment. Moreover, I found that many like have 3 years loan and only few have 1 year loan. In addition to this, only three kinds of employment status have 5 years loan. those are Employed, Full-time and self-employed categories.


## Key Insights for Presentation

From the analysis, I found that these features `employed, or having full-time contract, being professional, computer programmer, taking loan to be paid in 36months or 3years, coming from CA,FL,NY states ` increase the chances of getting the loan. In addition, I also found that as long as people take large amount of loan, also pay large amount of monthly loan payment. Moreover, as the BorrowerAPR, the BorrowerRate increases too and viceversa.

