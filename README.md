# Lab_7-Financial-Markets-Punish-Data-Breaches

https://public.tableau.com/profile/muhammad.adeel3420#!/vizhome/Lab_7FinancialMarketsPunishDataBreaches/EquifaxBollingerBands?publish=yes

Source : https://finance.yahoo.com/lookup/



#                                           Claim : Financial Markets do punish Security Breaches
                                           
# Perception
To pursuade our audience towards conveying our claim of this exercise that "Financial Markets do punish for Security Breaches", we used two companies in two different business segments. The companies analyzed below are Equifax and Anthem both of which suffered major data breaches in 2017 and 2015 respectively. We saparately analyze each Tableau visual by providing Warrant towards our main claim that
"Financial Markets do punish for Security Breaches."


<img width="1001" alt="equifax_1" src="https://user-images.githubusercontent.com/31932632/32403336-781840cc-c0f4-11e7-9990-4def8e8d64f2.png">
                                                           
#                                                           Fig 1.1
                                                 
# Warrant: 
Equifax candlesticks chart in Fig 1.1 is plotted in Tableau using Average closing prices and Average open, low and high stock prices for the period 2015 to 2017. The candlesticks chart confirms our claim that Financial Markets do punsish security breaches as shown by the drastic change and major decline in Equifax average stock prices in Sep 2017. After suffering a major decline in average stock prices during September 2017 post the data breach, the stockprice moved up on the improving trend and substantially started to stay uniform as of now Nov 4 2017. As soon as the CEO of Equifax publicly announced on Sep 7,2017 about one of the biggest data breaches in the country, investors and existing shareholders became hesitant and reluctant in their positive future predictibility of the company. This affected
investor sentiments and the resulting negative effect became apparent in the decreasing average price of the company stock. In my training data for analyzing the trend , i accessed Equifax stock price from Yahoo using Python 3 web datareader package.

<img width="993" alt="equifax_2" src="https://user-images.githubusercontent.com/31932632/32403368-f40e3e70-c0f4-11e7-81e7-d727214dcc53.png">
                                                          
#                                                           Fig 1.2
                                                          
# Warrant:
Equifax Bollinger Bands in Fig 1.2 are plotted in Tableau using Moving average, creating calculated fields of Upper and lower bounds using + and -2 standard deviation respectively. This visual is a great analysis of studying the pattern in the changing moving averages of stock prices. This visual further confirms our claim that Financial Markets do punish stock prices. After creating upper and lower
bounds for the moving average and the average closing prices, we analyzed the changing trend in the Bollinger Band chart in Fig 1.2, it shows that there was a wide dispersion in the lower and upper bounds, which occurred in Sep 2017 after the data breach was announced by Equifax.

<img width="1027" alt="anthem1" src="https://user-images.githubusercontent.com/31932632/32403369-fa4dc5bc-c0f4-11e7-8316-383fd76d499d.png">
                                                          
#                                                          Fig 1.3  

# Warrant:
Fig 1.3 shows the changing stock price of Anthem which is a health insurance company in the U.S. Anthem suffered two major data breaches 
in 2015 and 2016. The effect of Anthem Data Breach started reflecting in its stock price in Aug 2015 despite the fact that the data breach was announced in Feb 2015. The reason being that initially Anthem was not very much vocal about the data breach in terms of the records lost and the identities of the customers. It was later on revealed that around 79 million customer's personal information was stolen and Anthem had to face the lawsuits against the data breaches and the company announced in early 2017 that it was settling the litigations by compensating with over $115 Million.


<img width="1200" alt="anthem 2" src="https://user-images.githubusercontent.com/31932632/32403371-012e590a-c0f5-11e7-874f-a015d9e9741a.png">

#                                                           Fig 1.4
                                                           
# Warrant
Fig 1.4 is a Bollinger Bands plot for Anthem Insurance company's stock prices historical pattern using lower and upper bounds of average closing prices and analyzing the moving average trend. We analyze that due to successive data breaches, the recent one where an employee
had been involved in identity theft affected Anthem stock price drastically from 2015 to 2017. 

# Future Road Map
For further analysis of the companies and their respective data breaches and to affirm whether financial markets punish companies for the data breaches, we can use ARIMA package in Python to analyze the anomalies in the residual values of the stock prices and the percentage spreads in the open and close prices for a certain time period under consideration

