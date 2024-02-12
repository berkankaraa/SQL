1. **test** veritabanınızda **employee** isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee (
	id INT NOT NULL,
	name VARCHAR(50) NOT NULL,
	birthday DATE NOT NULL,
	email VARCHAR(100)
);
```
2. Oluşturduğumuz **employee** tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, email, birthday) values (1, 'Mathe', 'mtritton0@hhs.gov', '1969-08-07');
insert into employee (id, name, email, birthday) values (2, 'Clay', 'ccudmore1@csmonitor.com', '1994-08-15');
insert into employee (id, name, email, birthday) values (3, 'Ewan', 'earonow2@blogspot.com', '1984-07-01');
insert into employee (id, name, email, birthday) values (4, 'Rudiger', 'rclark3@washingtonpost.com', '1996-09-06');
insert into employee (id, name, email, birthday) values (5, 'Kit', 'kvardie4@networkadvertising.org', '1961-02-06');
insert into employee (id, name, email, birthday) values (6, 'Dominic', 'dpillington5@java.com', '1987-07-02');
insert into employee (id, name, email, birthday) values (7, 'Caz', 'cpearton6@sohu.com', '1969-01-27');
insert into employee (id, name, email, birthday) values (8, 'Rayshell', 'rbratton7@ask.com', '1982-10-09');
insert into employee (id, name, email, birthday) values (9, 'Althea', 'adunford8@soundcloud.com', '1993-04-04');
insert into employee (id, name, email, birthday) values (10, 'Drucie', 'drobert9@4shared.com', '1988-09-29');
insert into employee (id, name, email, birthday) values (11, 'Conney', 'ckubelkaa@is.gd', '1997-04-19');
insert into employee (id, name, email, birthday) values (12, 'Gawen', 'gremnantb@studiopress.com', '1982-05-29');
insert into employee (id, name, email, birthday) values (13, 'Becki', 'browneyc@phoca.cz', '1990-12-18');
insert into employee (id, name, email, birthday) values (14, 'Cecil', 'ckenwelld@weather.com', '1981-07-12');
insert into employee (id, name, email, birthday) values (15, 'Rodolph', 'rbuttene@ebay.com', '1970-04-24');
insert into employee (id, name, email, birthday) values (16, 'Ashla', 'acounsellf@vimeo.com', '1961-04-10');
insert into employee (id, name, email, birthday) values (17, 'Davis', 'dstenningg@amazon.de', '1974-08-16');
insert into employee (id, name, email, birthday) values (18, 'Carmen', 'cocrottyh@plala.or.jp', '1988-05-31');
insert into employee (id, name, email, birthday) values (19, 'Carey', 'cmccutcheoni@berkeley.edu', '1980-12-16');
insert into employee (id, name, email, birthday) values (20, 'Vinny', 'vburkmanj@seattletimes.com', '1974-07-31');
insert into employee (id, name, email, birthday) values (21, 'Mehmet', 'ikincimehmet@fetih', '1453-05-29');
insert into employee (id, name, email, birthday) values (22, 'Tedi', 'tdavisl@hao123.com', '1971-08-28');
insert into employee (id, name, email, birthday) values (23, 'Adam', 'edurmanm@latimes.com', '1965-04-21');
insert into employee (id, name, email, birthday) values (24, 'Kylen', 'khubbinsn@nasa.gov', '1996-03-11');
insert into employee (id, name, email, birthday) values (25, 'Red', 'rdeavino@edublogs.org', '1989-10-12');
insert into employee (id, name, email, birthday) values (26, 'Corby', 'ccreiganp@freewebs.com', '1985-11-30');
insert into employee (id, name, email, birthday) values (27, 'Lilas', 'lpiddletownq@sfgate.com', '1981-02-01');
insert into employee (id, name, email, birthday) values (28, 'Lani', 'lyearbyr@forbes.com', '1984-11-10');
insert into employee (id, name, email, birthday) values (29, 'Brandise', 'blillgards@phoca.cz', '1975-08-31');
insert into employee (id, name, email, birthday) values (30, 'Delores', 'dhartigant@go.com', '1987-04-29');
insert into employee (id, name, email, birthday) values (31, 'Tildi', 'tambrogiou@google.es', '1966-05-31');
insert into employee (id, name, email, birthday) values (32, 'Joseph', 'estartev@census.gov', '2002-08-26');
insert into employee (id, name, email, birthday) values (33, 'Messi', 'messi@europa.eu', '1985-03-12');
insert into employee (id, name, email, birthday) values (34, 'Marco', 'mcowinsx@businesswire.com', '1979-12-19');
insert into employee (id, name, email, birthday) values (35, 'Kelly', 'kgurradoy@amazon.com', '1988-01-19');
insert into employee (id, name, email, birthday) values (36, 'Kipp', 'kcohanez@senate.gov', '1971-12-14');
insert into employee (id, name, email, birthday) values (37, 'Lucius', 'lchatband10@yellowbook.com', '1981-08-29');
insert into employee (id, name, email, birthday) values (38, 'Sara', 'smillgate11@arstechnica.com', '1962-09-23');
insert into employee (id, name, email, birthday) values (39, 'Berkly', 'bgendricke12@desdev.cn', '1981-07-17');
insert into employee (id, name, email, birthday) values (40, 'Corny', 'cbeney13@a8.net', '1977-11-22');
insert into employee (id, name, email, birthday) values (41, 'Agnola', 'aquantrill14@independent.co.uk', '1970-05-25');
insert into employee (id, name, email, birthday) values (42, 'Wren', 'wcasillas15@issuu.com', '1989-03-12');
insert into employee (id, name, email, birthday) values (43, 'Nisse', 'npaler16@rakuten.co.jp', '1986-09-02');
insert into employee (id, name, email, birthday) values (44, 'Myrtle', 'mfranzke17@edublogs.org', '1999-01-22');
insert into employee (id, name, email, birthday) values (45, 'Winthrop', 'wranderson18@livejournal.com', '1967-12-21');
insert into employee (id, name, email, birthday) values (46, 'Nessi', 'nsynke19@domainmarket.com', '1980-08-15');
insert into employee (id, name, email, birthday) values (47, 'Jase', 'jorrell1a@marriott.com', '1972-06-03');
insert into employee (id, name, email, birthday) values (48, 'Harmon', 'hmathivet1b@sun.com', '1973-12-10');
insert into employee (id, name, email, birthday) values (49, 'Kenneth', 'kposner1c@indiatimes.com', '1970-02-25');
insert into employee (id, name, email, birthday) values (50, 'Carey', 'cscranney1d@barnesandnoble.com', '1988-07-13');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Fatih Furkan'
birthday = '1999-05-01'
email = 'fatih@furkan.com'
WHERE id = 21;

UPDATE employee
SET name = 'Ronaldo'
birthday = '1988-06-06'
email = 'siuu@uefa.com'
WHERE id = 33;

UPDATE employee
SET email = 'example@com.tr'
WHERE email LIKE '%.gov'
RETURNING *;

UPDATE employee
SET name = 'Yusuf'
WHERE name = 'Joseph'
RETURNING *;

UPDATE employee
SET name = 'Example'
birthday = '2024-02-06'
WHERE id BETWEEN 35 AND 45 ;
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE name ILIKE '%a%a%'	
RETURNING *;

DELETE FROM employee
WHERE id>48;

DELETE FROM employee
WHERE 
	(id>18 AND id<28) OR		
	(email LIKE '%.cz')
RETURNING *;

DELETE FROM employee
WHERE name LIKE 'Ro%

DELETE FROM employee
WHERE id =2;	
