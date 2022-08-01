# teste-fabricainfo
Teste da empresa fabricainfo - laravel 8 + Docker + Vue.js

## Acessar o projeto

Fazer o build do container

```bash
  docker-compose up -d --build  
```

Acessar o container dentro do projeto

```bash
  docker-compose exec php bash 
```

Levantar o container do projeto

```bash
  docker-compose up 
```

Parar o container do projeto

```bash
  docker-compose stop 
```

Acessar o Laravel do projeto 

```bash
  http://localhost:8080
```

Acessar o pgadmin4 para ver as tabelas
Acesso / E-mail: admin@admin.com / Senha: root
```bash
  http://localhost:5050
```

## Screenshots

![Acessar o postgress via pgadmin](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/pgadmin.png)
![Tela de Cadastro](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/cadastro.png)
![Tela de Login](https://github.com/vancouvertec/teste-fabricainfo/blob/main/imagem/login.png)
