#Rosario

Rosario es una colección de ficheros AIML y AIML 2.0 que forman una base sólida para cualquier proyecto chatbot. Rosario es un fork del proyecto Rosie, quien a su vez es un fork del proyecto ALICE 2.0. Rosie ha sido optimizada para su uso en la plataforma de Pandorabots, y Rosario es la versión en Español de la misma. 

El proyecto está en pleno desarrollo por lo que es totalmente inestable.

Para utilizar a Rosario, crea una cuenta y un nuevo bot en el [Playground](https://playground.pandorabots.com), y sube todos los ficheros del directorio lib. 

Para customizar a Rosario, cambia alguno de los valores que encontrás en rosario.properties

##Directorios

El proyecto tiene los siguientes directorios:

###aiml

Cada bot tiene su propio conjunto de ficheros AIML. Esta colección de ficheros AIML define de manera única la personalidad de un bot. Un bot puede ser el clon de otro, o puede conectar con otro bot a través de <sraix>, pero el propósito del AIML tiene como objetivo que cada bot posea sus propios ficheros AIML.

###maps

Los mapas definen un mapeo clave-valor y actúan como funciones que devuelven un valor para una clave dada.

###sets

Los sets AIML son listas de strings en JSON de elementos únicos que comparten una característica común. por ejemplo, un set de **colores** consistirá en una lista de colores (azul, rojo, amarillo, etc.). Gracias a los sets reduciremos dramáticamente el número de categorías necesarias para cubrir una conversación que implique hablar de colores.

- **Humano**: ¿Es el verde un color?
- **Bot**: Si, el verde es un color.
- **Humano**: ¿Es el rojo un color?
- **Bot**: Si, el rojo es un color.
- **Humano**: ¿Es el coche un color?
- **Bot**: No, el coche no es un color.
