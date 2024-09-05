## PostgreSQL Quickstart
### Installing PostgreSQL
```
sudo apt install postgresql postgresql-contrib
```
### Login
```
psql -h postgresql.default.svc.cluster.local -U postgres -d db_name -p 5432
```

### Create the database if it doesn't already exist
```
CREATE DATABASE database_name;
```
### See Database
```
\l 
```

### Connect to the 'database' database
```
\connect database_name;
```

### List the tables
```
\dt
```
### See table data
```
SELECT * FROM  students;
```
### Access the Postgres prompt
```
psql
```
### To exit out of the PostgreSQL prompt
```
\q
```
### Backing Up a Single Database to a SQL File
```
pg_dump -U [username] -h [host] -p [port] [database_name] > backup.sql

```

### Restoring a Database with psql
```
psql -U [username] -h [host] -p [port] -d [target_database] -f backup.sql
```
### Restoring from a Custom Format with pg_restore
```
Restoring from a Custom Format with pg_restore
```

### More Details 
https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-22-04-quickstart
