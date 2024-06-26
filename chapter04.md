# Capítulo IV: Product Design
## 4.1. Style Guidelines.
Un **Style Guideline** es un conjunto de reglas y normas que definen cómo se debe redactar, diseñar o presentar documentos, contenido web, software u otros trabajos creativos. A continuación, se detallan las especificaciones de los parámetros implementados en la estructura del proyecto. 
### 4.1.1. General Style Guidelines

**Overview:** <td>Deseamos capturar la atención del usuario desde el inicio mediante la creación y el diseño de una perspectiva del producto que establezca una conexión inmediata y reconocible.</td>

**Brand overview**

<td>Somos una compañía recién creada llamada "Gymfinity" que quiere mejorar la salud de todos nuestros usuarios mediante ayuda personalizada.
Por esta razón, nos reunimos y trabajamos con cooperación, eficencia y responsabilidad.</td>
<br><br>

**Misión:** <td>Nuestra misión es buscar respeto, colaboración, humildad y empatía en todas nuestras acciones. Escuchamos y actuamos sobre las mejores ideas de nuestros grupos de interés para lograr el mayor impacto. Reconocemos los esfuerzos de todos los involucrados en nuestro trabajo vital y apoyamos sus diversas necesidades.</td>

**Visión:** <td>Nuestra visión es un mundo donde todos tengan la oportunidad de llevar una vida saludable.</td>

**Brand Name:** <td>Como la startup se trata de querer ayudar a la gente a ejercitarse y comer sano, conectando al usuario con coaches y nutriólogos. Por esto, hemos decidido usar FlexPal como el nombre del producto, "Flex" de flexionar y "Pal" de amigo.</td>

<!-- Imagen!-->

**Typography:** <td>El tamaño de las tipografías elegido por el equipo fueron:</td>
<img src="assets/chapter04/Typography-stylesheet.png" alt="Typography">
Imagen 31 - Typography

**Colors:** <td></td>
<img src="assets/chapter04/Colors-stylesheet.png" alt="Colors">
Imagen 32 - Colors

### 4.1.2. Web Style Guidelines
<td>Para FlexPal, estamos planeando desarrollar una plataforma web. Por lo tanto, implementaremos un diseño adaptable (conocido como Web Responsive Design) con el objetivo de optimizar la presentación de información en cualquier dispositivo. Esto asegurará que el contenido se mantenga intacto y, en última instancia, mejorará la experiencia del usuario.</td>
<br><br>
<td>Como equipo, hemos optado por incorporar el patrón de diseño en forma de Z en nuestro sitio web. Esta técnica de diseño web es altamente efectiva para mejorar la experiencia del usuario, ya que guía su atención hacia los elementos clave y potencia la eficacia del contenido en la página. Por lo general, colocamos el logotipo en la esquina superior izquierda, asegurándonos de que sea lo primero que llame la atención del usuario. Justo enfrente, en la esquina superior derecha, ubicamos la barra de navegación, acompañada de un llamado a la acción destacada.</td>

## 4.2. Information Architecture
<td>Esta sección se basa principalmente del contenido visual, los estilos, los tags, etc, que se tomarán en cuenta para nuestra web y landing page de AquilaFacil. Se verá los tópicos de Organization Systems, Labeling Systemes, SEO and Meta Tags y Searching y Navigation Systems.</td>

### 4.2.1. Organization Systems
**Menú Principal**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Home</td>
            <td style="text-align: left">La página de inicio puede mostrar una vista general del servicio y destacar las características clave.</td>
        </tr>
        <tr>
            <td>Suscriptions</td>
            <td style="text-align: left">La página que ofrece los planes de suscripción para beneficios específicos con diferentes costos para cualquier tipo de presupuesto.</td>
        </tr>
        <tr>
            <td>Testimonials</td>
            <td style="text-align: left">La página que ofrece a la los usuarios comentarios y calificaciones sobre el servicio.</td>
        </tr>
        <tr>
            <td>Contact</td>
            <td style="text-align: left">La página que ofrece la manera más eficiente en caso de el usuario tener alguna duda o querer compartir algo con nosotros.</td>
        </tr>
        <tr>
            <td>Log In</td>
            <td style="text-align: left">La página para que el usuario ingrese a su sesión. En caso de no tener sesión hay una sección para poder registrarse gratis al servicio web.</td>
        </tr>
    </body>
