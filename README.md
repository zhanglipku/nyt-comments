# nyt-comments
The package scraps comments posted on New York Times articles and returns the data as pandas dataframes (with an option to directly store it in csv files). The two dataframes - one corresponding to comments and another articles - are cleaned up and preprocessed to be used as a dataset for data science/machine learning projects. The retrieval of the comments can be customized based on a number of parameters such as a specific timeline, a search query, etc. The package can also be used as an API wrapper for NYT article_search API to perform article search and get the results processed as a ready-to-use pandas dataframe (with an option to store it in csv files). The tutorial here illustrates the use of the three main functions -- `get_dataset`, `get_comments` and `get_articles`.

Before using the functions `get_dataset` and `get_articles` in the package, you will need to get NYT article_search API key from here. Please review the terms and condition.  The package can be used without the API key for retrieving comments using the function `get_comments` given the url of the specific article. There is no direct daily limits for comments, to the best of knowledge but the daily limit for article search is 1000.

### Dependencies
Python 3.4+


### Python package required
pandas

