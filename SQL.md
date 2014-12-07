SQL

EXERCISE: Write a query that returns The year, month, day, speciesID and weight in mg
`SELECT day,month,year,record_id,wgt*1000 FROM surveys;`

-----------

EXERCISE: Write a query that returns The year, month, day, speciesID and weight in mg
`SELECT day,month,year,record_id,wgt FROM surveys where plot=1 and wgt>75`

------------

Exercise: Write a query that returns year, species, and weight in kg from the surveys table, sorted with the largest weights at the 

`SELECT day,month,year,record_id,wgt FROM surveys order by wgt ASC;`

--------------
