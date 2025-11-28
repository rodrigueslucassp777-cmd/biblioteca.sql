# 📚 Banco de Dados – Biblioteca Universitária  
Projeto desenvolvido para a disciplina de Modelagem e Manipulação de Dados, utilizando SQLite e comandos SQL (DDL e DML).

---

## 🏛️ Mini-Mundo (Descrição do Problema)

Uma biblioteca universitária precisa organizar o cadastro de usuários (alunos e professores), livros, bibliotecários, empréstimos e devoluções.  
O sistema deve permitir:

- Registrar alunos e professores;
- Catalogar livros;
- Controlar quais bibliotecários atenderam cada empréstimo;
- Registrar empréstimos e devoluções;
- Controlar multas.

Este projeto implementa esse mini-mundo em um banco de dados SQLite, contendo criação de tabelas, inserção de dados, consultas, atualizações e exclusões.

---

## 🗂️ Estrutura do Banco de Dados (Tabelas)

O banco contém as seguintes tabelas:

- **Usuario**
- **Livro**
- **Bibliotecario**
- **Emprestimo**
- **Devolucao**

As chaves estrangeiras garantem integridade entre empréstimos e devoluções.

---

## 🛠️ Como Executar o Projeto

### ✔️ 1. Acessar o ambiente online  
Use o editor SQL online:  
🔗 https://sqliteonline.com/

### ✔️ 2. Criar um novo banco  
**File → New Database → SQLite**

### ✔️ 3. Rodar o script completo  
Copie o conteúdo do arquivo **biblioteca.sql** (presente neste repositório)  
e cole no editor do site.

Clique em **RUN**.

### ✔️ 4. Verificar tabelas  
No lado esquerdo devem aparecer:

