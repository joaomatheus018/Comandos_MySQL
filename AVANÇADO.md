# 💻 Comandos MySQL - Avançado

Este documento apresenta comandos avançados do MySQL para administração e consultas.

---

## 1. 📌 Listar Bancos de Dados

Exibe todos os bancos de dados disponíveis.

```bash
show databases;
```

---

## 2. 📌 Listar Tabelas

Exibe todas as tabelas do banco selecionado.

```bash
show tables;
```

---

## 3. 📌 Descrever uma Tabela

Mostra a estrutura de uma tabela.

```bash
describe alunos;
```

---

## 4. 📌 Ordenar Resultados

Ordena os registros em ordem crescente.

```bash
select * from alunos
order by nome;
```

---

## 5. 📌 Agrupar Registros

Agrupa registros por um campo.

```bash
select cidade, count(*)
from clientes
group by cidade;
```

---

## 6. 📌 Filtrar Agrupamentos

Filtra os grupos após o agrupamento.

```bash
select cidade, count(*)
from clientes
group by cidade
having count(*) > 5;
```
