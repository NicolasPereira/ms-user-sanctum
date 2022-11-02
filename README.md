# User-Sanctum

Esta aplicação tem como objetivo aprender a utilizar o Laravel Sanctum para aplicar conceitos de API Tokens com Laravel.

## Tecnologias

- Docker
- PHP
- Laravel & Laravel Sanctum
- MySQL


## Como rodar este projeto

### Clone este repositório
```bash
git clone git@github.com:NicolasPereira/ms-user-sanctum.git
```

### Execute o docker para buildar o ambiente
```bash
docker-compose build
```

### Instale os pacotes necessários
```bash
docker-compose exec web composer install
```

### Gere o arquivo .env

```bash
docker-compose exec web cp .env.example .env
```

### Crie a chave da aplicação
```bash
docker-compose exec web php artisan key:generate
```

### Execute as migrations
```bash
docker-compose exec web php artisan migrate
```

# Autor
Nicolas Pereira | [LinkedIn](https://www.linkedin.com/in/nicolas-pereira/) | [Twitter](https://twitter.com/devnic_)

