# Helpdesk
Sistema desenvolvido em PHP para atendimento (helpdesk) via chat. Pode ser incorporado a qualquer site.

## Manual de instalação

__Requisitos:__
Servidor Linux com cPanel (cPanel.net), Apache, Php 5.4+, Banco MySQL, phpMyAdmin
__Acesse o cPanel__ - o gerenciador de Banco de dados MySQL, crie o Banco de Dados MySQL, o Usuário de acesso ao banco + senha, depois atribua todas as permissões do usuário ao Banco.

Agora compacte o conteúdo da pasta /Script em um arquivo .zip e faça o upload deste arquivo zipado pelo Gerenciador de Arquivos do cPanel e assim que finalizar o upload descompacte o .zip lá pelo gerenciador mesmo.

Então depois de descompactado, acesse via navegador com a seguinte URL: http://www.DOMINIO.com.br/PASTA/php/app.php

E siga com a instalação digitando as informações do banco de dados mysql que criou e também os dados de acesso ao admin. E pronto! A instalação da base é automática.

Acesso Admin e Operadores:
http://www.DOMINIO.com.br/PASTA/php/app.php?login
Acesse com o admin e crie contas de Operadores para poder fazer o atendimento online.

## Inserir Chat no site / Páginas:
Você pode inserir esse chat em qualquer página HTML, php... Basta inserir o código Widget, é só ir na adminsitração usando o usuário Admin e ir no menu em Get widget script, então vai te dar o código para inserir na sua página. Deverá ser algo assim:

```
<script type="text/javascript" src="http://DOMINIO.com.br/PASTA/php/app.php?widgetinit.js"></script>
```
