DATA SCIENCE MODULE 1 PROJECT

OVERVIEW

I have assumed the role of a Data Scientist hired by Microsoft. My task is to use the six provided datasets from the various Movie Database
 website found online in order to give them actionable insights on how to go about creating a new movie studio.

I am to explore the types of films doing  the best on  the box office.
My hypothesis will be ;
        ◦ The International market will be more profitable than the domestic.
        ◦ The English language is by far the most available language for movies.
        ◦ There are  consistent times of the month every year which yields lower profits when movies are released on, termed as
	 ‘Dump Months’ and also there is a preferred length of time for movies which the audience can make time.
        ◦ There are genre types which are preferred by the majority of movie watchers. 


The data was collected from Github. There are 6 datasets provided.

DEFINING THE METRIC OF SUCCESS

When I show through visualizations that;
    • There exist the worst months to release films.
    • There are preferred genres.
    • More money is to be made Internationally.

I will select the following tables to work with;
    1. tn.movie_budgets.csv.gz database.
Chosen because it has the production_budget which can be used to create two new columns of domestic_profits and worldwide_profits. 
It also has the release data which can be useful.
    2. tmbd.movies.csv  database.
I selected this datasets because of the original_language, popularity, vote_average and the genres_id columns.

    3. imdb.sql  database.
Chosen because of the movie_ratings and movie basics tables within the sql database.

CONCLUSIONS

1. The English Language is by far the most dominant language.

2. The months of January to April and September to October are considered dump months where movies don't do quite well.

3.Documentary, Action, Fantasy and Comedy have been the best genres.

4. The international market brings in more money than the domestic market.

Files in This Repository
The following files are located in this repository:

README.md - this file

student.ipynb - A Jupiter Notebook representing the technical calculations for the project.

data_cleaning.ipynb - A Jupyter Notebook documenting the cleaning techniques used in this exercise.

Presentation Slides.pdf - A presentation of findings.

ZippedData - A zipped collection of the data used in the study.







