1. **test** veritabanınızda **employee** isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee (
	id INT NOT NULL,
	name VARCHAR(50) NOT NULL,
	birthday DATE NOT NULL,
	email VARCHAR(100));
```
2. Oluşturduğumuz **employee** tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, first_name, email, birthday) values (1, 'Stefa', 'sallwood0@cbc.ca', '3/20/2011');
insert into employee (id, first_name, email, birthday) values (2, 'Sarge', 'sdadswell1@senate.gov', '10/19/2018');
insert into employee (id, first_name, email, birthday) values (3, 'Lianna', 'lvanderbaaren2@unblog.fr', '12/23/1993');
insert into employee (id, first_name, email, birthday) values (4, 'Zola', 'zahrend3@livejournal.com', '3/10/1973');
insert into employee (id, first_name, email, birthday) values (5, 'Katrinka', 'kredpath4@gmpg.org', '8/19/2023');
insert into employee (id, first_name, email, birthday) values (6, 'Cos', 'cbuggy5@wunderground.com', '5/20/1970');
insert into employee (id, first_name, email, birthday) values (7, 'Isabel', 'idebell6@army.mil', '8/13/1966');
insert into employee (id, first_name, email, birthday) values (8, 'Edlin', 'eberka7@discuz.net', '12/20/1980');
insert into employee (id, first_name, email, birthday) values (9, 'Delora', 'dmcaughtrie8@upenn.edu', '6/13/2007');
insert into employee (id, first_name, email, birthday) values (10, 'Barny', 'bchessil9@tripadvisor.com', '11/18/2004');
insert into employee (id, first_name, email, birthday) values (11, 'Leola', 'lteuliera@yale.edu', '10/6/1996');
insert into employee (id, first_name, email, birthday) values (12, 'Rustie', 'rlegatb@noaa.gov', '4/19/1981');
insert into employee (id, first_name, email, birthday) values (13, 'Gregoor', 'gcurtisc@chicagotribune.com', '2/5/1987');
insert into employee (id, first_name, email, birthday) values (14, 'Moreen', 'moruaned@theguardian.com', '11/24/1983');
insert into employee (id, first_name, email, birthday) values (15, 'Deina', 'dcoultone@whitehouse.gov', '4/2/1974');
insert into employee (id, first_name, email, birthday) values (16, 'Rutledge', 'rgandleyf@addthis.com', '2/12/1982');
insert into employee (id, first_name, email, birthday) values (17, 'Farris', 'faldridgeg@slashdot.org', '8/14/2001');
insert into employee (id, first_name, email, birthday) values (18, 'Yelena', 'ygurtonh@mlb.com', '11/15/1982');
insert into employee (id, first_name, email, birthday) values (19, 'Giana', 'gtwinningi@is.gd', '4/23/1976');
insert into employee (id, first_name, email, birthday) values (20, 'Renado', 'rsimmsj@eepurl.com', '4/3/1982');
insert into employee (id, first_name, email, birthday) values (21, 'Ana', 'aelwoodk@fastcompany.com', '7/18/1989');
insert into employee (id, first_name, email, birthday) values (22, 'Rickert', 'rvizorl@amazon.co.uk', '1/6/1986');
insert into employee (id, first_name, email, birthday) values (23, 'Briano', 'bosmintm@archive.org', '1/4/1977');
insert into employee (id, first_name, email, birthday) values (24, 'Benni', 'bsturgesn@histats.com', '10/11/1986');
insert into employee (id, first_name, email, birthday) values (25, 'Rica', 'rhazello@godaddy.com', '8/5/2018');
insert into employee (id, first_name, email, birthday) values (26, 'Alastair', 'adannp@so-net.ne.jp', '5/12/2004');
insert into employee (id, first_name, email, birthday) values (27, 'Woodrow', 'wsibbsonq@nbcnews.com', '7/16/2018');
insert into employee (id, first_name, email, birthday) values (28, 'Hercule', 'hgraberr@vkontakte.ru', '12/26/1961');
insert into employee (id, first_name, email, birthday) values (29, 'Alexina', 'agowerss@mozilla.com', '2/15/2017');
insert into employee (id, first_name, email, birthday) values (30, 'Fiann', 'fwehnerrt@a8.net', '9/6/2017');
insert into employee (id, first_name, email, birthday) values (31, 'Donovan', 'dduckhamu@jugem.jp', '8/31/1988');
insert into employee (id, first_name, email, birthday) values (32, 'Jacinthe', 'jdeakesv@geocities.jp', '7/11/1961');
insert into employee (id, first_name, email, birthday) values (33, 'Louise', 'lwinmanw@unc.edu', '12/18/2007');
insert into employee (id, first_name, email, birthday) values (34, 'Sherri', 'sfincix@google.com.hk', '12/1/1961');
insert into employee (id, first_name, email, birthday) values (35, 'Didi', 'dlangthorny@github.com', '12/3/2012');
insert into employee (id, first_name, email, birthday) values (36, 'Britteny', 'bcasalettoz@dailymail.co.uk', '2/13/1994');
insert into employee (id, first_name, email, birthday) values (37, 'Angus', 'acapstake10@4shared.com', '2/26/1979');
insert into employee (id, first_name, email, birthday) values (38, 'Ber', 'bgaishson11@amazon.co.jp', '12/27/1990');
insert into employee (id, first_name, email, birthday) values (39, 'Tailor', 'tsexty12@netlog.com', '2/19/1966');
insert into employee (id, first_name, email, birthday) values (40, 'Gerrie', 'gdagleas13@baidu.com', '7/22/1964');
insert into employee (id, first_name, email, birthday) values (41, 'Modestine', 'mbreen14@live.com', '1/12/2000');
insert into employee (id, first_name, email, birthday) values (42, 'Horst', 'hkerbey15@t-online.de', '6/12/1977');
insert into employee (id, first_name, email, birthday) values (43, 'Jackie', 'jscholes16@google.ru', '1/1/1968');
insert into employee (id, first_name, email, birthday) values (44, 'Antonia', 'ahawyes17@blogs.com', '11/28/1984');
insert into employee (id, first_name, email, birthday) values (45, 'Heall', 'hbauldrey18@army.mil', '4/10/2018');
insert into employee (id, first_name, email, birthday) values (46, 'Celestia', 'cduberry19@disqus.com', '10/28/2008');
insert into employee (id, first_name, email, birthday) values (47, 'Ingra', 'ireith1a@ucla.edu', '7/6/2017');
insert into employee (id, first_name, email, birthday) values (48, 'Farlee', 'fbowdler1b@narod.ru', '12/8/1986');
insert into employee (id, first_name, email, birthday) values (49, 'Waylin', 'wubsdell1c@nsw.gov.au', '12/11/2000');
insert into employee (id, first_name, email, birthday) values (50, 'Natalina', 'nvasiljevic1d@ted.com', '11/10/2001');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Leo Messi'
birthday = '24/06/1987'
email = 'leo@messi.com'
WHERE id = 21;

UPDATE employee
SET name = 'Ronaldo'
birthday = '1988-06-06'
email = 'cr@ronaldo.com'
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
