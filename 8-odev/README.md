# Soru 1

### **test** veritabanınızda **employee** isimli sütun bilgileri **id**(INTEGER), **name** VARCHAR(50), **birthday** DATE, **email** VARCHAR(100) olan bir tablo oluşturalım.

## Cevap :
```sql
CREATE TABLE employee (
  id SERIAL PRIMARY KEY,
  name VARCHAR(80),
  birthday DATE,
  email VARCHAR(100)
);
```

# Soru 2

### Oluşturduğumuz **employee** tablosuna '**Mockaroo**' servisini kullanarak 50 adet veri ekleyelim.

## Cevap :
```sql
insert into employee (id, name, email, birthday) values (1, 'Frederic Darrel', 'fdarrel0@1688.com', '12/1/2021');
insert into employee (id, name, email, birthday) values (2, 'Kaila Feehan', 'kfeehan1@geocities.com', '5/31/2021');
insert into employee (id, name, email, birthday) values (3, 'Lazar McGlynn', 'lmcglynn2@dyndns.org', '2/4/2022');
insert into employee (id, name, email, birthday) values (4, 'Merv Donneely', 'mdonneely3@state.tx.us', '1/20/2022');
insert into employee (id, name, email, birthday) values (5, 'Brenden Strippel', 'bstrippel4@livejournal.com', '5/25/2021');
insert into employee (id, name, email, birthday) values (6, 'Don Matisoff', 'dmatisoff5@privacy.gov.au', '12/6/2021');
insert into employee (id, name, email, birthday) values (7, 'Liam Lugard', 'llugard6@state.tx.us', '6/24/2021');
insert into employee (id, name, email, birthday) values (8, 'Jordon Cicchitello', 'jcicchitello7@stumbleupon.com', '4/11/2022');
insert into employee (id, name, email, birthday) values (9, 'Idette Cogdon', 'icogdon8@ehow.com', '1/4/2022');
insert into employee (id, name, email, birthday) values (10, 'Bette Puddan', 'bpuddan9@patch.com', '1/23/2022');
insert into employee (id, name, email, birthday) values (11, 'Lonnie Farryann', 'lfarryanna@reddit.com', '12/20/2021');
insert into employee (id, name, email, birthday) values (12, 'Carlene Carnew', 'ccarnewb@studiopress.com', '5/21/2021');
insert into employee (id, name, email, birthday) values (13, 'Nahum Joinsey', 'njoinseyc@time.com', '9/13/2021');
insert into employee (id, name, email, birthday) values (14, 'Portie Miskimmon', 'pmiskimmond@last.fm', '9/10/2021');
insert into employee (id, name, email, birthday) values (15, 'Jerri Bostick', 'jbosticke@nps.gov', '8/28/2021');
insert into employee (id, name, email, birthday) values (16, 'Tyson Edgell', 'tedgellf@blogtalkradio.com', '9/22/2021');
insert into employee (id, name, email, birthday) values (17, 'Nissy Justis', 'njustisg@shinystat.com', '11/2/2021');
insert into employee (id, name, email, birthday) values (18, 'Kellby Malcolmson', 'kmalcolmsonh@globo.com', '10/16/2021');
insert into employee (id, name, email, birthday) values (19, 'Humbert Cicullo', 'hciculloi@google.com.br', '9/26/2021');
insert into employee (id, name, email, birthday) values (20, 'Inna Zold', 'izoldj@archive.org', '10/13/2021');
insert into employee (id, name, email, birthday) values (21, 'Mylo Whittier', 'mwhittierk@wufoo.com', '12/28/2021');
insert into employee (id, name, email, birthday) values (22, 'Bald Staveley', 'bstaveleyl@ask.com', '4/3/2022');
insert into employee (id, name, email, birthday) values (23, 'Serge Derricoat', 'sderricoatm@wiley.com', '9/26/2021');
insert into employee (id, name, email, birthday) values (24, 'Efren Skellen', 'eskellenn@yandex.ru', '5/23/2021');
insert into employee (id, name, email, birthday) values (25, 'Joe Quickenden', 'jquickendeno@cdbaby.com', '10/23/2021');
insert into employee (id, name, email, birthday) values (26, 'Gracia La Batie', 'glap@ehow.com', '2/8/2022');
insert into employee (id, name, email, birthday) values (27, 'Darbee Krebs', 'dkrebsq@ustream.tv', '2/22/2022');
insert into employee (id, name, email, birthday) values (28, 'Malachi Lamble', 'mlambler@feedburner.com', '1/7/2022');
insert into employee (id, name, email, birthday) values (29, 'Wallis MacNamee', 'wmacnamees@discovery.com', '10/1/2021');
insert into employee (id, name, email, birthday) values (30, 'Bonny Ravens', 'bravenst@exblog.jp', '6/1/2021');
insert into employee (id, name, email, birthday) values (31, 'Mortie Coyle', 'mcoyleu@domainmarket.com', '7/3/2021');
insert into employee (id, name, email, birthday) values (32, 'Ilyse Guisot', 'iguisotv@ebay.com', '4/30/2022');
insert into employee (id, name, email, birthday) values (33, 'Zora Domenget', 'zdomengetw@google.cn', '3/9/2022');
insert into employee (id, name, email, birthday) values (34, 'Oralle MacVean', 'omacveanx@geocities.jp', '12/21/2021');
insert into employee (id, name, email, birthday) values (35, 'Ernaline Rankling', 'eranklingy@ucla.edu', '9/27/2021');
insert into employee (id, name, email, birthday) values (36, 'Joni Pithie', 'jpithiez@uol.com.br', '10/16/2021');
insert into employee (id, name, email, birthday) values (37, 'Trenna Goddert.sf', 'tgoddertsf10@mysql.com', '10/8/2021');
insert into employee (id, name, email, birthday) values (38, 'Leo Howey', 'lhowey11@ftc.gov', '8/10/2021');
insert into employee (id, name, email, birthday) values (39, 'Odette Hatchette', 'ohatchette12@hubpages.com', '9/15/2021');
insert into employee (id, name, email, birthday) values (40, 'Rivkah Boddam', 'rboddam13@hubpages.com', '7/27/2021');
insert into employee (id, name, email, birthday) values (41, 'Jacques Dregan', 'jdregan14@sciencedirect.com', '5/2/2022');
insert into employee (id, name, email, birthday) values (42, 'Desi Pitsall', 'dpitsall15@xrea.com', '6/2/2021');
insert into employee (id, name, email, birthday) values (43, 'Darla Anselmi', 'danselmi16@google.com.hk', '6/10/2021');
insert into employee (id, name, email, birthday) values (44, 'Selig Newing', 'snewing17@hibu.com', '11/23/2021');
insert into employee (id, name, email, birthday) values (45, 'Manny Rawcliff', 'mrawcliff18@feedburner.com', '1/16/2022');
insert into employee (id, name, email, birthday) values (46, 'Burl Malinson', 'bmalinson19@hud.gov', '10/6/2021');
insert into employee (id, name, email, birthday) values (47, 'Marice Ollin', 'mollin1a@mit.edu', '3/13/2022');
insert into employee (id, name, email, birthday) values (48, 'Fanya Douberday', 'fdouberday1b@myspace.com', '9/23/2021');
insert into employee (id, name, email, birthday) values (49, 'Bond McKelvey', 'bmckelvey1c@vkontakte.ru', '1/6/2022');
insert into employee (id, name, email, birthday) values (50, 'Caddric Waggatt', 'cwaggatt1d@sohu.com', '2/15/2022');
```


# Soru 3

### Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

## Cevap :
```sql
UPDATE employee SET name = 'Ali Veli' WHERE id = 1;
UPDATE employee SET name = 'Muhammed Alparslan' WHERE id = 2;
UPDATE employee SET email = 'aliveli@aliveli.com' WHERE id = 1;
UPDATE employee SET email = 'muhammed@alparslan.com' WHERE id = 2;
UPDATE employee SET birthday = '1029-01-01' WHERE id = 2;
```

# Soru 4

### Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

## Cevap :
```sql
DELETE FROM employee WHERE id = '47';
DELETE FROM employee WHERE id = '3';
DELETE FROM employee WHERE name = 'Wallis MacNamee';
DELETE FROM employee WHERE birthday = '2022-04-03';
DELETE FROM employee WHERE birthday = '2021-10-08';
```