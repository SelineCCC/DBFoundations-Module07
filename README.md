# DBFoundations-Module07
## Views, Functions, and Stored Procedures

### Intro
This week is getting intense. It took me a while to figure out Question 6 and 7. I was sort of surprised that there’s only one question for UDF. However, it is a nice design as we probably need to get familiar with the Common Functions first.

### 1.	Explain when you would use a SQL UDF.
I will use a SQL UDF when:
-	I don’t want to repeat the same procedure over and over for efficiency.
-	I need to or want to use a function/procedure in a Select, Where, or Case statement.
-	I need to or want to use a function/procedure to create joins.
-	I need to or want to write fewer codes to invoke a function/procedure inside another statement.


### 2.	Explain the differences between Scalar, Inline, and Multi-Statement Functions.
I conclude their differences as below:

|                 | Parameters     | Returns                 | Performance   |
| :---            |     :---       |           :---          | :---          |
| Scalar	        | Any number     | A Single Value          |      N/A      |
| Inline          | Multiple       | A Virtual Table         | Better in performance (treated as a view) |
| Multi-Statement | Not required   | A Table-Type Result Set | Not as good in performance as Inline (Treated as a Table Variable) |

### Summary
Starting this week, we are saying goodbyes to the beginner stage. I look forward to assignments involving Scalar, Inline, and Multi-Statement Functions so we can compare them better. To be honest, there are several concepts related to functions that I still feel strange, like table variable and table-type result set. By ‘strange,’ I mean I know the definition and maybe can recognize them, but I don’t know what exactly they are.
