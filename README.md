# The coolest programming language

By collecting data from twitter users, we can
infer trending programming languages in our region,
in Italy, in EU, USA and so on.

A similar project can be found here http://mashable.com/2015/01/06/maps-programming-languages-states/


## Collect data from twitter

An http client using the twitter APIs, pulls all tweets
for a specific geographical region containing specific
text associated with a set of programming languages.

Raw data is stored in a local database for further analysis.


## Data cleanup and analysis

Clean up data removing unrelated tweets and group it by date/region/country.


## Presentation

Build a simple webapp to display results. Choose one of the following:

### Implementation A: Web application MVC

- create objects to load data from db (JDBC)
- write some dynamic java pages to show data loaded from the DB 
- implement some client feature to show the data in the best way 

### Implementation B: Restful (for example https://spring.io/guides/gs/rest-service/)

- create objects to load data from db (JDBC)
- implement some servlet to give some json information loaded from db 
- implement some client feature to get json info and show it the data in the best way