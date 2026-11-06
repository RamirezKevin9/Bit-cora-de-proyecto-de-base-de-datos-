# Bita-cora-de-proyecto-de-base-de-datos-
el dia de hoy decidi rehacer la base de datos, la anterior funcionaba pero no me gustaba, se podia mejorar y estar mejor estructurada, por eso la hice de cero y deje todos los nombres de las columnas escritos de la misma forma, quedaron 8 tablas

jugador: que tiene id y nombre
tematica: que tiene id, nombre y carpeta
modo_juego: que tiene id, nombre, descripcion, disponible, cantidadjugadores y guardarecords
nivel: que tiene id, modojuegoid, nombre, filas, columnas, pares que se calcula sola, tiempolimite y vidas
partida: que tiene id, jugadorid, nivelid, tematicaid, fecha, intentos, aciertos, fallos, tiemposegundos, puntuacion y gano
movimiento: que tiene id, partidaid, numero, fila1, columna1, fila2, columna2, acierto y momento
par_descubierto: que tiene id, partidaid, idvalor y puntos
record: que tiene id, partidaid, jugadorid, jugador, modo, nivel, tematica, intentos, aciertos, fallos, tiemposegundos, puntuacion y fecha

saque la tabla carta porque ya no hace falta

por ultimo cargue los datos iniciales, la tematica mezcla, los 6 modos de juego que son clasico, cronometro, contrarreloj, infinito, multijugador y supervivencia, y los 31 niveles (creo que son esas)
