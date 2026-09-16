# Financial-Market-Analytics-Risk-Analysis
Analyses Malaysian financial market data to identify MYR exchange-rate trends, currency movements, market volatility, and relationships between foreign exchange rates, the Overnight Policy Rate (OPR), and Malaysia Overnight Rate (MYOR).

Project Brief:

Data Source: Bank Negara Malaysia (BNM) – Financial Markets Data<br>
Period: 2015 – 28 Aug 2026 for FX and OPR, MYOR available from Sep 2021<br>
Skills: Pandas, NumPy, Time-Series Analysis, Matplotlib, Seaborn<br>
Tools: Python<br>

Objective:<br>
To analyse historical Malaysian financial-market data and identify exchange-rate trends, periods of elevated volatility, major market movements, and relationships between FX and domestic monetary-market indicators.

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/62555ec0-3fd3-436c-b8a9-b36c0a20bcb1" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/77aa590c-6955-452c-b071-4eab7b6477e1" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/125fe825-0de4-4ecc-b8c2-bb7c61c2e5b1" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/ec523ff6-6406-452a-9537-563e20d65538" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/6d15d2d5-45c2-44e8-9c50-451c84ecec31" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/360c2b9f-6ae8-45c5-94a7-e5da38963dc5" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/899455d5-e9a0-4223-b710-050efff43600" /><br>

<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/3724bebe-b607-478c-816d-00b4fe04a1c9" /><br>

## Summary:

The analysis uses official Bank Negara Malaysia financial-market data to examine MYR exchange-rate movements, market volatility, and domestic monetary-market conditions. The dataset contains **2,854 observations** across USD, GBP, EUR, JPY100 and SGD exchange rates.

USD/MYR averaged **4.2319** over the analysis period, with observed values ranging from **3.5100 to 4.7935**. The average daily return was **0.0057%**, while the largest daily increase was **+2.3632% on 24 June 2016** and the largest daily decline was **-2.8971% on 5 August 2024**.

A **30-day moving average** was used to identify broader exchange-rate trends, while **30-day rolling standard deviation** was applied to measure market volatility. Average 30-day volatility was **0.3502%**, with the highest level reaching **1.1104% on 26 October 2015**.

The analysis also incorporates Malaysia's **Overnight Policy Rate (OPR)** and **Malaysia Overnight Rate (MYOR)** to provide additional context on domestic monetary and money-market conditions.

## Key Insights:

**1. USD/MYR experienced substantial movements across the historical period:**
The exchange rate ranged from **3.5100 to 4.7935**, demonstrating meaningful changes in MYR valuation over time.

**2. Typical daily movements were relatively small, but extreme movements occurred:**
The average daily return was only **0.0057%**, while individual daily movements reached **+2.3632% and -2.8971%**, highlighting the importance of monitoring extreme market movements.

**3. Volatility was concentrated during specific periods:**
30-day volatility reached a maximum of **1.1104% on 26 October 2015**, with elevated volatility concentrated around October–November 2015.

**4. Moving averages provide clearer visibility of market trends:**
The 30-day moving average helps smooth daily fluctuations and provides a clearer view of broader USD/MYR movements.

**5. OPR and MYOR provide additional monetary-market context:**
Comparing FX movements with OPR and MYOR allows exchange-rate behaviour to be assessed alongside changes in Malaysia's monetary and overnight money-market conditions.

**6. Correlation analysis provides an initial view of market relationships:**
The analysis examines relationships between USD/MYR returns, volatility, OPR and MYOR. These correlations indicate statistical association and should not be interpreted as evidence of causation.

## Recommendations:

**1. Monitor exchange rates together with volatility:**
Combining price movements with rolling volatility can help distinguish normal fluctuations from periods of elevated market uncertainty.

**2. Use moving averages to monitor trend changes:**
Comparing current exchange-rate levels with moving-average trends can provide additional context when assessing market direction.

**3. Benchmark current market conditions against historical data:**
Historical averages, ranges and extreme movements can help contextualise current USD/MYR conditions.

**4. Monitor multiple currencies rather than USD/MYR alone:**
Analysing USD, GBP, EUR, JPY100 and SGD provides a broader perspective of MYR performance.

**5. Consider monetary indicators alongside FX movements:**
OPR and MYOR can be monitored together with FX data to provide a more comprehensive view of Malaysian financial-market conditions.

**6. Use the analysis for market monitoring rather than forecasting:**
Historical trends and volatility can support financial-market monitoring and risk assessment but should not be treated as direct forecasts or trading signals.


Prepared by: Ridzuan A., Finalized at: 12:00 PM / Sep 16, 2026.
