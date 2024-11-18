# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.

En esta sección, el equipo establece las decisiones y convenciones que permitirán mantener la consistencia durante todo el ciclo de vida del desarrollo de software para DittoBox. La configuración abarca la gestión del código fuente, la configuración del entorno de desarrollo y el despliegue de las aplicaciones. Estas decisiones garantizan una colaboración eficiente, asegurando que todos los miembros del equipo trabajen de manera coherente y organizada.
<br>

### 6.1.1. Software Development Environment Configuration.

En esta sección se especifican y describen las herramientas y productos de software que los miembros del equipo deben utilizar durante el ciclo de vida del desarrollo de **DittoBox**, para garantizar la colaboración eficiente y la consistencia en el proyecto. Estas herramientas cubren todas las áreas clave, incluyendo la gestión del proyecto, el diseño UX/UI, el desarrollo, las pruebas y el despliegue.

#### Project Management

- **Herramienta**: Jira
- **Propósito**: Gestionar tareas, sprints y backlog del proyecto. Se utilizará para la planificación y seguimiento del progreso del equipo.
- **Ruta de acceso**: SaaS. https://www.atlassian.com/software/jira

#### UX/UI Design

- **Herramienta**: Figma
- **Propósito**: Diseño colaborativo de las interfaces de usuario para la aplicación web y móvil. Permite al equipo diseñar, prototipar y colaborar en tiempo real en el diseño UX/UI de **DittoBox**.
- **Ruta de acceso**: SaaS. https://www.figma.com/

- **Herramienta adicional**: UXPressia
- **Propósito**: Mapeo de la experiencia del usuario y creación de journey maps. Utilizado para comprender y planificar las interacciones del usuario con el sistema, mejorando así la experiencia de usuario.
- **Ruta de acceso**: SaaS. https://uxpressia.com/

#### Software Development

##### Landing Page Development

- **Herramientas**: HTML5 y CSS
- **Propósito**: Desarrollo de la página de aterrizaje de DittoBox, donde se presentará la propuesta de valor del producto.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: https://code.visualstudio.com/

##### Web Application Development

- **Herramienta**: Angular
- **Propósito**: Desarrollo del frontend para la aplicación web de DittoBox. Angular se utiliza para crear una interfaz de usuario interactiva y modular, permitiendo una experiencia fluida para los usuarios web.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: https://code.visualstudio.com/

##### Mobile Application Development

- **Herramienta**: Flutter
- **Propósito**: Desarrollo de la aplicación móvil multiplataforma de DittoBox (iOS y Android). Flutter permite crear una aplicación nativa con un solo código base, lo que mejora la eficiencia en el desarrollo y el mantenimiento.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: https://code.visualstudio.com/

##### App Services (Backend Development)

- **Lenguaje**: C# con ASP.NET y .NET
- **Propósito**: Desarrollo de los servicios de backend de DittoBox. Estos servicios gestionan la lógica del negocio, la comunicación con la base de datos, y la integración con el sistema de IoT.
- **Editor de código**: Visual Studio Community
- **Ruta de descarga**: https://visualstudio.microsoft.com/es/vs/community/

#### Software Testing

- **Herramienta**: Selenium
- **Propósito**: Automatización de las pruebas de la aplicación web y móvil de DittoBox. Selenium se utilizará para crear scripts de prueba que validen la funcionalidad de la aplicación en diferentes navegadores y dispositivos.
- **Ruta de descarga**: https://www.selenium.dev/downloads/

#### Software Deployment

- **Herramienta**: Azure
- **Propósito**: Despliegue y administración de los servicios backend, frontend web y la aplicación móvil en entornos de producción. Azure proporciona una infraestructura escalable para garantizar la alta disponibilidad y el rendimiento de DittoBox.
- **Ruta de acceso**: SaaS. https://azure.microsoft.com/

#### Software Documentation

- **Herramientas**: GitHub y Markdown
- **Propósito**: La documentación técnica del proyecto DittoBox se gestiona en un repositorio privado de GitHub. Todo el equipo tiene acceso a este repositorio para colaborar en la redacción, edición y revisión de la documentación. Utilizamos Markdown como el formato de escritura, lo que permite una estructuración clara y consistente de la información técnica.

  - **Repositorio GitHub**: El informe y la documentación técnica de DittoBox están disponibles en un repositorio dedicado en GitHub.
  - **Formato**: Markdown para mantener la legibilidad, la facilidad de edición y el control de versiones.
  - **Ruta de acceso**: SaaS. https://github.com/

#### Source Code Management

- **Herramienta**: GitHub
- **Propósito**: Plataforma de control de versiones utilizada para gestionar el código fuente de todos los componentes de DittoBox, incluyendo el backend, frontend y la aplicación móvil. GitHub permitirá colaborar eficientemente, realizar seguimientos de cambios y gestionar el ciclo de vida del código.
- **Ruta de acceso**: SaaS. https://github.com/

### 6.1.2. Source Code Management.

En esta sección se detalla cómo el equipo de **DittoBox** gestionará el código fuente utilizando **GitHub** como plataforma y sistema de control de versiones. A continuación, se describen los medios y el esquema de organización que se implementarán para el seguimiento de modificaciones. El equipo aplicará el workflow **GitFlow** para organizar las ramas de desarrollo y mantendrá un seguimiento estricto del versionado y los commits.

#### Repositorios en GitHub

Cada uno de los componentes del proyecto DittoBox tendrá un repositorio en **GitHub**, donde se gestionará tanto el código fuente como las pruebas asociadas (pruebas unitarias e integradas). Los repositorios principales incluyen:

- **Organización**: Organización creada en GitHub donde están todos los repositorios que comprenden a la solución desarrollada

  - **URL de la organización**: https://github.com/DittoBox

- **Reporte**: Reposutorio donde se encuentra el reporte del trabajo desarrollado, usando Markdown.

  - **URL del repositorio**: https://github.com/DittoBox/FinalProjectReport

- **Landing Page**: Landing Page, desarrollada en HTML5 y CSS.
  - **URL del repositorio**: https://github.com/DittoBox/DittoBox-static
- **Web Services (Backend)**: Servicios backend desarrollados en C# con ASP.NET y .NET, junto con las pruebas unitarias y de integración.

  - **URL del repositorio**: https://github.com/DittoBox/DittoBox.API

- **Frontend Web Application**: Aplicación web desarrollada en Angular.

  - **URL del repositorio**: https://github.com/DittoBox/DittoBox-WebApp

- **Mobile Application**: Aplicación móvil multiplataforma desarrollada en Flutter.
  - **URL del repositorio**: https://github.com/DittoBox/DittoBox-Mobile

#### GitFlow Workflow

El equipo adoptará **GitFlow** como el modelo de control de versiones para gestionar las ramas del proyecto. Este flujo de trabajo permite una organización clara y estructurada del ciclo de desarrollo, desde el trabajo en nuevas características hasta las correcciones y lanzamientos.

Las principales ramas que se utilizarán son:

- **main**: Rama principal que contiene las versiones estables del proyecto, listas para producción.
- **develop**: Rama donde se integran las nuevas funcionalidades y correcciones antes de ser lanzadas a producción.
- **deployment** : Rama utilizada para la implementación de la aplicación en entornos de prueba o producción.

#### Ramas de características (feature branches)

Cada nueva funcionalidad o mejora se desarrollará en una rama de características, que se creará a partir de `develop`. Una vez que la funcionalidad esté completa y probada, la rama será fusionada nuevamente en `develop`.

- **Convención de nombres**: `feature/[nombre-descriptivo]`
  - Ejemplo: `feature/ajuste-temperatura`

#### Ramas de lanzamiento (release branches)

Las ramas de lanzamiento se crearán desde `develop` cuando un conjunto de funcionalidades esté listo para ser lanzado. Durante esta fase se realizan las pruebas finales y los ajustes necesarios antes de fusionarla en `main`.

- **Convención de nombres**: `release/[número-de-versión]`
  - Ejemplo: `release/1.0.0`

#### Ramas de corrección rápida (hotfix branches)

Para corregir errores críticos en producción, se crearán ramas de corrección rápida directamente desde `main`. Una vez corregido el error, se fusionará tanto en `main` como en `develop` para garantizar la coherencia entre ambas ramas.

- **Convención de nombres**: `hotfix/[descripción]`
  - Ejemplo: `hotfix/correccion-errores-api`

#### Semantic Versioning

El equipo aplicará **Semantic Versioning** (Versionado Semántico) para las versiones de lanzamiento del software. Este sistema de versionado sigue el formato `vX.X.X`:

- **X.**: Para cambios mayores que incluyen modificaciones significativas que no son compatibles con versiones anteriores.
- **.X**: Para nuevas funcionalidades que no rompen la compatibilidad con versiones anteriores.
- **.X**: Para correcciones de errores y pequeñas mejoras.

Ejemplos de versiones:

- `v1.0.0`: Primera versión estable de DittoBox.
- `v1.1.0`: Versión con nuevas funcionalidades agregadas.
- `v1.1.1`: Versión con correcciones menores y mejoras.

#### Conventional Commits

Para mantener un historial de commits claro y consistente, el equipo utilizará **Conventional Commits** para los mensajes de commit. Esta convención asegura que cada mensaje de commit refleje de forma precisa el tipo de cambio realizado en el código. Los tipos de commit son los siguientes:

- **feat**: Para la adición de una nueva funcionalidad.

  - Ejemplo: `feat: agregar ajuste automático de temperatura`

- **fix**: Para corrección de errores.

  - Ejemplo: `fix: corregir bug en la sincronización de datos`

- **docs**: Para cambios en la documentación.

  - Ejemplo: `docs: actualizar la documentación de la API`

- **style**: Para cambios que no afectan la lógica del código, como ajustes de formato.

  - Ejemplo: `style: corregir formato en archivo CSS`

- **refactor**: Para reestructuración del código que no añade nuevas funcionalidades ni corrige errores.
  - Ejemplo: `refactor: simplificar el manejo de eventos en la interfaz`

#### Proceso de Revisión de Código

Todo cambio en el código deberá pasar por un proceso de revisión antes de ser fusionado en las ramas `develop` o `main`. Este proceso se realizará a través de **pull requests (PRs)** en GitHub, y al menos un miembro del equipo debe aprobar el PR antes de proceder con la fusión.

El objetivo de esta revisión es garantizar la calidad del código y asegurar que las nuevas funcionalidades, correcciones o mejoras no rompan la estabilidad del sistema.

### 6.1.3. Source Code Style Guide & Conventions.

Esta parte establece las convenciones y guías de estilo que el equipo adoptará para la codificación en los diferentes lenguajes utilizados en el proyecto. Su propósito es garantizar la consistencia, legibilidad y mantenibilidad del código durante todo el ciclo de vida del desarrollo del software.

#### Nomenclatura General

Para todos los lenguajes, se seguirán las siguientes convenciones de nomenclatura:

- **Lenguajes**: HTML, CSS, JavaScript, TypeScript, C#, Dart , Gherkin (para archivos `.feature`).
- **Convención en inglés**: Todos los nombres de variables, funciones, métodos, clases y archivos se nombrarán en inglés.
- **Convención de nombres**:
  - **CamelCase**: Para nombres de variables, funciones y métodos.  
    Ejemplo: `calculateTotalAmount`.
  - **PascalCase**: Para nombres de clases y componentes.  
    Ejemplo: `UserService`, `ProductController`.
  - **snake_case**: Para nombres de archivos.  
    Ejemplo: `user_profile.dart`.

#### Convenciones por Lenguaje

##### HTML/CSS

- **Estilo**: Seguir la https://google.github.io/styleguide/htmlcssguide.html.
- **HTML**: Usar etiquetas semánticas, atributos en minúsculas y entre comillas dobles.
- **CSS**: Aplicar la metodología **BEM (Block Element Modifier)** para los nombres de clases.
- **Indentación**: Usar 2 espacios para la indentación.

**Ejemplo en HTML:**

```html
<div class="user-profile">
  <h1>User Profile</h1>
  <p>Welcome, John Doe</p>
</div>
```

**Ejemplo en CSS:**

```css
.user-profile__name {
  font-size: 18px;
  color: #333;
}
```

#### JavaScript

- **Estilo**: Seguir la https://google.github.io/styleguide/jsguide.html.
- Usar `let` y `const` en lugar de `var`.
- Priorizar el uso de funciones flecha y mantener los métodos pequeños y modulares.

**Ejemplo en JavaScript:**

```javascript
const calculateTotal = (price, quantity) => {
  return price * quantity;
};
```

#### TypeScript

- **Estilo**: Seguir la https://google.github.io/styleguide/tsguide.html.
- Usar el sistema de tipado fuerte de TypeScript para prevenir errores en tiempo de compilación.

**Ejemplo en TypeScript:**

```typescript
interface User {
  id: number;
  name: string;
}

const getUserName = (user: User): string => {
  return user.name;
};
```

#### Dart

- **Estilo**: Seguir la https://dart.dev/guides/language/effective-dart.
- Usar el sistema de tipado fuerte de Dart para prevenir errores en tiempo de compilación.

**Ejemplo en Dart:**

```dart
class User {
  final int id;
  final String name;

  User(this.id, this.name);
}

String getUserName(User user) {
  return user.name;
}
```

#### C#

- **Estilo**: Seguir la https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/.
- Usar modificadores de acceso explícitos (`public`, `private`) para definir el alcance de las clases y métodos.

**Ejemplo en C#:**

```csharp
public class UserController {
    public string GetUser(int id) {
        return "User" + id;
    }
}
```

#### Gherkin

- **Estilo**: Seguir las https://cucumber.io/docs/gherkin/ para escribir casos de prueba legibles y bien estructurados.

**Ejemplo en Gherkin:**

```gherkin
Feature: User Login

Scenario: Successful login
  Given the user is on the login page
  When they enter valid credentials
  Then they should be redirected to the dashboard
```

#### Convenciones de Código

##### Comentarios

