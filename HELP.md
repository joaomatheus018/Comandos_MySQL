# 🖥️ Comandos "AJUDA" MySQL

Este documento apresentas comando para ajudar.

---

## 1. 🧹 Limpar a tela do terminal

### Para limpar o histórico visual do terminal sem fechar a sessão:

```bash
system cls;
```

---

## 2. 🗑️ Apagar UMA linha específica (com condição)

### remove apenas o registro que atende à condição (ex: apagar o aluno de matrícula 1):

```bash
delete from aluno where matricula = 1;
```

---

## 3. 💥 Apagar TODOS os dados da tabela (mantendo a estrutura)

### Esvazia a tabela completamente de duas formas:

```bash
truncate table aluno;
```

---

## 4. ⚠️ Destruir a tabela por completo

### Apaga os dados e a própria estrutura da tabela do banco:

```bash
drop table aluno;
```

---

## 5. 💣 Destruir o Banco de Dados inteiro

### Apaga o banco de dados e todas as tabelas dentro dele:

```bash
drop database escola_db;
```

---

## 6. 🚪 Sair do MariaDB / MySQL

### Para fechar a sessão com segurança e voltar ao terminal do sistema:

```bash
exit;
```
