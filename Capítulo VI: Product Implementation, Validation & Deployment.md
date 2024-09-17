## Capítulo VI: Product Implementation, Validation & Deployment.

# 6.1. Software Configuration Management.

## 6.1.1. Software Development Environment Configuration.
### **Project Management**
Se emplearon herramientas de software que permiten la comunicación en tiempo real y la edición rápida y compartida, lo que facilitó el trabajo eficiente. Algunas de las herramientas utilizadas fueron los servicios de Google (Drive, Documents, Meet) y Microsoft Outlook. Para el registro de versiones y la creación de repositorios se utilizó GitHub, una plataforma que permite registrar de manera ordenada cada uno de los commits realizados y Git  una herramienta que permite el control de versiones.

 <img src="Assets/github.jpg" width="700"/>

### **Product UX/UI Design**
Se utilizó Miro y UXPressia para el desarrollo de los segmentos objetivos y sus mapeos, así como para los As-Is y To-Be Scenario Maps. Para los mockups, wireframes, wireflows y el prototipo de la aplicación web se empleó Figma.

### **Software Development**
Para el desarrollo del software se utilizó Visual Studio Code, HTML, CSS, Bootstrap y Javascript. Visual Studio Code es un software que admite muchos lenguajes de programación, incluyendo HTML y CSS, y fue utilizado principalmente para el Landing Page. HTML se utilizó para el desarrollo de la estructura de las páginas web, CSS para el diseño y presentación, Bootstrap para crear interfaces más limpias y responsive, y Javascript para implementar la interactividad dinámica y animaciones en el Landing Page.<br>
 <img src="Assets/visual%20studio.png" width="700"/>

También se está desarrollando la aplicación móvil emppleando el framework Flutter, la cual es multiplataforma. Sin embargo, no se utiliza Flutter solo por su responsiveness, sino que se eligió por el uso de distintos componentes que permite darle una estética más personalizado. El lenguaje en uso para el desarrollo de la aplicación móvil es Dart.
    <img src="Assets/android%20studio.png" width="700"/>

Asimismo, se utilizo Vue para el desarrollo de la aplicación web, un framework progresivo de JavaScript que permite crear interfaces de usuario interactivas y dinámicas.
    <img src="Assets/vue.jpg" width="700"/>

Para el desarrollo del backend se utilizó Node.js, un entorno de ejecución de JavaScript que permite ejecutar código JavaScript en el servidor.

    <img src="Assets/node.png" width="700"/>


### **Software Testing**
Para probar el Landing Page se utilizó la extensión LiveShare de Visual Studio Code, que permite crear un localhost para ver en tiempo real los cambios realizados. Para los test de aceptación se utilizó el lenguaje Gherkin y se subió al repositorio mencionado anteriormente.

### **Software Deployment**
Para desplegar la Landing Page, al ser una página de contenido estático que no necesita muchas actualizaciones, se utilizó GitHub Pages, que es gratuito y permite actualizar el contenido cuando sea necesario.

### **Software Documentation**
La documentación del software se realizó mediante comentarios en los archivos HTML, ya que al utilizar HTML para el desarrollo del Landing Page, un lenguaje de marcado, no era necesario crear diagramas de clases u otros tipos de documentación.

## 6.1.2. Source Code Management.

Para mantener el orden  y evitar conflictos o superposiciones de información, los proyectos se trabajaron en una
organización de GitHub y dentro de esta se encuentran los diferentes repositorios para cada proyecto cuyos enlaces de los repositorios son los
siguientes:
1. Repositorio para el landing page: https://github.com/OneUp-WS71/landign-page 
2. Repositorio de la aplicación web: https://github.com/OneUp-WS71/frontend-web-applications 
3. Repositorio de la aplicación móvil: https://github.com/OneUp-WS71/Mobile-applications 
4. Repositorio del backend: https://github.com/OneUp-WS71/web-services
5. Repositorio del embedded application: https://github.com/OneUp-WS71/embedded-application  

