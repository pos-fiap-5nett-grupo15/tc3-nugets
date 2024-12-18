
# Tech Challenge 3 - Grupo 15

Projeto realizado pelo **Grupo 15** da turma da FIAP de Arquitetura de Sistemas .NET com Azure


## Autores

||
|--|
| Guilherme Castro Batista Pereira |
| Evandro Prates Silva |
| Caio Vinícius Moura Santos Maia |
| Luis Gustavo Gonçalves Reimberg |


## UpdateContact

### Tecnologias Utilizadas
- .NET 8
- Dapper
- RabbitMQ
- FluentValidation
- XUnit
- MediatR
- Moq
- Nugget

Dentro da estrutura do tech challenge, este projeto tem como objetivo agrupar os recursos comuns a todas as aplicações, permitindo o compartilhamento de recursos(classes, métodos e configurações) entre os projetos por meio dos repositórios nugget:
- https://www.nuget.org/packages/TechChallenge3.Infrastructure
- https://www.nuget.org/packages/TechChallenge3.Common
- https://www.nuget.org/packages/TechChallenge3.Domain

Os recursos importados nestes repositórios foram utilizados por todos os microsserviços dentro da solução, garantindo uma maior facilidade de manutenção e menor duplicidade de código
