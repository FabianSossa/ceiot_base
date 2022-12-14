# Ejercicio CiberKillChain - Defensa


## Alumno

Fabian Dario Caihuara Sossa

## Enunciado

Desarrollar la defensa en función del ataque planteado en orden inverso.

## Resolución

### Ciber Kill Chain :

#### Actions on Objectives

- Medida de prevencion, capacitar a los usuarios finales sobre como debe cambiar una contraseña en caso de necesitarlo y poner advertencias para que los clientes no caigan en algun engaño donde brinden sus contraseñas ante un ataque de phishing o smishing.
- Uso de herramientas IDS/IPS para la deteccion de comportamientos anomalos.
- Definicion de permisos minimos y limitacion de conexion enrantes y salientes de los distintos componentes en la nube.

#### Command and Control

- Monitorear la ejecucion de procesos en los embebidos y en el  concentrador Raspberry PI.
- Uso de versiones superiores de raspberry PI 3+.

#### Installation

- Uso de doble factor de autenticación para el usuario.
- Realizar un control y log de logueo de region de cada usuario para identificar posibles infiltraciones.
- Configurar permisos de autenticacion customizados en la versión de SO de Raspberry.

#### Exploitation

- Mantener actualizado el SO de la Raspberry y firmaware del microcontrolador ESP32.
- Usar protocolo TLS 1.2 en adelante para la comunicación.

#### Delivery

- Reviso los usuarios con rol de administrador. Procedo a revisar el log de login y actividad. Intento detectar cual fue el usuario hackeado.
- Encriptar las comunicaciones de los datos de los sensores de los cultivos.

#### Reconnaissance

- Luego del análisis y evaluación del ataque, genero una acción en conjunto con el sector de seguridad informática para implementar a la brevedad un software adecuado para detección de anomalías y generación de alertas ante comportamientos fuera de lo común de los administradores.

- Implemento una nueva política de seguridad que obligue al cambio de contraseñas como mínimo cada 3 meses y mantengo actualizada la lista de administradores.

