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
En esta sección, presentamos la Capa de Infraestructura (Infrastructure Layer) dentro del contexto de Account & Subscription Management. Esta capa es responsable de proporcionar los componentes técnicos y de soporte necesarios para que las otras capas del sistema funcionen correctamente. Incluye la implementación de repositorios y servicios que se conectan con sistemas externos para manejar la persistencia y gestión de datos.

Los repositorios en la Capa de Infraestructura implementan las interfaces definidas en la Capa de Dominio y se encargan de interactuar con la base de datos utilizando Entity Framework en .NET. Los repositorios clave en este contexto son AccountRepository, que maneja la información de las cuentas, y SubscriptionRepository, que gestiona las suscripciones vinculadas a las cuentas.


![Account & Subscription Repositoires](/img/infrastructure-layer-Account&SubscriptionContext.png)



#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams



#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams  



##### 4.2.1.6.2. Bounded Context Database Design Diagram  


### 4.2.2. Bounded Context: <Bounded User & Profile Management Context>

El dominio de User & Profile Management describe detalladamente las funciones y procesos que se llevan a cabo para la gestión de usuarios y sus perfiles dentro de nuestra plataforma. Este dominio es responsable de manejar todas las operaciones relacionadas con la creación, actualización y eliminación de usuarios, así como la gestión de los perfiles asociados. Esto incluye la actualización de nombres, la asignación y revocación de privilegios, y el manejo de los diferentes roles dentro del sistema. Garantiza que los usuarios y sus perfiles estén correctamente sincronizados y que los cambios en los privilegios se gestionen de manera adecuada y eficiente, proporcionando una experiencia fluida y segura para los usuarios.

##### Diccionario de Clases

El Diccionario de Clases es una herramienta clave en el proceso de diseño y desarrollo del sistema de gestión de usuarios y perfiles. Proporciona una descripción detallada de las clases fundamentales que forman la base del modelo de dominio. Este diccionario documenta las entidades, sus atributos, métodos y relaciones, lo que facilita la comprensión y colaboración entre los desarrolladores, garantizando una base sólida para la solución implementada en el proyecto de User & Profile Management.

![User class chart](/img/user-chart-class.png)

![Profile class chart](/img/profile-chart-class.png)

![ProfilePrivilege class chart](/img/profileprivilage-chart-class.png)

#### 4.2.2.1. Domain Layer
Dentro del dominio de User & Profile Management, se encuentran entidades clave como lo escrito anteriormente. Estas entidades desempeñan un papel fundamental en los procesos necesarios para gestionar a los usuarios y sus perfiles, permitiendo a la plataforma administrar la información personal de los usuarios, así como los privilegios y roles asignados a cada perfil. Este dominio también garantiza que las interacciones entre los usuarios y el sistema se realicen de manera segura y eficiente, proporcionando acceso controlado a las distintas funcionalidades y recursos disponibles en la plataforma.

A continuación, se muestran todos los objetos relacionados con el dominio.

![User & Profile Domain Layer](/img/User-Profile-Domain-Layer.png)



#### 4.2.2.2. Interface Layer
En esta sección, presentamos la Capa de Interfaz para el User & Profile Management Context, que actúa como el punto de entrada para las interacciones de los usuarios con el sistema. La Capa de Interfaz incluye controladores que procesan las solicitudes entrantes relacionadas con usuarios y perfiles, gestionando las respuestas del sistema y permitiendo una comunicación efectiva entre la plataforma y los usuarios.

Este contexto incluye los siguientes controladores:

- UserController
- ProfileController

![User & Profile Interface Layer](/img/user-profile-interface-layer.png)


#### 4.2.2.3. Application Layer
En esta sección, presentamos la Capa de Aplicación (Application Layer) dentro del contexto de User & Profile Management siguiendo el enfoque de diseño Domain-Driven Design (DDD). La Capa de Aplicación es responsable de coordinar las acciones y el flujo de datos entre la Capa de Dominio y la Capa de Infraestructura, actuando como intermediario y gestionando las interacciones entre estas capas. Esta capa asegura que la lógica de negocio, representada por la Capa de Dominio, se ejecute de manera eficiente y coherente.

![User & Profile Application Layer](/img/User-Profile-application-Layer.png)

#### 4.2.2.4. Infrastructure Layer

En esta sección, presentamos la Capa de Infraestructura (Infrastructure Layer) dentro del contexto de User & Profile Management, utilizando .NET y Entity Framework Core para la persistencia y gestión de datos. Esta capa es crucial para proporcionar los componentes técnicos y de soporte necesarios para que las otras capas del sistema funcionen correctamente.

Los repositorios en la Capa de Infraestructura implementan las interfaces definidas en la Capa de Dominio y se encargan de la persistencia y gestión de datos. En nuestro sistema, los repositorios están diseñados para interactuar con Entity Framework Core y manejar la comunicación con la base de datos.

![User & Profile Infrastructure Layer](/img/User-Profile-infrastructure-Layer.png)


#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: <Bounded Container Management Context>
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.3.6.2. Bounded Context Database Design Diagram

### 4.2.4. Bounded Context: <Bounded Groups Management Context>
#### 4.2.4.1. Domain Layer
#### 4.2.4.2. Interface Layer
#### 4.2.4.3. Application Layer
#### 4.2.4.4. Infrastructure Layer
#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.4.6.2. Bounded Context Database Design Diagram