# VBA Stock Analysis

## Overview of VBA Challenge

### The purpose of this analysis is to assess multiple stock tickers, and to refactor VBA code to make it run more efficiently so it could potentially run over a larger amount of data. If the dataset were larger with more stock tickers it might slow down the original code, and the refactored code should run faster.

## Results

### Screenshots of runtimes are included for 2017 and 2018 with the original code, as well as for the refactored code. In this circumstance, the runtime were a touch slower for the refactored code, as per below:

### Original Code 2017 (runtime: 0.68 seconds)
![VBA_Challenge_2017_Original](https://user-images.githubusercontent.com/74624855/125227183-66aa1780-e2a0-11eb-9e43-d4a6bc311fb9.png)

### Refactored Code 2017 (runtime: 0.71 seconds)
<img width="500" alt="VBA_Challenge_2017_Refactored" src="https://user-images.githubusercontent.com/74624855/128508915-20bb0b4b-f5ad-48a5-8b85-1f6b335ce452.png">

### Original Code 2018 (runtime: 0.67 seconds)
![VBA_Challenge_2018_Original](https://user-images.githubusercontent.com/74624855/125227189-690c7180-e2a0-11eb-9d7b-5c7b656c80a8.png)

### Refactored Code 2018 (runtime: 0.71 seconds)
<img width="500" alt="VBA_Challenge_2018_Refactored" src="https://user-images.githubusercontent.com/74624855/128509008-9474e766-2ea0-48c9-b2ec-a67a5d6f79f8.png">

## Summary

1. The advantages of refactoring code are to make it run more efficiently, quicker, and more user-friendly. If the code is refactored there may be lines that are not necessary or could work better and refactoring these lines should reduse the runtime for the code and allow it to run over a larger dataset  more efficiently. 
Refactoring can also make the code more clear for others to follow. Adding comments to explain the purpose of the lines can be helpful for other people who may need to work with the code.
2. The goal for the refactored code was to have the runtime even faster so the code could be used to run over a larger index – more stock tickers that could be added to the tickers array. In the end the two codes ran in a similar amount of time.


