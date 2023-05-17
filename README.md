# Informe de obligatorio ISA

---------------------------------------------------------------------------

## Materia: INGENIERIA DE SOFTWARE AGIL 1

### Equipo 5 - Mini proyecto

### Estudiantes: Juan Manuel Rabuñal - Maximiliano Pascale - Sebastian Silveira

---------------------------------------------------------------------------

### Herramienta para gestión del proyecto

#### Azure Devops: <https://dev.azure.com/Pascale-Rabunal-Silvera/Mini%20Proyecto%202023>

### Versionado

#### Repositorio Github: <https://github.com/ORT-ISA1/pascale-rabunal-silvera>

---------------------------------------------------------------------------

## Definición del marco de trabajo

### Marco general del scrum

El resultado del proyecto es poder descubrir, idear y prototipar un MVP (Minimum Viable Product) de una aplicación móvil para ayudar al usuario a reservar canchas para realizar actividades deportivas.

Dicho marco de trabajo es desconocido para los integrantes del equipo por lo que va a haber una cierta curva de aprendizaje dentro del desarrollo de la aplicación.
Se va a necesitar de innovación, creatividad, interacción y buena comunicación con el usuario para lograr un producto que nos diferencia y logre fidelidad con el usuario ya que ya hay varias apps en el mercado.

El equipo de desarrollo va a utilizar la forma de trabajo basada en SCRUM y además optamos por seguir un ciclo de vida evolutivo en el desarrollo del producto:

