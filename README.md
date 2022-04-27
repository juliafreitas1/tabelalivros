# tabelalivros
id serial primary key,
titulo varchar(100)
);
CREATE TABLE cadusuariosdabiblioteca(
id serial primary key,
nome varchar(100) not null
);
CREATE TABLE emprestimos(
id serial primary key,
id_do_livro integer,
id_do_usuario integer
datadoemprestimo date
);select * from emprestimos;insert into cadlivros (titulo) values ('1984');
insert into cadlivros (titulo) values ('Revolucao dos bichos');
select * from cadlivros;
insert into cadusuariosdabiblioteca (id,nome) values (1,'Joao');
insert into cadusuariosdabiblioteca (id,nome) values (2,'Maria');
insert into cadusuariosdabiblioteca (id,nome) values (3,'David');
select * from cadusuariosdabiblioteca;

