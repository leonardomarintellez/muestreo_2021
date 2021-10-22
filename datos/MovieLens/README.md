## MOVIELENS

### Social Computing Research at the University of Minnesota

Los datos que utilizaremos se encuentran en el siguiente vínculo

https://drive.google.com/drive/folders/1Z-hIj3yygX3tJQ_lvdVOh_WZFAIvmUIm?usp=sharing

Para mayor detalle sobre los datos visitar:

[MovieLens](https://grouplens.org/datasets/movielens/)
[dataset_100k](https://grouplens.org/datasets/movielens/100k/)


**About MovieLens**


MovieLens

GroupLens Research has collected and made available rating data sets from the MovieLens web site (https://movielens.org). The data sets were collected over various periods of time, depending on the size of the set. Before using these data sets, please review their README files for the usage licenses and other details.

Seeking permission? If you are interested in obtaining permission to use MovieLens datasets, please first read the terms of use that are included in the README file. Then, please fill out this form to request use.  We typically do not permit public redistribution (see Kaggle for an alternative download location if you are concerned about availability).



DETAILED DESCRIPTIONS OF DATA FILES
==============================================

Here are brief descriptions of the data.


u.data     -- The full u data set, 100000 ratings by 943 users on 1682 items.
              Each user has rated at least 20 movies.  Users and items are
              numbered consecutively from 1.  The data is randomly
              ordered. This is a tab separated list of 
	         user id | item id | rating | timestamp. 
              The time stamps are unix seconds since 1/1/1970 UTC   


u.item     -- Information about the items (movies); this is a tab separated
              list of
              movie id | movie title | release date | video release date |
              IMDb URL | unknown | Action | Adventure | Animation |
              Children's | Comedy | Crime | Documentary | Drama | Fantasy |
              Film-Noir | Horror | Musical | Mystery | Romance | Sci-Fi |
              Thriller | War | Western |
              The last 19 fields are the genres, a 1 indicates the movie
              is of that genre, a 0 indicates it is not; movies can be in
              several genres at once.
              The movie ids are the ones used in the u.data data set.

