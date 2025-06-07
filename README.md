# st2195_assignment_6

1. Load and merge the datasets keeping all information available for the dates in 
which there is a measurement in “fx.csv”. [1 point]
2. Remove entries with obvious outliers or mistakes, if any. [1.5 points]
3. Handle missing observations for the exchange rate, if any. This should be done 
replacing any missing exchange rate with the latest information available. 
Whenever this cannot be done, the relevant entry should be removed entirely
from the dataset. [1.5 points]
4. Calculate the exchange rate return. Extend the original dataset with the 
following variables: “good_news” (equal to 1 when the exchange rate return is 
larger than 0.5 percent, 0 otherwise) and “bad_news” (equal to 1 when the 
exchange rate return is lower than -0.5 percent, 0 otherwise). [1.5 points]
5. Remove the entries for which contents column has NA values. Generate and 
store in csv the following tables [1.5 points each]:
a. “good_indicators” – with the 20 most common words (excluding articles, 
prepositions and similar connectors) associated with entries wherein 
“good_news” is equal to 1;
b. “bad_indicators” – with the 20 most common words (excluding articles,
prepositions and similar connectors) associated with entries wherein 
“bad_news” is equal to 1;
Any observation from the common words found above?
