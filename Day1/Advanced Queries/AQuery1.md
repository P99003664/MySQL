
# Question:
### Write the query to display productionid, production name with total number movies produced by each

# Query:
### select p.Productionid, p.Productionname, count(*) from productions p inner join movie m on p.Productionid = m.Productionid group by p.Productionname;</br>

![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq1.png)<br />