</table>
<br><br>

**Página de Suscriptions**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Lista de planes de suscripción</td>
            <td style="text-align: left">La página mostrará todos los planes que ofrece el servicio.</td>
        </tr>
        <tr>
            <td>Detalles de planes</td>
            <td style="text-align: left">La página mostrará los detalles de todos los planes que ofrece el servicio.</td>
        </tr>
    </body>
</table>
<br><br>


**Página de Testimonials**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Lista de testimonios</td>
            <td style="text-align: left">La página mostrará todos lod títulos de los 10 primeros testimonios dados por otros usuarios.</td>
        </tr>
        <tr>
            <td>Detalles de planes</td>
            <td style="text-align: left">La página mostrará con mayor detalle todos los comentarios dejados por los usuarios.</td>
        </tr>
    </body>
</table>
<br><br>

**Página de Contact:** <td>Proporciona información de contacto y formularios para consultas</td>
<br><br>

**Página de Log In**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Registro y autenticación</td>
            <td style="text-align: left">La página de inicio puede mostrar una vista general del servicio y destacar las características clave.</td>
        </tr>
    </body>
</table>

<br>


**Otras páginas y funciones**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Perfil de usuario</td>
            <td style="text-align: left">Permite a los usuarios gestionar su perfil y la información personal.</td>
        </tr>
        <tr>
            <td>Configuraciones</td>
            <td style="text-align: left">Permite a los usuarios y técnicos configurar sus preferencias.</td>
        </tr>
        <tr>
            <td>Pagina acerca de nosotros</td>
            <td style="text-align: left">Información sobre la empresa o la aplicación.</td>
        </tr>
        <tr>
            <td>Ayuda y soporte</td>
            <td style="text-align: left">Recursos de ayuda, preguntas frecuentes y opciones de asistencia.</td>
        </tr>
    </body>
</table>

**Barra de navegación:** <td>Una barra de navegación clara y consistente en la parte superior de cada página facilita la navegación entre las secciones principales de la aplicación.</td>

**Responsive design:** <td>La aplicación debe ser fácil de usar tanto en dispositivos de escritorio como en dispositivos móviles, adaptando la interfaz de usuario según
el tamaño de la pantalla.</td>

### 4.2.2. Labeling Systems
<td>Para los sistemas de etiquetado, hemos optado por organizar el contenido mediante encabezados que agrupen las secciones a las que el usuario puede acceder. De esta manera, el usuario sabe dónde hacer clic para acceder a las secciones correspondientes.</td>

<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Home</td>
            <td style="text-align: left">Sección principal a la cual llegará el usuario al entrar al link de la aplicación web.</td>
        </tr>
        <tr>
            <td>Suscriptions</td>
            <td style="text-align: left">En esta sección, se podrán ver los planes y tarifas disponibles con los cuales contamos.</td>
        </tr>
        <tr>
            <td>Testimonios</td>
            <td style="text-align: left">Aquí los clientes pondrán sus reseñas y comentarios acerca del servicio que se les brindó.</td>
        </tr>
        <tr>
            <td>Contacto</td>
            <td style="text-align: left">Esta es la sección en la cual se le brindará al usuario todos los canales por los cuales nos puede contactar.</td>
        </tr>
    </body>
</table>

### 4.2.3. SEO Tags and Meta Tags
<td>Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda.</td>
<br><br>

**Titulo** 
<br>
<td>Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda.</td>

`<title>Register your processes with FlexHub</title>`

**Codificación de caracteres** 
<br>
<td>Se decidió usar el utf-8 por la eficiencia de memoria. Es más eficiente en términos de memoria para caracteres del BMP (Plano Multilingüe Básico, que incluye la mayoría de los caracteres comunes).</td>

