# SQLhomewprk1
--
select * from film
WHERE  (length > 60 AND  length <75) AND (rental_rate = 0.99 ) AND (replacement_cost = 12.99 OR replacement_cost = 28.99 ) ;
--
SELECT * FROM customer
WHERE first_name = 'Mary';
--
SELECT * FROM film 
WHERE  length <=50 AND rental_rate <> 2.99 OR rental_rate <> 4.99;
