![](https://miro.medium.com/max/1200/1*kXElS1Y6s3HDgdZELh4smQ.png)
# Anotações do Master Class da Rocketseat de SASS com Maik Brito


### Guia
[Guia](https://www.notion.so/maykbrito/SASS-0ae90c9c85474e8caf1e5df8620aa3e4)

### Vídeo de Referência

[vídeo](https://www.youtube.com/watch?v=BaI8dHUthLA&t=1782s)


### Instalação

    npm i -g sass (sudo npm i -g sass)

### Extensões vs code

    live sass compiler
    SCSS Formatter

### Rodando o Projeto com Lite Server

    npx lite-server

    npm start

## Declarando Variáveis

Em SASS podemos declarar variáveis para facilitar o reuso de cores, margens, ou qualquer outro 
atributo que quisermos.

Declarando uma cor:

    $dark: #222;

Utilizando a variável:

    body {

        background-color: $dark;
        
    }


## Import e Export

Podemos criar outro arquivos .scss e ao nomear o arquivo, colocamos o "_" na frente para evitar
que ele seja compilado.


ex:
    _style2.scss


Para depois no main.css importá-lo assim:

    @import 'style2';


## Encadeamento

Assim como em uma linguagem de programação, podemos criar escopos e fazer encadeamento no SASS


    .container{

    background-color: whitesmoke;
    width: 300px;
    height: 300px;
    border-radius: 7px;
   

    .box-out{

        background-color: #4556f1;
        width: 200px;
        height: 200px;
        border-radius: 7px;
        



        .box-in{

            background-color: $pink;
            width: 100px;
            height: 100px;
            border-radius: 7px;



            }
        }
    }