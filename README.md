# Desafio TDD

## Tarefa: TDD Event-City

### Implementação:

![image](https://user-images.githubusercontent.com/15930456/147423317-537c3e97-5d25-4940-b494-8661faa502f9.png)

### Desafio:

Implementação das classes e funcionalidades necessárias para que os testes abaixo passem:

### Testes:

- CIDADE:

  - buscar todos, deverá retornar todos os recursos ordenado por nome
  - inserir, deverá retornar o recurso
  - deletar, deverá retornar _"no content"_ quando o id não tiver dependencia
  - deletar, deverá retornar _"not found"_ quando id não existir
  - deletar, deverá retornar _"bad request"_ quando id for dependente, ou seja, tiver pedendência com outra tabela

- EVENTOS
  - atualizar, deverá atualizar o recurso quando o id existir
  - atualizar, deverá retornar _"not found"_ quando o id não existir
