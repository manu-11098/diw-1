# GRID LAYOUT

## Que es

Sistema de rejillas en dos dimensiones (a diferencia de flexbox que solo actua sobre una dimensión, la horizontal o la vertical, pero solo una)

## Que tiene de diferente

1. Voy a poder colocar los items donde quiera... pero habrá items que se coloquen solos (AUTO-PLACEMENT)
2. Puedo hacer lo mismo de muchas formas... pero no todas hacen lo mismo
3. Controlo las dos dimensiones, no es flexbox
4. La colocación de los items es muy libre, no es una tabla
5. Tiene una extensa sintaxis
6. Nos va a volver un poco locos, pero es muy potente

## Conceptos básicos

![Grid Line](./doc/img/grid-concepts.svg)

1. Las lineas (marcadas en rojo)
2. Los tracks. Espacios entre líneas (marcadas en colores rosa y azul)7
3. Las celdas (marcadas en verde)
4. Las áreas (marcadas en amarillo)

## display grid

En cuanto declaro **display: grid** o **display: inline-grid** los hijos directos de ese elemento pasan a ser grid items

## Definiendo tracks en el grid

Debemos crear el grid explicitamente, es decir, al contenedor grid le indico como deben ser las filas y las columnas (existen múltiples sintaxis y formas de hacerlo)

## Posicionamiento de los grid-items

La enorme potencia de **Grid Layout** en parte viene dada porque una vez generada la regilla, puedo colocar los items donde quiera dentro de esta (Defino un grid donde luego puedo colocar items)

## Líneas nombradas

Dentro del posicionamiento de los grid-items podemos utilizar líneas nombradas, esto es una gran ventaja por:

1. Me ayudan a recordar como van los tracks en layouts complejos
2. En responsive me evitan sobreescribir la colocación de algunos items
3. Si cambia el número de tracks **no tengo que reposicionar elementos**