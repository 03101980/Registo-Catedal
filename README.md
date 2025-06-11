# Diocese Management Application

Este projeto é um aplicativo web para o registro de fiéis de uma diocese. Ele permite que os usuários se registrem, visualizem e gerenciem informações sobre sacramentos e catecúmenos. Além disso, inclui uma página administrativa para a aprovação de registros e notificações sobre o status dos pedidos.

## Estrutura do Projeto

```
diocese-management
├── src
│   ├── classes
│   │   ├── Auth.php
│   │   ├── Database.php
│   │   ├── Member.php
│   │   ├── Notification.php
│   │   └── Sacrament.php
│   ├── config
│   │   ├── config.php
│   │   └── database.php
│   ├── controllers
│   │   ├── AdminController.php
│   │   ├── MemberController.php
│   │   └── SacramentController.php
│   └── views
│       ├── admin
│       │   ├── dashboard.php
│       │   └── approvals.php
│       ├── members
│       │   ├── register.php
│       │   └── profile.php
│       ├── sacraments
│       │   └── index.php
│       └── layouts
│           ├── header.php
│           └── footer.php
├── public
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   ├── admin.js
│   │   ├── notifications.js
│   │   └── datatable-config.js
│   └── index.php
├── assets
│   └── lang
│       └── pt_BR.php
├── vendor
├── .htaccess
├── composer.json
└── README.md
```

## Funcionalidades

- **Registro de Fiéis**: Os usuários podem se registrar e gerenciar suas informações.
- **Aprovação Administrativa**: Os administradores podem aprovar ou rejeitar registros.
- **Notificações**: Os usuários recebem notificações sobre o status de seus pedidos (aceito, pendente, rejeitado).
- **DataTable**: Funcionalidade de DataTable com opções para imprimir e exportar em PDF.
- **Interface Moderna**: Utiliza Bootstrap para uma interface gráfica moderna.
- **Tradução para o Português**: Todo o conteúdo está traduzido para o português.

## Requisitos

- PHP 7.4 ou superior
- WampServer para o banco de dados
- Composer para gerenciar dependências

## Instalação

1. Clone o repositório.
2. Configure o banco de dados no arquivo `src/config/database.php`.
3. Execute `composer install` para instalar as dependências.
4. Acesse o aplicativo através do seu servidor local.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

## Licença

Este projeto está licenciado sob a MIT License.