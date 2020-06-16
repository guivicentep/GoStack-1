# Desafio01
Durante esse primeiro desafio do Bootcamp GoStack 12, foi proposto a criação de um gerenciador de projetos, aplicando os primeiros conceitos de CRUD (CREATE, READ, UPDATE, DELETE), onde os dados ficaram armazenados em variáveis, na memória.

## Abaixo, alguns conceitos importantes que foram utilizados:

### API REST
- Seu funcionamento ocorre através de uma requisição feita por um cliente, onde a resposta sempre vai ser retornada através de uma estrutura de dados. O cliente vai receber essa resposta e processar o resultado, sua diferença é que, o back-end deixa de retornar HTML como faz em uma estrutura MVC, e retorna apenas uma estrutura, fazendo uma "divisão" de trabalho com o front-end, que vai ficar responsável por organizar e exibir esses dados.
- Entre alguns dos seus benefícios, podemos citar a utilização de múltiplos clientes, ou seja, com apenas um back-end, podemos utilizar sua estrutura para uma aplicação web, mobile, e até mesmo uma API pública, isso só é possível graças ao uso do JSON (JavaScript Object Notation)

### Métodos HTTP
 <strong> GET:</strong> Realiza a busca de informações. Pode listar todos os itens, ou, com a utilização de filtros, listar apenas uma parte utilizando alguns parâmetros 

 <strong> POST:</strong> Realiza a criação de uma informação, esse tipo de requisição geralmente tem um corpo, onde vão ser passadas as informações a serem inseridas.

 <strong>PUT ou PATCH:</strong> Realiza a alteração de uma informação. Para isso, se faz necessário possuir o "id" desse registro, além da posição onde o mesmo está dentro do array, isso facilita sua atualização. O PATCH só é utilizado em casos de pequenas alterações, onde não se faz necessário a alteração de todo o registro, e sim de uma parte.

 <strong>DELETE:</strong> Realiza a exclusão de um registro. Para isso, precisamos também do "id" desse registro, bem como sua posição dentro do array, por retornar uma mensagem vazia, recomenda-se devolver um status code junto.
 
### Parâmetros da requisição

- Query Params: São utilizados para filtros e paginação, acabam sendo utilizados no método <strong>GET</strong>.
- Route Params: São utilizados para identificar recursos, utilizados para <strong>UPDATE</strong> ou <strong>DELETE</strong>
- Request Body: Basicamente, é conteúdo que será enviado no corpo de uma requisição na hora de criar ou editar um recurso. Por padrão usa o formato JSON

### Middleware
- Pode ser definido como um interceptador de requisições, que pode: interromper totalmente uma requisição ou alterar dados dela, é muito utilizado para realizar validações dentro dos métodos, e garantir que o usuário está passando os parâmetros corretamente. Também pode ser utilizado para analisar o tempo de resposta dos métodos, e o que está sendo passado como parâmetro.


 


