1. **film** tablosunda film uzunluğu **length** sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```
SELECT COUNT(*) FROM film WHERE length &gt; (SELECT AVG(length) FROM film);
```
2. **film** tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```
SELECT COUNT(*) FROM film WHERE rental_rate = (SELECT MAX(rental_rate) FROM film);
```
3. **film** tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
```
SELECT * FROM film WHERE (rental_rate = (SELECT MIN(rental_rate) FROM film) AND replacment_cost = (SELECT MIN(rental_rate) FROM film));
```
4. **payment** tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```
SELECT customer FROM payment WHERE amount = (SELECT MAX(amount) from payment);
```
---