# Welcome to my Portfolio!

Economist graduated from the University of Costa Rica in February 2020 and Nova SBE in 2023 (Master of Science in Economics).

Working as Financial Data Analyst at Bentley Systems (NYSE: BSY). 
 
Interested in Data Analytics, Macroeconomic Policy and International Economics.

Nationality: Costa Rican

Languages: Spanish (Native), English (C2), Portuguese (C2), French (C1), Polish (A1/Learning)

Location: Lisbon, Portugal
 
## Project 1: Dollarization and the Exchange Rate Pass-Through: Is there a link? (01/07/2023 - Ongoing)

Master of Science Thesis

i) The objective of this project is to understand if there is a link between the level of dollarization (deposit dollarization) in a country and the exchange rate pass-through to inflation. 

ii) Using R, dplyr, tidyquant, ggplot2, tidyverse, magrittr, writexl and WDI among other packages, I was able to construct a database using Levy-Yeyati 2021 data for deposit dollarization and the World Development Index (WDI) data from the World Bank. Also, I was able to come up with several interesting stylized facts. 

Change in Dollarization in the World: 2000 - 2018 (R)

![Change_dollarization](https://github.com/lufebose/lufebose.github.io/assets/109878424/a16b0abd-f614-4089-8ab5-571afe61ae0e)

Dollarization by decade (R): 

![dollarization_by_decade_viridis](https://github.com/lufebose/lufebose.github.io/assets/109878424/9be94a0a-d9cc-4cf9-a2f5-6702b53a52cf)

Exchange Rate Pass-through running a simple OLS regression 

<img width="154" alt="image" src="https://github.com/lufebose/lufebose.github.io/assets/109878424/3d413647-dac1-401c-9ac0-8c14c93e811d">

and plotting in a histogram the coefficients of the slopes for each country (R):  

![er_pass_through](https://github.com/lufebose/lufebose.github.io/assets/109878424/7443e7cb-d843-45ff-9fcb-a0749ceacca9)

Countries with the highest absolute change in dollarization (R):

![plot_planel_high_change](https://github.com/lufebose/lufebose.github.io/assets/109878424/7a469d9f-9a05-4c2d-9ba5-51fb06fade7d)





## Project 2: The impact of interest rate changes and inflationary pressures on sovereign debt dynamics: Portuguese Case Study (01/02/2023-02/06/2023)

(Document Co-Authored with Miguel Oliveira and Tiago Campos / Code completely written by myself)

i) I utilized R and Gretl for the purpose of employing a debt equation specification and a VAR(2) model. This allowed me to both predict and compute the Impulse Response Functions (IRFs) concerning Portuguese debt in relation to key variables, such as: debt interest rate, GDP growth, inflation, and primary surplus.

ii) With both the models, it was demonstrated that the Portuguese debt is sustainable and has a decreasing trajectory in the coming years. Also, with the IRFs, the reaction of debt with respect to various variables was effectively modelled. 

![forecasts_VAR2](https://github.com/lufebose/lufebose.github.io/assets/109878424/c55dd2ba-32b0-402a-aa82-0f3d40dfbc24)

![irf4](https://github.com/lufebose/lufebose.github.io/assets/109878424/82c5d9ea-597c-45ba-8b50-072bc0107a27)

![irf2](https://github.com/lufebose/lufebose.github.io/assets/109878424/a1e27894-b9a8-4851-b314-f4d814e7804e)

The code can be accessed here in this .txt file:
[Portugal Public Debt.txt](https://github.com/lufebose/lufebose.github.io/files/12428664/Copy.Portugal.Public.Debt.R.txt)


Full Document:
[Public Debt GPEARI Report](https://github.com/lufebose/lufebose.github.io/files/12427787/Public.Debt.GPEARI.Report.-.Final.pdf)


## Project 3: Forecasting the Costa Rican Colon (CRC) Exchange Rate using the Prophet Package and time series filtering using mFilter (21/06/2022 - 28/06/2022)

i) Used the Prophet package in R to forecast the CRC/USD exchange rate (ER). Prophet proved to be a good package to forecast these kinds of series because of non-linearity and high seasonality

ii) With Prophet the seasonality of the ER was analyzed thoroughly. It was observed that the days with the highest seasonality are from Wednesday to Saturday whereas the months with the highest seasonality are June and November

![forecasting365](https://github.com/lufebose/lufebose.github.io/assets/109878424/990573c6-8ae5-4df5-bd74-75e2b4d34f36)

![trend-weekly-yearly](https://github.com/lufebose/lufebose.github.io/assets/109878424/8fa69be7-b44e-4434-8ed1-0f32ab04c898)

![Filtered data](https://github.com/lufebose/lufebose.github.io/assets/109878424/93812911-f126-4358-9a28-84522d964495)

The code can be accessed here in this .txt file:

[ER Forecast Code (.txt)](https://github.com/lufebose/lufebose.github.io/files/12428258/Copy.tc_forecast_prophet.R.txt) 

Also available per request: felipebose18[at]gmail.com


## Project 4: Analyzing Bitcoin (BTC) price while inflation expectations are high (06/07/2022 - 12/07/2022)

i. Used tidyquant, tidyverse, timetk, lubridate, dplyr ggplot2 to extract, analyze and visualize how BTC behaved during 2022 when it went below $20,000 

ii. Obtained other time series such as University of Michigan monthly Inflation Expectations from the FRED Website using Tidyquant in order to better understand BTC's downward spiral

iii. Analyzed the foreign exchange market by extracting information in an automated way using the Tidyquant Package in R

![btc_price](https://github.com/lufebose/lufebose.github.io/assets/109878424/c6db37b3-5885-44b4-bde3-e3d0d4b47229)

![infl_exp](https://github.com/lufebose/lufebose.github.io/assets/109878424/921acfbe-23ea-40c3-8697-f30c43a2bbe1)

![dollar2022](https://github.com/lufebose/lufebose.github.io/assets/109878424/ea7e7d90-0250-489f-a1fb-0d6563cf518f)

The code can be accessed here in this .txt file: 

[Bitcoin Code (.txt)](https://github.com/lufebose/lufebose.github.io/files/12428320/Copy.Bitcoin.Price.Analysis.and.forecast.R.txt) 

Also available per request: felipebose18[at]gmail.com