`<meta charset="utf-8">` 

**Descripción** 
<br>
<td>Esta etiqueta meta nos permite ofrecer un resumen del contenido de la página web. En ella, proporcionamos una breve descripción de lo que los usuarios pueden esperar visualizar en la página.</td>

`<meta name="description" content="FlexPal is a web application focused on helping exercising and eating nutritionally"/>` 

**Palabras clave** 
<br>
<td>En esta etiqueta se pone las palabras claves relacionadas con el tema o contenido de la página web.</td>

`<meta name="keywords" content="exercise, eat, nutrition, coach, nutritionist, professionals"/>` 

**Autor y derechos de autor** 
<br>
<td>Se utiliza para registrar la información del autor de la página web y la propiedad y derechos de autor.</td>

`<meta name="author" content="FlexHub"/>` <br>
`<meta name="copyright" content="Copyright FlexHub team" />` 

### 4.2.4. Searching Systems
<td>El motor de búsqueda es fundamental para que los usuarios encuentren rápidamente detalles específicos</td>
<br><br>

**Características claves**
- *Busqueda por objetivo:* <td>Los usuarios podrán buscar dependiendo si dessean mejorar en aspectos físicos y saludables mendiante ejercicio o alimenación.</td>
- *Busqueda por características:* <td>Los usuarios podrán buscar profesionales por características específicas como: bajar de peso, definir/tonificar, volumen, etc.</td>
- *Filtros avanzados:* <td>Se proporcionarán filtros para refinar la búsqueda, como calificaciones y disponibilidad.</td>
- *Resultados revelantes:* <td>El sistema de búsqueda mostrará resultados revelantes y oirdenaelos de acuerdo con los criterio deseados por el usuario.</td>

### 4.2.5. Navigation Systems
<td>El Sistema de Navegación es la estructura que permite a los usuarios desplazarse eficientemente entre las distintas secciones y páginas de la aplicación</td>
<br><br>

**Estructura de navegación:** <td> El Sistema de Navegación constará de las siguientes secciones principales en la barra de navegación</td>

- Home
- Susriptions
- Testimonials
- Contact
- Log In

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
**Landing Page para Desktop Web Browser**
<img src="assets/chapter04/LandingaPage-wireframe-desktop.png" alt="Landing Page web wireframe">
Imagen 33 - Landing Page web Wireframe

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=1%3A2&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

**Landing Page para Mobile Web Browser**
<img src="assets/chapter04/LandingPage-wireframe-mobile.png" alt="Landing Page mobile wireframe">
Imagen 34 - Landing Page mobile Wireframe

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=38%3A140&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

### 4.3.2. Landing Page Mock-up
**Landing Page para Desktop Web Browser**
<img src="assets/chapter04/Web Browser-landingPage.png" alt="Landing Page (Mock up) web">
Imagen 35 - Landing Page web Mock-up

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=40%3A141&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

**Landing Page para Mobile Web Browser**
<img src="assets/chapter04/Mobile Browser-landingPage.png" alt="Landing Page (Mock up) mobile">
Imagen 36 - Landing Page mobile Mock-up

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=56%3A288&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

**Web Application para Desktop Web Browser**
<br><br>
<img src="assets/chapter04/Web Application Desktop-wireframe.png" alt="Web Application Deskktop">
Imagen 37 - Web Application web Wireframe

*Iniciar sesión*<br>
<img src="assets/chapter04/Log In-wireframe.png" alt="Log in wireframe">
Imagen 38 - Web Application Log in Wireframe

*Crear cuenta*<br>
<img src="assets/chapter04/Register-wireframe.png" alt="Register wireframe">
Imagen 39 - Web Application Register Wireframe

*Mi perfil*<br>
<img src="assets/chapter04/Profile-wireframe.png" alt="My profile wireframe">
Imagen 40 - Web Application My profile Wireframe

