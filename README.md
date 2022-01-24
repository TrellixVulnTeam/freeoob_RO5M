# freeoob

Objetivo: Crear un pequeno sitio con Bootstrap/Sass/Parcel

1- Creamos mkdir freeoob / cd freeoob a través de la consola.
2- En la consola  npm init -y 
3- Instalamos bootstrap  - npm install --save-dev parcel bundler sass
4- En la consola creamos  mkdir src / mkdir scss / touch scss/style.scss  / touch .sassrc
5- Copiamos y pegamos el codigo: {"includePaths": ["node_modules"]
6- En la consola  creamos touch src/index.html y  añadimos los codigos.
7- Añadimos hoja de estilo al archivo index.html 
8- Creamos contiidos (.container)
9- En la consola : npm install @popperjs/core | touch src/ index.js
 y añadimos  import * as bootstrap from 'bootstrap';
 10- Añadimos <script src="./index.js"></script en la página index.html
 11- Creamos en el archivo package.json 
  "start": "parcel ./ src/index.html"
12- En la consola: npm start
13- Editamos style.scss: @import "../node_modules/bootstrap/scss/variables";
  $primario: red;
  $ theme-colors: ("primario":$primario);
  
  
[Sass-Bootstrap-Parcel.pdf](https://github.com/YanLeandro/freeoob/files/7925256/Sass-Bootstrap-Parcel.pdf)
[resultado.pdf](https://github.com/YanLeandro/freeoob/files/7925257/resultado.pdf)
[loginbasico.pdf](https://github.com/YanLeandro/freeoob/files/7925260/loginbasico.pdf)
