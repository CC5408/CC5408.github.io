---
title: Hito 0
nav_order: 0
layout: page
---

# Hito 0

Como primer proyecto deben realizar un videojuego de manera individual utilizando el motor Godot. El juego debe pertenecer a una de las cuatro categorías listadas a continuación y contener al menos los requerimientos enunciados. Al final de este documento se pueden encontrar las rúbricas de evaluación.

## Opciones de Proyecto

### **1. Platformer**

El juego consiste en un personaje que puede moverse, saltar y aplastar enemigos.


Debe tener al menos las siguiente escenas:

#### Jugador

El jugador debe ser capaz de moverse de izquierda a derecha y saltar. Si colisiona con un enemigo con los pies, mientras va cayendo, debe dañarlo / destruirlo y al mismo tiempo rebotar. Si choca de otra manera con un enemigo, entonces debe recibir daño / destruirse.
Debe tener al menos animaciones de idle, correr y salto. Debe tener un sonido al aplastar enemigos y otro sonido al saltar.

#### Enemigo

El enemigo no necesariamente debe ser capaz de moverse. Debe dañar / destruir al jugador si ocurre una colisión, a menos que esta se produzca desde arriba.

#### Nivel

El nivel debe contener plataformas sobre las cuales se encuentre el jugador y el / los enemigos.

---

### 2. Shooter

El juego consiste en una nave que se mueve de izquierda a derecha y dispara proyectiles hacia arriba, los cuales dañan / destruyen enemigos. Si colisiona con un enemigo debe recibir daño / destruirse.

Debe tener al menos las siguiente escenas:

#### Jugador

El jugador debe ser capaz de moverse y disparar.
Debe tener al menos animaciones de idle, movimiento, disparo y sonido al disparar.

#### Proyectil

El proyectil debe moverse en la dirección que fue disparado y al colisionar con un enemigo lo tiene que dañar / destruir.
Debe tener sonido al chocar con un enemigo.

#### Enemigo

El enemigo no necesariamente debe ser capaz de moverse. Tiene que ser destruible por un proyectil y dañar al jugador en caso de colisión.

#### Nivel

El nivel debe contener al jugador y a el / los enemigos. También debe poseer bloques con los que el jugador y proyectiles colisionen.

---

### 3. Arcade

El juego consiste en un personaje que puede moverse, recolectar consumibles y ser destruido por enemigos.

Debe tener al menos las siguiente escenas:

#### Jugador

El jugador debe ser capaz de moverse en todas direcciones. Si colisiona con un consumible debe recolectarlo y al colisionar con un enemigo deber ser destruido.
Debe tener al menos animaciones de idle, movimiento, recolectar y sonido al recolectar y ser destruido.

#### Consumible

El consumible debe poder ser recolectado por el jugador. Una vez recolectado desaparece de la pantalla.

#### Enemigo

El enemigo no necesariamente debe ser capaz de moverse. Si colisiona con el jugador, debe destruirlo.

#### Nivel

El nivel debe contener al jugador, a el / los consumibles y enemigos. También debe poseer muros con los que el jugador puede colisionar.

---

### 4. Lógica

El juego consiste en un tablero formado de varias celdas que pueden estar vacías o tener una bomba. Si el jugador hace click en una celda con una bomba, se acaba el juego.

Debe tener al menos las siguiente escenas:

#### Tablero

El tablero se debe generar al iniciar el juego, y consiste en una grilla formada por celdas.

#### Celda

Una celda puede contener una bomba o estar vacía. Al hacer click se revela, si tiene bomba la celda debe explotar y se acaba el juego, si está vacía se muestra un número que indique la cantidad de bombas que rodean la celda. De igual manera, al hacer click secundario en una celda no revelada, se pone / saca una bandera, la cual al estar presente impide revelar la celda. Debe tener animaciones de revelar, explosión y bandera.

#### Nivel

En el nivel debe estar el tablero. También debe exister la opcion de cambiar su número de filas y columnas.

## Entrega
Deben crear un proyecto en [itch.io](https://itch.io):
- La página de itch.io **debe ser pública**. *Recomendación:* Revisar la entrega en modo incognito.
- Subir un **ejecutable generado por Godot**, no el proyecto de Godot. *Recomendación:* Decargar el juego de la página de itch.io y revisar que funcione.
- Incluir **los controles de su juego** en la página.
### Importante
- Si el equipo docente no puede acceder a una carácteristica (por ejemplo, implementaron el daño de los enemigos pero no hay enemigos en el nivel) **se hará descuento como si no estuviese implementado**.
- **No está permitido usar assets con copyright**. Deben dar créditos a todos los assets que usen según las licencias correspondientes.

Es factible crear variaciones de los juegos mientras estén dentro de las mismas 4 categorías e incluyan los elementos mínimos enunciados. Por ejemplo es válido hacer un platformer en que aplastes botones para abrir puertas y existan pinchos en el suelo con los que morir en vez de tener enemigos, o un shooter donde seas un personaje que dispara balas contra enemigos o un arcade que sea similar al juego snake. Ante cualquier duda sobre alguna idea alterna, cambio o variación, consúltenlo con el equipo docente. 
