# Desafio01
Durante esse primeiro desafio, aplicamos alguns conceitos importantes de métodos HTTP, utilizamos:

 <strong> GET:</strong> Realiza a busca de informações. Pode listar todos os itens, ou, com a utilização de filtros, listar apenas uma parte utilizando alguns parâmetros 

 <strong> POST:</strong> Realiza a criação de uma informação, esse tipo de requisição geralmente tem um corpo, onde vão ser passadas as informações a serem inseridas.

 <strong>PUT ou PATCH:</strong> Realiza a alteração de uma informação. Para isso, se faz necessário possuir o "id" desse registro, além da posição onde o mesmo está dentro do array, isso facilita sua atualização. O PATCH só é utilizado em casos de pequenas alterações, onde não se faz necessário a alteração de todo o registro, e sim de uma parte.

 <strong.DELETE:</strong> Realiza a exclusão de um registro. Para isso, precisamos também do "id" desse registro, bem como sua posição dentro do array, por retornar uma mensagem vazia, recomenda-se devolver um status code junto.