Se utilizará GitFlow para la administración de versiones del proyecto, en concreto se hará uso de las ramas main, develop and feature. 
+ Para cada commit que se realice, ya sea para el landing page o los archivos .feature, se utilizará el formato de mensaje "Conventional Commits" para ayudar a reconocer mejor lo que se hizo en los commits y de esta forma conocer mejor el estado del proyecto.
+ Cada repositorio de código tendrá sus respectivas ramas tal como lo describe Vincent Driessen, donde estará presente la rama Main (que almacenará las versiones estables y finales), Develop (donde se irán integrando los cambios implementados por cada feature y estará en constante actualización). 
+ Además, para la creación de ramas feature se utilizará el formato, feature/< user story / technical story> y para los commits Se utilizara el siguiente formato para realizar los commits: < type>[optional scope]< optional sticker>: < description> 
[optional body]
[optional footer(s)]

## 6.1.3. Source Code Style Guide & Conventions.
A continuación, se mostrarán las pautas, convenciones, estilo y principios que se utilizarán para cada uno de los lenguajes de se emplearán en la creacion y desarrollo de nuestra aplicación. La práctica de este conjunto de reglas es de suma importancia, ya que estas tienen el propósito de conservar la calidad estructural del software, dar una mayor legibilidad al código fuente y facilitar el mantenimiento del código.

**HTML:**
+ Declarar siempre el tipo de documento con <! DOCTYPE html>.
+ Utilizar nombres de etiquetas y atributos en minúscula.
+ Cerrar todas las etiquetas.
+ Siempre utilizar comillas para los valores de los atributos.
+ Especificar los atributos alt, width y height para las imágenes.
+ No omitir la etiqueta < title> ni los metadatos (< meta>).
```
<!DOCTYPE html>
<html>
<head>
  <title>Example Page</title>
  <meta charset="UTF-8">
  <meta name="description" content="This is an example page">
</head>
<body>
  <img src="example.jpg" alt="Example Image" width="200" height="150">
</body>
</html>

```

**CSS:**
+ Usar nombres de clases generales y descriptivos.
+ Utilizar nombres de clase cortos y concisos.
+ Separar palabras en nombres de clase con guiones.
+ Evitar los selectores de ID.
+ Usar propiedades abreviadas cuando sea posible.

