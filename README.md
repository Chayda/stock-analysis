#VBA Stock Analysis
##Overview of VBA Challenge
###The purpose of this analysis is to assess multiple stock tickers, and to refactor VBA code to make it run more efficiently so it could potentially run over a larger amount of data. If the dataset were larger with more stock tickers it might slow down the original code, and the refactored code should run faster.
##Results
###I can include screenshots of the runtimes for 2017 and 2018 with the original code. The refactored code does not output the proper values to the worksheet, so it seems redundant to include screenshots of any code runtimes.
##Summary
###I struggled with this challenge. I couldn’t get my code to properly calculate the values then to output to the worksheet. I was unable to set up an output for Returns (tickerEndingPrice / tickerStartingPrice) because the values were staying at zero and zero is not a divisible number.
1. The advantages of refactoring code are to make it run more efficiently, quicker, and more user-friendly. If the code is refactored there may be lines that are not necessary or could work better and refactoring these lines should reduse the runtime for the code and allow it to run over a larger dataset  more efficiently. 
Refactoring can also make the code more clear for others to follow. Adding comments to explain the purpose of the lines can be helpful for other people who may need to work with the code.
2. The original VBA script seemed a lot more straightforward to me and I had no issues following instructions and successfully outputting the results to the worksheet. I can’t state any advantages of the refactored worksheet because I wasn’t able to complete the challenge. I’m assuming the goal for the refactored code was to have the runtime even faster so the code could be used to run over a larger index – more stock tickers that could be added to the tickers array.
