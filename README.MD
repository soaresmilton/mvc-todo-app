<div align="center">
<h1>TODO APP</h1>

This repo is about a TODO APP built using MVC architeture, following the tutorial made by [Tania Rascia](www.taniarascia.com)

You can check this tutorial [clicking here](https://www.taniarascia.com/javascript-mvc-todo-app/#getting-started)

</div>

---

### Model

O Model foca em construir as funções que atuam diretamento com os elementos que devem ser construídos. Nesse caso, estamos construindo uma todo-list, o Model tem a função de manipular cada todo dessa lista, sendo que possui as funções para adicionar, editar ou remover. Então, basicamente o Model é responsável pelo CRUD da aplicação.

Apesar de ser responsável pelas funções de CRUD, é importante notar que o MODEL não tem nenhuma funcionaldiade ou conexão com as informações do front-end, que no caso será os formulários que o usuṕario irá interagir para conseguir salvar informações da sua lista de todos.

### View

O View é o responsável pela nossa interface e é nessa classe que iremos construir todo o frontend que dará vida a aplicação. A View lida diretamente com a manipulação da DOM para criar a interface UI do usuário.

É importante destacar que nem o Model e nem o Controller devem saber sobre algum aspecto da DOM. Todo o aspecto visual está inteiramente focado na View.

### Controller