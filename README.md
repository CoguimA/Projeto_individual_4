ESCOLA:

Curso:
- nome varchar(50),
- carga_horaria int,
- local varchar(50),
- id int primary key;

Turma:
- turno varchar(20),
- professor varchar(50),
- numero_da_turma int primary key,
- numero_de_alunos int;

Alunos:
- nomes varchar(50),
- email varchar(50),
- cpf varchar(20) primary key,
- nota float;
