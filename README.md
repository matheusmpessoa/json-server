# json-server
Ferramenta para criação de uma fake REST API.

## Documentação da ferramenta
__[https://github.com/typicode/json-server](https://github.com/typicode/json-server)__

## Instalação
```js
npm install -g json-server
```

## Execução
```js
json-server --watch db.json
```

Uma página __[localhost](http://localhost:3000/)__ será aberta contendo sua aplicação e conteúdo do arquivo *db.json*

---

## Acessos

### Visualizar determinada empresa
__[http://localhost:3000/companies/1](http://localhost:3000/companies/1)__

### Pegar todos os usuários de uma empresa
__[http://localhost:3000/companies/2/users](http://localhost:3000/companies/2/users)__

### Filtrar empresas por nome
__[http://localhost:3000/companies?name=Akna](http://localhost:3000/companies?name=Akna)__

### Paginação e limite
__[http://localhost:3000/companies?_page=1&_limit=2](http://localhost:3000/companies?_page=1&_limit=2)__

### Sorting
__[http://localhost:3000/companies?_sort=name&_order=asc](http://localhost:3000/companies?_sort=name&_order=asc)__


### Pegar todos os usuários da aplicação
__[http://localhost:3000/users](http://localhost:3000/users)__

### Determinado usuário
__[http://localhost:3000/users/1](http://localhost:3000/users/1)__

### Determinada idade de usuários
__[http://localhost:3000/users?age_gte=21](http://localhost:3000/users?age_gte=21)__

### Min e max de idade dos usuários
__[http://localhost:3000/users?age_gte=21&age_lte=24](http://localhost:3000/users?age_gte=21&age_lte=24)__

### Pesquisa por nome
__[http://localhost:3000/users?q=Matheus](http://localhost:3000/users?q=Matheus)__