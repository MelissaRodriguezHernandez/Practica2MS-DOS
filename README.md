# Practica2MS-DOS
1. Crea la siguiente estructura de carpetas:

`md APLI PROG VARIOS`

`md WORD ACCESS EXCEL`

`md TEXTOS NOTAS`

`md TABLAS INFO`

`md BASIC PASCAL FORTRN`

2. Sitúate en la carpeta TABLAS

`cd APLI\EXCEL\TABLAS`

3. Vuelve a la carpeta raíz

`cd \`

4. Muestra el contenido de la carpeta PROG

`dir PROG`

5. Borra la carpeta PASCAL

`rd PROG\PASCAL`

6. Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamado PRACT

`md APLI\WORD\PRACT`

7. Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL

`cd APLI\WORD\PRACT`

`dir..\..\EXCEL`

8. Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz 

`cd APLI\EXCEL\TABLAS`

`dir \`

9.Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de VARIOS

`cd APLI`

`mkdir ..\VARIOS\AGENDA`

10. Borra la carpeta EXCEL

`rd /S EXCEL`

11. Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO

`cd \`

`mkdir NUEVO`

12. Desde PRACT muestra el contenido de WORD

`cd APLI\WORD\PRACT`

`dir ..`

1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT,
con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior):

“La información dentro de los discos se almacena en forma de archivos. Un archivo
o fichero es un conjunto de datos que MS-DOS almacena en un disco y cuyo
control interno es realizado por el sistema operativo, aunque desde el punto de
vista lógico el control es del usuario”
 
`cd APLI\WORD\TEXTOS`

`type EJER.TXT`

2. Copia el archivo EJER.TXT en AGENDA

`copy EJER.txt ..\..\..\VARIOS\AGENDA`

3. Borra el archivo almacenado en la carpeta TEXTOS

`del EJER.txt`

4. Añade el siguiente párrafo al archivo EJER.TXT: 
“Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos”



5. Copia el archivo EJER.TXT en la carpeta BASIC

`copy EJER.txt ..\..\PROG\BASIC`

6. Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT

`rename ARCHIVO.txt FICHERO.txt`

7. Mueve el archivo FICHERO.TXT a la carpeta BASIC

`cd APLI\WORD\TEXTOS\AGENDA FICHERO.txt move ..\..\..\PROG\BASIC`

8. Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el
nombre NUEVO.TXT dentro de la carpeta BASIC

`move FICHERO.txt ..\..\..\PROG\BASIC` 

9. Copia el archivo NUEVO.TXT en la carpeta NOTAS

''

11. ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?
``
``
``
