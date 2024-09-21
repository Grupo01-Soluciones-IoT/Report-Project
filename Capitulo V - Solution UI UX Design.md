![Sensores - Applications Mock-ups](https://github.com/user-attachments/assets/279550d4-807e-4218-adab-3f84f4c0c5a7)# Capítulo V: Solution UI/UX Design

## 5.1 Style Guidelines

### 5.1.1. General Style Guidelines


### Brand Overview
La creciente necesidad de optimizar la gestión agrícola en un entorno cada vez más afectado por el cambio climático y la variabilidad de los recursos naturales ha puesto de manifiesto la importancia de contar con herramientas tecnológicas avanzadas. **IAgroT** surge como respuesta a esta necesidad, proporcionando una solución integral que combina dispositivos IoT y una plataforma móvil para el monitoreo y gestión de cultivos en tiempo real. Nuestro equipo ha desarrollado esta solución para ofrecer a los agricultores peruanos una herramienta eficiente, accesible y personalizada que les permita maximizar la productividad de sus tierras y garantizar la sostenibilidad a largo plazo de sus cultivos.

### Brand Name
El nombre del software identificado es **IAgroT**. Este nombre surgió a partir de la necesidad de integrar tecnología avanzada en la agricultura, enfocándonos en soluciones que optimicen la gestión de cultivos a través de dispositivos IoT. El equipo eligió una combinación de "I" por Internet y "Agro", que representa el sector agrícola, para resaltar la conexión directa entre tecnología e innovación en el campo. La letra "T" representa la transformación digital en la agricultura. Esperamos que los agricultores y técnicos asocien IAgroT con herramientas tecnológicas que modernizan y optimizan sus procesos agrícolas, facilitando el monitoreo y gestión eficiente de sus cultivos.

<p align="center">
  <img src="images/Iagrot-logo-blacksite.png" alt="Brand Logo - IagrOT" width="250"/>
</p>

### Typography
La tipografía es un elemento esencial para estructurar y organizar el lenguaje visual de todas las plataformas desarrolladas para IAgroT. Es fundamental que las fuentes seleccionadas sean legibles y contribuyan a mejorar la experiencia del usuario en la interfaz. Por ello, se ha elegido la fuente **Nunito** como la principal, una tipografía sans-serif moderna y amigable que se adapta bien al enfoque tecnológico del proyecto. Nunito destaca por su legibilidad tanto en pantallas pequeñas como grandes, aportando claridad y consistencia en todos los dispositivos utilizados por los agricultores y técnicos.

Como tipografía secundaria, se ha optado por **Roboto Flex**, una fuente versátil y flexible que complementa a Nunito. Roboto Flex será utilizada en textos secundarios y áreas que requieran una mayor variabilidad en peso y estilo, aportando dinamismo sin perder la coherencia visual en la experiencia del usuario.

<img src="images/Iagrot - Nunito - Font.png" alt="Nunito Font - IagrOT" width="250"/>
<img src="images/Iagrot - Roboto-Flex - Font.png" alt="Roboto Flex Font - IagrOT" width="250"/>

### Head
<img src="images/Head - Style Guidelines.png" alt="Head - Style Guidelines"/>

### Body
<img src="images/Body - Style Guidelines.png" alt="Body - Style Guidelines"/>

### Colors
<img src="images/Colors - Style Guidelines.png" alt="Colors - Style Guidelines"/>

### Spacing
<img src="images/Spacing - Style Guidelines.png" alt="Spacing - Style Guidelines"/>


#### Tono de comunicación y lenguaje aplicado
- **Color Primario:** El color primario (#049404) refleja la esencia de la naturaleza y la vida agrícola. Este verde vibrante representa el crecimiento, la frescura y la sustentabilidad, valores centrales de IAgroT. Se ha elegido para transmitir una sensación de confianza y seguridad a los agricultores, ya que está vinculado con la idea de campos fértiles y una agricultura próspera.
- **Color Secundario:** El color secundario (#A2CA71) aporta un tono suave y relajante asociado con el bienestar y el equilibrio natural. Este verde más claro evoca esperanza y renovación, conectando al usuario con el ciclo natural de la vida agrícola.
- **Blanco:** El blanco (#FFFFFF) se utiliza para transmitir claridad y simplicidad en la interfaz. Este color permite que los elementos importantes resalten, brindando un aspecto limpio y moderno que facilita la navegación y la lectura.
- **Negro:** Los tonos de negro (#000000, #1D1D1D, #282828) son utilizados para dar un toque de elegancia y profesionalismo a la plataforma. Estos colores refuerzan la seriedad de los datos presentados, asegurando que la tecnología de IAgroT se perciba como confiable y precisa.
- **Grises:** Los tonos de gris (#333333, #4F4F4F, #828282, #BDBDBD, #E0E0E0) aportan neutralidad y equilibrio al diseño, sirviendo de fondo para resaltar la información esencial.

  El lenguaje utilizado en la plataforma será accesible, profesional y orientado al soporte, ya que IAgroT busca no solo ofrecer soluciones tecnológicas, sino también acompañar al agricultor en su camino hacia la optimización de sus cultivos. La comunicación debe ser clara, confiable y cercana, promoviendo la eficiencia y el uso adecuado de la tecnología para transformar la agricultura.


### 5.1.2. Web, Mobile and IoT Style Guidelines

Desarrollaremos una aplicación adaptable a cualquier dispositivo tecnológico sin comprometer el diseño del contenido. Por esta razón, se considerará cada tipo de dispositivo, garantizando que el contenido esté organizado de la forma más adecuada para cada uno.

<img src="images/Responsive - Web, Mobile and IoT Style Guidelines.png" alt="Spacing - Style Guidelines"/>

Emplearemos el patrón **Z** en nuestro diseño, comenzando con la identificación de nuestra marca que se ubicará en la esquina superior izquierda. Desde ahí, el usuario iniciará su interacción visual con el logotipo de IAgroT. Luego se desplazará horizontalmente hacia la derecha, donde encontrará las opciones principales como "Inicio", "Nosotros", "Servicios" y "Contáctanos", facilitando su navegación por el sitio. A continuación, el usuario bajará verticalmente para interactuar con el contenido principal, donde verá el mensaje destacado sobre la agricultura inteligente junto con una imagen representativa. Finalmente, el recorrido terminará en la parte inferior, donde podrá acceder a los enlaces de descarga de la aplicación en Google Play y App Gallery, asegurando un acceso fácil a las plataformas móviles.

Este flujo visual asegura que el usuario capte de manera eficiente los elementos clave del sitio, manteniendo una estructura intuitiva y fluida.

<img src="images/Z Pattern - Web, Mobile and IoT Style Guidelines.png" alt="Spacing - Style Guidelines"/>



## 5.2. Information Architecture

### 5.2.1. Organization Systems

En esta sección, describiremos cómo se implementarán diferentes métodos de organización visual para cada uno de nuestros segmentos de usuarios en la plataforma IAgroT, asegurando que el contenido esté estructurado de manera coherente y accesible.

### Segmento 1: Agricultores Pequeños y Medianos
**Jerárquica:**
- **Cultivos y Recursos:** 
  Los agricultores podrán acceder a una lista de sus cultivos y recursos. Esta información se organizará por categorías de cultivo (como frutas, vegetales, etc.) y por recursos (agua, fertilizantes), permitiendo a los usuarios navegar y monitorear el estado de cada elemento.
- **Recomendaciones de Gestión:**
  Se mostrarán recomendaciones personalizadas basadas en los datos recopilados en tiempo real. Estas recomendaciones estarán organizadas por prioridad (alta, media, baja) y secciones específicas de acción, como riego o fertilización.
- **Alertas de Condiciones Climáticas:**
  Las alertas se organizarán cronológicamente, mostrando primero las alertas más recientes o críticas que afecten a los cultivos.

**Secuencial:**
- **Configuración del Sistema de Monitoreo:**
  Los agricultores seguirán un conjunto de pasos para configurar el sistema de monitoreo. Esto incluirá la selección de sensores, la definición de umbrales de alerta, y la configuración de notificaciones.

### Segmento 2: Técnicos Agrícolas y Asesores
**Jerárquica:**
- **Lista de Agricultores:**
  Los técnicos podrán ver una lista de agricultores que están utilizando la plataforma, organizada por región o tipo de cultivo.
- **Análisis de Datos Agrícolas:**
  Los técnicos accederán a un panel de control donde los datos de los cultivos se organizan en gráficos y tablas por categorías como tipo de cultivo, salud del suelo, y uso de recursos.
- **Informes de Rendimiento:**
  Los informes generados se organizarán por fecha y tipo, facilitando la revisión de la evolución del rendimiento de los cultivos a lo largo del tiempo.

### Características Compartidas

**Jerárquica:**
- **Landing Page:**
  Información general sobre el uso de la plataforma IAgroT, con detalles sobre funcionalidades y ventajas, organizada de manera que los elementos más importantes aparezcan primero.
- **Reseñas:**
  Evaluaciones de usuarios sobre la efectividad de las herramientas y dispositivos utilizados, organizadas de manera cronológica.

**Matricial:**
- **Menú de Opciones:**
  Tanto agricultores como técnicos tendrán acceso a un menú principal con categorías específicas como "Monitoreo de Cultivos", "Alertas", "Configuraciones", y "Análisis de Datos".
- **Noticias y Recomendaciones:**
  Actualizaciones y sugerencias organizadas por temas relacionados con agricultura sostenible, nuevos productos y cambios climáticos.

### 5.2.2 Labeling Systems

Presentamos el sistema de etiquetado que permitirá a los usuarios de IAgroT acceder a la información relevante de manera rápida y eficiente.

- **Dashboard Principal:** "Home" – Información clave sobre el estado general de los cultivos y recursos, con gráficos de fácil interpretación.
- **Gestión de Cultivos:** "Manage Crops" – Sección donde los agricultores pueden añadir, editar o eliminar información sobre sus cultivos.
- **Monitoreo en Tiempo Real:** "Real-Time Monitoring" – Espacio donde se muestran datos en vivo del estado del cultivo y las condiciones ambientales.
- **Alertas y Notificaciones:** "Alerts" – Sección dedicada a mostrar todas las alertas activas relacionadas con el estado del cultivo y condiciones climáticas.
- **Configuraciones:** "Settings" – Sección donde los usuarios pueden ajustar preferencias de monitoreo, notificaciones, y gestionar perfiles.

### 5.2.3 SEO Tags and Meta Tags Systems

A continuación, se presentan las etiquetas SEO y Meta Tags empleadas en las páginas principales de la plataforma IAgroT para mejorar su visibilidad en motores de búsqueda.

- **Meta Title:** "IAgroT - Plataforma de Monitoreo Agrícola Inteligente"
- **Meta Description:** "Optimiza la gestión agrícola con IAgroT. Monitoreo en tiempo real, alertas climáticas y recomendaciones basadas en datos para maximizar la productividad."
- **Keywords:** "Agricultura Inteligente, IoT en Agricultura, Monitoreo de Cultivos, Gestión de Recursos, Alertas Climáticas"
- **Alt Text para Imágenes:** "Gráfico de monitoreo de cultivos en tiempo real", "Dispositivo IoT para agricultura sostenible".

### 5.2.4 Searching Systems

En esta sección se detallan los sistemas de búsqueda diseñados para facilitar la localización de información en la plataforma IAgroT.

### Segmento 1: Agricultores
- **Búsqueda de Cultivos:**
  Los agricultores podrán buscar información específica de sus cultivos utilizando filtros como tipo de cultivo, estado del crecimiento, y fecha de plantación. Los resultados se mostrarán en formato de lista con detalles resumidos, y un clic en un cultivo específico abrirá una vista detallada.
- **Búsqueda de Recomendaciones:**
  Los usuarios pueden aplicar filtros para buscar recomendaciones específicas basadas en la condición del cultivo, tipo de recurso (agua, fertilizante) o fecha.

### Segmento 2: Técnicos y Asesores
- **Búsqueda de Agricultores:**
  Los técnicos podrán buscar a agricultores específicos usando una barra de búsqueda o filtros avanzados como ubicación, tipo de cultivo, y nivel de interacción.
- **Análisis de Datos:**
  Los técnicos podrán buscar y filtrar datos históricos o específicos de cultivos para realizar análisis detallados.

### 5.2.5 Navigation Systems

Los sistemas de navegación han sido diseñados para guiar a los usuarios de manera intuitiva a través de las distintas funciones de la plataforma IAgroT.

- **Barra de Navegación Global:** 
  En la parte superior de todas las páginas, se encuentra una barra de navegación horizontal con enlaces a "Home", "Gestión de Cultivos", "Alertas", "Monitoreo en Tiempo Real", y "Configuraciones".
- **Menú Lateral para Aplicaciones Móviles:**
  En las versiones móviles, se utiliza un menú lateral desplegable donde los usuarios pueden acceder rápidamente a las secciones principales.

Estos sistemas garantizan una experiencia de usuario optimizada, facilitando la navegación y el acceso a la información relevante para cada segmento de usuarios en la plataforma IAgroT.

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

Las landing pages son herramientas clave para convertir visitantes en posibles clientes, utilizando elementos como mensajes atractivos e información detallada sobre el producto. Por esta razón, se decidió emplear esta herramienta, diseñando una versión preliminar tanto para dispositivos móviles como para computadoras.

En la versión móvil, se incluye el mismo contenido que en la versión de escritorio, pero reorganizado para adaptarse al tamaño de pantalla de los dispositivos móviles. Esta versión cuenta con un botón que facilita la navegación, permitiendo al usuario explorar la página de forma más cómoda. El diseño también es práctico y visualmente amigable, mejorando la experiencia del usuario.

Por otro lado, la versión para computadoras ofrece una estructura de ventanas con opciones claramente especificadas acompañadas de descripciones, para que el usuario pueda comprender fácilmente cada sección del sitio web. Además, se implementó una barra de navegación estática, asegurando su disponibilidad constante y facilitando una experiencia de navegación cómoda a lo largo de toda la landing page.


<img src="images/Selection Boxes - Style Guidelines.png" alt="Spacing - Style Guidelines"/>

Esta sección de "Cuadros de Selección" presenta los diferentes elementos interactivos que serán utilizados en la interfaz de IAgroT para mejorar la experiencia del usuario al gestionar y monitorear sus cultivos. Los cuadros de selección permiten elegir entre diferentes opciones de menú desplegable (dropdown), como la selección de tipos de cultivos o sensores IoT específicos.

- **Checkboxes y Toggles:** Estos elementos permitirán a los usuarios activar o desactivar diferentes funcionalidades, como el monitoreo en tiempo real o las alertas de condiciones climáticas. Los toggles también serán útiles para configurar opciones como el encendido y apagado de dispositivos IoT conectados.
- **Selector de fechas (Date Picker):** Este componente es esencial para planificar actividades agrícolas. Los usuarios podrán elegir fechas para programar el riego automático, la aplicación de fertilizantes o la cosecha.
- **Paginación:** Facilitará la navegación entre diferentes secciones de datos, permitiendo a los usuarios revisar historiales de monitoreo o análisis de rendimiento.
- **Breadcrumbs:** Ofrecerán una navegación clara a través de las distintas secciones de la aplicación, permitiendo a los usuarios moverse entre páginas de configuración, monitoreo y reportes.

Este diseño de cuadros de selección asegura que los agricultores puedan interactuar fácilmente con la plataforma, configurando y ajustando los sistemas de IoT de manera eficiente y organizada.

<img src="images/Buttons - Style Guidelines.png" alt="Spacing - Style Guidelines"/>

Este esquema de "Botones" se aplica al diseño de la interfaz de IAgroT y sigue una estructura clara para mantener la coherencia visual y funcional en toda la plataforma.

- **Color Primario y Secundario:** Los botones primarios, en verde intenso, se utilizarán para acciones clave dentro de la plataforma, como iniciar un monitoreo o confirmar una configuración. El color secundario, en un tono verde más claro, está destinado a acciones complementarias o menos urgentes.
- **Tamaños:** Los botones estarán disponibles en diferentes tamaños (pequeño, normal, mediano y grande) según la importancia de la acción y el contexto. Los botones grandes, por ejemplo, serán usados para acciones principales que requieren mayor visibilidad, mientras que los botones pequeños se utilizarán para opciones secundarias en secciones más específicas.
- **Full-width y comportamiento:** Los botones de ancho completo (full-width) se ajustarán al tamaño del dispositivo, proporcionando una experiencia óptima tanto en móviles como en pantallas más grandes. Los botones también tendrán diferentes estados (default, hover, active, disabled), permitiendo al usuario entender visualmente cuándo una opción está disponible o no.

Estas reglas y estilos aseguran una interacción eficiente y accesible para los usuarios de IAgroT, permitiendo que las acciones importantes se destaquen y sean fáciles de identificar en cualquier dispositivo.

<img src="images/Big Elements - Style Guidelines.png" alt="Spacing - Style Guidelines"/>  

En la sección de "Elementos Grandes" para IAgroT, los elementos visuales y estructurales clave serán:

- **Imágenes:** Las imágenes destacadas en la galería serán utilizadas para mostrar vistas de los campos agrícolas, tecnología IoT en acción o representaciones gráficas de los resultados del monitoreo. Cada imagen tendrá un título descriptivo para proporcionar contexto visual al usuario, destacando elementos importantes del proceso agrícola.
- **Tablas:** Las tablas en la interfaz estarán diseñadas para organizar datos cruciales, como los resultados del monitoreo de cultivos, estadísticas de rendimiento o información sobre las condiciones climáticas. Cada columna estará claramente etiquetada, y las filas contendrán datos organizados para facilitar su lectura. La función "Add" permitirá a los usuarios añadir nuevas entradas, como la inclusión de nuevos sensores IoT o campos de cultivo adicionales.

El uso de estos Elementos Grandes es fundamental para mostrar información detallada y visualmente atractiva, facilitando a los agricultores la gestión eficiente de sus cultivos y recursos mediante la plataforma IAgroT.

<img src="images/Cards - Style Guidelines.png" alt="Spacing - Style Guidelines"/>  

En la sección de Tarjetas para IAgroT, estas servirán para presentar información clave de forma visual y organizada.

- **Presentaciones:** La tarjeta principal, con un encabezado destacado y una imagen de fondo atractiva, permitirá a los usuarios obtener una visión general de temas importantes, como el monitoreo en tiempo real de sus cultivos o las características principales de la plataforma. Además, incluirá un botón de Call to Action que invitará al usuario a realizar una acción clave, como acceder a informes de rendimiento o comenzar a utilizar una nueva funcionalidad de IoT.
- **Tarjetas Individuales:** Las tarjetas más pequeñas presentarán contenido resumido y útil, como informes rápidos sobre el estado de los cultivos, datos climáticos o recomendaciones personalizadas basadas en el análisis de los datos del IoT. Cada tarjeta incluirá un título, una breve descripción, y un enlace o botón que dirigirá al usuario a más información, como "Leer más" o "Enlace a estadísticas."

Estas tarjetas son fundamentales para organizar visualmente la información dentro de IAgroT, ofreciendo a los usuarios acceso rápido y fácil a las diferentes funciones y reportes sin sobrecargar la interfaz.

### 5.3.1. Landing Page Wireframe

En esta sección, se presenta la base para el diseño del sitio web de nuestro software, estableciendo los elementos que brindarán una mejor visión del contenido que se mostrará tanto en la plataforma como en la versión móvil.

La landing page se diseñará en un tamaño adecuado para las pantallas de cada ordenador, centrando la información para que sea fácilmente visible para el usuario. Se priorizará la inclusión de contenido preciso y relevante, evitando sobrecargar al usuario. Para facilitar la navegación, se implementará una barra de navegación estática que permitirá al usuario desplazarse cómodamente por toda la página.

### Desktop Web

#### Menú

<img src="images/Inicio - Landing Page Wireframe.png" alt="Inicio - Landing Page Wireframe"/>

Este wireframe muestra una barra de navegación estática en la parte superior con enlaces a las secciones principales: "Inicio," "Nosotros," "Servicios," "Planes," y "Únete." Al centro, se destaca un mensaje principal y una breve descripción. A la derecha, hay un espacio para una imagen. En la parte inferior, se incluyen botones para descargar la aplicación desde Google Play y AppGallery, resaltando la disponibilidad móvil. El diseño es sencillo y centrado para facilitar la navegación.

#### Nosotros

<img src="images/Nosotros - Landing Page Wireframe.png" alt="Nosotros - Landing Page Wireframe"/>

Este wireframe muestra la sección "Nosotros" con un diseño limpio y organizado. A la izquierda, se encuentra un título destacado "NOSOTROS" seguido de un breve párrafo que describe la sección. A la derecha, hay un espacio reservado para una imagen representativa. El diseño es simétrico y se enfoca en proporcionar información de manera clara, combinando texto e imagen para captar la atención del usuario.

#### Servicios

<img src="images/Servicios - Landing Page Wireframe.png" alt="Servicios - Landing Page Wireframe"/>

Este wireframe corresponde a la sección "Nuestros Servicios." Al centro, se encuentra el título destacado seguido de una breve descripción. Debajo, se presentan tres imágenes alineadas horizontalmente, cada una con su respectivo texto descriptivo. Este diseño ofrece una estructura clara y simétrica que permite resaltar los servicios de manera visual y organizada, facilitando al usuario la comprensión de la oferta.

#### Contáctanos

<img src="images/Contactanos - Landing Page Wireframe.png" alt="Contactanos - Landing Page Wireframe"/>

Este wireframe corresponde a la sección "Contáctanos." A la izquierda, se muestra un espacio reservado para una imagen. A la derecha, se encuentra un formulario simple que incluye campos para "Nombre," "Correo" y "Mensaje," junto con un botón para "Enviar." Este diseño ofrece una forma clara y directa para que los usuarios se unan o se pongan en contacto, combinando elementos visuales con la funcionalidad de un formulario.

Enlace: [Figma Wireframe](https://www.figma.com/design/LN2VU2tN0rNd7Xkk9RtQTj/Untitled?node-id=0-1&t=ZviVgomnPOScb13B-1)

### 5.3.2. Landing Page Mock-up

Se presenta una versión preliminar de nuestro sitio web, detallando el contenido que incluirá. Esta versión incorpora los colores según nuestra guía de estilos y añade imágenes coherentes con la información presentada, con el objetivo de facilitar al usuario una comprensión más clara de los conceptos que queremos transmitir.

### Desktop Web

#### Menú
<img src="images/Inicio - Landing Page Mock-up.png" alt="Inicio - Landing Page Mock-up"/>

#### Nosotros
<img src="images/Nosotros - Landing Page Mock-up.png" alt="Nosotros - Landing Page Mock-up"/>

#### Nuestros Servicios
<img src="images/Servicios - Landing Page Mock-up.png" alt="Servicios - Landing Page Mock-up"/>

#### Contáctanos
<img src="images/Contactanos - Landing Page Mock-up.png" alt="Contactanos - Landing Page Mock-up"/>

## 5.4. Applications UX/UI Design

A continuación, se presentan los diseños aplicados para nuestro Mobile Application.

### 5.4.1 Applications Wireframes
**Segmento Objetivo Agricultor**

<img src="images/Inicio de Sesion - Applications Wireframes.png" alt="Inicio de Sesion - Applications Wireframes"/>

<img src="images/Registro - Applications Wireframes.png" alt="Registro - Applications Wireframes"/>

<img src="images/Sensores - Applications Wireframes.png" alt="Sensores - Applications Wireframes"/>

<img src="images/Sensores Informe - Applications Wireframes.png" alt="Sensores Informe - Applications Wireframes"/>

<img src="images/Chatbot - Applications Wireframes.png" alt="Chatbot - Applications Wireframes"/>

<img src="images/Registrar Sensor - Applications Wireframes.png" alt="Registrar Sensor - Applications Wireframes"/>

<img src="images/Soporte - Applications Wireframes.png" alt="Soporte - Applications Wireframes"/>

<img src="images/Chatbot - Applications Wireframes.png" alt="Chatbot - Applications Wireframes"/>

Enlace: [Applications Wireframes](https://www.figma.com/design/7CoaPJs0RAyKdgYdSQOuqF/Untitled?node-id=0-1&t=BBCe4c8k9FuznVyI-1)

**Segmento Objetivo Empresa Agricultora**

<img src="images/Inicio de Sesion - Applications Wireframes.png" alt="Inicio de Sesion - Applications Wireframes"/>

<img src="images/Registro - Applications Wireframes.png" alt="Registro - Applications Wireframes"/>

<img src="images/Sensores - Applications Wireframes.png" alt="Sensores - Applications Wireframes"/>

<img src="images/Sensores Informe - Applications Wireframes.png" alt="Sensores Informe - Applications Wireframes"/>

<img src="images/Chatbot - Applications Wireframes.png" alt="Chatbot - Applications Wireframes"/>

<img src="images/Registrar Sensor - Applications Wireframes.png" alt="Registrar Sensor - Applications Wireframes"/>

<img src="images/Soporte - Applications Wireframes.png" alt="Soporte - Applications Wireframes"/>

<img src="images/Chatbot - Applications Wireframes.png" alt="Chatbot - Applications Wireframes"/>  

Enlace: [Applications Wireframes](https://www.figma.com/design/7CoaPJs0RAyKdgYdSQOuqF/Untitled?node-id=0-1&t=BBCe4c8k9FuznVyI-1)

### 5.4.2 Applications Wireflow Diagrams
**Segmento Objetivo Agricultor**

**User Goal: **Como agricultor deseo Iniciar Sesion
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 1 - Applications Wireflow Diagrams.png" alt="User Goal 1 - Applications Wireflow Diagrams"/>  

**User Goal: **Como agricultor deseo saber cuándo he introducido "contraseña" incorrecta
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 2 - Applications Wireflow Diagrams.png" alt="User Goal 2 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo saber cuándo he introducido "correo electrónico" incorrecto
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 3 - Applications Wireflow Diagrams.png" alt="User Goal 3 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo registrarme en AIgrot
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 4 - Applications Wireflow Diagrams.png" alt="User Goal 4 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo visualizar el reporte de un sensor funcional.
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 5 - Applications Wireflow Diagrams.png" alt="User Goal 5 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo visualizar un informe general anual del estado de mis recursos.
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 6 - Applications Wireflow Diagrams.png" alt="User Goal 6 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo interactuar con el chat bot IAgrot.
Descripción: 
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 7 - Applications Wireflow Diagrams.png" alt="User Goal 7 - Applications Wireflow Diagrams"/>  

User Goal: Como agricultor deseo registrar un sensor en IAgrot.
Descripción: 
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 1 - Applications Wireflow Diagrams.png" alt="User Goal 1 - Applications Wireflow Diagrams"/>  

**User Goal:** Como agricultor deseo ponerme en contacto con el equipo de soporte de IAgrot. 
**Descripción: **
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electrónico y contraseña, para poder ingresar a IAgrot. 

<img src="images/User Goal 1 - Applications Wireflow Diagrams.png" alt="User Goal 1 - Applications Wireflow Diagrams"/>  

Enlace: [Applications Wireflow Diagrams](https://lucid.app/lucidspark/fd105459-002e-4fc7-8785-4d362b4459be/edit?viewport_loc=816%2C-4472%2C7807%2C3710%2C0_0&invitationId=inv_df8357a4-eeb7-4b1f-bf9c-fbf7e1b223bb) 

**Segmento Objetivo Empresa Agricultora**

**User Goal:** Visualizar el Estado de los Sensores en Tiempo Real
**Descripción: **
Como empresa agrícola, deseo ver el estado de mis sensores de manera centralizada para monitorear el funcionamiento y la salud de mis dispositivos.

**User Goal:** Acceder a Reportes Históricos de los Sensores
**Descripción:** 
Como empresa agrícola, quiero acceder a informes históricos de los datos recolectados por los sensores para analizar tendencias y tomar decisiones estratégicas sobre mis cultivos.

**User Goal: **Configurar Sensores Remotamente
**Descripción: **
Como empresa agrícola, deseo configurar mis sensores a través de la aplicación para optimizar el monitoreo de mis cultivos sin necesidad de desplazarme al campo.

**User Goal:** Autenticarse y Registrarse
**Descripción: **
Como empresa agrícola, deseo poder registrarme e iniciar sesión en la aplicación para acceder a la gestión de mis sensores y cultivos.

**User Goal:** Selección de Rol
**Descripción: **
Como empresa agrícola, deseo seleccionar mi rol (Empresa Agricultora) para personalizar la experiencia y acceder a las funciones específicas para mi negocio.

**User Goal:** Monitoreo de Sensores
**Descripción: **
Como empresa agrícola, deseo visualizar todos mis sensores en una lista para monitorear su funcionamiento y estado en tiempo real.

**User Goal:** Ver detalles del sensor
**Descripción:** 
Como empresa agrícola, quiero acceder a la información detallada de cada sensor para verificar su precisión, rango de medición y otros parámetros importantes.

**User Goal:** Visualizar Gráficos e Informes de Sensores
**Descripción:** 
Como empresa agrícola, deseo ver los gráficos y estadísticas generadas por cada sensor para analizar el rendimiento y las condiciones de mis cultivos.

**User Goal:** Acceso a Informes Generales
**Descripción: **
Como empresa agrícola, deseo acceder a un informe general de operación para evaluar la consistencia, precisión y consumo de energía de mis sensores y equipos.

**User Goal:** Registrar Nuevos Sensores
**Descripción: **
Como empresa agrícola, deseo registrar un nuevo sensor con su tipo, estado y otros parámetros para agregarlo a mi red de monitoreo.

**User Goal:** Comunicación a través del ChatBot
**Descripción:** 
Como empresa agrícola, deseo poder comunicarme con el chatbot para resolver dudas o recibir soporte técnico sobre el uso de la aplicación y mis sensores.

**User Goal:** Contacto con Soporte Técnico
**Descripción:** 
Como empresa agrícola, deseo poder comunicarme con el soporte técnico cuando experimente problemas con mis sensores o la aplicación.

## 5.4.3. Applications Mock-ups 
**Segmento Objetivo Agricultor**

<img src="images/Inicio de Sesion - Applications Mock-ups.png" alt="Inicio de Sesion - Applications Mock-ups"/> 

<img src="images/Registro - Applications Mock-ups.png" alt="Registro - Applications Mock-ups"/> 

<img src="images/Sensores Informe - Applications Mock-ups.png" alt="Sensores Informe - Applications Mock-ups"/> 

<img src="images/Sensores - Applications Mock-ups.png" alt="Sensores - Applications Mock-ups"/>   

<img src="images/Registrar Sensores - Applications Mock-ups.png" alt="Registrar Sensores - Applications Mock-ups"/> 

<img src="images/Registrar Sensores 2 - Applications Mock-ups.png" alt="Registrar Sensores 2 - Applications Mock-ups"/> 

<img src="images/Soporte - Applications Mock-ups.png" alt="Soporte - Applications Mock-ups"/> 

Enlace: [Applications Mock-ups](https://www.figma.com/design/7CoaPJs0RAyKdgYdSQOuqF/Untitled?node-id=0-1&t=BBCe4c8k9FuznVyI-1 ) 

## 5.4.4. Applications User Flow Diagrams
**Segmento Objetivo Agricultor**

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

<img src="images/Iniciar Sesion - Applications User Flow Diagrams.png" alt="Iniciar Sesion - Applications User Flow Diagrams"/>   

**User Goal:** Como agricultor, deseo iniciar sesión
En el presente Wireflow, se evidencia el flujo que seguirá el usuario agricultor para poder iniciar sesión. Iniciará en el login, seleccionará la opción paciente e ingresará su Correo electronico y contraseña correctamente, para poder ingresar a IAgrot, de lo contrario se mostrarán mensajes de alerta. 

Enlace: [Applications User Flow Diagrams](https://lucid.app/lucidspark/fd105459-002e-4fc7-8785-4d362b4459be/edit?viewport_loc=816%2C-4472%2C7807%2C3710%2C0_0&invitationId=inv_df8357a4-eeb7-4b1f-bf9c-fbf7e1b223bb) 

**Segmento Objetivo Empresa Agricultora**

**User Goal:** Como empresa agricultora deseo Iniciar Sesión
La empresa agricultora inicia sesión en la aplicación "IAgrot" utilizando sus credenciales previamente registradas (correo electrónico y contraseña). Este proceso le permite acceder a su cuenta y a las funcionalidades disponibles para monitorear y gestionar sus sensores, cultivos y recursos. En caso de error, se mostrarán mensajes de advertencia claros que guiarán al usuario para ingresar los datos correctos

<img src="images/Inicio Sesion - Empresa Agricultora - Applications User Flow Diagrams.png" alt="Inicio Sesion - Empresa Agricultora - Applications User Flow Diagrams"/>   

**User Goal:** Como empresa agricultora deseo registrarme en IAgrot
La empresa agricultora completa un proceso de registro proporcionando información básica como nombre de la empresa, correo electrónico, contraseña y otros detalles relevantes. Esto le permitirá crear un perfil en "IAgrot" para acceder a todas las funcionalidades de la plataforma y empezar a gestionar sus cultivos y sensores. El proceso incluye la confirmación de datos ingresados para garantizar la seguridad y validez de la cuenta creada.

<img src="images/Registro - Empresa Agricultora - Applications User Flow Diagrams.png" alt="Registro - Empresa Agricultora - Applications User Flow Diagrams"/>   

**User Goal:** Como empresa agricultora deseo visualizar el reporte de un sensor funcional
La empresa agricultora selecciona un sensor específico desde su panel de control para visualizar un informe detallado sobre su rendimiento. El reporte incluye datos como rango de medición, precisión, resolución, frecuencia de muestreo, y gráficos que muestran el comportamiento del sensor a lo largo del tiempo. Esto permite a la empresa evaluar el estado actual del sensor y tomar decisiones informadas sobre el monitoreo de sus cultivos.

<img src="images/Visualizar reporte - Empresa Agricultora - Applications User Flow Diagrams.png" alt="Visualizar reporte - Empresa Agricultora - Applications User Flow Diagrams"/>   

**User Goal:** Como empresa agricultora deseo visualizar un informe general anual del estado de mis recursos
La empresa agricultora accede a un informe anual que presenta una visión general del estado y rendimiento de todos sus recursos, incluyendo sensores y equipos. Este informe incluye métricas clave como la consistencia, precisión, energía consumida, alertas registradas y mantenimiento realizado durante el año. Esta información le permite a la empresa evaluar la eficiencia de sus operaciones, identificar áreas de mejora, y planificar acciones futuras.

<img src="images/Visualizar informe general - Empresa Agricultora - Applications User Flow Diagrams.png" alt="Visualizar informe general - Empresa Agricultora - Applications User Flow Diagrams"/>   

## 5.5. Applications Prototyping

El prototipo de la aplicación web "IAgrot" proporciona una solución integral para empresas agrícolas, comenzando con pantallas de inicio de sesión y registro que permiten a los usuarios acceder fácilmente a la plataforma, con mensajes claros de validación para facilitar la entrada correcta de datos. El diseño incluye una funcionalidad de selección y monitoreo de sensores donde los usuarios pueden identificar rápidamente el estado de sus sensores a través de códigos de color y acceder a informes detallados que incluyen gráficos y estadísticas, proporcionando información clave para la toma de decisiones. Además, la opción de registrar nuevos sensores asegura que las empresas puedan expandir y gestionar su red de monitoreo de manera eficiente.

El prototipo también incorpora un chatbot interactivo que facilita la comunicación y asistencia, mejorando la experiencia del usuario al ofrecer soporte inmediato. La inclusión de una pantalla de soporte técnico permite que los usuarios reporten problemas y reciban ayuda, lo que es crucial para mantener la funcionalidad de sus operaciones. En conjunto, el prototipo demuestra un enfoque bien estructurado y funcional que responde a las necesidades de gestión y monitoreo de las empresas agrícolas, garantizando una experiencia de usuario intuitiva y eficaz.
