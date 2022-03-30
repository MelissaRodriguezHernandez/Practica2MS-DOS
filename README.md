# Practica2MS-DOS

## Ejercicio 1

1. Crea la siguiente estructura de carpetas:

![estructura](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/ejemplo.png)

`md APLI PROG VARIOS`

`md WORD ACCESS EXCEL`

`md TEXTOS NOTAS`

`md TABLAS INFO`

`md BASIC PASCAL FORTRN`

![estructura D](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/tree%20esquema%20principal.png)


2. Sitúate en la carpeta TABLAS

`cd APLI\EXCEL\TABLAS`

3. Vuelve a la carpeta raíz

`cd \`

4. Muestra el contenido de la carpeta PROG

`dir PROG`

![contenido PROG](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/mostrar%20contenido%20PROG.png)

5. Borra la carpeta PASCAL

`rd PROG\PASCAL`

6. Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamado PRACT

`cd VARIOS`

`md APLI\WORD\PRACT`

7. Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL

`cd APLI\WORD\PRACT`

`dir..\..\EXCEL`

![contenido EXCEL](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/contenido%20excel.png)

8. Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz 

`cd APLI\EXCEL\TABLAS`

`dir \`

![contenido raiz](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/contenido%20carpeta%20raiz.png)

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

![contenido WORD](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/contenido%20word.png)

---

## Ejercico 2

1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT,
con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior):

*“La información dentro de los discos se almacena en forma de archivos. Un archivo
o fichero es un conjunto de datos que MS-DOS almacena en un disco y cuyo
control interno es realizado por el sistema operativo, aunque desde el punto de
vista lógico el control es del usuario”*

![texto notepad](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/archivo%20notepad.png)
 
`cd APLI\WORD\TEXTOS`

`type EJER.TXT`

![texto en terminal](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/Ejer.png)

2. Copia el archivo EJER.TXT en AGENDA

`copy EJER.txt ..\..\..\VARIOS\AGENDA`

3. Borra el archivo almacenado en la carpeta TEXTOS

`del EJER.txt`

4. Añade el siguiente párrafo al archivo EJER.TXT: 

*“Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos”*

![añadir texto](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/Ejer%20parte%202.png)

5. Copia el archivo EJER.TXT en la carpeta BASIC

`copy EJER.txt ..\..\PROG\BASIC`

6. Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT

`rename EJER.txt FICHERO.txt`

7. Mueve el archivo FICHERO.TXT a la carpeta BASIC

`move FICHERO.txt ..\..\..\PROG\BASIC`

8. Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el
nombre NUEVO.TXT dentro de la carpeta BASIC

![borrar frase](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/nuevo%20archivo.png)

9. Copia el archivo NUEVO.TXT en la carpeta NOTAS

`copy NUEVO.txt \..\APLI\WORD\NOTAS`

11. ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?

*En BASIC esta EJER.txt y NUEVO.txt. En NOTAS esta la copa de NUEVO.txt*

---

## Ejercicio 3

1. Borra la carpeta ACCESS y en su lugar crea una nueva carpeta llamada ASTRO

`rd /S ACCESS`

`md ASTRO`

2. Crea la siguiente estructura de subcarpetas dentro de la carpeta ASTRO

![estructura](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/estructura%20ejercicio%203.png)

`md HISTORIA CIENCIA`
`md DATOS1 DATOS2`
`md ASTRO1 ASTRO2`

![arbol astro](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/estructura%20astro.png)

3. Sitúate en la carpeta CIENCIA y desde allí muestra el listado de archivos y subcarpetas de la
carpeta HISTORIA

`cd ASTRO\CIENCIA`

`dir..\HISTORIA`

![contenido historia](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/contenido%20historia.png)

4. Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre
TYCHO.TXT dentro de la carpeta DATOS1

*“La importancia de Tycho Brahe (1546-1601) es debida a sus trabajos
observacionales, que registraron posiciones notables del Sol, la Luna y los
planetas”*

![crear archivo TYCHO](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/crear%20archivo%20tycho.png)

5. Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y
guárdalo con el nombre KEPLER.TXT dentro de la carpeta DATOS2

*“ La información acumulada facilitó a Johannes Kepler (1571-1630) el
descubrimiento de las leyes que gobiernan el movimiento de los planetas”*

![crear archivo KEPLER](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/crear%20archivo%20kepler.png)

6. Copia los archivos TYCHO.TXT y KEPLER.TXT en la carpeta CIENCIA

`copy KEPLER.txt ..\..\CIENCIA`

`copy TYCHO.txt ..\..\CIENCIA`

7. Cambia de lugar los archivos almacenados en DATOS1 y DATOS2 de forma que TYCHO.TXT
quede guardado dentro DATOS2 y KEPLER.TXT en DATOS1

`move TYCHO.txt ..\DATOS2`

`move KEPLER.txt ..\DATOS1`

8. Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el
texto) y guárdalo dentro de la carpeta HISTORIA con el nombre TOTAL.TXT

`type KEPLER.txt >> ..\TOTAL.txt`

`type TYCHO.txt >> ..\TOTAL.txt`

9. Abre el archivo KEPLER.TXT almacenado en la carpeta CIENCIA y añade el siguiente texto:

*“Kepler aplicó sus teorías a los satélites de Júpiter, descubiertos por
Galileo a través de un pequeño telescopio, cuya introducción en la
observación astronómica constituye uno de los hitos de la astronomía.”*

![archivo kepler](https://github.com/MelissaRodriguezHernandez/Practica2MS-DOS/blob/main/añadir%20contenido%20a%20kepler.png)

10. Cambia el nombre del archivo anterior por el de GALILEO.TXT

`rename KEPLER.txt GALILEO.txt`

---

## Ejercicio 4

1. Crea en la carpeta raíz de la unidad A: una carpeta denominada TECINFO


3. Crea dentro de TECINFO el siguiente archivo de texto y llámalo HARD.TXT

*“El HARDWARE está constituido por los elementos físicos del ordenador.
Consta esencialmente de componentes electrónicos que proporcionan el
soporte necesario para la interpretación y ejecución de las operaciones
elementales que realiza el ordenador”*

3. Crea dentro de TECINFO el siguiente archivo de texto y llámalo SOFT.TXT

*“El SOFTWARE es el conjunto de elementos lógicos necesarios para que el
ordenador realice las funciones que se le encomiendan. Está formado por
los programas, es decir, por un conjunto ordenado de instrucciones,
comprensibles por la máquina, que permiten desarrollar tareas concretas”*

4. Mueve el contenido de TECINFO a la carpeta APLI del disquete A utilizado para realizar los
ejercicios anteriores

5. Crea un nuevo archivo formado por la unión de HARD.TXT y SOFT.TXT, sin volver a escribir
el texto, y guárdalo en la carpeta AGENDA con el nombre ORDER.TXT

6. Elimina la carpeta TECINFO

7. Copia a la vez los archivos HARD.TXT y SOFT.TXT en la carpeta VARIOS

8. Cambia la extensión de los archivos contenidos en AGENDA por .TYP
9. Cambia la primera letra del nombre de todos los archivos del directorio APLI que empiecen
por la letra C y tengan extensión DOC de forma que empiecen con la letra S
10. Copia los archivos contenidos en la carpeta APLI que tengan extensión DOC en la carpeta
AGENDA

``
``
