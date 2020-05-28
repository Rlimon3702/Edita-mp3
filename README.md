# Edita-mp3
Permite editar la meta data de los archivos mp3, asi como renombrar los archivos usando el nombre de artista y titulo. Por ultimo, les deja copiar el archivo a una o varias carpetas que funcionan como playlist


El archivo Programa.INI

Tiene cuatro compos

*Directorio inicial Es un valor que se puede definir como el directorio inicial a buscar los archivos (opcional)

*Directorio Final. busca alguna ruta donde las subcarpetas del primer nivel funcionan como el listado de playlist (opcional)

*def si, en caso de querer usar el acceso directo para mover el archivo a un playlist definido, aqui se coloca

*def no, funciona igual que el anterior. la diferencia entre estas es la combinacion de teclas para ejecutarse. ^U ó ^L

El archivo Artistas

Contiene una lista de artistas que se han guardado anteriormente. Se puede editar con un editor de texto o desde el programa se anexa un artista nuevo al seleccionar la opcion +Artist


El archivo cambios

Permite crear un listado de cambios a realizar en el nombre del archivo antes de renombrarlo.
Recordar que el renombrado de archivo usa como base la metadata de artista / titulo y en estos valores pueden existir caracteres especiales que windows no soporta como por ejemplo "/". para agregar un nuevo valor solo editar el archivo con un editor de texto y separar los valores antes y despues usando el caracter asterisco. Por ejemplo, "/*_" (Sin comillas) en este caso sustituye cualquier diagonal que encuentre por un guión bajo.

El archivo genero

Una lista con los generos a incluir.

El archivo incluye

Al igual que el archivo cambios permite realizar cambios, pero en este caso permite incluir una regla para cambiar la metadata del archivo y evitar que este quede por defecto en modo TITLE y puede hacer que quede algo en un formato en especifico. Por ejemplo al incluir aqui el cambio "Ac / Dc*AC / DC" me permite que el nombre de este artista siempre permanezca en mayusculas.

Saludos
