<h1>Comandos Artisan Laravel<h1>

<h1><b>migrate<b></h1>
 
<h2><b>php artisan migrate<b></h2>
  <p>Cria todas tabelas as tabelas do banco de dados apartir dos aquivos na pasta migrations do laravel</p>
<h2><b>php artisan migrate:rollback</b></h2>
  <p>Efetua um rollback na última database migration executada no console</p>
<h2><b>php artisan migrate:reset</b></h2> 
  <p>Efetua um rollback em todas database migration da aplicação</p>
<h2><b>php artisan migrate:refresh</b></h2>
  <p>Dropa todas as tabelas na base de dados do sistema e as crias novamente e seguida</p>
<h2><b>php artisan migrate:status</b></h2>
  <p>Mostra o status de cada migration</p>
 
<h1><b>cache</b></h1>
<h2><b>php artisan cache:clear</b></h2>
  <p>Limpa o cache do aplicativo</p>
<h2><b>php artisan cache:table</b></h2>        
  <p>Cria uma migration para gerar uma tabela de cache</p>
  
<h1><b>make</b></h1>
<h2><b>php artisan make:auth</b></h2>
  <p>Cria uma estrutura básica de login e registro de usuário com views e routes</p>
<h2><b>php artisan make:controller NameController</b></h2>
  <p>Cria um novo controler <b>chamado NameController</b></p>
<h2><b>php artisan make:controller NomeController --resource</b></h2>
  <p>Cria um novo controler <b>chamado NameController</b> que conterá um método para cada uma das operações de recursos.</b></p>
<h2><b>php artisan make:migration create_users_table --create=users<b></h2>
  <p>Cria um aquivo de migration chamado <b>create_users_table</b> para a criação de uma tabela chamada <b>users</b></p>
<h2>php artisan make:migration add_votes_to_users_table --table=users</h2>
  <p>Cria um aquivo de migration chamado <b>add_votes_to_users_table</b> para a alteração de uma tabela chamada <b>users</b></p>
<h2>php artisan make:middleware CheckAge</h2>
  <p>Cria uma nova classe chamada <b>CheckAge</b></p>
<h2>php artisan make:model Pessoa</h2>
  <p>Cria uma nova model Eloquent chamada <b>Pessoa</b></p>
<h2>php artisan make:seeder UsersTableSeeder</h2>
  <p>Cria uma nova seeder chamada <b>UsersTableSeeder</b></p>
<h2>php artisan make:test UserTest</h2>
  <p>Cria uma nova classe de teste chamada <b>UserTest</b></p>
<h2>php artisan make:request StoreBlogPost</h2>
  <p>Cria uma nova form request class chamada <b>StoreBlogPost</b></p>
  
<h1><b>db</b></h1>
<h2><b>php artisan db:seed<b></h2>
  <p>Popula com dados as tabelas do framework de acordo os arquivos de seeds</p>

<h1><b>Outros comandos disponiveis</h1>
<h2><b>php artisan clear-compiled<b></h2>
  <p>Remove os arquivos compilados</p>
<h2><b>php artisan serve<b></h2>
  <p>Inicia o servidor interno do PHP para que a aplicação seja acessada</p>
<h2><b>php artisan tinker<b></h2>
  <p>Disponibiliza terminal interativo que nos possibilita rodarmos nossa aplicação via console./p>
  

  

