# Hospital API

API backend desenvolvida com Java e Spring Boot para gerenciamento de pacientes e consultas médicas.

## Tecnologias utilizadas

* Java
* Spring Boot
* Lombok
* Maven
* Programação Orientada a Objetos (POO)

## Funcionalidades

### Pacientes

* Cadastro de pacientes
* Validação de dados

### Consultas

* Agendamento de consultas
* Cancelamento de consultas
* Realização de consultas
* Validação de consultas já realizadas

## Estrutura do projeto

O projeto foi organizado utilizando separação em camadas:

```txt
Controller → Requisições HTTP
Service → Regras de negócio
Repository → Manipulação de dados
Data → Estrutura das entidades
```

## Endpoints

### Cadastrar paciente

```http
POST /hospital/cadastrar
```

### Agendar consulta

```http
POST /hospital/agendar
```

### Realizar consulta

```http
POST /hospital/realizar
```

### Cancelar consulta

```http
DELETE /hospital/cancelar
```

## Objetivo do projeto

O projeto foi desenvolvido com foco em aprendizado de:

* APIs REST
* Estruturação backend
* Spring Boot
* Organização em camadas
* Regras de negócio

## Melhorias futuras

* Integração com banco de dados
* Utilização de JPA/Hibernate
* Implementação de ResponseEntity
* Tratamento global de exceções
* Documentação com Swagger
* Validação utilizando Bean Validation
