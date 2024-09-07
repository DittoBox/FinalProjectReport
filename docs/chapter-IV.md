# Chapter IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.3. Software Architecture Container Level Diagrams
#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: <Bounded Account & Subscription Management Context>
El dominio de Account & Subscription Management describe detalladamente las funciones y procesos que se llevan a cabo para la gestión de cuentas de usuario y suscripciones dentro de nuestra plataforma. Este dominio es responsable de manejar todas las operaciones relacionadas con la creación, actualización y eliminación de cuentas, así como la gestión de suscripciones. Esto incluye la actualización de datos del negocio, la gestión de representantes, y el manejo de niveles de suscripción, pagos y estados de la misma. Garantiza que las cuentas estén correctamente sincronizadas con el sistema de suscripción y que los cambios en las suscripciones se manejen de manera adecuada y eficiente, proporcionando un servicio fluido para los usuarios.


###### Diccionario de Clases

El Diccionario de Clases es una herramienta clave en el proceso de diseño y desarrollo del sistema de gestión de cuentas y suscripciones. Proporciona una descripción detallada de las clases fundamentales que forman la base del modelo de dominio. Este diccionario documenta las entidades, sus atributos, métodos y relaciones, lo que facilita la comprensión y colaboración entre los desarrolladores, garantizando una base sólida para la solución implementada en el proyecto de Account & Subscription Management.

#### Account

![Cuadro de la clase Account](/img/Account-Class.png)



#### Subscription

![Cuadro de la clase Subscription](/img/Subscription-Class.png)


#### 4.2.1.1. Domain Layer
Dentro del dominio de Account & Subscription Management, se encuentran entidades clave que permiten gestionar las cuentas de negocio y sus suscripciones dentro de nuestra plataforma. Estas entidades desempeñan un papel fundamental en los procesos de creación, actualización y administración de cuentas de usuario, así como en el manejo de las suscripciones, lo que incluye cambios en el nivel de suscripción, actualizaciones de datos empresariales, y el seguimiento de los pagos y estados de las suscripciones. Estas entidades garantizan que los usuarios puedan gestionar eficientemente su suscripción y que el sistema mantenga los datos actualizados de las cuentas.

![Domain Layer Account and Subscription](/img/Domain-layer-account.png)

#### 4.2.1.2. Interface Layer

En esta sección, presentamos la Capa de Interfaz de nuestra plataforma de Account & Subscription Management, que representa el punto de entrada para las interacciones entre los usuarios y el sistema. La Capa de Interfaz está compuesta por una serie de controladores que manejan las peticiones entrantes de los usuarios y devuelven las respuestas adecuadas, permitiendo una comunicación efectiva entre la plataforma y sus usuarios.

El contexto de esta capa incluye cuatro controladores principales: AccountController, SubscriptionController, UserController, y PaymentController. Estos controladores tienen la responsabilidad de gestionar las operaciones relacionadas con las cuentas, suscripciones, usuarios y pagos.


![Account & Subscription Controllers](/img/AccountAndSubscriptionControllers.png)

#### 4.2.1.3. Application Layer
En esta sección, presentamos la Capa de Aplicación (Application Layer) dentro del contexto de Account & Subscription Management. Esta capa actúa como intermediaria entre la lógica de negocio y la infraestructura del sistema, gestionando el flujo de datos y las interacciones. Los Command Handlers y Event Handlers son responsables de ejecutar acciones de escritura y manejar eventos del sistema, coordinándose con los servicios relevantes para realizar sus operaciones.

Cada Handler en esta capa utiliza servicios específicos para ejecutar las funciones relacionadas con cuentas y suscripciones.

![Account & Subscription Handlers](/img/Handlers-Account&SubscriptionContext.png)


#### 4.2.1.4. Infrastructure Layer
#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.1.6.2. Bounded Context Database Design Diagram

### 4.2.2. Bounded Context: <Bounded Context Name>
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer
#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: <Bounded Context Name>
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.3.6.2. Bounded Context Database Design Diagram

### 4.2.4. Bounded Context: <Bounded Context Name>
#### 4.2.4.1. Domain Layer
#### 4.2.4.2. Interface Layer
#### 4.2.4.3. Application Layer
#### 4.2.4.4. Infrastructure Layer
#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.4.6.2. Bounded Context Database Design Diagram