- Los comentarios deben ser útiles, explicativos y evitar redundancias.
- Usar el formato adecuado de comentarios según el lenguaje. Ejemplo:
  - **JavaScript/C#/Kotlin**: `//`
  - **Dart**: `///`

**Ejemplo en Dart:**

```dart
/// This method calculates the total price of an order
double calculateTotal(double price, int quantity) {
  return price * quantity;
}
```

#### Referencias

- https://google.github.io/styleguide/htmlcssguide.html
- https://google.github.io/styleguide/jsguide.html
- https://google.github.io/styleguide/tsguide.html
- https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/
- https://cucumber.io/docs/gherkin/

### 6.1.4. Software Deployment Configuration.

La configuración de despliegue de software para la solución propuesta por DittoBox depende del componente específico que se esté desplegando. A continuación, se detallan las configuraciones de despliegue para cada uno de los componentes principales del proyecto.

#### Landing Page

El landing page se desplegará como una página web estática, haciendo uso de https://azure.microsoft.com/products/app-service/static/. Este servicio de Azure permite alojar aplicaciones web estáticas de forma sencilla y escalable, proporcionando un entorno seguro y de alto rendimiento para el landing page de DittoBox.

##### Proceso de Despliegue:

- **Clonar Repositorio**: Clonar el repositorio de la landing page desde GitHub.
- **Configuración de Azure Static Web Apps**: Crear una instancia de Azure Static Web Apps y configurarla para que apunte al repositorio clonado.
- **Despliegue Automático**: Configurar el despliegue automático desde GitHub, de modo que cada cambio en el repositorio se refleje automáticamente en el landing page. La rama principal (`main`) se utilizará para el despliegue para garantizar la estabilidad.

#### Web Application

La aplicación web de DittoBox, desarrollada en Angular, se desplegará en https://azure.microsoft.com/services/app-service/. Este servicio de Azure permite alojar aplicaciones web y APIs de forma escalable y segura, con opciones de escalado automático y alta disponibilidad.

##### Proceso de Despliegue:

- **Clonar Repositorio**: Clonar el repositorio de la aplicación web desde GitHub.
- **Configuración de Azure App Service**: Crear una instancia de Azure App Service y configurarla para que apunte al repositorio clonado.
- **Despliegue Automático**: Configurar el despliegue automático desde GitHub, de modo que cada cambio en el repositorio se refleje automáticamente en la aplicación web. La rama principal (`main`) se utilizará para el despliegue para garantizar la estabilidad. Adicionalmente, se configurarán dos slots de implementación (`staging` y `development`) para pruebas y validaciones previas al despliegue en producción. Las ramas `staging` y `development` se utilizarán para desplegar en los slots de implementación.

#### Mobile Application

La aplicación móvil de DittoBox, desarrollada en Flutter, se distribuirá inicialmente como un paquete de instalación (APK para Android) de descarga directa desde el landing page. Esto es debido a que este es un prototipo inicial y no se distribuirá a través de las tiendas de aplicaciones en esta etapa hasta validar la funcionalidad, calidad y viabilidad económica del producto.

##### Proceso de Despliegue:

- **Configuración de workflow**: Crear un flujo de trabajo en GitHub Actions para compilar y generar el paquete de instalación de la aplicación móvil.
- **Carga del APK**: Subir el APK generado a un servicio de almacenamiento en la nube, Azure Blob Storage, al cual se accederá desde el landing page para la descarga.

#### App Services (Backend)

Los servicios backend de DittoBox, desarrollados en C# con ASP.NET y .NET, se desplegarán en https://azure.microsoft.com/services/app-service/. Estos servicios se alojarán en un entorno de producción seguro y escalable, con opciones de escalado automático y alta disponibilidad para garantizar el rendimiento y la disponibilidad de la aplicación.

##### Proceso de Despliegue:

- **Clonar Repositorio**: Clonar el repositorio de los servicios backend desde GitHub.
- **Configuración de Azure App Service**: Crear una instancia de Azure App Service y configurarla para que apunte al repositorio clonado.
- **Despliegue Automático**: Configurar el despliegue automático desde GitHub, de modo que cada cambio en el repositorio se refleje automáticamente en los servicios backend. La rama principal (`main`) se utilizará para el despliegue para garantizar la estabilidad. Adicionalmente, se configurarán dos slots de implementación (`staging` y `development`) para pruebas y validaciones previas al despliegue en producción. Las ramas `staging` y `development` se utilizarán para desplegar en los slots de implementación.
- **Conexión con Base de Datos**: Configurar la conexión con la base de datos de Azure SQL Database para que los servicios backend puedan acceder y gestionar los datos de la aplicación. El slot de producción se conectará a la base de datos de producción, mientras que los slots de implementación (`staging` y `development`) se conectarán a bases de datos de prueba, la cual es una copia de la base de datos de producción realizada de forma regular para pruebas.

#### Embedded application

La aplicación embebida en el dispositivo IoT se desplegará a través de un proceso de actualización de firmware. Este proceso se realizará de forma remota, permitiendo la instalación de nuevas versiones de la aplicación en los dispositivos IoT conectados a la red. Durante el proceso de fabricación de los dispositivos, sin embargo, se instalará la versión estable más reciente de la aplicación embebida.

##### Proceso de Despliegue:

- **Compilación de embedded application**: Compilar la aplicación embebida en un archivo de firmware compatible con los dispositivos IoT.
- **Carga del firmware**: Subir el archivo de firmware a un servicio de almacenamiento en la nube, Azure Blob Storage, al cual se accederá para la actualización remota de los dispositivos IoT.
- **Actualización remota**: Configurar el proceso de actualización remota de firmware para los dispositivos IoT, de modo que puedan descargar e instalar la nueva versión de la aplicación embebida de forma segura y automática. El dispositivo IoT, en intervalos determinados, comprobará la disponibilidad de nuevas actualizaciones y las instalará si están disponibles. Opcionalmente, el usuario puede iniciar manualmente el proceso de actualización desde la aplicación de escritorio con los dispositivos conectados.

## 6.2. Landing Page, Services & Applications Implementation.

En esta sección, detallamos el proceso completo de implementación, pruebas, documentación y despliegue de los distintos componentes que conforman la solución DittoBox. Esto incluye el desarrollo de nuestra Landing Page, que sirve como punto de entrada y presentación de nuestro producto al público general, así como la implementación de los Servicios Web, Aplicaciones Web, Aplicaciones Móviles y Aplicaciones Embebidas que constituyen el núcleo funcional de nuestra propuesta.

A lo largo de esta sección, explicamos cómo hemos abordado cada fase del ciclo de vida del desarrollo de software para estos componentes, desde la planificación inicial y el diseño, hasta la ejecución de pruebas y el despliegue en entornos de producción. Detallamos las tecnologías utilizadas, los desafíos enfrentados y las soluciones implementadas para asegurar que cada componente cumpla con los requisitos establecidos y proporcione una experiencia de usuario óptima.

### 6.2.1. Sprint 1

En el Sprint 1, nuestro equipo se enfocó en el desarrollo y despliegue de la Landing Page para DittoBox, con el objetivo de crear un punto de entrada amigable y accesible que causara una excelente primera impresión y proporcionara información clave a potenciales clientes.

##### 6.2.1.1. Sprint Planning 1.

| Sprint #                   | Sprint 1                                                                                                                                                                                                        |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sprint Planning Background |
| Date                       | 2024-09-21                                                                                                                                                                                                     |
| Location                   | Universidad Peruana de Ciencias Aplicadas, Campus Villa                                                                                                                                                         |
| Prepared by                | Cancho Coila, Diego Fabian                                                                                                                                                                                      |
| Attendees                  | Cancho Coila, Diego Fabian / Arenas Conde, José Anthony / Lagos Aguilar, Luis Eduardo / Guerrero Castillo, Anthony Jeandet / Chamorro Torres, Samuel Rolando                                                    |
| Sprint Goal & User Stories |
| Sprint 1 Goal              | Our focus is on developing and deploying the landing page for DittoBox with essential service, contact, testimonial, and pricing sections. <br> We believe it delivers a user-friendly and accessible entry point to DittoBox, enhancing first impressions and providing key information to potential customers. This will be confirmed when the landing page is live, fully responsive, and meets accessibility standards across devices. |
| Sprint 1 Velocity          | 20 Story Points                                                                                                                                                                                                 |
| Sum of Story Points        | 20 Story Points                                                                                                                                                                                                 |

##### 6.2.1.2. Sprint Backlog 1

| Sprint #   | Sprint 1                                                                                          |     |       |             |            |             |        |
| ---------- | ------------------------------------------------------------------------------------------------- | --- | ----- | ----------- | ---------- | ----------- | ------ |
| User story | Work-Item / Task                                                                                   |
| Id         | Title                                                                                              | Id  | Title  | Description | Estimation | Assigned to | Status |
| DIT-317    | Add information about the service in landing page                                                  |     |       |             |            |             |        |
|            |                                                                                                    | WIT-1 | Design service info section | Create and design the section to display the service information on the landing page. | 2         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-2 | Write service content | Write the text to explain the platform's features and benefits. | 1         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-3 | Implement service info section | Add and implement the service section into the landing page. | 3         | Samuel Chamorro    | Completed |
| DIT-318    | Contact with sales team in landing page                                                            |     |       |             |            |             |        |
|            |                                                                                                    | WIT-4 | Design contact form layout | Create a simple and user-friendly contact form layout. | 2         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-5 | Develop form functionality | Implement the backend for the contact form. | 3         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-6 | Test form and integration | Test the contact form for usability and integrate it into the landing page. | 2         | Samuel Chamorro    | Completed |
| DIT-319    | Customers' review in landing page                                                                  |     |       |             |            |             |        |
|            |                                                                                                    | WIT-7 | Collect testimonials | Gather customer reviews and success stories to feature. | 2         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-8 | Design testimonials section | Design a visually appealing section for displaying testimonials. | 3         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-9 | Implement testimonials section | Add and integrate the testimonials section into the landing page. | 3         | Samuel Chamorro    | Completed |
| DIT-320    | Prices and tiers information on landing page                                                       |     |       |             |            |             |        |
|            |                                                                                                    | WIT-10 | Design pricing table | Create a layout to display pricing tiers and details. | 3         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-11 | Write plan descriptions | Write descriptions for each pricing plan. | 2         | Samuel Chamorro    | Completed |
|            |                                                                                                    | WIT-12 | Implement pricing table | Develop and integrate the pricing table on the landing page. | 4         | Samuel Chamorro    | Completed |


##### 6.2.1.3. Development Evidence for Sprint Review.

| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                                         | Committed on (Date)    |
|----------------------|--------------------|-----------|--------------------------------------------------------------|-------------------------------------------------------------|------------------------|
| DittoBox-WebApp      | hotfix-fakeapi      | 4ecdbb2   | fix: update fakeapi url                                       | Merged pull request #3 from DittoBox/hotfix-fakeapi          | 27/09/2024             |
| DittoBox-WebApp      | main(#3)            | 085e98a   | fix: update fakeapi url                                       | Updating fakeapi url                                         | 27/09/2024             |
| DittoBox-WebApp      | develop             | 8d95475   | Merge pull request #2 from DittoBox/develop                   | Merged develop branch                                        | 27/09/2024             |
| DittoBox-WebApp      | main(#1)            | 244b710   | feat: updating container-item component                       | Updating container-item component                            | 27/09/2024             |
| DittoBox-static      | main               | cd201ec   | Update call to action                                         | Updated call to action section on the static page.           | 27/09/2024             |
| DittoBox-static      | main(#1)           | 752878e   | Merge pull request #1 from DittoBox/fix-names                 | Remove unnecessary license and readme files, update page title. | 27/09/2024             |
| DittoBox-static      | main(#1)           | a0b948a   | fix: Remove unnecessary license and readme files, and update page title | Removed license, readme files and updated page title.       | 27/09/2024             |


##### 6.2.1.4. Testing Suite Evidence for Sprint Review.
No se han realzado archivos de testing, debido a que el producto realizado no posee las funcionalidades necesarias para ser probada con herramientas de testing

##### 6.2.1.5. Execution Evidence for Sprint Review.
Para el logro de este proyecto, se realizó el despliegue tanto de la Landing Page, como la primera versión de la aplicación web, las cuales se encuentran en los siguientes enlaces a continuación:

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: https://black-dune-093481d10.5.azurestaticapps.net/.
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: https://dittobox.github.io/DittoBox-static/.


##### 6.2.1.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers.

##### 6.2.1.7. Software Deployment Evidence for Sprint Review.
La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: https://black-dune-093481d10.5.azurestaticapps.net/.
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: https://dittobox.github.io/DittoBox-static/.

##### 6.2.1.8. Team Collaboration Insights during Sprint.
Para esta sección del documentos, añadimos los insights realizados durante el sprint, tanto de la realización de la aplicación web, como el landing page:

Insight del Static Web App, donde se muestran los commits realizados en el ultimo mes del repositorio de
<img src="/img/insights%201.png" alt="Image insights 1" width="500"/>

Insights del Reporte o informe del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes
<img src="/img/insights%202.png" alt="Image insights 1" width="500"/>

Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/img/insight%203.png" alt="Image insights 1" width="500"/>



### 6.2.2. Sprint 2

En el Sprint 2, nuestro equipo se centró en la implementación de las funcionalidades clave para la gestión de usuarios y cuentas en las plataformas web y móvil de DittoBox. Este sprint tuvo como objetivo principal desarrollar e integrar endpoints REST, así como componentes de interfaz de usuario (UI) para la gestión de grupos y contenedores. Con estas mejoras, buscamos ofrecer a nuestros usuarios administrativos y clientes una mayor eficiencia y control en la administración de cuentas, suscripciones y funcionalidades de grupos.

##### 6.2.2.1. Sprint Planning 2.

| **Sprint #**                   | **Sprint 2**                                                                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background** |                                                                                                                                                                                                                     |
| **Date**                       | 2024-09-28                                                                                                                                                                                                          |
| **Location**                   | Universidad Peruana de Ciencias Aplicadas, Campus Villa                                                                                                                                                             |
| **Prepared by**                | Cancho Coila, Diego Fabian                                                                                                                                                                                          |
| **Attendees**                  | Cancho Coila, Diego Fabian / Arenas Conde, José Anthony / Lagos Aguilar, Luis Eduardo / Guerrero Castillo, Anthony Jeandet / Chamorro Torres, Samuel Rolando                                                        |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                     |
| **Sprint 2 Goal**              |Our focus is on implementing key features for user and account management across both web and mobile platforms, which includes creating and integrating REST endpoints, along with UI components for group and container management. We believe it delivers improved control and efficiency in managing user accounts, subscriptions, and group functionalities to our administrative users and customers. This will be confirmed when users can successfully create, update, and manage their accounts, groups, and containers via the web and mobile apps, and when real-time data for containers is displayed and modifiable.|
| **Sprint 2 Velocity**          | 75 Story Points                                                                                                                                                                                                     |
| **Sum of Story Points**        | 70 Story Points                                                                                                                                                                                                     |
##### 6.2.2.2. Sprint Backlog 2

#### Technical Stories y Tasks

| Sprint # | Sprint 2                                          |     |       |             |            |             |        |
|----------|---------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **Technical Story** | **Work-Item / Task**                         |
| **Id**     | **Title**                                       | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-12**   | Create REST endpoint for user management          | **DIT-331** | Implement mockup profile endpoints | Implement the mockup of profile endpoints for user management.    | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-324** | Implement mockup user endpoints  | Implement mockup user-related endpoints.                          | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-325** | Connect user endpoints to domain model | Connect the user endpoints to the domain model for user management. | 1         | Diego Cancho       | Done    |
| **DIT-13**   | Create REST endpoint for account management        | **DIT-327** | Implement mockup account endpoints | Create and implement mockup endpoints for account management.     | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-326** | Define account/subscription bounded context model | Define the bounded context model for accounts and subscriptions. | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-421** | Create account usage report endpoint | Create an endpoint to generate account usage reports.             | 1         | Diego Cancho       | Done    |
| **DIT-49**   | Implement REST endpoints for group management      | **DIT-451** | Implement Create Group Endpoint  | Implement services to create group endpoints.                     | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-452** | Implement Group Endpoint Commands Handler | Implement command handlers and interfaces for group endpoint creation. | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-453** | Create Group Repositories and Controller | Create repositories, resources, and controller for group endpoint management. | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-454** | Implement Get Group Endpoint Services | Implement services to retrieve group endpoints.                   | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-455** | Implement Get Group Query Handler | Implement query handlers and interfaces to retrieve group information. | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-456** | Implement Get Group Repositories and Controller | Implement repositories, resources, and controller for retrieving group details. | 1         | Jose Conde         | Done    |
| **DIT-91**   | Set up CI/CD pipelines for automated testing, deployment, and monitoring | **DIT-321** | Configure public GitHub repositories | Set up and configure public GitHub repositories for CI/CD pipelines. | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-322** | Create Azure services and connect workflows | Set up Azure services and integrate with CI/CD workflows.        | 1         | Diego Cancho       | Done    |
| **DIT-92**   | Implement email service integration                | **DIT-410** | Configure Azure Communication Services | Configure Azure Communication Services for email integration.     | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-411** | Define and connect email service to cloud server | Define and establish the email service connection to the cloud server. | 1         | Diego Cancho       | Done    |
| **DIT-471**  | Implement REST endpoints for container management  | **DIT-459** | Implement mockup container endpoints | Implement mockup container-related endpoints for management.      | 1         | Anthony Guerrero   | Done    |
|            |                                                   | **DIT-458** | Define container bounded context model | Define the bounded context model for container management.        | 1         | Anthony Guerrero   | Done    |
|            |                                                   | **DIT-461** | Connect container endpoints to domain model | Connect the container endpoints to the domain model.              | 1         | Anthony Guerrero   | Done    |


#### User Stories y Tasks

| Sprint # | Sprint 2                                          |     |       |             |            |             |        |
|----------|---------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **User Story** | **Work-Item / Task**                         |
| **Id**     | **Title**                                       | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-109**  | Revoke subscription privileges in the mobile app  | **DIT-467** | Design Revoke Privileges Subscription UI | Design the UI for revoking subscription privileges in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-108**  | Grant subscription privileges in the mobile app   | **DIT-465** | Design Privileges Subscription UI | Design the UI for granting subscription privileges in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-105**  | Revoke privileges from a user in the mobile app   | **DIT-467** | Design Revoke Privileges UI      | Design the UI for revoking privileges from a user in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-110**  | View account information in the mobile app        | **DIT-457** | User Account Information UI      | Design and implement the user account information UI for the mobile app. | 1         | Luis Lagos         | Done    |
| **DIT-377**  | View notifications in the web app                 | **DIT-416** | Create filters for notifications | Create filters to manage and display notifications in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                   | **DIT-447** | Integrate alert notifications    | Integrate alert notifications so users receive alerts when thresholds are exceeded. | 1         | Samuel Chamorro    | Done    |
| **DIT-374**  | Change language in the web app                    | **DIT-419** | Implement i18n in the web app    | Implement internationalization (i18n) for multiple language support in the web app. | 1         | Luis Lagos         | Done    |
| **DIT-42**   | Update account information in the web app         | **DIT-420** | Create dialog for account updates | Create a dialog to allow users to update their account information in the web app. | 1         | Luis Lagos         | Done    |
| **DIT-41**   | View account information in the web app           | **DIT-388** | Implement static subscription view | Implement a static view to display subscription details in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                   | **DIT-418** | Implement static account information view | Implement a static view for account information in the web app.  | 1         | Luis Lagos         | Done    |
| **DIT-45**   | Upgrade a subscription in the web app             | **DIT-381** | Design subscription view         | Design the subscription view for the web app.                     | 1         | Luis Lagos         | Done    |
| **DIT-46**   | Downgrade a subscription in the web app           | **DIT-381** | Design subscription view         | Design the subscription view for downgrading a subscription in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                   | **DIT-396** | Create warning modal for downgrade | Create a modal warning users about the consequences of downgrading their subscription. | 1         | Diego Cancho       | Done    |
| **DIT-116**  | Create a group in the mobile app                   | **DIT-340** | Design Group Creation UI         | Design the UI for group creation in the mobile app.               | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-341** | Implement Validation for Group Fields | Implement input validation for the group creation fields.         | 1         | Diego Cancho       | Done    |
|            |                                                   | **DIT-342** | Backend Integration for Group Creation | Integrate backend services for group creation in the mobile app.  | 1         | Diego Cancho       | Done    |
| **DIT-119**  | View a group in the mobile app                     | **DIT-472** | View Group Details UI            | Design and implement the group details UI in the mobile app.      | 1         | Jose Conde         | Done    |
| **DIT-120**  | Register a worker to a group in the mobile app     | **DIT-352** | UI Design for Worker Registration | Design the UI for the worker registration screen in the mobile app. | 1         | Jose Conde         | Done    |
|            |                                                   | **DIT-353** | Backend Integration for Worker Registration | Integrate backend services for worker registration in the mobile app. | 1         | Samuel Chamorro    | Done    |
|            |                                                   | **DIT-354** | User Feedback and Confirmation Screen | Design the feedback and confirmation screens for worker registration. | 1         | Anthony Guerrero   | Done    |
| **DIT-70**   | View container status in the web app               | **DIT-359** | Design Container Status UI       | Design the UI for viewing the status of containers in the web app. | 1         | Anthony Guerrero   | Done    |
|            |                                                   | **DIT-360** | Implement Container Status Component | Implement the component for displaying container details in the web app. | 1         | Anthony Guerrero   | Done    |
|            |                                                   | **DIT-361** | Backend Integration for Container Status | Integrate backend services for retrieving container status information. | 1         | Anthony Guerrero   | Done    |
| **DIT-71**   | View container inner conditions in the web app     | **DIT-362** | Extend Container Details Component | Extend the container details component to display inner conditions. | 1         | Luis Lagos         | Done    |
|            |                                                   | **DIT-363** | Backend Integration for Inner Conditions | Integrate backend services for retrieving inner container conditions. | 1         | Luis Lagos         | Done    |
|            |                                                   | **DIT-371** | Implement State Management for Container Conditions | Implement state management for input fields and toggles to control container conditions. | 1         | Anthony Guerrero   | Done    |
|            |                                                   | **DIT-372** | Backend Integration for Updating Container Conditions | Integrate backend services to update container inner conditions.  | 1         | Luis Lagos         | Done    |

##### 6.2.2.3. Development Evidence for Sprint Review.

| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                   | Committed on (Date)    |
|----------------------|-----------|----------|--------------------------------------------------|-------------------------------------------------------------|------------------------|
| DittoBox-static      | develop   | 1ca177f  | Add language switcher for English and Spanish    | Implemented a language toggle switch on the landing page to switch between English and Spanish.  | 18/10/2024  |
| DittoBox-static      | develop   | 23150de  | Updated App Store Botton   | Updated App Store Botton  | 02/11/2024  |
| DittoBox-webapp      | develop   | 53e3f89  | fix(routes): resolve problems of route | resolve problems of route | 02/11/2024 |
| DittoBox-webapp      | develop   | f769c5c  | fix(styles): remove background color from full-height class | remove background color from full-height class | 03/11/2024 |
| DittoBox-webapp      | develop   | b077bb6  | feat(db): add new notifications to db.json | add new notifications to db.json | 03/11/2024 |
| DittoBox-mobile      | develop   | e819ace  | fix(account-details): resolve translation english issue on mobile view | resolve translation english issue on mobile view | 02/11/2024 |
| DittoBox-mobile      | develop   | 57be830  | fix(account-details): resolve navigation spanish issue on mobile view | resolve navigation spanish issue on mobile view | 02/11/2024 |
| DittoBox-mobile      | develop   | 4f40904  | feat(account-details): add account details localization and update navigation | add account details localization and update navigation | 02/11/2024 |
| DittoBox.API         | develop   | bca3992  | feat: add get subscription and create subscription endpoint | add get subscription and create subscription endpoint | 02/11/2024 |
| DittoBox.API         | develop   | 3b0da34  | feat: complete account endpoints | complete account endpoints | 02/11/2024 |
| DittoBox.API         | develop   | be3f0c3  | hotfix: check missing changes | check missing changes | 03/11/2024 |
| DittoBox.Embedded    | develop   | 9c31616  | fix: conections to board sp32 fixed | conections to board sp32 fixed | 01/11/2024 |
| DittoBox.Embedded    | develop   | e2ad229  | feaT: add health monitor | add health monitor | 01/11/2024 |
| DittoBox.Embedded    | develop   | e6206fd  | feat: add health monitoring data to REST payload | add health monitoring data to REST payload | 02/11/2024 |

##### 6.2.2.4. Testing Suite Evidence for Sprint Review.

En esta sección se explica y presenta el conjunto de Unit Tests, Integration Tests y Acceptance Tests automatizados para los Web Services correspondientes a las User Stories especificadas en el Sprint. Estos tests fueron diseñados bajo el enfoque BDD utilizando el lenguaje Gherkin para los archivos .feature y Steps en el lenguaje de programación correspondiente.

#### Unit Tests
Los Unit Tests se enfocan en validar clases y comportamientos específicos dentro de la aplicación. Se han diseñado para asegurar que las unidades individuales de código (métodos y funciones) funcionen correctamente. Los archivos de Unit Testing se encuentran en la rama feature/unit-tests, y el commit relevante para los avances en esta entrega


#### Integration Tests
Los Integration Tests tienen como objetivo validar que los diferentes módulos o servicios de la aplicación se integren y funcionen de manera conjunta como se espera. Estos tests fueron añadidos en la rama feature/integration-tests y su commit se detalla en la tabla

#### Acceptance Tests
Para los Acceptance Tests, se utilizaron User Stories específicas para probar las funcionalidades desde la perspectiva del usuario final. Los archivos .feature contienen los escenarios en lenguaje Gherkin, que validan los criterios de aceptación definidos para cada historia de usuario. Los commits relacionados a estos avances se encuentran en la rama feature/acceptance-tests.


| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                   | Committed on (Date)    |
|----------------------|-----------|----------|--------------------------------------------------|-------------------------------------------------------------|------------------------|
| DittoBox-Testing      | feature/acceptance-tests   | e1de8a | feat: Add acceptance tests for various user features in the web app  |  | 3/11/2024  |
| DittoBox-Testing      | feature/acceptance-tests   | e1de8ae | Merge pull request #1 from DittoBox/feature/acceptance-test  |  | 3/11/2024  |
| DittoBox-Testing      | feature/integration-tests   | d94f677 | feat: added integration test files  |  | 3/11/2024  |
| DittoBox-Testing      | feature/unit-tests   | c84286d1| feat: Add acceptance tests for various user features in the web app  |  | 3/11/2024  |


##### 6.2.2.5. Execution Evidence for Sprint Review.
Para el logro de este proyecto, se realizó el despliegue tanto de la segunda versión de la aplicación web, como de la aplicación móvil las cuales se encuentran en los siguientes enlaces a continuación:

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: https://black-dune-093481d10.5.azurestaticapps.net/.
<img src="/img/Containers_DittoBox_Web_App.png" alt="Image insights 1" width="500"/>
<img src="/img/Templates_DittoBox_Web_App.png" alt="Image insights 1" width="500"/><br><br>
La aplicación móvil en Flutter ha sido deplegada en Firebase, y se puede acceder a través de la siguiente URL: https://appdistribution.firebase.google.com/pub/i/db6c701af66c0568.
<img src="/img/Templates_DittoBox_Mobile_App.png" alt="Image insights 1" width="150"/>
<img src="/img/Facilities_DittoBox_Mobile_App.png" alt="Image insights 1" width="150"/> <br>
Video de las aplicaciones en funcionamiento: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/EcuCFRDa25dJn74pSl-FLP0Bw8urTErBxYyyo6szCQZ8Bw?e=4MgHfh

##### 6.2.2.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers.

##### 6.2.2.7. Software Deployment Evidence for Sprint Review.
## Introducción

Durante este Sprint, se realizaron las actividades relacionadas con el **Deployment** de los distintos productos digitales del proyecto DittoBox. Esto incluyó el despliegue de aplicaciones web, servicios backend y landing page. Los pasos abarcaron desde la configuración inicial de los recursos en la nube hasta la automatización de ciertas tareas dentro del flujo de despliegue continuo. Los entornos utilizados abarcaron **Azure**, **Firebase Distribution** y **GitHub Pages**, según las características de cada producto.

## Procesos Realizados

1. **Despliegue del Web App y Web App Service en Azure (Entornos de Desarrollo y Producción)**  
   Se implementó la aplicación web en el servicio de **Azure Web App** en ambos entornos: desarrollo (dev) y producción (pro). Esto nos permitió probar y validar las funcionalidades en el entorno de desarrollo antes de implementarlas en producción.
   Para ello, se configuraron los siguientes aspectos:
    - *Creación de cuentas en Azure*: Utilizamos las credenciales proporcionadas por los Microsoft Learn Student Ambassadors de dos miembros del equipo para acceder a los servicios de Azure.
    - *Configuración del Web App Service*: Se crearon los recursos necesarios en Azure para ambos entornos y se automatizó el proceso de despliegue desde el repositorio del proyecto.
    - *Integración con el backend*: La aplicación web se conectó con el backend mediante los servicios de Azure, asegurando una comunicación eficiente y segura.

   <img src="/img/dittobox_pro_azure.jpeg" alt="Image insights 1" width="500"/><br>
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <img src="/img/dittobox_dev_azure.jpeg" alt="Image insights 1" width="500"/><br>
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <br>

<br>

2. **Distribución de la App Móvil mediante Firebase Distribution**  
   El deployment del aplicativo móvil se realizó utilizando **Firebase Distribution**, una herramienta que facilita la distribución de versiones de prueba a testers o usuarios internos antes de su lanzamiento oficial.
   - Configuración del proyecto en Firebase.
   - Subida de la APK/IPA para distribución interna.
   - Envío de invitaciones a los testers para que accedan a la aplicación y proporcionen retroalimentación.
    
   <img src="/img/firebase-app-distribution.png" alt="Image insights 1" width="500"/><br>
   *Panel de Firebase Distribution mostrando la versión más reciente de la app.*

3. **Despliegue de la Landing Page en GitHub Pages**  
    La landing page se desplegó utilizando **GitHub Pages**, aprovechando su simplicidad y la integración con el repositorio del proyecto:
    - Configuración del repositorio y activación de GitHub Pages.
    - Configuración del dominio personalizado y ajustes visuales según los requerimientos del cliente.
    - Verificación de la correcta visualización y responsividad en diferentes dispositivos.

<img src="/img/github_pages.png" alt="Image insights 1" width="500"/><br>
*Vista del despliegue en Github Pages.*

<img src="/img/github-pages-landing.png" alt="Image insights 1" width="500"/><br>
*Vista previa de la landing page en un navegador.*

##### 6.2.2.8. Team Collaboration Insights during Sprint.
En este Sprint, el equipo ha trabajado de manera colaborativa en la implementación de los diferentes productos: **Web Services**,  **Aplicación Móvil** y el **Embedded Application**. A continuación, se muestran los datos obtenidos de los analíticos de colaboración y commits en **GitHub**, realizados por los miembros del equipo. Estos datos reflejan la participación activa de cada integrante en las diferentes fases de desarrollo según la distribución de tareas asignadas.


#### Web Services
Insights del Web Services del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/webservices-insight-tb2.png" alt="Image insights 1" width="500"/><br>

#### Embedded Application
Insights del Embedded Application del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/embedded-insights-tb2.png" alt="Image insights 1" width="500"/><br>


#### Web App
Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes

<img src="/img/web-app-insights-tb2.png" alt="Image insights 1" width="500"/><br>

#### Mobile App
Insights del Mobile App, donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/app-insights-tb2.png" alt="Image insights 1" width="500"/><br>


### 6.2.3. Sprint 3
En el Sprint 3, nuestro equipo se centró en la implementación de nuevas funcionalidades y mejoras clave para optimizar la gestión de grupos, contenedores y el dashboard en las plataformas web y móvil de DittoBox. Este sprint tuvo como objetivo ofrecer una experiencia más eficiente y organizada para los usuarios, brindándoles nuevas herramientas para gestionar de manera integral los recursos dentro de la plataforma.

Entre las principales tareas realizadas, destacamos la creación de interfaces para la gestión de grupos y la integración con el backend para permitir la creación y visualización de grupos en la web. También avanzamos en la funcionalidad de registro de trabajadores a un grupo, facilitando la administración de equipos dentro de la plataforma. Para los contenedores, implementamos la posibilidad de vincularlos a cuentas y grupos, además de permitir a los usuarios ver el estado interno de los contenedores en tiempo real.

##### 6.2.3.1. Sprint Planning 3.

| **Sprint #**                   | **Sprint 3**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Date**                       | 2024-11-09                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Location**                   | Universidad Peruana de Ciencias Aplicadas, Campus Villa                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Prepared by**                | Cancho Coila, Diego Fabian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Attendees**                  | Cancho Coila, Diego Fabian / Arenas Conde, José Anthony / Lagos Aguilar, Luis Eduardo / Guerrero Castillo, Anthony Jeandet / Chamorro Torres, Samuel Rolando                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Sprint 3 Goal**              | Our focus is on implementing key features for user and account management across both web and mobile platforms, which includes creating and integrating REST endpoints, along with UI components for group and container management. We believe it delivers improved control and efficiency in managing user accounts, subscriptions, and group functionalities to our administrative users and customers. This will be confirmed when users can successfully create, update, and manage their accounts, groups, and containers via the web and mobile apps, and when real-time data for containers is displayed and modifiable. |
| **Sprint 3 Velocity**          | 85 Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Sum of Story Points**        | 83 Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
##### 6.2.3.2. Sprint Backlog 3

#### Technical Stories y Tasks

| **Sprint 3** | **Sprint 3**                                                                 |     |       |             |            |             |        |
|--------------|------------------------------------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **Technical Story** | **Work-Item / Task**                                                     |
| **Id**     | **Title**                                                                | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-31**  | Implement REST endpoints for granting and revoking privileges                | **DIT-331** | Implement mockup profile endpoints | Implement mockup profile endpoints for managing user privileges. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-335** | Implement Input Validation for Login Fields | Implement validation for login fields to ensure proper data input. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-336** | Backend Integration for Login | Implement backend integration for the login process. | 1         | Diego Cancho      | Done    |
| **DIT-29**  | Define roles and permissions in the system                                  | **DIT-506** | Define privilege management in cloud service | Implement privilege management logic in the cloud service. | 1         | Diego Cancho      | Done    |
| **DIT-50**  | Implement group ownership and user association logic                        | **DIT-481** | Validate user and group relationships in database | Validate user-group relationships in the database. | 1         | Diego Cancho      | Done    |
| **DIT-64**  | Implement data processing logic                                             | **DIT-422** | Design Data Processing Flow | Design the data processing flow. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-423** | Implement Data Collection Module | Implement the data collection module. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-424** | Implement Data Transformation and Aggregation Logic | Implement data transformation and aggregation logic. | 1         | Jose Arenas       | Done    |
| **DIT-65**  | Implement data storage logic                                                | **DIT-422** | Design Data Processing Flow | Design the data processing flow. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-423** | Implement Data Collection Module | Implement the data collection module. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-424** | Implement Data Transformation and Aggregation Logic | Implement data transformation and aggregation logic. | 1         | Jose Arenas       | Done    |
| **DIT-62**  | Implement data sending logic                                                | **DIT-429** | Design Data Sending Protocol and Communication Flow | Design the data sending protocol and communication flow. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-430** | Implement Data Transmission Logic for Containers | Implement data transmission logic for containers. | 1         | Jose Arenas       | Done    |
| **DIT-63**  | Implement data receiving logic                                              | **DIT-432** | Design Data Receiving Protocol and Communication Flow | Design the data receiving protocol and communication flow. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-433** | Implement Data Reception and Parsing Logic | Implement data reception and parsing logic. | 1         | Diego Cancho      | Done    |
| **DIT-58**  | Time-series database implementation                                         | **DIT-436** | Implement Data Insertion and Retrieval Logic for Time-Series Data | Implement data insertion and retrieval logic for time-series data. | 1         | Diego Cancho      | Done    |
| **DIT-59**  | Implement real-time data retrieval                                          | **DIT-437** | Implement real-time data retrieval on the embedded system | Implement real-time data retrieval on the embedded system. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-438** | Integrate real-time data transmission with the edge server | Integrate real-time data transmission with the edge server. | 1         | Diego Cancho      | Done    |
| **DIT-57**  | Implement container linkage logic                                           | **DIT-443** | Implement container linkage functionality to allow users to link containers to their accounts | Implement container linkage functionality to allow users to link containers to their accounts. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-445** | Integrate container linkage logic with the backend system to manage associations | Integrate container linkage logic with the backend system to manage associations. | 1         | Diego Cancho      | Done    |
| **DIT-61**  | Threshold-based alerting logic                                              | **DIT-446** | Implement threshold-based alerting logic to monitor container data | Implement threshold-based alerting logic to monitor container data. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-447** | Integrate alert notifications so users receive alerts when thresholds are exceeded | Integrate alert notifications so users receive alerts when thresholds are exceeded. | 1         | Samuel Chamorro   | Done    |
| **DIT-60**  | Data export and formatting logic                                            | **DIT-446** | Implement threshold-based alerting logic to monitor container data | Implement threshold-based alerting logic to monitor container data. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-447** | Integrate alert notifications so users receive alerts when thresholds are exceeded | Integrate alert notifications so users receive alerts when thresholds are exceeded. | 1         | Samuel Chamorro   | Done    |
| **DIT-83**  | Implement threshold and alert configuration                                 | **DIT-440** | Implement threshold configuration so users can set thresholds in templates | Implement threshold configuration so users can set thresholds in templates. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-441** | Implement alert configuration so users can set alerts in templates | Implement alert configuration so users can set alerts in templates. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-442** | Integrate threshold and alert settings with the backend system | Integrate threshold and alert settings with the backend system. | 1         | Diego Cancho      | Done    |
| **DIT-81**  | Implement template creation and storage                                     | **DIT-479** | Create endpoints for Template Management | Create endpoints for managing templates. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-480** | Connect Template endpoints with domain models | Connect template endpoints with domain models. | 1         | Jose Arenas       | Done    |

#### User Stories y Tasks

| **Sprint 3** | **Sprint 3**                                                                 |     |       |             |            |             |        |
|--------------|------------------------------------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **User Story** | **Work-Item / Task**                                                     |
| **Id**     | **Title**                                                                | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-19**   | Create a new user in the web app                                           | **DIT-475** | SignUp Interface in WebApp | Implement sign-up interface for new user registration in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-476** | Integrate backend for register a new user in WebApp | Backend integration for new user registration in the web app. | 1         | Luis Lagos        | Done    |
| **DIT-22**   | Log in to an existing account in the web app                               | **DIT-477** | Login Interface in WebApp | Create login interface for existing users. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-478** | Integrate backend for Login in WebApp | Backend integration for user login in the web app. | 1         | Luis Lagos        | Done    |
| **DIT-100**  | Change a password in the mobile app                                        | **DIT-484** | Implement password change UI in mobile app | Create UI for changing the password in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-503** | Change Password backend integration in mobile app | Backend integration for password change in mobile app. | 1         | Jose Arenas       | Done    |
| **DIT-98**   | Log out of an account in the mobile app                                    | **DIT-504** | Log out in mobile app UI Design | Implement UI design for logging out of an account in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-505** | Log out in mobile app backend integration | Backend integration for logging out in mobile app. | 1         | Jose Arenas       | Done    |
| **DIT-94**   | Create a new user in the mobile app                                        | **DIT-349** | Create Registration Form UI | Create the registration form UI for new users in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-350** | Validate User Input on Registration Form | Implement validation for user input on registration form. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-351** | Implement Backend Integration for User Registration | Implement backend integration for user registration in the mobile app. | 1         | Diego Cancho      | Done    |
| **DIT-97**   | Log in to an existing account in the mobile app                             | **DIT-334** | Create Login Screen UI | Design the login screen UI for mobile app login. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-335** | Implement Input Validation for Login Fields | Implement input validation for login fields in the mobile app. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-336** | Backend Integration for Login | Backend integration for user login in the mobile app. | 1         | Diego Cancho      | Done    |
| **DIT-33**   | Grant privileges to a user in the web app                                  | **DIT-509** | Design interface to grant privileges in the web app | Design the interface for granting privileges in the web app. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-510** | Implement privilege granting in the frontend in the web app | Implement privilege granting functionality in the frontend. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-511** | Integrate with backend to update user privileges in the web app | Integrate frontend with backend to update privileges. | 1         | Samuel Chamorro   | Done    |
| **DIT-34**   | Revoke privileges from a user in the web app                               | **DIT-512** | Design interface to revoke privileges in the web app | Design the interface for revoking privileges in the web app. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-513** | Implement privilege revocation in the frontend in the web app | Implement functionality to revoke privileges from users in the frontend. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-514** | Integrate with backend to update user privileges in the web app | Integrate the revocation process with the backend. | 1         | Samuel Chamorro   | Done    |
| **DIT-104**  | Grant privileges to a user in the mobile app                               | **DIT-357** | UI Design for Privilege Assignment Screen | Design the UI for privilege assignment in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-508** | Backend Integration to grant privileges to a user in mobile app | Integrate backend to allow granting privileges to users in the mobile app. | 1         | Jose Arenas       | Done    |
| **DIT-377**  | View notifications in the web app                                          | **DIT-415** | Implements static notification view | Implement static view for notifications in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-416** | Create filters of notifications | Implement notification filters in the web app. | 1         | Luis Lagos        | Done    |
| **DIT-374**  | Change language in the web app                                             | **DIT-419** | Implements i18n in the web app | Implement i18n (Internationalization) for the web app. | 1         | Jose Arenas       | Done    |
| **DIT-41**   | View account information in the web app                                    | **DIT-388** | Implements static subscription view | Implement static view for subscription in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-418** | Implements static account information view | Implement static view for account information in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-516** | Backend integration for account information in web app | Integrate backend to display account information in the web app. | 1         | Anthony Guerrero  | Done    |
| **DIT-116**  | Create a group in the mobile app                                           | **DIT-340** | Design Facility Creation UI | Design UI for facility creation in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-341** | Implement Validation for Facility Fields | Implement validation for fields in the facility creation form. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-342** | Backend Integration for Group/Facility Creation | Integrate backend for group/facility creation in the mobile app. | 1         | Diego Cancho      | Done    |
| **DIT-51**   | Create a group in the web app                                              | **DIT-373** | Interface design for creating a group in the web app | Design the interface for creating a group in the web app. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-375** | Implementing the group creation form in the web application | Implement group creation form functionality in the web app. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-376** | Integration with the backend for group creation | Integrate backend for creating a group in the web app. | 1         | Diego Cancho      | Done    |
| **DIT-54**   | View a group in the web app                                                | **DIT-382** | Design the interface to display a group in the web application | Design the interface for displaying a group in the web app. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-384** | Integrate with the backend to get the group information in the web app | Integrate backend to retrieve and display group information. | 1         | Diego Cancho      | Done    |
| **DIT-55**   | Register a worker to a group in the web app                                | **DIT-393** | Design the interface to register a worker in a group in the web application | Design UI to register a worker in a group. | 1         | Samuel Chamorro   | Done    |
|            |                                                                          | **DIT-394** | Implement the registration functionality in the web application | Implement functionality to register a worker to a group. | 1         | Diego Cancho      | Done    |
|            |                                                                          | **DIT-395** | Integrate with the backend to add the worker to the group | Integrate backend to register a worker to a group in the web app. | 1         | Diego Cancho      | Done    |
| **DIT-122**  | Link a container to an account in the mobile app                           | **DIT-492** | Link Container to an account UI Design | Design UI for linking a container to an account. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-493** | Backend integration to link a container to an account | Implement backend to link a container to an account in the mobile app. | 1         | Jose Arenas       | Done    |
| **DIT-126**  | View container status in the mobile app                                    | **DIT-494** | View Container Status UI Design in mobile app | Design UI for viewing the status of a container. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-495** | Backend integration for view container status in mobile app | Implement backend to retrieve container status for display in the mobile app. | 1         | Jose Arenas       | Done    |
| **DIT-124**  | Register a container to a group in the mobile app                          | **DIT-346** | Design Container Registration UI | Design the UI for registering a container in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-347** | Implement Input Validation for Container Details | Implement validation for container details on registration. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-348** | Implement Backend Integration for Registering Container | Implement backend integration for registering a container. | 1         | Jose Arenas       | Done    |
| **DIT-131**  | Load a template to a container in the mobile app                           | **DIT-517** | Load Template Design UI for mobile app | Design UI for loading a template into a container. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-518** | Backend integration for load a template to a container in mobile app | Implement backend integration to load templates into containers. | 1         | Jose Arenas       | Done    |
| **DIT-127**  | View container inner conditions in the mobile app                          | **DIT-482** | Implement UI for container view on mobile app | Implement UI for viewing container conditions in the mobile app. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-483** | Connect to container information endpoint for display on mobile app | Connect to backend to fetch container information for display. | 1         | Jose Arenas       | Done    |
| **DIT-130**  | Alter container inner conditions actively in the mobile app                | **DIT-519** | Alter container inner conditions UI Design in mobile app | Design UI to allow users to alter container conditions. | 1         | Jose Arenas       | Done    |
|            |                                                                          | **DIT-520** | Backend integration for alter container inner conditions actively in the mobile app | Implement backend integration to alter container conditions. | 1         | Jose Arenas       | Done    |
| **DIT-521**  | Create a dashboard in the web                                              | **DIT-522** | Implements the dashboard functionality in the web application | Implement dashboard functionality in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-523** | Dashboard interface in WebApp | Design the interface for the dashboard in the web app. | 1         | Luis Lagos        | Done    |
|            |                                                                          | **DIT-524** | Create the dashboard static view in the web application | Implement static view for the dashboard in the web app. | 1         | Luis Lagos        | Done    |
| **DIT-25**   | Change a password in the web app                                           | **DIT-526** | Implements the change password functionality in the web application | Implement change password functionality in the web app. | 1         | Anthony Guerrero  | Done    |
|            |                                                                          | **DIT-527** | Integrate backend for change password in WebApp | Backend integration for password change in the web app. | 1         | Anthony Guerrero  | Done    |
|            |                                                                          | **DIT-528** | Create the dialog static view to change password in the web application | Design a dialog for the change password feature in the web app. | 1         | Anthony Guerrero  | Done    |


##### 6.2.3.3. Development Evidence for Sprint Review.

| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                   | Committed on (Date) |
|----------------------|-----------|----------|--------------------------------------------------|-------------------------------------------------------------|---------------------|
| DittoBox-webapp      | develop   | 1a2bfc5  | fix: Improve component styles and structure | add support for loading status in container service | 04/11/2024          |
| DittoBox-webapp      | develop   | de0ad68  | style: Refactor subscription component layout and improve CSS structure | Refactor subscription component layout and improve CSS structure | 05/11/2024          |
| DittoBox-webapp      | develop   | b0d9990  | refactor: Remove unused db.json file and update facility details component styles and structure | Remove unused db.json file and update facility details component styles and structure | 05/11/2024          |
| DittoBox-mobile      | develop   | da90368  | feat: update base URL to point to production environment | update base URL to point to production environment | 17/11/2024          |
| DittoBox-mobile      | develop   | 19135c8  | feat: make accountId nullable in Profile model and add changePassword method in user service | make accountId nullable in Profile model and add changePassword method in user service | 17/11/2024          |
| DittoBox-mobile      | develop   | 4bc2359  | feat: add query parameters for priority and limit in notification fetch endpoint | add query parameters for priority and limit in notification fetch endpoint | 16/11/2024          |
| DittoBox.API         | develop   | 99760a7  | feat: filter amount of notifications by priority | filter amount of notifications by priority | 18/11/2024          |
| DittoBox.API         | develop   | d6e3876  | feat: add limit and priority filter | add limit and priority filter | 17/11/2024          |
| DittoBox.API         | develop   | 95ea614  | fix: add conditions validation on update metrics | add conditions validation on update metrics | 17/11/2024          |
| DittoBox.Embedded    | develop   | 4d738c4  | docs: update .gitignore and add Wokwi configuration files | update .gitignore and add Wokwi configuration files | 16/11/2024          |
| DittoBox.Embedded    | develop   | e6206fd  | feat: add health monitoring data to REST payload | add health monitoring data to REST payload | 16/11/2024          |
| DittoBox.Embedded    | develop   | 9c31616  | fix: conections to board sp32 fixed | conections to board sp32 fixed | 16/11/2024          |

##### 6.2.3.4. Testing Suite Evidence for Sprint Review.

En esta sección se explica y presenta el conjunto de Unit Tests, Integration Tests y Acceptance Tests automatizados para los Web Services correspondientes a las User Stories especificadas en el Sprint. Estos tests fueron diseñados bajo el enfoque BDD utilizando el lenguaje Gherkin para los archivos .feature y Steps en el lenguaje de programación correspondiente.

#### Unit Tests
Los Unit Tests se enfocan en validar clases y comportamientos específicos dentro de la aplicación. Se han diseñado para asegurar que las unidades individuales de código (métodos y funciones) funcionen correctamente. Los archivos de Unit Testing se encuentran en la rama feature/unit-tests, y el commit relevante para los avances en esta entrega


#### Integration Tests
Los Integration Tests tienen como objetivo validar que los diferentes módulos o servicios de la aplicación se integren y funcionen de manera conjunta como se espera. Estos tests fueron añadidos en la rama feature/integration-tests y su commit se detalla en la tabla

#### Acceptance Tests
Para los Acceptance Tests, se utilizaron User Stories específicas para probar las funcionalidades desde la perspectiva del usuario final. Los archivos .feature contienen los escenarios en lenguaje Gherkin, que validan los criterios de aceptación definidos para cada historia de usuario. Los commits relacionados a estos avances se encuentran en la rama feature/acceptance-tests.


| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                   | Committed on (Date)    |
|----------------------|-----------|----------|--------------------------------------------------|-------------------------------------------------------------|------------------------|
| DittoBox-Testing      | feature/acceptance-tests   | e1de8a | feat: Add acceptance tests for various user features in the web app  |  | 3/11/2024  |
| DittoBox-Testing      | feature/acceptance-tests   | e1de8ae | Merge pull request #1 from DittoBox/feature/acceptance-test  |  | 3/11/2024  |
| DittoBox-Testing      | feature/integration-tests   | d94f677 | feat: added integration test files  |  | 3/11/2024  |
| DittoBox-Testing      | feature/unit-tests   | c84286d1| feat: Add acceptance tests for various user features in the web app  |  | 3/11/2024  |


##### 6.2.3.5. Execution Evidence for Sprint Review.
Para el logro de este proyecto, se realizó el despliegue tanto de la segunda versión de la aplicación web, como de la aplicación móvil las cuales se encuentran en los siguientes enlaces a continuación:

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: https://green-sky-02d70500f.5.azurestaticapps.net/.<br>
<img src="/img/Containers_DittoBox_Web_App_3.png" alt="Image insights 1" width="500"/><br>
<img src="/img/Facilities_DittoBox_Web_App_3.png" alt="Image insights 1" width="500"/><br><br>
<img src="/img/Templates_DittoBox_Web_App_3.png" alt="Image insights 1" width="500"/><br><br>

La aplicación móvil en Flutter ha sido deplegada en Firebase, y se puede acceder a través de la siguiente URL: https://appdistribution.firebase.google.com/pub/i/db6c701af66c0568.<br>
<img src="/img/mobile_templates.jpeg" alt="Image insights 1" width="150"/>
<img src="/img/mobile_workers.jpeg" alt="Image insights 1" width="150"/>
<img src="/img/mobile_containers.jpeg" alt="Image insights 1" width="150"/><br>

Video de las aplicaciones en funcionamiento: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/EcuCFRDa25dJn74pSl-FLP0Bw8urTErBxYyyo6szCQZ8Bw?e=4MgHfh

##### 6.2.3.6. Services Documentation Evidence for Sprint Review.
En este Sprint, hemos implementado los servicios correspondientes al proyecto y los hemos documentado utilizando OpenAPI. Los logros alcanzados incluyen el desarrollo del backend y la documentación de los Endpoints, lo que nos ha permitido integrar funcionalidades completas para nuestra aplicación web.

<img src="/img/webappservice-swagger.png" alt="Image insights 1" width="500"/><br>

La siguiente tabla muestra la relación de los Endpoints documentados, las acciones implementadas, los verbos HTTP utilizados y los enlaces a la documentación correspondiente. Para cada acción, se especifican la sintaxis de llamada, los posibles parámetros, ejemplos de requests/responses y una explicación detallada.


### Account

| Endpoint                                          | Acciones Implementadas                           | Verbo HTTP | Parámetros                                                                                                                                                                                                                                        | Ejemplo de Response                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|---------------------------------------------------|--------------------------------------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/account/{accountId}`                     | Obtener información de una cuenta                | GET        | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                                   | ```json<br>{<br>  "id": 0,<br>  "businessName": "string",<br>  "bussinessId": "string",<br>  "representativeId": 0<br>}```                                                                                                                                                                                                                                                                                                                                                |               |
| `/api/v1/account`                                 | Crear una cuenta                                 | POST       | **Request Body:**<br>{<br>  "businessName": "string",<br>  "businessId": "string",<br>  "representativeId": 0<br>}                                                                                                                               | ```json<br>{<br>  "id": 0,<br>  "businessName": "string",<br>  "bussinessId": "string",<br>  "representativeId": 0<br>}```                                                                                                                                                                                                                                                                                                                                                |               |
| `/api/v1/account`                                 | Actualizar una cuenta                            | PUT        | **Request Body:**<br>{<br>  "accountId": 0,<br>  "representativeId": 0<br>}                                                                                                                                                                       | ```json<br>{<br>  "id": 0,<br>  "businessName": "string",<br>  "bussinessId": "string",<br>  "representativeId": 0<br>}```                                                                                                                                                                                                                                                                                                                                                |               |
| `/api/v1/account/{command}`                       | Eliminar una cuenta                              | DELETE     | **Path Parameters:**<br>- `command` (string)                                                                                                                                                                                                      | **Respuesta:**<br>- Código: `204 No Content`                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |               |
| `/api/v1/account/{accountId}/business`            | Actualizar información del negocio de una cuenta | PUT        | **Path Parameters:**<br>- `accountId` (integer)<br><br>**Request Body:**<br>{<br>  "accountId": 0,<br>  "businessName": "string",<br>  "businessId": "string"<br>}                                                                               | ```json<br>{<br>  "id": 0,<br>  "businessName": "string",<br>  "bussinessId": "string",<br>  "representativeId": 0<br>}```                                                                                                                                                                                                                                                                                                                                                |               |
| `/api/v1/account/{accountId}/subscription-status` | Obtener el estado de suscripción de una cuenta   | POST       | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                                   | ```json<br>{<br>  "accountId": 0,<br>  "currentPlan": "string",<br>  "lowerPlan": "string",<br>  "upperPlan": "string",<br>  "users": {<br>    "current": 0,<br>    "currentLimit": 0,<br>    "lowerPlanLimit": 0,<br>    "upperPlanLimit": 0<br>  },<br>  "containers": {<br>    "current": 0,<br>    "currentLimit": 0,<br>    "lowerPlanLimit": 0,<br>    "upperPlanLimit": 0<br>  },<br>  "facilities": {<br>    "current": 0,<br>    "currentLimit": 0,<br>    "lowerPlanLimit": 0,<br>    "upperPlanLimit": 0<br>  }<br>}``` |               |
| `/api/v1/account/{accountId}/containers`          | Obtener contenedores asociados a una cuenta      | GET        | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                                   | ```json<br>[<br>  {<br>    "id": 0,<br>    "name": "string",<br>    "description": "string",<br>    "groupId": 0,<br>    "temperature": 0,<br>    "humidity": 0,<br>    "oxygen": 0,<br>    "dioxide": 0,<br>    "ethylene": 0,<br>    "ammonia": 0,<br>    "sulfurDioxide": 0,<br>    "minTemp": 0,<br>    "maxTemp": 0,<br>    "minHumidity": 0,<br>    "maxHumidity": 0,<br>    "oxygenMin": 0,<br>    "oxygenMax": 0,<br>    "dioxideMin": 0,<br>    "dioxideMax": 0,<br>    "ethyleneMin": 0,<br>    "ethyleneMax": 0,<br>    "ammoniaMin": 0,<br>    "ammoniaMax": 0,<br>    "sulfurDioxideMin": 0,<br>    "sulfurDioxideMax": 0,<br>    "lastKnownHealthStatus": "string",<br>    "lastKnownContainerStatus": "string",<br>    "lastSync": "2024-11-18T15:26:45.992Z"<br>  }<br>]```                                |               |
| `/api/v1/account/{accountId}/users`               | Obtener usuarios asociados a una cuenta         | GET        | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                                   | ```json<br>[<br>  {<br>    "id": 0,<br>    "firstName": "string",<br>    "lastName": "string",<br>    "accountId": 0,<br>    "groupId": 0,<br>    "userId": 0,<br>    "privileges": [<br>      "string"<br>    ]<br>  }<br>]```                                                                                                                                                                                                                                                                           |               |
| `/api/v1/account/{accountId}/groups`              | Obtener grupos asociados a una cuenta           | GET        | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                                   | ```json<br>[<br>  {<br>    "id": 0,<br>    "name": "string",<br>    "location": {<br>      "id": 0,<br>      "latitude": 0,<br>      "longitude": 0,<br>      "plusCode": "string",<br>      "country": "string",<br>      "state": "string",<br>      "city": "string",<br>      "address": "string"<br>    },<br>    "accountId": 0,<br>    "facilityType": 0,<br>    "containerCount": 0,<br>    "profileCount": 0<br>  }<br>]```                                                                                                                                  |               |

### AlertInstance

| Endpoint                                          | Acciones Implementadas                      | Verbo HTTP | Parámetros                                                                         | Ejemplo de Response |
|---------------------------------------------------|---------------------------------------------|------------|------------------------------------------------------------------------------------|----------------------|
| `/api/v1/alertinstance/{alertInstanceId}/ack`     | Reconocer una instancia de alerta           | POST       | **Path Parameters:**<br>- `alertInstanceId` (string)                               | `{}`                 |               |
| `/api/v1/alertinstance/{alertInstanceId}/dismiss` | Descartar una instancia de alerta           | POST       | **Path Parameters:**<br>- `alertInstanceId` (string)                               | `{}`                 |               |
| `/api/v1/alertinstance`                           | Obtener todas las instancias de alertas     | GET        | No parámetros                                                                      | `[{}]`               |               |

### Container

| Endpoint                                              | Acciones Implementadas                              | Verbo HTTP | Parámetros                                                                                                                                                                                                                                                      | Ejemplo de Response                                                                                                                                                                                                                                                                                                                                                                                                                          |
|-------------------------------------------------------|-----------------------------------------------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/container`                                   | Crear un contenedor                                 | POST       | **Request Body:**<br>{<br>  "deviceId": "string",<br>  "name": "string",<br>  "description": "string",<br>  "accountId": 0,<br>  "groupId": 0<br>}                                                                                                             | ```json<br>{<br>  "id": 0,<br>  "uuid": "string",<br>  "name": "string",<br>  "description": "string"<br>}```                                                                                                                                                                                                                                                                                                                             |               |
| `/api/v1/container`                                   | Obtener todos los contenedores                      | GET        | No parámetros                                                                                                                                                                                                                                                  | ```json<br>[<br>  {<br>    "id": 0,<br>    "name": "string",<br>    "description": "string",<br>    "groupId": 0,<br>    "temperature": 0,<br>    "humidity": 0,<br>    "oxygen": 0,<br>    "dioxide": 0,<br>    "ethylene": 0,<br>    "ammonia": 0,<br>    "sulfurDioxide": 0,<br>    ...<br>  }<br>]```                                                                                                                        |               |
| `/api/v1/container/{ContainerId}`                     | Obtener información de un contenedor específico     | GET        | **Path Parameters:**<br>- `ContainerId` (integer)                                                                                                                                                                                                               | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "description": "string",<br>  "groupId": 0,<br>  "temperature": 0,<br>  "humidity": 0,<br>  "oxygen": 0,<br>  "dioxide": 0,<br>  "ethylene": 0,<br>  "ammonia": 0,<br>  "sulfurDioxide": 0,<br>  ...<br>}```                                                                                                                                                                     |               |
| `/api/v1/container/{containerId}/assign/{templateId}` | Asignar un template a un contenedor                 | POST       | **Path Parameters:**<br>- `containerId` (integer)<br>- `templateId` (integer)                                                                                                                                                                                  | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "description": "string",<br>  "groupId": 0,<br>  "temperature": 0,<br>  "humidity": 0,<br>  ...<br>}```                                                                                                                                                                                                                                                                           |               |
| `/api/v1/container/{ContainerId}/status`              | Obtener el estado de un contenedor                  | GET        | **Path Parameters:**<br>- `ContainerId` (integer)                                                                                                                                                                                                               | ```json<br>{<br>  "lastKnownContainerStatus": "string",<br>  "lastKnownContainerStatusReport": "2024-11-18T15:26:46.026Z"<br>}```                                                                                                                                                                                                                                                                  |               |
| `/api/v1/container/{ContainerId}/health`              | Obtener la salud de un contenedor                   | GET        | **Path Parameters:**<br>- `ContainerId` (integer)                                                                                                                                                                                                               | ```json<br>{<br>  "lastKnownContainerHealth": "string",<br>  "lastKnownContainerHealthReport": "2024-11-18T15:26:46.027Z"<br>}```                                                                                                                                                                                                                                                                  |               |
| `/api/v1/container/{containerId}/status`              | Actualizar el estado de un contenedor               | PUT        | **Path Parameters:**<br>- `containerId` (integer)<br><br>**Request Body:**<br>{<br>  "containerStatus": "string"<br>}                                                                                                                                           | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                                                                                                                         |               |
| `/api/v1/container/{containerId}/health`              | Actualizar la salud de un contenedor                | PUT        | **Path Parameters:**<br>- `containerId` (integer)<br><br>**Request Body:**<br>{<br>  "healthStatus": "string"<br>}                                                                                                                                              | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                                                                                                                         |               |
| `/api/v1/container/{containerId}/metrics`             | Actualizar las métricas de un contenedor            | PUT        | **Path Parameters:**<br>- `containerId` (integer)<br><br>**Request Body:**<br>{<br>  "temperature": 0,<br>  "humidity": 0,<br>  "oxygen": 0,<br>  "dioxide": 0,<br>  "ethylene": 0,<br>  "ammonia": 0,<br>  "sulfurDioxide": 0<br>}                                                                     | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                                                                                                                         |               |
| `/api/v1/container/{containerId}/parameters`          | Actualizar los parámetros de un contenedor          | PUT        | **Path Parameters:**<br>- `containerId` (integer)<br><br>**Request Body:**<br>{<br>  "minTemp": 0,<br>  "maxTemp": 0,<br>  "minHumidity": 0,<br>  "maxHumidity": 0,<br>  "oxygenMin": 0,<br>  "oxygenMax": 0,<br>  "dioxideMin": 0,<br>  "dioxideMax": 0,<br>  ...<br>} | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                                                                                                                         |               |

### Group

| Endpoint                                           | Acciones Implementadas                            | Verbo HTTP | Parámetros                                                                                                                                                                                                                                                      | Ejemplo de Response                                                                                                                                                                                                                                                                                                                           |
|----------------------------------------------------|---------------------------------------------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/group/register-container`                 | Registrar un contenedor en un grupo               | POST       | **Request Body:**<br>{<br>  "uiid": "string"<br>}                                                                                                                                                                                                              | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/containers`               | Obtener contenedores asociados a un grupo         | GET        | **Path Parameters:**<br>- `groupId` (integer)                                                                                                                                                                                                                   | ```json<br>[<br>  {<br>    "id": 0,<br>    "name": "string",<br>    "description": "string",<br>    "groupId": 0,<br>    "temperature": 0,<br>    "humidity": 0,<br>    "oxygen": 0,<br>    ...<br>  }<br>]```                                                                                                                            |               |
| `/api/v1/group/{groupId}/unregister-container`     | Desregistrar un contenedor de un grupo            | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{}                                                                                                                                                                                   | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/transfer-container`       | Transferir un contenedor a otro grupo             | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{}                                                                                                                                                                                   | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/register-user`            | Registrar un usuario en un grupo                  | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{<br>  "email": "string",<br>  "accountId": 0,<br>  "groupId": 0<br>}                                                                                                                | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/unregister-user`          | Desregistrar un usuario de un grupo               | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{}                                                                                                                                                                                   | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/transfer-user`            | Transferir un usuario a otro grupo                | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{}                                                                                                                                                                                   | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}/get-group-location`       | Obtener la ubicación de un grupo                  | POST       | **Path Parameters:**<br>- `groupId` (integer)<br><br>**Request Body:**<br>{}                                                                                                                                                                                   | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                                                           |               |
| `/api/v1/group/{groupId}`                          | Obtener información de un grupo                   | GET        | **Path Parameters:**<br>- `groupId` (integer)                                                                                                                                                                                                                   | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "location": {<br>    "id": 0,<br>    "latitude": 0,<br>    "longitude": 0,<br>    "plusCode": "string",<br>    "country": "string",<br>    "state": "string",<br>    "city": "string",<br>    "address": "string"<br>  },<br>  "accountId": 0,<br>  "facilityType": 0,<br>  "containerCount": 0,<br>  "profileCount": 0<br>}``` |               |
| `/api/v1/group/create-group`                       | Crear un nuevo grupo                              | POST       | **Request Body:**<br>{<br>  "name": "string",<br>  "location": {<br>    "id": 0,<br>    "latitude": 0,<br>    "longitude": 0,<br>    "plusCode": "string",<br>    "country": "string",<br>    "state": "string",<br>    "city": "string",<br>    "address": "string"<br>  },<br>  "accountId": 0,<br>  "facilityType": 0<br>} | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "location": { ... },<br>  "accountId": 0,<br>  "facilityType": 0,<br>  "containerCount": 0,<br>  "profileCount": 0<br>}```                                                                                                                                                                                               |               |

### Notification

| Endpoint                                                | Acciones Implementadas                                 | Verbo HTTP | Parámetros                                                                                                                                                                                                                     | Ejemplo de Response                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------|--------------------------------------------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/notification`                                  | Crear una notificación                                 | POST       | **Request Body:**<br>{<br>  "alertType": 0,<br>  "accountId": 0,<br>  "groupId": 0,<br>  "containerId": 0<br>}                                                                                                                 | ```json<br>{<br>  "id": 0,<br>  "alertType": 1,<br>  "issuedAt": "2024-11-18T15:26:46.062Z",<br>  "accountId": 0,<br>  "groupId": 0,<br>  "containerId": 0<br>}```                                                                                                                                                                                              |               |
| `/api/v1/notification/account/{accountId}`              | Obtener notificaciones de una cuenta                   | GET        | **Path Parameters:**<br>- `accountId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)<br>- `limit` (integer, default: 20)                                                                              | ```json<br>[<br>  {<br>    "id": 0,<br>    "alertType": 1,<br>    "issuedAt": "2024-11-18T15:26:46.068Z",<br>    "accountId": 0,<br>    "groupId": 0,<br>    "containerId": 0<br>  }<br>]```                                                                                                                          |               |
| `/api/v1/notification/group/{groupId}`                  | Obtener notificaciones de un grupo                     | GET        | **Path Parameters:**<br>- `groupId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)<br>- `limit` (integer, default: 20)                                                                                | ```json<br>[<br>  {<br>    "id": 0,<br>    "alertType": 1,<br>    "issuedAt": "2024-11-18T15:26:46.072Z",<br>    "accountId": 0,<br>    "groupId": 0,<br>    "containerId": 0<br>  }<br>]```                                                                                                                          |               |
| `/api/v1/notification/container/{containerId}`          | Obtener notificaciones de un contenedor                | GET        | **Path Parameters:**<br>- `containerId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)<br>- `limit` (integer, default: 20)                                                                            | ```json<br>[<br>  {<br>    "id": 0,<br>    "alertType": 1,<br>    "issuedAt": "2024-11-18T15:26:46.075Z",<br>    "accountId": 0,<br>    "groupId": 0,<br>    "containerId": 0<br>  }<br>]```                                                                                                                          |               |
| `/api/v1/notification/container/{containerId}/latest`   | Obtener la última notificación de un contenedor        | GET        | **Path Parameters:**<br>- `containerId` (integer)                                                                                                                                                                               | ```json<br>{<br>  "id": 0,<br>  "alertType": 1,<br>  "issuedAt": "2024-11-18T15:26:46.077Z",<br>  "accountId": 0,<br>  "groupId": 0,<br>  "containerId": 0<br>}```                                                                                                                                                         |               |
| `/api/v1/notification/group/{groupId}/latest`           | Obtener la última notificación de un grupo             | GET        | **Path Parameters:**<br>- `groupId` (integer)                                                                                                                                                                                   | ```json<br>{<br>  "id": 0,<br>  "alertType": 1,<br>  "issuedAt": "2024-11-18T15:26:46.078Z",<br>  "accountId": 0,<br>  "groupId": 0,<br>  "containerId": 0<br>}```                                                                                                                                                         |               |
| `/api/v1/notification/account/{accountId}/latest`       | Obtener la última notificación de una cuenta           | GET        | **Path Parameters:**<br>- `accountId` (integer)                                                                                                                                                                                 | ```json<br>{<br>  "id": 0,<br>  "alertType": 1,<br>  "issuedAt": "2024-11-18T15:26:46.081Z",<br>  "accountId": 0,<br>  "groupId": 0,<br>  "containerId": 0<br>}```                                                                                                                                                         |               |
| `/api/v1/notification/container/{containerId}/amount`   | Obtener la cantidad de notificaciones de un contenedor | GET        | **Path Parameters:**<br>- `containerId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)                                                                                                                | `0`                                                                                                                                                                                                                                                                                                                                                                                       |               |
| `/api/v1/notification/group/{groupId}/amount`           | Obtener la cantidad de notificaciones de un grupo      | GET        | **Path Parameters:**<br>- `groupId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)                                                                                                                    | `0`                                                                                                                                                                                                                                                                                                                                                                                       |               |
| `/api/v1/notification/account/{accountId}/amount`       | Obtener la cantidad de notificaciones de una cuenta    | GET        | **Path Parameters:**<br>- `accountId` (integer)<br>**Query Parameters:**<br>- `priority` (integer, default: 1)                                                                                                                  | `0`                                                                                                                                                                                                                                                                                                                                                                                       |               |

### Profile

| Endpoint                                      | Acciones Implementadas                | Verbo HTTP | Parámetros                                                                                                                                       | Ejemplo de Response                                                                                                                                                                                                                                              |
|-----------------------------------------------|---------------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/profile/{ProfileId}`                 | Obtener información de un perfil      | GET        | **Path Parameters:**<br>- `ProfileId` (integer)                                                                                                 | ```json<br>{<br>  "id": 0,<br>  "firstName": "string",<br>  "lastName": "string",<br>  "accountId": 0,<br>  "groupId": 0,<br>  "userId": 0,<br>  "privileges": [<br>    "string"<br>  ]<br>}```                                                              |               |
| `/api/v1/profile/update-names`                | Actualizar nombres de un perfil       | PUT        | **Request Body:**<br>{<br>  "profileId": 0,<br>  "firstName": "string",<br>  "lastName": "string"<br>}                                          | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                              |               |
| `/api/v1/profile/grant-privileges`            | Conceder privilegios a un perfil      | POST       | **Request Body:**<br>{<br>  "profileId": 0,<br>  "privilegeId": 0<br>}                                                                          | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                              |               |
| `/api/v1/profile/revoke-privileges`           | Revocar privilegios de un perfil      | PUT        | **Request Body:**<br>{<br>  "profileId": 0,<br>  "privilegeId": 0<br>}                                                                          | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                              |               |

