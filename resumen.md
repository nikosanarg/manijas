Flujo del uso de Git:
1) git pull (actualiza la rama en la que estas parado)
2) git checkout -b "feature/comentario-nombre" (crea una nueva rama)
3) Hacer los cambios
4) Guardar los cambios
5) git add * (guarda todos los cambios hechos en esa rama creada)
6) git commit -m "Mensaje con los cambios" (comentario sobre los cambios realizados)
7) git push (sube la rama creada a la nube)
8) git checkout master (con checkout te moves de una rama a la otra, en esta caso queremos volver a la rama master, que es la principal)
9) git merge feature/comentario-nombre (con merge traemos la rama que hayamos creado a la rama en la que estamos parados)
10) git push (ya con la rama que creamos y la pusimos en la master, se envia nuevamente nuestros cambios a la nube)

git status (sirve para ver el estado en el que se encuentra lo que estas haciendo, puede que tengas un error en el medio)
git branch (sirve para ver las ramas disponibles que hay)

Elementos HTMl / <etiquetas>

HAY DOS TIPOS: BLOCK E INLINE

Blok:
      *heading desde <h1> hasta <h6> (representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, así como también un logo, un formulario de búsqueda, un nombre de autor y otros componentes)
      *parrafos <p> (es el apropiado para distribuir el texto en párrafos)
      *bloques <div> (define las divisiones lógicas existentes en el contenido de una página web. Puede utilizar etiquetas div para centrar bloques de contenido, crear efectos de columna y crear diferentes áreas de color, entre otras posibilidades)
      *secciones <section> (representa una sección genérica de un documento. Sirve para determinar qué contenido corresponde a qué parte de un esquema)
      *articulos <article> (no entiendo lo que dice de internet xD)


Inline:
       *fragmentos <span> (Sirve para aplicar estilo al texto o agrupar elementos en línea)
       *links <a> (aca se puede poner un link de otra pagina, o que abra una imagen o que te lleve a otra pestaña de tu pagina)
       *imagenes <img> ( representa una imagen en el documento)
       *botones <buttom> (La etiqueta de HTML <button> representa un elemento cliqueable de tipo botón que puede ser utilizado en formularios o en cualquier parte de la página que necesite un botón estándar y simple de aplicar.)




Flujo del ejercicio de HTML:
0) git pull para actualizar el repositorio(actualizar rama master para tener la ultima version)
1) git checkout -b para crear una rama (nombre: "feature/html-mi-nombre")
2) Crear un archivo HTML con tu nombre(nombre.html)
3) Usar el snippet para crear la estructura(el snipet son unas cuantas lineas de codigo resumidas en un simbolo. en este caso es "!")
4) Cambiar el título de la página (se hace cambiando el texto que esta en title)
5) Usar un heading para el título
6) Usar elementos inline simulando una barra
7) Usar elementos block para el contenido
8) Guardar los cambios ( los cambios se puede ir guardando con ctrl + s)
9) git add + commit + push (guardar + empaquetar poniendo una descripcion de lo que hiciste + subir a la nube)
10) Mergear a master y pushear (traer la rama creada a la rama master y subir a la nube la rama master con tu nueva rama incorporada)


Flujo del ejercicio de HTML + CSS:

Parte 1: Estructura
0) git pull para actualizar el repositorio
1) crear una rama nueva (nombre: "feature/css-mi-nombre)
- se recomienda usar solo minúsculas para el nombre
2) Crear una carpeta de nombre: "mi-nombre" dentro de la carpeta "pages" 
3) Colocar la página HTML que hicimos la última clase en esa carpeta con tu nombre
4) Crear en la carpeta con tu nombre un archivo CSS (con extensión .css y cualquier nombre)
5) git add + commit + push (pero NO mergear a master)

Parte 2: Estilos
1) En el archivo HTML, asociar el archivo CSS con la etiqueta <link>
2) En el CSS: Crear una Clase "texto-color" que cambie el color del texto a uno específico (propiedad color)
3) En el CSS: Crear un ID "texto-grande" que le ponga al texto un tamaño de 32px (propiedad font-size)
4) En el CSS: Darle al elemento body (que no es Clase ni ID) un color de fondo claro (propiedad background-color)
5) En el HTML: Ponerle el atributo class="texto-color" a los elementos que queremos cambiar el color de texto
6) En el HTML: Ponerle el atributo id="texto-grande" al primer h1 que tengamos en la página

Parte 3: Confirmar cambios
1) Guardar los cambios en ambos archivos (HTML y CSS) con CTRL + S
2) git add + commit + push
3) Mergear a master y pushear