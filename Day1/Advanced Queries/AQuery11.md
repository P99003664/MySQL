# Question:
### Write the query to display the productionname, producername who has not produced any movie.
# Query:
### select p.Ownername ,p.Productionname from  movie as m right join productions as p ON  m.Productionid =p.Productionid where m.Moviename is  null ;
![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq11.png)<br />
