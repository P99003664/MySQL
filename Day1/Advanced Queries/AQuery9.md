# Question:
### Write the query to display the heroname who acted in maximum languages.
# Query
### select distinct Heroname_cast1 ,Language , count(Heroname_cast1) as result from  movie group by(Language) order by (result) desc limit 1   ;
![Alt Text](https://github.com/P99003664/MySQL/blob/main/Day1/AQImages/aq9.png)<br />
