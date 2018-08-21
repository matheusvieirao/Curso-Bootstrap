# Curso-Bootstrap
Curso de bootstrap feito online com o professor Ricardo Sanches.  
Link do curso: https://www.youtube.com/playlist?list=PLBbHLUbqqCrTwIrdix6kl84m4OPE0JexR

# Rodando Bootstrap com os arquivos fontes

É como foi utilizado para fazer o tutorial. Uma maneira alternativa e mais rápida é só adicionar os arquivos remotos como é explicado no próximo item.

obs: tudo que vem depois de "$" é texto que deve ser digitado no terminal

Para instalar npm:
https://www.npmjs.com/get-npm

ir até a pasta raiz do projeto no prompt e digitar:

$ npm init

$ npm install bootstrap

se não tiver jquerry no pc:

$ npm install jquery

$ npm install popper.js 

</br>
Adicionando as referencias ao código: <br/><br/>

Adicionar para o head:

\<link rel="stylesheet" href="node_modules/bootstrap/compilados/bootstrap.css"> </br>
\<link rel="stylesheet" href="styles/css/estilos.css">

Colocar perto do final da página, logo antes da tag de fechamento </ body>:

\<script src="node_modules/jquery/dist/jquery.js"></script> <br/>
\<script src="node_modules/popper.js/dist/umd/popper.js"></script> <br/>
\<script src="node_modules/bootstrap/dist/js/bootstrap.js"></script>

</br>

Para compilar os arquivos:

instalar sass no site www.sass-lang.com/

executar essa linha para compilar o site (antes dos : é a pasta dos arquivos scss a serem compilados e depois dos : são os arquivos css compilados):<br/>
$ sass --watch node_modules\bootstrap\scss:node_modules\bootstrap\compilados   styles\scss:styles\css 

# Rodando Bootstrap com arquivos remotos

O site https://getbootstrap.com/ deve conter a versão mais atual, mas para rodar a versão 4.1.3 basta:

Adicionar para o head antes de todas as outras folhas de estilo:

\<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">


Colocar perto do final da página, logo antes da tag de fechamento </ body>. O jQuery deve vir primeiro, depois o Popper.js e nossos plugins JavaScript.

\<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
\<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
\<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

# Adicionando FontAwesome (Icones)

colocar no cabeçalho do arquivo html (ou a versão atualizada desse site https://fontawesome.com/how-to-use/on-the-web/setup/getting-started?using=web-fonts-with-css):

\<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">


