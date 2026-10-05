# Zomato Restaurant Data Analysis

**Prepared By:** [Your Name]  
**Organization / Institute:** [College / Institute Name]  
**Dataset:** `cleaned_zomato_data.csv`  
**Date:** 08 August 2026  

## Executive Summary
The supplied dataset contains 148 restaurant records and 8 columns. There are no missing values and no exact duplicate rows. The average rating is 3.63, average votes are 264.81, and average approximate cost for two people is ₹418.24.

Dining is the largest category with 110 records. Online ordering is available at 58 restaurants, while table booking is available at only 8. Votes and ratings have a correlation of 0.49; votes and cost have a correlation of 0.32.

## Dataset
| Column | Type | Description |
|---|---|---|
| name | Text | Restaurant name |
| online_order | Categorical | Online ordering availability |
| book_table | Categorical | Table booking availability |
| rate | Text/rating string | Rating such as 4.1/5 |
| votes | Numerical | Number of customer votes |
| approx_cost(for two people) | Numerical | Approximate cost for two people |
| listed_in(type) | Categorical | Restaurant type |

## Key Findings
- Dining: 110/148 records (74.3%).
- Cafes: 23 records.
- Other: 8 records.
- Buffet: 7 records.
- Online order Yes: 58 (39.2%).
- Book table Yes: 8 (5.4%).
- Mean rating: 3.63; median: 3.70.
- Mean cost: ₹418.24; median: ₹400.
- Votes vs rating correlation: 0.49.
- Votes vs cost correlation: 0.32.

## Business Recommendations
1. Benchmark restaurant pricing by restaurant type.
2. Evaluate digital ordering and table-booking adoption separately.
3. Consider rating and vote volume together when assessing customer engagement.
4. Study high-vote restaurants as engagement benchmarks.
5. Collect location, cuisine, revenue, review text, and time-based data for future analysis.

## Conclusion
The analysis demonstrates how Python, Pandas, NumPy, and visualization tools can transform restaurant records into business insights. The strongest conclusions are about restaurant-category mix, digital-service availability, pricing differences, and relationships among ratings, votes, and cost.

## References
- User-provided dataset: `cleaned_zomato_data.csv`
- Python: https://docs.python.org/3/
- Pandas: https://pandas.pydata.org/docs/
- NumPy: https://numpy.org/doc/
- Matplotlib: https://matplotlib.org/stable/
- Seaborn: https://seaborn.pydata.org/
