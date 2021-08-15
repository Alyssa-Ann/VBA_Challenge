# VBA_Challenge
Stock Analysis with refactored Code for increased efficiency 
# Stock Analysis with VBA

## Overview of Project
	Our friend Steve is trying to run a stock analysis to present to his parents who are interested in
  investing. An original dataset of twelve stocks was presented, and VBA code was created to analyze
  this data. After the success of the analysis of the original dataset, Steve asks for an edited code
  that could work for data from the entire stock market over the past few years. 

### Purpose
	The purpose of this project is to refactor the original VBA code that worked for a small amount of
  stocks and try to run it faster. Analyzing thousands of stocks may take a long time to execute with
  the orginal code, but hopefully a refactored code will be more efficient and able to analyze the data
  faster. Both the original code and the refactored code use run buttons linked to code to determine the
  year the data is run through. The code then uses arrays, a timer, if-then conditional statements, and
  conditional formatting to present this data in an easy to read and visually appealing display. 

### Differences in Code
	The original code looped through the entire dataset for each stock ticker symbol, driving up the run
  time. This original code was refactored to only have to loop once for all datasets and stock ticker
  symbols. As you will learn in the following report, the refactored code does indeed lower run time. 

## Results

### Analysis of Stock Performance between 2017 and 2018
	For all of the stocks presented by Steve, the total daily volume was 3,166,639,100 in 2017 and
  3,306,038,200 for 2018. That is a growth of about 140,000,000 from 2017 to 2018. Despite this growth,
  many of the stocks saw a negative return percentage in 2018 as compared to 2017. The growth was seen
  in tickers ENPH and RUN. If one was looking to invest in stocks, these two would be considered good
  return on investments. The ticker TERP was a negative return in both 2017 and 2018. All other tickers
  went from positive returns in 2017 to negative returns in 2018 with DQ seeing the biggest drop in
  return percentage. This is relevant because Steve's parents were originally only interested in
  investing in DQ.
![VBA_Challenge_2017_Stock_Analysis](https://user-images.githubusercontent.com/88064181/129464514-e876b8db-e6c3-4f42-9a2d-ae508725a918.png)
 
 
![VBA_Challenge_2018_Stock_Analysis](https://user-images.githubusercontent.com/88064181/129464427-a9685ac2-1b71-4508-bc58-05ef5eb9da9e.png)


### Analysis of Execution Time Between Original and Refactored Script
	Run times for the original code averaged almost .7 seconds per analysis. Run times for the refactored
  code ran for almost .1 second. This difference of .5 seconds means the refactored code was successful
  in optimizing the analysis. While it may not seem like a significant time with such a small dataset,
  when applied to datasets for thousands of tickers, this will indeed save time. 
  
  ![VBA_Challenge_2017_Before_Refractoring](https://user-images.githubusercontent.com/88064181/129464429-60e0e13c-49de-476d-9140-97ea3a983d5b.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/88064181/129464431-84e5e325-b7f2-424a-9782-ba11db127636.png)
![VBA_Challenge_2018_Before_Refractoring](https://user-images.githubusercontent.com/88064181/129464433-0e8a3d52-4791-4a2a-8bba-2f71d3b5d1cb.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/88064181/129464434-00e06eb6-e56e-41b2-827c-1920c90bbaea.png)


## Summary

### Advantages of Refactoring Code
	As proven with this dataset, refactoring a code can show significant increase in efficiancy.
  Optimizing a code is never a bad thing when it comes to running the code. Through the refactoring
  process, a coder can spot redundancies and dulications in code that may not need to be there.
  Especially for beginner coders, the original codes may be expanded to overcorrect errors or bug fixes,
  as well as run with expanded loops. By refactoring, the coder can clean up the code, input fresh
  perspectices, and cut down on the number of routines within the subsets.
	

### Disadvantage of Refactoring Code
	As with most editing, refactoring a code comes with distinct disadvantages. If one coder is
	trying to
  refactor a code written by another, they may be thinking in opposing logic. This can create errors
  within the code which makes the coder have to go back and debug the code multiple times. Refactoring a
  code also leads to the potential of taking a stable code and making it severely unstable by cutting
  out relevant script. Coders in the industry may be under deadlines which will lead to questioning
  whether optimized code will save more time than refactoring a code will take.
	

### Relevancy fo Pros and Cons Concerning Refactoring the Original VBA Code
In terms of this project, the original code was a nested for loop. This loop had to output all
current
  data each time it looped, resulting in numerous repetitions of the same loop. The refactored code had
  one loop for the data and another output loop for the datasets which reduced the amount of times it
  had to be repeated to get the same results. This is advantagous because reducing the loops decreases
  the memory needed to process the data, reducing the run time. The con is the time put into refactoring
  the code. For such a small dataset, it took more time to refactor this code than it did to run the
  data. When this dataset is expanded, the decreased run time will be exponetial and well worth the time
  put into refactoring the code.
