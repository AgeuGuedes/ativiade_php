# ativiade_php
Sistema de Gerenciamento de Tarefas (API)
<br>
No repositório contém uma API desenvolvida como parte de um exercício para a disciplina de PHP API's.
<br>

Para executar a API, abaixo:

Clone o repositório do projeto usando o comando git clone seguido pelo link do repositório.<br>
No terminal, execute o comando composer install para baixar as dependências do projeto.<br>
Inicie o servidor Apache e o MySQL no XAMPP ou em outra ferramenta semelhante.<br>
No terminal, execute o comando php artisan migrate para executar as migrações do banco de dados.<br>
Em seguida, execute o comando php artisan serve para iniciar o servidor da API.<br>

No Postman:

criar uma nova coleção para organizar as solicitações.<br>
Adicione cinco solicitações à coleção:<br>
Listar todas as tarefas - método GET<br>
Detalhes de uma tarefa específica - método GET<br>
Adicionar uma nova tarefa - método POST<br>
Atualizar dados de uma tarefa - método PUT<br>
Excluir uma tarefa - método DELETE<br>
<br>
![image](https://github.com/AgeuGuedes/ativiade_php/assets/125320542/5290fb29-c84c-4393-ade9-965cbba02d0e)
<br>

Coloque a URL que foi gerada no comando php artisan serve <br>
Get - URL/tasks <br>
Get - URL/tasks/{id} <br>
Post - URL/tasks <br>
Put - URL/tasks/{id} <br>
Del - URL/tasks/{id} <br>
No método Post e Put vá em body, selecione row e coloque em JSON <br>
<br>
Método postman <br>
<br>
{<br>
    "title": "Titulo da tarefa",<br>
    "description": "Descrição da tarefa",<br>
    "status": true <br>
}<br>
Agora você pode executar as solicitações no Postman para interagir com a API.<br>

