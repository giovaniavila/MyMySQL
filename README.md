# MyMySQL
### Scripts genéricos para treinar comandos sql



```
create database literatura; 
use literatura; 

create table if not exists livro( 
id_livro int primary key auto_increment, 
nome_livro varchar(50) not null, 
autor_livro varchar(50) not null 
) auto_increment = 10; 

create table if not exists livraria( 
id_livraria int primary key auto_increment, 
nome_livraria varchar(60) not null, 
local_livraria varchar(60) not null 
);

insert into livro(nome_livro, autor_livro) values('Quincas Borba', 'Machado de Assis'); 
insert into livro(nome_livro, autor_livro) values('Meridiano de Sangue', 'Cormac McCarthy'); 
insert into livro(nome_livro, autor_livro) values('Notas do Subsolo', 'Fiódor Dostoievski'); 
insert into livro(nome_livro, autor_livro) values('São Bernardo', 'Graciliano Ramos');

insert into livraria(nome_livraria, local_livraria) values('Editora 34', 'São Paulo'); 
insert into livraria(nome_livraria, local_livraria) values('Bourbon' , 'Rio de Janeiro'); 
insert into livraria(nome_livraria, local_livraria) values('São Paulo', 'São paulo'); 
insert into livraria(nome_livraria, local_livraria) values('Real', 'Rio Grande do Sul'); 
```
