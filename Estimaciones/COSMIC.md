# Estimaciones COSMIC

**Sprint #2:**

Durante este sprint, el equipo se enfocó en el desarrollo del prototipo en Figma.

## Actividades:

### Diseño de UI:

- Interfaz de login
- Interfaz de mensajería
- Homepage
- Edición de perfiles
- Puntos de función

### Para el cálculo de puntos de función COSMIC, se definió que se trabajaría con el sprint #2, enfocado al desarrollo de UI (Prototipo de Figma), ya que fue el sprint en el que se involucraron en mayor medida los requerimientos funcionales.

## Interfaz 1: RF001

**The app has a login in which users can create an account, access with an already existing account, or through another platform’s account (Google, Apple, Facebook), as well as a "forgot password" option with e-mail verification.**

**Proceso funcional: Crear una cuenta nueva (no Google, Apple o Facebook)**
- Movimiento de datos:
  - Entrada: Presionar el botón crear una cuenta
  - Entrada: Datos del usuario nuevo (nombres, e-mail, fecha de nacimiento, contraseña y confirmación) y aceptar términos de uso.
  - Entrada: Presionar el botón de confirmación de creación de cuenta.
  - Salida: Se presenta la pantalla de crear una cuenta.
  - Salida: Se accede a la homepage.
- Puntos de función COSMIC: 5

**Proceso funcional: Acceder con Google, Apple o Facebook**
- Movimiento de datos:
  - Entrada: Presionar el botón para acceder con Google, Apple o Facebook.
  - Entrada: Seleccionar una cuenta.
  - Entrada: Se presiona el botón “Continuar” para ingresar en otra cuenta.
  - Salida: Se muestra la opción “TuriAmigos quiere acceder a (Plataforma)”.
  - Salida: Mostrar pantalla de acceso.
  - Salida: Acceder a la homepage.
- Puntos de función COSMIC: 6

**Proceso funcional: Login con una cuenta existente**
- Movimiento de datos:
  - Entrada: Presionar el botón “Login”.
  - Salida: Mostrar Pantalla de login.
  - Salida: Mostrar pantalla de Homepage (Radar).
- Puntos de función COSMIC: 3

## Interfaz 2: RF-002

**Implement a primary user interface able to detect nearby tourists. Display a box with basic information about them and being able to send a friend request.**

**Proceso funcional: Buscar turistas**
- Movimiento de datos:
  - Entrada: Activar o desactivar el radar para buscar turistas.
  - Salida: Aviso de turistas cercanos.
- Puntos de función COSMIC: 2

**Proceso funcional: Ver perfil de otro usuario**
- Movimiento de datos:
  - Entrada: Presionar el icono para ver el perfil de un usuario.
  - Salida: Se muestra la pantalla de perfil de otro usuario con su información pública.
- Puntos de función COSMIC: 2

**Proceso funcional: Agregar a un usuario para chatear**
- Movimiento de datos:
  - Entrada: Presionar el botón de la flecha en la pantalla de perfil de un usuario.
  - Salida: Se abre la pantalla de chat para enviar mensaje a otro usuario.
- Puntos de función COSMIC: 2

## Interfaz 3: RF003

**The application has an editable profile system, in which users can verify others' identities, such as origin, number of trips, age, gender.**

**Proceso funcional: Editar el perfil**
- Movimiento de datos:
  - Entrada: Botón “Perfil”.
  - Entrada: Botón “Editar perfil”:
  - Salida: Datos del perfil, calificación, etc.
  - Salida: Edición de datos del perfil: Edad, nombre, género, Nacionalidad, Viajes, etc.
- Puntos de función COSMIC: 4

## Interfaz 4: 

**RF: Include a chat library in which users can direct message others, with the purpose of organizing group trips and facilitating communication for user activities.**
**Implement a message request interface, in which users can manage their message requests.**
**Enable users to share any location through direct messages (theirs or any other) in order to help them establish a reunion point or make suggestions to others.**

**Proceso Funcional: Utilizar el chat** 
- Movimiento de datos:
  - Entrada: Escritura del mensaje.
  - Salida: Mensaje del otro usuario.
  - Entrada: Solicitar reunirse con otro usuario.
  - Salida: Recibir una solicitud para reunirse.
  - Entrada: Enviar una ubicación.
  - Salida: Pantalla con mapa y opciones disponibles.
  - Entrada: Enviar ubicación.
  - Salida: Icono de ubicación enviada.
- Puntos de función COSMIC: 8

**Proceso funcional: Navegar a través del sistema de mensajería**
- Movimiento de datos:
  - Entrada: Presionar el icono de uno de los usuarios disponibles.
  - Salida: Pantalla con iconos de usuarios disponibles con nombre y foto.
  - Entrada: Botón para visualizar las solicitudes de mensaje.
  - Salida: Pantalla con las solicitudes recibidas.
  - Entrada: Aceptar o rechazar una solicitud de mensaje.
  - Salida: Se abre el chat con el usuario aceptado.
- Puntos de función COSMIC: 6

**Total puntos de función COSMIC: 38**

## Esfuerzo:

Obtuvimos un total de 38 CFP para este Sprint.

## Estimación de costos:

Referencia utilizada para salarios (Diseñador UI/UX junior en México): [Glassdoor](https://www.glassdoor.com.mx/Sueldos/junior-ux-ui-designer-sueldo-SRCH_KO0,21.htm#:~:text=¿Cuánto%20gana%20un%20Junior)

Considerando un aproximado de 200 horas de trabajo mensuales, y un salario promedio de $22,000 pesos al mes para UI/UX designer Junior, entonces:

**Salario/hora = $22,000 / 200 horas = $110/hora**

## Integrantes (rol) y Salario-hora:

| Integrantes        | Rol       | Salario-hora | Horas trabajadas en el sprint | Total salario |
| ------------------ | --------- | ------------ | ----------------------------- | ------------- |
| Daniela Villarino  | Designer  | $110         | 6                             | $660          |
| Daniel Corona      | Designer  | $110         | 6                             | $660          |
| Damian Villares    | Designer  | $110         | 6                             | $660          |
| Axel Morales       | Designer  | $110         | 6                             | $660          |
| Jefte Chunab       | Designer  | $110         | 6                             | $660          |
| Rodrigo Farfán     | Designer  | $110         | 6                             | $660          |
| **Total**          |           |              | **36 horas**                  | **$3,960**    |

## Costo por punto de función:

Una vez tenemos el costo por Sprint del equipo de desarrollo ($3,960), se puede estimar el costo por punto de función:

**Costo/CFP = (Costo/Sprint) / (CFP/Sprint) = $3,960 / 38CFP = $104.21 / CFP.**

## Estimación de la duración del Sprint:

Al tratarse de un prototipo de desarrollo, aproximamos para este Sprint un promedio de 0.869 horas/CFP:

**0.869 horas/CFP x 38CFP = 33.07 Horas.**