📱 AppAgenda

Aplicação Android desenvolvida em Java utilizando SQLite para cadastro de pessoas.
O sistema permite cadastrar, listar, atualizar, pesquisar e excluir registros de pessoas no banco de dados.

🚀 Funcionalidades

✅ Cadastro de pessoas
✅ Armazenamento em banco SQLite
✅ Listagem de registros
✅ Pesquisa de pessoas por nome
✅ Atualização de cadastro
✅ Exclusão de registros
✅ Menu superior com pesquisa e botão adicionar
✅ Menu de contexto com atualizar e excluir
✅ Utilização de CRUD completo

🛠 Tecnologias Utilizadas
Java
Android Studio
SQLite
XML
ConstraintLayout
AppCompat
📋 Componentes Utilizados
EditText
Button
ListView
Toolbar
SearchView
AlertDialog
Menu
SQLiteDatabase
🗄 Estrutura do Banco de Dados

Tabela utilizada:

CREATE TABLE pessoa(
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nome VARCHAR(50),
    cpf VARCHAR(50),
    telefone VARCHAR(50)
)
📂 Estrutura do Projeto
AppAgenda
│
├── MainActivity
├── ListarPessoaActivity
├── Pessoa
├── PessoaDAO
├── Conexao
│
├── res
│   ├── layout
│   ├── menu
│   └── values
📌 Funcionalidades CRUD
➕ Create

Cadastro de pessoas no banco de dados.

📖 Read

Listagem e pesquisa dos registros cadastrados.

✏ Update

Atualização das informações da pessoa.

❌ Delete

Exclusão de registros cadastrados.

📱 Telas do Aplicativo
Tela Principal
Cadastro de Nome
Cadastro de CPF
Cadastro de Telefone
Botão Salvar
Tela de Listagem
Lista de pessoas cadastradas
Campo de pesquisa
Menu adicionar
Atualizar cadastro
Excluir cadastro
🔍 Pesquisa de Pessoas

A pesquisa é realizada utilizando SearchView no menu principal.

O usuário pode pesquisar nomes em tempo real diretamente na ListView.

🗃 Classes do Projeto
Pessoa.java

Classe entidade responsável pelos atributos:

id
nome
cpf
telefone

Implementa Serializable.

Conexao.java

Classe responsável pela conexão com o banco SQLite.

PessoaDAO.java

Classe responsável pelos scripts SQL:

INSERT
SELECT
UPDATE
DELETE
MainActivity.java

Responsável pelo cadastro e atualização das pessoas.

ListarPessoaActivity.java

Responsável pela:

Listagem
Pesquisa
Exclusão
Atualização
⚙ Menus do Sistema
menu_principal.xml

Possui:

Buscar
Adicionar
menu_contexto.xml

Possui:

Atualizar
Excluir
⚠ Requisitos

Para executar o projeto é necessário possuir:

Android Studio
JDK
SDK Android

Download Android Studio:

Android Studio

▶ Como Executar
1. Clonar o projeto
git clone https://github.com/seuusuario/AppAgenda.git
2. Abrir no Android Studio
File → Open
Selecionar a pasta do projeto
3. Executar
Conectar um celular Android
ou
Iniciar um emulador

Clique em:

Run ▶
👨‍💻 Desenvolvido por

Wesley Leandro Pinheiro Sebastiana

📚 Objetivo do Projeto

Projeto desenvolvido para aprendizado de:

Banco de dados SQLite
CRUD em Android
Manipulação de ListView
Menus e ContextMenu
Persistência de dados
Desenvolvimento Android em Java
