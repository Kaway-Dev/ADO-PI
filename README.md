SQL
CREATE TABLE USUARIO(
    id int PRIMARY KEY,
    nome VARCHAR(50) NOT NULL,
    cpf VARCHAR(14) NOT NULL,
    email VARCHAR(50) NOT NULL,
    senha VARCHAR(20) NOT NULL,
    telefone varchar (20) NOT NULL,   
    logradouro varchar (50) NOT NULL,
    numero_endereco varchar (50) NOT NULL

);