![image](https://user-images.githubusercontent.com/64442147/235362931-867b5b72-dfb6-4173-8678-b1afa27c7d91.png)

### Supuestos Efectuados

1. La aplicación va a ser únicamente para Uruguay.
2. La descarga de la aplicación será gratuita.
3. Únicamente va a estar en Español

### Roles

![image](https://user-images.githubusercontent.com/64442147/235363898-57a075bb-3c79-44a8-ae4e-264c9b3fbc44.png)

### Políticas de trabajo

#### Definición de Ready

Antes de que una historia de usuario pueda ser incluida en una iteración, es necesario que cumpla con ciertas condiciones previas.
Estas condiciones incluyen que el equipo de desarrollo debe tener una comprensión compartida de lo que la historia de usuario significa y qué se espera de ella.
También se debe presentar una estimación relativa del trabajo necesario para completar la historia de usuario, y los criterios de aceptación deben ser claros y representados en escenarios para que puedan ser comprobados.
Además, la historia de usuario debe ser valiosa y no depender de otras historias de usuario para su completitud.
En resumen, estas condiciones previas aseguran que el equipo de desarrollo tenga toda la información necesaria y comprenda completamente lo que se espera de la historia de usuario antes de comenzar a trabajar en ella.

La definición de lista de requisitos previos para una historia de usuario entrar en una iteración incluye que:

1. El título debe ser breve y muy descriptivo.
2. La narrativa debe tener una estructura que explique qué hace el usuario, qué quiere y por qué lo quiere.
3. La estimación de tiempo debe estar en horas ideales de trabajo y estar en valores predefinidos.
4. Los criterios de aceptación deben ser claros y presentados como escenarios, explicando el contexto, el evento y los resultados esperados.

#### Definición de Done

Los criterios para determinar qué historias terminaron con éxito su proceso de implementación serán:

1. Las pruebas automatizadas y manuales han sido completadas satisfactoriamente.
2. El elemento ha sido revisado por un par o por el equipo de desarrollo.
3. El elemento ha sido probado y se ha verificado que funciona correctamente en diferentes entornos.
4. El elemento ha sido integrado y desplegado en el entorno de producción.
5. La documentación ha sido actualizada y se ha revisado para asegurarse de que esté completa y precisa.

### Control de versiones

Se crea el repositorio <https://github.com/ORT-ISA1/pascale-rabunal-silvera>

Se trabaja con dos ramas “main” y “develop”, en esta última cada miembro del equipo trabajará de acuerdo a las buenas prácticas aprendidas.

Trabajaremos sobre “develop”, donde cada miembro creara sus ramas y trabaja sobre ellas. Una vez completado el desarrollo deberá mergear a “develop”.

Al finalizar cada sprint “develop” será mergeada a “main”.

---------------------------------------------------------------------------

## Identificación del problema a resolver

### Características deseadas de la población uruguaya

Se realizan entrevistas a potenciales interesados en el uso de la aplicación a desarrollar.
Se les informa de las características que tendrá el MVP y de la interacción con los entrevistados surgen las siguiente comentarios
Es importante aclarar, que estas características son las deseadas por los entrevistados, no significa un compromiso para su desarrollo.

**1. Variedad de canchas y deportes disponibles:**
Según lo expresado por los entrevistados es importante que la aplicación ofrezca una amplia variedad de canchas deportivas y deportes para reservar.
Para priorizar esta característica, deberemos realizar encuestas para conocer los deportes y tipos de canchas que los usuarios más frecuentan y desean reservar.
Para validarla, deberíamos hacer pruebas de usabilidad en las que los usuarios busquen y reserven canchas y deportes para comprobar que la aplicación ofrece suficientes opciones.

**2. Facilidad de uso:**
La aplicación debe ser fácil y amigable de usar, con una interfaz intuitiva que permita reservar canchas en pocos pasos.
Para priorizarlo, deberían realizarse pruebas de usabilidad en las que los usuarios interactúen con la aplicación y reporten cualquier dificultad o confusión.
Para validarla, se deberán hacer pruebas con usuarios reales y medir su tiempo de interacción con la aplicación y la tasa de éxito de reservas.

**3. Pago en línea seguro:**
La aplicación debe ofrecer opciones de pago en línea seguras y confiables, para evitar el riesgo de fraudes y garantizar la seguridad de los usuarios.
Para priorizar esta característica, se debería realizar encuestas para conocer las preferencias de los usuarios respecto a los métodos de pago en línea.
Para validarla, deberíamos hacer pruebas de seguridad en las que se compruebe que los datos de pago están protegidos y encriptados.

**4. Comentarios y valoraciones de otros usuarios:**
La aplicación podría ofrecer un sistema de comentarios y valoraciones de otros usuarios, para ayudar a los usuarios a elegir las mejores canchas y a mejorar la calidad del servicio.
Para priorizarlo, deberían realizarse pruebas en las que los usuarios interactúen y así conocer si los usuarios valoran y utilizan este tipo de información.
Para validarla, podrías hacer pruebas con usuarios en las que se compruebe que los comentarios y valoraciones son útiles y confiables.

**5. Recordatorios y notificaciones:**
La aplicación podría enviar recordatorios y notificaciones a los usuarios para recordarles sus reservas y para informarles sobre nuevas ofertas y descuentos.
Para priorizarlo, deberían realizarse pruebas en las que los usuarios interactúen y así conocer si los usuarios valoran y utilizan este tipo de información.
Para validarla, podrías hacer pruebas con usuarios en las que se compruebe que las notificaciones son útiles y no resultan molestas o intrusivas.

### Identificación de interesados

Se realizan entrevistas a potenciales interesados en el uso de la aplicación a desarrollar.
Se les informa de las características que tendrá el MVP y de la interacción con los entrevistados surgen las siguiente comentarios
Es importante aclarar, que estas características son las deseadas por los entrevistados, no significa un compromiso para su desarrollo.

**1. Usuarios finales:**
Los usuarios finales son las personas que utilizarán la aplicación para reservar canchas deportivas.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Búsqueda de canchas deportivas por ubicación y deporte , disopnibilidad.
    - Reserva de canchas deportivas en tiempo real.
    - Cancelación de reservas.
    - Pago en línea seguro.
    - Valoraciones y comentarios sobre otros usuarios , canchas.
    - Calificación y reseñas de las canchas y proveedores de servicios deportivos.
    -Comunicación en tiempo real con el propietario de la cancha o otros usuarios.
    - Notificaciones y recordatorios de reservas y ofertas.

**2. Propietarios de canchas deportivas:**
Los propietarios de canchas deportivas podrían estar interesados en la aplicación para promocionar sus instalaciones y aumentar sus ingresos.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Registro y publicación de sus canchas deportivas en la aplicación.
    - Edición de información y precios de sus canchas deportivas.
    - Gestion de precios y descuentos disponibles
    - Gestión de reservas y cancelaciones.
    - Pago en línea seguro.
    - Comunicación en tiempo real con los usuarios finales.
    - Anuncios y promociones de sus canchas deportivas.

**3. Organizadores de eventos deportivos:**
Los organizadores de eventos deportivos podrían estar interesados en la aplicación para gestionar y promocionar sus eventos.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Publicación y promoción de sus eventos deportivos en la aplicación.
    - Poder conocer datos estadisticos de los usuarios o posibles interesados.
    - Integracion con redes sociales como Instagram o Facebook.
    - Gestión de reservas y cancelaciones de sus eventos deportivos.
    - Pago en línea seguro.
    - Valoraciones y comentarios de los participantes.
    - Anuncios y promociones de sus eventos deportivos.

**4. Entrenadores y clubes deportivos:**
Los entrenadores y clubes deportivos podrían estar interesados en la aplicación para gestionar y promocionar sus entrenamientos y actividades.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Publicación y promoción de sus entrenamientos y actividades en la aplicación.
    - Gestión de reservas y cancelaciones de sus entrenamientos y actividades.
    - Pago en línea seguro.
    - Valoraciones y comentarios de los participantes.
    - Anuncios y promociones de sus entrenamientos y actividades.

## Perfiles de Posibles Usuarios

![Usuario1](https://user-images.githubusercontent.com/62801065/236575902-e30bc2b9-067d-4d85-9c9b-1541c4224368.png)

![Usuario2](https://user-images.githubusercontent.com/62801065/236575919-30a765c7-f775-4ac2-b5bf-5252a500910f.png)

![Usuario3](https://user-images.githubusercontent.com/62801065/236575956-66a867e2-6256-478f-9c6a-d7e9f9edece7.png)

### Estudio de competidores

Se realiza el análisis de posibles competidores que se encuentran en el mercado uruguayo.

**1. Wonasports**
    <https://wonasports.com/>  
    Es un sistema que facilita el acceso a toda la oferta del deporte amateur en una misma plataforma.
    Algunas de sus principales funcionalidades son:  

    - Búsqueda y reserva de canchas deportivas, los usuarios pueden buscar canchas deportivas cercanas y reservar su horario preferido directamente a través de la plataforma.
    - Gestión de complejos deportivos, Wonasports ofrece un software completo de gestión para los complejos deportivos, lo que les permite administrar y programar sus canchas, y aceptar reservas en línea.
    - Conexión entre jugadores, la plataforma permite a los jugadores conectarse entre sí, unirse a equipos y participar en ligas y torneos.
    - Pagos en línea, los usuarios pueden realizar pagos en línea de forma segura y fácil a través de la plataforma

![Wonasports_1](https://user-images.githubusercontent.com/22498383/235555673-283a831c-035b-4e76-a30d-cfedbbb493d7.jpeg)

**2. Canchea**
    <https://canchea.com.uy/>  
    Es un sitio web uruguayo que se dedica a la reserva de canchas de fútbol.
    A continuación se describen algunas de sus funcionalidades:  

    - Reserva de canchas: los usuarios pueden encontrar canchas disponibles en Montevideo y reservarlas directamente desde la página web.
    - Información de complejos deportivos: Canchea.com.uy cuenta con información detallada de los complejos deportivos que ofrecen canchas de fútbol en Montevideo, incluyendo horarios, servicios (como barbacoa, parrillero, cantina, estacionamiento, entre otros), y fotografías.
    - Promoción de complejos deportivos: los complejos deportivos pueden agregar su información al sitio web para ser promocionados en la página y ganar mayor visibilidad en las búsquedas relacionadas con el alquiler de canchas deportivas.
    - Se realizan menciones periódicas en redes sociales y correos electrónicos a los complejos agregados, lo que aumenta la audiencia y las consultas de los usuarios.

![Canchea_1](https://user-images.githubusercontent.com/22498383/235555718-a9a253a9-3e81-4b5b-8e07-417ddcbb92ee.jpeg)
![Canchea_2](https://user-images.githubusercontent.com/22498383/235555720-fabb55e9-80ee-42eb-9278-15246425266b.jpeg)
![Canchea_3](https://user-images.githubusercontent.com/22498383/235555722-85887a83-4e60-4895-9f5f-f4fe75371384.jpeg)

**3. Alquilatucancha**
    <https://alquilatucancha.com/>  
    Alquila Tu Cancha es una plataforma en línea que permite a los usuarios reservar canchas deportivas en complejos deportivos a través de Internet. También ofrece una solución de gestión para los propietarios de complejos deportivos que les permite gestionar sus instalaciones en línea.
    Algunas de sus principales funcionalidades son:  

    - La plataforma ofrece una serie de funciones para los usuarios, como la capacidad de reservar una cancha deportiva en línea y acceder a información detallada sobre los complejos deportivos.
    - También permite a los usuarios consultar los precios y los horarios de las canchas disponibles.
    - Para los propietarios de complejos deportivos, Alquila Tu Cancha ofrece una solución de gestión en línea que permite la reserva de canchas deportivas y la administración de las reservas.
    - La plataforma unifica toda la gestión de los complejos deportivos, lo que permite a los propietarios de los mismos acceder a información en tiempo real sobre la disponibilidad de las canchas y gestionar las reservas en línea.

![Alquilatucancha_1](https://user-images.githubusercontent.com/22498383/235555733-e16d11e5-194f-4522-980f-3659d6c64fb9.jpeg)
![Alquilatucancha_2](https://user-images.githubusercontent.com/22498383/235555736-d4c459cb-21fc-41ee-8f7f-3dc60c327be8.jpeg)
![Alquilatucancha_4](https://user-images.githubusercontent.com/22498383/235555739-78a6d50e-7d9c-4de6-9599-fd9cb74de110.jpeg)

**4. Quierojugar**
    <https://quierojugar.com.uy/>  
     Algunas de sus funcionalidades más destacadas son:  

    - Posibilidad de buscar canchas deportivas disponibles para reservar en la zona deseada.
    - Opción de realizar reservas y pagos en línea de forma segura.
    - Información detallada sobre las canchas deportivas, incluyendo fotos, ubicación y características.
    - Administración de reservas y pagos a través de una cuenta personal.
    - Acceso a promociones y descuentos exclusivos.

![Quierojugar_1](https://user-images.githubusercontent.com/22498383/235555763-71431ca7-eb4d-4dff-a842-4f19c520fa61.jpeg)
![Quierojugar_2](https://user-images.githubusercontent.com/22498383/235555766-fa1200ed-b005-458f-b301-c8678b36531d.jpeg)

### Comparación de competidores

Hemos realizado un análisis comparativo, Wonasports, Canchea, Alquilatucancha y Quierojugar en función a sus funcionalidades, servicios y características teniendo como objetivo la población de Uruguay.

Comenzando con **Wonasports**, se trata de un software de gestión completo que busca facilitar el acceso al deporte amateur, conectando a posibles clientes con instituciones y actividades deportivas que se adapten a sus necesidades y preferencias.  
En cuanto a sus características y servicios, Wonasports ofrece la gestión de reservas y pagos, así como la administración de membresías y clases. También incluye un sistema de notificaciones y un panel de control para que los administradores puedan gestionar su centro deportivo.

**Canchea**, por su parte, es una plataforma uruguaya (enfocado en el fútbol uruguayo) de reserva de canchas de fútbol en línea, que permite a los usuarios elegir la cancha, la hora y la fecha que desean para jugar. Canchea se enfoca en ofrecer una experiencia de usuario rápida y sencilla, además de contar con una variedad de opciones de canchas.  
Entre sus características y servicios se encuentran la publicación de noticias, resultados de partidos, estadísticas de jugadores y equipos, además de una sección de opinión y análisis. Cancha.com.uy no ofrece funcionalidades para la gestión de centros deportivos o reservas.

**Alquilatucancha** es otra plataforma uruguaya de reserva de canchas de fútbol en línea. Ofrecen una amplia variedad de canchas y servicios, como canchas con césped sintético, vestuarios y estacionamiento. También permiten hacer reservas a través de su aplicación móvil, lo que resulta muy cómodo para los usuarios.  
Algunas de sus características son la posibilidad de reservar canchas en línea, pagar en línea y recibir confirmación inmediata de la reserva. También incluye un sistema de evaluación de las canchas por parte de los usuarios.

Finalmente, **Quierojugar** es una plataforma que permite reservar canchas de fútbol, básquetbol y volley en Uruguay. Ofrecen una amplia variedad de opciones y permiten hacer reservas en línea. Además, su sitio web es fácil de usar y ofrece la posibilidad de pagar en línea.  
Entre sus características y servicios se encuentran la posibilidad de reservar canchas en línea, pagar en línea y recibir confirmación inmediata de la reserva.

Teniendo en cuenta el objetivo de atender a la población de Uruguay, podemos señalar que todas estas plataformas se enfocan en ofrecer una experiencia de usuario sencilla y rápida al momento de reservar canchas deportivas en línea. Sin embargo, es importante señalar que Wonasports parece ser la única plataforma que se enfoca en la gestión deportiva en general, lo que puede incluir reservas de canchas, pero también la organización de torneos y la gestión de ligas.  

En cuanto a la variedad de opciones de canchas y servicios, Alquilatucancha es la plataforma que ofrece una mayor cantidad de opciones, como canchas con césped sintético, vestuarios y estacionamiento. No obstante, Canchea y Quierojugar también ofrecen una buena variedad de opciones en términos de canchas deportivas.  

En resumen, si bien todas estas plataformas comparten un objetivo común de facilitar la reserva de canchas deportivas en línea, cada una tiene características y enfoques únicos.

### Priorización de funcionalidades basadas en la importancia del negocio

Al desarrollar una aplicación móvil para reservar canchas deportivas, es importante priorizar las funcionalidades más críticas para el negocio, teniendo en cuenta que el equipo está formado por 3 personas.  
Aquí nuestra lista de prioridades:  

1. **Registrar nuevo usuario**: Es importante permitir que nuevos usuarios se registren en la aplicación y accedan a sus características.
2. **Login de usuario**: Esto es importante para garantizar la seguridad de los datos del usuario y permitir una experiencia personalizada.
3. **Edición de usuario**: Esto es importante para garantizar la integridad de los datos del usuario y permitir una experiencia personalizada.
4. **Buscar canchas para reservar utilizando filtros**: Esta es una funcionalidad clave, ya que permitirá a los usuarios encontrar fácilmente las canchas que mejor se adapten a sus necesidades.
5. **Notificaciones de reserva y cancelación**: Es importante mantener a los usuarios informados de cualquier cambio en sus reservas para evitar confusiones y malentendidos.
6. **Modo Juego Aleatorio**: Esta es una función interesante para permitir a los usuarios encontrar compañeros de juego, pero puede ser menos crítica que otras funciones y puede requerir más tiempo y recursos para desarrollarla.

---------------------------------------------------------------------------

## Sprint Review

Durante el evento, el Equipo Scrum y las partes interesadas revisan lo que se hizo en el Sprint y los cambios que ocurrieron en el entorno. En el progreso, los aspectos generales del proyecto pasan a primer plano, como la definición del marco, las iteraciones y la planificación del repositorio.
Luego de la definición del marco de trabajo basado en SCRUM, con los roles definidos para cada integrante en el equipo y los acuerdos principales y sus políticas de trabajo.
Asimismo, se enfatiza la identificación del problema a resolver y la definición del problema.
Se realizo una definición del problema, el armado de un product backlog definido con su jerarquía de épicas, historias de usuario y tareas con su respectiva priorización, estimación y criterios de aceptación.
Ademas de un análisis exploratorio de mercado que incluye identificación de interesados con sus funcionalidades y estudio de competidores.

## Sprint Retrospective

Al finalizar la primera iteración del proyecto logramos identificar varias conclusiones.
En primer lugar estuvimos muy trancados al principio sobre como arrancar a trabajar, pero a medida que fue pasando el tiempo ya pudimos trabajar cada uno de forma independiente pasando status en las daily meeting.
Para la próxima iteración vamos a mejorar mucho la velocidad de trabajo del equipo ya que nos llevo gran tiempo aprender a utilizar las diferentes herramientas como el Azure DevOps y Clockify. Pero para la próxima iteración ya vamos a tener practica con el uso de ellas.
Al tener un equipo de trabajo tan pequeño es complicado poder estimar la capacidad de trabajo por sprint ya que son muchas las tareas que se deben realizar por cada iteración.

---------------------------------------------------------------------------

## Product Backlog

Evidencia del Product Backlog

![Backlog_1](https://user-images.githubusercontent.com/22498383/236547875-f4d31b4f-a68e-44f9-8b9d-375d02db5e10.png)
![Backlog_2](https://user-images.githubusercontent.com/22498383/236547877-5b78bfd8-4ea9-4541-a49f-d7c2007f736b.png)
![Backlog_3](https://user-images.githubusercontent.com/22498383/236547880-4dc2e19d-0958-4036-9f4c-e924e4ccc636.png)
![Backlog_4](https://user-images.githubusercontent.com/22498383/236548102-154baac2-f37f-4215-93da-42b79daca7fa.png)

## Sprint Backlog

Evidencia del Sprint Backlog

![Sprint Backlog_1](https://user-images.githubusercontent.com/22498383/236549470-fd63c52a-21f1-4b5e-aebb-9710f3233d6e.PNG)

## Boards

![Boards_1](https://user-images.githubusercontent.com/22498383/236550850-194c9084-949b-461b-b58b-f782cffaab46.PNG)
![Boards_2](https://user-images.githubusercontent.com/22498383/236550856-5403aeb1-04c5-4ae7-8bfe-65dfdefc0aaf.PNG)
![Boards_3](https://user-images.githubusercontent.com/22498383/236550858-24b14bef-bda2-4b0d-99f1-041a35c9dd16.PNG)

## Burndown Trend

![Burndown Trend _1](https://user-images.githubusercontent.com/22498383/236554453-b6ee5e80-ad1c-455b-94ac-42922312152a.PNG)
![Burndown Trend _2](https://user-images.githubusercontent.com/22498383/236554458-d4fe8cb5-35c4-4c97-912b-78a27af48676.PNG)

## Dedicación del equipo

### Tags creados

Tags creados siguiendo los principios del Proceso de software genérico

![Tags](https://user-images.githubusercontent.com/22498383/236591600-1e108cc7-ee0d-4065-a5bc-49ee706ae0b9.PNG)

### Dedicación por integrantes del equipo

#### Maximiliano Pascale

![Horas_Pascale](https://user-images.githubusercontent.com/22498383/236591596-f508cb0b-3dae-4be9-b223-4c462452f674.PNG)

#### Juan Manuel Rabuñal

![Horas_Rabunal](https://user-images.githubusercontent.com/22498383/236591597-7607ca9e-ff3b-4fe1-9b06-3a32a4001e69.PNG)

#### Sebastian Silveira

![Horas_Silvera](https://user-images.githubusercontent.com/22498383/236591599-6e142480-4708-491f-b0fd-33d7e6f15b77.PNG)

### Dedicación equipo

Dedicación de horas acumuladas por el equipo.

![Horas_Equipo](https://user-images.githubusercontent.com/22498383/236591592-a63eb3ac-d1d9-4086-a294-52a01bdeab12.PNG)

![Horas_Equipo_2](https://user-images.githubusercontent.com/22498383/236591595-a0dc4780-b792-40be-a9a2-8dab85addd16.PNG)

## Evidencia de manejo de versiones

A continuación se demuestra evidencia del uso de los principios de manejo de versiones adoptados por el equipo.

![Control version_1](https://user-images.githubusercontent.com/22498383/236552621-a3cbbb43-bd9b-42af-a0db-96835fc598fe.PNG)
![Control version_2](https://user-images.githubusercontent.com/22498383/236552626-4211cd9b-2f76-4373-9109-be4ce368a9d1.PNG)

#### Prototipos Busqueda de cancha

| Título | Imagen |
|--------|--------|
| Busqueda Cancha | ![Busqueda Cancha](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/aa0a40b0-a37d-4ec6-b55c-64035d341ee1) |
| Filtros | ![Filtros](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/1df4c978-0315-4ce5-a0e7-7f2c903aef28) |
| Resultado Aplicar Filtro | ![Resultado Aplicar Filtro](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/121f7d92-d223-4903-8499-8a5702978032) |


