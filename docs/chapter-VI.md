# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.

En esta sección, el equipo establece las decisiones y convenciones que permitirán mantener la consistencia durante todo el ciclo de vida del desarrollo de software para DittoBox. La configuración abarca la gestión del código fuente, la configuración del entorno de desarrollo y el despliegue de las aplicaciones. Estas decisiones garantizan una colaboración eficiente, asegurando que todos los miembros del equipo trabajen de manera coherente y organizada.
<br>

### 6.1.1. Software Development Environment Configuration.

En esta sección se especifican y describen las herramientas y productos de software que los miembros del equipo deben utilizar durante el ciclo de vida del desarrollo de **DittoBox**, para garantizar la colaboración eficiente y la consistencia en el proyecto. Estas herramientas cubren todas las áreas clave, incluyendo la gestión del proyecto, el diseño UX/UI, el desarrollo, las pruebas y el despliegue.

#### Project Management

- **Herramienta**: Jira
- **Propósito**: Gestionar tareas, sprints y backlog del proyecto. Se utilizará para la planificación y seguimiento del progreso del equipo.
- **Ruta de acceso**: SaaS. [Jira](https://www.atlassian.com/software/jira)

#### UX/UI Design

- **Herramienta**: Figma
- **Propósito**: Diseño colaborativo de las interfaces de usuario para la aplicación web y móvil. Permite al equipo diseñar, prototipar y colaborar en tiempo real en el diseño UX/UI de **DittoBox**.
- **Ruta de acceso**: SaaS. [Figma](https://www.figma.com/)

- **Herramienta adicional**: UXPressia
- **Propósito**: Mapeo de la experiencia del usuario y creación de journey maps. Utilizado para comprender y planificar las interacciones del usuario con el sistema, mejorando así la experiencia de usuario.
- **Ruta de acceso**: SaaS. [UXPressia](https://uxpressia.com/)

#### Software Development

##### Landing Page Development

- **Herramientas**: HTML5 y CSS
- **Propósito**: Desarrollo de la página de aterrizaje de DittoBox, donde se presentará la propuesta de valor del producto.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: [Visual Studio Code](https://code.visualstudio.com/)

##### Web Application Development

- **Herramienta**: Angular
- **Propósito**: Desarrollo del frontend para la aplicación web de DittoBox. Angular se utiliza para crear una interfaz de usuario interactiva y modular, permitiendo una experiencia fluida para los usuarios web.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: [Visual Studio Code](https://code.visualstudio.com/)

##### Mobile Application Development

- **Herramienta**: Flutter
- **Propósito**: Desarrollo de la aplicación móvil multiplataforma de DittoBox (iOS y Android). Flutter permite crear una aplicación nativa con un solo código base, lo que mejora la eficiencia en el desarrollo y el mantenimiento.
- **Editor de código**: Visual Studio Code (VSC)
- **Ruta de descarga**: [Visual Studio Code](https://code.visualstudio.com/)

##### App Services (Backend Development)

- **Lenguaje**: C# con ASP.NET y .NET
- **Propósito**: Desarrollo de los servicios de backend de DittoBox. Estos servicios gestionan la lógica del negocio, la comunicación con la base de datos, y la integración con el sistema de IoT.
- **Editor de código**: Visual Studio Community
- **Ruta de descarga**: [Visual Studio Community](https://visualstudio.microsoft.com/es/vs/community/)

#### Software Testing

- **Herramienta**: Selenium
- **Propósito**: Automatización de las pruebas de la aplicación web y móvil de DittoBox. Selenium se utilizará para crear scripts de prueba que validen la funcionalidad de la aplicación en diferentes navegadores y dispositivos.
- **Ruta de descarga**: [Selenium](https://www.selenium.dev/downloads/)

#### Software Deployment

- **Herramienta**: Azure
- **Propósito**: Despliegue y administración de los servicios backend, frontend web y la aplicación móvil en entornos de producción. Azure proporciona una infraestructura escalable para garantizar la alta disponibilidad y el rendimiento de DittoBox.
- **Ruta de acceso**: SaaS. [Microsoft Azure](https://azure.microsoft.com/)

#### Software Documentation

- **Herramientas**: GitHub y Markdown
- **Propósito**: La documentación técnica del proyecto DittoBox se gestiona en un repositorio privado de GitHub. Todo el equipo tiene acceso a este repositorio para colaborar en la redacción, edición y revisión de la documentación. Utilizamos Markdown como el formato de escritura, lo que permite una estructuración clara y consistente de la información técnica.

  - **Repositorio GitHub**: El informe y la documentación técnica de DittoBox están disponibles en un repositorio dedicado en GitHub.
  - **Formato**: Markdown para mantener la legibilidad, la facilidad de edición y el control de versiones.
  - **Ruta de acceso**: SaaS. [GitHub](https://github.com/)

#### Source Code Management

- **Herramienta**: GitHub
- **Propósito**: Plataforma de control de versiones utilizada para gestionar el código fuente de todos los componentes de DittoBox, incluyendo el backend, frontend y la aplicación móvil. GitHub permitirá colaborar eficientemente, realizar seguimientos de cambios y gestionar el ciclo de vida del código.
- **Ruta de acceso**: SaaS. [GitHub](https://github.com/)

### 6.1.2. Source Code Management.

En esta sección se detalla cómo el equipo de **DittoBox** gestionará el código fuente utilizando **GitHub** como plataforma y sistema de control de versiones. A continuación, se describen los medios y el esquema de organización que se implementarán para el seguimiento de modificaciones. El equipo aplicará el workflow **GitFlow** para organizar las ramas de desarrollo y mantendrá un seguimiento estricto del versionado y los commits.

#### Repositorios en GitHub

Cada uno de los componentes del proyecto DittoBox tendrá un repositorio en **GitHub**, donde se gestionará tanto el código fuente como las pruebas asociadas (pruebas unitarias e integradas). Los repositorios principales incluyen:

- **Organización**: Organización creada en GitHub donde están todos los repositorios que comprenden a la solución desarrollada

  - **URL de la organización**: [GitHub - Organización DittoBoc](https://github.com/DittoBox)

- **Reporte**: Reposutorio donde se encuentra el reporte del trabajo desarrollado, usando Markdown.

  - **URL del repositorio**: [GitHub - Reporte o informe](https://github.com/DittoBox/FinalProjectReport)

- **Landing Page**: Landing Page, desarrollada en HTML5 y CSS.
  - **URL del repositorio**: [GitHub - Landing Page](https://github.com/DittoBox/DittoBox-static)
- **Web Services (Backend)**: Servicios backend desarrollados en C# con ASP.NET y .NET, junto con las pruebas unitarias y de integración.

  - **URL del repositorio**: [GitHub - Web Services](https://github.com/DittoBox/DittoBox.API)

- **Frontend Web Application**: Aplicación web desarrollada en Angular.

  - **URL del repositorio**: [GitHub - Web Application](https://github.com/DittoBox/DittoBox-WebApp)

- **Mobile Application**: Aplicación móvil multiplataforma desarrollada en Flutter.
  - **URL del repositorio**: [GitHub - Mobile App](https://github.com/DittoBox/DittoBox-Mobile)

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

- **Estilo**: Seguir la [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html).
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

- **Estilo**: Seguir la [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html).
- Usar `let` y `const` en lugar de `var`.
- Priorizar el uso de funciones flecha y mantener los métodos pequeños y modulares.

**Ejemplo en JavaScript:**

```javascript
const calculateTotal = (price, quantity) => {
  return price * quantity;
};
```

#### TypeScript

- **Estilo**: Seguir la [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html).
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

- **Estilo**: Seguir la [Effective Dart Guide](https://dart.dev/guides/language/effective-dart).
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

- **Estilo**: Seguir la [Microsoft C# Style Guide](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/).
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

- **Estilo**: Seguir las [Gherkin Conventions for Readable Specifications](https://cucumber.io/docs/gherkin/) para escribir casos de prueba legibles y bien estructurados.

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

- [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
- [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html)
- [Microsoft C# Style Guide](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/)
- [Gherkin Syntax](https://cucumber.io/docs/gherkin/)

### 6.1.4. Software Deployment Configuration.

La configuración de despliegue de software para la solución propuesta por DittoBox depende del componente específico que se esté desplegando. A continuación, se detallan las configuraciones de despliegue para cada uno de los componentes principales del proyecto.

#### Landing Page

El landing page se desplegará como una página web estática, haciendo uso de [Azure Static Web Apps](https://azure.microsoft.com/products/app-service/static/). Este servicio de Azure permite alojar aplicaciones web estáticas de forma sencilla y escalable, proporcionando un entorno seguro y de alto rendimiento para el landing page de DittoBox.

##### Proceso de Despliegue:

- **Clonar Repositorio**: Clonar el repositorio de la landing page desde GitHub.
- **Configuración de Azure Static Web Apps**: Crear una instancia de Azure Static Web Apps y configurarla para que apunte al repositorio clonado.
- **Despliegue Automático**: Configurar el despliegue automático desde GitHub, de modo que cada cambio en el repositorio se refleje automáticamente en el landing page. La rama principal (`main`) se utilizará para el despliegue para garantizar la estabilidad.

#### Web Application

La aplicación web de DittoBox, desarrollada en Angular, se desplegará en [Azure App Service](https://azure.microsoft.com/services/app-service/). Este servicio de Azure permite alojar aplicaciones web y APIs de forma escalable y segura, con opciones de escalado automático y alta disponibilidad.

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

Los servicios backend de DittoBox, desarrollados en C# con ASP.NET y .NET, se desplegarán en [Azure App Service](https://azure.microsoft.com/services/app-service/). Estos servicios se alojarán en un entorno de producción seguro y escalable, con opciones de escalado automático y alta disponibilidad para garantizar el rendimiento y la disponibilidad de la aplicación.

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

### 6.2.1. Sprint 1

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

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: [DittoBox Landing Page](https://dittobox.github.io/DittoBox-static/).


##### 6.2.1.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

[My JSON Server](https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers).

##### 6.2.1.7. Software Deployment Evidence for Sprint Review.
La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: [DittoBox Landing Page](https://dittobox.github.io/DittoBox-static/).

##### 6.2.1.8. Team Collaboration Insights during Sprint.
Para esta sección del documentos, añadimos los insights realizados durante el sprint, tanto de la realización de la aplicación web, como el landing page:

Insight del Static Web App, donde se muestran los commits realizados en el ultimo mes del repositorio de
![Image insights 1](/img/insights%201.png).


Insights del Reporte o informe del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes
![Image insights 2](/img/Insights%202.png).

Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes
![Image insights 3](/img/insight%203.png).



### 6.2.2. Sprint 2

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

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
![Image insights 1](/img/Containers_DittoBox_Web_App.png). ![Image insights 1](/img/Templates_DittoBox_Web_App.png). <br>
La aplicación móvil en Flutter ha sido deplegada en Firebase, y se puede acceder a través de la siguiente URL: [DittoBox Mobile App](https://appdistribution.firebase.google.com/pub/i/db6c701af66c0568).
![Image insights 1](/img/Templates_DittoBox_Mobile_App.png). ![Image insights 1](/img/Facilities_DittoBox_Mobile_App.png). <br>
Video de las aplicaciones en funcionamiento: [DittoBox Video Execution](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/EcuCFRDa25dJn74pSl-FLP0Bw8urTErBxYyyo6szCQZ8Bw?e=4MgHfh)

##### 6.2.2.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

[My JSON Server](https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers).

##### 6.2.2.7. Software Deployment Evidence for Sprint Review.
## Introducción

Durante este Sprint, se realizaron las actividades relacionadas con el **Deployment** de los distintos productos digitales del proyecto DittoBox. Esto incluyó el despliegue de aplicaciones web, servicios backend y landing page. Los pasos abarcaron desde la configuración inicial de los recursos en la nube hasta la automatización de ciertas tareas dentro del flujo de despliegue continuo. Los entornos utilizados abarcaron **Azure**, **Firebase Distribution** y **GitHub Pages**, según las características de cada producto.

## Procesos Realizados

1. **Despliegue del Web App y Web App Service en Azure**  
   Se implementó la aplicación web en el servicio de **Azure Web App**. Para ello, se configuraron los siguientes aspectos:
   - Creación de la cuenta en Azure a través de las credenciales proporcionadas por los **Microsoft Learn Student Ambassadors** de dos miembros del equipo.
   - Configuración del Web App Service, incluyendo la creación de los recursos necesarios y la automatización del proceso de despliegue desde el repositorio del proyecto.
   - Integración de la aplicación web con el backend mediante servicios de Azure.
  
   ![Web Service App](/img/webappservice-swagger.png)  
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <br>

   ![Web App](/img/Containers_DittoBox_Web_App.png)  
   *Despliegue exitoso en el panel de Azure Web App*

<br>

1. **Distribución de la App Móvil mediante Firebase Distribution**  
   El deployment del aplicativo móvil se realizó utilizando **Firebase Distribution**, una herramienta que facilita la distribución de versiones de prueba a testers o usuarios internos antes de su lanzamiento oficial.
   - Configuración del proyecto en Firebase.
   - Subida de la APK/IPA para distribución interna.
   - Envío de invitaciones a los testers para que accedan a la aplicación y proporcionen retroalimentación.

   ![Firebase App Distribution](/img/firebase-app-distribution.png)  
   *Panel de Firebase Distribution mostrando la versión más reciente de la app.*

2. **Despliegue de la Landing Page en GitHub Pages**  
   La landing page se desplegó utilizando **GitHub Pages**, aprovechando su simplicidad y la integración con el repositorio del proyecto:
   - Configuración del repositorio y activación de GitHub Pages.
   - Configuración del dominio personalizado y ajustes visuales según los requerimientos del cliente.
   - Verificación de la correcta visualización y responsividad en diferentes dispositivos.

   ![Captura de pantalla 3](/img/github-pages-landing.png)  
   *Vista previa de la landing page en un navegador.*

##### 6.2.2.8. Team Collaboration Insights during Sprint.
En este Sprint, el equipo ha trabajado de manera colaborativa en la implementación de los diferentes productos: **Web Services**,  **Aplicación Móvil** y el **Embedded Application**. A continuación, se muestran los datos obtenidos de los analíticos de colaboración y commits en **GitHub**, realizados por los miembros del equipo. Estos datos reflejan la participación activa de cada integrante en las diferentes fases de desarrollo según la distribución de tareas asignadas.


#### Web Services
Insights del Web Services del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![Web Services insights 2](/img/webservices-insight-tb2.png).

#### Embedded Application
Insights del Embedded Application del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![Embedded App insights 2](/img/embedded-insights-tb2.png).


#### Web App
Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes

![Web App insights 3](/img/web-app-insights-tb2.png).

#### Mobile App
Insights del Mobile App, donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![App  insights 2](/img/app-insights-tb2.png).


### 6.2.3. Sprint 3

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
| **Sprint 3 Velocity**          | 75 Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Sum of Story Points**        | 70 Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
##### 6.2.3.2. Sprint Backlog 3

#### Technical Stories y Tasks

| Sprint # | Sprint 3                                                                 |     |       |             |            |             |        |
|----------|--------------------------------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **Technical Story** | **Work-Item / Task**                                                     |
| **Id**     | **Title**                                                                | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-12**   | Create REST endpoint for user management                                 | **DIT-331** | Implement mockup profile endpoints | Implement the mockup of profile endpoints for user management.    | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-324** | Implement mockup user endpoints  | Implement mockup user-related endpoints.                          | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-325** | Connect user endpoints to domain model | Connect the user endpoints to the domain model for user management. | 1         | Diego Cancho       | Done    |
| **DIT-13**   | Create REST endpoint for account management                              | **DIT-327** | Implement mockup account endpoints | Create and implement mockup endpoints for account management.     | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-326** | Define account/subscription bounded context model | Define the bounded context model for accounts and subscriptions. | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-421** | Create account usage report endpoint | Create an endpoint to generate account usage reports.             | 1         | Diego Cancho       | Done    |
| **DIT-49**   | Implement REST endpoints for group management                            | **DIT-451** | Implement Create Group Endpoint  | Implement services to create group endpoints.                     | 1         | Jose Conde         | Done    |
|            |                                                                          | **DIT-452** | Implement Group Endpoint Commands Handler | Implement command handlers and interfaces for group endpoint creation. | 1         | Jose Conde         | Done    |
|            |                                                                          | **DIT-453** | Create Group Repositories and Controller | Create repositories, resources, and controller for group endpoint management. | 1         | Jose Conde         | Done    |
|            |                                                                          | **DIT-454** | Implement Get Group Endpoint Services | Implement services to retrieve group endpoints.                   | 1         | Jose Conde         | Done    |
|            |                                                                          | **DIT-455** | Implement Get Group Query Handler | Implement query handlers and interfaces to retrieve group information. | 1         | Jose Conde         | Done    |
|            |                                                                          | **DIT-456** | Implement Get Group Repositories and Controller | Implement repositories, resources, and controller for retrieving group details. | 1         | Jose Conde         | Done    |
| **DIT-91**   | Set up CI/CD pipelines for automated testing, deployment, and monitoring | **DIT-321** | Configure public GitHub repositories | Set up and configure public GitHub repositories for CI/CD pipelines. | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-322** | Create Azure services and connect workflows | Set up Azure services and integrate with CI/CD workflows.        | 1         | Diego Cancho       | Done    |
| **DIT-92**   | Implement email service integration                                      | **DIT-410** | Configure Azure Communication Services | Configure Azure Communication Services for email integration.     | 1         | Diego Cancho       | Done    |
|            |                                                                          | **DIT-411** | Define and connect email service to cloud server | Define and establish the email service connection to the cloud server. | 1         | Diego Cancho       | Done    |
| **DIT-471**  | Implement REST endpoints for container management                        | **DIT-459** | Implement mockup container endpoints | Implement mockup container-related endpoints for management.      | 1         | Anthony Guerrero   | Done    |
|            |                                                                          | **DIT-458** | Define container bounded context model | Define the bounded context model for container management.        | 1         | Anthony Guerrero   | Done    |
|            |                                                                          | **DIT-461** | Connect container endpoints to domain model | Connect the container endpoints to the domain model.              | 1         | Anthony Guerrero   | Done    |


#### User Stories y Tasks

| Sprint # | Sprint 3                                         |     |       |             |            |             |        |
|----------|--------------------------------------------------|-----|-------|-------------|------------|-------------|--------|
| **User Story** | **Work-Item / Task**                             |
| **Id**     | **Title**                                        | **Id**  | **Title** | **Description**                                                    | **Estimation (points)** | **Assigned to**     | **Status**     |
| **DIT-109**  | Revoke subscription privileges in the mobile app | **DIT-467** | Design Revoke Privileges Subscription UI | Design the UI for revoking subscription privileges in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-108**  | Grant subscription privileges in the mobile app  | **DIT-465** | Design Privileges Subscription UI | Design the UI for granting subscription privileges in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-105**  | Revoke privileges from a user in the mobile app  | **DIT-467** | Design Revoke Privileges UI      | Design the UI for revoking privileges from a user in the mobile app. | 1         | Jose Conde         | Done    |
| **DIT-110**  | View account information in the mobile app       | **DIT-457** | User Account Information UI      | Design and implement the user account information UI for the mobile app. | 1         | Luis Lagos         | Done    |
| **DIT-377**  | View notifications in the web app                | **DIT-416** | Create filters for notifications | Create filters to manage and display notifications in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                  | **DIT-447** | Integrate alert notifications    | Integrate alert notifications so users receive alerts when thresholds are exceeded. | 1         | Samuel Chamorro    | Done    |
| **DIT-374**  | Change language in the web app                   | **DIT-419** | Implement i18n in the web app    | Implement internationalization (i18n) for multiple language support in the web app. | 1         | Luis Lagos         | Done    |
| **DIT-42**   | Update account information in the web app        | **DIT-420** | Create dialog for account updates | Create a dialog to allow users to update their account information in the web app. | 1         | Luis Lagos         | Done    |
| **DIT-41**   | View account information in the web app          | **DIT-388** | Implement static subscription view | Implement a static view to display subscription details in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                  | **DIT-418** | Implement static account information view | Implement a static view for account information in the web app.  | 1         | Luis Lagos         | Done    |
| **DIT-45**   | Upgrade a subscription in the web app            | **DIT-381** | Design subscription view         | Design the subscription view for the web app.                     | 1         | Luis Lagos         | Done    |
| **DIT-46**   | Downgrade a subscription in the web app          | **DIT-381** | Design subscription view         | Design the subscription view for downgrading a subscription in the web app. | 1         | Luis Lagos         | Done    |
|            |                                                  | **DIT-396** | Create warning modal for downgrade | Create a modal warning users about the consequences of downgrading their subscription. | 1         | Diego Cancho       | Done    |
| **DIT-116**  | Create a group in the mobile app                 | **DIT-340** | Design Group Creation UI         | Design the UI for group creation in the mobile app.               | 1         | Jose Conde         | Done    |
|            |                                                  | **DIT-341** | Implement Validation for Group Fields | Implement input validation for the group creation fields.         | 1         | Diego Cancho       | Done    |
|            |                                                  | **DIT-342** | Backend Integration for Group Creation | Integrate backend services for group creation in the mobile app.  | 1         | Diego Cancho       | Done    |
| **DIT-119**  | View a group in the mobile app                   | **DIT-472** | View Group Details UI            | Design and implement the group details UI in the mobile app.      | 1         | Jose Conde         | Done    |
| **DIT-120**  | Register a worker to a group in the mobile app   | **DIT-352** | UI Design for Worker Registration | Design the UI for the worker registration screen in the mobile app. | 1         | Jose Conde         | Done    |
|            |                                                  | **DIT-353** | Backend Integration for Worker Registration | Integrate backend services for worker registration in the mobile app. | 1         | Samuel Chamorro    | Done    |
|            |                                                  | **DIT-354** | User Feedback and Confirmation Screen | Design the feedback and confirmation screens for worker registration. | 1         | Anthony Guerrero   | Done    |
| **DIT-70**   | View container status in the web app             | **DIT-359** | Design Container Status UI       | Design the UI for viewing the status of containers in the web app. | 1         | Anthony Guerrero   | Done    |
|            |                                                  | **DIT-360** | Implement Container Status Component | Implement the component for displaying container details in the web app. | 1         | Anthony Guerrero   | Done    |
|            |                                                  | **DIT-361** | Backend Integration for Container Status | Integrate backend services for retrieving container status information. | 1         | Anthony Guerrero   | Done    |
| **DIT-71**   | View container inner conditions in the web app   | **DIT-362** | Extend Container Details Component | Extend the container details component to display inner conditions. | 1         | Luis Lagos         | Done    |
|            |                                                  | **DIT-363** | Backend Integration for Inner Conditions | Integrate backend services for retrieving inner container conditions. | 1         | Luis Lagos         | Done    |
|            |                                                  | **DIT-371** | Implement State Management for Container Conditions | Implement state management for input fields and toggles to control container conditions. | 1         | Anthony Guerrero   | Done    |
|            |                                                  | **DIT-372** | Backend Integration for Updating Container Conditions | Integrate backend services to update container inner conditions.  | 1         | Luis Lagos         | Done    |

##### 6.2.3.3. Development Evidence for Sprint Review.

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

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
![Image insights 1](/img/Containers_DittoBox_Web_App.png). ![Image insights 1](/img/Templates_DittoBox_Web_App.png). <br>
La aplicación móvil en Flutter ha sido deplegada en Firebase, y se puede acceder a través de la siguiente URL: [DittoBox Mobile App](https://appdistribution.firebase.google.com/pub/i/db6c701af66c0568).
![Image insights 1](/img/Templates_DittoBox_Mobile_App.png). ![Image insights 1](/img/Facilities_DittoBox_Mobile_App.png). <br>
Video de las aplicaciones en funcionamiento: [DittoBox Video Execution](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/EcuCFRDa25dJn74pSl-FLP0Bw8urTErBxYyyo6szCQZ8Bw?e=4MgHfh)

##### 6.2.3.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

[My JSON Server](https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers).

##### 6.2.3.7. Software Deployment Evidence for Sprint Review.
## Introducción

Durante este Sprint, se realizaron las actividades relacionadas con el **Deployment** de los distintos productos digitales del proyecto DittoBox. Esto incluyó el despliegue de aplicaciones web, servicios backend y landing page. Los pasos abarcaron desde la configuración inicial de los recursos en la nube hasta la automatización de ciertas tareas dentro del flujo de despliegue continuo. Los entornos utilizados abarcaron **Azure**, **Firebase Distribution** y **GitHub Pages**, según las características de cada producto.

## Procesos Realizados

1. **Despliegue del Web App y Web App Service en Azure**  
   Se implementó la aplicación web en el servicio de **Azure Web App**. Para ello, se configuraron los siguientes aspectos:
    - Creación de la cuenta en Azure a través de las credenciales proporcionadas por los **Microsoft Learn Student Ambassadors** de dos miembros del equipo.
    - Configuración del Web App Service, incluyendo la creación de los recursos necesarios y la automatización del proceso de despliegue desde el repositorio del proyecto.
    - Integración de la aplicación web con el backend mediante servicios de Azure.

   ![Web Service App](/img/webappservice-swagger.png)  
   *Despliegue exitoso en el panel de Azure Web App Service.*

   <br>

   ![Web App](/img/Containers_DittoBox_Web_App.png)  
   *Despliegue exitoso en el panel de Azure Web App*

<br>

1. **Distribución de la App Móvil mediante Firebase Distribution**  
   El deployment del aplicativo móvil se realizó utilizando **Firebase Distribution**, una herramienta que facilita la distribución de versiones de prueba a testers o usuarios internos antes de su lanzamiento oficial.
    - Configuración del proyecto en Firebase.
    - Subida de la APK/IPA para distribución interna.
    - Envío de invitaciones a los testers para que accedan a la aplicación y proporcionen retroalimentación.

   ![Firebase App Distribution](/img/firebase-app-distribution.png)  
   *Panel de Firebase Distribution mostrando la versión más reciente de la app.*

2. **Despliegue de la Landing Page en GitHub Pages**  
   La landing page se desplegó utilizando **GitHub Pages**, aprovechando su simplicidad y la integración con el repositorio del proyecto:
    - Configuración del repositorio y activación de GitHub Pages.
    - Configuración del dominio personalizado y ajustes visuales según los requerimientos del cliente.
    - Verificación de la correcta visualización y responsividad en diferentes dispositivos.

   ![Captura de pantalla 3](/img/github-pages-landing.png)  
   *Vista previa de la landing page en un navegador.*

##### 6.2.3.8. Team Collaboration Insights during Sprint.
En este Sprint, el equipo ha trabajado de manera colaborativa en la implementación de los diferentes productos: **Web Services**,  **Aplicación Móvil** y el **Embedded Application**. A continuación, se muestran los datos obtenidos de los analíticos de colaboración y commits en **GitHub**, realizados por los miembros del equipo. Estos datos reflejan la participación activa de cada integrante en las diferentes fases de desarrollo según la distribución de tareas asignadas.


#### Web Services
Insights del Web Services del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![Web Services insights 2](/img/webservices-insight-tb2.png).

#### Embedded Application
Insights del Embedded Application del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![Embedded App insights 2](/img/embedded-insights-tb2.png).


#### Web App
Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes

![Web App insights 3](/img/web-app-insights-tb2.png).

#### Mobile App
Insights del Mobile App, donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes

![App  insights 2](/img/app-insights-tb2.png).


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

En esta sección se especifican   .

### 6.3.3. Evaluaciones según Heurísticas.

En esta sección, el equipo  .


## 6.4. Video About-The-Product.

En esta sección, el equipo introduce y describe el contenido del video About-the-Product, diseñado especialmente para los visitantes de la Landing Page y los usuarios de las aplicaciones. Este video tiene como objetivo presentar el modelo de negocio y las principales características de los productos de software, ayudando a los usuarios a comprender mejor cómo la solución respalda sus necesidades y los procesos que realiza.
<br>
![Image insights 1](/img/Video_About-The-Product.jpg).<br>
Ver el vídeo About-The-Product, a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
