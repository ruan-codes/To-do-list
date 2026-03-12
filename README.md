# 📋 To Do List App

**Um gerenciador de tarefas simples, bonito e funcional feito com Flask + SQLAlchemy.**

---

## ✨ Sobre o Projeto

Este é um aplicativo web de **Lista de Tarefas** (To-Do List) desenvolvido em Python com o framework Flask.  
Ele permite adicionar, editar e excluir tarefas, tudo salvo automaticamente em um banco de dados SQLite.

---

## 🚀 Funcionalidades

- ✅ Adicionar nova tarefa
- ✏️ Editar qualquer tarefa existente
- 🗑️ Excluir tarefas
- 🔒 Validação inteligente:
  - Não permite tarefas duplicadas
  - Não permite atualizar para o mesmo texto
- 🎨 Design bonito e responsivo

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia          | Uso                          |
|---------------------|------------------------------|
| **Python 3**        | Linguagem principal          |
| **Flask**           | Framework web                |
| **Flask-SQLAlchemy**| ORM e banco de dados         |
| **SQLite**          | Banco de dados               |
| **HTML + CSS**      | Interface (com animações)    |

---

## 📁 Como Executar o Projeto

1. **Clone ou baixe o projeto:**
   ```bash
   git clone "https://github.com/ruan-codes/To-do-list.git"
   cd todo-list-app
2. **Instale as dependências:**
    ```bash
    pip install flask flask-sqlalchemy
3. **Execute a aplicação:**
    ```bash
    python app.py
4. **Acesse no navegador:**
    Abra: http://127.0.0.1:5000


    O arquivo todo.db será criado automaticamente na primeira execução.
