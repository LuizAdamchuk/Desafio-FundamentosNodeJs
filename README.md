# Desafio Fundamentos Node.js - GoStack/Rocketseat

O Desafio consiste na adequeação de um projeto node.js.
Para isso foi necessário formular as rotas da aplicação de acordo com as necessidades de cada rota. listagem/criação
As regras de validação estipuladas no desafio foram formuladas em service, então qualquer regra de validação deve ser criada em services.O service passa a funcionar como um filtro entre as rotas e repositories.
O repositories faz a ligação entre o model da nossa aplicação, que é o modelo de armazenamento em nosso banco de dados, e nosso banco de dados. O repositories fica responsável pela interação entre entre o model e o banco de dados, ou seja, qualquer função de listagem, criação, deleção, etc deve ser implementada ali.

## Tecnologias usadas no desafio

- Typescript
- uuidv4

## Padrão de Projeto

- Data Mapper Pattern ou Repository Pattern

Esse padrão tem com foco os princípios dos SOLID e DDD, visando a melhor separação de resposabilidadades da aplicação entre arquivos de rotas, services e repositories.

### Repositório do desafio

- [Respositório no Github do desafio](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-nodejs)
