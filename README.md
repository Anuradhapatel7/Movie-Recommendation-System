# Movie-Recommendation-System
Based on the Preference that a user would give to an item movies will be recommend.

Performed:
1.Exploratory data analysis
2.Data Preprocessing 
3.NLP-Tfidf 
3.Sparse Matrix 
4.Pairwise from sklearn

And give recommendations system you give title and sig , so in the sig  there was an object which having different values,  so this will take the movie ID and find the title, so when I get the movie title it will be searching in the indices and it will give a Indices number, then this end indise number will go into the sig object, Sig[4799] after this it will give me a range of values having probability between 0 and 1, then I will convert this  value that is between 0 and 1 into a list and add enumerate to have the numbering , now the values that is between 0 and 1 I will sort two value in ascending order, after converting it into a ascending order like the maximum score will be on the top and it will be the score that the sig is having, so as we are having the numbers in ascending order so I will pick up the values the top 10 values that are more relevant to the movie ID 4799, because those are the most relevant title of the summary of the movie that is related, and this top 10 will be the recommended movie. I can pick up the movie title because I am having the movie ID in the list.