### Subscription

| Endpoint                                    | Acciones Implementadas                          | Verbo HTTP | Parámetros                                                                                                                                       | Ejemplo de Response                                                                                                                                                                                                                                                                                           |
|---------------------------------------------|-------------------------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/subscription/{subscriptionId}`     | Obtener información de una suscripción          | GET        | **Path Parameters:**<br>- `subscriptionId` (integer)                                                                                            | ```json<br>{<br>  "id": 0,<br>  "accountId": 0,<br>  "tier": "string",<br>  "paymentDate": "2024-11-18",<br>  "subscriptionStatusId": 0,<br>  "lastPaidPeriod": "2024-11-18"<br>}```                                                                                                                         |               |
| `/api/v1/subscription/upgrade`              | Mejorar una suscripción                         | POST       | **Request Body:**<br>{<br>  "subscriptionId": 0,<br>  "newTierId": 0<br>}                                                                       | ```json<br>{<br>  "id": 0,<br>  "accountId": 0,<br>  "tier": "string",<br>  "paymentDate": "2024-11-18",<br>  "subscriptionStatusId": 0,<br>  "lastPaidPeriod": "2024-11-18"<br>}```                                                                                                                         |               |
| `/api/v1/subscription/downgrade`            | Degradar una suscripción                        | POST       | **Request Body:**<br>{<br>  "subscriptionId": 0,<br>  "newTierId": 0<br>}                                                                       | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                           |               |
| `/api/v1/subscription/cancel`               | Cancelar una suscripción                        | POST       | **Request Body:**<br>{<br>  "subscriptionId": 0<br>}                                                                                            | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                                                                                                                                                           |               |

### Template

| Endpoint                       | Acciones Implementadas                       | Verbo HTTP | Parámetros                                                                                                                                           | Ejemplo de Response                                                                                                                                                                                                                                                                              |
|--------------------------------|----------------------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/template/{templateId}`| Obtener información de un template           | GET        | **Path Parameters:**<br>- `templateId` (integer)                                                                                                     | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "maxTemperatureThreshold": 0,<br>  "minTemperatureThreshold": 0,<br>  ...<br>  "category": 0<br>}```                                                                                                |               |
| `/api/v1/template`             | Obtener todos los templates                  | GET        | No parámetros                                                                                                                                        | ```json<br>[<br>  {<br>    "id": 0,<br>    "name": "string",<br>    "maxTemperatureThreshold": 0,<br>    "minTemperatureThreshold": 0,<br>    ...<br>    "category": 0<br>  }<br>]```                                                                    |               |
| `/api/v1/template`             | Crear un nuevo template                      | POST       | **Request Body:**<br>{<br>  "name": "string",<br>  "maxTemperatureThreshold": 0,<br>  "minTemperatureThreshold": 0,<br>  ...<br>  "category": 0<br>} | ```json<br>{<br>  "id": 0,<br>  "name": "string",<br>  "maxTemperatureThreshold": 0,<br>  "minTemperatureThreshold": 0,<br>  ...<br>  "category": 0<br>}```                                                                                                |               |

### User

| Endpoint                      | Acciones Implementadas            | Verbo HTTP | Parámetros                                                                                                                                 | Ejemplo de Response                                                                                                                                                        |
|-------------------------------|-----------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/user/{UserId}`       | Obtener información de un usuario | GET        | **Path Parameters:**<br>- `UserId` (integer)                                                                                              | ```json<br>{<br>  "id": 0,<br>  "username": "string",<br>  "email": "string"<br>}```                                                                                       |               |
| `/api/v1/user/{UserId}`       | Eliminar un usuario               | DELETE     | **Path Parameters:**<br>- `UserId` (integer)                                                                                              | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                       |               |
| `/api/v1/user`                | Crear un usuario                  | POST       | **Request Body:**<br>{<br>  "firstName": "string",<br>  "lastName": "string",<br>  "username": "string",<br>  "email": "string",<br>  "password": "string"<br>} | ```json<br>{<br>  "id": 0,<br>  "username": "string",<br>  "email": "string"<br>}```                                                                                       |               |
| `/api/v1/user/change-password`| Cambiar la contraseña de un usuario | PUT        | **Request Body:**<br>{<br>  "userId": 0,<br>  "newPassword": "string"<br>}                                                               | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                       |               |
| `/api/v1/user/login`          | Iniciar sesión de un usuario      | POST       | **Request Body:**<br>{<br>  "email": "string",<br>  "password": "string"<br>}                                                            | **Respuesta:**<br>- Código: `200 OK`                                                                                                                                       |               |



