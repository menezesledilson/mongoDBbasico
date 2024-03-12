
### Básico mongodb

MongoDB é um software de banco de dados orientado a documentos livre, de código aberto e multiplataforma.
Classificado como um programa de banco de dados NoSQL, o MongoDB usa documentos semelhantes a JSON com esquemas.




## Comandos básico

- mongosh
Listar os databases
- show databases
Selecione o databases
- use nome_do_banco_de_dados

listar a coleção 
- use dbmedias
- show collections

Operações CRUD (Create, Read, Update, Delete)

- db.nome_da_colecao.insertOne({campo: valor})

- db.nome_da_colecao.find({filtro})

- db.nome_da_colecao.updateOne({filtro}, {$set: {campo: novo_valor}})

- db.nome_da_colecao.deleteOne({filtro})

Listar bancos de dados disponíveis:
- show databases

Exibir todas as coleções em um banco de dados:
- show collections

Sair do mongoDB Shell
- exit
Fazer importação

- mongoimport --db nome_do_banco_de_dados --collection nome_da_colecao --file "caminho do arquivo\nome.json"

Fazer exportação
- mongoexport --db=nome_do_banco_de_dados --collection=posts --out=nome_exportados.json

- --db=dbmedias indica o banco de dados do qual você deseja exportar os dados.
- --collection=posts indica a coleção da qual você deseja exportar os dados.
- --out=posts_exportados.json indica o nome do arquivo JSON de saída onde os dados serão exportados.


Installing  the Database Tools
- [Link Database Tools](https://www.mongodb.com/docs/database-tools/installation/installation-windows/)


