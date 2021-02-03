# Project1

This Project is a collaborative effort to build a portfolio recommendation that complements an existing portfolio for a potential client : Ralph 

## Team Effort

We divided the components of this project work into technical, research, presentation and miscellaneous to enable collorative contributions by team members. This division allowed for minimizing turnaround ties


## Project Proposal

Proposal for Project1 :

The project involves comparing the performance of the top 10 market cap stocks in the FINTECH domain and comparing the past 12 month performance with the SPY (index)
The tools we used :
1. alpaca api to get the data of the past 12 months    2. pandas   3. python  4.plotting libraries : maxplot, hvplot, sns, plotly , plotly express, dash gallery, Kaggle


## Finding Data

Source of Data for the following tickers : "SQ","ADYEY","MELI","GDOT","PYPL","FISV","PFE","GS","V","AXP","SPY"
https://app.alpaca.markets/brokerage/dashboard/overview
 
 The current portfolio stocks were: AAPL,NKE,GLW,NEE,IBM,UIS,TROX,BND,MSFT,JNJ,BRK.B,VCLT,SPLB,IGLB,BAR,SLV,DBO
 An .csv file exported from Ralph's current brokerage firm helped us get the data for these stocks.
 
 Some of the other sources our team used for research were:
 
 * [data.world](https://data.world/)

* [Kaggle](https://www.kaggle.com/)

* [Data.gov](https://www.data.gov)

* [Public APIs](https://github.com/abhishekbanthia/Public-APIs)

* [Awesome-APIs List](https://github.com/Kikobeats/awesome-api)

* [Medium APIs List](https://medium.com/@benjamin_libor/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)

## Data Cleanup & Analysis

There were two main notebooks used for coding the cleanup and analysis for this project :

#1. Data_Cleanup.ipynb : 
     a. Importing Libraries and dependencies -- os, numpy,pandas,alpaca_trade_api
     b. Generated the dataframe for top 10 fintech stocks using api
     c.The tickers used to create dataframe :  "SQ","ADYEY","MELI","GDOT","PYPL","FISV","PFE","GS","V","AXP","SPY" . These are the top 10 fintech stock found in Referenc: Motley        fool and other online investment portals
     d.The .csv file exported from potential Client's brokerage contained the details of the stocks : 
     AAPL,NKE,GLW,NEE,IBM,UIS,TROX,BND,MSFT,JNJ,BRK.B,VCLT,SPLB,IGLB,BAR,SLV,DBO
     e. The two datafiles were checked for nulls and other incongruent data and using code cleansed.
     
 #2. Data_Analysi.ipynb :
     a.Importing Libraries and dependencies -- os, numpy,pandas,alpaca_trade_api, MCForecastTools,panel,pypfopt
     b.Analysis involved creating data frames of percentage daily returns using closing prices of the top 10 fintech stocks based on the data from alpaca trade api
     c.Create line plot of cumulative returns for our portfolio
     d.Create distribution plot of cumulative returns for our portfolio using MCForecastTools library ( performing Monte Carlo Simulation).
     e.Creating a Monte Carlo Simulation of the SPY data
     f.Comparitive study of Simulated data and plotting graphs of Individual Stocks vs SPY
     g.Calculation and plotting graphs of co-variance of stocks
     h.Calculation and plotting graphs of beta of stocks
     i.Calculation and plotting of sharpe ratios of stocks
     j.Correlation graph - heat map of SPY and fintech stocks
     k.Identification of the top 4 fintech stocks that performed well compared to SPY using the sharpre ratios of above 1, high beta
    
     

#Text from original instructions below:

## Presentation
    Link to the presentation : 

As long as your slides meet the [presentation requirements](PresentationRequirements.md), you are free to structure the presentation however you wish, but students are often successful with the format laid out in the [presentation guidelines](PresentationGuidelines.md).

## Submission

In addition to submitting your project on Bootcamp Spot individually, please [fill out this form](https://forms.gle/CBk5tyy4sSsGN8k38) **once per group**.

- - -

© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
