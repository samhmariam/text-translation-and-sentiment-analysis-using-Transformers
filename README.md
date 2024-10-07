# Text Translation and Sentiment Analysis using Transformers

### Project Overview
In this project, we will analyze the sentiment of movie reviews in three different languages - English, French, and Spanish. We have been given 30 movies, 10 in each language, along with their reviews and synopses in separate CSV files named `movie_reviews_eng.csv`, `movie_reviews_fr.csv`, and `movie_reviews_sp.csv`.

The objective of this project is to read data from all the .csv files and create a single pandas dataframe. This dataframe should have the following columns - `Title`, `Year`, `Synopsis`, `Review`, and `Original Language`.

### Project Steps
1. Read data from all the .csv files and create a single pandas dataframe with columns - `Title`, `Year`, `Synopsis`, `Review`, and `Original Language`.
2. Convert the French and Spanish reviews and synopses into English using pre-trained transformers from HuggingFace.
3. Analyze the sentiment of each review using pretrained transformers from HuggingFace and add the results to the dataframe in a new column called `Sentiment`.
4. Save the final dataframe to a CSV file with columns - `Title`, `Year`, `Synopsis`, `Review`, `Sentiment`, and `Original Language`.

### Project Output
The output of the project will be a CSV file with a header row that includes column names such as `Title`, `Year`, `Synopsis`, `Review`, `Sentiment`, and `Original Language`. The `Original Language` column will indicate the language of the review and synopsis (`en`/`fr`/`sp`) before translation. The `Sentiment` column will contain the sentiment of the review (`positive`/`negative`/`neutral`).

### Tools used
- Pandas: for data manipulation and analysis
- HuggingFace Transformers: for natural language processing tasks, such as translation and sentiment analysis

### Skills learned
- Data cleaning and manipulation using Pandas
- Natural language processing techniques, such as translation and sentiment analysis, using HuggingFace Transformers






