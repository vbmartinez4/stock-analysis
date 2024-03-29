# VBA of Wall Street: Stock Analysis

## Project Overview
Steve has approached us needing assistance in analyzing performance of Daqo New Energy Corporation (DQ), as his parents have placed a majority of their money in this single name stock position. His primary concern is diversification of their equity assets and therefore would like to analyze the rate of return using two years of historical data from a handful of green energy stocks in addition to Daqo’s stock. We have already prepared a workbook using VBA to automate tasks and assist with analyzing the return of these stocks. 

While Steve loved the original workbook provided to him, he is now looking to do more research for his parents and wants to expand the dataset to include the entire stock market over the last few years. We will be refactoring the VBA code originally provided to allow Steve to use the code more seamlessly and efficiently when he does analyze thousands of stocks. 

## Tools Used:
- Microsoft Excel

## Objectives:
- Create a VBA macro that can trigger pop-ups and inputs, read and change cell values, and format cells.
- Use for loops and conditionals to direct logic flow.
- Use nested for loops.
- Apply coding skills such as syntax recollection, pattern recognition, problem decomposition, and debugging.

## Results
### Original VBA Script
Upon comparing the results of the original VBA script and the refactored script, with no question the refactored code successfully allows the VBA script to run faster. Taking a closer look at before the VBA code was bring refactored, we can see that it took 0.6601563 seconds for the 2017 dataset to be analyzed when the VBA code ran and 0.6640625 seconds for the 2018 dataset. 

![original2017](Resources/2017_Before_Refactoring.png)
![original2018](Resources/2018_Before_Refactoring.png)

### Refactored Code
The essential goal of refactoring is to automate the steps of the VBA code to produce quicker results while keeping in mind that the dataset will be expanding by the thousands with the way Steve is looking to utilize it. With the inclusion of more arrays and conditional loops, they both work in tandem to allow the code to process and be more efficient with pulling the same results faster than the original script. 

![code](Resources/Refactored_code_image.png)

### Refactored Script
Viewing the below images, we can see that the execution times for the code for 2017 is 0.2148438 seconds and 2018 is 0.2265625 seconds. The refactored code not only provides the results of the returns for each stock quicker, but the dataset maintains consistency without altering any result or producing any errors. The conditional formatting code utilized shows that with the original and refactored scripts they produced the same results of visual highlighting the good and poor performance stocks. 
![refactor2017](Resources/2017_After_Refactoring.png)
![refactor2018](Resources/2018_After_Refactoring.png)

Looking at DQ’s performance for 2017 and 2018, we notice the stock is volatile and maintains a high level of risk to invest in it just alone without any diversification. High-level, it appears the green-energy space demonstrates extreme volatility as noted by the positive performance in 2017, followed by significant negative returns the following year. Honing in on DQ’s performance, the stock was up 199.4% in 2017, followed by a poor performance in 2018 with -62.6%. 

Steve should consider telling his parents to diversify away from his position, and investment in other alternative energy stocks such as ENPH or RUN, who have had positive performance in back-to-back years. While previous performance is not indicative of future returns, having a diversification strategy in general will assist in producing balanced returns where his parents will not run the risk of losing a portion of their portfolio. 

## Summary
### Advantages of Refactoring
Refactoring code is a key part of the coding process, one that allows the code to be more efficient and improves the logic of the code itself to allow it to be easily readable and understood for other coders. If code smell is present, then refactoring helps to remove it by providing cleaner design patterns of code and keeping it properly structured. It helps utilize less memory in the system as well, making it easier to update, maintain, or improve if needed down the line. That way, others are able to assist or tweak the program’s code much faster versus if left in the original script.   

### Disadvantages of Refactoring
A distinct disadvantage of refactoring is that if done imprecisely, it could introduce new bugs and errors into the code that did not exists prior, especially when the dataset is quite large. Likewise, it can be somewhat time consuming to refactor code, in which the opportunity cost of time and money need to be evaluated to see if it truly worth it. If it is expensive to refactor previous code, then the idea of refactoring might not be worthwhile to pursue. Depending on the time constraints of the project at hand, there might not be the sufficient time to go through and refactor. If rushed, then the risk of creating new errors rises.

### Pros and Cons of Original and Refactored VBA Scripts
Comparing the original and refactored VBA scripts produced for the stock analysis, the refactored code will allow for Steve to run his analysis faster if he does choose to move forward and have a larger dataset. The refactored code is clearer and has a good design pattern that makes the code easier to follow. This is where the underlying benefit of using arrays and loops provide the additional touch to improve the functionality of the code. However, if Steve’s plan is to analyze thousands of more stock positions, the refactored code might pose a problem and might need to be refactored with more complicated code. The bigger the dataset, the increase chance of an error or mistake in the code increases, which is a big caveat to the refactored code.  
