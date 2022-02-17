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

## Clase 4
- Se continua la explicacion de las etiquetas:
  
    ```html
<h1>Titulo com mayor gerarquia semantica</h1>
<h2>Titulo</h2>
<h3>Titulo</h3>
<h4>Titulo</h4>
<h5>Titulo</h5>
<h6>Titulo</h6>
<p>parrafo</p>
<ul> lista "marca los elementos con viñetas"
    <li>elemento de la lista</li>
</ul>
<ol> lista ordenada "maraca los elementos con numeros"
    <li>elemento de la lista</li>
</ol>
<a>links o hipervinculos</a>
<b>negrilla</b>
<br>salto de linea</br>
<hr>linea</hr>
<button>boton</button>
<div>bloque o secion de documento</div>
<form> formulario
    <lable>etiqueta para el input</lable>
    <input>espacio para digitar</input>
    <textarea>espacio mayor que el input</textarea>
    <checkbox>cuadro de seleccin</checkbox>
    <select>lista de seleccion</select>
</form>
<img/> imagen
<table>
    <tr> fila de tabla
        <th>titulo de tabla</th>
    </tr>
    <tr> fila de tabla
        <td>informacion de tabla</td>
    </tr>
</table>
    ```

- Se utiliza class como atributo en las etiquetas para añadir una clase y usarla para agregar estilos, en la hoja de estilos se pone un punto y el nombre de la clase para pador usar. 

```html
    <h1 class="titulo">Titulo com mayor gerarquia semantica</h1>
```

```css
    .titulo {
        color: red; 
    }
```