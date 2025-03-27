# Examining Liquidity and Market Trends: A Reverse Repo and S&P 500 Analysis

This repository contains code that explores the relationship between the Federal Reserve’s reverse repo operations and the S&P 500 stock index. It aims to shed light on whether changes in liquidity—reflected by the amount of cash placed in the Fed’s reverse repo facility—may hint at subsequent movements in the equity market. While high or low correlations between these two data series can be observed, this analysis does **not** prove that shifts in reverse repo amounts **cause** changes in stock prices.

## What Are Reverse Repo Operations?

Reverse repo transactions occur when financial institutions—such as banks and money market funds—temporarily deposit excess cash with the Federal Reserve in exchange for securities. This mechanism helps manage short-term liquidity in the financial system. It is closely related to other Fed tools like quantitative easing (QE) and balance sheet adjustments that can affect the flow of money in and out of markets.

## Key Takeaways

1. **Correlation vs. Causation**: The code computes rolling correlations between reverse repo totals and next-day S&P 500 closes. While correlations may spike toward 1 or -1, this does not guarantee that outflows from reverse repos are the direct source of capital for equity investments.

2. **Excluded Factors**: This analysis does not include other critical influences such as prevailing interest rates, the yield curve, or the amount of treasuries purchased by the Fed. Each of these can affect the flow of funds and the broader liquidity environment.

3. **Visual Diagnostics**: The script produces charts showing:
   - Smoothed Reverse Repo totals (in billions USD),
   - The S&P 500’s next-day closing price,
   - Rolling correlation data to see how the relationship shifts over time.