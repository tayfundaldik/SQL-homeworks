CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
	
);

insert into employee (name, birthday, email) values ('Anstice', '1999-03-03', 'aclement0@wunderground.com');
insert into employee (name, birthday, email) values ('Dimitri', '1983-12-03', 'dmckibbin1@microsoft.com');
insert into employee (name, birthday, email) values ('Ofelia', '1983-03-30', 'ocaldeiro2@apache.org');
insert into employee (name, birthday, email) values ('Myrle', '1963-01-11', 'mmassenhove3@gov.uk');
insert into employee (name, birthday, email) values ('Jessa', '1966-03-14', 'jfern4@dell.com');
insert into employee (name, birthday, email) values ('Elisabet', '1996-07-06', 'ebonde5@ihg.com');
insert into employee (name, birthday, email) values ('Elijah', '1995-02-18', 'eleek6@cloudflare.com');
insert into employee (name, birthday, email) values ('Farley', '1986-08-29', 'falldre7@berkeley.edu');
insert into employee (name, birthday, email) values ('Parke', '1995-07-13', 'pangeau8@deliciousdays.com');
insert into employee (name, birthday, email) values ('Bern', '1969-11-02', 'bsoppett9@dailymotion.com');
insert into employee (name, birthday, email) values ('Bradly', '1980-03-21', 'bwhatsizea@usatoday.com');
insert into employee (name, birthday, email) values ('Adams', '1991-09-26', 'amulrenanb@de.vu');
insert into employee (name, birthday, email) values ('Cassius', '1956-04-04', 'cbrinkmanc@ovh.net');
insert into employee (name, birthday, email) values ('Lauree', '1983-10-30', 'lduffieldd@lulu.com');
insert into employee (name, birthday, email) values ('Jenni', '1991-09-30', 'jarneckee@clickbank.net');
insert into employee (name, birthday, email) values ('Konrad', '1989-01-27', 'kcaserif@weather.com');
insert into employee (name, birthday, email) values ('Damiano', '1999-10-22', 'daclandg@furl.net');
insert into employee (name, birthday, email) values ('Max', '1998-09-10', 'mrosih@squidoo.com');
insert into employee (name, birthday, email) values ('Felicio', '1950-04-05', 'fmaccourti@pen.io');
insert into employee (name, birthday, email) values ('Hammad', '1956-10-27', 'hfrischj@newyorker.com');
insert into employee (name, birthday, email) values ('Charlena', '1999-05-17', 'chartillk@bluehost.com');
insert into employee (name, birthday, email) values ('Maressa', '1971-12-10', 'mpetracchil@indiegogo.com');
insert into employee (name, birthday, email) values ('Gareth', '1974-06-09', 'gdallowaym@pbs.org');
insert into employee (name, birthday, email) values ('Elladine', '1969-09-02', 'ekyngen@instagram.com');
insert into employee (name, birthday, email) values ('Yves', '1971-11-09', 'ydimitriouo@netscape.com');
insert into employee (name, birthday, email) values ('Timmie', '1957-07-19', 'tangeaup@google.com.br');
insert into employee (name, birthday, email) values ('Veronique', '1990-09-13', 'vbreitlerq@java.com');
insert into employee (name, birthday, email) values ('Burke', '1975-06-26', 'bbinleyr@msu.edu');
insert into employee (name, birthday, email) values ('Carlita', '1977-02-28', 'cpressdees@csmonitor.com');
insert into employee (name, birthday, email) values ('Dolores', '1953-12-13', 'dalveyt@springer.com');
insert into employee (name, birthday, email) values ('Galvin', '1978-04-09', 'grulleru@yandex.ru');
insert into employee (name, birthday, email) values ('Lewes', '1971-11-13', 'lrylandv@vimeo.com');
insert into employee (name, birthday, email) values ('Hymie', '1995-08-01', 'hskillenw@narod.ru');
insert into employee (name, birthday, email) values ('Bryon', '1974-04-21', 'bsideyx@bloglovin.com');
insert into employee (name, birthday, email) values ('Barbette', '1984-10-29', 'bskoylesy@dmoz.org');
insert into employee (name, birthday, email) values ('Sebastiano', '1970-05-26', 'stresisez@icq.com');
insert into employee (name, birthday, email) values ('Sarina', '1978-03-24', 'soscanlon10@cdbaby.com');
insert into employee (name, birthday, email) values ('Perl', '1988-04-03', 'pjamison11@fema.gov');
insert into employee (name, birthday, email) values ('Abrahan', '1997-09-26', 'aorbine12@ucsd.edu');
insert into employee (name, birthday, email) values ('Gabbey', '1972-09-12', 'glamping13@wunderground.com');
insert into employee (name, birthday, email) values ('Annalise', '1984-07-07', 'azollner14@weibo.com');
insert into employee (name, birthday, email) values ('Northrup', '1960-05-18', 'ngath15@ezinearticles.com');
insert into employee (name, birthday, email) values ('Riley', '1990-08-14', 'rrosbrough16@delicious.com');
insert into employee (name, birthday, email) values ('Kevan', '1958-08-29', 'kbirds17@accuweather.com');
insert into employee (name, birthday, email) values ('Dacia', '1954-04-01', 'dbrantzen18@businessweek.com');
insert into employee (name, birthday, email) values ('Reeba', '1971-05-15', 'rscoles19@merriam-webster.com');
insert into employee (name, birthday, email) values ('Johanna', '1977-05-04', 'jgibb1a@altervista.org');
insert into employee (name, birthday, email) values ('Sharleen', '1969-06-06', 'sburgoine1b@usa.gov');
insert into employee (name, birthday, email) values ('Joaquin', '1977-08-23', 'jcomrie1c@nydailynews.com');
insert into employee (name, birthday, email) values ('Rebekah', '1964-11-14', 'ratterbury1d@washington.edu');

UPDATE employee
SET name = 'Anastasia'
WHERE id =1;

UPDATE employee
SET name = 'Slaurent'
WHERE id =14;

UPDATE employee
SET name = 'Clement'
WHERE id =32;

UPDATE employee
SET name = 'Christian'
WHERE id =50;

UPDATE employee
SET name = 'Julius'
WHERE id =42;

DELETE FROM employee
WHERE name = 'Kevan';

DELETE FROM employee
WHERE name = 'Sebastiano';

DELETE FROM employee
WHERE name = 'Elisabet';

DELETE FROM employee
WHERE name = 'Galvin';

DELETE FROM employee
WHERE name = 'Myrle';