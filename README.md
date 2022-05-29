### PROYECTO FINAL (COMPILADOR)🙂

** CENTRO UNIVERSITARIO DE CIENCIAS EXACTAS E INGENERIAS**
- Alumno: Dana Ochoa Velasco
- Materia: Seminario de Traductores de Lenguaje II
- Seccion: D02
- Profesor: Dr. Michel Emanuel Lopez Franco


######ANALIZADOR LEXICO
El analizador lexico es la primera fase de un compilador, consistente en un programa que recibe como entrada el código fuente de otro programa (secuencia de caracteres) y produce una salida compuesta de tokens (componentes léxicos) o símbolos. Estos tokens sirven para una posterior etapa del proceso de traducción, siendo la entrada para el analizador sintáctico.

######ANALIZADOR SINTACTICO
Es la segunda fase de un compilador, en cuyo caso, transforma una entrada en un árbol sintáctico de derivación.

El análisis sintáctico convierte el texto de entrada en otras estructuras (comúnmente árboles), que son más útiles para el posterior análisis y capturan la jerarquía implícita de la entrada. Un analizador léxico crea tokens de una secuencia de caracteres de entrada y son estos tokens los que son procesados por el analizador sintáctico para construir la estructura de datos, por ejemplo un árbol de análisis o árboles de sintaxis abstracta.

######ANAIZADOR SEMANTICO
El analizador semántico utiliza el árbol sintáctico y la información en la tabla de símbolos para comprobar la consistencia semántica del programa fuente con la definición del lenguaje. También recopila información sobre el tipo y la guarda, ya sea en el árbol sintáctico o en la tabla de símbolos, para usarla más tarde durante la generación de código intermedio.