**JavaScript:**
+ Usar nombres cortos y descriptivos para variables, funciones, etc.
+ Evitar el uso de variables globales (var).
+ Comentar líneas de código complejas para facilitar la comprensión.
+ Utilizar notaciones simples y comprensibles.
```
// Declaración de variables
let nombreUsuario = "Juan";

// Definición de función
function saludar() {
  return "Hola, " + nombreUsuario + "!";
}

// Uso de función
console.log(saludar());
```
**Dart:**
+ Usar nombres de clases, métodos y variables en minúsculas.
+ Utilizar nombres de clases en singular y en mayúscula.
+ Utilizar nombres de métodos y variables en minúscula.
+ Utilizar nombres de métodos en camelCase.
+ Utilizar nombres de variables en minúscula y separados por guiones bajos.
```
// Declaración de variable utilizando camelCase
String nombreUsuario = 'Juan';

// Definición de función utilizando camelCase
void saludar() {
  print('Hola, $nombreUsuario!');
}
```
**Vue:**
+ Usar nombres de componentes en singular y en mayúscula.
+ Utilizar nombres de métodos y variables en minúscula.
+ Seguir las convenciones de Vue.js para la estructura del proyecto, como el uso de componentes y la organización del código. Por ejemplo, dividir la interfaz de usuario en componentes reutilizables y mantener una estructura de carpetas lógica para los archivos de componentes.
+ Utilizar la sintaxis de Vue.js de manera consistente en los archivos de componentes. Por ejemplo, utilizar la notación v-bind para enlazar atributos y v-on para manejar eventos.
```
<!-- Ejemplo de componente Vue -->
<template>
  <div>
    <p>{{ mensaje }}</p>
    <button @click="cambiarMensaje">Cambiar Mensaje</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensaje: 'Hola Mundo!'
    };
  },
  methods: {
    cambiarMensaje() {
      this.mensaje = '¡Hola Vue!';
    }
  }
};
</script>
```
**Node.js:**
+ Usar nombres de variables y funciones en minúsculas.
+ Utilizar nombres descriptivos y significativos para las variables y funciones.
+ Seguir las convenciones de Node.js para la estructura del proyecto, como el uso de módulos y la organización del código. Por ejemplo, dividir la lógica de la aplicación en módulos reutilizables y mantener una estructura de carpetas lógica para los archivos de módulos.
+ Utilizar módulos npm y gestionar las dependencias de manera adecuada. Por ejemplo, especificar las dependencias en un archivo package.json y utilizar herramientas como npm o yarn para instalar y gestionar paquetes.
```
proyecto-node/
│
├── src/
│   ├── index.js
│   ├── controllers/
│   │   └── usuarioController.js
│   ├── models/
│   │   └── usuarioModel.js
│   └── routes/
│       └── usuarioRoutes.js
│
├── package.json
└── README.md
```
**Spring:** 
Se siguieron las convenciones y guías de estilo de código de la documentación oficial de Spring Boot y se destaca lo siguiente:
+ Uso de Anotaciones: Utilizar anotaciones como @Controller, @Service, @Repository y @Component para marcar clases y componentes
específicos de Spring.
+ Convención de Paquetes: Organizar los archivos y clases en carpetas que representen la estructura lógica de la aplicación, como controladores,
servicios, repositorios, etc.
+ Convención de Nombres en Bases de Datos: Utilizar la convención de nombres en bases de datos como snake_case para nombres de tablas y
columnas. Spring Boot se encargará de mapear estos nombres a objetos Java.
+ Uso de Spring Data JPA: Emplear Spring Data JPA para simplificar la interacción con la capa de persistencia y bases de datos.
+ Uso de Inyección de Dependencias: Aplicar la inyección de dependencias utilizando el constructor de las clases.
+ Uso de @RestController: Usar la anotación @RestController para marcar controladores que devuelven datos en formato JSON.
+ Seguridad con Spring Security: Implementar la seguridad en la aplicación utilizando Spring Security para autenticación y autorización.

**Java:**
+ Seguir las convenciones de nomenclatura de Java para nombres de variables, clases, métodos y paquetes. Por ejemplo, utilizar camelCase para nombres de variables y métodos, UpperCamelCase para nombres de clases, y utilizar nombres descriptivos que reflejen el propósito de la entidad.
+ Utilizar comentarios Javadoc para documentar clases y métodos públicos. Esto es fundamental para proporcionar una descripción clara de la funcionalidad de las clases y métodos, así como para generar documentación automáticamente.
+ Organizar el código en paquetes lógicos y utilizar la convención de nombres de paquetes de dominio invertido para evitar conflictos de nombres. Por ejemplo, el nombre de paquete com.ejemplo.proyecto indica que el proyecto pertenece al dominio ejemplo.com.
```
package com.ejemplo.proyecto.modelo;

/**
 * Clase que representa un usuario en el sistema.
 */
public class Usuario {
    private String nombre;
    private int edad;
    
    /**
     * Constructor de la clase Usuario.
     * @param nombre El nombre del usuario.
     * @param edad La edad del usuario.
     */
    public Usuario(String nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    /**
     * Método para obtener el nombre del usuario.
     * @return El nombre del usuario.
     */
    public String getNombre() {
        return nombre;
    }
    
    /**
     * Método para establecer el nombre del usuario.
     * @param nombre El nuevo nombre del usuario.
     */
    public void setNombre(String nombre) {
        this.nombre = nombre;
    }
    
    /**
     * Método para obtener la edad del usuario.
     * @return La edad del usuario.
     */
    public int getEdad() {
        return edad;
    }
    
    /**
     * Método para establecer la edad del usuario.
     * @param edad La nueva edad del usuario.
     */
    public void setEdad(int edad) {
        this.edad = edad;
    }
    
    /**
     * Método para imprimir los datos del usuario.
     */
    public void imprimirDatos() {
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
    }
}
```
## 6.1.4. Software Deployment Configuration.
En este punto, se dara a conocer el proceso de despliegue de las aplicaciones, así como la configuración de los servidores y la infraestructura necesaria para su correcto funcionamiento.

