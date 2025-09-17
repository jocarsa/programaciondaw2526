🏀 Enunciado del ejercicio: "Gestor de partido de baloncesto"

Vas a programar una pequeña aplicación en JavaScript que simule un partido de baloncesto entre dos equipos.
El objetivo es poner en práctica todas las estructuras que hemos visto en clase: variables, condicionales, bucles, arrays y funciones.

Requisitos

Definición de equipos

Pide al usuario por teclado (prompt) los nombres de los dos equipos.

Guarda los nombres en variables.

Marcador inicial

El marcador empieza en 0 para ambos equipos.

Debe mostrarse en pantalla (document.write o console.log).

Simulación de jugadas (bucles)

Usa un bucle para simular las jugadas de 4 cuartos.

Dentro de cada cuarto, genera con Math.random() varias jugadas en las que un equipo puede anotar 1, 2 o 3 puntos.

Condicionales

Si el número aleatorio es bajo, anota el primer equipo.

Si el número es alto, anota el segundo equipo.

Muestra en cada jugada qué equipo ha anotado y cuántos puntos.

Funciones

Crea una función anotar(equipo, puntos) que reciba el nombre del equipo y los puntos, sume al marcador y devuelva el nuevo total.

Utiliza la función dentro del bucle de jugadas.

Resultado final

Al terminar el bucle, muestra el marcador final.

Si ambos equipos empatan, el programa debe añadir una prórroga hasta que haya un ganador.

Extra (opcional)

Guarda las jugadas en un array y, al final, muestra el “resumen del partido” con todas las anotaciones.
