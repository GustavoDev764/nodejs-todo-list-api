
## Codigo Criado por Gustavo José
<p>Conceitos trabalhados nesse projeto foram middlewares, codigos https, validação de request, API, Parametros, CRUD de todos e teste unitarios.</p>

**Tecnologias usadas**:
- NodeJs
- JavaScript
- Teste Unitarios Jest

**Funcionalidades** - As funcionalidades implementada neste backend
- :heavy_check_mark:`[POST]/users/:` Cadastrar usuario com `
{ 
	name: 'Danilo Vieira', 
	username: 'danilo'	
}
`
- :heavy_check_mark:`[GET]/todos:`   Listar todos os todos do usuario passando na headers username
- :heavy_check_mark:`[POST]/todos:` Cadastrar Todo `
{ 
	title: 'Nome da tarefa', 
	deadline: '2022-04-06'	
}
`
- :heavy_check_mark:`[PUT/]todos/{id}/:` Alterar apenas o title e deadline
- :heavy_check_mark:`[PATCH ]/todos/{id}/done:` Marca todo com feito
- :heavy_check_mark:`[DELETE]/todos/{id}:` Remover um todo baseado no `id`

inicia o app
```sh
yarn dev
```

teste unitarios do app
```sh
yarn test
```
![infor](https://user-images.githubusercontent.com/59968150/162078087-b3ec9bd8-b2d4-4a12-b926-cbbb7e37c8e8.png)
