INTRODUCCIÓN
Este repositorio de GitHub trata es un ejemplo de XML de Netflix. Representa la información de varias películas, series y documentales de forma organizada.

ESTRUCTURA
Se divide en tres secciones, películas, series y documentales. Estas secciones se dividen en película, serie o documental respectivamente. Estos elementos deben tener nombre, genero y fecha o numero de episodios en el caso de los documentales. Además cada elemento requiere de un índice como atributo.

ARCHIVO DTD
El archivo .dtd valida que en el XML haya una sola etiqueta raíz llamada Netflix. Que los elemento se encuentren en el orden de los elemento además de que permite que haya varios. Obliga a que cada uno de estos elementos tengan el atributo id. Por último permite que las etiquetas contengan texto

ARCHIVO XSD
El archivo .xsd comprueba que los elementos peliculas, series y documentales esten dentro de la etiqueta raíz netflix. Permite que haya varios elementos y que cada unio tenga los elementos hijos correctos y con el orden indicado. Por último hace que sea obligatorio poner un id en cada elemento y que los tipos de los elementos hijos sean correctos.


DIFICULTADES ENCONTRADAS
Durante el desarrollo de este proyecto, se han encontrado dificultades como el uso adecuado de mayúsculas y minúsculas para las etiquetas y los elementos. Además de definir correctamente los elementos en el DTD.