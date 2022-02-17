# Desarrollo de Software

Este repositorio contendra lo visto en las clases, principalmente los comandos utilizados y el paso a paso de cada una.

## Clase 1

- Primera clase se instalo vscode, se intalo git, se creo repositorio en github y se clono.
- Consola se abre en el vscode con CTRL + ñ.
- En la consola se pueden ver los directorios con comado: dir
- En consola se mueve por carpetas con comando: cd
- Mover hacia atras: cd ..
- Mover hacia adelante: cd "nombre de la carpeta"

## Clase 2
#### comandos de git
- git config --global user.name "John Doe"
- git config --global user.email johndoe@example.com
- git clone : clonar repositorio
- git status : muestra cambios en archivos
- git add "nombre del archivo", git add . : agregar archivo, cambio o todos los cambios
- git commit -m "mensaje" : añadir mensaje al cambio de archivo
- git push : subir cambios al repositorio
- Se crea archivo con extencion .html escribiendo html5 en el documento y vs code autocompleta la estructura

## Clase 3

- Se crean etiquetas semanticas de estructura dentro del body.
- Se crean estilos en diferentes espacios como directamente en las etiquetas, en header y en una hoja de estilos aparte que es la mejor manera de hacerlo.

HTML

mi-primera-web.html
```html
<head>
    <link rel="stylesheet" href="styles.css"> <!--agrego la ubicacion del archivo css--> 
    <style>
        nav{
            background: green;
        }
    </style>
</head>
<body>
    <header style="background-color:red">Encabezados</header>
    <nav>barra de navegacion</nav>
    <section>secciones de informacion</section>
    <article>seccion con informacion diferente e independiente</article>
    <aside>informacion adicional normalmente informacion relacionada en un lateral de la pagina</aside>
    <footer>informacion adicional, links, firma del autor</footer>
</body>
```
CSS

styles.css
```css
    section{
        background: yellow;
    }
```