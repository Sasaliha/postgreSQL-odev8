# postgreSQL-odev8


/*---1.SORU----------
CREATE TABLE employee (
id INT,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)
---------------2.SORU----------------
insert into employee (name, birthday, email) values ('Humberto', '2015-07-24', 'hpepperell0@unblog.fr');
insert into employee (name, birthday, email) values ('Asia', '1999-04-22', 'aabell1@sina.com.cn');
insert into employee (name, birthday, email) values ('Bernard', '1945-03-20', 'bbouette2@a8.net');
insert into employee (name, birthday, email) values ('Harrie', '1906-02-11', 'hwindle3@imgur.com');
insert into employee (name, birthday, email) values ('Rowland', '1909-01-27', 'rbauckham4@mysql.com');
insert into employee (name, birthday, email) values ('Del', '2011-04-29', 'dgueny5@squarespace.com');
insert into employee (name, birthday, email) values ('Arabela', '1914-12-18', 'aneeds6@drupal.org');
insert into employee (name, birthday, email) values ('Tammara', '1993-06-20', 'tcorkish7@tripadvisor.com');
insert into employee (name, birthday, email) values ('Lynde', '1938-02-16', 'lrupert8@uol.com.br');
insert into employee (name, birthday, email) values ('Andrus', '2019-05-01', 'abingall9@e-recht24.de');
insert into employee (name, birthday, email) values ('Virginia', '1903-11-07', 'vbavestera@accuweather.com');
insert into employee (name, birthday, email) values ('Nicolis', '1991-07-20', 'nswayslandb@theguardian.com');
insert into employee (name, birthday, email) values ('Noemi', '1922-07-12', 'nkaygillc@cocolog-nifty.com');
insert into employee (name, birthday, email) values ('Patric', '1995-08-11', 'pmoscond@house.gov');
insert into employee (name, birthday, email) values ('Vidovic', '1913-01-22', 'vfauguele@springer.com');
insert into employee (name, birthday, email) values ('Svend', '1956-08-08', 'sgunnyf@histats.com');
insert into employee (name, birthday, email) values ('Almira', '1942-12-12', 'amcaviyg@cnn.com');
insert into employee (name, birthday, email) values ('Hedvig', '1950-11-24', 'hblaylockh@amazon.com');
insert into employee (name, birthday, email) values ('Siusan', '1916-07-06', 'shallowesi@fastcompany.com');
insert into employee (name, birthday, email) values ('Isidor', '2015-01-22', 'iriggeyj@vinaora.com');
insert into employee (name, birthday, email) values ('Tedman', '1925-12-18', 'tuppettk@surveymonkey.com');
insert into employee (name, birthday, email) values ('Mikaela', '1903-08-15', 'mrosewelll@ft.com');
insert into employee (name, birthday, email) values ('Delcine', '1987-08-03', 'dstockerm@home.pl');
insert into employee (name, birthday, email) values ('Roddie', '1909-02-11', 'rgruben@dedecms.com');
insert into employee (name, birthday, email) values ('Costanza', '1978-04-11', 'csauvageo@paginegialle.it');
insert into employee (name, birthday, email) values ('Salomone', '2006-11-02', 'sespinosap@wordpress.org');
insert into employee (name, birthday, email) values ('Ike', '1942-04-08', 'iroseq@drupal.org');
insert into employee (name, birthday, email) values ('Ealasaid', '1981-02-02', 'ebrittonerr@google.co.uk');
insert into employee (name, birthday, email) values ('Celle', '1969-09-23', 'cbloxsums@stumbleupon.com');
insert into employee (name, birthday, email) values ('Parke', '1958-04-30', 'ptunnowt@behance.net');
insert into employee (name, birthday, email) values ('Jonell', '1934-05-07', 'jniccolsu@wsj.com');
insert into employee (name, birthday, email) values ('Delaney', '1983-06-16', 'dkruschovv@miitbeian.gov.cn');
insert into employee (name, birthday, email) values ('Lari', '1924-08-30', 'lmccomishw@wsj.com');
insert into employee (name, birthday, email) values ('Renelle', '1924-09-01', 'rakramx@netlog.com');
insert into employee (name, birthday, email) values ('Bessie', '1922-06-23', 'bhullocky@etsy.com');
insert into employee (name, birthday, email) values ('Hartwell', '2008-02-10', 'hwanklinz@domainmarket.com');
insert into employee (name, birthday, email) values ('Lind', '1911-09-13', 'lbunning10@vk.com');
insert into employee (name, birthday, email) values ('Sol', '1904-03-21', 'sflewitt11@nytimes.com');
insert into employee (name, birthday, email) values ('Dniren', '1912-11-29', 'dmandres12@ovh.net');
insert into employee (name, birthday, email) values ('Rick', '1912-11-02', 'rwesthoff13@stanford.edu');
insert into employee (name, birthday, email) values ('Cindy', '1918-12-25', 'chrycek14@webmd.com');
insert into employee (name, birthday, email) values ('Jannelle', '2003-01-09', 'jpadmore15@walmart.com');
insert into employee (name, birthday, email) values ('Carly', '1963-12-27', 'cdobrovolski16@answers.com');
insert into employee (name, birthday, email) values ('Jackquelin', '1962-02-13', 'jchesley17@nyu.edu');
insert into employee (name, birthday, email) values ('Kizzee', '1965-07-22', 'kfirebrace18@youtu.be');
insert into employee (name, birthday, email) values ('Gae', '2003-05-18', 'gkenvin19@google.com.au');
insert into employee (name, birthday, email) values ('Lanie', '1999-04-21', 'lemmanuele1a@tiny.cc');
insert into employee (name, birthday, email) values ('Polly', '1948-12-18', 'pclayborn1b@photobucket.com');
insert into employee (name, birthday, email) values ('Mirabelle', '2018-05-02', 'mhurnell1c@economist.com');
insert into employee (name, birthday, email) values ('Sim', '1975-09-02', 'sbly1d@gnu.org');*/


------------3.SORU---------------------

/*UPDATE employee
SET name='Saliha',
	email='saliha@akjskjd.com'
WHERE id=67;

UPDATE employee
SET birthday='1994-08-02'
WHERE id=67 

UPDATE employee
SET email='hasting@sjkjs.com'
WHERE id=53

UPDATE employee
SET name='Jos'
WHERE id=3;

UPDATE employee
SET birthday='1994-09-08'
WHERE id=30*/

--------------4.soru-----------------------------------------
--DELETE FROM employee WHERE id=3;

--DELETE FROM employee
--WHERE id=30;

--DELETE FROM employee
--WHERE id=27;

--DELETE FROM employee
--WHERE id=85;

--DELETE FROM employee
--WHERE id=41;



