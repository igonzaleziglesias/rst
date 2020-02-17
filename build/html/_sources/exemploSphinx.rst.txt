====================
Esto es una cabecera
====================

Cabeceira h1
************

Titulo h2
=========

Titulo h3
---------

Titulo h4
+++++++++

Marcado dentro de texto
+++++++++++++++++++++++

Escribimos texto en varias lineas y esto forma un parrafo.
Recuerda que el tabulado es importante para que lo entienda sphinx. Dentro del texto podemos
mediante *cursiva*, o **negrita**  y ``dobles comillas para el codigo``.

Listas no numeradas
+++++++++++++++++++
* Podemos hacer listas.
* Desde distintos elementos.
* Utilizando el * .

Listas numeradas
++++++++++++++++
1. Otra lista numerada.
2. Utilizando el numero seguido del punto.

#. Seguimos numerando listas
#. En este caso utilizamos #.

Con un nuevo parrafo en el medio comienza una nueva numeración?

#. Nueva lista.

Sublistas
+++++++++
* Lista
* con elementos

  * Iinternos
  * Con distintos niveles

* Y subniveles
   * negrita

Definicións
+++++++++++
Termino
  Definición del termino, mediante tabulación

Otro termino.
    Con su definición.

Saltos de linea
+++++++++++++++
| En estas lineas se muestra
| un texto mas grande
| con saltos de linea marcados
| de forma exacta.

Bloques de texto literales
++++++++++++++++++++++++++

El texto normal de un parrafo.
El texto que se muestra a continuación sería un bloque literal ::

    import sys

    class MiClase:
        #Por hacer

Continuamos el texto al mismo nivel de parrafo a continuación.

 >>> 2+2
 4

Tablas
++++++
+---------------------------+-------------+-------------+-------------+
| Cabecera fila, columna 1  | cabecera 2  | cabecera 3  | cabecera 4  |
| Puede usar varias lineas  |             |             |             |
+===========================+=============+=============+=============+
| Fila 1, columna 1         | Fila 1, col2|             |             |
+---------------------------+-------------+-------------+-------------+
| Fila 2, columna 1         | Fila 2, col2|             |             |
+---------------------------+-------------+-------------+-------------+

Listas
++++++

========== ========== ==========
Lista 1    Lista 2    Lista 3
========== ========== ==========
Elemento 1 Elemento 2 Elemento 3
Elemento 4 Elemento 5 Elemento 6
Elemento 7 Elemento 8 Elemento 9
========== ========== ==========

Enlaces
+++++++


 .. _a: link: http://www.danielcastelao.org/

Los enlaces no es necesario marcarlos http://www.danielcastelao.org salvo que queramos
ponerle una etiqueta para el enlace `pepe <http://www.danielcastelao.org/>`_

Otra forma de acceder o `a`_
