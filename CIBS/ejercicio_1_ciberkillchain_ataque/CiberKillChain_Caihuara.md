# Ejercicio CiberKillChain - Ataque



## Alumno

Fabian Dario Caihuara Sossa

## Enunciado

Armar una cyberkillchain usando técnicas de la matriz de Att&ck para un escenario relacionado al trabajo práctico de la carrera.

## Datos trabajo práctico

link

El trabajo práctico tiene como principal objetivo unir tecnologıas IoT (Internet of Things) con
el cultivo hortícola en huertos urbanos, que con el tiempo se están volviendo mas comunes en
terrazas y balcones.

Las razones de esta nueva moda urbana son diversas. El creciente uso de productos quımicos
en los cultivos tradicionales, ası como el crecimiento del mercado de productos transg ́enicos son
un motivo de reflexión que está incrementando la venta de productos ecológicos en la sociedad.

Se desarrollar ́a una solucion capaz de brindar el servicio a invernaderos de distintos clientes,
ofreciendo una herramienta centralizada, donde se pueda consultar las distintas metricas
definidas por el usuario.

Se desarrollara la solucion en entornos propios usando tecnolog ́ıas de software libre, la conexión
de los dispositivos será de manera inalámbrica (Wi-Fi).

Los datos recolectados por los sensores son enviados al servidor, ante eventuales cortes de
comunicación debe existir un mecanismo de retención de la informacion, la comunicación cliente-
servidor se lleva a cabo a través del protocolo MQTT.

En la figura 1 se presenta el diagrama en bloques del sistema. Se observa que el módulo
Wi-Fi se comunica y envia datos al servidor, ya sea de variables y/o estado de actuadores
conectados al equipo. Una base de datos administrar ́a la información de todos los equipos
conectados al servidor, se debera ademas visualizar el estado actual en un tablero, enviar alertas
y notificaciones y gestionar la información mediante una API, para permitir al usuario descargar
los datos en algún formato definido como csv, xlsx, pdf, etc.

### Instrucciones

El escenario debe ser con el sistema ya funcionando en el futuro.

Debe ser en primera persona, es el punto de vista del atacante.

Es recomendable hacer dos o tres pasadas, en la primera la idea, en las siguientes refinamientos especificando las técnicas.
PURO ATAQUE, nada de andar pensando cómo corregir nada.

Para cada etapa, si hay varias medidas posibles, ordenar dejando para lo último lo que se va a hacer en el siguiente paso.

### Ejemplo adaptado a un juego de guerra inventado:

* Reconnaissance
  - Imagen satelital identifica una pista de aterrizaje.
  - Espías dicen que por el puerto entra el combustible.
  - Espías locales dicen que la playa cercana no tiene buena vigilancia.

* Weaponization
  - Puedo preparar un bombardeo.
  - Puedo preparar un equipo de comandos de sabotage.
  
* Delivery
  - Envío al equipo de sabotage a la playa cercana en submarino.
  
* Exploit
  - El equipo logra desembarcar sin incidentes en la playa.
  
* Installation  
  - El equipo se hace pasar por una compañia de circo como camuflaje.

* Command & Control
  - Podría utilizar palomas mensajeras.
  - Podría utilizar Super High TeraHertz Radio que el adversario no puede detectar, eso haré.
  
* Actions on Objectives
  - El equipo de comandos provoca daños menores en las cañerías.
  - El equipo de comandos coloca minas en el puerto.
  



## Resolución


  

