
# Question:
### Write the query to display productionid, production name with total number movies produced by each

# Query:
### select p.Productionid, p.Productionname, count(distinct movie.Moviename) as movie_count from productions p inner join movie m where p.Productionid = m.Productionid group by p.Productionid;</br>

![Alt Text]()<br />
