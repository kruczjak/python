SQL

EXERCISE: Write a query that returns The year, month, day, speciesID and weight in mg
`SELECT day,month,year,record_id,wgt*1000 FROM surveys;`

-----------

EXERCISE: Write a query that returns The year, month, day, speciesID and weight in mg (ciekawe co to to speciesID, możliwe że trzeba będzie poprawić)
`SELECT day,month,year,record_id,wgt FROM surveys where plot=1 and wgt>75`

------------

Exercise: Write a query that returns year, species, and weight in kg from the surveys table, sorted with the largest weights at the top

`SELECT day,month,year,record_id,wgt/1000 FROM surveys order by wgt DESC;`

--------------

Exercise: Let's try to combine what we've learned so far in a single query. Using the surveys table write a query to display the three date fields, species ID, and weight in kilograms (rounded to two decimal places), for rodents captured in 1999, ordered alphabetically by the species ID.

`SELECT month,day,year,record_id,ROUND(wgt/1000.0,2) from surveys where year=1999 order by record_id`

