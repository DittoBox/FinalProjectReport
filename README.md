<center>

# Universidad Peruana De Ciencas Aplicadas
## Desarrollo de Soluciones IOT

</center>

<p align = "center"> <img src = "https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img> </p>

<center>

# **Informe TB1**
## **Ditto - Dittobox**
## **Sección: WV71**  
## Profesor: Angel Augusto Velasquez Nuñez


</center>

## **Integrantes:**

*  **Diego Fabian Cancho Coila**
*  **José Anthony Arenas Conde**
*  **Samuel Rolando Chamorro Torres**
*  **Luis Eduardo Lagos Aguilar**
*  **Anthony Jeandet Guerrero Castillo**
-----

<center>

**Agosto 2024**

</center>

---

## Registro de Versiones Del Informe

| **Version** | **Fecha** | **Autor**                                                                               | **Descripcion de modificacion**                                                                 |
|-------------|-----------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| 0.1         | 22/08/24  | Cancho Coila Diego        | Descripcion Profile Start Up             |
| 0.2         | 07/09/24  | Arenas Conde José Anthony | Lean UX Process, EventStorming, Entrevista, Bounded Contexts          |
| 0.3         | 07/09/24  | Lagos Aguilar, Luis Eduardo        | C4 Model, Entrevista    |
| 0.4         | 07/09/24  | Guerrero Castillo, Anthony Jeandet       | Startup Profile, Solution Profile, entrevista, Impact Mapping, Context Mapping           |




## Project Report Collaboration Insights

