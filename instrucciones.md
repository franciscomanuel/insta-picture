# Primeros pasos

1. Clonar el repositorio.
2. Generar el **package.json:**
    ``npm init -y``
3. Instalar **webpack** y **webpack-cli:** 
    ``npm install webpack webpack-cli --save-dev``
4. Creamos la carpeta **src** y dentro el archivo **index.js**
5. Empaquetamos con webpack:
    ``./node_modules/.bin/webpack src/index.js``
6. Ejecutamos nuestra aplicación:
    ``node dist/main.js``
7. Para verla con html, necesitamos instalar un pluggin:
    ``npm install html-webpack-plugin --save-dev``
8. Instalamos el servidor de desarrollo de webpack:
    ``npm install webpack-dev-server --save-dev``
