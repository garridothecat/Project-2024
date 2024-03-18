# Documento Descritivo do Projeto

## Introdução

O objetivo deste projeto foi desenvolver uma aplicação full-stack integrando Laravel como backend, fornecendo uma REST API com funcionalidades de login e registro, e React como frontend. O projeto também incluiu o deploy da aplicação para ambiente de produção.

## Instruções de Configuração:

1. **Navegar até ao Diretório Raiz do Projeto:**

    - Abrir o terminal e acessar o diretório raiz do projeto.

2. **Instalar Dependências:**

    - Executar `composer install` para instalar as dependências do PHP (Laravel).

3. **Definir Chave de Encriptação:**

    - Gerar uma nova chave de encriptação executando `php artisan key:generate --ansi`.

4. **Executar Migrações:**

    - Executar `php artisan migrate --seed` para executar as migrações da base de dados.

5. **Iniciar Servidor Local:**

    - Iniciar o servidor local executando `php artisan serve`.

6. **Configuração do React:**

    - Abrir uma nova janela do terminal.
    - Navegar até à pasta do React.

7. **Instalar Dependências do React:**

    - Executar `npm install` para instalar as dependências do Node.js para o React.

8. **Iniciar Servidor Vite para o React:**
    - Executar `npm run dev` para lançar o servidor Vite para o React.

## Tecnologias usadas em React:

-   Utilização da API de Contexto
-   Uso de hooks do React
-   Implementação do React Router
-   Criação de rotas protegidas
-   Desenvolvimento de layouts variados
-   Conexão com uma API
-   Gestão de autenticação

## Tecnologias usadas em Laravel:

-   Criação de endpoints de API para login e registro
-   Implementação de endpoints de API CRUD básicos
-   Tratamento de dados de solicitação de formulário
-   Criação de recursos
-   Implantação da aplicação em um ambiente de produção através de SSH, Git e conexões de banco de dados MySQL.

## Descrição da Aplicação:

Quando a aplicação é iniciada, os utilizadores são recebidos com uma página de login. Aqui, têm a opção de entrar com uma conta existente ou criar uma nova. Após o processo de login, os utilizadores são conduzidos a um layout padrão de painel administrativo, composto por um cabeçalho, barra lateral e tabela. Serão implementadas funcionalidades CRUD nesta tabela, juntamente com um router do React para facilitar a navegação entre páginas. Os utilizadores também terão a capacidade de adicionar, editar e eliminar entradas. Ao adicionar uma nova entrada, qualquer erro de validação necessário será exibido, enquanto as notificações serão apresentadas discretamente no canto inferior direito da tela. Quando os utilizadores optam por "Terminar sessão", o token de autorização é revogado, encerrando a sessão atual. A partir daqui, os utilizadores podem optar por efetuar novamente o login ou criar uma nova conta, conforme necessário.

## Conclusão:

Este projeto demonstra uma integração eficaz entre Laravel e React, resultando em uma aplicação web completa e funcional. A ênfase na segurança e na experiência do usuário é evidente nas implementações de autenticação e operações CRUD. Em resumo, é um exemplo sólido de como tecnologias modernas podem ser combinadas para criar soluções web robustas e intuitivas.
