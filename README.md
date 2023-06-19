# SecuritiesAndFuturesP2
Obtaining certain ratios, weighted averages, and True Latencies from Data 
Fields need to be counted (recommended): instrument id, counter ip, client ip, exchange ip. You can add more if you want.
Based on the combinations of the fields, for the past 7 days, calculate their weighted latency mean (choose a weighting method). Only show the top 5 combinations. In addition, for the top 5 combinations, show their latency median per day (if data is available), efficiency ratio ((number of days data is available)/7), change ratio ((max - min)/min).

Final result will be like this:
 ![image](https://github.com/stanwu4/SecuritiesAndFuturesP2/assets/113301955/62be61ab-991d-45a8-8976-45e77f8bf1a9)
![image](https://github.com/stanwu4/SecuritiesAndFuturesP2/assets/113301955/0d61fc9f-a491-466c-8e7b-000923d27a61)

 
Fields explanations:
instrumentId	id of future being traded
counterIp	counterIp
clientIp	clientIp
exchangeIp	exchangeIp
WeightedLantency	weighted lantency (divided by 10^6)
effRatio	efficiency ratio
changeRatio	change ratio
TrueLatencyDx	latency median each day (divided by 10^6)


