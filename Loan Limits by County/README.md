# Loan-Limits-by-County-Fannie-Mae-2022
This project analyzes the 2022 Loan Limits by county. Skills used: Parsing JSON, grouping and summarizing data, slicing and filtering data frames, data visualization, and exporting data to excel. 

## Loan Limits by County 2022: 
Data is from [The Exchange by Fannie Mae](https://theexchange.fanniemae.com), a data resource provided from Fannie, one of the Government Sponsered Enterprises (GSE) of the mortgage industry. `Loan Limits` are set every year by the Federal Housing Finance Agency (FHFA) on the unit size level (one unit, two unit, three unit, four unit). Loan limits set a maximum dollar amount on loans that Fannie Mae and Freddie Mac (the GSEs) are willing to buy or guarantee. If a loan exceeds this limit, a borrower cannot use a conventional loan, and they will have to apply for a Jumbo loan (yes, that's the real name!). Loan limits are set annually based on the market to prevent overborrowing and foreclosures. 

## CBSA Number and FIPs Code:

### CBSA... 
stands for Core-Based Statistical Area and is defined as a U.S. geographic area that consists of one or more counties connected by an urban center of at least 10,000 people plus adjacent counties. It is a unique identifier to locate urban areas defined by the Office of Management and Budget (OMB). Here is a resource on [FIPS Metropolitan Area CBSA Codes](https://www2.census.gov/programs-surveys/cps/methodology/2015%20Geography%20Cover.pdf). If `CBSA Code = 99999`, the CBSA Name is `"Not in a metro/micro area"`.

### FIPS Code...
are numbers that uniquely define geographical areas. Here is more information of [FIPS codes](https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt). 