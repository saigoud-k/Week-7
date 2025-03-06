


First we have to install this libraries

# !pip install praw matplotlib wordcloud textblob pandas
# !conda install -c conda-forge nltk -y


We use praw (Python Reddit API Wrapper) to fetch posts in the r/Gemini subreddit.
Fetches the primary information like title, author, score, comment number, and text content.
Data Storage

Than Stores the fetched data into an SQLite3 database.
Stores data in a table named "posts".
Exploratory Data Analysis (EDA)

Histograms: Plots the distribution of scores.

Boxplots: Plots the spread of comments with a logarithmic scale.

Scatter Plot: Analyzes correlation between number of comments and score.

Bar Charts: Presents most common Reddit authors by frequency of posts.

Word Frequency Analysis: Uses nltk to determine most common words used in post titles.

Stopword Removal & Cleaning: Eliminates common English words to constrain word frequency results.

Results & Insights

Posts that have a high score garner more engagement.
Some writers publish more frequently.
Common words that are used within the titles refer to popular threads on the subreddit.