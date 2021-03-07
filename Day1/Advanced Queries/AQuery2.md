# Question:
### Write the query to display production name, owner name have produced more than 2 movies

# Query:
### select p.Productionname, p.Ownername, count(*) from productions p left join movie m on p.Productionid = m.Productionid group by p.Productionname having count(*) > 2;

![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq2.png)<br />
