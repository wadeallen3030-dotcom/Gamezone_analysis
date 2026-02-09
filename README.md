# Project Background
This project focuses on a comprehensive business intelligence analysis for GameZone, a global gaming hardware retailer, to evaluate multi-regional sales performance and operational efficiency. As the Business Analyst, I conducted an end-to-end investigation into global revenue drivers, seasonal market trends, and platform-specific purchasing behaviors. By analyzing large-scale transactional data, the project aims to identify high-performing product categories and regional growth opportunities, providing executive leadership with the data-driven insights necessary to optimize marketing strategies and stabilize global profit margins.

Beyond performance metrics, the analysis serves as a critical diagnostic tool for GameZone’s operational health. It addresses significant data integrity challenges and logistical anomalies, such as purchase-to-shipment inconsistencies and duplicate processing, which impact financial reporting. Additionally, the project investigates historical refund patterns to uncover potential bottlenecks in fulfillment or product quality. This report ultimately functions as a strategic roadmap for stakeholders in Sales, Marketing, and Operations to improve customer retention and streamline international business processes.

A Jupyter notebook of complete work-through python file can be viewed [here](https://github.com/wadeallen3030-dotcom/Gamezone_analysis/blob/main/gamezone.ipynb)

# Executive Summary
<img width="1166" height="576" alt="image" src="https://github.com/user-attachments/assets/c3918d7c-fe57-4b6d-9450-a611092c8020" />

## To optimize future growth, the following actions are receommended:

### - Revenue & Market Performance:
The total gross revenue for the recorded period reached approximately $6.1M. The United States remains the primary engine of growth, contributing over $2.9M with an Average Order Value (AOV) of $$287. While revenue remained steady in the early stages, a significant upward trend began in April 2020, eventually peaking in December 2020 with monthly sales exceeding $540K.
### - Refund Analysis & Financial Impact:
The analysis uncovered a significant volume of returns, with 3,197 orders being refunded. This represents a total value of $1.18M, which accounts for approximately 19.4% of the total gross revenue. This high refund rate is a critical concern, as it represents a substantial loss of realized profit and suggests potential issues in product quality or customer satisfaction.
### - Data Integrity & Operational Risks:
A deep dive into the operational data revealed that 1,992 orders contained chronological anomalies—specifically, purchase timestamps documented as occurring after shipping timestamps. These errors represent nearly 10% of the total dataset. Such inconsistencies pose a risk to future predictive modeling and strategic planning, as they can lead to inaccurate lead-time reporting and skewed performance metrics.
### - Recommendations:
 - Resource Optimization: Maintain and strengthen the supply chain for high-margin drivers, specifically 27-inch 4K Gaming Monitors, Nintendo Switch, and PS5 Bundles in the US market.
 - Expansion Targeting: Redirect resources toward regions and products showing high potential, such as the United Kingdom market and the Ideapad product line, which show promising traction.
 - Portfolio Rationalization: Phase out low-performing accessories, such as gaming mice and headsets, to allow for more focused marketing and inventory investment in core hardware.
 - Trend Replication: Conduct a post-mortem on the marketing and external factors that drove the 2020 surge to develop a repeatable strategy for future peak seasons.
 - Audit Data Workflows: Investigate the data entry and storage processes immediately. Implementing automated validation rules at the point of entry is necessary to eliminate the $10\%$ error rate in order documentation.

# Insights & Deep - Dive

## Revenue Analysis
<img width="690" height="449" alt="image" src="https://github.com/user-attachments/assets/a41e995c-5664-4b63-a096-8249ff80bd0b" />


<img width="696" height="449" alt="image" src="https://github.com/user-attachments/assets/c718f5d8-e0ed-4f21-b53b-dea3fbcec30e" />


- The top 3 most profitable products are 27 inches 4k gaming montior (leading with $1.75M), Nitendo Switch ($1.5M) and PS5 bundle ($1.45M). All three have the same selling trend that began to spike up toward the end of the year. 


   
