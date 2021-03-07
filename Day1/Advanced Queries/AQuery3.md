# Question:
### Write the query to display production name, owner name have produced maximum movies
# Query:
### select p.Productionname,p.Ownername from productions p inner join movie m on m.productionid=p.Productionid group by productionname order by count(*) desc limit 1;
