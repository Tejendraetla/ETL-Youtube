Trending YouTube Videos – ETL Project
Objective
The goal of this project is to design and implement a complete ETL (Extract, Transform, Load) pipeline that processes trending YouTube video data. The dataset is sourced from Kaggle and includes video metadata from the United States and Canada. The cleaned and transformed data is loaded into a PostgreSQL database, enabling analysis to identify the most and least popular video categories based on views, likes, dislikes, and comments.

Data Source
Trending video data was sourced from Kaggle:
[📁 YouTube Trending Videos Dataset](https://www.kaggle.com/datasnaek/youtube-new)

Files used:

CAvideos.csv – Trending videos in Canada

USvideos.csv – Trending videos in the United States

US_category_id.json – Category mapping for video types

Methodology
1. Extraction
Downloaded CSV and JSON files from Kaggle

Read data into Pandas DataFrames using Python in a Jupyter Notebook environment

2. Transformation
Cleaned and standardized the datasets using Pandas

Merged category information with the main datasets

Handled missing values, renamed columns for clarity, and filtered key metrics (e.g., views, likes, comments)

3. Loading
Established a connection to a PostgreSQL relational database

Loaded the cleaned data into structured SQL tables, preparing it for future querying and analysis

Outcome
This project enables deeper insight into video performance trends across categories and regions. The ETL pipeline created serves as a foundation for more advanced analytics, including popularity prediction, sentiment analysis, and dashboard visualization.