## Repositorio de Web Services

URL del repositorio: https://github.com/DittoBox/DittoBox.API


##### 6.2.3.7. Software Deployment Evidence for Sprint Review.
## Introducción

Durante este Sprint, se realizaron las actividades relacionadas con el **Deployment** de los distintos productos digitales del proyecto DittoBox. Esto incluyó el despliegue de aplicaciones web, servicios backend y landing page. Los pasos abarcaron desde la configuración inicial de los recursos en la nube hasta la automatización de ciertas tareas dentro del flujo de despliegue continuo. Los entornos utilizados abarcaron **Azure**, **Firebase Distribution** y **GitHub Pages**, según las características de cada producto.

<img src="/img/dittobox_azure.jpeg" alt="Image insights 1" width="500"/><br>
<img src="/img/dittobox_master_azure.jpeg" alt="Image insights 1" width="500"/><br>

## Procesos Realizados

1. **Despliegue del Web App y Web App Service en Azure (Entornos de Desarrollo y Producción)**  
   Se implementó la aplicación web en el servicio de **Azure Web App** en ambos entornos: desarrollo (dev) y producción (pro). Esto nos permitió probar y validar las funcionalidades en el entorno de desarrollo antes de implementarlas en producción.
   Para ello, se configuraron los siguientes aspectos:
    - *Creación de cuentas en Azure*: Utilizamos las credenciales proporcionadas por los Microsoft Learn Student Ambassadors de dos miembros del equipo para acceder a los servicios de Azure.
    - *Configuración del Web App Service*: Se crearon los recursos necesarios en Azure para ambos entornos y se automatizó el proceso de despliegue desde el repositorio del proyecto. 
    - *Integración con el backend*: La aplicación web se conectó con el backend mediante los servicios de Azure, asegurando una comunicación eficiente y segura.

    Enlace: https://app-prod-01-dittobox-argeesg8era0c7ex.eastus-01.azurewebsites.net/swagger/index.html

    <img src="/img/dittobox_pro_azure.jpeg" alt="Image insights 1" width="500"/><br> 
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <img src="/img/dittobox_dev_azure.jpeg" alt="Image insights 1" width="500"/><br>
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <br>

