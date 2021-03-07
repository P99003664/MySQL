# Question:
### Write the query to display the moviename, heroname and productionname acted in the producer name= ’Subaskaram’.
# Query:
### select m.Moviename,m.Heroname_cast1,p.Productionname from productions p inner join movie m on p.Productionid =m.Productionid and p.Ownername="Subaskaram";
![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq4.png)<br />
