# Bita-cora-de-proyecto-de-base-de-datos-
El dia de hoy decidi que voy a reaser la base de datos por que estaba orriblemente mal, de cero asi que cree 9 tablas que fueron 

carta: que contiene id, partida_id, fila, columna, id_valor, esta_descubierta, esta_emparejada

jugador: que tiene id y nombre

modo de juego: que tiene id, nombre, descripcion, disponible, cantidad_jugadores, guarda_records

movimiento: que tiene id, partida_id, fila1, columna1, fila2, columna2, acierto, momento

nivel: que tiene id, modo_juego_id, nombre, filas, columnas, pares, tiempo_limite, vidas

partida: que tiene id, jugador_id, nivel_id, tematica_id, fecha, intentos, aciertos, fallos, tiempo_segundos, puntuacion, gano

par_descubierto: que tiene id, partida_id, id_valor, puntos

record:que tiene id, partida_id, jugador_id, nivel, intentos, aciertos, fallos, tiempo_segundos, puntuacion, fecha

tematica: que tiene id, nombre, carpeta

eso seria todo (me da peresa decir que tipo son pero creo que es simple de intuir con el nombre)
