# AtomSkills 2020. IT Solution for business

**Участник:** Каменкцкий Александр Сергеевич

windows 10 pro

nw.js     v0.47.1
Node      v14.6.0
Chromium  84.0.4147.89

postgresql-12.3-2-windows-x64
пароль
pGs12D3t2wX64

Installation Directory:                     C:\Program Files\PostgreSQL\12
Server Installation Directory:              C:\Program Files\PostgreSQL\12
Data Directory:                             F:\PostgreSQL\12\data
Database Port:                              5432
Database Superuser:                         postgres
Operating System Account:                   NT AUTHORITY\NetworkService
Database Service:                           postgresql-x64-12
Command Line Tools Installation Directory:  C:\Program Files\PostgreSQL\12
pgAdmin4 Installation Directory:            C:\Program Files\PostgreSQL\12\pgAdmin 4
Stack Builder Installation Directory:       C:\Program Files\PostgreSQL\12
select version() "PostgreSQL 12.3, compiled by Visual C++ build 1914, 64-bit"

CREATE DATABASE "kas_DRON_TAXI"
    WITH 
    OWNER = postgres
    ENCODING = 'UTF8'
    LC_COLLATE = 'Russian_Russia.1251'
    LC_CTYPE = 'Russian_Russia.1251'
    TABLESPACE = pg_default
    CONNECTION LIMIT = -1;

INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Фамилия', 'Имя', 'Отчество', '1999-01-08', false, 'email@mail.ru', '9 999-999-9999', 'Password', 'c:\Users\Default\Desktop\');
INSERT INTO users (Surname, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Фамилия', 'Отчество', '1999-01-08', false, 'email@mail.ru', '9 999-999-9999', 'Password', 'c:\Users\Default\Desktop\');

INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Фамилия', 'Имя', 'Отчество', '1999-01-08', false, 'email1@mail.ru', '9 999-999-1111', 'Password1', 'c:\Users\Default1\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Каменецкий', 'Александр', 'Сергеевич', '1988-09-04', false, 'email2@mail.ru', '9 999-999-1112', 'Password2', 'c:\Users\Default2\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Иванова', 'Инна', 'Ивановна', '1985-05-20', true, 'email3@mail.ru', '9 999-999-1113', 'Password3', 'c:\Users\Default3\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Петров', 'Петр', 'Петрович', '2000-01-02', false, 'email4@mail.ru', '9 999-999-1114', 'Password4', 'c:\Users\Default4\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Сидорова', 'Ольга', 'Алексеевна', '1973-05-09', true, 'email5@mail.ru', '9 999-999-1115', 'Password5', 'c:\Users\Default5\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Кузнецова', 'Дарья', 'Владимировна', '1991-03-19', true, 'email6@mail.ru', '9 999-999-1116', 'Password6', 'c:\Users\Default6\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Довгань', 'Константин', 'Игоревич', '1995-06-29', false, 'email7@mail.ru', '9 999-999-1117', 'Password7', 'c:\Users\Default7\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Козлова', 'Анна', 'Витальевна', '1968-08-17', true, 'email8@mail.ru', '9 999-999-1118', 'Password8', 'c:\Users\Default8\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Орлов', 'Сергей', 'Федорович', '1983-11-03', false, 'email9@mail.ru', '9 999-999-1119', 'Password9', 'c:\Users\Default9\Desktop\');
INSERT INTO users (Surname, Name, MiddleName, Birthday, Sex, Email, Phone, Password, Path) VALUES ('Власова', 'Юлия', 'Геннадьевна', '1994-12-15', true, 'email10@mail.ru', '9 999-999-1120', 'Password10', 'c:\Users\Default10\Desktop\');
