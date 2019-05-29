## Link to App

You can visit the app by clicking this link: [Access App](https://reluviaris-rails-admin.herokuapp.com/admin).

# Reluviaris Gem Rails Admin

Learning Gem Rails Admin with RAILS 5.

## Ruby version: 

* 2.5.1

## System dependencies

* rails 5.2.1

## Configuration
```sh
 $ bundle install
```
```sh
 $ yarn install
```
```sh
 $ rails g rails_admin:install
```
## Database creation
```sh
 $ rails db:create
```
```sh
 $ rails db:migrate
```
## Database initialization

## How to run the test suite

## Services (job queues, cache servers, search engines, etc.): 

## Deployment instructions

### Deploy Heroku

1. Primeiro (via heroku Cli) criamos APP no heroku. Rode no console no diretório do projeto:
```sh
 $ heroku create app-name
```
2. Agora vamos incluir os buildpacks, que são os pacotes que vão ajudar o heroku a instalar nossas dependências:
```sh
 $ heroku buildpacks:add heroku/ruby
```
* *Se você fizer o deploy sem ‘setar’ o buildpack, o heroku vai detectar qual é o seu framework principal e vai ‘setar’ para você, neste caso o buildpack do ruby.*

3. Para finalizar basta rodar os comandos para subir o código:

```sh
 $ git add .
```
```sh
 $ git commit -m 'My first commit'
```
```sh
 $ git push heroku master
```

## Todos

 - Write MORE Tests


License
----

MIT (change)

.
