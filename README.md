# SQLOdev8
SQLÖDEVİ8

--test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE <employee> (
id INTEGER PRIMARY KEY,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100) );


--Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
insert into MOCK_DATA (id, first_name, email, birthday) values (1, 'Claresta Ivshin', 'civshin0@statcounter.com', '1999-09-17');
insert into MOCK_DATA (id, first_name, email, birthday) values (2, 'Markos Boxhill', 'mboxhill1@bloomberg.com', '1959-08-25');
insert into MOCK_DATA (id, first_name, email, birthday) values (3, 'Basia Wetheril', 'bwetheril2@google.com', '1939-09-02');
insert into MOCK_DATA (id, first_name, email, birthday) values (4, 'Andee Sheeres', 'asheeres3@dailymotion.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (5, 'Celestine Redsull', 'credsull4@github.com', '1940-01-29');
insert into MOCK_DATA (id, first_name, email, birthday) values (6, 'Bobbi Fehners', 'bfehners5@meetup.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (7, 'Abbot Johanchon', 'ajohanchon6@free.fr', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (8, 'Maison Littleproud', 'mlittleproud7@quantcast.com', '1929-08-17');
insert into MOCK_DATA (id, first_name, email, birthday) values (9, 'Thibaud Remmers', 'tremmers8@51.la', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (10, 'Farand Mobbs', 'fmobbs9@delicious.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (11, 'Huntington Venard', 'hvenarda@samsung.com', '1940-04-18');
insert into MOCK_DATA (id, first_name, email, birthday) values (12, 'Betty McPhillips', 'bmcphillipsb@xinhuanet.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (13, 'Jacquenette Maestrini', 'jmaestrinic@free.fr', '1922-12-26');
insert into MOCK_DATA (id, first_name, email, birthday) values (14, 'Catha Oven', 'covend@prweb.com', '1921-10-18');
insert into MOCK_DATA (id, first_name, email, birthday) values (15, 'Giorgio Hoult', 'ghoulte@jugem.jp', '1951-09-23');
insert into MOCK_DATA (id, first_name, email, birthday) values (16, 'Balduin Fabler', 'bfablerf@huffingtonpost.com', '1975-02-06');
insert into MOCK_DATA (id, first_name, email, birthday) values (17, 'Raye Kanter', 'rkanterg@shareasale.com', '1936-04-25');
insert into MOCK_DATA (id, first_name, email, birthday) values (18, 'Sutton Paget', 'spageth@homestead.com', '1941-02-19');
insert into MOCK_DATA (id, first_name, email, birthday) values (19, 'Magdalena Exon', 'mexoni@spotify.com', '1912-06-30');
insert into MOCK_DATA (id, first_name, email, birthday) values (20, 'Simona Walczak', null, '1967-06-09');
insert into MOCK_DATA (id, first_name, email, birthday) values (21, 'Wells Bladge', 'wbladgek@blinklist.com', '1947-09-30');
insert into MOCK_DATA (id, first_name, email, birthday) values (22, 'Luke Grzelak', 'lgrzelakl@msu.edu', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (23, 'Huntlee Messom', 'hmessomm@storify.com', '1968-12-27');
insert into MOCK_DATA (id, first_name, email, birthday) values (24, 'Maure Quantick', 'mquantickn@freewebs.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (25, 'Mendie Feare', 'mfeareo@themeforest.net', '1908-06-09');
insert into MOCK_DATA (id, first_name, email, birthday) values (26, 'Eduardo Pidler', null, '1974-10-05');
insert into MOCK_DATA (id, first_name, email, birthday) values (27, 'Jamison Kemwall', 'jkemwallq@squarespace.com', '1962-11-24');
insert into MOCK_DATA (id, first_name, email, birthday) values (28, 'Alicea Danser', 'adanserr@bloomberg.com', '1903-11-12');
insert into MOCK_DATA (id, first_name, email, birthday) values (29, 'Ernest Urpeth', 'eurpeths@mapy.cz', '1971-08-28');
insert into MOCK_DATA (id, first_name, email, birthday) values (30, 'Gerard Peirson', 'gpeirsont@sfgate.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (31, 'Karena Giller', 'kgilleru@t.co', '1949-02-25');
insert into MOCK_DATA (id, first_name, email, birthday) values (32, 'Pooh Chatel', 'pchatelv@php.net', '1946-09-03');
insert into MOCK_DATA (id, first_name, email, birthday) values (33, 'Loree Dudson', 'ldudsonw@google.ru', '1985-10-25');
insert into MOCK_DATA (id, first_name, email, birthday) values (34, 'Kessiah Sabatier', 'ksabatierx@ask.com', '1912-02-14');
insert into MOCK_DATA (id, first_name, email, birthday) values (35, 'Blinny Kennifeck', 'bkennifecky@army.mil', '1979-07-31');
insert into MOCK_DATA (id, first_name, email, birthday) values (36, 'David Norgan', 'dnorganz@last.fm', '1910-12-08');
insert into MOCK_DATA (id, first_name, email, birthday) values (37, 'Mei Smeeton', 'msmeeton10@wikispaces.com', '1925-06-17');
insert into MOCK_DATA (id, first_name, email, birthday) values (38, 'Cherise Brinson', 'cbrinson11@flickr.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (39, 'Genna Lambertini', 'glambertini12@examiner.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (40, 'Bobine Redmond', 'bredmond13@ebay.com', '1911-08-11');
insert into MOCK_DATA (id, first_name, email, birthday) values (41, 'June Kensington', 'jkensington14@ted.com', '1994-01-27');
insert into MOCK_DATA (id, first_name, email, birthday) values (42, 'Carrie Trivett', 'ctrivett15@ox.ac.uk', '1919-12-15');
insert into MOCK_DATA (id, first_name, email, birthday) values (43, 'Leontine Pimer', 'lpimer16@goo.gl', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (44, 'Alfi Dewett', 'adewett17@pagesperso-orange.fr', '1940-02-12');
insert into MOCK_DATA (id, first_name, email, birthday) values (45, 'Kaycee Crang', 'kcrang18@mashable.com', '1930-04-15');
insert into MOCK_DATA (id, first_name, email, birthday) values (46, 'Davidson Hing', null, '1922-06-10');
insert into MOCK_DATA (id, first_name, email, birthday) values (47, 'Lynne Hise', 'lhise1a@slate.com', '1983-04-28');
insert into MOCK_DATA (id, first_name, email, birthday) values (48, 'Benedicta Hatchette', 'bhatchette1b@example.com', null);
insert into MOCK_DATA (id, first_name, email, birthday) values (49, 'Arlana Boman', 'aboman1c@prweb.com', '1953-01-25');
insert into MOCK_DATA (id, first_name, email, birthday) values (50, 'Antin Challis', 'achallis1d@weibo.com', '1909-07-05');

--Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
SET name= 'Duygu',
WHERE id= 5;
--------------------
UPDATE employee
SET birthday= '1996-09-15',
WHERE birthday= NULL;
---------------------
UPDATE employee
SET email= 'xracex@example.com',
WHERE name= 'Alfi';
---------------------
UPDATE employee
SET birthday= '1995-02-01',
WHERE id= 41;
---------------------
UPDATE employee
SET email 'sadecesql@ted.com',
WHERE birthday= '1947-09-30';

--Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE id= 7;
-----------------
DELETE FROM employee
WHERE name= 'Alfi';
-----------------
DELETE FROM employee
WHERE email= NULL;
-----------------
DELETE FROM employee
WHERE birthday IN (1940-01-01,1990-05-15);
-----------------
DELETE FROM employee
WHERE name = 'J%';
-----------------
