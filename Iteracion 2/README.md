# Informe de obligatorio ISA (Sprint 2)

## Fecha de entrega: 19/5/2023

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

## Product Backlog

Estado del product backlog al finalizar la iteración 2

## Sprint Backlog

Evidencia del Sprint Backlog

---------------------------------------------------------------------------

## Propuestas de solución

### Brainstorming de nombres para la app

Los miembros del equipo realizamos una sesion de brainstorming para lograr decidir el nombre de la app.
Algunos de los nombres mencionados: Cancha-Ya, Ya Cancha, Futbol 5 App, GameTime.

Decidimos elegir el nombre de Ya Cancha por las siguientes razones:

- El uso del término "Ya" en el nombre añade un elemento emocional y de urgencia, generando un sentido de acción inmediata.
  Sugiere que los usuarios pueden reservar una cancha de fútbol de forma rápida y sin demoras, lo cual puede ser atractivo para aquellos que buscan jugar al fútbol de manera espontánea o que tienen una ventana de tiempo limitada.
- "Ya Cancha" es un nombre corto y conciso, lo cual lo hace fácil de recordar para los usuarios.
  La simplicidad del nombre evita confusiones y lo hace más accesible para una amplia gama de usuarios, incluyendo aquellos que no son expertos en tecnología.
  
### Logotipo de la app y paleta de colores

Luego de tomar la decision de escoger el nombre, decidimos elegir un logotipo claro y sencillo que muestre las intensiones de nuestra aplicacion.
Decidimos utilizar una letra sencilla que sea un poco mas descontracturada de lo usual, acompañado de una paleta de colores asociada al deporte (Verde y blanco).

![image](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/64442147/b05a3a5b-ac7e-46dd-97d9-0078d9551e82)

### Implementación de trabajo en Crazy 8s - Reserva de Canchas de Fútbol

#### Equipo

Product Owner: Responsable de definir las necesidades del negocio y los objetivos del proyecto.
Scrum Master: Encargado de facilitar el proceso y asegurar que se sigan los principios y prácticas ágiles.
Desarrollador: Encargado de diseñar y desarrollar la aplicación móvil.

#### Preparación

El Scrum Master explica las reglas del Crazy 8s al equipo:

- Se establece un tiempo límite de 8 minutos para generar ideas y dibujar soluciones.

Pantallas para generar:

- Crear el Login de usuario
- Crear el Registro de nuevo usuarios
- Crear la Edición de los usuarios registrados
- Crear la Búsqueda de canchas para permitir la reserva.
- Crear la Reserva de canchas para permitir el uso de las mismas

Establecimiento de una meta:

- El Product Owner establece una meta clara y específica: "Generar ideas para mejorar la experiencia de reserva de canchas".

#### Sesión de Crazy 8s

Se inicia el temporizador de 8 minutos y cada miembro del equipo genera ideas rápidas y las dibuja en papel.  

El Product Owner se centra en ideas relacionadas con la experiencia del usuario y la satisfacción del cliente.  

El desarrollador se enfoca en soluciones técnicas y la viabilidad de implementación.  

Una vez finalizada la sesión de Crazy 8s, cada miembro del equipo muestra y explica sus ideas al resto del equipo.

##### Bosquejo Maximiliano Pascale

![Bosquejo_Pascale](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/d07484cf-b48a-410a-8a35-a4dc7523a950)

##### Bosquejo Juan Manuel Rabuñal

![Bosquejo_Rabunal_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/90cd4e47-334f-44f6-bd0f-f45ec1d1bee6)
![Bosquejo_Rabunal_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/e7ae4bac-5ee2-4703-b0f9-066919654407)

##### Bosquejo Sebastian Silvera

![Bosquejo_Silvera_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/e1a15cd8-0c5f-4437-a5ca-d788339ddcda)
![Bosquejo_Silvera_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/8b9ee042-9dbf-4154-a16b-0fc9049d4f74)

#### Discusión y selección

El equipo discute las ideas presentadas y evalúa su valor, viabilidad y alineación con los objetivos del proyecto.  

Se seleccionan las ideas más prometedoras para su desarrollo en el MVP de la aplicación, la cual se verá reflejada en el desarrollo del prototipo.  

El Product Owner y el Scrum Master colaboran en la síntesis de las ideas seleccionadas y las priorizan en función de su valor y esfuerzo.  

