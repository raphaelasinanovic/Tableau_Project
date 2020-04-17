# Tableau_Project

Source: https://www.kaggle.com/brosen255/goodreads-books

web scraped author and book data from the most popular lists on goodreads

20 columns


General question:
What makes for a popular book? Are there common denominators?

Who are the top ...
Which author has the most books in the list?

filter by count of votes

Which are the most popular genres?
Does the page number play a role?
Are classics still popular or modern books?
Are authors from a specific country more popular?-->map



which correlations can be made?

1) checking data for completeness, missing values, inconsistencies etc
2) data cleaning: renaming columns (first row issue), changing string to integers (author-average-rating)
3)inspecting different columns to understand what they mean, reading up on goodbooks.com, especially the metrics are not clear at first
4)thinking in more detail about possible questions and how to visualize
5)percentage



Columns:
author_average_rating: from 1 to 5, sum of all book ratings
author_gender
author_genres
author_id
author_name
author_page_url
author_rating_count: how many users rated in total on any of the books of the author
author_review_count: number of written reviews of users on all books in total
birthplace
book_average_rating: sum of particular book ratings
book_fullurl
book_id
book_title
genre_1
genre_2
num_ratings: per book
num_reviews:per book
pages
publish_date
score: 
