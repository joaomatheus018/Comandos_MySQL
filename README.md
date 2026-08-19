# 🖥️ Comandos MySQL

Este documento apresenta os principais comandos utilizados para criar e selecionar um banco de dados no MySQL/MariaDB.

---

## 1. 🔐 Login no MySQL

Execute o seguinte comando no terminal:

```bash
mysql -u root
```

---

## 2. 🔐 Criar e selecionar o Banco de Dados

Criação da base de dados:

```bash
create database escola_db;
```

---

## 3. 🔐 Seleção do banco em uso

(visível no prompt MariaDB [escola_db]>):

```bash
use escola_db;
```

---

## 4. 🔐 Criar a tabela "aluno"

Definição dos campos matricula (chave/número), nome (texto) e cpf (texto/número):

```bash
CREATE TABLE aluno (
    matricula,
    nome VARCHAR,
    cpf VARCHAR)
);
```

---

## 5. 🔐 Inserir os registros

Inclusão dos dados dos 5 alunos exibidos na tabela:

```bash
insert into aluno (matricula, nome, cpf) values
(1, 'Jose Maria', '12312312312'),
(2, 'Ana Silva', '11122233344'),
(3, 'Carlos Oliveira', '22233344455'),
(4, 'Mariana Souza', '33344455566'),
(5, 'Lucas Pereira', '44455566677');
```

---

## 6. 🔐 Consultar e exibir os dados

Envio da instrução de seleção (o ponto e vírgula na linha seguinte indica que a consulta foi confirmada e executada):

```bash
select * from aluno;
```
