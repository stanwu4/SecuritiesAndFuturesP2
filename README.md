SecuritiesAndFuturesP2
Obtaining certain ratios, weighted averages, and True Latencies from Data Fields need to be counted (recommended): instrument id, counter ip, client ip, exchange ip. You can add more if you want. Based on the combinations of the fields, for the past 7 days, calculate their weighted latency mean (choose a weighting method). Only show the top 5 combinations. In addition, for the top 5 combinations, show their latency median per day (if data is available), efficiency ratio ((number of days data is available)/7), change ratio ((max - min)/min).

Final result will be like this:  ![image](https://github.com/stanwu4/SecuritiesAndFuturesP2/assets/113301955/5fafa99f-cb60-4ba9-90fd-c3b308938d01)


Fields explanations: instrumentId id of future being traded counterIp counterIp clientIp clientIp exchangeIp exchangeIp WeightedLantency weighted lantency (divided by 10^6) effRatio efficiency ratio changeRatio change ratio TrueLatencyDx latency median each day (divided by 10^6)

For Part 3, your task is to find the number of days with no data for a specific combination.

Select a period of 7 consecutive days. For each of the 7 days, do the same job in phase 2. For the combinations in last day's result, find out which day they first appeared in the past 7days. After you find out their day of first appearance, find the their number of days with no data after this day.

