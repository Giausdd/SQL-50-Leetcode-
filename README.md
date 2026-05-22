# Write your MySQL query statement below

select p.firstName, p.lastName,A.city ,A.state 

from person AS p 

left join Address AS A 

on p.personID =A.personID 
