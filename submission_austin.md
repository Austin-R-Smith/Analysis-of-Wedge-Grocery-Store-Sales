
# Applied Data Analytics

## Wedge Project

<!-- Any general commentary you'd like to say about the project --> 

### Task 1

* Files for this task: 

`Part 1-A.ipynb`: 
Cleans all of the Wedge ZipOfZips File and, theoretically, would push them to my GBQ project. However, I uploaded the clean files into GBQ via the google cloud storage method because of the "time out" error.


### Task 2

* Files for this task: 

`Part 2.ipynb`: extracts a random sample of 2.5% of owners and all of their associated transactions, then writes that sample to a local text file.
	

### Task 3

* Files for this task: 

`Part 3.ipynb`: queries GBQ for tables that return sales by date by hour, sales by owner by year by month, and sales by product description by year by month. The code pulls those queries into a dataframe and then a text file, then uploads the text files to a database.

## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |85,760,139   |85,760,139   | 0  | 0  |
| January 2012 Rows  | 1,070,907  | 1,070,907  |  0 | 0  |
| October 2012 Rows  | 1,042,287  | 1,042,287   |  0 | 0  |
| Month with Fewest  | February   | February  | No  | NA  |
| Num Rows in Month with Fewest  | 6,556,770  | 6,556,770   |0   | 0  |
| Month with Most  |May   | May  | No  | NA  |
| Num Rows in Month with Most  | 7,578,372  | 7,578,372  | 0  | 0  |
| Null_TS  | 7,123,792  | 7,123,792  | 0  | 0  |
| Null_DT  | 0  | 0  | 0  | 0  |
| Null_Local  | 234,843  | 234,843  | 0  | 0  |
| Null_CN  | 0  |  0 |  0 | 0  |
| Num 5 on High Volume Cards  |14987   |14987   | No  | NA  |
|  Num Rows for Number 5 | 460,630  |460,630   |  0 | 0  |
| Num Rows for 18736  |12,153   |12153 | 0  | 0  |
| Product with Most Rows  | banana organic  | banana organic  | No  | NA  |
| Num Rows for that Product  |908,639   | 908,639  | 0  | 0  |
| Product with Fourth-Most Rows  | avocado hass organic  | avocado hass organic  | No  | NA  |
| Num Rows for that Product  | 456,771  | 456,771  |  0 |  0 |
| Num Single Record Products  | 2,769  | 2,769   | 0  | 0  |
| Year with Highest Portion of Owner Rows  |2014   | 2014  | No  | NA |
| Fraction of Rows from Owners in that Year  | 0.7591   | 0.7591  | 0  |  0 |
| Year with Lowest Portion of Owner Rows  |2011   | 2011  | No  | NA |
| Fraction of Rows from Owners in that Year  | 0.7372  | 0.7372  | 0  |  0 |

## Reflections

I am absolutely amazed that our results match. So much so that I'm suspicious of it. But I won't dig!

This was a doozy. I thought the advice to start on part 3 and work your way backwards was good as it forced me to repeatedly go through the python-gbq and python-sql exercises and wrap my head around how all the different programs "talk" to each other via python scripts. 

By FAR, the most difficult part of this, for me, was the cleaning (probably because I didn't do the summer python course). I could follow the exercises and figure out how to identify headers and delimiters, but I had no idea how to approach fixing them or unifying them. An extra exercise or two with some sample code geared towards those kinds of tasks would have helped me, though I will say that it didn't seem like others struggled as much as me in this regard. 
