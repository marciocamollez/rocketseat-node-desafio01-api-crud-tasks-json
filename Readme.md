API de cadastro de tarefas em json

Rodar o servidor
node src/server.js

Endereco que vai rodar
http://localhost:3333/tasks

Rotas (inserir via insomnia ou postman):

GET - http://localhost:3333/tasks
POST - http://localhost:3333/tasks
DELETE - http://localhost:3333/tasks/ID
PUT - http://localhost:3333/tasks/ID
PATCH - http://localhost:3333/tasks/ID/complete - Vai concluir a tarefa, inserindo a data de conclusao

Vai gerar o arquivo db.json com as tarefas

Arquivo insomnia.json contém as rotas com o json pronto

Sobre a planilha:

Exportar arquivo em formato .csv conforme exemplo

title,description
Task 01,Descrição da Task 01
Task 02,Descrição da Task 02
Task 03,Descrição da Task 03
Task 04,Descrição da Task 04
Task 05,Descrição da Task 05

Dentro da pasta streams vai ter um arquivo chamado import-csv.js. Rodar o comando node streams/import-csv.js

O arquivo planilha-exemplo.csv vai ser executado e mandar pro db.json
