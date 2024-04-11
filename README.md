
# Simple Todo List

Projeto desenvolvido com Minimal API com ASP .NET 8.0 apenas para aprendizado 🚀


## Documentação da API

#### Retorna todos as tarefas

```http
  GET /api/Tarefa
```

#### Retorna uma tarefa

```http
  GET /api/Tarefa/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID da tarefa que sera retornada |

#### Cria uma tarefa

```http
  POST /api/Tarefa/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `titulo`      | `string` | **Obrigatório**. Título da tarefa |
| `prazo`      | `data` | **Obrigatório**. Data da Tarefa |
| `concluido`      | `boolean` | **Obrigatório**. Status da tarefa |

#### Atualiza uma tarefa

```http
  PUT /api/Tarefa/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID da tarefa que será atualizada |
| `titulo`      | `string` | **Obrigatório**. Título da tarefa |
| `prazo`      | `data` | **Obrigatório**. Data da Tarefa |
| `concluido`      | `boolean` | **Obrigatório**. Status da tarefa |

#### Remove uma tarefa

```http
  DELETE /api/Tarefa/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID da tarefa que será removida |