El desarrollador participa en la planificación del siguiente paso y fundamentalmente en el desarrollo del prototipo.  

#### Prototipos

Se realiza el prototipo de las pantallas planificadas en este sprint.

Este prototipo inicial, tiene pendiente la validación con usuarios y con el cliente por el PO (los ajustes propuesto por usuarios y cliente lo expondremos mas adelante en este documento).

##### Prototipos Login Usuario

| Presentación |  Login Usuario |
|--------|--------|
| ![Presentacion](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/86aba527-3b05-49ba-baab-fa8d2313e89f) | ![Login](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/e2bff46f-bded-41ca-97f2-0f228b969bd3) |
| Login Error datos | Login Error reintentos |
| ![Error datos](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/1adfa12f-c2fd-4e32-98c8-070ba6a4d3ce) | ![Error reintentos](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/e04bf227-fa2e-4487-b2df-cd18052f9cc6) |

##### Prototipos Registro Usuario

|  Presentación Registro de Usuario | Caso Exitoso |
|--------|--------|
| ![Registro](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/bcde80bd-50cb-4555-b78d-649ef3cc8e51) | ![Exitoso](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/41e19459-bc72-4ba8-adfe-bfc5a65eb268) |
| Mensajes de Error | Mensajes de Error |
| ![Error 1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/a41cf6d9-41cf-492a-951b-5fcb2d8747f7) | ![Error 2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/22abeebd-0cff-497e-b01b-eb4aeb2e142d) |
| Mensajes de Error | Mensajes de Error |
| ![Error 3](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/b67d7086-0740-4ac0-8b34-497276f0c229) | ![Error 4](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/3855e4f0-e883-49a5-a83a-84e690df1853) |
| Mensajes de Error |
| ![Error 5](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/5ea5becd-38f6-41cc-b286-1e7226f3d88d) |

##### Prototipos Búsqueda de cancha

| Búsqueda Cancha | Filtros |
|--------|--------|
| ![Busqueda](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/aa0a40b0-a37d-4ec6-b55c-64035d341ee1) | ![Filtros](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/1df4c978-0315-4ce5-a0e7-7f2c903aef28) |
| Resultado |
| ![Resultado](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/121f7d92-d223-4903-8499-8a5702978032) |

##### Prototipos Edición

| Edición Datos | Edición Satisfactoria |
|--------|--------|
| ![Edicion](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/6aa19eb4-f35a-4527-a776-5dae27881703) | ![Satisfactoria 1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/9f365c5b-549f-45f8-ac5b-22614950cf62) |
| Edición Satisfactoria | Contraseña diferente a la actual |
| ![Satisfactoria 2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/3f2df90b-33d8-4365-8c2f-4a5667b4114c) | ![RS3](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/a8695858-09f2-4b5b-82d1-51ea458a8eb0) |
| RS1 Email invalido | RS2 Largo contraseña |
| ![RS1 Email](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/4dbb1b96-1c2e-4095-a0c4-24305aa4b023) | ![RS2 Contraseña](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/331111da-62f8-4454-9802-ee10e364eed9) |

##### Prototipo Reserva

| Reserva | Confirmación de Reserva |
|--------|--------|
| ![Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/1b986650-f09f-464c-b2f8-b5d9c5c53b8e) | ![Confirmacion de Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/3f2bb2f0-e59e-405d-857f-bbe94e06afbc) |
| Reserva Exitosa | Email de Confirmación |
| ![Reserva Exitosa](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/46852fa3-f935-47b5-8da6-eec0a532083b) | ![Email de Confirmacion](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/89e8e674-7be9-45f9-94c7-54cb389f4921) |

#### Mejoras en prototipos propuestos por el PO

El Product Owner ha identificado una serie de mejoras clave que pueden enriquecer la experiencia de los usuarios y optimizar el funcionamiento de la plataforma.
A continuación, presentaremos estas mejoras y explicaremos cómo pueden beneficiar a los usuarios.

- Login
  - Se agrega Un avatar y opción de visualizar el sitio sin estar registrado

- Registro
  - Avatar de Usuario
  - Opción de cédula de identidad
  - Opción de dudas contactarte

- Edición de datos personales
  - Correo electrónico actual
  - Contactarte con nosotros

- Selección tu cancha
  - Se añade tipo de cancha

- Detalle Reserva
  - Se re diseña para mostrar mas información de la reserva

