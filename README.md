# Stock-Analysis

## Overview 
The purpose of this project was to refactor a script in order to make it run more efficiently. The purpose of the script is to pull data about various stocks for a given year and determine their total volume and return. That output is formatted to show positive and negative returns, in order to gain insight on which stocks would be profitable to invest in.  

## Results
By cutting off the for-loop that goes over the rows after it determines that you are out of data for a stock increased the speed of the program greatly. If the loop were to continue you would have looped every row of data for every stock, leading to a lot of unnecessary computation. After testing it against the original script,  the completion time of 2017 went down from ~.83 seconds to ~.52.
![2017 analysis](https://github.com/Hojo0210/Stock-Analysis/blob/main/Resources/VBA%20_Challenge_2017.png)
As expected, 2018 had similar results down from ~.83 to ~.54.
![2018 analysis](https://github.com/Hojo0210/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Summary
### Advantages or Disadvantages 
There is a very clear advantage to refactoring code, which is to increase its efficiency. Although the dataset is relatively small, if this were to be a dataset of thousands of stocks then refactoring code to run faster could result in a large amount of time saved compiling the data. Also, I'm sure refactoring code to simplify or otherwise make it more "readable" would be a bebefit to anyone (including yourself) who would need to look at the code later. 

### How do these pros and cons apply to refactoring the original VBA script?
Refactoring here resulted in a large decrease in the time to completion, increasing efficiency. 
