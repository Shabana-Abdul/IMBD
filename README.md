# IMBD
Dataset containing information about movies which appears on IMDB website.
Data was obtained by means of a web scraping in Python and combined with repository shared by IMDB. Data was preprocessed to include only movies which were released after 1970 and currently have over 50 000 ratings. Additionally there were selected only these movies whose budgets and gross' are denominated in USD to avoid discrepancies.
Dataset contains 3348 observations described by 12 attributes.

Attributes

id - movie's ID used by IMDB repository
primaryTitle - title in English
originalTitle - original title in native language
isAdult - parental guidance
runtimeMinutes - total runtime in minutes
genres - genres
averageRating - final rating, based on all the ratings
numVotes - total number of votes (ratings)
budget - total budget in USD
gross - total gross worldwide in USD
release_date - release date, first occurrence
directors - directors
