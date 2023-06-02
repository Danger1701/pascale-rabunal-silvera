# Informe de obligatorio ISA (Sprint 3)

## Fecha de entrega: 02/06/2023

---------------------------------------------------------------------------

## Materia: INGENIERIA DE SOFTWARE AGIL 1

### Equipo 5 - Mini proyecto

### Estudiantes: Juan Manuel Rabuñal - Maximiliano Pascale - Sebastian Silvera

---------------------------------------------------------------------------

### Herramienta para gestión del proyecto

#### Azure Devops: <https://dev.azure.com/Pascale-Rabunal-Silvera/Mini%20Proyecto%202023>

### Versionado

#### Repositorio Github: <https://github.com/ORT-ISA1/pascale-rabunal-silvera>

---------------------------------------------------------------------------

### Sprint planning

Fecha: 22/05/2023
Hora: 18:00
Duración: 1h

Objetivos de la misma:

- Corregir los issues de la devolución
- Terminar el prototipo funcional
- Funcionalidad Juego aleatorio
- Funcionalidad de notificaciones

En dicho orden debe ser la prioridad

Dinámica:
Leímos todas las issues a corregir y realizamos puestas en común de cómo mejorarlo.
Luego comenzamos la estimación donde nos pusimos de acuerdo luego de votar, si hay diferencia entre las tarjetas en algunas ocasiones optamos por dejar el promedio y el otras elegimos un valor justificado por el argumento de el que lo voto.

En la carpeta "Evidencia" hay una carpeta llamada Sprint Planning donde están todas las fotos de la evidencia de la planning poker.

---------------------------------------------------------------------------

### Sprint daily

A continuación vamos a poner una grilla personal donde fuimos registrando lo sucedido en las dailys.
Dejando en evidencia las tareas en las que estamos trabajando, las que ya finalizamos, si estamos con algún bloqueo y los temas hablados en la reunión.

![image](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/64442147/0b6b00ad-6f8d-43ff-82b0-c66481990b82)

---------------------------------------------------------------------------

## Identificación del problema a resolver

### Propuesta de valor

Experiencia de usuario intuitiva: La aplicación se destacará por ofrecer una interfaz de usuario fácil de usar, con un proceso de reserva rápido y sencillo, priorizando la experiencia del usuario, para que cualquier persona, independientemente de su edad o habilidades tecnológicas, pueda navegar y reservar canchas sin dificultad.

Funcionalidad de Modo Juego Aleatorio: Una característica única de la aplicación será el Modo Juego Aleatorio, donde los usuarios podrán unirse a actividades deportivas junto con otros usuarios de forma aleatoria. Esto fomentará la interacción social, permitiendo que los jugadores se conozcan y disfruten de la actividad deportiva en un entorno inclusivo.

Lista de canchas favoritas y recomendaciones personalizadas: La aplicación permitirá a los usuarios guardar sus canchas favoritas para acceder rápidamente a ellas en el futuro.

Interacción social y funciones de invitación: La aplicación facilitará la interacción social entre los usuarios, permitiéndoles invitar a amigos y contactos a unirse a sus reservas o juegos. Esto fomentará la participación en grupo y hará que la experiencia deportiva sea más divertida y social.

---------------------------------------------------------------------------

### Control de versiones

Se crea el repositorio <https://github.com/ORT-ISA1/pascale-rabunal-silvera>

Se trabaja con dos ramas “main” y “develop”, en esta última cada miembro del equipo trabajará de acuerdo a las buenas prácticas aprendidas.

Trabajaremos sobre “develop”, donde cada miembro creara sus ramas y trabaja sobre ellas. Una vez completado el desarrollo deberá mergear a “develop”.

Al finalizar cada sprint “develop” será mergeada a “main”.

Borrar las ramas que ya integradas

![Repositorio del proyecto_01](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/df8a0c9e-c365-4b71-922a-aac28feb8582)

#### Descripción de los PRs

En función a las recomendaciones utilizaremos el siguiente articulo para definir como deben ser las descripciones de los PRs

Articulo: <https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository>

Puntos clave para redactar la descripción de los PRs:

- Propósito del PR: Explicar de manera clara el propósito del PR, describiendo el problema que soluciona, la función que agrega o la mejora que implementa. Esto brinda contexto a los revisores y colaboradores.

- Cambios realizados: Detallar específicamente los cambios efectuados, junto con cualquier detalle relevante.

- Impacto y dependencias: Es importante mencionar si el PR tiene algún impacto en otras partes de las funcionalidades existentes.

- Si el PR depende de otros PRs, debe ser informado.

- Instrucciones para revisores: Proporciona orientación clara a los revisores sobre cómo evaluar y probar los cambios. Esto puede incluir detalles sobre la configuración necesaria, comandos específicos que deben ejecutarse u otros requisitos relevantes.

- Capturas de pantalla (opcional): Si es relevante, incluir capturas de pantalla que muestren visualmente los cambios realizados. Esto puede ser especialmente útil en cambios relacionados con la interfaz de usuario.

#### Nombre de ramas, commits y PRs

En función a las recomendaciones utilizaremos el siguiente articulo para definir como deben ser los nombre de ramas, commits y PRs

<https://code.erpenbeck.io/git/2021/03/01/git-naming-conventions/>

1. Para nombrar las ramas:

    - Los nombres deben ser descriptivos y concisos.
    - Utilizar minúsculas y separa las palabras con guiones.
    - Agregar prefijos como "feature/" para nuevas características, "bugfix/" para correcciones de errores, "hotfix/" para soluciones urgentes, entre otros.
    - Evitar nombres genéricos o ambiguos y eligir nombres que reflejen el propósito o contenido de la rama.