**Landing Page:** 
Para desplegar la Landing Page, se utilizó GitHub Pages, una plataforma gratuita que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. El proceso de despliegue fue el siguiente:
1. Crear un repositorio en GitHub con el código de la Landing Page.
2. Acceder a la configuración del repositorio y habilitar GitHub Pages.
<img src="Assets/landing%20deploy%201.png" width="700"/>



4. Seleccionar la rama y la carpeta de origen del sitio web.
5. Guardar la configuración y obtener la URL del sitio web desplegado.
6. Finalmente, acceder a la URL del sitio web para verificar que se haya desplegado correctamente.
    <img src="Assets/landing%20deploy%202.png" width="700"/>


+ Enlace de la Landing Page desplegada: https://oneup-ws71.github.io/landign-page/

**FrontEnd:**
Para el despliegue de la aplicacion se ha usado los servicios que ofrecen netlify una plataforma de alojamiento web que ofrece integración continua y despliegue automático desde repositorios de Git. El proceso de despliegue fue el siguiente:
+ Preparación del Repositorio:
Asegúrarse que la página web esté almacenada en un repositorio Git, como GitHub, GitLab.
+ Crear una Cuenta en Netlify:
Regístrarse en la plataforma.
+ Conectar el Repositorio:
Inicia sesión en Netlify y ve al panel de control.
Hacer clic en el botón "New site from Git" (Nuevo sitio desde Git).
Selecciona tu proveedor de servicios de alojamiento de Git (por ejemplo, GitHub) y autoriza la conexión con tu cuenta.
Seleccionar el repositorio que contiene la página web.
<img src="Assets/netlify.png" width="700"/>

+ Configurar las Opciones de Despliegue:
Netlify detectará automáticamente la configuración de tu proyecto. Si necesitas ajustes adicionales, como la configuración del directorio de compilación, puedes establecerlos en la sección de configuración de tu sitio.
<img src="Assets/netlify%202.png" width="700"/>

+ Despliegue Automático:
Activa la opción de "Deploy site" (Desplegar sitio) para habilitar el despliegue automático cada vez que realices cambios en tu repositorio.
+ Verificar el Despliegue:
Una vez que se complete el despliegue, Netlify te proporcionará una URL única para acceder a tu página web.

**BackEnd:**
Para el despliegue del backend se ha utilizado los servicios de Railway, una plataforma de alojamiento de aplicaciones web que permite desplegar aplicaciones de Node.js, Python, Ruby, Java, PHP, Go y Docker. El proceso de despliegue fue el siguiente:
+ Preparación del Repositorio:
Asegúrarse de que el backend esté almacenado en un repositorio Git, como GitHub, GitLab.
+ Crear una Cuenta en Railway:
Registrarse en la plataforma.
+ Crear un Nuevo Proyecto:
Inicia sesión en Railway y ve al panel de control.
Crea un nuevo proyecto y selecciona "Backend" como tipo de proyecto.
Conectar el Repositorio:
Selecciona tu proveedor de servicios de alojamiento de Git (por ejemplo, GitHub) y autoriza la conexión con tu cuenta.
Selecciona el repositorio que contiene tu backend.
 <img src="Assets/railway.png" width="700"/>

+ Configurar el Entorno:
Railway detectará automáticamente el tipo de backend que estás utilizando y configurará el entorno según sea necesario.
Si tu backend necesita variables de entorno específicas, como claves API o configuraciones de base de datos, puedes establecerlas en la sección de configuración de tu proyecto.
 <img src="Assets/railway2.png" width="700"/>

+ Despliegue Automático:
Activar la opción de "Auto Deploy" (Despliegue Automático) para habilitar el despliegue automático cada vez que realices cambios en tu repositorio.
+ Verificar el Despliegue:
Una vez que se complete el despliegue, Railway te proporcionará una URL única para acceder a tu backend.
# 6.2. Landing Page, Services & Applications Implementation.

## 6.2.1. Sprint 1

### 6.2.1.1. Sprint Planning 1.