| Detalle Reserva | Selección de Cancha |
|--------|--------|
| ![Detalle Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/9413cb06-c214-4214-bc35-59d0f1399c7d) | ![Selección de Cancha](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/35ac562a-cdde-48d8-8c98-aee3c0f1dbe2) |
| Inicio con Modificaciones | Modificación Edición Datos Personales |
| ![Inicio con Modificaciones](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/26d601e2-0e9a-42a7-a233-c1ab4358c92e) | ![Modificación Edición Datos Personales](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/54aa2306-0ce3-4fff-934a-b95956b1c6cd) |
| Modificación Registro |
| ![Modificación Registro](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/ee54e58c-201b-4602-b772-9334db42546d) |

#### Encuesta de usabilidad YaCancha por usuarios

Hemos llevado a cabo una encuesta para evaluar la satisfacción y recopilar comentarios sobre el prototipo de nuestra aplicación móvil para la reserva de canchas de fútbol.  
Los resultados son muy importantes para nosotros, ya que eso nos ayuda a garantizar que la aplicación se ajuste de manera óptima a las necesidades y expectativas.

Durante el proceso de encuesta, hemos recopilado información sobre diversos aspectos de la aplicación móvil, incluyendo la usabilidad de la interfaz, la facilidad de navegación, la claridad de las instrucciones, la eficacia del proceso de reserva, entre otros.  
Las respuestas nos proporcionan una visión más clara de los puntos fuertes y áreas de oportunidad de nuestro prototipo.

En base a los resultados preliminares de la encuesta, observamos que la mayoría de los participantes encontraron la interfaz intuitiva y fácil de usar.  
También se ha destacado la facilidad de la aplicación para la reserva de canchas de fútbol.  
No obstante, también hemos identificado algunas áreas en las que podemos realizar mejoras para garantizar una experiencia aún más satisfactoria como por ejemplo la edición de datos personales.

Nos comprometemos a tomar en consideración cada comentario y sugerencia recibida para optimizar el rendimiento y funcionalidad de nuestra aplicación.

Link a encuesta: <https://docs.google.com/forms/d/e/1FAIpQLSfVwug9xuKzRgaWvpiltpq-NGzf3HdAv-kwmxGpf6BR4kQvxg/viewform>

#### Resultados de encuesta de usabilidad

##### Login

![Login](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/239e6a08-97cf-4144-b3f7-0f877b0fd72b)
![Login_Error](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/c657df0f-b8f5-4874-ad84-98bedf842d58)

##### Registro

![Registro](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/18758eaa-9ac7-45be-86c1-3058ba9728d3)
![Registro_Error](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/4c831f99-bd0d-4b8c-b7e9-561d65fc775c)

##### Edición

![Edicion](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/1b04a309-f9cf-42d4-b3de-052fd8cb7fb2)

##### Búsqueda

![Busqueda](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/81a599ba-5aef-461f-843b-59ea2c3168ac)
![Busqueda_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/e47b14f2-6535-4af8-b9fe-5ebcf599d520)

##### Reserva

![Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/90d5dd3b-0a78-4b88-b127-ee4f2a66d0ff)
![Reserva_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/2e61e744-f07f-4f83-9443-b47c63eaa570)
![Reserva_mejoras](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/c3a33e52-bc2b-4266-b516-cddc63e37371)

##### General

![General_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/7d0a1bfb-bb40-4811-b8fb-1c18eba200ab)
![General_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/b88bf7d1-3176-465f-b8a9-f513534f356e)
![General_3](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/23a9fd7c-ea28-4fa0-b6f7-5e90996ad4af)
![General_4](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/4fa169ad-3cc2-4d75-b840-b4757243fe83)

---------------------------------------------------------------------------

### Sprint Review




---------------------------------------------------------------------------

### Sprint Retrospective

Realizamos la retospective utilizando metroretro la herramienta que aprendimos en clase.
Decidimos utilizar el template I Like, I Wish para la dinamica de la misma.
El template consiste en poner ¿Cuáles fueron las cosas buenas que sucedieron? y ¿Cuáles son algunas de las cosas que te gustaría que sucedieran en el futuro?.

Resultados de I like - ¿Cuáles fueron las cosas buenas que sucedieron?

Resultado de I Wolud - ¿Cuáles son algunas de las cosas que te gustaría que sucedieran en el futuro?





