# Quiz-game   Lo primero que hago es usar un comando de impresión o la función de impresión y escribir un valor o cadena para dar la bienvenida a los usuarios. print("Welcome to the Quiz! ").
Luego escribiré una variable para saber si los usuarios van a jugar o no. Así que escribiré playing = y una función de entrada y escribiré una pregunta entre paréntesis  playing = input("Do you want to play? ")
Y luego quiero verificar si los usuarios escribieron sí, así que si escribieron no, finalizaré la programación. Así que escribiré si jugar no es igual a sí. lo que significa que si el usuario escribió una palabra que no es sí, abandonaré la prueba .
if playing.lower() != "yes":
    quit()
Si el usuario escribe sí, le mostraré una oración para comenzar la prueba. print("Great! let's play: ")
después de que el usuario ingresó al cuestionario, daré una primera pregunta y abajo escribiré cuál es la respuesta correcta y, si es correcta, mostraré que es correcta y le daré un punto al usuario, si no lo es, se mostrará incorrecta y sin punto. 
Q1 = input("What does CPU stand for? ")
if Q1.lower() == "central processing unit":
    print('Correct! ')
    score += 1
else:
    print("Incorrect!")
    haré lo mismo con otras preguntas copiándolas y solo cambiando su número, pregunta y la respuesta correcta.
    Q2 = input("What does GPU stand for? ")
if Q2.lower() == "graphics processing unit":
    print('Correct! ')
    score += 1
else:
    print("Incorrect!")
    Después de que los usuarios terminen todas las preguntas que les di, debo darles su resultado o su puntuación en el cuestionario.
    Así que al final de mi programa diré Obtuviste puntos del total de puntos.
    print("You got " + str(score) + "/" + "15" + " questions correct")
    Si los usuarios acertaron 10 preguntas obtendrán 10/15 y si 13 el resultado será 13/15
