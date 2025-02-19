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

RESULTS


![image](https://user-images.githubusercontent.com/111562184/203306762-49ff1a5f-5284-43bb-945b-5af4e4cc996c.png)
   English is the most used language.

![image](https://user-images.githubusercontent.com/111562184/203307220-c1f9b17a-2425-406a-b33d-204023208c18.png)
Documentaries is the most desired Genre.

![image](https://user-images.githubusercontent.com/111562184/203307484-d14516b8-bbac-48ee-99a6-efd7ab878af3.png)
          Foreign profits far exceed domestic profits in relation to production cost.

![image](https://user-images.githubusercontent.com/111562184/203307869-c9bcb7d2-2f1b-4443-84c6-e499877188ed.png)
             There are some months called "dump months" during which movies don't do well when released in those months.


CONCLUSIONS

1. The English Language is by far the most dominant language.
2. The months of January to April and September to October are considered dump months where movies don't do well.
3. Documentary, Action, Fantasy and Comedy have been the best genres.
4. The international market brings in more money than the domestic market.

RECOMMENDATIONS

1. Produce more movies and films that cater to the International market than the domestic one.
2. Invest more finances on Documentary, Action and Comedy films.
3. Avoid releasing movies during the dump months but rather focus on the holiday months for example December.
4. Produce a lot of English speaking movies but at the same time allow a suitable budget for the other languages

Files in This Repository:


1. README.md - this file
2. student.ipynb - A Jupiter Notebook representing the technical calculations for the project.
3. data_cleaning.ipynb - A Jupyter Notebook documenting the cleaning techniques used in this exercise.
4. Presentation Slides.pdf - A presentation of findings.
5. ZippedData - A zipped collection of the data used in the study.







