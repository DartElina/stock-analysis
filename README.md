# Stock-Analysis

## Overview of Project

### Aim 
Steve has requested a workbook that analyzes stock volumes and returns at the click of a button. We had provided him with this but as the dataset grows the runtimes were getting very long, so we have simplified the code and reduced the nested loops for faster runtimes. The resulting code allows Steve to add more tickers or ticker data and keep runtimes low.
 
### Refactoring
To reduce runtimes, I’ve designated a variable index that will be used to run through the data one time and get all data arrays in one pass. Removing the nested for loops and reducing the number of loops in the program reduces the memory needed and as a result the length of time needed to run the program. 


## Results
The program created produces an output sheet with the ticker names, volumes, and returns by year requested. The sheet is formatted so that we can quickly see if the returns are positive (green) or negative (red). 
![IMAGE] Initial Run Time 2017.png
I have added a timer to measure code efficiency as well. The original code ran in approximately .75secs and new refactored codes run in approximately .18 secs.  

The resulting code quartered the time needed to run program on 3013 lines of data. This means as Steve’s data set grows, he will be able to continue to run the program efficiently. Additionally, as he runs the program on subsequent years the program will continue to operate since variables are being used throughout for use on new datasets. 

## Summary
### 1.	What are the advantages and disadvantages of refactoring code in general?
An advantage of refactoring code is to make code more efficient, or cleaner with better logic. It may be difficult, and time consuming though, so a programmer may introduce new bugs that need to be fixed.
### 2.	What are the advantages and disadvantages of the original and refactored code in this program?
I struggled with keeping my index variables straight as I added subsequent for loops. A disadvantage of refactoring code is I could have created new bugs that caused the code to break. My first pass through the program was easier for me to understand, meaning the code I created during the module, but the program took considerably longer to run. The advantages of refactoring are more efficient programs that run faster, and a clearer logic in the program. But I think I need more time to get the hang of this language to avoid creating new bugs!

