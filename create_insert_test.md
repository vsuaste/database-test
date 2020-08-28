### postgres
```
CREATE TABLE dogs( id integer PRIMARY KEY, name varchar, personids json );
insert into dogs(id, name, arrayids) values (1, 'toto', '[3,4,5]' );
insert into dogs(id, name, arrayids) values (2, 'toto2', '[1,2,5]' );
```

### mysql
```
CREATE TABLE dogs( id INTEGER PRIMARY KEY, name VARCHAR(50), personids JSON );
insert into dogs (id, name, personids) values (1, 'toto', '[3,4,5]');
insert into dogs (id, name, personids) values (2, 'toto2', '[1,2,5]');
```

### mariadb
```
CREATE TABLE dogs( id INTEGER PRIMARY KEY, name VARCHAR(50), personids JSON );
insert into dogs (id, name, personids) values (1, 'toto', '[3,4,5]');
insert into dogs (id, name, personids) values (2, 'toto2', '[1,2,5]');
```

### sqlite
```
create table dogs( id INTEGER PRIMAR KEY, name TEXT, personids TEXT);
insert into dogs (id, name, personids) values (1, 'toto', '[3,4,5]');
insert into dogs (id, name, personids) values (2, 'toto2', '[1,2,5]');
```

