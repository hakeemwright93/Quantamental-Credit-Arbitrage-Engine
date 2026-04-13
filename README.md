# Quantamental-Credit-Arbitrage-Engine

EXECUTIVE SUMMARY: Systematic Credit Risk & Covenant Analysis

Issuer: Ford Motor Credit Company LLC (FMCC)

Date: April 2026

Thesis: Identifying structural risk-adjusted alpha through the synthesis of maturity bottlenecks and legal covenant strength.

1. Quantitative Signal: The 2026 Maturity Wall
Using Note 9 (Debt and Commitments) from the 2026 10-K, my analysis identified a massive liquidity "bottleneck":
•	2026 Maturity Peak: $51.8 billion in debt is contractually due in 2026. 
•	Context: This represents a significant refinancing risk peak for the company's $141.4 billion total debt stack. 
•	Risk: This "Maturity Wall" creates substantial pressure in the current interest rate environment, as nearly 37% of the debt matures within a single year.

2. Qualitative Analysis: NLP-Driven Legal Due Diligence
I utilized a custom NLP pipeline (Gemini) to parse Exhibit 4-C (Description of Securities) to determine if bondholders are protected during this 2026 peak:
•	Covenant Strength Score: 3/10 (Weak)
•	Key Vulnerabilities Identified:
o	Porous Negative Pledge: The indenture includes a 5% "basket" of Consolidated Net Tangible Assets (CNTA) and broad carve-outs for securitizations, hedging, and export financing. 
o	Lack of Event Risk Protection: The document contains no "Change of Control Put" or 101% repurchase clause, leaving bondholders exposed if the company is acquired. 
o	No Cross-Default: The "Events of Default" are limited to specific note series; a default on one series does not necessarily trigger a default for others. 
o	Unsecured Ranking: These are unsecured obligations, ranking equally with other unsecured debt but structurally subordinate to any secured debt.

![Ford Covenant Analysis](outputs/Ford_Covenant_Summary_Table.png)

4. Conclusion & Strategy
The combination of a high-pressure $51.8B maturity wall and minimal legal protection suggests that the market may be underpricing the potential for structural subordination. A systematic credit strategy should favor issuers with flatter maturity profiles or higher "Covenant Strength Scores" to mitigate the risk of refinancing-driven distress.

![Ford Maturity Wall 2026](outputs/ford_maturity_wall.png)