*Elegir plan de pago*<br>
<img src="assets/chapter04/Suscriptions-wireframe.png" alt="Suscriptions plans wireframe">
Imagen 41 - Web Application Suscriptions plan Wireframe

*Pasarela de pagos*<br>
<img src="assets/chapter04/Payment hall-wireframe.png" alt="Payment hall wireframe">
Imagen 42 - Web Application Payment Hall Wireframe

<img src="assets/chapter04/Confirm payment-wireframe.png" alt="Confirm payment wireframe">
Imagen 43 - Web Application Confirm Payment Wireframe
<br><br>

*Escribir testimonios*<br>
<img src="assets/chapter04/Write testimonials-wireframe.png" alt="Testimonials wireframe">
Imagen 44 - Web Application Testimonials Wireframe

*Escribir dudas/quejas*<br>
<img src="assets/chapter04/Complaints-wireframe.png" alt="Doubt/Complaints wireframe">
Imagen 45 - Web Application Doubt/Complaints Wireframe

*Preferencias del usuario*<br>
<img src="assets/chapter04/User preferences-wireframe.png" alt="User Preference wireframe">
Imagen 46 - Web Application User Preference Wireframe

*Lista de perfiles profesionales*<br>
<img src="assets/chapter04/Professionals profiles list-wireframe.png" alt="Professionals profiles list wireframe">
Imagen 47 - Web Application Professionals Profiles List Wireframe

*Perfil del profesional*<br>
<img src="assets/chapter04/Professionals profiles-wireframe.png" alt="Professional profile wireframe">
Imagen 48 - Web Application Professionals Profile Wireframe

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=72%3A1409&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

**Web Application para Mobile Web Browser**
<img src="assets/chapter04/Web Application Mobile-wireframe.png" alt="Web Application Mobile">
Imagen 49 - Web Application mobile Wireframe

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=62%3A911&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

### 4.4.2. Web Applications Wireflow Diagrams
**User goal: Creación de cuenta**
<img src="assets/chapter04/op-wireflow1.png" alt="wireflow1">
Imagen 50 - Wireflow Diagram - User Goal 1: Account creation

**User goal: Establecimiento de objetivos**
<img src="assets/chapter04/op-wireflow2.png" alt="wireflow1">
Imagen 51 - Wireflow Diagram - User Goal 2: Setting objects

**User goal: Acceso a contenido exclusivo**
<img src="assets/chapter04/op-wireflow3.png" alt="wireflow1">
Imagen 52 - Wireflow Diagram - User Goal 3: Access to exclusive content

