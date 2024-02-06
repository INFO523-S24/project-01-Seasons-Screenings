# Data
-   **[holiday_movies.csv]**: The *Holiday Movies* dataset is a collection that focuses on movies with themes or titles related to various holidays. It spans various genres, years, and holiday themes, looking at how holiday movies have evolved over time and how audiences have received them. This dataset looks at popularity, genre distribution, and temporal trends.

# Codebook for [holiday_movies.csv] Dataset

## Variable Names and Descriptions:

-   **tconst**:  Alphanumeric unique identifier of the title
-   **title_type**:  The type/format of the title (movie, video, or tvMovie)
-   **primary_title**:  The more popular title / the title used by the filmmakers on promotional materials at the point of release
-   **original_title**:  Original title, in the original language
-   **year**:  The release year of a title
-   **runtime_minutes**:  Primary runtime of the title, in minutes
-   **genres**:  Includes up to three genres associated with the title (comma-delimited)
-   **simple_title**:  The title in lowercase, with punctuation removed, for easier filtering and grouping
-   **average_rating**:  Weighted average of all the individual user ratings on IMDb
-   **num_votes**:  Number of votes the title has received on IMDb (titles with fewer than 10 votes were not included in this dataset)
-   **christmas**:  Whether the title includes "christmas", "xmas", "x mas", etc
-   **hanukkah**:  Whether the title includes "hanukkah", "chanukah", etc
-   **kwanzaa**:  Whether the title includes "kwanzaa"
-   **holiday**:  Whether the title includes the word "holiday"


## Data Types:

-   **tconst**:  string
-   **title_type**: categorical
-   **primary_title**: strin
-   **original_title**: string
-   **year**:  numerical
-   **runtime_minutes**:  numerical
-   **genres**:  categorical
-   **simple_title**: string
-   **average_rating**: numerical
-   **num_votes**:  numerical
-   **christmas**:  boolean 
-   **hanukkah**:  boolean
-   **kwanzaa**:  boolean
-   **holiday**:  boolean
