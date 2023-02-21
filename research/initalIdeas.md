# Idea Bank

Use geopolitical data to understand potential political influences for prices in currencies
Use correlated currency pairs and use similar strategies for that to the understand and confirm potential movement in price
Use Carry Trading strategy/incorporate a component of that
Use fred to retrieve data from fed res
Use News API for geopolitics alongisde twitter api
Use maybe alpha vantange to gather economic data from here

- Data collection: Start by collecting data on geopolitical events, economic data releases, and market news that may impact the GBP/USD exchange rate. You can use news APIs, RSS feeds, and other sources to gather this information.
- Data processing: Clean and pre-process the data to make it usable for your algorithmic trading strategy. You may need to extract relevant information, such as key economic indicators or market sentiment, and store it in a suitable format.
- Data analysis: Analyze the data to identify patterns and relationships that may impact the GBP/USD exchange rate. You can use statistical analysis and machine learning techniques to identify patterns and make predictions about market behavior.
- Integration with your trading strategy: Use the insights from your data analysis to inform your trading strategy. For example, you could use news sentiment analysis to help determine market sentiment, or incorporate economic indicators into your mean reversion strategy to better predict market movements.
- Regular review and adjustment: Regularly review and adjust your algorithmic trading strategy to incorporate new data and respond to changing market conditions.

## For GBP

- Macro Influences:
    - BoE Monetary Policy
    - Employment Change
    - Industrial Production
    - Trade Balance
    - Purchasing Managers Index
    - RPI


## For USD

- Macro Influences:
    - Non-farm Payrolls
    - CPI
    - PPI
    - Trade Balance
    - ISM Non-Manufacturing
    - ISM Manufacturing
    - Fed Reserve Minutes 
    - Consumer Confidence (*look conference board by michingan uni/thomas reutuers*)
    - **Retail** <- US known to be home to largest retailers
    - Industrial Production

- For Both look at **Fiscal and Monetary Policy both fed res and BoE announce**
- **Major factor** - how to understand the semantics of the news releases

## Correlated currency pairs

- GBP/TRY
- NZDUSD
- USD/SGD *-ve*
- USD/JPY *-ve*
- USD/CAD *-ve*
- GBP/CHF

to check - look here `https://www.investopedia.com/trading/using-currency-correlations-advantage/#toc-calculating-correlations-yourself`

## Risk Management

- Use MonteCarlo to mitigate risk
- Bayesian methods to analyse risks and potential for future pricing

This is very different to traditional trading strategies as this is not live, our influence has no influence and therefore any market maker strategies are useless as there is not way of influencing the price.
This challenge has to be done through statistics and fundamental analyses 


## Questions:

- Is there a spread between the sell and buy prices?
