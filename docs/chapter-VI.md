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

- **Organización**:  Organización creada en GitHub donde están todos los repositorios que comprenden a la solución desarrollada
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
## 6.2. Landing Page, Services & Applications Implementation.
### 6.2.1. Sprint 1
##### 6.2.1.1. Sprint Planning 1.
##### 6.2.1.2. Sprint Backlog 1.
##### 6.2.1.3. Development Evidence for Sprint Review.
##### 6.2.1.4. Testing Suite Evidence for Sprint Review.
##### 6.2.1.5. Execution Evidence for Sprint Review.
##### 6.2.1.6. Services Documentation Evidence for Sprint Review.
##### 6.2.1.7. Software Deployment Evidence for Sprint Review.
##### 6.2.1.8. Team Collaboration Insights during Sprint.