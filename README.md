# Project2

Data set considered for analysis
https://www.kaggle.com/kingburrito666/shakespeare-plays
This dataset consists of details of Shakespeare plays along with player deatils.

Loaded the data set into Pandas dataframe

Performed data cleaning in data and removed the redundant records and null records and described the dataset

Modified the data type of ‘Date’ column from string to date and set it as an index for pandas to treat it as a date.

Calculated the length of each play in the dataset using as per the number of Lines in each play

Created a subset of 4 longest plays

Classification:
K-means, Wordcloud and network analysis

Performed principle component analysis and retained all the features of the datasets into 2 columns- x and y which contained almost 90 % of the features of the entire dataset. Divided the data set into three clusters as per their categories.

Created a Word cloud of the words given in the column 'Playerline' and noted that words such as 'will', 'lord', 'come', 'thy', 'good', 'thee' were frequently used.

Performed network analysis on the dataset and plotted a network diagram with plays and the players in it to analyse the plays with maximum number of connections.

Observations

There are 36 unique plays. Hamlet is the longest play with 4244 lines and A comedy of errors is the shortest with 2055 lines.

Using the analysis noted that 'Hamlet' is the longest play with 4244 lines and 'A Comedy of Errors' is the smallest play 2055 lines
Plotted the plays as per their lengths in ascending order using scatter plot

Shakesphere plays are divided into three categories- History, Tragedy and Comedy
On analysing samples of plays belonging to each of these three categories:
1. Noted that plays falling into the category 'comedy' are the shortest with an average of about 2700 lines per play
2. Historical plays have an average length of about '3200' lines
3. Plays falling into the category of 'Tragedy' have an average length of '3300' lines per play and hence are the longest plays

The play with highest degree of centrality is Richar III which implies it has the maximum number of connections.
'Twelfth Night' has the least degree of centrality and hence has the least connections.
The plays in this dataset are divided into three categories- History, Tragedy and Comedy
Words such as 'will', 'lord', 'come', 'thy', 'good', 'thee' are frequently used in the plays

References:
https://folgerpedia.folger.edu/William_Shakespeare%27s_plays#:~:text=Shakespeare's%20plays%20are%20traditionally%20divided,comedies%2C%20histories%2C%20and%20tragedies.
https://matplotlib.org/tutorials/introductory/pyplot.html
https://verbingnouns.github.io/AdventuresInR/docs/shakespeare.nb.html