[Enlace para acceder al Wireflow](https://lucid.app/lucidchart/06e5a9b6-2a6f-4ca7-ac20-4729765c13d4/edit?viewport_loc=-5553%2C-4577%2C15457%2C8180%2C8M5xaniXGb-W&invitationId=inv_65cf465b-fcaf-444a-b6bf-edd39644b707)
### 4.4.3. Web Applications Mock-ups

*Inicio*
<img src="assets/chapter04/app web-mock ups/Home-mock up.png" alt="Home mock up">
Imagen 53 - Web Application Home Mock-up

*Crear de cuenta*
<img src="assets/chapter04/app web-mock ups/Register-mock up.png" alt="Register mock up">
Imagen 54 - Web Application Register Mock-up

*Iniciar sesión*<br>
<img src="assets/chapter04/app web-mock ups/Log In-mock up.png" alt="Log in mock up">
Imagen 55 - Web Application Log in Mock-up

*Mi perfil*<br>
<img src="assets/chapter04/app web-mock ups/Profile-mock up.png" alt="My profile mock up">
Imagen 56 - Web Application Profile Mock-up

*Preferencias del usuario*<br>
<img src="assets/chapter04/app web-mock ups/User preferences-mock up.png" alt="User Preference mock up">
Imagen 57 - Web Application User Preference Mock-up

*Objetivos del usuario*<br>
<img src="assets/chapter04/app web-mock ups/Goals-mock up.png" alt ="Goals mock up">
Imagen 58 - Web Application User Goals Mock-up

*Elegir plan de pago*<br>
<img src="assets/chapter04/app web-mock ups/Suscriptions-mock up.png" alt="Suscriptions plans mock up">
Imagen 59 - Web Application Suscriptions plans Mock-up

*Pasarela de pagos*<br>
<img src="assets/chapter04/app web-mock ups/Payment hall-mock up.png" alt="Payment hall mock up">
Imagen 60 - Web Application Payment hall Mock-up

<img src="assets/chapter04/app web-mock ups/Corfirm payment-mock up.png" alt="Confirm payment mock up">
Imagen 61 - Web Application Confirm payment Mock-up
<br><br>

*Escribir testimonios*<br>
<img src="assets/chapter04/app web-mock ups/Write testimonials-mock up.png" alt="Testimonials mock up">
Imagen 62 - Web Application Testimonials Mock-up

*Escribir dudas/quejas*<br>
<img src="assets/chapter04/app web-mock ups/Complaints-mock up.png" alt="Doubt/Complaints mock up">
Imagen 63 - Web Application Doubt/Complaints Mock-up

*Lista de perfiles profesionales*<br>
<img src="assets/chapter04/app web-mock ups/Professionals profiles list-mock up.png" alt="Professionals profiles list mock up">
Imagen 64 - Web Application Profiles list Mock-up

*Perfil del profesional*<br>
<img src="assets/chapter04/app web-mock ups/Professionals profiles-mock up.png" alt="Professional profile wireframe">
Imagen 65 - Web Application Professional profile Mock-up

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=129%3A101&mode=design&t=Mjm0lJYxmxKPpxjm-1)
<br><br>

### 4.4.4. Web Applications User Flow Diagrams
**User goal: Creación de cuenta**
<td><b>Given</b> que el usuario ha ingresado sus datos de registro correctamente, 
<br><b>When</b> el usuario hace clic en el botón "Registrarse",

<b>Then</b> la cuenta del usuario se crea exitosamente y se le redirige a la página de inicio.</td>
<img src="assets/chapter04/user flow1.png" alt="user flow-crear cuenta">
Imagen 66 - User Flow Diagram - User Goal 1: Account creation
<br><br>

**User goal: Inicializacion de sesión**
<td>Explicación del flujo: El proceso comienza con el usuario accediendo a la aplicación desplegada. Luego, se le presentará un formulario en pantalla donde deberá ingresar su correo electrónico y contraseña para iniciar sesión. Si los datos son válidos, el sistema lo redirigirá al perfil del usuario. En caso contrario, permanecerá en la página de inicio de sesión y se le pedirá que vuelva a ingresar sus credenciales.</td><br><br>
<img src="assets/chapter04/user flow2.png" alt="user flow-iniciar sesión"><br>
Imagen 67 - User Flow Diagram - User Goal 2: Log in
<br><br><br>

**User goal: Visualización de perfil**
<td>Explicación del flujo: En la aplicación, siempre se mostrará una barra de navegación (navbar) en la parte superior. Cuando el usuario haga clic en su nombre, que están ubicados en el extremo derecho de la barra de navegación, podrá acceder a su perfil de usuario y visualizar sus datos.</td><br><br>
<img src="assets/chapter04/user flow3.png" alt="user flow-ver perfil">
Imagen 68 - User Flow Diagram - User Goal 3: Profile display
<br><br><br>

**User goal: Establecimineto de objetivos**
<td><b>Given</b> que el usuario ha iniciado sesión en su cuenta, 
<br><b>When</b> el usuario selecciona la opción "Establecer objetivos" en su perfil,

<b>Then</b> el usuario puede ingresar sus metas de salud y fitness, incluyendo peso objetivo, porcentaje de grasa corporal, etc.</td>
<img src="assets/chapter04/user flow4.png" alt="user flow-establecer objetivos">
Imagen 69 - User Flow Diagram - User Goal 2: Settings objetives<br><br>

