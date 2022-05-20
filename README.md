
# Stock-Analysis Report
---

### Background:

---

This analysis was created with the purpose of refactoring the Microsoft Excel VBA code while obtaining better efficiency on the code's runtime. We obtain 12 different stock data over the years from 2017 and 2018. With this data, we want to determine which stocks would be advisable to invest in based on the stock's history. The daily stock data for each stock contains the following information: 

- Stock Opening price
- Stock Closing price 
- Stock High Price
- Stock Low Price
- Stock Closing Price 
- Stock Adjusted Closing Price
- Volume of the Stock


Arrays provide you with random access to elements, which allows you to access position elements more efficiently compared to data structures. For the refactored code I created 4 arrays which are called: 

- tickers(12) = This array intends to create a ticker symbol that will be used to identify each stock
- tickerVolume(12) = This array intends to hold volume data
- tickerStartingPrice(12) = This array intends to hold the starting price 
- tickerEndingPrice(12) = This array intends to hold the ending price 

---

### Our Data Results: 

---

2017 Stock Analysis:

![2017 Stock Analysis](https://i.ibb.co/5GZJkyM/2017-Stock-Analysis.png)

2018 Stock Analysis:

![2018 Stock Analysis](https://i.ibb.co/YQk6mY0/2018-Stock-Analysis.png)



Looking solely at the 2017 results, it would be very misleading for a potential investor because 11 of the 12 stocks that we are analyzing are showing a positive return, and some stocks with close to a 200% increase. However, one year later in 2018 only 2 out of the 12 stocks were showing a positive return. Based on a two-year trend we can see that the following stocks return a positive return in both years. : 

- ENPH 
- RUN

---

### Efficiency with Refactoring: 

---

The initial runtime for my 2017 code took approximately 36.8828 seconds, however by refactoring I was able to bring the runtime down to approximately 0.4668 seconds. 

Initial 2017 Runtime:

![Initial 2017 Runtime](https://i.ibb.co/B4SkGxP/2017-Intial-Speed.png)

Refactored 2017 Runtime: 

![Refactored 2017 Runtime](https://i.ibb.co/wctYhr1/2017-Refactored-Speed.png)

The initial runtime for my 2018 code took approximately 17.8964 seconds, however by refactoring I was able to bring the runtime down to approximately 0.2519 seconds. 

Initial 2018 Runtime:

![Initial 2018 Runtime](https://i.ibb.co/1rn646b/2018-Intial-Speed.png)

Refactored 2018 Runtime: 

![Refactored 2018 Runtime](https://i.ibb.co/ZmbtqBc/2018-Refactored-Speed.png)

----

### Conclusion: 

---
 
The advantage of refactoring the code is that when working with larger sums of data this could be an even more significant delay which in turn means a loss of profit for large companies. It is always best practice to save the original code as you don't want to make life harder by making a mistake while refactoring and then losing track of the original code. 