<br>

2. **Despliegue del Edge Server en Azure (Entornos de Desarrollo y Producción)**  
   Se implementó la aplicación web en el servicio de **Azure Web App** en ambos entornos: desarrollo (dev) y producción (pro). Esto nos permitió probar y validar las funcionalidades en el entorno de desarrollo antes de implementarlas en producción.
   Para ello, se configuraron los siguientes aspectos:
    - *Creación de cuentas en Azure*: Utilizamos las credenciales proporcionadas por los Microsoft Learn Student Ambassadors de dos miembros del equipo para acceder a los servicios de Azure. 
    - *Configuración del Web App Service*: Se crearon los recursos necesarios en Azure para ambos entornos y se automatizó el proceso de despliegue desde el repositorio del proyecto. 
    - *Integración con el backend*: La aplicación web se conectó con el backend mediante los servicios de Azure, asegurando una comunicación eficiente y segura.

   Enlace: https://edge-prod-01-dittobox-gtayf0aufehwctar.eastus-01.azurewebsites.net/swagger/index.html

   <img src="/img/dittobox_edge_pro_azure.jpeg" alt="Image insights 1" width="500"/><br>
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <img src="/img/dittobox_edge_dev_azure.jpeg" alt="Image insights 1" width="500"/><br>
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <br>

