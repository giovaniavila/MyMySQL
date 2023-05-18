# MyMySQL
### Scripts genéricos para treinar comandos sql




>create database literatura; <br>
  use literatura; 
 > create table if not exists livro( <br>
  id_livro int primary key auto_increment, <br>
  nome_livro varchar(50) not null, <br>
  autor_livro varchar(50) not null <Br>
  ) auto_increment = 10; <br>
> create table if not exists livraria( <br>
id_livraria int primary key auto_increment, <Br>
nome_livraria varchar(60) not null, <Br>
local_livraria varchar(60) not null <Br>
); <br>
> insert into livro(nome_livro, autor_livro) values('Quincas Borba', 'Machado de Assis'); <Br>
insert into livro(nome_livro, autor_livro) values('Meridiano de Sangue', 'Cormac McCarthy'); <br>
insert into livro(nome_livro, autor_livro) values('Notas do Subsolo', 'Fiódor Dostoievski'); <Br>
insert into livro(nome_livro, autor_livro) values('São Bernardo', 'Graciliano Ramos'); <Br>
> insert into livraria(nome_livraria, local_livraria) values('Editora 34', 'São Paulo'); <Br>
insert into livraria(nome_livraria, local_livraria) values('Bourbon' , 'Rio de Janeiro'); <Br>
insert into livraria(nome_livraria, local_livraria) values('São Paulo', 'São paulo'); <Br>
insert into livraria(nome_livraria, local_livraria) values('Real', 'Rio Grande do Sul'); <Br>
