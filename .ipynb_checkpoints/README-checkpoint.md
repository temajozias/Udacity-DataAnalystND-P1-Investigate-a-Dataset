# Udacity-DataAnalystND-P1-Investigate-a-Dataset

# Project: Investigate a Dataset - TMDb movie data
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Conclusions

- there has been an increasing films budgets in the early 2000's

- There were great revenues in `1967` and `1977`. But the revenues are stable and greatly high overall time.

- We can surely say that the film industry is a paying industry. The minimum mean gain overall time is around `40 000 000 $`.

- We can say that the total year film gain evolution over the years is greatly increasing. Year `2014` is the year of biggest gain overall time, and year `2015` comes closer.

- The most successfull years are the `1975 - 1980`

- There is a greatly increasing gain in films over the years.

- The mean film gain is around `0.5 * 1e8 $` overall time

- The most popular genre overall time is `Drama` followed by `Comedy`, `Thriller` and `Action`.

- Looks like overall time, films used to have 5 principal actors in thier cast.

- The mean film runtime overall time is `106 min` and  film runtime is between `103 min` and `109 min`.

- There are some unrealistic values within our dataset in the `runtime` column, regarding the maximum film runtime over the years.

- The most popular actor overall time is `Robert De Niro` followed by `Samuel L. Jackson`.

- The most popular production company overall time is `Universal Pictures` followed by `Warner Bros.` and `Paramount Pictures`.

- The most film's director overall time is `Woody Allen` followed by `Clint Eastwood` and `Steven Spielberg`.

- The best months to release a movie are `December` and `June`

- Most films mix about 2 or 3 differents genres.

- The most successful film director overall time is `Steven Spielberg` followed by `James Cameron` and `George Lucas`.

- The most successful film's genre is `Comedy` followed by `Drama`, `Comedy|Romance` and `Comedy|Drama|Romance`.

- The most rated film's genre is `Drama` followed by `Comedy`, `Drama|Romance` and `Comedy|Drama`.

- The most successfull production company overall time is `Paramount Pictures` followed by `Universal Pictures`.


## Limitations ecountered:

- There are multiple rows with crucial missing values that led to removal, leading to information loss

- We choosed to fill the zeros values by the corresponding mean to avoid information loss