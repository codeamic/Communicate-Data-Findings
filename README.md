# (ProsperLoan Data Exploration)
## by Sango Pascal


## Dataset

> This is a Loan data set which consist of information regarding 113,937 loan records with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income,ProsperScore, EmploymentStatus and many others.


## Summary of Findings

> To start with my exploration was based on some of the factors affecting the prosperScore of a particular borrower. I decided to base my analysis on these 4 variables, IsBorrowerHomeowner,EmploymentStatus, IncomeVerifiable,OnTimeProsperPayments. Before i proceeded with the analysis process i had to clean outliers found in my variable of interest, i removed all columns with null values from the dataset based on ProsperScore variable, i later on changed the datatype of prosperScore from float to Int^4, and finally i had to make sure the highes value in this column is 10 as described in the data dictionary. 
> I continued my exploration by looking at the distribution of prosperScore(my variable of interest) and i realised that the prosper Score with the greatest count is 4 followed by6 and 8. To continue, i saw the distribution of employmeent status, here i realised that majority of borowers are employed. Again, the distribution of IncomVerifiable shows that, most of borrowers have a verifiable income source. Borrowers who have homes and pay their loan ontime will receive loan as well.

> Furthermore, i went forward to seeing the relationship between these variables. majority of borrowers who are home owners have high prosper score,same fro borrowers who with verifiable income. i also saw that most of the borrowers who are employed ow a home. Again majority of borrowers who pay their loan ontime have a high prosperScore. It was also  observed that those who are retired but own a home or have verifiable income source have a higher prosper rating.
## Key Insights for Presentation

> For the presentation, i will focus start with the distribution of the prosperScore, to see which prosperScore has the greatest count, i went ahead on seeing the distribution of employment status.
> Again, i am interested in seeing how income verifiable affects the prosperScore of the borrower. in the presentation, i also went ahead to look at the relation ships between EmploymentStatus, ProsperScore and IsBorrowerHomeowner Also the relationship between EmploymentStatus, ProsperScore and IncomeVerifiable, using a pointplot.