1. **city** tablosu ile **country** tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
```
SELECT country, city FROM city LEFT JOIN country ON city.country=country.country;
```
2. **customer** tablosu ile **payment** tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
```
SELECT first_name, last_name FROM customer RIGHT JOIN payment ON customer.payment_id=payment.payment_id;
```
3. **customer** tablosu ile **rental** tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
```
SELECT first_name, last_name FROM customer FULL JOIN rental ON customer.rental_id=rental.rental_id;
```
---