<br>

3. **Distribución de la App Móvil mediante Firebase Distribution**  
   El deployment del aplicativo móvil se realizó utilizando **Firebase Distribution**, una herramienta que facilita la distribución de versiones de prueba a testers o usuarios internos antes de su lanzamiento oficial.
    - Configuración del proyecto en Firebase.
    - Subida de la APK/IPA para distribución interna.
    - Envío de invitaciones a los testers para que accedan a la aplicación y proporcionen retroalimentación.

   Enlace: https://appdistribution.firebase.google.com/pub/i/db6c701af66c0568

    <img src="/img/firebase-app-distribution.png" alt="Image insights 1" width="500"/><br>
   *Panel de Firebase Distribution mostrando la versión más reciente de la app.*
   <br>

<br>

4. **Despliegue de la Landing Page en GitHub Pages**  
   La landing page se desplegó utilizando **GitHub Pages**, aprovechando su simplicidad y la integración con el repositorio del proyecto:
    - Configuración del repositorio y activación de GitHub Pages.
    - Configuración del dominio personalizado y ajustes visuales según los requerimientos del cliente.
    - Verificación de la correcta visualización y responsividad en diferentes dispositivos.

   <img src="/img/github_pages.png" alt="Image insights 1" width="500"/><br>
   *Vista del despliegue en Github Pages.*    

    <img src="/img/github-pages-landing.png" alt="Image insights 1" width="500"/><br>
   *Vista previa de la landing page en un navegador.*

##### 6.2.3.8. Team Collaboration Insights during Sprint.
En este Sprint, el equipo ha trabajado de manera colaborativa en la implementación de los diferentes productos: **Web Services**,  **Aplicación Móvil** y el **Embedded Application**. A continuación, se muestran los datos obtenidos de los analíticos de colaboración y commits en **GitHub**, realizados por los miembros del equipo. Estos datos reflejan la participación activa de cada integrante en las diferentes fases de desarrollo según la distribución de tareas asignadas.

#### Web Services
Insights del Web Services del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/insights_API.png" alt="Image insights 1" width="500"/><br>

#### Embedded Application
Insights del Embedded Application del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/insights_embbeded.png" alt="Image insights 1" width="500"/><br>

#### Web App
Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes

<img src="/img/insights_webapp.png" alt="Image insights 1" width="500"/><br>

#### Mobile App
Insights del Mobile App, donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

<img src="/img/insights_mobile.png" alt="Image insights 1" width="500"/><br>


## 6.3. Validation Interviews.

En esta sección, el equipo  .
<br>

### 6.3.1. Diseño de Entrevistas.

### Preguntas para trabajadores
- ¿Cómo describirías tu experiencia general al usar DittoBox?
- ¿Qué impresiones te llevaste tras interactuar con la aplicación?
- ¿Qué características de DittoBox encontraste más útiles para tu trabajo diario?
- ¿Tuviste dificultades al navegar por la aplicación?
- ¿Hubo alguna función que esperabas encontrar en DittoBox pero no estaba disponible?
- Si pudieras implementar una mejora en DittoBox, ¿cuál sería y por qué?
- Después de usar DittoBox, ¿cómo crees que ha cambiado tu forma de gestionar los insumos alimenticios?
- ¿Qué tan fácil o difícil te resultó introducir y actualizar información sobre los insumos en DittoBox?

