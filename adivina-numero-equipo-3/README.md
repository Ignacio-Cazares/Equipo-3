# Adivina el número

Jesus Paul Hernandez de la Torre
Jose Ignacio Cazares Bocanegra
Jaime Galvan Mendoza

## Descripción

Este proyecto es un juego sencillo desarrollado en Python, donde el jugador debe adivinar un número generado aleatoriamente por el programa.
El objetivo es descubrir el número secreto utilizando la menor cantidad de intentos posible para conseguir una mejor puntuación.

## ¿Cómo funciona?
1. El jugador escribe su nombre.
2. Selecciona una dificultad.
3. El programa genera un número aleatorio.
4. El jugador intenta adivinar el número.
5. El juego indica si el número ingresado es mayor o menor que el número secreto.
6. Al terminar, se muestra la puntuación y los mejores resultados.
7. El jugador puede decidir si quiere volver a jugar.

## Dificultades
- **Fácil:** Números del 1 al 20, con 8 intentos.
- **Medio:** Números del 1 al 50, con 7 intentos.
- **Difícil:** Números del 1 al 100, con 6 intentos.

## Sistema de puntuación
Los puntos se calculan dependiendo de cuántos intentos se utilizaron. Entre menos intentos se necesiten, mayor será la puntuación.
Si el jugador no logra adivinar el número, obtiene 0 puntos.
El programa también muestra los 3 mejores resultados de la sesión.

## Cómo ejecutar el juego
1. Tener Python 3 instalado.
2. Descargar el archivo del juego.
3. Abrir una terminal en la carpeta donde está el archivo.
4. Ejecutar el siguiente comando:

`python juego.py`

## Tecnologías utilizadas
- Python 3
- Librería `random` para generar números aleatorios.
- Librería `datetime` para registrar la fecha y hora de las partidas.

## Objetivo del proyecto
Practicar conceptos básicos de programación en Python, como funciones, condicionales, ciclos, diccionarios, listas y manejo de entradas del usuario.

## Observaciones del código
1. Comportamiento del programa
- El juego permite elegir entre tres dificultades con diferentes rangos de números e intentos.
- El programa indica si el número ingresado es mayor o menor que el número secreto.
2. Entrada del usuario
- El programa verifica que el usuario ingrese números enteros.
- Si el jugador no escribe su nombre, automáticamente se utiliza "Jugador".
- Si se selecciona una dificultad inválida, el programa dice que usará Fácil, pero realmente selecciona Medio.
3. Legibilidad y estructura
- El código está dividido en funciones, lo que facilita entenderlo.
- Los nombres de las variables y funciones son claros y describen lo que hacen.
- El uso de un diccionario para las dificultades permite modificar fácilmente los valores sin cambiar varias partes del código.