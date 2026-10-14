NYC Household Inflation Analysis (2019–2024)
Project Overview
This project looks at how inflation affected a hypothetical household of two young professionals living in Brooklyn, New York, between 2019 and 2024. The goal was to understand how rising prices impact everyday expenses and whether the inflation experienced by our household matched the national inflation rate.
Using Python and inflation data from the Federal Reserve Economic Data (FRED), I created a household price index and compared it with official Consumer Price Index (CPI) data.
Tools and Technologies
- Python: Data analysis and calculations
- Pandas and NumPy: Data cleaning and manipulation
- Matplotlib: Data visualization
- FRED: Historical inflation data
- Jupyter Notebook: Analysis and documentation
Methodology
I started by creating a hypothetical monthly budget for two young professionals sharing an apartment in Brooklyn. The budget included rent, groceries, transportation, restaurants, utilities, entertainment, shopping, and gym memberships.
I then used a Laspeyres Price Index to calculate how much the household's living expenses increased between 2019 and 2024.
To better understand these changes, I also:
- Compared household inflation with national CPI data.
- Examined inflation trends across different spending categories.
- Checked FRED data for missing observations and differences in available historical data.
- Compared seasonally adjusted and unadjusted grocery prices.
- Conducted a sensitivity analysis to see how changing spending weights affected the household index.
Key Findings
Our household experienced an estimated 36.6% increase in living costs between 2019 and 2024, exceeding the national inflation rate over the same period.
Rent was particularly important because it accounted for 40% of the household's budget. However, the sensitivity analysis also showed that categories with larger price increases could significantly influence the index when their spending weights changed.
Another important finding was that national inflation figures don't necessarily represent what individual households experience. Where someone lives and how they spend their money can make a difference.
Limitations
One limitation of this project is that the household budget uses estimated prices rather than actual spending records. While official FRED data helped provide a reliable comparison, the household index should be viewed as an illustration rather than an exact measure of inflation in Brooklyn.
Conclusion
This project helped me better understand how inflation is measured and why it can affect households differently. It also gave me experience working with economic data, calculating price indexes, checking data quality, and using sensitivity analysis to evaluate results.
My biggest takeaway is that inflation isn't just about how much prices increase, but also about what people spend their money on.
