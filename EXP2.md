# EXPERIMENT 2
# 01 Find the movie with a row id of 6 
QUERY
~~~sql
SELECT * FROM movies WHERE ID=6;
~~~
# 02 Find the movies released in the years between 2000 and 2010
QUERY
~~~sql 
SELECT * FROM movies WHERE YEAR BETWEEN 2000 AND 2010;
~~~
# 03 Find the movies not released in the years between 2000 and 2010
QUERY
~~~sql 
SELECT * FROM movies WHERE YEAR NOT BETWEEN 2000 AND 2010;
~~~
# 04 Find the first 5 Pixar movies and their release year
QUERY
~~~sql
SELECT * FROM movies LIMIT 5;
~~~
