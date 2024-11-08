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
| Sprint 1 Goal              | Desarrollar el landing page de DittoBox. El landing page debe estar desplegado y con las secciones diseñadas implementadas adecuadamente. Debe cumplir con los requisitos de accesibilidad y responsive design. |
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

| Sprint #                   | Sprint 2                                                                                                                                                                                                        |
| -------------------------- |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint Planning Background |
| Date                       | 2024-09-28                                                                                                                                                                                                      |
| Location                   | Universidad Peruana de Ciencias Aplicadas, Campus Villa                                                                                                                                                         |
| Prepared by                | Cancho Coila, Diego Fabian                                                                                                                                                                                      |
| Attendees                  | Cancho Coila, Diego Fabian / Arenas Conde, José Anthony / Lagos Aguilar, Luis Eduardo / Guerrero Castillo, Anthony Jeandet / Chamorro Torres, Samuel Rolando                                                    |
| Sprint Goal & User Stories |
| Sprint 1 Goal              | Desarrollar el landing page de DittoBox. El landing page debe estar desplegado y con las secciones diseñadas implementadas adecuadamente. Debe cumplir con los requisitos de accesibilidad y responsive design. |
| Sprint 1 Velocity          | 20 Story Points                                                                                                                                                                                                 |
| Sum of Story Points        | 20 Story Points                                                                                                                                                                                                 |

##### 6.2.2.2. Sprint Backlog 2

| Sprint #   | Sprint 2                                          |     |       |             |            |             |        |
| ---------- |---------------------------------------------------| --- | ----- | ----------- | ---------- | ----------- | ------ |
| User story | Work-Item / Task                                  |
| Id         | Title                                             | Id  | Title  | Description | Estimation | Assigned to | Status |
| DIT-317    | Add information about the service in landing page |     |       |             |            |             |        |
|            |                                                   | WIT-1 | Design service info section | Create and design the section to display the service information on the landing page. | 2         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-2 | Write service content | Write the text to explain the platform's features and benefits. | 1         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-3 | Implement service info section | Add and implement the service section into the landing page. | 3         | Samuel Chamorro    | Completed |
| DIT-318    | Contact with sales team in landing page           |     |       |             |            |             |        |
|            |                                                   | WIT-4 | Design contact form layout | Create a simple and user-friendly contact form layout. | 2         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-5 | Develop form functionality | Implement the backend for the contact form. | 3         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-6 | Test form and integration | Test the contact form for usability and integrate it into the landing page. | 2         | Samuel Chamorro    | Completed |
| DIT-319    | Customers' review in landing page                 |     |       |             |            |             |        |
|            |                                                   | WIT-7 | Collect testimonials | Gather customer reviews and success stories to feature. | 2         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-8 | Design testimonials section | Design a visually appealing section for displaying testimonials. | 3         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-9 | Implement testimonials section | Add and integrate the testimonials section into the landing page. | 3         | Samuel Chamorro    | Completed |
| DIT-320    | Prices and tiers information on landing page      |     |       |             |            |             |        |
|            |                                                   | WIT-10 | Design pricing table | Create a layout to display pricing tiers and details. | 3         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-11 | Write plan descriptions | Write descriptions for each pricing plan. | 2         | Samuel Chamorro    | Completed |
|            |                                                   | WIT-12 | Implement pricing table | Develop and integrate the pricing table on the landing page. | 4         | Samuel Chamorro    | Completed |


##### 6.2.2.3. Development Evidence for Sprint Review.

| Repository           | Branch             | Commit Id | Commit Message                                               | Commit Message Body                                         | Committed on (Date)    |
|----------------------|--------------------|-----------|--------------------------------------------------------------|-------------------------------------------------------------|------------------------|
| DittoBox-WebApp      | hotfix-fakeapi      | 4ecdbb2   | fix: update fakeapi url                                       | Merged pull request #3 from DittoBox/hotfix-fakeapi          | 27/09/2024             |
| DittoBox-WebApp      | main(#3)            | 085e98a   | fix: update fakeapi url                                       | Updating fakeapi url                                         | 27/09/2024             |
| DittoBox-WebApp      | develop             | 8d95475   | Merge pull request #2 from DittoBox/develop                   | Merged develop branch                                        | 27/09/2024             |
| DittoBox-WebApp      | main(#1)            | 244b710   | feat: updating container-item component                       | Updating container-item component                            | 27/09/2024             |
| DittoBox-static      | main               | cd201ec   | Update call to action                                         | Updated call to action section on the static page.           | 27/09/2024             |
| DittoBox-static      | main(#1)           | 752878e   | Merge pull request #1 from DittoBox/fix-names                 | Remove unnecessary license and readme files, update page title. | 27/09/2024             |
| DittoBox-static      | main(#1)           | a0b948a   | fix: Remove unnecessary license and readme files, and update page title | Removed license, readme files and updated page title.       | 27/09/2024             |

##### 6.2.2.4. Testing Suite Evidence for Sprint Review.
No se han realzado archivos de testing, debido a que el producto realizado no posee las funcionalidades necesarias para ser probada con herramientas de testing

##### 6.2.2.5. Execution Evidence for Sprint Review.
Para el logro de este proyecto, se realizó el despliegue tanto de la Landing Page, como la primera versión de la aplicación web, las cuales se encuentran en los siguientes enlaces a continuación:

La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: [DittoBox Landing Page](https://dittobox.github.io/DittoBox-static/).


##### 6.2.2.6. Services Documentation Evidence for Sprint Review.
Aún no se han implementado servicios para nuestro proyecto, pero tenemos desplegado un Fake-API con JSON usando la herramienta My JSON Server, donde desplegamos un json, para simular los datos y que se muestren en la aplicación web

[My JSON Server](https://my-json-server.typicode.com/DittoBox/DittoboxFakeApi/containers).

##### 6.2.2.7. Software Deployment Evidence for Sprint Review.
La aplicación web en Angular ha sido deplegada en Azure Static Web Apps, y se puede acceder a través de la siguiente URL: [DittoBox Web App](https://black-dune-093481d10.5.azurestaticapps.net/).
El landing page ha sido desplegado en GitHub Pages, y se puede acceder a través de la siguiente URL: [DittoBox Landing Page](https://dittobox.github.io/DittoBox-static/).

##### 6.2.2.8. Team Collaboration Insights during Sprint.
Para esta sección del documentos, añadimos los insights realizados durante el sprint, tanto de la realización de la aplicación web, como el landing page:

Insight del Static Web App, donde se muestran los commits realizados en el ultimo mes del repositorio de
![Image insights 1](/img/insights%201.png).


Insights del Reporte o informe del proyecto donde se muestran la cantidad realizada de commits por los integrantes del grupo el últime mes
![Image insights 2](/img/Insights%202.png).

Insights del Web App, donde se muestran los commits realizados al repositorio en el ultimo mes
![Image insights 3](/img/insight%203.png).


## 6.3. Validation Interviews.

En esta sección, el equipo  .
<br>

### 6.3.1. Diseño de Entrevistas.

En esta sección, el equipo  .

### 6.3.2. Registro de Entrevistas.

En esta sección se especifican   .

### 6.3.3. Evaluaciones según Heurísticas.

En esta sección, el equipo  .


## 6.4. Video About-The-Product.

En esta sección, el equipo  .
<br>
