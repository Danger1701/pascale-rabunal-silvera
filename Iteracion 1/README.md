# Informe de obligatorio ISA (Sprint 1)

## Fecha de entrega: 5/5/2023

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

## Identificación del problema a resolver

### Identificación de interesados

Se realizan entrevistas a potenciales interesados en el uso de la aplicación a desarrollar.
Se les informa de las características que tendrá el MVP y de la interacción con los entrevistados surgen las siguiente comentarios
Es importante aclarar, que estas características son las deseadas por los entrevistados, no significa un compromiso para su desarrollo.

**1. Usuarios finales:**
Los usuarios finales son las personas que utilizarán la aplicación para reservar canchas deportivas.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Búsqueda de canchas deportivas por ubicación y deporte.
    - Reserva de canchas deportivas en tiempo real.
    - Cancelación de reservas.
    - Pago en línea seguro.
    - Valoraciones y comentarios de otros usuarios.
    - Notificaciones y recordatorios de reservas y ofertas.

**2. Propietarios de canchas deportivas:**
Los propietarios de canchas deportivas podrían estar interesados en la aplicación para promocionar sus instalaciones y aumentar sus ingresos.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Registro y publicación de sus canchas deportivas en la aplicación.
    - Edición de información y precios de sus canchas deportivas.
    - Gestión de reservas y cancelaciones.
    - Pago en línea seguro.
    - Anuncios y promociones de sus canchas deportivas.

**3. Organizadores de eventos deportivos:**
Los organizadores de eventos deportivos podrían estar interesados en la aplicación para gestionar y promocionar sus eventos.
Algunas de las funcionalidades que surgen de la entrevista son:

    - Publicación y promoción de sus eventos deportivos en la aplicación.
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

Hemos realizado un análisis comparativo, Wonasports, Canchea, Alquilatucancha y Quierojugar en función a sus funcionalidades, servicios y características teniendo como objetivo la población de Uruguay

Comenzando con Wonasports, se trata de un software de gestión completo que busca facilitar el acceso al deporte amateur, conectando a posibles clientes con instituciones y actividades deportivas que se adapten a sus necesidades y preferencias.
En cuanto a sus características y servicios, Wonasports ofrece la gestión de reservas y pagos, así como la administración de membresías y clases. También incluye un sistema de notificaciones y un panel de control para que los administradores puedan gestionar su centro deportivo.

Canchea, por su parte, es una plataforma uruguaya (enfocado en el fútbol uruguayo) de reserva de canchas de fútbol en línea, que permite a los usuarios elegir la cancha, la hora y la fecha que desean para jugar. Canchea se enfoca en ofrecer una experiencia de usuario rápida y sencilla, además de contar con una variedad de opciones de canchas.
Entre sus características y servicios se encuentran la publicación de noticias, resultados de partidos, estadísticas de jugadores y equipos, además de una sección de opinión y análisis. Cancha.com.uy no ofrece funcionalidades para la gestión de centros deportivos o reservas.

Alquilatucancha es otra plataforma uruguaya de reserva de canchas de fútbol en línea. Ofrecen una amplia variedad de canchas y servicios, como canchas con césped sintético, vestuarios y estacionamiento. También permiten hacer reservas a través de su aplicación móvil, lo que resulta muy cómodo para los usuarios.
Algunas de sus características son la posibilidad de reservar canchas en línea, pagar en línea y recibir confirmación inmediata de la reserva. También incluye un sistema de evaluación de las canchas por parte de los usuarios.

Finalmente, Quierojugar.com.uy es una plataforma que permite reservar canchas de fútbol, básquetbol y volley en Uruguay. Ofrecen una amplia variedad de opciones y permiten hacer reservas en línea. Además, su sitio web es fácil de usar y ofrece la posibilidad de pagar en línea.
Entre sus características y servicios se encuentran la posibilidad de reservar canchas en línea, pagar en línea y recibir confirmación inmediata de la reserva.

Teniendo en cuenta el objetivo de atender a la población de Uruguay, podemos señalar que todas estas plataformas se enfocan en ofrecer una experiencia de usuario sencilla y rápida al momento de reservar canchas deportivas en línea. Sin embargo, es importante señalar que Wonasports parece ser la única plataforma que se enfoca en la gestión deportiva en general, lo que puede incluir reservas de canchas, pero también la organización de torneos y la gestión de ligas.

En cuanto a la variedad de opciones de canchas y servicios, Alquilatucancha es la plataforma que ofrece una mayor cantidad de opciones, como canchas con césped sintético, vestuarios y estacionamiento. No obstante, Canchea y Quierojugar también ofrecen una buena variedad de opciones en términos de canchas deportivas.

En resumen, si bien todas estas plataformas comparten un objetivo común de facilitar la reserva de canchas deportivas en línea, cada una tiene características y enfoques únicos.