**User goal: Acceso a contenido exclusivo**
<td><b>Given</b> que el usuario ha adquirido una suscripción premium o acceso exclusivo,
<br><b>When</b> el usuario accede a la sección de contenido premium,

<b>Then</b> el usuario puede disfrutar de características exclusivas, como videos de entrenamiento, artículos, etc.</td>
<img src="assets/chapter04/user flow5.png" alt="user-flow acceder a contenido exclusivo">
Imagen 70 - User Flow Diagram - User Goal 2: Access to exclusive content
<br>

[Enlace para acceder a los User Flows](https://lucid.app/lucidchart/06e5a9b6-2a6f-4ca7-ac20-4729765c13d4/edit?viewport_loc=-14424%2C-7724%2C30264%2C15085%2CnN5xv8hT21Jk&invitationId=inv_65cf465b-fcaf-444a-b6bf-edd39644b707)

## 4.5. Web Applications Prototyping
Nuestro prototipo la web application sería algo así
<img src="assets/chapter04/prototype.png">
Imagen 71 - Prototype

[Enlace para acceder al Figma](https://www.figma.com/file/Pd1z1lfG0NMz9fbfCVBHdC/FlexPal?type=design&node-id=34%3A117&mode=design&t=Mjm0lJYxmxKPpxjm-1)

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
**Nuestro diagrama de contexto muestra las relaciones principales de “”. 
Este se relaciona primeramente con sus tres tipos de usuarios 
(Cliente, Especialista y Coach) y dos sistemas externos a la 
aplicación web. Communication System para realizar reuniones 
(Zoom o Google Meet) y Analysis and monotoring System para 
realizar una recopilación y análisis para el Cliente 
(Adobe Analytics)**


<img src="assets/chapter04/Context Diagram.png" alt="Context Diagram">
<br>
Imagen 72 - Context Diagram

[Enlace para acceder al Context Diagram](https://online.visual-paradigm.com/w/cmsorqxf/diagrams/#diagram:workspace=cmsorqxf&proj=0&id=5&type=C4Model)

### 4.6.2. Software Architecture Container Diagrams
**En el diagrama de contenedores, se observan 
la aplicación web, la landing page y la aplicación móvil. 
Cada una de estas realiza solicitudes a la API de la aplicación.**

<img src="assets/chapter04/Container Diagram.png" alt="Container Diagram">
<br>
Imagen 73 - Container Diagram

[Enlace para acceder al Container Diagram](https://online.visual-paradigm.com/w/cmsorqxf/diagrams/#diagram:workspace=cmsorqxf&proj=0&id=1&type=C4Model)

### 4.6.3. Software Architecture Components Diagrams
**Se muestra los componentes. Se encuentra la seguridad para 
la cuenta del usuario, el progreso, el análisis del progreso 
y la comunicación (Security Service, Client Progress Service,
Analysis and Monitoring Component y Communication Component)**

<img src="assets/chapter04/Component Diagram.png" alt="Component Diagram">
<br>
Imagen 74 - Component Diagram

[Enlace para acceder al Component Diagram](https://online.visual-paradigm.com/w/cmsorqxf/diagrams/#diagram:workspace=cmsorqxf&proj=0&id=2&type=C4Model)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
<img src="assets/chapter04/Class Diagram.png" alt="Class Diagram">
<br>
Imagen 75 - Class Diagram

### 4.7.2. Class Dictionary
<table>

  <tr>
    <td colspan="1"><p>N</p></td>
    <td colspan="1">Entidad</td>
    <td colspan="1">Nombre de Tributos</td>
    <td colspan="1">Definicion</td>
    <td colspan="1">Tipo de Datos</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3">1</td>
    <td colspan="1" rowspan="3">Usuario</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Usuario<br>(Numero de Usuarios)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">nombre</td>
    <td colspan="1" valign="top">Nombre del Usuario</td>
    <td colspan="1" valign="top">string</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">email</td>
    <td colspan="1" valign="top">Email del Usuario</td>
    <td colspan="1" valign="top">string</td>
  </tr>

  <tr>
    <td colspan="1" rowspan="2">2</td>
    <td colspan="1" rowspan="2">Coach</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Coach<br>(Identificador)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">especialidad</td>
    <td colspan="1" valign="top">Especialidad de Coach</td>
    <td colspan="1" valign="top">string</td>
  </tr>

  <tr>
    <td colspan="1" rowspan="2">3</td>
    <td colspan="1" rowspan="2">Nutricionista</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Nutricionista<br>(Identificador)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">especialidad</td>
    <td colspan="1" valign="top">Especialidad de Nutricionista</td>
    <td colspan="1" valign="top">string</td>
  </tr>

  <tr>
    <td colspan="1" rowspan="3">4</td>
    <td colspan="1" rowspan="3">Cliente</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Cliente<br>(Identificador)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">suscripcion</td>
    <td colspan="1" valign="top">Tipo de Suscripcion</td>
    <td colspan="1" valign="top">suscripcion</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">progreso</td>
    <td colspan="1" valign="top">Avance de Cliente</td>
    <td colspan="1" valign="top">progreso</td>
  </tr>

  <tr>
    <td colspan="1" rowspan="3">5</td>
    <td colspan="1" rowspan="3">Suscripcion</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Suscripcion<br>(Clave de membresia)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">precio</td>
    <td colspan="1" valign="top">Costo</td>
    <td colspan="1" valign="top">float</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">servicios</td>
    <td colspan="1" valign="top">Lo que ofrece</td>
    <td colspan="1" valign="top">string</td>
  </tr>

  <tr>
    <td colspan="1" rowspan="6">6</td>
    <td colspan="1" rowspan="6">Progreso</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Progreso<br>(Identificador por Cliente)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">fecha</td>
    <td colspan="1" valign="top">Fecha de Registro</td>
    <td colspan="1" valign="top">date</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">peso</td>
    <td colspan="1" valign="top">Peso en KG</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">calorias_quemadas</td>
    <td colspan="1" valign="top">Calorias quemadas despues<br>de cada dia o semana</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">distancia_corrida</td>
    <td colspan="1" valign="top">Cantidad corrida del Cliente</td>
    <td colspan="1" valign="top">float</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">ejercicios_realizado</td>
    <td colspan="1" valign="top">Ejecicios realizados del Cliente</td>
    <td colspan="1" valign="top">List<.Ejercicio></td>
  </tr>

  <tr>
    <td colspan="1" rowspan="3">7</td>
    <td colspan="1" rowspan="3">ReunionVirtual</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Reunion<br>(url de Reunion)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">fecha</td>
    <td colspan="1" valign="top">Fecha de Reunion</td>
    <td colspan="1" valign="top">date</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">duracion</td>
    <td colspan="1" valign="top">Tiempo de Reunion</td>
    <td colspan="1" valign="top">time</td>
  </tr> 

  <tr>
    <td colspan="1" rowspan="3">8</td>
    <td colspan="1" rowspan="3">PlanAlimentario</td>
    <td colspan="1" valign="top">ID</td>
    <td colspan="1" valign="top">Codigo de Plan<br>(Identificador por Cliente)</td>
    <td colspan="1" valign="top">int</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">descripcion</td>
    <td colspan="1" valign="top">Descripcion<br>(Explica el Plan Alimentario)</td>
    <td colspan="1" valign="top">string</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">recomendaciones</td>
    <td colspan="1" valign="top">Lista de comidas recomendables</td>
    <td colspan="1" valign="top">string</td>
  </tr> 

</table>

## 4.8. Database Design. 
### 4.8.1. Database Diagram.
<img src="assets/chapter04/Database Diagram.png" alt="Database Diagram">
Imagen 76 - Database Diagram

[Enlace para acceder al Vertabelo](https://my.vertabelo.com/doc/pM7c21fm3tWnk1CxtixSdD4CMRheV7rR)
