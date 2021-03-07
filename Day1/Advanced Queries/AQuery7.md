# Question:
### Write the query to display the productionname, ownername who has not produced the ‘hindi’ movie.
# Query:
### select p.Productionname,p.Ownername from productions p left join movie m on m.Productionid=p.Productionid where m.Language="Hindi" where m.Language is null;
![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq7.png)<br />
