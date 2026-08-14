---
title: Pauta
parent: Hito 0
nav_order: 0
layout: page
---

# Pauta Hito 0

## 1. Platformer

- **[1.35] Jugador**
  - (0.25) Movimiento: En dos ejes
  - (0.10) Movimiento: Salto
  - (0.10) Sonido: Salto
  - (0.10) Sonido: Aplastar enemigo
  - (0.80) Animaciones: Idle, Correr, Salto, Rebote (0.2 cada una)

- **[1.00] Cámara**
  - (1.00) Sigue al jugador y muestra hacia donde se mueve. (Derivada del movimiento, sin mouse, no fija a la espalda)

- **[1.90] Enemigo & Interacciones**
  - (0.60) Ataque: Jugador daña/mata enemigo (colisión con los pies mientras cae)
  - (0.60) Ataque: Enemigo daña/mata jugador (colisión desde otros lados)
  - (0.30) Movimiento: Rebote del jugador al aplastar enemigo
  - (0.40) Aparición: Más enemigos a lo largo del tiempo. (No deben aparecer dentro de otro enemigo o del jugador)

- **[0.75] Nivel**
  - (0.75) Nivel con piso y al menos tres plataformas visibles. (Incluye colisiones)

- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menú)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menú. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Salir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - El jugador es un modelo con animaciones de esqueleto hechas en blender


## 2. Shooter

- **[1.95] Jugador**
  - (0.20) Movimiento: En dos ejes
  - (0.10) Movimiento: Salto
  - (0.10) Sonido: Salto
  - (0.10) Sonido: Disparo
  - (1.00) Animaciones: Idle, Correr, Salto, Disparo, Apuntar (0.2 cada una)
  - (0.45) Proyectil: Jugador puede disparar (crear un proyectil)

- **[0.75] Cámara**
  - (0.30) Primera o tercera persona, fija al jugador y rota con el mouse
  - (0.45) Apuntar: Botón que mueve y/o hace zoom a la cámara

- **[1.55] Enemigo & Interacciones**
  - (0.25) Proyectil: Se mueve en la dirección disparada
  - (0.60) Ataque: Proyectil daña/mata enemigo
  - (0.10) Sonido: Proyectil al chocar con un enemigo
  - (0.60) Ataque: Enemigo daña/mata jugador

- **[0.75] Nivel**
  - (0.75) Nivel con bloques/muros visibles. (Incluye colisiones con el jugador y los proyectiles)

- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menú)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menú. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Salir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - El jugador es un modelo con animaciones de esqueleto hechas en blender


## 3. Racing

- **[1.45] Jugador**
  - (0.30) Movimiento: Acelerar y frenar
  - (0.20) Movimiento: Girar (dos ejes)
  - (0.20) Movimiento: Reversa
  - (0.15) Luces: Delanteras (prender y apagar con un botón)
  - (0.20) Luces: Traseras (al frenar y retroceder)
  - (0.40) Sonido: Avance, Retroceso, Bocina, Choque (0.1 cada uno)

- **[1.20] Cámara**
  - (1.00) Tercera persona: Ve al auto desde atrás. (Derivada de la posición del auto, sin mouse)
  - (0.10) Primera persona: Desde dentro del auto
  - (0.10) Cámara hacia atrás

- **[1.60] Enemigo & Interacciones**
  - (0.60) Ataque: Jugador destruye enemigo (colisión a alta velocidad)
  - (0.60) Ataque: Enemigo daña/destruye jugador (colisión a baja velocidad)
  - (0.40) Aparición: Enemigos reaparecen tras un tiempo de ser destruidos. (No deben aparecer dentro de otro enemigo o del jugador)

- **[0.75] Nivel**
  - (0.75) Nivel con elevaciones de terreno y/o rampas. (No puede ser solo un plano infinito)

- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menú)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menú. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Salir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - Se utilizan modelos con materiales y texturas hechos en blender. El auto debe parecer hecho de metal.


## 4. Puzzle

- **[2.20] Jugador**
  - (0.80) Movimiento: Rotación de 90° sobre las aristas en 4 direcciones
  - (0.30) Caída: Al salir del tablero
  - (0.20) Victoria: Llegar a la celda de meta avanza al siguiente tablero
  - (0.20) Teletransporte: Moverse a la celda inicial al caer del tablero o morir
  - (0.40) Animaciones: Victoria, Muerte (0.2 cada una)
  - (0.30) Sonido: Rotar, Ganar, Morir (0.1 cada uno)

- **[0.60] Cámara**
  - (0.10) Fija, permite ver todo el tablero
  - (0.50) Se acerca y enfoca al jugador al morir y ganar

- **[1.60] Enemigo & Interacciones**
  - (0.50) Ataque: Enemigo mata jugador al tocarlo 
  - (0.20) Acción: Enemigo se destruye al clickearlo
  - (0.60) Aparición: Constante con el tiempo, indicando su celda antes de aparecer. (No deben aparecer dentro de otro enemigo o del jugador)
  - (0.30) Sonido: Aviso, Aparición, Muerte (0.1 cada uno)

- **[0.60] Tablero**
  - (0.60) Al menos 3 tableros distintos y no triviales de resolver (0.40 el primer tablero, 0.10 el segundo y 0.10 tercero)

- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menú)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menú. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Salir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - La rotación del jugador es una animación interpolada (no se teletransporta a la siguiente posición)
