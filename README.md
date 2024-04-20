# Performance-of-ESG-based-strategies
 Replication of a paper on the topic of ESG-based strategies

### Summary of the Notebook: "Performance von ESG basierten Strategien"

This Jupyter notebook explores the performance of investment strategies based on Environmental, Social, and Governance (ESG) scores, assessing the financial viability of socially responsible investing. It uses Python libraries such as `pandas` for data manipulation, `matplotlib` and `ffn` for financial performance visualization, `numpy` for numerical operations, and `scipy` along with `statsmodels` for statistical analysis.

Key techniques include:
- Analyzing investment returns from portfolios formed based on high and low ESG scores.
- Using statistical tests to compare the performance of these portfolios against market benchmarks.

### Detailed Explanation

The notebook does not define functions within the code cells but rather focuses on executing a series of analyses directly within each cell. It starts by loading financial data and ESG scores, then processes this data to form portfolios based on the top and bottom percentiles of ESG scores.

For each year, the notebook:
1. Identifies top and bottom ESG companies.
2. Constructs long and short investment portfolios.
3. Calculates daily and cumulative returns for these portfolios.

Statistical analysis is performed to evaluate the significance of the returns, using metrics like geometric mean and percentile-based comparisons to assess the impact of ESG scores on investment performance.

Additionally, factor analysis is conducted to understand the underlying factors that affect ESG score variability and its consequent impact on stock performance. This involves the use of a `FactorAnalyzer` to delve deeper into the dimensions of ESG that influence financial returns the most.

Visualization plays a crucial role in the notebook, with extensive use of plots to illustrate the cumulative returns and performance trends of the ESG-based portfolios over time. This provides a visual representation of the potential financial advantages or drawbacks of incorporating ESG criteria into investment strategies.

Overall, the notebook is a comprehensive analysis tool for evaluating the financial performance of ESG-based investment strategies, providing valuable insights into the viability and impact of socially responsible investing.