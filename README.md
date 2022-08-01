![Logo](https://www.fabricainfo.com/wp-content/uploads/2015/07/logo1.png)

# Sistema de Gerenciamento de Alunos
Teste da empresa fabricainfo - laravel 8 + Docker + Vue.js

## Instalar as dependências do projeto
### Fazer o build do container
```bash
 docker-compose up -d --build
```
### Acessar o container dentro do projeto
```bash
 docker-compose exec php bash
```
### Criar a pasta vendor dentro do container
```bash
 docker-compose exec php bash
```

## Acessar o projeto
### Acessar o container dentro do projeto e instalar as dependências - /var/www/html
```bash
 mkdir vendor
 cd vendor
 composer install
```
### Parar iniciar o laravel
```bash
 php artisan serve
```
### Acessar o Laravel do projeto 
```bash
  http://localhost:8080
```
## Acessar o pgadmin4 para ver as tabelas

```bash
 E-mail: admin@admin.com / Senha: root
 http://localhost:5050
```

## Screenshots

![Acessar o postgress via pgadmin](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/pgadmin.png)
![Tela de Cadastro](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/cadastro.png)
![Tela de Login](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/login.png)
