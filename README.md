# sql_odev5
<br></br><b> Soru 1 </b> 
<code> SELECT * FROM film
WHERE title LIKE ('%n')
ORDER BY length DESC
LIMIT 5;</code>
<br></br><b> Soru 2 </b> 
<code> SELECT * FROM film
WHERE title LIKE ('%n')
ORDER BY length
OFFSET 5
LIMIT 5;</code>
<br></br><b> Soru 3 </b> 
<code> SELECT * FROM customer 
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4;</code>
