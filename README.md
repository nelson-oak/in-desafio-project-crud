# Todo List - Desafio Complementar 1A

Desafio com o intuito de corrigir o códigio de uma API Rest com Node.js e Express

## Entidades

| Entidades | Atributos |
| - | - |
| repository | id, title, url, techs, likes |
| techs | name |

## Requisitos

- [x] Deve ser possível listar os repositórios
- [x] Deve ser possível cadastrar um repositório
- [x] Deve ser possível editar um repositório
- [x] Deve ser possível deletar um repositório
- [x] Deve ser possível incrementar o número de likes de um repositório em 1

## Regras de negócio

- [x] Não deve ser possível editar um repositório não existente
- [x] Não deve ser possível editar os likes de um repositório manualmente
- [x] Não deve ser possível excluir um repositório não existente

## Recursos

- Express
- Dados armazenados em memória

## Iniciando o projeto

Após clonar o projeto, é necessário atualizar as dependências.

### Comandos para baixar dependências e iniciar a aplicação

```bash
yarn
yarn dev
```

### Testar a aplicação

```bash
yarn test
```