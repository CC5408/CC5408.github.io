---
title: Pauta
parent: Hito 0
nav_order: 0
layout: page
---

# Pauta Hito 0

## 1. Platformer

- **[1.75] Jugador**
  - (0.50) Movimiento: Horizontal
  - (0.50) Movimiento: Salto
  - (0.15) Sonido: Salto
  - (0.60) Animaciones: Idle, Correr, Salto (0.2 cada una)
  
- **[2.50] Enemigo & Interacciones**
  - (1.00) Ataque: Jugador mata enemigo (colisión desde arriba)
  - (1.00) Ataque: Enemigo mata jugador (colisión desde otros lados)
  - (0.40) Movimiento: Rebote del jugador al matar enemigo
  - (0.10) Sonido: ataque direccional (aplastar enemigo)
  
- **[0.75] Nivel**
  - (0.75) Nivel con plataformas visibles. (Incluye colisiones)
  
- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menu)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menu. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Sal  ir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - Página de itch.io bonita/creativa

## 2. Shooter

- **[2.00] Jugador**
  - (0.50) Movimiento: Horizontal
  - (0.75) Animaciones: Idle, Movimiento, Disparo (0.25 cada una)
  - (0.50) Proyectil: Jugador puede disparar (crear un proyectil)
  - (0.25) Sonido: Disparo
  
- **[2.25] Enemigo & Interacciones**
  - (0.25) Proyectil: Se mueve
  - (1.00) Ataque: Proyectil mata enemigo
  - (1.00) Ataque: Enemigo mata jugador
  
- **[0.75] Nivel**
  - (0.75) Nivel con bloques visibles. (Incluye colisiones)
  
- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menu)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menu. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Sal  ir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - Página de itch.io bonita/creativa

## 3. Arcade

- **[1.75] Jugador**
  - (1.00) Movimiento: en todas las direcciones
  - (0.75) Animaciones: Idle, Mobimiento, Recolección (0.25 cada una)

- **[2.50] Enemigo & Interacciones**
  - (1.00) Consumible: se puede recoger
  - (0.25) Sonido: Recolección de consumible
  - (1.00) Ataque: Enemigo mata jugador
  - (0.25) Sonido: Muerte de jugador
 
  - **[0.75] Nivel**
  - (0.75) Nivel con muros visibles. (Incluye colisiones)
  
- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menu)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menu. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Sal  ir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - Página de itch.io bonita/creativa


## 4. Lógica

- **[0.35] Tablero**
  - (0.35) Revelar todas las celdas al perder
  
- **[3.9] Celda**
  - (1.00) Interarcción: Vacía (Revelar el número de bombas adyacentes)
  - (1.00) Interarcción: Bomba
  - (1.00) Acción: Bandera
  - (0.60) Animaciones: Vacía, Bomba, Bandera (0.2 cada una)
  - (0.30) Sonido: Vacía, Bomba, Bandera (0.1 cada una)
  
- **[0.75] Nivel**
  - (0.75) Nivel con tablero visible. Debe permitir cambiar la cantidad de filas y columnas.
  
- **[1.0] Interfaz**
  - [0.20] Menú principal.
    - (0.10) Acceder al nivel
    - (0.10) Salir del juego
  - [0.35] Menú de pausa.
    - (0.10) Continuar. (El juego debe pausarse al abrir el menu)
    - (0.10) Reiniciar. (El juego debe continuarse al poner continuar)
    - (0.10) Volver a menu. (Bug común: no debe seguir pausado al volver al menú principal)
    - (0.05) Sal  ir del juego
  - [0.45] Créditos. 
    - Debe mencionar assets usados según la licencia que tengan

- _[+5 décimas] Bonus_
  - Página de itch.io bonita/creativa
