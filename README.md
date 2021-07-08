# IntroducaoLaravel
<br />
Comandos:<br />
<br />
Para criar migration:<br />
php artisan [nome_função] [nome_tabela_padrao] --create=[nome_tabela_plural]<br />
php artisan make:migration create_produtos_table --create=produtos<br /><br />

Para criar model: <br />
php artisan [nome_função] [nome_model_singular] -m // -m faz com que crie automaticamente uma migration.<br />
php artisan make:model Contato -m<br />

Para criar controller: <br />
php artisan [nome_função] [nome_controller] <br />
php artisan make:controller ContatoController <br />
<br />
Para gerar uma key: <br />
php artisan [nome_função] <br />
php artisan key:generate<br />
Essa key preenche o .env automaticamente <br />
<br />
Para rodar o servidor local: <br />
php artisan serve <br />

<br /><br />
Acessar o tinker: <br />
php artisan tinker <br />

<br />
Listar todos os dados de determinada tabela: <br />
App\[nome_tabela]::all(); <br />

<br />
Criar uma nova instância de determinado dado: <br />
$[variavel] = new App\[nome_model];
<br />
<br />
Popular um objeto: <br />
$[variavel]->[atributo] = "[valor]";<br />
<br />
Listar objeto: <br />
$[variavel];<br />
<br />
Salvar no banco: <br />
$[variavel]->save();<br />
<br />
Encontrar dado no banco: <br />
$[variavel] = App\[nome_model]::find([id]); <br /><br />
Deletar dado do banco: <br />
$[variavel]->delete();

