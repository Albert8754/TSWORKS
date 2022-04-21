# TSWORKS OPTINAL ASSIGNMENT
Download Apple Inc. (AAPL) stock data from https://finance.yahoo.com/quote/AAPL/history?p=AAPL
Optional Steps-
Install MySQL/Postgres or any DB on your personal desktop or Cloud free account.
Create a table for Apple's stock data.
Load the downloaded data from CSV to DB table using python or any programming language.
Create a Rest API using any programming language which uses the CSV or data base table as back-end data source.
API should accept date as Input and return stock values as a json as mentioned below.
{

"Date": "2021-02-18",

"Open": 129.199997,

"High": 130,

"Low": 127.410004,

"Close": 129.710007,

"Adj Close": 128.943634,

"Volume": 96856700

}
ANS:
hERE i HAVE USED sqlite3 to create the Data base and csv file was uploaded

https://github.com/Albert8754/TSWORKS/blob/main/Abby.sqlite3

Then I have make connection to python  sqlite to database
https://github.com/Albert8754/TSWORKS/blob/main/restflask.py

then flask file is been created:

The Html File:
