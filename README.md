### Data Duration
This study focuses mainly on the period of January to July 2020, during which, COVID-19 spread to Europe and North America, and the World Health Organization declared the coronavirus a global pandemic.


### The Stock Data
We requested financial data of companies listed in [S&P 1500](https://www.money-zine.com/definitions/investing-dictionary/sp-1000-index/) from [FACTSET] (https://www.factset.com/products-data), a financial data supplier. The variables we used for analysis include daily closing price, market value, and MSCI ESG rating score (MSCI, 2020). This list combines S&P 500, S&P MidCap 400, and S&P Small 600 and ccounts for approximately [90% of U.S. market capitalization (https://www.spglobal.com/spdji/en/indices/equity/sp-composite-1500/#overview). 

### Treasury Data
We use the three-month U.S. Treasury bill as [the proxy for the return of risk-free assets](https://www.investopedia.com/terms/r/risk-freerate.asp). The data is downloaded from [FRED-Economic Data](https://fred.stlouisfed.org/series/DTB3). The original data is annualized using a [360-day year or bank interest](https://www.federalreserve.gov/releases/h15/).  

### The Pandemic Data

We use pandemic data from Our World in Data (OWD) ([[Webpage](https://ourworldindata.org/coronavirus-source-data)]; [[Github](https://github.com/owid/covid-19-data/tree/master/public/data)]) based at Oxford University. (Ritchie et. al. 2020)  The pandemic data is constituted of daily total-cases data and new-cases data (See [full codebook](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data-codebook.md) from the source data) in the United States and Globally (See [Source Information by Country](https://ourworldindata.org/coronavirus-testing#source-information-country-by-country)) from January to the end of June 2020. The first corona-virus case was found on January 20, so we take this date as the start point of the pandemic in the United States. 




### References

Ritchie, Hannah. 2020. “Coronavirus Pandemic (COVID-19).” Our World in Data. https://ourworldindata.org/coronavirus

MSCI, Inc. 2020. “Methodology Book for The MSCI ESG Rating Select And The MSCI: ESG Rating Select Decrement Indexes.” https://www.msci.com/eqb/methodology/meth_docs/MSCI_ESG_Rating_Select_Indexes_Methodology_Feb2020.pdf.
