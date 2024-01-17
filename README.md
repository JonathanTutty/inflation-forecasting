# Random Forest Model for One-month-ahead Inflation Forecasting

## Methodology

The following GitHub repository was used as a starting point: https://github.com/o-meneses-covarrubias/inflation_forecasting

Methodology comes from the following article by Medeiros, Vasconcelos, Veiga, and Zilberman: [Forecasting Inflation in a Data-Rich Environment: The Benefits of Machine Learning Methods](https://www.tandfonline.com/doi/epdf/10.1080/07350015.2019.1637745?needAccess=true)

## Data

The data is focused on the UK economy. It is compiled from the following sources:

- CPIH annual rate, all items: [ONS](https://www.ons.gov.uk/economy/inflationandpriceindices/timeseries/l55o/mm23)
- Unemployment rate: [ONS](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/timeseries/s2pu/lms)
- Employment rate: [ONS](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/timeseries/s2pw/lms)
- GDP percentage change: [ONS](https://www.ons.gov.uk/economy/grossdomesticproductgdp/timeseries/ihyq/qna)
- Money in circulation: [BoE](https://www.bankofengland.co.uk/boeapps/database/fromshowcolumns.asp?Travel=NIxAZxSUx&FromSeries=1&ToSeries=50&DAT=RNG&FD=1&FM=Jan&FY=1989&TD=31&TM=Dec&TY=2025&FNY=Y&CSVF=TT&html.x=66&html.y=26&SeriesCodes=LPMB8H4&UsingCodes=Y&Filter=N&title=LPMB8H4&VPD=Y)
- BoE's Bank rate: [BoE](https://www.bankofengland.co.uk/boeapps/database/Bank-Rate.asp)
