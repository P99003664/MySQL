# Question:
### Write the query to display the production name, owner name who has produced movie for more languages.
# Query:
### select Distinct p.Productionname,p.Ownername ,count(p.Productionname) as count from  movie m right join productions p ON  m.productionid =p.productionid  group by(m.Language) order by(count) desc limit 1;
![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq10.png)<br />
