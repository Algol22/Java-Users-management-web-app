## In order to run the application the following should be created via PostgresSQL
# DB: Users
# table: users_table


create table users_table
(
id serial not null
constraint users_table_pk
primary key,
name varchar(50),
login varchar(50),
email varchar(40)
);