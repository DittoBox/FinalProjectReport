# Chapter IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming

Nuestro proceso de event storming se llevó a cabo utilizando la herramienta MURAL, donde desarrollamos todo el flujo. Comenzamos con el primer paso, la Exploración No Estructurada, en el cual analizamos y compartimos nuestras opiniones sobre los eventos del dominio, siguiendo las recomendaciones pertinentes. Además, consideramos varios criterios para seleccionar los eventos del dominio, como su relevancia, frecuencia, y temporalidad.

![image](https://github.com/user-attachments/assets/3bb41469-0491-4d3a-84c5-dd0994b8b0c6)
*Evidencia del desarrollo del primer paso del DDD.*

Después de ello, comenzamos con el segundo paso llamado Timelines, donde discutimos el flujo de los eventos del dominio.<br>
![image](https://github.com/user-attachments/assets/8a8f8d5a-6ebb-450c-bb57-096418dd1cd5)
![image](https://github.com/user-attachments/assets/2416eea5-6103-4c39-b4bd-a76045651936)
![image](https://github.com/user-attachments/assets/b38656ad-b5de-4c77-8d36-13f555bf301c)
![image](https://github.com/user-attachments/assets/c0b1c19e-964f-4b2c-bcd4-9db76d6ceffb)
![image](https://github.com/user-attachments/assets/c391eaac-01d9-40b5-9de1-fa809be82b72)
![image](https://github.com/user-attachments/assets/87d86800-b5e2-46c8-b368-0ec365d52edc)
![image](https://github.com/user-attachments/assets/f1e2c9da-b713-4742-a62c-c81e9f84e08e)
![image](https://github.com/user-attachments/assets/2cd169ca-7a5f-4a5f-8a0c-0eeb81596b1c)
![image](https://github.com/user-attachments/assets/5f0e6be5-b849-4b31-907d-e8cea3f49c6e)
![image](https://github.com/user-attachments/assets/abfc0c2d-817a-4d85-9d94-a4919ec1814e)
<br>*Evidencia del desarrollo del segundo paso de DDD.*

#### 4.1.1.1. Candidate Context Discovery

Para hallar a nuestros Candidate Context, continuamos con el paso 3 Pain Points, donde discutimos eventos del flujo que podrían ser cuellos de botella o pasos manuales que requieren automatización. <br>
![image](https://github.com/user-attachments/assets/64cf8988-27b3-4b3c-82d6-2abd8b8e65b4)
![image](https://github.com/user-attachments/assets/fc3bb9cd-e08d-4c9a-9b69-f3f04e066e01)
![image](https://github.com/user-attachments/assets/cb14936e-d68b-4d03-8168-903fa918ea65)
![image](https://github.com/user-attachments/assets/be01dc99-97c4-4aec-b136-75fb39f18d38)
![image](https://github.com/user-attachments/assets/18023a7e-2527-4b3e-9094-a2360536f2a2)
![image](https://github.com/user-attachments/assets/cfcd6411-eb0d-498c-b494-23a0fdd0912f)
![image](https://github.com/user-attachments/assets/bdf93aa1-f131-4bf4-9053-aaa062a0f85a)
![image](https://github.com/user-attachments/assets/87fc441b-336a-4134-8a35-02ec124f8e4b)
![image](https://github.com/user-attachments/assets/c90deb7f-ae6c-4204-801f-95c7405ca2cf)
<br>*Evidencia del desarrollo del tercer paso del DDD.*

Después, comenzamos con el cuarto paso del DDD llamado Pivotal Points, donde identificamos puntos o eventos comerciales importantes que indicaban un cambio en el contexto o la fase.<br>

![image](https://github.com/user-attachments/assets/b696a956-9579-48ec-81da-74ed2cfc9942)
![image](https://github.com/user-attachments/assets/2df3f7db-64e2-405f-8831-7193eedd6ff6)
![image](https://github.com/user-attachments/assets/e0d6ff5f-68b0-4e03-952d-2b6a723d044e)
![image](https://github.com/user-attachments/assets/60a57796-712b-4c71-b91c-cbafcf93635d)
![image](https://github.com/user-attachments/assets/adc5d5f3-d548-421b-abb6-da2b20d87c6e)
![image](https://github.com/user-attachments/assets/d9f0b346-75f4-490b-8aee-bef71260f702)
![image](https://github.com/user-attachments/assets/e6d60308-eae6-48ca-96f3-325d1560bc93)
<br>*Evidencia del desarrollo del cuarto paso del DDD.*

Con todo ello, comenzamos el paso de Commands, donde escribimos el desencadenante de ciertos eventos del dominio, así como el actor encargado.<br><br>
![image](https://github.com/user-attachments/assets/773662a3-b9dc-4996-94d9-4792b27e828b)
![image](https://github.com/user-attachments/assets/05bf66a3-cebd-4ecf-9b3a-939e8d8e1738)
![image](https://github.com/user-attachments/assets/45b7e058-fae5-4e4d-b5e2-f3c527b8776e)
![image](https://github.com/user-attachments/assets/539a6a85-3a76-40ab-baca-8383e9059757)
![image](https://github.com/user-attachments/assets/290723cd-e173-4d10-baad-a9e0acfbc6ec)
![image](https://github.com/user-attachments/assets/8788dc02-eb6c-4141-bd67-f5db18d6afef)
![image](https://github.com/user-attachments/assets/cba7b61b-1f84-4040-a7ad-f87320f24baf)
<br>*Evidencia del desarrollo del quinto paso del DDD.*

Después proseguimos con el paso 6, Policies donde identificamos eventos que debían de ejecutarse en automático o necesitaban alguna politica.<br>
![image](https://github.com/user-attachments/assets/cee0bde6-3e3c-4675-adf9-a525c5c98c0f)
![image](https://github.com/user-attachments/assets/e3019aba-306d-4854-a7c7-fc7df51f1af1)
![image](https://github.com/user-attachments/assets/99758c04-cfd7-4140-b391-9620425fd609)
![image](https://github.com/user-attachments/assets/4cee27c2-25d6-4f3d-b1d0-b57ff5309204)
![image](https://github.com/user-attachments/assets/f1d22019-c7c2-4ac9-9ca7-bf8070da098b)
![image](https://github.com/user-attachments/assets/bcf1a6fa-f9f2-450e-866e-a91555d8e547)
![image](https://github.com/user-attachments/assets/844bdc41-5dc2-444b-8929-695aaf8442cc)
<br>*Evidencia del desarrollo del sexto paso del DDD.*

Con ello procedemos a discutir los modelos de lectura de datos.<br>
![image](https://github.com/user-attachments/assets/1ac94fc3-1931-4eb4-b0bd-3e8042e18f36)
![image](https://github.com/user-attachments/assets/b4c1596d-073c-4355-ada8-fe19b084410e)
![image](https://github.com/user-attachments/assets/2ffb54e0-f50c-44c1-a905-fb94900f3dba)
![image](https://github.com/user-attachments/assets/f30e0223-8d36-4278-aef1-ef1937fcd9e0)
![image](https://github.com/user-attachments/assets/846ebaef-2068-4b1a-91fd-9ed80b7099a4)
![image](https://github.com/user-attachments/assets/fbb5983e-00c9-4b0a-8911-5edf57f2c3cf)
![image](https://github.com/user-attachments/assets/eb2aca75-464f-49e4-9f67-49c0eccc777c)
<br>*Evidencia del desarrollo del septimo paso del DDD.*

También empezamos a discutir el uso de sistemas externos, donde únicamente se encontró necesario en el siguiente.<br>
![image](https://github.com/user-attachments/assets/728a53c1-269e-4f6e-a70b-a7e43e003362)
<br>*Evidencia del desarrollo del octavo paso del DDD.*

Después, se comenzó con la identificación de los agregattes, para ello, tomamos criterios como granularidad, consistencia, y estabilidad. Con esos criterios, se procedió a elegir los Agreggattes, los cuales fueron los siguientes.<br>
![image](https://github.com/user-attachments/assets/9ad47b07-75a5-41fa-ad95-962d5a0be83c)
![image](https://github.com/user-attachments/assets/f208c05b-750b-4278-bc0b-2daf9b5963aa)
![image](https://github.com/user-attachments/assets/d15835b7-aa43-4f28-aa7f-e01a5afa3ef2)
![image](https://github.com/user-attachments/assets/d6460f4d-bcd3-4586-a361-b88a4ebd5671)
![image](https://github.com/user-attachments/assets/ae48a953-6384-4efe-9bc6-cb8b6aa6f517)
![image](https://github.com/user-attachments/assets/d9e3325d-5b49-4230-9429-269f62e38cc5)
![image](https://github.com/user-attachments/assets/59ade63c-df80-4ac1-88fd-5c8fb341569c)
<br>*Evidencia del desarrollo del noveno paso del DDD.*

Ya por ultimo y después de un análisis y discusión grupal, los siguientes bounded contexts fueron elegidos.<br>
![image](https://github.com/user-attachments/assets/3c5320ab-ec90-4dcd-b3f4-343eaa0051da)
<br>*Evidencia del desarrollo del DDD*

<br>Revisar el Mural para un mayor detalle:
[Eventstorming DittoBox](https://app.mural.co/t/ditto4864/m/ditto4864/1725121777423/239190dadf52ee7435517714464aff1e7a8980cd?sender=u68114f0b4359c72ffebc1564)

#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
De acuerdo con los boundend contexts definidos en puntos anteriores, se crearon sus respectivos Canvases:
![BoundedContext1](/img/BDContext1.png)

![BoundedContext2](/img/BDContext2.png)

![BoundedContext3](/img/BDContext3.png)

![BoundedContext4](/img/BDContext4.png)

### 4.1.2. Context Mapping

### Container Management Context
![image](https://github.com/user-attachments/assets/a28e4fbb-18ca-4674-95d1-dbe4c840216a)
![image](https://github.com/user-attachments/assets/9b2f5549-4b87-4418-8992-27b3976bcf78)
### Account & Subscriptions Management Context
![image](https://github.com/user-attachments/assets/2dfcfb71-ef5a-47ea-b879-c17b24573bee)
### User and Profile Management Context
![image](https://github.com/user-attachments/assets/e6f1c25a-7809-4b53-9791-bbf9f7f76188)
### Group Context
![image](https://github.com/user-attachments/assets/b62b131b-1d45-4933-af71-5fb180bd6e2c)

### Context Mapping
1. Container Management Context ↔ Account & Subscriptions Management Context:
Relación clave: El Container Management Context necesita verificar las suscripciones y los permisos de los usuarios antes de permitir que gestionen los contenedores. El Account & Subscriptions Management Context proporciona la validación necesaria para permitir o denegar el acceso, asegurando que solo los usuarios con una suscripción válida y los permisos adecuados puedan interactuar con los contenedores.
2. Account & Subscriptions Management Context ↔ User and Profile Management Context:
Relación clave: El Account & Subscriptions Management Context depende del User and Profile Management Context para manejar la autenticación y los perfiles de usuario. Aquí, la información sobre los usuarios, sus privilegios y permisos es clave para asociar las suscripciones y validar el acceso a las funcionalidades del sistema.
3. User and Profile Management Context ↔ Group Context:
Relación clave: El User and Profile Management Context se relaciona con el Group Context para gestionar los roles y permisos a nivel grupal. Esto es importante en el caso de organizaciones que gestionan múltiples usuarios en grupos, donde ciertos usuarios pueden tener privilegios que les otorgan diferentes niveles de acceso.

<p align="center">
  <img src="../img/BoundedContext.png"/>
</p>

Para una mejor visibilidad: https://app.mural.co/t/ditto4864/m/ditto4864/1725121777423/239190dadf52ee7435517714464aff1e7a8980cd?sender=u68114f0b4359c72ffebc1564



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

El dominio de Container Management describe detalladamente las funciones y procesos que se llevan a cabo para la gestión de contenedores dentro de nuestra plataforma. Este dominio es responsable de manejar todas las operaciones relacionadas con la creación, monitoreo, y mantenimiento de contenedores. Esto incluye la asignación de plantillas de control, el monitoreo de la salud del contenedor, la gestión de alertas en caso de que los umbrales establecidos sean superados, y la regulación automática de la temperatura, humedad, y ventilación dentro de los contenedores. Garantiza que los contenedores operen dentro de los parámetros deseados y que los eventos inesperados o problemas de funcionamiento sean manejados de manera eficiente, proporcionando un servicio confiable y seguro para los usuarios.

##### Diccionario de Clases

El Diccionario de Clases es una herramienta clave en el proceso de diseño y desarrollo del sistema de gestión de contenedores. Proporciona una descripción detallada de las clases fundamentales que forman la base del modelo de dominio. Este diccionario documenta las entidades, sus atributos, métodos y relaciones, lo que facilita la comprensión y colaboración entre los desarrolladores, garantizando una base sólida para la solución implementada en el proyecto de Container Management.

![Container chart class](/img/Container-chart-class.png)

![Template chart class](/img/template-chart-class.png)

![Alert chart class](/img/alert-chart-class.png)

![AlertInstance chart class](/img/alertinstance-chart-class.png)

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
