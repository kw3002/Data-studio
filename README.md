# Data-studio
  My project aims to examine whether a gradual increase in service charges by banks after the Global Financial Crisis (GFC) in 2008 has a statistically significant impact on the bank account ownership rate.

# Bacnground
  After the GFC, banks rely more heavily on service charges (ATM fees, income from the sales of checks, safe deposit box fees, wire transfer fees and card charges) due to the collapse in securitization fees and stricter regulations (Joseph G. Haubrich and Tristan Young, "Trends in the Noninterest Income of Banks"). The gradual increase in bank fees may have exacerbated financial inclusion by forcing low-income households to give up maintaining bank accounts. In 2019, 5.4 percent of US households were unbanked, meaning that no one in the household had a checking or savings account at a bank or credit union. Nearly one-third of them cite fees that are too high as a reason for being unbanked (Federal Deposit Insurance Corporation, "How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey"). 

The Consumer Financial Protection Bureau reported in its 2022 report that overdraft fees can lead to account closure (Joe Valenti, "Overdraft fees can price people out of banking"). Democrats including Carolyn Maloney are considering introducing legislation that would crack down on overdraft fees, making it illegal for banks to charge more than one fee per month (Matt Egan, "Democrats relaunch crackdown on bank overdraft fees"). By examining whether and to what extent the increase in bank fees impacts financial inclusion, I want to contribute to the debate on the effectiveness of the cap on fees currently under consideration.

# Intended audience
・U.S. House Committee on Financial Services

・U.S. Senate Committee on Banking, Housing, and Urban Affairs

・Director of Consumer Financial Protection Bureau

・Federal Reserve Board

# Data
# 1. Bank fee data
I use survey data by Bankrate (Matthew Goldberg, "Survey: Free checking accounts on the rise as total ATM fees fall"). Three types of bank cost data can be obtained from Bankrate: (1) average monthly service fee for interest accounts, (2) average monthly service fee for non-interest accounts and (3) average annual overdraft fee. The average monthly fee for interest-bearing accounts rose to $15.05 in 2019 from $12.55 in 2009. And that for non-interest checking account roses to $5.61 from $1.77 in 2009. In addition, the average annual overdraft fee increased to $33.36 in 2019 from $29.58 in 2009.

Based on them, I create four models each with the following as independent variables.
(ⅰ) increase in the average annual cost of maintaining interest accounts from 2009 to 2019
(average annual service fee for interest accounts only)

(ⅱ) increase in the average annual cost of maintaining non interest accounts from 2009 to 2019
(average annual service fee for non interest accounts only)

(ⅲ) increase in the annual cost of using interest accounts from 2009 to 2019
(average annual service fee for interest accounts + average annual overdraft fee)

(ⅳ) increase in the cost of using non interest accounts from 2009 to 2019
(average annual service fee for non interest accounts + average annual overdraft fee)

# 2. Household income data
Wages are also expected to have a significant impact on bank account ownership rates. To omit the effect of wages, I also add changes in household income to regression equation as the independent variable, using average Before-tax family income from the Survey of Consumer Finances by Federal Reserve Board.

# 3. Bank Account Holding Ratio Data
I use the FDIC Survey on Household Use of Banking and Financial Services as our source for Bank Account Holding Ratio data.This survey began in 2009 and is conducted every two years through 2019. I create two models with the following dependent variables.

(ⅰ) changes in unbanked households from 2009 to 2019

(ⅱ) changes in unbanked households that previously had a bank account but closed it due to cost from 2009 to 2019

# Source, existing literature, research and reporting
・Joseph G. Haubrich and Tristan Young, "Trends in the Noninterest Income of Banks"
https://www.clevelandfed.org/en/newsroom-and-events/publications/economic-commentary/2019-economic-commentaries/ec-201914-trends-in-the-noninterest-income-of-banks.aspx

・Federal Deposit Insurance Corporation, "How America Banks: Household Use of Banking and Financial Services 2019 FDIC Survey"
https://www.fdic.gov/analysis/household-survey/2019report.pdf

・Joe Valenti, "Overdraft fees can price people out of banking"
https://www.consumerfinance.gov/about-us/blog/overdraft-fees-can-price-people-out-of-banking/#:~:text=CFPB%20research%20has%20found%20that,overdraft%20fees%20during%20the%20year.

・Matt Egan, "Democrats relaunch crackdown on bank overdraft fees"
https://www.cnn.com/2021/06/30/investing/bank-overdraft-fees-democrats/index.html

・Matthew Goldberg, "Survey: Free checking accounts on the rise as total ATM fees fall"
https://www.bankrate.com/banking/checking/checking-account-survey/

・Board of Governors of the Federal Reserve System,"Survey of Consumer Finances"
https://www.federalreserve.gov/econres/scf/dataviz/scf/table/#series:Before_Tax_Income;demographic:all;population:all;units:median

・FDIC Survey of Household Use of Banking and Financial Services
https://www.economicinclusion.gov/surveys/

https://www.fdic.gov/analysis/household-survey/2009/2009appendix.pdf  

https://www.fdic.gov/analysis/household-survey/2011/2011-unbankedreport-app-a-g.pdf

https://www.fdic.gov/analysis/household-survey/2013/2013appendix.pdf

https://www.fdic.gov/analysis/household-survey/2015/2015appendix.pdf

https://www.fdic.gov/analysis/household-survey/2017/2017appendix.pdf

https://www.fdic.gov/analysis/household-survey/2019appendix.pdf