### Preguntas para dueños de restaurantes
- Tras usar DittoBox, ¿cómo evaluarías su efectividad en la gestión del inventario de insumos alimenticios?
- Desde que comenzaste a usar DittoBox, ¿has notado cambios en la rentabilidad de tu restaurante relacionados con la gestión de insumos?
- ¿Has experimentado alguna mejora en la calidad del servicio o la satisfacción del cliente desde que implementaste DittoBox?
- ¿Qué información clave sobre los insumos te gustaría tener disponible en tiempo real a través de DittoBox?
- ¿Te gustaría que DittoBox se integrara con otros sistemas que utilizas en tu restaurante?
- En comparación con los métodos tradicionales de gestión de insumos, ¿qué tan satisfecho estás con DittoBox?
- Si pudieras proponer cambios o nuevas características en DittoBox, ¿cuáles serían y por qué crees que son esenciales para mejorar tu experiencia?


### 6.3.2. Registro de Entrevistas.
#### Informe de Entrevista

#### Información del Entrevistado:

**Entrevista 01**

- **Nombre:** Mariela Matinez Carbajal
- **Edad:** 22 años
- **Distrito de Residencia:** Lima, Perú
Evidencia de la reunión:

<p align="center">
  <img src="/img/Entrevista_Mariela.jpg" width="450">
</p>

**Enlace de entrevista:** https://web.microsoftstream.com/video 

* 00:00 minutos hasta 16:01 minutos.

**Resumen de la entrevista:** En esta entrevista, la trabajadora destacó su experiencia positiva con DittoBox, resaltando cómo ha simplificado sus tareas diarias al garantizar el monitoreo y conservación óptima de los insumos. Mencionó que la aplicación es intuitiva y facilita el acceso a datos en tiempo real, lo cual considera crucial para prevenir problemas. Entre las funciones más útiles, mencionó el ajuste automático de temperatura y humedad según el tipo de insumo, aunque sugirió que sería beneficioso incorporar un cálculo automático de la vida útil de los productos y una integración con el inventario general del restaurante. También comentó que el proceso de introducir y actualizar información es sencillo gracias a las plantillas predefinidas. Finalmente, señaló que DittoBox ha mejorado significativamente la gestión de insumos, reduciendo desperdicios y aumentando la confianza en la calidad de los productos almacenados.



**Entrevista 02**

- **Nombre:** Luis Alfredo Pinto Conde
- **Edad:** 30 años
- **Distrito de Residencia:** Arequipa, Perú
- **URL del Video en Microsoft Stream:** https://web.microsoftstream.com/video
- **Screenshot del Cuadro de Video:**

<p align="center">
  <img src="/img/Entrevista de validación-Jose.jpg" width="150">
</p>

**Enlace de entrevista:** 

* 16:01 minutos hasta 37:39 minutos.

**Resumen de la entrevista:** 



##### Resumen de la Entrevista:

##### Descripción General:
Luis Alfredo Pinto Conde, al realizar la prueba de la aplicación, describe su experiencia como positiva, destacando la interfaz bien distribuida y la facilidad para encontrar la información relevante. A través de filtros y las plantillas, puede gestionar contenedores para diferentes tipos de alimentos en un restaurante, lo que le parece muy útil para la organización del espacio y la temperatura.

##### Características del Entrevistado:
- **Personalidad:** Luis es organizado y valora las herramientas tecnológicas que faciliten la gestión de su trabajo diario. Muestra una actitud reflexiva y enfocada en los detalles, lo que le permite identificar aspectos importantes en la aplicación, como la configuración de parámetros y plantillas.
- **Marcas e Influencias:** Aunque no menciona marcas específicas, el uso de la tecnología para la gestión de productos en restaurantes le resulta esencial.
- **Tecnología y Dispositivos:** Luis utiliza dispositivos móviles y aplicaciones para mejorar la eficiencia en su trabajo, como se observa en su interacción con la aplicación.
- **Canales de Interacción:** Principalmente interactúa con aplicaciones móviles y busca sistemas automatizados que optimicen su trabajo.
- **Browser y Dispositivos:** Utiliza aplicaciones móviles para la gestión de contenedores. No se menciona el navegador específicamente, pero se da a entender que usa aplicaciones integradas a su dispositivo móvil.

##### Respuestas a las Preguntas Realizadas:
1. **¿Cómo escribirías tu experiencia general usando la aplicación?**
   - **Respuesta:** Luis comenta que la aplicación está bien distribuida y permite encontrar lo que necesita rápidamente, gracias a los filtros y la información bien organizada sobre los parámetros de los contenedores.

2. **¿Cómo percibes la interacción con la aplicación? ¿Te parece dinámica y fácil de usar?**
   - **Respuesta:** Luis encuentra la aplicación bien diseñada, con acceso rápido a la información y la capacidad de configurar plantillas para diferentes tipos de productos. Se siente cómodo usando la aplicación sin necesidad de mucha explicación.

3. **¿Qué características de la aplicación encontraste más útiles para el trabajo diario?**
   - **Respuesta:** Resalta la utilidad de las plantillas para configurar parámetros y la sincronización automática de los contenedores cada 1-5 minutos. Considera que estos beneficios mejoran la capacidad de monitorear los productos de manera eficiente.

4. **¿Tuviste dificultades usando la aplicación?**
   - **Respuesta:** No experimentó dificultades significativas en el uso de la aplicación, pero mencionó que le gustaría que la notificación de parámetros erróneos fuera más automatizada, sugiriendo un sistema que ajuste los parámetros de los contenedores automáticamente.

5. **¿Hay alguna mejora que te gustaría implementar?**
   - **Respuesta:** Luis sugiere agregar un sistema más automatizado que permita la corrección de parámetros de temperatura sin intervención manual, facilitando la operación de los contenedores sin necesidad de tener la aplicación abierta constantemente.

6. **¿Cómo crees que cambiará tu forma de gestionar los alimentos en un restaurante?**
   - **Respuesta:** La aplicación le permitirá gestionar los tipos de alimentos más eficazmente, tener un mejor control sobre los parámetros de los contenedores y optimizar el tiempo de caducidad de los productos.

#### Arquetipos Construidos:
Con base en las respuestas obtenidas de esta entrevista, se podrán construir arquetipos de usuarios con características como:
   - **Arquetipo Principal:** Usuario con enfoque práctico en la gestión de alimentos, interesado en sistemas automatizados de monitoreo para optimizar tiempos y parámetros.
   - **Características Demográficas y Tecnológicas:** Hombre, edad media, profesional en la industria alimentaria, uso frecuente de aplicaciones móviles, busca eficiencia y automatización en su trabajo diario.



### 6.3.3. Evaluaciones según Heurísticas.
# Evaluación de User Experience según Heurísticas

## Información General

- **CARRERA**: Ingeniería de Software
- **CURSO**: Desarrollo de Soluciones IoT
- **SECCIÓN**: WV71
- **PROFESORES**: Todos
- **AUDITOR**: Grupo Ditto
- **CLIENTE(S)**: Luis Alfredo Pinto Conde
- **FECHA DE AUDITORÍA**: 18 de noviembre de 2024
---

## SITE o APP A EVALUAR:
**Aplicación DittoBox**

## TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
1. Registro de un usuario nuevo
2. Asociar de un contendor
3. Búsqueda de un Template
4. Ver Lista de Workers y privilegios
5. Cambio de contraseñas
6. Agregar un trabajador a un Facilty o Group
7. Creación de un nuevo Facility o Group
8. Gestión de contenedores (Monitoreo de parámetros como temperatura y humedad)
9. Etc.

No están incluidas en esta versión de la evaluación las siguientes tareas:
1. Subscripción a un plan de pago
2. Edicion de perfiles de usuario
3. Creación	de un nuevo Template
4. Notificaciones push
5. Etc.

## ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| **Nivel** | **Descripción**                                                                                   |
|-----------|--------------------------------------------------------------------------------------------------|
| 1         | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2         | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja para resolverlo en el siguiente lanzamiento. |
| 3         | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que se corrija y se le debe asignar una prioridad alta. |
| 4         | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

## TABLA RESUMEN:

| **#** | **Problema (¿Cuál es?)**                                                            | **Escala de severidad** | **Heurística / Principio violado**                               |
|-------|------------------------------------------------------------------------------------|-------------------------|-----------------------------------------------------------------|
| 1     | Hay algunos lugares donde no se traduce completamente al cambiar entre inglés y español  | 2                       | Usability: Consistencia y estándares                            |
| 2     | Los templates son limitados, deberían agregarse más y ser más específicos para los diferentes productos a almacenarse en los contenedores | 3                       | Usability: Flexibilidad y eficiencia de uso                     |
| 3     | No se puede recuperar contraseña en la pestaña de login                             | 4                       | Usability: Prevención de errores                                |
| 4     | Añadir más mensajes de confirmación cuando se realiza una acción o se completa una tarea | 2                       | Usability: Visibilidad del estado del sistema                   |

## DESCRIPCIÓN DE PROBLEMAS:
---

### PROBLEMA #1: Hay algunos lugares donde no se traduce completamente al cambiar entre inglés y español

- **Severidad**: 2
- **Heurística violada**: Usabilidad - Consistencia y estándares

#### Problema:
Luis observó que algunos elementos de la interfaz no se traducen correctamente cuando se cambia entre inglés y español, lo que puede generar confusión para los usuarios que dependen de la traducción completa de la aplicación.

#### Recomendación:
Asegurarse de que todos los textos y elementos interactivos estén completamente traducidos en ambas versiones del idioma. Realizar pruebas de localización para garantizar la consistencia en todos los idiomas soportados.

---
### PROBLEMA #2: Los templates son limitados, deberían agregarse más y ser más específicos para los diferentes productos a almacenarse en los contenedores

- **Severidad**: 3
- **Heurística violada**: Usabilidad - Flexibilidad y eficiencia de uso

#### Problema:
Luis mencionó que los templates disponibles son limitados y no cubren una variedad suficiente de productos que se almacenan en los contenedores. Esto obliga al usuario a realizar configuraciones adicionales o utilizar templates genéricos que no siempre son apropiados.

#### Recomendación:
Agregar más templates específicos y detallados para diferentes tipos de productos que se almacenan en los contenedores. Esto mejoraría la eficiencia del usuario al permitirle configurar rápidamente según el tipo de producto.

---

### PROBLEMA #3: No se puede recuperar contraseña en la pestaña de login

- **Severidad**: 4
- **Heurística violada**: Usabilidad - Prevención de errores

#### Problema:
Luis señaló que no hay una opción para recuperar la contraseña en la pestaña de login, lo que puede bloquear a los usuarios que olviden su contraseña, ya que no tienen una forma sencilla de recuperarla.

#### Recomendación:
Incluir un enlace de "Olvidé mi contraseña" en la pantalla de login, que permita a los usuarios restablecer su contraseña de manera fácil y rápida. Esto es esencial para la accesibilidad y la continuidad del uso de la aplicación.

---
### PROBLEMA #4: Añadir más mensajes de confirmación cuando se realiza una acción o se completa una tarea

- **Severidad**: 2
- **Heurística violada**: Usabilidad - Visibilidad del estado del sistema

#### Problema:
Luis comentó que al realizar ciertas acciones, como agregar un contenedor o modificar parámetros, no siempre recibe un mensaje de confirmación, lo que deja a los usuarios inciertos sobre si la acción se realizó correctamente.

#### Recomendación:
Incluir mensajes de confirmación claros y visibles para todas las acciones relevantes, como la adición de contenedores, cambios en los parámetros y finalización de tareas. Esto asegurará que los usuarios siempre sepan el estado de sus acciones y tareas dentro de la aplicación.

---
### PROBLEMA #X: Titulo del problema

- **Severidad**: X
- **Heurística violada**: XXXXXXXXXXXXXXXXXXXXXXXXXXXX

#### Problema:
Ejemplo de problema:
En algunos casos, Luis hizo clic en un botón de "Ver más", pero no había contenido adicional al que acceder, lo que genera frustración en los usuarios.

#### Recomendación:
Ejemplo de Recomendación:
Retirar el botón "Ver más" si no se proporciona contenido adicional o asegurarse de que siempre haya algo relevante que mostrar al usuario al hacer clic en este botón.

---





## 6.4. Video About-The-Product.

Presentamos nuestro Video About-The-Product, diseñado específicamente para los visitantes de nuestra Landing Page y para los usuarios interesados en nuestras aplicaciones. Este video ofrece una visión general atractiva de nuestro modelo de negocio y destaca las características principales de nuestros productos de software. Su objetivo es ayudar a los usuarios a entender cómo DittoBox puede satisfacer sus necesidades de almacenamiento de manera eficiente y segura.

El video adopta un tono amigable e informativo, coherente con nuestro compromiso de innovación y satisfacción del cliente. Muestra la facilidad de uso de nuestras aplicaciones, la integración fluida entre plataformas y las avanzadas características de seguridad que nos distinguen en el mercado.

Como parte de nuestro enfoque centrado en el usuario, el video incluye un testimonio positivo de una de nuestras primeras usuarias, """, quien participó en las entrevistas de validación. Ella comparte su experiencia con DittoBox, enfatizando cómo ha simplificado la gestión de sus datos y mejorado su productividad:
<br><br>
A continuación, se muestra una captura de pantalla del video:
<br><br>
<img src="/img/Video_About-The-Product.jpg" alt="Image insights 1" width="500"/><br><br>
Puedes ver el Video About-The-Product en los siguientes enlaces:<br><br>
Microsoft Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/EZ76cZiCLaJMsOLDzJYqWMQB2o3rMjejgpfcvMheiSfXVQ?e=b9GmNo <br>
YouTube: 

