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
