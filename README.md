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


## Declarando Variáveis

Em SASS podemos declarar variáveis para facilitar o reuso de cores, margens, ou qualquer outro 
atributo que quisermos.

Declarando uma cor:

    $dark: #222;

Utilizando a variável:

    body {

        background-color: $dark;
        
    }