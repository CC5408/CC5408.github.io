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

El jugador debe ser capaz de moverse en dos ejes y saltar en el eje restante.\
Si colisiona con un enemigo con los pies, mientras va cayendo, debe dañarlo y/o destruirlo y al mismo tiempo rebotar. Si choca de otra manera con un enemigo, entonces debe recibir daño y/o destruirse.\
Debe tener al menos animaciones de idle, correr, salto y rebote.\
Debe tener un sonido al aplastar enemigos y otro sonido al saltar.

#### Cámara

La cámara debe seguir al jugador y mostrar hacia donde este quiere moverse.\
La posición y orientación de la cámara se deben derivar del mismo movimiento, no se debe usar el mouse para mover la cámara.\
No es válido que esté fija a la parte de atrás del jugador.

#### Enemigos

Los enemigos no necesariamente debe ser capaces de moverse. Deben dañar / destruir al jugador si ocurre una colisión, a menos que esta se produzca desde arriba.\
Deben aparecer más enemigos a lo largo del tiempo. Los enemigos no deben aparecer dentro de otro enemigo o del jugador.

#### Nivel

El nivel debe contener un piso y al menos tres plataformas sobre las cuales se encuentre el jugador y los enemigos.

---

### 2. Shooter

El juego consiste en un personaje que puede moverse, saltar y disparar proyectiles, los cuales dañan / destruyen enemigos. Si colisiona con un enemigo debe recibir daño / destruirse.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador debe ser capaz de moverse en dos ejes, saltar en el eje restante y disparar.\
Debe tener al menos animaciones de idle, correr, salto, disparo y apuntar.\
Debe tener un sonido al disparar y otro sonido al saltar.

#### Cámara

La cámara puede ser primera o tercera persona. Esta debe encontrarse fija al jugador y rotar con el mouse.\
Se debe poder apretar un botón para apuntar con el arma, es decir, mover y/o hacer zoom a la cámara.

#### Proyectil

El proyectil debe moverse en la dirección que fue disparado y al colisionar con un enemigo lo tiene que dañar / destruir.\
Debe tener sonido al chocar con un enemigo.

#### Enemigos

Los enemigos no necesariamente deben ser capaces de moverse. Tienen que ser destruibles por un proyectil y dañar al jugador en caso de colisión.

#### Nivel

El nivel debe contener al jugador y a los enemigos. También debe poseer bloques / muros con los que el jugador y proyectiles colisionen.

---

### 3. Racing

El juego consiste en un auto que se puede mover y chocar con enemigos.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador se mueve en dos ejes y debe ser capaz de acelerar y frenar e ir en reversa.
Si colisiona con un enemigo a baja velocidad debe recibir daño / ser destruido.\
Si colisiona con un enemigo a alta velocidad debe destruirlo.\
Debe poseer luces delanteras que pueda prender y apagar con un botón, y luces traseras que se prendan al frenar y retroceder.\
Debe tener sonido de avance, retroceso, bocina y choque.

#### Cámara

Tienen que haber al menos tres cámaras.\
Una en tercera persona que permita ver al auto desde atrás. Su posición y orientación es determinada por la posición del auto y no se mueve con el mouse.\
Una en primera persona donde se vea el auto desde dentro.\
Una que permita ver hacia atrás.

#### Enemigos

Los enemigos no necesariamente deben ser capaces de moverse. Si colisionan con el jugador a alta velocidad son destruidos y a baja velocidad lo dañan / destruyen.\
Luego de ser destruidos, y al pasar un tiempo, deben volver a aparecer, siempre y cuando no aparezcan dentro  del jugador u otro enemigo.

#### Nivel

El nivel debe contener al jugador y a los enemigos. Debe tener elevaciones de terreno y/o rampas. No puede ser solo un plano infinito y nada más.

---

### 4. Puzzle

El juego consiste en llegar desde una celda inicial a una final en un tablero.\
El personaje es un bloque de 1x2 que solo puede moverse al rotar sobre sus aristas en 90 grados.\
En el tablero deben aparecer enemigos que matan al jugador al tocarlo y pueden ser destruidos al clickearlos.

Debe tener al menos los siguientes elementos:

#### Jugador

El jugador es un bloque de 1x2 unidades. En cada estado, posee 4 direcciones de movimiento las que al realizarse provocan que este rote en 90 grados sobre la arista en esa dirección que está en contacto con el tablero.\
Si es que alguna parte del cuerpo del jugador se sale del tablero entonces este cae al vacío / muere y es teletransportado a la celda inicial.\
Si el jugador colisiona con la celda de meta entonces se avanza al siguiente tablero.\
Si el jugador colisiona con un enemigo, muere y es teletransportado a la celda inicial.\
Debe tener al menos animación de victoria y muerte.\
Debe tener un sonido al rotar, ganar y morir.

#### Cámara

La cámara es fija y permite ver todo el tablero.\
Debe acercarse y enfocar al jugador cuando muere y gana.

#### Enemigos

Los enemigos no deben ser capaces de moverse. Si colisionan con el jugador lo matan. Si el jugador les hace click, se destruyen.\
Deben aparecer constantemente con el tiempo, indicando su celda de aparición antes de hacerlo.\
Un enemigo no puede aparecer dentro de otro enemigo o dentro del jugador.\
Deben tener un sonido al avisar de su aparición, aparecer y morir.

#### Tablero

El tablero consiste en un conjunto de celdas organizadas en forma de grilla. Estas celdas deben estar conectadas entre si y proveer el piso por sobre el cual debe moverse el personaje y aparecer enemigos.\
La cantidad y posicionamiento de celdas debe producir un tablero que no sea trivial de resolver para el jugador.\
Se debe tener al menos 3 tableros distintos que puedan ser jugador en sucesión.


## Entrega
Deben crear un proyecto en [itch.io](https://itch.io):
- La página de itch.io **debe ser pública**. *Recomendación:* Revisar la entrega en modo incognito.
- Subir un **ejecutable generado por Godot**, no el proyecto de Godot. *Recomendación:* Decargar el juego de la página de itch.io y revisar que funcione.
- Incluir **los controles de su juego** en la página.
### Importante
- Si el equipo docente no puede acceder a una característica (por ejemplo, implementaron el daño de los enemigos pero no hay enemigos en el nivel) **se hará descuento como si no estuviese implementado**.
- **No está permitido usar assets con copyright**. Deben dar créditos a todos los assets que usen según las licencias correspondientes.

Es factible crear variaciones de los juegos mientras estén dentro de las mismas 4 categorías e incluyan los elementos mínimos enunciados. Por ejemplo es válido hacer un platformer en que aplastes botones para abrir puertas y existan pinchos en el suelo con los que morir en vez de tener enemigos, o un shooter donde los enemigos disparan y se tiene que esquivar, u otro juego de puzzle que incluya la aparición de elementos y manejos de cámara. Ante cualquier duda sobre alguna idea alterna, cambio o variación, consúltenlo primero con el equipo docente. 
