# Aplicação em Laravel

Criação de um site institucional para praticar o uso do framework. O projeto contempla:
## Sistema Administrativo
- Cadastro de banners
- Cadastro de Serviços
- Inclusão de fotos no portifólio

## Landing page
- Barra de Navegação
- Banner Slider
- Quem Somos
- Serviços
- Portifólio
- Contato
- Rodapé
- Chat entrada WhatsApp
## Documentação
https://laravel.com/docs/7.x

### Estrutura do MVC
Site fica em public
http://localhost/site/public

- Controlador
`app/Http/Controllers`

- Visão
Fica em `resources/views`
 
- Modelo
Fica na raiz do `/app`

### Gestão das Rotas
Rotas para site, api e ets
`routes/web.php` são listadas as rotas para navegador
`routes/api.php` são listadas as rotas para api

# Etapas de Instalação

### Requisitos
Postgresql
Php
Composer

### Instalação do Laravel pelo Composer
`composer global require laravel/installer`

### Criação da aplicação
`laravel new site`

### Ajuste no BD
- Arquivo .env
```
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=bd_site
DB_USERNAME=postgres
DB_PASSWORD=
```

### Xampp php.ini
Liberar extensão `extension=pdo_pgsql`

### Criar as tabelas basicas pelo migrate
`php artisan migrate`

### Uso do Artisan para auxiliar na criação
O artisan auxilia na criação de migrates, controllers, view e models

