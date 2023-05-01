# Informe de obligatorio ISA
---------------------------------------------------------------------------

## Materia: INGENIERIA DE SOFTWARE AGIL 1

### Equipo 5 - Mini proyecto
### Estudiantes: Juan Manuel Rabuñal - Maximiliano Pascale - Sebastian Silveira
---------------------------------------------------------------------------

### Herramienta para gestión del proyecto
#### Azure Devops: https://dev.azure.com/Pascale-Rabunal-Silvera/Mini%20Proyecto%202023

### Versionado
#### Repositorio Github: https://github.com/ORT-ISA1/pascale-rabunal-silvera
---------------------------------------------------------------------------

## Definición del marco de trabajo
### Marco general del scrum
El resultado del proyecto es poder descubrir, idear y prototipar un MVP (Minimum Viable Product) de una aplicación móvil para ayudar al usuario a reservar canchas para realizar actividades deportivas.

Dicho marco de trabajo es desconocido para los integrantes del equipo por lo que va a haber una cierta curva de aprendizaje dentro del desarrollo de la aplicación.
Se va a necesitar de innovación, creatividad, interacción y buena comunicación con el usuario para lograr un producto que nos diferencia y logre fidelidad con el usuario ya que ya hay varias apps en el mercado.

El equipo de desarrollo va a utilizar la forma de trabajo basada en SCRUM y además optamos por seguir un ciclo de vida evolutivo en el desarrollo del producto:

![image](https://user-images.githubusercontent.com/64442147/235362931-867b5b72-dfb6-4173-8678-b1afa27c7d91.png)

### Supuestos Efectuados
1.	La aplicación va a ser únicamente para Uruguay.
2.	La descarga de la aplicación será gratuita.
3.	Únicamente va a estar en Español

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
1.	El título debe ser breve y muy descriptivo.
2.	La narrativa debe tener una estructura que explique qué hace el usuario, qué quiere y por qué lo quiere.
3.	La estimación de tiempo debe estar en horas ideales de trabajo y estar en valores predefinidos.
4.	Los criterios de aceptación deben ser claros y presentados como escenarios, explicando el contexto, el evento y los resultados esperados.

#### Definición de Done
Los criterios para determinar qué historias terminaron con éxito su proceso de implementación serán: 
1.	Las pruebas automatizadas y manuales han sido completadas satisfactoriamente.
2.	El elemento ha sido revisado por un par o por el equipo de desarrollo.
3.	El elemento ha sido probado y se ha verificado que funciona correctamente en diferentes entornos.
4.	El elemento ha sido integrado y desplegado en el entorno de producción.
5.	La documentación ha sido actualizada y se ha revisado para asegurarse de que esté completa y precisa.

### Versionado

Se crea el repositorio https://github.com/ORT-ISA1/pascale-rabunal-silvera 

Se trabaja con dos ramas “main” y “develop”, en esta última cada miembro del equipo trabajará de acuerdo a las buenas prácticas aprendidas. 

Trabajaremos sobre “develop”, donde cada miembro creara sus ramas y trabaja sobre ellas. Una vez completado el desarrollo deberá mergear a “develop”.

Al finalizar cada sprint “develop” será mergeada a “main”.

---------------------------------------------------------------------------

## Características deseadas de la población uruguaya 

### Entrevistas 

Se realizan entrevistas a potenciales interesados en el uso de la aplicación a desarrollar. 
Se les informa de las características que tendrá el MVP y de la interacción con los entrevistados surgen las siguiente comentarios
Es importante aclarar, que estas características son las deseadas por los entrevistados, no significa un compromiso para su desarrollo. 

#### Variedad de canchas y deportes disponibles: 
Según lo expresado por los entrevistados es importante que la aplicación ofrezca una amplia variedad de canchas deportivas y deportes para reservar. 
Para priorizar esta característica, deberemos realizar encuestas para conocer los deportes y tipos de canchas que los usuarios más frecuentan y desean reservar. 
Para validarla, deberíamos hacer pruebas de usabilidad en las que los usuarios busquen y reserven canchas y deportes para comprobar que la aplicación ofrece suficientes opciones.

#### Facilidad de uso: 
La aplicación debe ser fácil y amigable de usar, con una interfaz intuitiva que permita reservar canchas en pocos pasos. 
Para priorizarlo, deberían realizarse pruebas de usabilidad en las que los usuarios interactúen con la aplicación y reporten cualquier dificultad o confusión. 
Para validarla, se deberán hacer pruebas con usuarios reales y medir su tiempo de interacción con la aplicación y la tasa de éxito de reservas.

#### Pago en línea seguro: 
La aplicación debe ofrecer opciones de pago en línea seguras y confiables, para evitar el riesgo de fraudes y garantizar la seguridad de los usuarios. 
Para priorizar esta característica, se debería realizar encuestas para conocer las preferencias de los usuarios respecto a los métodos de pago en línea. 
Para validarla, deberíamos hacer pruebas de seguridad en las que se compruebe que los datos de pago están protegidos y encriptados.

#### Comentarios y valoraciones de otros usuarios: 
La aplicación podría ofrecer un sistema de comentarios y valoraciones de otros usuarios, para ayudar a los usuarios a elegir las mejores canchas y a mejorar la calidad del servicio. 
Para priorizarlo, deberían realizarse pruebas en las que los usuarios interactúen y así conocer si los usuarios valoran y utilizan este tipo de información. 
Para validarla, podrías hacer pruebas con usuarios en las que se compruebe que los comentarios y valoraciones son útiles y confiables.

#### Recordatorios y notificaciones: 
La aplicación podría enviar recordatorios y notificaciones a los usuarios para recordarles sus reservas y para informarles sobre nuevas ofertas y descuentos. 
Para priorizarlo, deberían realizarse pruebas en las que los usuarios interactúen y así conocer si los usuarios valoran y utilizan este tipo de información. 
Para validarla, podrías hacer pruebas con usuarios en las que se compruebe que las notificaciones son útiles y no resultan molestas o intrusivas.


