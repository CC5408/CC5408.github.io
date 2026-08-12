---
title: Hito 0
nav_order: 0
layout: page
---

# Hito 0

Como primer proyecto deben realizar un videojuego en 3D de manera individual utilizando el motor Godot. El juego debe pertenecer a una de las cuatro categorías listadas a continuación y contener al menos los requerimientos enunciados. Al final de este documento se pueden encontrar las rúbricas de evaluación.

## Opciones de Proyecto

### **1. Platformer**

El juego consiste en un personaje que puede moverse, saltar y aplastar enemigos.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador debe ser capaz de moverse y saltar. Si colisiona con un enemigo con los pies, mientras va cayendo, debe dañarlo / destruirlo y al mismo tiempo rebotar. Si choca de otra manera con un enemigo, entonces debe recibir daño / destruirse.
Debe tener al menos animaciones de idle, correr, salto y rebote.
Debe tener un sonido al aplastar enemigos y otro sonido al saltar.

#### Cámara

La cámara debe seguir al jugador y mostrar hacia donde este quiere moverse.
La posición y orientación de la cámara se deben derivar del mismo movimiento, no se debe usar el mouse para mover la cámara.
No es válido que esté fija a la parte de atrás del jugador.

#### Enemigos

Los enemigos no necesariamente debe ser capaces de moverse. Deben dañar / destruir al jugador si ocurre una colisión, a menos que esta se produzca desde arriba.
Deben aparecer más enemigos a lo largo del tiempo. Los enemigos no deben aparecer dentro de otro enemigo.

#### Nivel

El nivel debe contener un piso y al menos tres plataformas sobre las cuales se encuentre el jugador y los enemigos.

---

### 2. Shooter

El juego consiste en un personaje que puede moverse, saltar y disparar proyectiles, los cuales dañan / destruyen enemigos. Si colisiona con un enemigo debe recibir daño / destruirse.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador debe ser capaz de moverse, saltar y disparar.
Debe tener al menos animaciones de idle, correr, salto, disparo y apuntar.
Debe tener un sonido al disparar y otro sonido al saltar.

#### Cámara

La cámara puede ser primera o tercera persona. Esta debe encontrarse fija al jugador.
Se debe poder apretar un botón para apuntar con el arma, es decir, mover y/o hacer zoom a la cámara.

#### Proyectil

El proyectil debe moverse en la dirección que fue disparado y al colisionar con un enemigo lo tiene que dañar / destruir.
Debe tener sonido al chocar con un enemigo.

#### Enemigos

Los enemigos no necesariamente deben ser capaz de moverse. Tienen que ser destruibles por un proyectil y dañar al jugador en caso de colisión.

#### Nivel

El nivel debe contener al jugador y a los enemigos. También debe poseer bloques / muros con los que el jugador y proyectiles colisionen.

---

### 3. Racing

El juego consiste en un auto que se puede mover y chocar con enemigos.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador debe ser capaz de acelerar y frenar e ir en reversa.
Si colisiona con un enemigo a baja velocidad debe recibir daño / ser destruido.
Si colisiona con un enemigo a alta velocidad debe destruirlo.
Debe poseer luces delanteras que pueda prender y apagar con un botón, y luces traseras que se prendan al frenar y retroceder.
Debe tener sonido de avance, retroceso, bocina y choque.

#### Cámara
Tienen que haber al menos tres cámaras.
Una en tercera persona que permita ver al auto desde atrás. Su posición y orientación es determinada por la posición del auto y no se mueve con el mouse.
Una en primera persona donde se vea el auto desde dentro.
Una que permita ver hacia atrás.

#### Enemigos

Los enemigos no necesariamente deben ser capaz de moverse. Si colisionan con el jugador a alta velocidad son destruidos y a baja velocidad lo dañan / destruyen.
Luego de ser destruido, un enemigo debe volver a aparecer en el mismo lugar, siempre y cuando no aparezca dentro el jugador.

#### Nivel

El nivel debe contener al jugador y a los  enemigos. Debe tener elevaciones de terreno y/o rampas. No puede ser solo un plano infinito y nada más.

---

### 4. Lógica

El juego consiste en un tablero formado de varias celdas que pueden estar vacías o tener una bomba. Si el jugador hace click en una celda con una bomba, se acaba el juego y se revelan todas las celdas.

Debe tener al menos las siguiente escenas:

#### Tablero

El tablero se debe generar al iniciar el juego. Consiste en una grilla de celdas, compuesta por una cantidad ajustable de filas y columnas.

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