![Repositorio del proyecto_02](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/be2e62d1-75c2-4efc-8eb0-a28738105797)

2. Para nombrar los commits:

    - Los nombres deben ser claros y descriptivos.
    - Utilizar verbos en tiempo presente para indicar la acción realizada, seguidos de una breve descripción del cambio.
    - Limitar la longitud a unos 50 caracteres.
    - Evitar agregar información innecesaria o detalles irrelevantes.

3. Para nombrar los Pull Requests:

    - Comenzar con un prefijo que indique el propósito, como "Feature:", "Fix:", "Docs:", etc.
    - Continuar con una breve descripción del cambio o problema que aborda.
    - Utilizar un estilo conciso y claro.
    - Evitar incluir información técnica compleja en el título del PR, reservar esos detalles para la descripción del PR.

---------------------------------------------------------------------------

#### Pruebas de usabilidad YaCancha por usuarios

Pruebas de usabilidad que aplicaremos, utilizando como guía <https://www.nngroup.com/articles/better-usability-tasks/>:

Prueba de navegación: Evaluar la facilidad con la que los usuarios pueden moverse por la aplicación, acceder a diferentes secciones y utilizar las funciones de navegación, como botones de retroceso y menús desplegables.

Prueba de registro y autenticación: Verificar si los usuarios pueden registrarse de manera sencilla, completar los campos requeridos y acceder a sus cuentas con facilidad. Identificar posibles obstáculos o errores en el proceso de inicio de sesión.

Prueba de búsqueda de canchas: Evaluar la eficacia de la función de búsqueda de canchas, incluyendo la usabilidad de los filtros y la precisión de los resultados obtenidos.

Prueba de reserva de canchas: Verificar la facilidad con la que los usuarios pueden seleccionar una cancha, elegir una fecha y hora de reserva, y completar el proceso de reserva sin confusiones ni dificultades.

Prueba del modo de Juego Aleatorio: Evaluar la facilidad con la que los usuarios pueden seleccionar el modo de juego aleatorio, ver el progreso de otros jugadores y unirse a los partidos. Identificar posibles problemas de visualización de información o dificultades en la interacción con otros usuarios.

#### Encuesta de usabilidad YaCancha por usuarios

#### Resultados de encuesta de usabilidad

---------------------------------------------------------------------------

### Prototipo Funcional

Se presenta el link al prototipo funcional de Figma.

<https://www.figma.com/proto/hRuzPMFiU7WcV1k9be08U7/Prototipo?type=design&node-id=431-714&scaling=scale-down&page-id=0%3A1&starting-point-node-id=28%3A46>

### Crear Juego Aleatorio

| Titulo | Enlace |
|-------------------|--------|
| Modificación Inicio | ![Modificacion Inicio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/3123caf1-0ac5-4feb-a1da-18a6cfa9f114) |
| JuegoAleatorio | ![JuegoAleatorio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/bdef91ee-854e-4051-9b23-0489ecd3b872) |

### Unirse a Juego Aleatorio

| Descripción              | Enlace                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------|
| Universe A Juego Aleatorio | ![Universe A Juego Aleatorio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/0be97ba9-b349-4a8c-b0b2-88dd46262bc9) |
| Unión Correcta            | ![Unión Correcta](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/fa45f289-afc5-4ecf-8c10-0b90b0b8c173)                    |

### Notificaciones

Se agrega un menu de notificaciones donde el usuario puede ver distinto tipos de notificaciones ademas de una visualización sencilla de cuales notificaciones ya visualizo y cuales aun no.

| Titulo modificación | Enlace |
|-------------------|--------|
| Notificaciones | ![Notificaciones](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/b01a02a9-c9ca-4155-82bd-d17d0c9e94cd) |

### Update Pantalla de Reserva

| Descripción                    | Enlace                                                                                                       |
|-------------------------------|-------------------------------------------------------------------------------------------------------------|
| Update Pantalla de Reserva     | ![Update Pantalla de Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/114319c1-1c25-4fd4-8861-a3865c62e218)        |

---------------------------------------------------------------------------

## Sprint Backlog

Evidencia del Sprint Backlog

![Sprint Backlog_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/45d0fb46-17b1-48a9-9093-303646a4b687)

## Boards

![Boards_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/0b5aa47a-54aa-4f70-8848-3a573a9c1ee4)

## Burndown Trend

![Burndown Trend _1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/f35ea847-11cc-483e-8bbc-bc1f6e2a9691)

![Burndown Trend _2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/71778460-be63-4aef-a672-7fae2f3f69aa)

## Dedicación del equipo

### Dedicación por integrantes del equipo

#### Maximiliano Pascale

![Horas_Pascale](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/c771fb49-c63c-4a63-9d6b-85ea28ec1f00)

#### Juan Manuel Rabuñal

![Horas_Rabunal](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/9db0c9b2-5d55-44b6-b41b-d65357e21e89)

#### Sebastian Silvera

![Horas_Silvera](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/8fae9542-56c4-47ce-b2ed-a608bcfa6821)

### Dedicación equipo

Dedicación de horas acumuladas por el equipo.

![Horas_Equipo](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/44a5c6f7-7bd5-442e-ae5a-5fb925b71192)

![Horas_Equipo_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/a2e4e7a3-b274-47c5-90cc-2fa4e854aa5f)

## Evidencia de manejo de versiones

A continuación se demuestra evidencia del uso de los principios de manejo de versiones adoptados por el equipo.

![Control version_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/cc9c564e-ee87-441e-8f4d-0e49793112fc)

![Control version_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/8dac9fc4-bdbe-4e9a-b766-ccb21b51d930)
