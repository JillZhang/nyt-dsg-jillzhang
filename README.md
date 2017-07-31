Problem description: In homework_singlecopy.tsv you will find one year of time series data for 100 stores which sell The New York Times newspaper. The data appears as follows in tab delimited format (tsv):


date	account	bipad	draws	sold

2014-01-06 00:00:00	1	90016	8.0	0.0

2014-01-13 00:00:00	1	90016	12.0	3.0

2014-01-20 00:00:00	1	90016	11.0	4.0

2014-01-27 00:00:00	1	90016	7.0	1.0

2014-01-07 00:00:00	1	90026	3.0	2.0

The columns are:

‘date’: The date that the transactions occurred on.

‘account’: The account number which uniquely identifies the store.

‘bipad’: Represents the day of the week and edition of the paper - e.g., 900dm is the dth day of the week (starting on Monday) and m is the edition of the paper.

‘draws’: The number of papers which The New York Times delivered to the particular store.

‘sold’: The number of papers which were purchased at that store.

In this task, you are asked to create a model, in Python, which attempts to predict the optimal number of newspapers to deliver (aka "draw") for each day during the week starting on January 01-2015.

It is expected that you validate your model against the historical data to confirm its accuracy (however you choose to define it), and that you explain your work. 

If you would like to take the exercise further and optimize for profit instead of accuracy, you can assume a cost to the company of $0.25 and a sale price of $1. (neither is accurate).

Please feel free to contact us if you have any questions concerning the project. 

Please submit solutions as pushed+committed changes; please ask any questions as github issues. 

Best regards,
The Data Science Group, The New York Times
