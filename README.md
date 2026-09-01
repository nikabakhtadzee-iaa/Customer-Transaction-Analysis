# Customer-Transaction-Analysis
I worked on customer transaction data in various ways. Firstly, i cleaned data to make it sophisticated for further analysis. Then i made exploratory analysis in order to get full picture.

Detailed review:
In the data cleaning phase, I created formulas to reclassify products to their correct categories: Electronics, Furniture, and Office Supplies. I also extracted year, month, and quarter attributes from purchase dates for easy tracking over time and added a audit math check that confirmed zero calculation errors across the entire dataset. With the help of Power Query, I made sure that all columns types were appropiate, also trimmed and did set first letter uppercase PaymentMethod column.

During exploratory data analysis, I categorized payment methods into monitored electronic channels (Credit Card, Debit Card, Online) and unmonitored cash channels (Cash, Gift Cards). I discovered that unmonitored payments accounted for 1.26 million (39% of the total 3.27 million portfolio). Additionally, I identified 390 large transactions over 3,000 that made up nearly half (1.61 million) of total spending, and flagged 1.40 million in potential dispute risk from low customer review ratings (1 or 2 stars).

Finally, I built an automated dashboard in Excel by pivot tables and KPI  The dashboard highlights total volume, unmonitored payment share, and dispute exposure alongside charts. I made the entire report interactive, allowing all charts and metrics to update instantly when specific filters are applied.
