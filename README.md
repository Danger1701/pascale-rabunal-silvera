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

1. Las validaciones correspondiente con el cliente, ajustando su correspondiente feedback.
2. El elemento ha sido revisado por un par o por el equipo de desarrollo.
3. El elemento ha sido probado y se ha verificado que funciona correctamente en diferentes entornos.
4. Todo el trabajo debe estar integrado a main.
5. La documentación ha sido actualizada y se ha revisado para asegurarse de que esté completa y precisa.
6. Debe ser probada por usuarios reales, ajustando su correspondiente feedback.

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

1.Para nombrar las ramas:

    - Los nombres deben ser descriptivos y concisos.
    - Utilizar minúsculas y separa las palabras con guiones.
    - Agregar prefijos como "feature/" para nuevas características, "bugfix/" para correcciones de errores, "hotfix/" para soluciones urgentes, entre otros.
    - Evitar nombres genéricos o ambiguos y eligir nombres que reflejen el propósito o contenido de la rama.

![Repositorio del proyecto_02](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/be2e62d1-75c2-4efc-8eb0-a28738105797)

2.Para nombrar los commits:

    - Los nombres deben ser claros y descriptivos.
    - Utilizar verbos en tiempo presente para indicar la acción realizada, seguidos de una breve descripción del cambio.
    - Limitar la longitud a unos 50 caracteres.
    - Evitar agregar información innecesaria o detalles irrelevantes.

3.Para nombrar los Pull Requests:

    - Comenzar con un prefijo que indique el propósito, como "Feature:", "Fix:", "Docs:", etc.
    - Continuar con una breve descripción del cambio o problema que aborda.
    - Utilizar un estilo conciso y claro.
    - Evitar incluir información técnica compleja en el título del PR, reservar esos detalles para la descripción del PR.

---------------------------------------------------------------------------

## Identificación del problema a resolver

### Propuesta de valor

Experiencia de usuario intuitiva: La aplicación se destacará por ofrecer una interfaz de usuario fácil de usar, con un proceso de reserva rápido y sencillo, priorizando la experiencia del usuario, para que cualquier persona, independientemente de su edad o habilidades tecnológicas, pueda navegar y reservar canchas sin dificultad.

Funcionalidad de Modo Juego Aleatorio: Una característica única de la aplicación será el Modo Juego Aleatorio, donde los usuarios podrán unirse a actividades deportivas junto con otros usuarios de forma aleatoria. Esto fomentará la interacción social, permitiendo que los jugadores se conozcan y disfruten de la actividad deportiva en un entorno inclusivo.

Lista de canchas favoritas y recomendaciones personalizadas: La aplicación permitirá a los usuarios guardar sus canchas favoritas para acceder rápidamente a ellas en el futuro.

Interacción social y funciones de invitación: La aplicación facilitará la interacción social entre los usuarios, permitiéndoles invitar a amigos y contactos a unirse a sus reservas o juegos. Esto fomentará la participación en grupo y hará que la experiencia deportiva sea más divertida y social.

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

---------------------------------------------------------------------------

# Informe de obligatorio ISA (Sprint 2)

## Fecha de entrega: 19/5/2023

---------------------------------------------------------------------------

## Propuestas de solución

### Brainstorming de nombres para la app

Los miembros del equipo realizamos una sesión de brainstorming para lograr decidir el nombre de la app.
Algunos de los nombres mencionados: Cancha-Ya, Ya Cancha, Fútbol 5 App, GameTime.

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

Durante la revisión del sprint, el equipo de Scrum y los interesados examinamos los logros alcanzados durante el sprint y los cambios ocurridos en nuestro entorno. Entre los avances destacados, hemos construido y validado posibles soluciones del MVP a través de prototipos específicos para nuestra aplicación de reserva de canchas de fútbol.

En particular, hemos desarrollado prototipos que ofrecen soluciones para entregar valor y resolver el problema identificado. 
También hemos realizado inspecciones del producto que incluyen instancias de validación con usuarios reales, recolectando sus comentarios y realizando ajustes finales a los prototipos.
Ademas les pedimos si podían poner sugerencias y aspectos que no le gusten para poder mejorar aun mas la experiencia del usuario.

---------------------------------------------------------------------------

### Sprint Retrospective

