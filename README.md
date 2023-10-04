<html>
<body>

<h1 align="center">API Ruby on Rails</h1>

<p align="center">
    Esta é uma API simples construída com Ruby on Rails para gerenciamento de usuários (CRUD).
</p>

<h2>🛠️ Requisitos</h2>
<ul>
    <li><strong>Ruby</strong></li>
    <li><strong>Ruby on Rails</strong></li>
</ul>

<h2>🔧 Instalação e Configuração</h2>
<ol>
    <li>Clone este repositório:
        <code>git clone https://github.com/[seu_nome_de_usuário]/API-Ruby-on-Rails.git</code>
    </li>
    <li>Entre na pasta do projeto:
        <code>cd API-Ruby-on-Rails</code>
    </li>
    <li>Instale as dependências:
        <code>bundle install</code>
    </li>
    <li>Crie o banco de dados e migre:
        <code>rails db:create db:migrate</code>
    </li>
</ol>

<h2>🚀 Rodando o Servidor</h2>
<p>Para iniciar o servidor:</p>
<code>rails s</code>

<p>
    Acesse a API através da URL:
    <a href="http://localhost:3000/">http://localhost:3000/</a>
</p>

<h2>📌 Endpoints</h2>
<p>A API possui os seguintes endpoints para gerenciamento de usuários:</p>

<h3>🧑‍💻 Usuários</h3>
<ul>
    <li>Listar todos os usuários: <code>GET</code> <a href="http://localhost:3000/api/v1/users">http://localhost:3000/api/v1/users</a></li>
    <li>Visualizar detalhes de um usuário: <code>GET</code> <a href="http://localhost:3000/api/v1/users/:id">http://localhost:3000/api/v1/users/:id</a></li>
    <li>Criar um novo usuário: <code>POST</code> <a href="http://localhost:3000/api/v1/users">http://localhost:3000/api/v1/users</a></li>
    <li>Atualizar um usuário: <code>PUT</code> ou <code>PATCH</code> <a href="http://localhost:3000/api/v1/users/:id">http://localhost:3000/api/v1/users/:id</a></li>
    <li>Excluir um usuário: <code>DELETE</code> <a href="http://localhost:3000/api/v1/users/:id">http://localhost:3000/api/v1/users/:id</a></li>
</ul>
</body>
</html>
