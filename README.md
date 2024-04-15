# Inflation Forecasting

## Methodology

The following GitHub repository was used as a starting point: https://github.com/o-meneses-covarrubias/inflation_forecasting. Its methodology comes from the following article by Medeiros, Vasconcelos, Veiga, and Zilberman where RF was found to outperform other models for inflation forecasting: [Forecasting Inflation in a Data-Rich Environment: The Benefits of Machine Learning Methods](https://www.tandfonline.com/doi/epdf/10.1080/07350015.2019.1637745?needAccess=true)

A Random Forest (RF) model is used as a benchmark to compare inflation forecasting models.

## Data

The data is focused on the UK economy. It is compiled from the following sources:

- CPIH annual rate, all items (CPIH): [ONS](https://www.ons.gov.uk/economy/inflationandpriceindices/timeseries/l55o/mm23)
- Unemployment rate (Unemployment): [ONS](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/timeseries/s2pu/lms)
- Employment rate (Employment): [ONS](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/timeseries/s2pw/lms)
- GDP percentage change (GDP): [ONS](https://www.ons.gov.uk/economy/grossdomesticproductgdp/timeseries/ihyq/qna)
- Public Sector financial borrowing (JW2P, GVHE, ANSC): [ONS](https://www.ons.gov.uk/economy/governmentpublicsectorandtaxes/publicsectorfinance/datasets/publicsectorfinancesborrowingbysubsector)
- Money in circulation (Money): [BoE](https://www.bankofengland.co.uk/boeapps/database/fromshowcolumns.asp?Travel=NIxAZxSUx&FromSeries=1&ToSeries=50&DAT=RNG&FD=1&FM=Jan&FY=1989&TD=31&TM=Dec&TY=2025&FNY=Y&CSVF=TT&html.x=66&html.y=26&SeriesCodes=LPMB8H4&UsingCodes=Y&Filter=N&title=LPMB8H4&VPD=Y)
- BoE's Bank rate (Bank_Rate): [BoE](https://www.bankofengland.co.uk/boeapps/database/Bank-Rate.asp)
- Economic Optimism Index (EOI): [Ipsos](https://www.ipsos.com/en-uk/new-uk-opinion-polls/state-of-the-nation)
