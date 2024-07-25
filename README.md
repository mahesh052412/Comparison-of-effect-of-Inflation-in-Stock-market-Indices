# Comparison-of-effect-of-Inflation-in-Stock-market-Indices

## Introduction
This study investigates the impact of inflation on stock market indices in various countries from 2000 to 2023. It explores the relationship between inflation and stock market performance, focusing on different stock types and sectors, especially in the context of the COVID-19 pandemic and the economic conditions it created.

## Background
Inflation represents the gradual loss of purchasing power due to rising prices. This study categorizes inflation into built-in inflation, cost-push inflation, and demand-pull inflation. Stock market indices, which track the performance of specific groups of stocks, can be influenced by inflation in complex ways. The study aims to identify patterns and trends in how stock market indices respond to inflationary pressures before and after the pandemic​(Mahesh_Dissertation)​.

## Tools Used
The analysis in this study utilizes several mathematical and statistical concepts:


## Analysis Performed
- Scales features to a specified range (typically 0-1).
- PowerTransformer applies a power transformation to stabilize variance and make data more Gaussian-like.
- Pearson Correlation Coefficient measures the linear relationship between two variables.
- ADF test (Augmented Dickey-Fuller Test) determines the stationarity of a time series.
- Data Transformations includes standardization, Yeo-Johnson, Box-Cox, and logarithmic transformations​.
  Standardized Data
  ![Standardized Data](https://github.com/user-attachments/assets/54c2e2b7-9a2f-46f9-871f-b403974ff4da)

  Below image of Yeo-Johnson transformation shows the results suggest that underlying non-linearities might exist in
  the data.
  ![Yeo-Johnson Transformation](https://github.com/user-attachments/assets/c128e90b-f750-4a51-b1c6-2092a5e267ad)

  The Box-Cox transform, designed for strictly positive data, might introduce distortions, making it less reliable for this particular dataset. It empha
  sizes the importance of choosing transformations that align with the characteristics of the data.
  ![Box-Cox-transformation](https://github.com/user-attachments/assets/4d55d86c-4833-4073-89e9-fff25669187e)

- **Basic Correlation Analysis:** Examines raw data to understand initial correlations.
- **Stationarity Tests:** Uses tests like the ADF test to check for trends and seasonality in the data.
- **Data Transformations:** Applies various transformations to ensure stationarity.
- **Country-wise Analysis:** Provides a detailed examination of how different countries' stock indices respond to inflation.
- **Leading Inflation Study:** Investigates the impact of leading inflation indicators on stock indices​.

## Conclusion
The study provides insights into the complex relationship between inflation and stock market indices. It reveals that certain sectors, such as energy and healthcare, performed better during the pandemic's high inflation period. The findings can help financial analysts and investors understand market behavior in response to inflation and assist policymakers in formulating economic strategies​. The inflation in all cases proved to moderately impact the stock market, while there being a 6 month lead for inflation in US and China and a 1 month lead in India. This could be a factor of India being a less mature economy and the sort term impact of inflation being magnified in the market.