Realizamos la retospective utilizando metroretro la herramienta que aprendimos en clase.
Decidimos utilizar el template I Like, I Wish para la dinámica de la misma.
El template consiste en poner ¿Cuáles fueron las cosas buenas que sucedieron? y ¿Cuáles son algunas de las cosas que te gustaría que sucedieran en el futuro?.

Resultados de I like - ¿Cuáles fueron las cosas buenas que sucedieron?

![image](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/64442147/7d0824c4-a1e4-4e90-a049-e204c39420c0)

Conclusiones:

- Mejoro la comunicación entre el equipo
- Mejor organización
- Mayor fluidez comparado con el sprint anterior

Resultado de I Wolud - ¿Cuáles son algunas de las cosas que te gustaría que sucedieran en el futuro?

![image](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/64442147/c4bfc072-2837-4da9-a2cf-1aa91e4a81d0)

Conclusiones:

- seguir mejorando la comunicación entre el equipo
- Lograr una buena experiencia de usuario
- Poder culminar las tareas en tiempo y forma

## Sprint Backlog

Evidencia del Sprint Backlog

![Sprint Backlog_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/8374318c-7b1c-4b2f-8cda-8137f0b64c93)

## Boards

![Boards_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/d74fba01-b0dc-496c-a73e-e62007a4cfcd)

## Burndown Trend

![Burndown Trend _1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/34eaea84-a0ad-4d70-8772-2762fc848826)
![Burndown Trend _2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/667e63de-891e-424d-9278-3570314bd7c4)

## Dedicación del equipo

### Dedicación por integrantes del equipo

#### Maximiliano Pascale

![Horas_Pascale](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/4c4d31f2-c62d-469f-93af-f1e1790b10fc)

#### Juan Manuel Rabuñal

![Horas_Rabunal](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/11e955c4-2d0d-4ad7-ad75-f0ab82e5390e)

#### Sebastian Silveira

![Horas_Silvera](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/06d3c63c-969d-4d70-ad02-b1e83ba00cba)

### Dedicación equipo

Dedicación de horas acumuladas por el equipo.

![Horas_Equipo](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/699eabaa-028d-4c8d-a2f2-abe21a6040e4)

![Horas_Equipo_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/d5e82a9a-c162-4d21-b71c-4511b4579c2f)

## Evidencia de manejo de versiones

A continuación se demuestra evidencia del uso de los principios de manejo de versiones adoptados por el equipo.

![Control version_1](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/3dce3c1a-c526-4510-8ee9-1f607e6cf46a)
![Control version_2](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/22498383/73ac2452-532c-42c9-8e22-7bf3743509ab)

---------------------------------------------------------------------------

### Prototipo Funcional

Se presenta el link al prototipo funcional de Figma.

https://www.figma.com/proto/hRuzPMFiU7WcV1k9be08U7/Prototipo?type=design&node-id=431-714&scaling=scale-down&page-id=0%3A1&starting-point-node-id=28%3A46

### Crear Juego Aleatorio 

| Titulo | Enlace |
|-------------------|--------|
| Modificacion Inicio | ![Modificacion Inicio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/3123caf1-0ac5-4feb-a1da-18a6cfa9f114) |
| JuegoAleatorio | ![JuegoAleatorio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/bdef91ee-854e-4051-9b23-0489ecd3b872) |

### Unirse a Juego Aleatorio

| Descripción              | Enlace                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------|
| Universe A Juego Aleatorio | ![Universe A Juego Aleatorio](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/0be97ba9-b349-4a8c-b0b2-88dd46262bc9) |
| Unión Correcta            | ![Unión Correcta](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/fa45f289-afc5-4ecf-8c10-0b90b0b8c173)                    |

### Notificaciones

Se agrega un menu de notificaciones donde el usuario puede ver distinto tipos de notificaciones ademas de una visualizacion sencilla de cuales notificaiones ya visualizo y cuales aun no. 

| Titulo modificacion | Enlace |
|-------------------|--------|
| Notificaciones | ![Notificaciones](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/b01a02a9-c9ca-4155-82bd-d17d0c9e94cd) |


### Update Pantalla de Reserva

| Descripción                    | Enlace                                                                                                       |
|-------------------------------|-------------------------------------------------------------------------------------------------------------|
| Update Pantalla de Reserva     | ![Update Pantalla de Reserva](https://github.com/ORT-ISA1/pascale-rabunal-silvera/assets/62801065/114319c1-1c25-4fd4-8861-a3865c62e218)        |

