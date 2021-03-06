# SC1015-Mini-Project-SC5-Grp-3
Group Members: Gwee Jia Xiang, Solomon Tneo, Xavier Wong


Percentage of work done: 

                         Gwee Jia Xiang - Coding (40%) + Powerpoint(33%)
                         Solomon Tneo - Coding (30%)+ Powerpoint(33%) + Recording(50%)
                         Xavier Wong - Coding (30%)+ Powerpoint(33%) + Recording(50%)

Dataset: Top 1000 Highest Grossing Movie from Kraggle


**Problem Statements**:

    Does the distributor of the movie affect the world sales?
    Does the release date of the movie affect the world sales?
    Does the movie runtime affect the world sales?
    Does the genre of the movie affect the world sales?

Used pandas to extract, analyse and clean the data. Plotted graphs to easily visualise and analyse data. Splitted data into 75:25 train and test data for machine learning using logistic regression. Logistic Regression is used to predict world sales with distributor, release date, movie runtime and genre.


**Conclusions**:

The world sales is affected by all the above mentioned variables. However, individually, the variables are bad predictors for world sales yet when combined, world sales can be predicted with 68.8% precision with logistic regression.
Movies distributed by Walt Disney Studios in the month of April to August, with 90 to 140mins runtime and the adventure genre generally do better with its World Sales. 


**Main Takeaways**:

    Learnt about machine learning with categorical data
    Learnt about new data formatting methods (e.g. pd.melt, _timedelta, str.extract)


**References**:
 
    https://www.investopedia.com/articles/financial-theory/11/walt-disney-entertainment-to-empire.asp
    https://nofilmschool.com/adventure-genre-in-film-and-tv#:~:text=The%20adventure%20genre%20is%20built%20around%20our%20desire%20to%20search,pure%20escapism%20for%20those%20watchin
    https://www.kdnuggets.com/2021/05/deal-with-categorical-data-machine-learning.html
