# NYCHA Development Data Analysis

📌 **Purpose of the Project**

This project analyzes the NYCHA Development Data Book to determine when and where it is profitable to build affordable housing in New York City (based on gross revenue only, excluding capital and construction costs). The main objectives are:

* To identify which borough is most attractive for subsidized housing development.
* To compare the profitability of new construction vs. rehabilitation projects.
* To evaluate which financing program yields the highest returns for developers.

---

🔍 **Analysis Performed**

1. Data Cleaning & Preparation
2. Correlation & Regression Analysis (Development Cost vs. Average Monthly Gross Rent)
3. Borough-Level Development Cost and Rent Analysis
4. New Construction vs. Rehabilitation Profitability Comparison
5. Financing Program Analysis (Federal, Mixed Finance/LLC1, MHOP)

---

📌 **Results**

* Development costs and number of rental rooms are strongly correlated (r = 0.73).
* Development costs and average gross rent show low correlation (r = -0.13), but the relationship is statistically significant (p < 0.05).
* Brooklyn has the most NYCHA developments (99), followed by Manhattan (96) and the Bronx (93). Queens (22) and Staten Island (10) have the fewest.
* Queens is the most attractive borough for subsidized developers, offering lower development costs with average or above-average gross rents.
* Rehabilitation projects generate similar gross revenue to new construction but at lower development costs.
* MHOP (Multi-Family Home Ownership Program) buildings have the lowest average development cost ($2.16M) and the highest average gross rent ($893/month).

---

📌 **Recommendations**

* Focus new construction under the MHOP financing program for the best cost-to-revenue ratio.
* Prioritize rehabilitation projects in Queens and Staten Island where competition is low and margins are higher.
* Avoid over-investing in the Bronx and Manhattan, which have high development costs without commanding premium rental prices.

---

📌 **Data Source**

NYCHA Development Data Book via NYC Open Data:
https://data.cityofnewyork.us/Housing-Development/NYCHA-Development-Data-Book/evjd-dqpz

---

📌 **Technologies Used**

* Microsoft Excel (Correlation, Regression, Data Visualization)
* Git & GitHub
