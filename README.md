# Data-studio
  My project aims to examine whether a gradual increase in service charges by banks after the Global Financial Crisis (GFC) in 2008 has a statistically significant impact on the bank account ownership rate.

# Bacnground
  After the GFC, banks rely more heavily on service charges (ATM fees, income from the sales of checks, safe deposit box fees, wire transfer fees and card charges) due to the collapse in securitization fees and stricter regulations (Joseph G. Haubrich and Tristan Young, "Trends in the Noninterest Income of Banks"). The gradual increase in bank fees may have exacerbated financial inclusion by forcing low-income households to give up maintaining bank accounts. In 2019, 5.4 percent of US households were unbanked, meaning that no one in the household had a checking or savings account at a bank or credit union. Nearly one-third of them cite fees that are too high as a reason for being unbanked (Federal Deposit Insurance Corporation, "How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey"). 


By examining whether and to what extent the increase in bank fees impacts financial inclusion, I want to contribute to the debate on the effectiveness of the cap on fees currently under consideration.

# Intended audience
・U.S. House Committee on Financial Services

・U.S. Senate Committee on Banking, Housing, and Urban Affairs

・Director of Consumer Financial Protection Bureau

・Federal Reserve Board

# Data
# 1. Bank fee data
I use survey data by Bankrate (Matthew Goldberg, "Survey: Free checking accounts on the rise as total ATM fees fall"). Three types of bank cost data can be obtained from Bankrate: (1) average monthly service fee for interest accounts, (2) Average monthly service fee for non-interest accounts, (3) and (4) Average annual overdraft fee. The average monthly fee for interest-bearing accounts rose to $16.35 in 2021 from $12.55 in 2009. And that for non-interest checking account roses to $5.08 from $1.77 in 2009. In addition, the average annual overdraft fee increased to $33.58 in 2021 from $29.58 in 2009.

Based on them, I set these four data as independent variables for bank account fee changes.
(ⅰ) Average annual increase in the average annual cost of maintaining a interest bank account
(average annual service fee for interest accounts only)

(ⅱ) Average annual increase in the average annual cost of maintaining a non interest bank account
(average annual service fee for non interest accounts only)

(ⅲ) Average annual increase in the cost of using a interest bank account
(average annual service fee for interest accounts + average annual overdraft fee)

(ⅳ) Average annual increase in the cost of using a non interest bank account
(average annual service fee for non interest accounts + average annual overdraft fee)

# 2. Household income data
Wages are also expected to have a significant impact on bank account ownership rates. To eliminate the effect of wages, I also add changes in average household income to the independent variable, using average Before-tax family income from the Survey of Consumer Finances by Federal Reserve Board.

# 3. Bank Account Holding Ratio Data
The following two data sets were used as the bank account ownership percentage data sources.
(1) FDIC Survey, How America Banks: Household Use of Banking and Financial Services
(2)
# Source, existing literature, research and reporting
・Joseph G. Haubrich and Tristan Young, "Trends in the Noninterest Income of Banks"
https://www.clevelandfed.org/en/newsroom-and-events/publications/economic-commentary/2019-economic-commentaries/ec-201914-trends-in-the-noninterest-income-of-banks.aspx

・Federal Deposit Insurance Corporation, "How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey"
https://www.fdic.gov/analysis/household-survey/2019report.pdf

・Matthew Goldberg, "Survey: Free checking accounts on the rise as total ATM fees fall"
https://www.bankrate.com/banking/checking/checking-account-survey/

・Board of Governors of the Federal Reserve System,"Survey of Consumer Finances"
https://www.federalreserve.gov/econres/scf/dataviz/scf/table/#series:Before_Tax_Income;demographic:all;population:all;units:median

・
・・
・
・

