Project: Air Quality in Indian State Capitals (2018–2023)

Problem: Which Indian state capitals have the worst air quality, in which months, and is it improving?

Data: Daily AQI bulletins from CPCB for 11 state capitals, sourced via urbanemissions.info. 23,557 city-day records after cleaning and filtering to 2018–2023.

Tools: Microsoft Excel (Power Query, Pivot Tables, Charts, Conditional Formatting)

Source: https://urbanemissions.info/india-air-quality/india-ncap-aqi-indian-cities-2015-2023/

What I did:

Combined 11 city CSV files using Power Query’s From Folder feature
Cleaned data: fixed date formats, standardised category labels, replaced inconsistent pollutant names (OZONE → O3), and split multi-pollutant cells into one row per pollutant
Validated all results using two independent methods (pivot vs AVERAGEIFS)
Built 5 charts and a one-page dashboard

Key findings:

Delhi had the worst average AQI at 207.8 (Poor category), followed by Patna (184.7) and Lucknow (167.4). Southern cities were the cleanest.
December is the worst month (avg AQI 182.0); July is the cleanest (62.2). Monsoon rains clean the air.
Average AQI fell from 136.4 in 2018 to 113.1 in 2023, but the 2020 COVID lockdown distorts the trend.
PM10 and PM2.5 dominate, accounting for 68% of all prominent pollutant days.
Severe pollution days declined from 42 (2018) to 18 (2023), the clearest sign of genuine improvement.

Limitations: ~5% of city-days are missing (mostly 2018–2019); only 11 of 26 state capitals included; 2020 COVID effect distorts the trend; AQI is capped at 500.

Author: Palavesh Raja K R
