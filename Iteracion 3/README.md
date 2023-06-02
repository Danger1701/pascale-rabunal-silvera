# Informe de obligatorio ISA (Sprint 3)

## Fecha de entrega: 2/6/2023

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

A continuación vamos a poner una grilla personal donde fuimos registrando lo sucedido en las dailys
Dejando en evidencia las tareas en las que estamos trabajando, las que ya finalizamos, si estamos con algún bloqueo y los temas hablados en la reunión.

Juan Manuel Rabuñal

Maximiliano Pascale

Sebastian Silvera

---------------------------------------------------------------------------

### Control de versiones

Se crea el repositorio <https://github.com/ORT-ISA1/pascale-rabunal-silvera>

Se trabaja con dos ramas “main” y “develop”, en esta última cada miembro del equipo trabajará de acuerdo a las buenas prácticas aprendidas.

Trabajaremos sobre “develop”, donde cada miembro creara sus ramas y trabaja sobre ellas. Una vez completado el desarrollo deberá mergear a “develop”.

Al finalizar cada sprint “develop” será mergeada a “main”.

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

**1. Para nombrar las ramas:

    - Los nombres deben ser descriptivos y concisos.
    - Utilizar minúsculas y separa las palabras con guiones.
    - Agregar prefijos como "feature/" para nuevas características, "bugfix/" para correcciones de errores, "hotfix/" para soluciones urgentes, entre otros.
    - Evitar nombres genéricos o ambiguos y eligir nombres que reflejen el propósito o contenido de la rama.

**2. Para nombrar los commits:

    - Los nombres deben ser claros y descriptivos.
    - Utilizar verbos en tiempo presente para indicar la acción realizada, seguidos de una breve descripción del cambio.
    - Limitar la longitud a unos 50 caracteres.
    - Evitar agregar información innecesaria o detalles irrelevantes.

**3. Para nombrar los Pull Requests:

    - Comenzar con un prefijo que indique el propósito, como "Feature:", "Fix:", "Docs:", etc.
    - Continuar con una breve descripción del cambio o problema que aborda.
    - Utilizar un estilo conciso y claro.
    - Evitar incluir información técnica compleja en el título del PR, reservar esos detalles para la descripción del PR.
