# Sistema de Pedidos com Java, Spring Boot e JPA

Este projeto é um estudo de caso para implementar um sistema de pedidos utilizando Java, Spring Boot e JPA (Java Persistence API). Ele se baseia em um modelo conceitual abrangente, com diversos recursos como associações, herança, tipos enumerados, entre outros. O objetivo é demonstrar na prática como um modelo conceitual pode ser implementado usando padrões de mercado e boas práticas de desenvolvimento.

## Modelo Conceitual

O modelo conceitual é a base do projeto e inclui:

- Associações: muitos para muitos, um para um, um para muitos.
- Classe de associação.
- Herança.
- Associação direcionada e bidirecional.
- Tipos enumerados (enumerações).

O diagrama do modelo conceitual serve como guia durante a implementação, ajudando a compreender o sistema e identificar tarefas a serem realizadas.

## Objetivos do Estudo de Caso

### Geral:
- Implementar o modelo conceitual utilizando Java, Spring Boot e JPA.
- Criar instâncias do modelo, incluindo objetos associados conforme o diagrama conceitual.

### Específicos:
1. Implementar o modelo gradualmente, com testes e versionamento no GitHub.
2. Gerar automaticamente uma base de dados relacional a partir do modelo conceitual e populá-la com instâncias.
3. Disponibilizar endpoints REST para recuperar e apresentar os dados:
   - `/categorias`: Retorna categorias e produtos associados.
   - `/clientes`: Retorna dados dos clientes, incluindo endereços e telefones.
   - `/pedidos`: Retorna informações sobre os pedidos, incluindo itens associados.

## Estrutura do Projeto

O projeto segue uma estrutura organizada em camadas:

- **Camada de Domínio**: Classes que representam o modelo conceitual.
- **Camada de Acesso a Dados**: Repositórios para interação com o banco de dados.
- **Camada de Serviço**: Lógica de negócio e manipulação dos objetos do domínio.
- **Controladores REST**: Endpoints para acesso aos dados através da API REST.

## Princípios e Boas Práticas

O desenvolvimento segue boas práticas, incluindo:

- Estruturação em camadas.
- Tratamento de exceções personalizado.
- Utilização do padrão DTO (Data Transfer Object) para transferência de dados entre camadas.
- Implementação de uma fachada REST para exposição dos endpoints.

## Como Contribuir

Este estudo de caso estará disponível no GitHub, permitindo acompanhar as modificações feitas ao longo do desenvolvimento. Contribuições, sugestões e feedback são bem-vindos para aprimorar o projeto.

Vamos aprender juntos e desenvolver um sistema de pedidos completo!