**Link del repositorio-Informe:** [https://github.com/DittoBox/FinalProjectReport](https://github.com/DittoBox/FinalProjectReport)

**Link de los repositorios de la oraganización:** [https://github.com/orgs/DittoBox/repositories](https://github.com/orgs/DittoBox/repositories)

### **Reporte de colaboración de la entrega del TB1:**

En esta entrega, nuestra meta principal fue la creación de nuestro start-up y los bounded context. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Mural, Jira, UXPressia y Miro. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo Ditto:




En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo en para realizar el TB1.




En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.



Estos gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

------


# Contenido
## Capitulo I: Introducción
### [1.1. Startup Profile](/docs//chapter-I.md/#11-startup-profile)
* #### [1.1.1. Descripcion de la Startup](/docs/chapter-I.md/#111-descripción-de-la-startup)
* #### [1.1.2. Perfiles de Integrantes del equipo](/docs/chapter-I.md/#112-perfiles-de-integrantes-del-equipo)
### [1.2. Solution Profile](/docs/chapter-I.md/#12-solution-profile)
* #### [1.2.1. Antecedentes y problematica](/docs/chapter-I.md/#121-antecedentes-y-problemática)
* #### [1.2.2. Lean UX Process](/docs/chapter-I.md/#122-lean-ux-process)
    * ##### [1.2.2.1. Lean UX Problem Statements](/docs/chapter-I.md/#1221-lean-ux-problem-statements)
    * ##### [1.2.2.2. Lean UX Assumptions](/docs/chapter-I.md/#1222-lean-ux-assumptions)
    * ##### [1.2.2.3. Lean UX Hypothesis Statements](/docs/chapter-I.md/#1223-lean-ux-hypothesis-statements)
    * ##### [1.2.2.4. Lean UX Canvas](/docs/chapter-I.md/#1224-lean-ux-canvas)
### [1.3. Segmentos Objetivos](/docs/chapter-I.md/#13-segmentos-objetivos)

## Capitulo II: Requirements Elicitation & Analysis
### [2.1. Competidores](/docs/chapter-IV.md/#21-competidores)
* #### [2.1.1. Analisis Competitivo](/docs/chapter-IV#211-análisis-competitivo)
* #### [2.1.2. Estrategias y tacticas frente a competidores](/docs/chapter-IV#212-estrategias-y-tácticas-frente-a-competidores)
### [2.2. Entrevistas](/docs/chapter-IV#22-entrevistas)
* #### [2.2.1. Diseño de entrevistas](/docs/chapter-IV#221-diseño-de-entrevistas)
* #### [2.2.2. Registro de entrevistas](/docs/chapter-IV#222-registro-de-entrevistas)
* #### [2.2.3. Analisis de entrevistas ](/docs/chapter-IV#223-análisis-de-entrevistas)
### [2.3. Needfinding](/docs/chapter-IV#23-needfinding)
* #### [2.3.1. User Personas](/docs/chapter-IV#231-user-persona)
* #### [2.3.2. User Task Matrix](/docs/chapter-IV#232-user-task-matrix)
* #### [2.3.3. User Journey Mapping](/docs/chapter-IV#233-user-journey-mapping)
* #### [2.3.4. Empathy Mapping](/docs/chapter-IV#234-empathy-mapping)
* #### [2.3.5. As-is Scenario Mapping](/docs/chapter-IV#235-as-is-scenario-mapping) 
### [2.4. Ubiquitous Language]()

## Capitulo III: Requirements Specification
### [3.1. To-Be Scenario Mapping](/docs/chapter-IV#31-to-be-scenario-mapping)
### [3.2. User Stories ](/docs/chapter-IV#32-user-stories)
### [3.3. Impact Mapping](/docs/chapter-IV#33-impact-mapping)
### [3.4. Product Backlog](/docs/chapter-IV#34-product-backlog)

## Capítulo IV: Solution Software Design
### [4.1. Sgtrategic-Level Domain-Driven Desin](/docs/chapter-IV#31-to-be-scenario-mapping)
* #### [4.1.1. EventStorming](/docs/chapter-IV#231-user-persona)
   * ##### [4.1.1.1. Candidate Context Discovery](#41-strategic-level-domain-driven-design)
   * ##### [4.1.1.2. Domain Message Flows Modeling](#41-strategic-level-domain-driven-design)  
   * ##### [4.1.1.3. Bounded Context Canvases](#41-strategic-level-domain-driven-design)
* #### [4.1.2. Context Mapping.](/docs/chapter-IV#231-user-persona)
* #### [4.1.3. Software Architecture](/docs/chapter-IV#231-user-persona)
   * ##### [4.1.3.1. Software Architecture System Landscape Diagram.](#41-strategic-level-domain-driven-design)   
   * ##### [4.1.3.2. Software Architecture Context Level Diagrams.](#41-strategic-level-domain-driven-design)
   * ##### [4.1.3.3. Software Architecture Container Level Diagrams.](#41-strategic-level-domain-driven-design)
   * ##### [4.1.3.3. Software Architecture Deployment Diagrams.](#41-strategic-level-domain-driven-design)
### [4.2. Tactical-Level Domain-Driven Design](/docs/chapter-IV#31-to-be-scenario-mapping)
* #### [4.2.1. Bounded Context: <Bounded Context Name>](/docs/chapter-IV#231-user-persona)
    * ##### [4.2.1.1. Domain Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.1.2. Interface Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.1.3. Application Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.1.4. Infrastructure Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.1.6.2. Bounded Context Database Design Diagram.](#41-strategic-level-domain-driven-design)
* #### [4.2.2. Bounded Context: <Bounded Context Name>](/docs/chapter-IV#231-user-persona)
    * ##### [4.2.2.1. Domain Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.2.2. Interface Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.2.3. Application Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.2.4. Infrastructure Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.2.6.2. Bounded Context Database Design Diagram.](#41-strategic-level-domain-driven-design)
* #### [4.2.3. Bounded Context: <Bounded Context Name>](/docs/chapter-IV#231-user-persona)
    * ##### [4.2.3.1. Domain Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.3.2. Interface Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.3.3. Application Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.3.4. Infrastructure Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.3.6.2. Bounded Context Database Design Diagram.](#41-strategic-level-domain-driven-design)
* #### [4.2.4. Bounded Context: <Bounded Context Name>](/docs/chapter-IV#231-user-persona)
    * ##### [4.2.4.1. Domain Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.4.2. Interface Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.4.3. Application Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.4.4. Infrastructure Layer.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.](#41-strategic-level-domain-driven-design)
    * ##### [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams.](#41-strategic-level-domain-driven-design)
        * ##### [4.2.4.6.2. Bounded Context Database Design Diagram.](#41-strategic-level-domain-driven-design)

------

## Student Outcome

| **Criterio Específico** | **Acciones Realizadas** | **Conclusiones**                                                                               |
|-------------------------|--------------------------|-----------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | Chamorro Torres Samuel Rolando<br><br>TB1<br>Se desarrolló el Needfinding para identificar necesidades y optimizar la experiencia del usuario. También se crearon los Bounded Context Canvases para definir y contextualizar los aspectos críticos del sistema en el monitoreo. <br><br>Anthony Guerrero Castillo<br>TB1<br>Se elbaró la descripción de la startup, información y análisis de los competidores, parte del Requirement Elicitation, entrevistas y partes del Solution Software Design <br><br> Arenas Conde, José Anthony <br> TB1 <br> <br> Se desarrollaron diversos puntos de manera conjunta, identificando diversos aspectos de la propuesta de software a través de reuniones presenciales que fue la principal actividad que contribuyó al desarrollo del proyecto. <br><br> Cancho Coila, Diego Fabian<br>TB1<br>Se realizó la definición de requirements, user stories y product backlog, tomando en cuenta las necesidades de los usuarios y las funcionalidades esperadas del sistema por parte de los mismos.| |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | Chamorro Torres Samuel Rolando<br><br>TB1<br>Se fomentó un entorno colaborativo estableciendo metas claras y planificando tareas con el equipo para asegurar un desarrollo eficaz del sistema. <br><br>Anthony Guerrero Castillo<br>TB1<br>Se realizaron reuniones para crear una misma idea entre todos los participantes, y de esta forma avanzar más rápido y seguro  <br><br> Arenas Conde, José Anthony <br> TB1 <br> <br> Se usaron herramientas que facilitaron un entorno colaborativo y comunicación constante entre los miembros del equipo, para realizar una buena solución de software<br><br>Cancho Coila, Diego Fabian<br><br>TB1<br>Como grupo, se procuró incentivar la participación y oportunidad de comunicar, proponer y defender ideas propias, buscando tanto un consenso en los objetivos planteados como en el desarrollo de cada uno de los integrantes como líderes capaces. <br><br>| |

### Anexos:

| **Seccion**    | **Características del video** | **Sobre el contenido** | Integracion y entrega |
|----------------|-----------|------------------------|-----------------------|
| Exposicion Tb1 |Cantidad de videos: 1 <br>Nomenclatura: <br >upc-pre-202402-si572-WV71-Ditto-expo-tb1 <br>Formato: .mp4 <br>Duración: 33 minutos            | Presentación de la tb1 |https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211d744_upc_edu_pe/ESYno-fhaBBJiIjt70tGougBmdAW0Y2RzB4bNjpfh9d35w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=ROpuWg                        |


## Bibliografía 
* Bashir, A., Hassan, S. A., Ali, A., & Kazmi, S. J. H. (2021). "IoT based intelligent food storage system." Journal of Food Engineering, 300, 110563. DOI: 10.1016/j.jfoodeng.2021.110563
* BBVA Spark. (2022, agosto 22). Innovación y tecnología contra el desperdicio de alimentos - BBVA. BBVA Spark [OI]. https://www.bbvaspark.com/contenido/es/noticias/se-acabo-tirar-comida-innovacion-y-tecnologia-contra-el-desperdicio-de-alimentos/
* Bureau of Labor Statistics. (2023). Occupational outlook handbook: Food and beverage serving and related workers. U.S. Department of Labor. Recuperado de https://www.bls.gov/ooh/food-preparation-and-serving/food-and-beverage-serving-and-related-workers.htm
* De Cover, A. (2024, julio 1). Cómo Mejorar la Experiencia de los Clientes en Restaurantes a través de la Tecnología - Blog CoverManager. CoverManager. https://blog.covermanager.com/como-mejorar-la-experiencia-de-los-clientes-en-restaurantes-a-traves-de-la-tecnologia/
* FAO (2019). "The State of Food and Agriculture 2019: Moving Forward on Food Loss and Waste Reduction." Recuperado de https://www.fao.org/family-farming/detail/en/c/1245425/
* IBISWorld. (2023). Restaurants in the US - Market size and growth. Recuperado de https://www.ibisworld.com/united-states/market-research-reports/restaurants-industry/
* Statista. (2023). Revenue of the restaurant industry in Latin America from 2016 to 2023. Recuperado de https://www.statista.com/statistics/1126198/latin-america-restaurant-industry-revenue/
* Tech, R. T. F. (2024, enero 17). Los desafíos de la conservación de los alimentos en Latinoamérica. THE FOOD TECH - Medio De Noticias Líder En La Industria De Alimentos Y Bebidas. https://thefoodtech.com/industria-alimentaria-hoy/los-desafios-de-la-conservacion-de-los-alimentos-en-latinoamerica/ 
* Vicedo, J. M. (2024, setiembre 5). Prospectiva: 7 grandes avances en tecnología alimentaria. AINIA. https://www.ainia.com/ainia-news/prospectiva-7-grandes-avances-tecnologia-alimentaria/