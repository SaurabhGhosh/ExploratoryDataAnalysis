<span style="color:#000000"> __Background\, Challenge and Business Objective__ </span>

<span style="color:#000000"> __Background__ </span>

<span style="color:#000000">A certain consumer finance company\, which specialises in lending various types of loans to urban customers\, wants to have more knowledge to make its portfolio and risk assessment better\. This company is the largest online loan marketplace\, facilitating personal loans\, business loans\, and financing of medical procedures\.</span>

<span style="color:#000000"> __Challenge__ </span>

<span style="color:#000000">Lending loans to ‘risky’ applicants is the largest source of financial loss \(called</span>  <span style="color:#000000"> __credit loss__ </span>  <span style="color:#000000">\)\. The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed\.  One major challenge area for the company in question is to reduce credit loss\.</span>

<span style="color:#000000"> __Business Objective__ </span>

<span style="color:#000000">In order to have more control on credit loss and in the process have betterment in portfolio and risk management\, the company wants to understand the</span>  <span style="color:#000000"> __driving factors \(or driver variables\)__ </span>  <span style="color:#000000">behind loan default\, i\.e\. the variables which are strong indicators of default\.</span>

<span style="color:#000000"> __Problem solving methodology__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda0.png" width=500px />

<span style="color:#000000"> __Analysis__ </span>

<span style="color:#000000">We majorly followed method of elimination in reducing the initial data set having</span>  <span style="color:#000000"> __111__ </span>  <span style="color:#000000">columns \(“possible” List of predictor or decision variables\) and</span>  <span style="color:#000000"> __39\,717__ </span>  <span style="color:#000000">rows \(or records\) to</span>  <span style="color:#000000"> __23__ </span>  <span style="color:#000000">and</span>  <span style="color:#000000"> __37\,283__ </span>  <span style="color:#000000">respectively\. The column elimination \(equivalent to disqualifying a given column from being a decision variable\) and row reduction</span>

<span style="color:#000000">\(equivalent to disqualifying certain rows from being eligible records to predictive modelling\) are based on concrete logic and being highlighted in the following slides\.</span>

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda1.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda2.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda3.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda4.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda5.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda6.png" width=500px />

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda7.png" width=500px />

<span style="color:#000000"> __Analysis\-Bivariate__ </span>

<span style="color:#000000"> __Data Frame Sub\-setting__ </span>

<span style="color:#000000"> __Generating the correlation matrix to check if Inter\-dependency exists__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda8.png" width=500px />

<span style="color:#000000"> __CONCLUSION__ </span>  <span style="color:#000000">:</span>  <span style="color:#000000"> _Inter\-dependency  is NOT present in appreciable scale for we decided to keep the correlation threshold to be \.8\. No value was greater than the threshold\._ </span>

<span style="color:#000000"> __Analysis\-Data Frame Sub\-setting__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda9.png" width=458px />

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda10.png" width=440px />

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda11.png" width=479px />

<span style="color:#000000"> __CONCLUSION:__ </span>  <span style="color:#000000"> _Graph for loan\_amt\, instalment and revol\_bal did not show up any outrageous outliers for which we decided not to further reduce the dataframe\, row\-wise\._ </span>

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda12.png" width=500px />

<span style="color:#000000">UNIVARIATE ANALYSIS on Categorical data :PART 1  :</span>

<span style="color:#000000"> _On Loan\_status column_ </span>

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda13.png" width=418px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data : PART 2 :</span>

<span style="color:#000000"> _On 'term' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda14.png" width=425px />

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda15.png" width=246px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda16.png" width=364px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data:  PART 3  :</span>  <span style="color:#000000"> _On 'grade' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda17.png" width=352px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda18.png" width=372px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data :PART 4 :</span>

<span style="color:#000000"> _On 'emp\_length' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda19.png" width=494px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda20.png" width=408px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data  :PART 5  :</span>  <span style="color:#000000"> _On 'home\_ownership' column_ </span>

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda21.png" width=384px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data  :PART 6 :</span>

<span style="color:#000000"> _On 'verification\_status' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda22.png" width=365px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data  :PART 7  :</span>  <span style="color:#000000"> _On 'purpose' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda23.png" width=500px />

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda24.png" width=220px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda25.png" width=79px />

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda26.png" width=96px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data  :PART 8  :</span>

<span style="color:#000000"> _On 'addr\_state' column_ </span>

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data:  PART 9  :</span>  <span style="color:#000000"> _On 'delinq\_2yrs’ column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda27.png" width=389px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data:  PART 10  :</span>  <span style="color:#000000"> _On 'pub\_rec' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda28.png" width=237px />

<span style="color:#000000"> __Analysis\-Univariate__ </span>

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data:  PART 11  :</span>  <span style="color:#000000"> _On 'inq\_last\_6mths' column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda29.png" width=433px />

<span style="color:#000000"> __Analysis\-Univariate on derived data__ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda30.png" width=500px />

<span style="color:#000000">\#UNIVARIATE ANALYSIS on Categorical data:  PART 12  :</span>  <span style="color:#000000"> _On derived column ‘issue\_year’ column_ </span>

<img src="https://github.com/SaurabhGhosh/ExploratoryDataAnalysis/blob/master/img/eda31.png" width=311px />

<span style="color:#000000"> __Conclusion__ </span>

<span style="color:#000000"> __We finally arrive at the set of decision variables__ </span>

<span style="color:#000000"> __Based on the above Univariate and Bivariate__ </span>

<span style="color:#000000"> __Analysis\,  as given below__ </span>

<span style="color:#000000"> __Target Variable__ </span>  <span style="color:#000000">: loan\_status</span>

<span style="color:#000000"> __Note__ </span>  <span style="color:#000000">: There is 14\.38% of the total loan which is charged off \(defaulted\)</span>

<span style="color:#000000">1\. Term \- Loans having Tenure as 6yrs have defaulted \(25%\) more than those having 3yrs \(defaulted 10%\) tenure\.</span>

<span style="color:#000000">2\. Grade \- 11% of the total Grade B \(LC assigned loan grade\) has defaulted\.</span>

<span style="color:#000000">3\. Address\_State\- People staying in Tier1 cities\(like CA\, NY etc\.\) have defaulted the loan more than who are staying in other cities\.</span>

<span style="color:#000000">4\. Emp\_length \- Employees having employment length less than 1yr and 10yrs tend to default more\.</span>

<span style="color:#000000">5\. Home\_ownership\- People staying on Rent or Mortgage have higher tendency to default the loan\.</span>

<span style="color:#000000">6\. Verification status\- Loans granted without any verification has been defaulted more\.</span>

<span style="color:#000000">7\. Purpose \- People granted loan on purpose of other Loan Consolidation have defaulted more\.</span>

<span style="color:#000000">8\. Delinq\_2yrs \- Pleple who don't have any record of delinquency in past 2 yrs also tend to default the loan\.</span>

<span style="color:#000000">9\. Pub\_rec: People not having any Public derogatory record also tend to default the loan\.</span>

<span style="color:#000000">10\. Inq\_last\_6mths\- If there is no enquiries has been done in last 6 months\, the loan tend to go to 	a default more\.</span>

