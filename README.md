Projeto de Mini Blog
Backend

    Tecnologias Utilizadas: Flask, SQLAlchemy, SQLite

    Funcionalidades:
        Autenticação: Criação e login de usuários com gerenciamento de sessão.
        CRUD de Posts:
            Criação: Usuários autenticados podem criar novos posts.
            Leitura: Exibição de todos os posts, com detalhes completos ao selecionar um post específico.
            Atualização: Usuários podem editar seus próprios posts.
            Exclusão: Usuários podem deletar seus próprios posts.

    Rotas Principais:
        /register: Registro de novos usuários.
        /login: Login de usuários existentes.
        /logout: Logout do usuário.
        /create_post: Criação de novos posts.
        /edit_post/<id>: Edição de posts existentes.
        /delete_post/<id>: Exclusão de posts existentes.
        /posts: Exibição de todos os posts.
        /post/<id>: Exibição de um post específico.

Frontend

    Tecnologias Utilizadas: HTML, CSS, Bootstrap

    Funcionalidades:
        Interface de Usuário:
            Formulários:
                Registro e login de usuários.
                Criação e edição de posts com campos para título e conteúdo.
            Exibição:
                Listagem de todos os posts com títulos e resumos.
                Página de detalhes de um post específico.
            Botões:
                Links para editar e excluir posts (disponíveis apenas para o autor do post).
                Botão para criação de novos posts (disponível para usuários autenticados).

    Layout:
        Navbar: Navegação com links para Home, Login, Registro e Logout.
        Página Principal: Listagem de posts com títulos, resumos e links para detalhes.
        Página de Post: Exibição completa do post com título e conteúdo.
        Formulários de Criação e Edição: Campos para entrada de título e conteúdo do post.

Banco de Dados

    Tecnologia Utilizada: SQLite
    Estrutura:
        Tabelas:
            User: ID, nome de usuário, senha hash.
            Post: ID, título, conteúdo, data de criação, ID do autor.

Esse mini blog fornece uma plataforma básica para usuários criarem, visualizarem, editarem e deletarem posts, com uma interface simples e intuitiva.
