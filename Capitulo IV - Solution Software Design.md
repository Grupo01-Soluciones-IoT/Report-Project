# Capítulo IV: Solution Software Design

## 4.1 Strategic-Level Domain-Driven Design

### 4.1.1 Event Storming

#### 4.1.1.1 Candidate Context Discovery

#### 4.1.1.2 Domain Message Flows Modeling

#### 4.1.1.3 Bounded Contexts Canvases


### 4.1.2 Context Mapping

### 4.1.3 Software Architecture

#### 4.1.3.1 Software Architecture System Landscape Diagram 

#### 4.1.3.2 Software Architecture Context Level Diagrams 

En nuestro diagrama de contexto se presentan las relaciones fundamentales de IAgroT. Esta aplicación web y móvil está conectada principalmente con usuarios distintos y dos sistemas externos, el Payment System para llevar a cabo transacciones de pago y el Notification System para enviar alertas y notificaciones. 

<img src="images/IAgroT Context Diagram.png">

#### 4.1.3.3 Software Architecture Container Level Diagrams 

Con este diagrama se puede observar nuestro proyecto de manera más expandida. Se muestra la aplicación web, landing page, aplicación móvil cada una realizando llamadas API a los distintos Bounded Context que interactuan con los sistemas externos de Payment. Además, a su vez interactuarán con un broker que irá conectado a la Base de Datos.

<img src="images/IAgroT Container Diagram.png">