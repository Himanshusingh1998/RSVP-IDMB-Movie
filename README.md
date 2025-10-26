# RSVP-IDMB-Movie

1. Goal of the Project

The goal of this project was to analyze IMDb movie data to help RSVP Movies (a production company) make data-driven decisions — such as identifying top-rated movies, trends in ratings, high-performing production houses, and potential collaboration opportunities based on performance metrics.

2. What Does the Code Do?

The SQL code performs data exploration, cleaning, and analysis on multiple tables (movie, ratings, genre, etc.).
Specifically, it:

Checks for outliers in the ratings table using min and max values.

Identifies the top 10 movies based on average rating using window functions (DENSE_RANK()).

Summarizes movie counts by median ratings to find common rating trends.

Determines which production companies produce the most hit movies (avg rating > 8).

Finds popular genres in the USA during March 2017 with more than 1,000 votes.

Extracts movies starting with "The" and having high ratings (>8).

3. Output Generated

Top 10 movies based on average rating (e.g., FAN expected to appear with 9.6 rating).

Distribution of movies by median rating, showing most movies rated around 7.

Top production companies producing hit movies (e.g., Dream Warrior Pictures, National Theatre Live).

Genre distribution for March 2017 movies (USA) with significant audience engagement (>1,000 votes).

List of high-rated movies starting with “The”, showcasing consistent excellence among specific genres.

4. Key Insights from the Output

The ratings table showed no outliers, indicating clean and reliable data.

Movies with a median rating of 7 are the most common — suggesting average audience satisfaction across most titles.

Dream Warrior Pictures and National Theatre Live emerged as the most consistent producers of high-quality (avg > 8) films, making them strong candidates for RSVP’s collaboration.

Genres such as Drama, Action, and Thriller dominated the U.S. market in March 2017.

Movies starting with “The” and having avg rating > 8 often belong to well-produced, globally appealing genres.
