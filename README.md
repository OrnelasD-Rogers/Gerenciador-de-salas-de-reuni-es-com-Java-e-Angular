# Gerenciador de Sala de Reuniões com Java e Angular

## Stack utilizada:


 * Spring Web
 * Spring Data JPA
 * H2 Database
 * Java 8
 * Maven

-  [Angular CLI](https://github.com/angular/angular-cli) versão 9.0.0-rc.7.

## Server de Desenvolvimento

Rode o servidor local através do comando`ng serve`. Vá até o endereço `http://localhost:4200/`.

É necessário também rodar a aplicação SpringBoot para termos acesso a API

## Endpoints criados na API

* Criar sala de reuniao
  POST - /api/v1/rooms

* Listar todas as salas
  GET - /api/v1/rooms

* Buscar uma sala pelo Id
  GET - /api/v1/rooms/{id}

* Atualizar uma sala pelo Id
  PUT - /api/v1/rooms/{id}

* Excluir uma sala pelo id
  DELETE - /api/v1/rooms/{Id}









