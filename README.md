# Robot Control Parser

Este proyecto contiene un parser para controlar un robot en un entorno simulado. El robot puede realizar diversas acciones como moverse, girar, recoger objetos, poner objetos y más, utilizando una sintaxis específica definida en la gramática de este parser.


## Descripción

El objetivo de este proyecto es proporcionar un parser que permite al robot realizar acciones definidas en un lenguaje sencillo. El parser interpreta comandos que el robot debe ejecutar en una interfaz de usuario, y también incluye la posibilidad de realizar verificaciones de estado como si el robot puede moverse o realizar una acción específica.

## Anotaciones
1. Al final de todo un texto que quiera ser parseado y ejecutado ha de ir un punto y coma.
2. Es importante respetar los espacios antes de las instrucciones como toThe, inDir o repeat. Esto debido a que estas pueden ser precedidas por variables y el parser no va a poder distinguir correctamente dónde termina la variable.
3. Se siguen las convenciones establecidas por el enunciado del proyecto, no necesariamente lo que dice el ejemplo. Esto siguiendo lo establecido por el profesor. Esto incluye: los puntos al final de condiciones e instrucciones simples; la no terminación en punto de condicionales y ciclos; la construcción de bloques ejecutables rodeados por corchetas con obligatoriedad, ya sea como parte de un ciclo, condicional o un bloque general/código independiente.

Este proyecto está escrito en Java y usa JavaCC (Java Compiler Compiler) para generar el código del parser a partir de la gramática definida.

# Nombres
- Santiago Muñoz Martinez - 202221167 - s.munoz234@uniandes.edu.co
- César Augusto Espinosa Gómez - 202220692 - c.espinosag@uniandes.edu.co 
