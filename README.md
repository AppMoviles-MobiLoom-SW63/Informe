<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br><img src="https://www.upc.edu.pe/static/img/logo_upc_red.png"></img><br>
    <br>
    <strong>Ingeniería de Software - 2024-02</strong><br>
    <br>
    <strong>CC238 - Aplicaciones para Dispositivos Móviles - SW63</strong><br>  
    <br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br> <strong>INFORME DE TRABAJO 1 - TB1</strong> 
</p>
<p align="center">
    <strong>Startup: MobiLoom</strong><br>
    <strong>Producto:  DiligenceTech</strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Miembro</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Criollo De La Cruz, Diego Anderson</td>
            <td>U202219639</td>
        </tr>
        <tr>
            <td>Herrera González, Luis Eduardo</td>
            <td>U202218227</td>
        </tr>
        <tr>
            <td>Morales Calderón, Hernan Emilio</td>
            <td>U202216263</td>
        </tr>
        <tr>
            <td>Valle Zuta, Abel Andrés</td>
            <td>U202210297</td>
        </tr>
    </table>
</div>
<br>

# Registro de Versiones del Informe

<div align="center">

| Versión |   Fecha    | Autor | Descripción de modificación | 
|:-------:|:----------:|:-----:|:----------------------------| 
|TB1| 20/08/2024 |Criollo De La Cruz, Diego Anderson| Realicé el capítulo II y mis entrevistas|
|TB1| 20/08/2024 |Herrera González, Luis Eduardo| Completé el capítulo I y mis entrevistas|
|TB1| 20/08/2024 |Morales Calderón, Hernan Emilio| Llevé a cabo el capítulo I y mis entrevistas|
|TB1| 20/08/2024 |Valle Zuta, Abel Andrés| Desarrollé a cabo el capítulo II y mis entrevistas|

</div>

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Objetivos SMART](#objetivos-smart)
### [Capítulo I: Presentación](#capítulo-i-presentacion)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmento-objetivo)

### [Capítulo II: Needfinding](#capitulo-ii-needfinding)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. To-Be Scenario Mapping](#241-to-be-scenario-mapping)
    - [2.4.2. User Stories](#242-user-stories)
    - [2.4.3. Impact Mapping](#243-impact-mapping)
    - [2.4.4. Product Backlog](#244-product-backlog)

### [Capítulo III: Arquitectura](#capitulo-iii-arquitectura)
- [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
        - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
        - [3.1.2.1. Organization Systems](#3121-organization-systems)
        - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
        - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
        - [3.1.2.4. Searching Systems](#3124-searching-systems)
        - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
        - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
        - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-ux-ui-design)
        - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
        - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
        - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
        - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
        - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [3.2. Architecture Overview](#32-architecture-overview)
    - [3.2.1. Domain-Driven Software Architecture](#321-domain-driven-software-architecture)
        - [3.2.1.1. Software Architecture Context Level Diagram](#3211-software-architecture-context-level-diagram)
        - [3.2.1.2. Software Architecture Container Level Diagram](#3212-software-architecture-context-level-diagram)
        - [3.2.1.3. Software Architecture Components Diagram](#3213-software-architecture-components-diagram)
    - [3.2.2. Software Object-Oriented Design](#322-software-object-oriented-design)
        - [3.2.2.1. Class Diagrams](#3221-class-diagrams)
        - [3.2.2.2. Class Dictionary](#3222-class-dictionary)
        - [3.2.2.3. Database Design](#3223-database-design)
        - [3.2.2.4. Database Diagram](#3224-database-diagram)

### [Capítulo IV: Backend Product Implementation & Validation](#capitulo-iv-backend-product-implementation-validation)
- [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)



# Student Outcome

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| Actualiza conceptos <br> y conocimientos <br> necesarios para su <br> desarrollo profesional <br> y en especial para su <br> proyecto en soluciones <br> de software. | **TB1:**<br><br>Criollo De La Cruz, Diego Anderson<br><br>Herrera González, Luis Eduardo<br><br>Morales Calderón, Hernan Emilio<br><br>Valle Zuta, Abel Andrés<br> | **TB1:** |
| Reconoce la <br> necesidad del <br> aprendizaje permanente <br> para el desempeño <br> profesional y el desarrollo <br> de proyectos en <br> soluciones de software. | **TB1:**<br><br>Criollo De La Cruz, Diego Anderson<br><br>Herrera González, Luis Eduardo<br><br>Morales Calderón, Hernan Emilio<br><br>Valle Zuta, Abel Andrés <br>| **TB1:** |


# Objetivos SMART

<div align="justify">

En esta sección, se detallan los objetivos específicos asignados a cada estudiante, aplicando la metodología SMART. Este enfoque asegura que los objetivos sean Específicos, Medibles, Ambiciosos, Relevantes y estén limitados en el Tiempo. La definición precisa de estos objetivos no solo orienta el trabajo de cada estudiante hacia resultados claros y alcanzables, sino que también garantiza que cada paso contribuya de manera significativa al éxito del proyecto MobiLoom, alineándose con su misión de transformar el proceso de due diligence en línea. A continuación, se presenta un desglose de los objetivos SMART asignados, junto con sus respectivas métricas y plazos.

<div style="font-size: 9px;">

| Nombre                                  | Descripción del objetivo                                                                                                                                           | Fecha de inicio | Fecha de cump. esperada | Specific                                                                                                          | Measurable                                                                                                               | Ambitious                                                                                                                        | Relevant                                                                                                                     | Time-Bound                                                                                                               |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|--------------------------|-------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| Criollo De La Cruz, Diego Anderson       | Definirá el Problem Statement para MobiLoom, estableciendo con precisión los desafíos en la automatización del proceso de due diligence financiero y formulando las Asumptions y Hypothesis Statements. | 2024-08-12      | 2024-08-19               | Definir el Problem Statement para MobiLoom, estableciendo claramente los desafíos en la automatización del due diligence. | Se medirá mediante la claridad y precisión del Problem Statement, y la alineación de las Asumptions y Hypothesis Statements con los desafíos identificados. El KPI será la aceptación de estas definiciones por el equipo de desarrollo. | Este objetivo reta al estudiante a identificar con precisión problemas complejos y formular suposiciones e hipótesis que proyecten soluciones innovadoras.            | Alineado con la estrategia de MobiLoom de transformar la due diligence en línea, proporcionando una base sólida para el desarrollo de soluciones tecnológicas avanzadas. | Este objetivo deberá cumplirse en las primeras dos semanas del proyecto para garantizar un desarrollo ágil.                  |
| Herrera González, Luis Eduardo           | Realizará una investigación de competidores en el sector de due diligence automatizado y diseñará preguntas para las entrevistas clave. También gestionará la recopilación de evidencias para mejorar la propuesta de valor de MobiLoom. | 2024-08-12      | 2024-08-26               | Realizar una investigación exhaustiva de los competidores de MobiLoom y diseñar preguntas para las entrevistas clave. | Se medirá mediante la identificación de al menos tres competidores directos y la creación de un informe comparativo detallado. El KPI será la cantidad y calidad de las evidencias recopiladas para apoyar la propuesta de valor.            | El objetivo desafía al estudiante a identificar tendencias clave en la industria y recopilar datos que impulsen mejoras estratégicas en MobiLoom, superando las ofertas de la competencia. | Es fundamental para asegurar que MobiLoom se posicione de manera competitiva en el mercado de due diligence automatizado. | La investigación y recopilación de evidencias deben completarse dentro de las primeras tres semanas del proyecto.         |
| Morales Calderón, Hernan Emilio          | Analizará las entrevistas para identificar y desarrollar las fichas de la Persona Principal y Secundaria. Además, definirá una propuesta de valor innovadora que se alinee con las necesidades del mercado. | 2024-08-12      | 2024-08-26               | Analizar las entrevistas para identificar y desarrollar las fichas de la Persona Principal y Secundaria, y definir una propuesta de valor innovadora y alineada con las necesidades del mercado. | Se evaluará mediante la precisión y utilidad de las fichas de Persona y la alineación de la propuesta de valor con las necesidades detectadas en las entrevistas. El KPI será la validación de estas fichas y la propuesta de valor por parte del equipo directivo. | Exige una profunda comprensión del usuario y del mercado, retando al estudiante a proponer una oferta que destaque en un mercado altamente competitivo. | Alineado con la misión de MobiLoom, es crucial para garantizar que las soluciones desarrolladas respondan a las necesidades de los usuarios y se diferencien en el mercado. | Este objetivo deberá cumplirse dentro de las primeras cuatro semanas del proyecto para asegurar su relevancia y aplicabilidad. |
| Valle Zuta, Abel Andrés	                | Identificará y definirá las User Stories necesarias para desarrollar las funciones críticas de MobiLoom, asegurando que estén alineadas con el alcance del producto y las necesidades del usuario. | 2024-08-12      | 2024-09-02               | Identificar y definir las User Stories necesarias para el desarrollo de MobiLoom, alineadas con el alcance del producto y las necesidades del usuario. | El cumplimiento se medirá mediante la cantidad de User Stories definidas y su alineación con el roadmap del producto. El KPI será la aprobación de estas historias por el equipo de desarrollo.            | Este objetivo reta al estudiante a pensar de manera integral y anticipada, creando User Stories que no solo respondan a las necesidades actuales, sino que también proyecten la evolución futura del producto. | Es vital para asegurar que el desarrollo de MobiLoom siga una dirección estratégica clara y enfocada en las necesidades del usuario final. | Las User Stories deben estar completamente definidas y aprobadas dentro de las primeras cinco semanas del proyecto.       |

</div>


# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
<div align="justify">
    MobiLoom es una startup centrada en ofrecer soluciones innovadoras para el proceso de due diligence
en línea. Nos especializamos en la automatización de una variedad de procesos, desde el análisis
de datos financieros de empresas hasta la revisión de sus estados de cuenta, entre otras funciones
críticas. Nuestras plataformas tecnológicas están diseñadas para proporcionar una manera eficiente y
precisa de llevar a cabo una debida diligencia exhaustiva durante transacciones comerciales, como la
venta de empresas. En DeltaTech, nos comprometemos a simplificar y agilizar el proceso de evaluación, permitiendo a nuestros clientes tomar decisiones informadas con confianza. Cada solución que
desarrollamos está impulsada por la búsqueda constante de la excelencia en la eficiencia operativa y
la precisión en el análisis de datos. En MobiLoom, estamos transformando la forma en que se aborda la
due diligence en línea, llevando la automatización al centro de las transacciones comerciales del siglo
XXI.
    <br>
    
  <div align="center">

  ![Diego Criollo](Resources/cap1/logomobilom-removebg-preview.png)

  </div>

</div>
<div align="justify">
    <ul>
        <li>
            <b>Misión:</b>
        </li>
        Nuestra misión en MobiLoom es proporcionar soluciones innovadoras y eficientes para el proceso
de due diligence en línea, permitiendo a nuestros clientes realizar evaluaciones exhaustivas de
manera rápida y precisa durante transacciones comerciales críticas, como la venta de empresas.
Nos esforzamos por automatizar y simplificar el análisis de datos financieros, brindando a los
inversores las herramientas necesarias para tomar decisiones informadas y estratégicas que
impulsen el éxito en sus operaciones.
        <li>
            <b>Visión:</b>
        </li>
        Nuestra visión en MobiLoom es transformar la forma en que se realiza la debida diligencia,
siendo líderes en el desarrollo de plataformas tecnológicas avanzadas que agilizan el análisis de
información financiera. Nos comprometemos a ofrecer una experiencia de usuario excepcional
a través de interfaces intuitivas y seguras, respaldadas por algoritmos avanzados y cifrado de
datos de extremo a extremo. Buscamos ser reconocidos como socios confiables y fundamentales
en el éxito de las transacciones comerciales, facilitando la toma de decisiones estratégicas para
nuestros clientes en todo momento.
</div>

### 1.1.2. Perfiles de integrantes del equipo

### Los integrantes que conforman parte de nuestro startup son:
<div align="justify">

| Integrante                | Perfil                                | Foto                                                |
|---------------------------|--------------------------------------------------|-------------------------------------|
| Criollo De La Cruz, Diego Anderson (U202219639) | Mi nombre es Diego Anderson Criollo de La Cruz, soy estudiante de 6to ciclo de la carrera de Ingeniería de Software. Me gusta mucho emplear soluciones creativas y que busquen eficiencia para poder aborder de esta forma cualquier desafío de la mejor manera. Como miembro del grupo, pretendo aportar con todos mis conocimientos en el desarrollo web tanto como en el front-end y back-end, además de siempre colaborar con mis ideas y soluciones ante cualquier dificultad que se presente en el desarrollo. Espero poder aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del desarrollo del proyecto. | ![Diego Criollo](Resources/Team%20Members/Criollo-Diego.jpg)             |
| Herrera González, Luis Eduardo (U202218227) | Me llamo Luis Eduardo Herrera González, tengo 20 años y curso el 6to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Como habilidades técnicas conozco los lenguajes de C++, C#, Java, Python y Visual Basic; manejo base de datos SQL y NoSQL (MongoDB); manejo los frameworks de Angular, Vue, Spring Boot y .NET. Por la parte de mis habilidades blandas siento que soy buen comunicador, responsable, empático y buen organizador de grupo. Espero ser de utilidad para el equipo en cumplir todos los requisitos con alta calidad de este proyecto. | ![Luis Herrera](Resources/Team%20Members/Herrera-Luis.png)               |
| Morales Calderón, Hernan Emilio (U202216263) | Soy Hernan Morales, tengo 19 años y actualmente estoy cursando el 6to ciclo de Ingeniería de Software. Me considero una persona sumamente responsable y organizada, especialmente en trabajos universitarios. Mi objetivo es culminar exitosamente el curso y nuestro proyecto junto a mi equipo, asegurando que cada detalle se ejecute con precisión. Tengo conocimientos sólidos en lenguajes como C++, C#, y JavaScript, así como en frameworks como Angular y Vue, lo que me permite desarrollar interfaces dinámicas y adaptarme rápidamente a diferentes entornos de desarrollo. Además, manejo SQL para la gestión y optimización de bases de datos. Estoy convencido de que, con buena planificación y comunicación, entregaremos un proyecto de alta calidad que supere las expectativas. | ![Hernan Morales](Resources/Team%20Members/Morales-Hernan.png)              |
| Valle Zuta, Abel Andrés (U202210297) | Soy Abel Andrés Valle Zuta, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), tengo 19 años y actualmente estoy cursando el 6to ciclo en la sede de Monterrico. Sé programar y editar videos. Además, sé resolver problemas, trabajar en equipo y lograr unir más al grupo. Mis hobbies son jugar básquet, fútbol, tenis, videojuegos, escuchar música, salir a pasear con mis amigos, ver películas, nadar, hacer ejercicio, pasear a mis mascotas y pasar tiempo con mi familia. Finalmente, siempre estoy dispuesto a trabajar y terminar a tiempo los deberes, esforzándome para aprender y comprender lo máximo posible y finalizar con éxito todos mis objetivos. | ![Abel Valle](Resources/Team%20Members/Valle-Abel.jpg)               |

## 1.2. Solution Profile

<div align="justify">

En el cambiante mundo empresarial actual, la debida diligencia financiera se ha convertido en un pilar fundamental para asegurar transacciones comerciales seguras y exitosas. Sin embargo, el proceso tradicional de recolección y análisis de datos financieros de empresas puede ser lento, tedioso y propenso a errores. Esta realidad ha generado una necesidad urgente de encontrar soluciones innovadoras que permitan a los inversores realizar este crucial proceso de manera más eficiente y efectiva.
En este contexto, surge una nueva era de la debida diligencia financiera, donde la tecnología y la inteligencia se unen para ofrecer soluciones ágiles y precisas. La búsqueda de métodos más inteligentes para acceder y analizar datos financieros se ha convertido en una prioridad para los profesionales que buscan tomar decisiones informadas y estratégicas en sus inversiones.

</div>

![Recurso extraído de Canva](Resources/cap1/solutionp.png)

### 1.2.1. Antecedentes y problemática

<div align="justify">

***What***

* El proceso tradicional de *Due Diligence* se caracteriza por ser laborioso, costoso y propenso a errores.
* Los inversores y profesionales financieros revisan una gran cantidad de documentos financieros, legales y operativos en un tiempo limitado.
* Esto puede resultar en la contratación de servicios adicionales y gastos innecesarios.



***Who***

* Inversores y profesionales financieros se ven afectados por la complejidad y la carga de trabajo del proceso tradicional de *Due Diligence*.
* Propietarios de empresas enfrentan el desafío de compartir información confidencial con inversores potenciales.


***Where***

Esta problemática es común en transacciones comerciales y de inversión, donde la debida diligencia es crucial.



***When***

La problemática surge en cada proceso de adquisición o inversión, donde la toma de decisiones debe realizarse en un tiempo limitado.



***Why***

* La falta de acceso rápido y la preocupación por la seguridad de la información sensible de la empresa dificultan la toma de decisiones.
* Existe el riesgo de que los inversores utilicen los datos sensibles con otros fines, lo que genera incertidumbre y desconfianza.


***How***

* En el estado normal, los contadores e inversores pueden requerir días o semanas para revisar y analizar manualmente los documentos financieros de una empresa. Con "MobiLoom", el proceso se acelerará significativamente, permitiendo la revisión y análisis en cuestión de horas

* El problema sigue un patrón de ineficiencia y lentitud en el proceso de *Due Diligence*. Los contadores y los inversores a menudo se ven abrumados por la cantidad de documentos y la falta de herramientas eficientes para analizarlos de manera rápida y precisa.



***How Much***

* En un día, un inversor puede perder oportunidades de inversión valiosas debido a la demora en la obtención de informes financieros. Con "MobiLoom", estas oportunidades podrían aumentar en un 50%.

* En términos de pérdida de oportunidades de inversión, el retraso actual podría estar implicando el equivalente a 50 000 soles por mes por los participantes de la inversión. Con "MobiLoom", se podrían reducir los retrasos que se pueden presentar en el proceso de **Due Diligence**.

</div>

### 1.2.2. *Lean UX Process*

![Recurso extraído de Canva](Resources/cap1/leanux.png)

#### 1.2.2.1. *Lean UX Problem Statements*

<div align="justify">

***Problem Statement***

* El estado actual del Due Diligence para los inversionistas, y contadores que representan a sus empresas, es muy extenuante.

* Los productos actuales no ofrecen una solución completa. Ya sea esto solo el análisis, la búsqueda de empresas, la seguridad para trabajar con archivos. Sin embargo, nunca algo que embarque todo. Debido a esto, todos los involucrados son afectados de manera negativa, perdiendo grandes oportunidades de negocio o la inversión que necesitan para poder crecer en el mercado.

* ¿Cómo podemos mejorar la experiencia del proceso Due Diligence con el fin de agilizar y mejorar la calidad del trabajo?

</div>

#### 1.2.2.2. *Lean UX Assumptions*

***Business Assumptions:***

<div align="justify">

1. **Creo que mis clientes necesitan** una herramienta eficiente y confiable para realizar sus análisis financieros exhaustivos durante el proceso de *Due Diligence*.

2. **Estas necesidades se pueden resolver con** nuestra plataforma inteligente que automatice el análisis financiero y que ofrezca acceso rápido y seguro a información relevante de las empresas objetivo.

3. **Mis clientes iniciales son** inversores y contadores financieros que trabajan en sell-side.

4. **El valor #1 que un cliente quiere de mi servicio es** una manera eficiente y precisa de realizar sus transacciones durante el proceso de *Due Diligence*.

5. **El cliente también puede obtener estos beneficios adicionales** como una mayor confianza en el proceso de *Due Diligence*, una mayor seguridad de los datos financieros y una experiencia de usuario mejorada.
6. **Voy a adquirir la mayoría de mis clientes a través de** campañas de marketing dirigidas a empresas de capital privado, fondos de inversión y otros actores clave en el mercado de transacciones

7. **Haré dinero a través de** la venta de suscripciones a nuestra plataforma "Diligence Tech", ofreciendo diferentes niveles de acceso según las necesidades del cliente.

8. **Mi competencia principal en el mercado serán** otras plataformas de *Due Diligence* en línea, así como servicios tradicionales de consultoría que ofrecen análisis de datos financieros.

9. **Los venceremos debido a** nuestra capacidad para ofrecer una solución tecnológica más rápida, precisa y fácil de usar que nuestras competidoras, así como nuestro enfoque en la seguridad de los datos y la experiencia del usuario..

10. **El mayor riesgo del producto es** que la tecnología pueda no funcionar como se espera, lo que podría resultar en errores en los datos o brechas de seguridad.

11. **Resolveremos esto a través de la** implementación de rigurosas pruebas de calidad y seguridad, así como la rápida corrección de errores a medida que surjan.

12. **¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio/proyecto no funcione?** Otras suposiciones que tenemos son si:
    - Existe una demanda significativa.
    - La automatización de datos financieros mejorará el proceso de *Due Diligence*.
    - Garantizar la seguridad y privacidad de los datos financieros de las empresas objetivo a través de cifrado de extremo a extremo generará confianza entre los usuarios

</div>

***Business Outcomes:***

<div align="justify">

- Conseguir los primeros 100 usuarios registrados para la aplicación de ambos segmentos objetivos.

- Retener el 50% de los usuarios
  durante el primer semestre.

- Registrar 20 usuarios activos al mismo tiempo utilizando la aplicación.

- Conseguir el registro de 10 nuevos usuarios referidos a través de links compartidos.

</div>

***Users Assumptions:***

<div align="justify">

1. **¿Quién es el usuario?**

   Los usuarios son los asociados al proceso de Due Diligence, tanto los inversores que están interesados participar con empresas, como estás mismas representadas con sus contadores financieros.

2. **¿Qué problemas tiene nuestro producto? ¿Resolver?**

    * Dificultad para acceder y comparar de manera eficiente la información financiera de múltiples empresas durante el proceso de Due Diligence.
    * Riesgos asociados con la toma de decisiones basadas en datos financieros incompletos o inexactos.
    * Falta de una plataforma centralizada y fácil de usar para analizar y evaluar oportunidades de inversión de manera efectiva.
    * Dificultad para acceder y analizar rápidamente datos financieros de empresas objetivo durante el proceso de debida diligencia.
    * Riesgos asociados con la falta de seguridad y privacidad de los datos financieros sensibles.
    * Falta de eficiencia en el proceso de debida diligencia debido a la dependencia de métodos manuales y lentos.

3. **¿Qué características son importantes?**

* Interfaz de usuario intuitiva y eficiente que permita una navegación fluida y acceso rápido a la información financiera clave.
* Funcionalidades avanzadas de comparación y análisis de datos financieros para facilitar la toma de decisiones informadas.
* Seguridad de datos avanzada para garantizar la confidencialidad y protección de la información financiera sensible.
* Herramientas de visualización y generación de informes que permitan una comprensión clara y rápida de la salud financiera de las empresas objetivo.

4. **¿Dónde encaja nuestro producto en su trabajo o vida?**

   Nuestro producto se incorpora en el proceso de Due Diligence que los usuarios realizan. Estos lo utilizarían para agilizar los procesos que usualmente se realizan de manera manual o menos automatizada.

5. **¿Cuándo y cómo es usado nuestro producto?**

    * Es utilizado por los inversores y contadores desde el inicio del proceso de evaluación de una empresa objetivo hasta la toma final de decisiones de compra o inversión.
    * Los inversores utilizan nuestro producto para analizar los estados financieros, realizar comparaciones entre empresas y   evaluar los riesgos y oportunidades de inversión.
    * Los contadores lo utilizan para poder comunicarse con los inversores interesados y realizar transacciones de información de manera segura.

6. **¿Cómo debe verse nuestro producto y cómo comportarse?**

    * Debe comportarse de manera eficiente y rápida, brindando resultados precisos y actualizados de manera oportuna.
    * La seguridad y confidencialidad de los datos financieros es fundamental, por lo que el producto debe garantizar un cifrado sólido y medidas de protección avanzadas.
    * Nuestro producto debe tener una apariencia profesional y moderna, con una interfaz de usuario clara y organizada que facilite la comparación y análisis de datos.

</div>

***User outcomes:***

<div align="justify">

- Acceso de manera rápida y eficiente a la información financiera relevante de las empresas objetivo.
- Confianza en la seguridad y privacidad de los datos financieros sensibles
- Experiencia de usuario mejorada gracias a la interfaz intuitiva y fácil de usar

</div>

***Feature Assumptions***

<div align="justify">

* Herramientas avanzadas de análisis:
    - Los inversores podrán utilizar herramientas avanzadas para comparar rápidamente los datos financieros de múltiples empresas.
    - Se asume que características como gráficos interactivos, análisis comparativos y tablas dinámicas mejorarán la eficiencia del análisis.
    - Funciones especializadas para analizar estados financieros, ratios financieros, tendencias históricas y comparaciones sectoriales.
* Automatización de Procesos Repetitivos:
    - Capacidad de automatizar tareas como la extracción de datos financieros, el cálculo de ratios y la generación de informes estándar.
* Funcionalidades de Seguridad Avanzada:
    - Los inversores confiarán en la plataforma debido a las medidas de seguridad avanzada, como cifrado de extremo a extremo y autenticación de dos factores.
    - Se asume que la seguridad sólida garantizará la protección de los datos financieros confidenciales.
* Generación de Informes Personalizados:
    - Los inversores podrán crear informes personalizados basados en sus criterios de evaluación y preferencias.
    - Se asume que los informes detallados y personalizados facilitarán la toma de decisiones informadas.
* Visualización de Datos Interactiva:
    - Gráficos interactivos y tablas dinámicas para visualizar los datos financieros de manera clara y comprensible.
* Alertas y Notificaciones Relevantes:
    - Los inversores recibirán alertas sobre cambios significativos en los datos financieros de las empresas en su lista de seguimiento.
    - Se asume que las alertas oportunas y relevantes mejorarán la capacidad de reacción a los cambios en las empresas objetivo.

</div>

#### 1.2.2.3. *Lean UX Hypothesis Statements*

<div align="justify">

* **Creemos que** los usuarios valoran la eficiencia y precisión en el análisis de datos financieros durante el proceso de *Due Diligence*. **Sabremos que** esto es cierto **cuando** observemos una disminución significativa en el tiempo dedicado al análisis manual de datos, medido por una reducción del 30% en el tiempo promedio necesario para completar una debida diligencia.

* **Creemos que** los usuarios encuentran la automatización un elemento esencial para agilizar el proceso de cDue Diligence*. **Sabremos que** esto es cierto **cuando** veamos la disminución en el tiempo que se ocupa por cada proceso, medido por una reducción en 40% en el tiempo de los procesos que tienen la capacidad de ser automatizados.

* **Creemos que** la seguridad y privacidad de los datos financieros sensibles es una preocupación clave para los usuarios durante el proceso de *Due Diligence*. **Sabremos que** esto es cierto **cuando** veamos una mayor confianza en la plataforma “DiligenceTech” por parte de los contadores, medido por una reducción del 20% en las solicitudes de soporte relacionadas con la seguridad de los datos.

* **Creemos que** la generación de informes personalizados será importante para tomar decisiones finales para los usuarios. **Sabremos que** esto es cierto **cuando** veamos un incremento en la cantidad de adquisiciones que se realicen. Medido por un aumento en un 20% de compras después de realizarse el proceso de analisis financiero.

* **Creemos que** los usuarios valoran la visualización de datos interactivos durante el proceso de *Due Diligence*. **Sabremos que** esto es cierto **cuando** observemos un aumento del 30% en la tasa de participación de los usuarios en proyectos de análisis financiero donde se ofrecen visualizaciones de datos interactivos en comparación con sesiones donde no se proporcionan

* **Creemos que** las alertas y notificaciones son una funcionalidad muy importante para todos los usuarios. **Sabremos que** esto es cierto **cuando** veamos una reducción en el tiempo de respuesta entre los usuarios y la entrega de sus partes correspondientes., medido por un 20% en la reducción de quejas por falta de respuestas a tiempo de los usuarios durante el proceso de *Due Diligence*.

</div>

#### 1.2.2.4. *Lean UX Canvas*

![Artefacto creado en Figma ([URL](https://www.figma.com/file/jX7TR5fsEkgbQVH44vAmDb/Lean-UX-Canvas-2.0?type=design&node-id=0%3A1&mode=design&t=uRI0WHIdDhIsWi2g-1))](Resources/cap1/Lean-UX-Canvas.png)

## 1.3. Segmentos objetivo

![Tabla del segmento 1](Resources/cap1/segmento-1.png)

![Tabla del segmento 2](Resources/cap1/segmento-2.png)

# Capítulo II: Needfinding

## 2.1. Competidores

![](Resources/cap2/competidores-baner.png)

<div align="justify">

En el contexto de un mercado peruano en constante cambio y evolución, donde la gestión eficiente en los procesos de *Due Diligence*  se convierten en una necesidad primordial en el rubro de las inversiones. **DiligenceTech** se enfrenta a una urgente tarea: comprender y abordar a sus competidores para lograr una posición sólida y garantizar la satisfacción de sus usuarios.

</div>

**Competidores:**

<div align="justify">

* ***Datasite Diligence:***
  El *virtual data room* más utilizado en el mercado. Proporcionada por la empresa Datasite, esta solución mediante aplicación web brinda un espacio de almacenamiento y edición de archivos, los cuales se esperan que sean documentos financieros para posteriormente ser enviados por correo electrónico a quien sea desee el usuario. Entre las mecánicas más resaltantes en este competidor está la posibilidad de censura mediante IA elementos de los documentos y la modalidad Q&A. Su precio es a base de páginas que contengan los archivos, costando 7 mil dólares por cada 10 mil páginas.

</div>

  ![Imagen extraída de Datasite([URL](https://www.datasite.com/es/es/products/diligence))](Resources/cap2/datasite.png)

<div align="justify">

* ***iDeals:***
  *Virtual data room online* para servicios financieros, Biotech, IT y otras especializaciones del sistema que utilizan organizaciones de muchos usuarios dentro de la aplicación, la simplificación del ingreso y uso de archivos, y la seguridad del sistema en cuidarlos. Cuenta actualmente con más de 1 millón de usuarios y destaca en el mercado por su atención al cliente rápida y constante.

</div>

  ![Imagen extraída de iDeals([URL](https://es.idealsvdr.com/))](Resources/cap2/ideals.png)

<div align="justify">

* ***Firmex:***
  *Virtual data room* para contadores financieros que permite insertar y guardar archivos al sistema con funcionalidades como Q&A y censura. Reconocido en el mercado por la seguridad que mantiene en los archivos.

</div>

  ![Imagen extraída de Firmex([URL](https://www.firmex.com/))](Resources/cap2/firmex.png)

### 2.1.1. Análisis competitivo

<table><tr><th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th></tr>
<tr><td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?  </td><td colspan="7" valign="top">Este análisis nos permitirá reconocer a las compañías competidoras y sus respectivos productos similares a DiligenceTech y resaltar las funcionalidades y carencias que estas mismas posean para comparar con nuestra propuesta.</td></tr>
<tr><td colspan="6" valign="top"><p><b>Nombre</b></p><p></p></td><td colspan="3" valign="top"><b>DillingenceTech</b></td><td colspan="3" valign="top"><b>Datasite Dilligence</b></td><td colspan="3" valign="top">` `<b>iDeals</b></td><td valign="top"><b>Firmex</b></td></tr>
<tr><td colspan="6" valign="top"><b>Logo</b> </td><td colspan="3" valign="top"><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/dilligencetech-logo.png" alt="DilligenceTech logo" /></div></td><td colspan="3" valign="top"><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/datasitedillingence-logo.png" alt="Datasite Dilligence logo" /></div></td><td colspan="3" valign="top"><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/ideals-logo.png" alt="iDeals logo" /></div></td><td valign="top"><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/firmex-logo.png" alt="Firmex logo" /></div></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td><td colspan="3" rowspan="2" valign="top"><b>Overview</b></td><td colspan="3" rowspan="2" valign="top">Web application que ofrece una virtual data room especializada en el análisis y edición de contenido de documentos financieros, la presentación de estos y la extracción web complementaria de documentos financieros públicos.</td><td colspan="3" rowspan="2" valign="top">Web y mobile application que ofrece una virtual data room especializada en Due Diligence con sistemas de inteligencia artificial en la búsqueda de archivos, censura y formatos Q&A para el trabajo colaborativo.</td><td colspan="3" rowspan="2" valign="top">Web y mobile application que ofrece una virtual data room especializada en utilizar márgenes separados para proceso de Due Diligence. Lo que ofrece funcionalidades únicas separar los. documentos financieros por categorías.</td><td rowspan="2" valign="top">Web y mobile application especializada en la carga de archivos financieros y la utilización del formato Q&A para la colaboración entre múltiples usuarios autorizados que participen en el proceso de Due Diligence.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td><td colspan="3" rowspan="2" valign="top">La ventaja competitiva de DiligenceTech reside en su enfoque especializado en la eficiencia y seguridad del manejo de archivos e información sensible con el cifrado de extremo a extremo. Asimismo, su interfaz intuitiva y fácil de usar, facilita los flujos de trabajo.</td><td colspan="3" rowspan="2" valign="top">La ventaja competitiva de Datasite Diligence reside en la gestión de diferentes archivos a través del uso de sistemas con inteligencia artificial. Asimismo, destaca por tener herramientas y una amplia base de datos con información detallada para análisis financieros.</td><td colspan="3" rowspan="2" valign="top">La ventaja competitiva de iDeals reside en la categorización de sus archivos e información sensible. Asimismo, ofrece una atención eficiente y rápida a sus clientes en los procesos de Due Diligence.</td><td rowspan="2" valign="top">La ventaja competitiva de Firmex es la carga especializada de archivos financieros y el uso del formato Q&A. Asimismo, es una plataforma segura para procesos de fusiones y adquisiciones.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td><td colspan="3" valign="top"><b>Mercado objetivo</b></td><td colspan="3" valign="top"><p>- Contadores financieros. </p><p>- Inversores. </p><p>- Firmas de capital privado. </p><p>- Empresas en procesos de fusiones y adquisiciones.</p></td><td colspan="3" valign="top"><p>- Empresas en procesos de fusiones y adquisiciones. </p><p>- Empresas financieras que trabajan realizando Due Diligence.</p></td><td colspan="3" valign="top"><p>- Empresas en busca de realizar un Due Diligence para su beneficio. </p><p>- Empresas financieras que trabajan realizando Due Diligence.</p></td><td valign="top"><p>- Empresas en busca de realizar un Due Diligence para su beneficio. </p><p>- Empresas financieras que trabajan realizando Due Diligence.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Estrategias de Marketing</b></td><td colspan="3" valign="top"><p>- Social Ads. </p><p>- Email marketing. </p><p>- Marketing en redes sociales. </p><p>- Marketing de contenidos.</p></td><td colspan="3" valign="top"><p>- Estrategia de up-selling. </p><p>- Marketing de contenidos. </p><p>- Email marketing. </p><p>- Marketing en redes sociales. </p><p>- SEM (Search Engine Marketing).</p></td><td colspan="3" valign="top"><p>- Marketing de contenidos. </p><p>- Email marketing. </p><p>- SEM (Search </p><p>&emsp;Engine Marketing).</p></td><td valign="top"><p>- Marketing en redes sociales. </p><p>- Marketing de contenidos. </p><p>- Social Ads.</p></td></tr>
<tr><td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td><td colspan="3" valign="top"><b>Productos y Servicios</b></td><td colspan="3" valign="top"><p>- Plataforma de gestión de datos financieros y revisión segura de información sensible. </p><p>- Herramientas de análisis y comparación.</p></td><td colspan="3" valign="top"><p>- Base de datos con extensa información detallada. </p><p>- Herramientas avanzadas de análisis financiero y comparativo.</p></td><td colspan="3" valign="top"><p>- Plataforma segura para compartir documentos con información sensible. </p><p>- Herramientas de colaboración y seguimiento de transacciones.</p></td><td valign="top"><p>- Virtual data room con un soporte para una cantidad ilimitada de usuarios en cualquier tipo de Due Diligence (M&A, Buy Side, Sell Side, etc). </p><p>- Atención especializada a los clientes las 24 horas del día.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Precios y Costos</b></td><td colspan="3" valign="top">DiligenceTech tendrá dos planes de suscripción. Un plan básico de 500 soles anuales y un plan avanzado de 800 soles anuales. El plan básico ofrece las funciones principales de la web application, mientras que el plan avanzado, ofrece herramientas avanzadas de recolección de datos financieros de empresas publicas.</td><td colspan="3" valign="top">Datasite Diligence ofrece sus precios en base a la cantidad de datos y tiempo utilizados en su plataforma. Sin embargo, un uso basico de sus funciones puede costar aproximadamente 1000 délares mensuales. Es importante resaltar que sus precios no son compartidos públicamente, la cotización se hace de forma personalizada.</td><td colspan="3" valign="top">iDeals ofrece tres planes de suscripción para sus servicios de salas de datos: el plan Pro, diseñado para proyectos pequeños y medianos; el plan Business, adecuado para proyectos de tamaño mediano a grande; y el plan Enterprise, que es una solución de nivel empresarial pensada para diversos objetivos comerciales.</td><td valign="top"><p>Firmex ofrece planes de precios personalizados que dependen de dos factores: si se requiere la plataforma para un solo proyecto o múltiples proyectos, y la cantidad de memoria requerida. Por ejemplo, para empresas financieras que necesitan 5 GB de memoria y soporte para múltiples proyectos, el precio es de 1000 dólares anuales.</p><p></p></td></tr>
<tr><td colspan="3" valign="top"><b>Canales de distribución</b></td><td colspan="3" valign="top">DiligenceTech contara con un website en donde se mostraran y detallaran sus planes de suscripción.</td><td colspan="3" valign="top"><p>Datasite Diligence cuenta con un formulario de contacto para la cotización y venta de las aplicaciones de su web application. (Web)</p><p></p></td><td colspan="3" valign="top">iDeals cuenta con un formulario de contacto para obtener el precio de cada uno de sus planes de suscripción. (Web)</td><td valign="top">Firmex cuenta con un formulario de contacto para la cotización de sus precios. (Web)</td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td><td colspan="3" valign="top"><b>Fortalezas</b></td><td colspan="3" valign="top"><p>- Interfaz intuitiva y fácil de usar. </p><p>- Cifrado de extremo a extremo para seguridad de datos. </p><p>- Perfecto para inversores y contadores financieros, debido a que ofrecemos opciones de personalización para adaptarse a las necesidades específicas de cada cliente. </p><p>- Informes detallados y análisis profundo de datos financieros.</p></td><td colspan="3" valign="top"><p>- Competidor líder en el mercado. </p><p>- Presencia global y local, en especial en empresas grandes del país. </p><p>- Aplicación móvil como contraparte. </p><p>- Experiencia en el campo de Due Diligence.</p></td><td colspan="3" valign="top"><p>- Atención al cliente las 24 horas del día y con respuesta rápida. </p><p>- Experiencia en el campo de Due Diligence. </p><p>- Seguridad en el Data Room. </p><p>- Aplicación móvil como contraparte. </p><p>- Enfocado para todo tipo de Due </p><p>- Diligence junto a todo tipo de documentos requeridos.</p></td><td valign="top"><p>- Atención al cliente las 24 horas del día y con respuesta rápida. </p><p>- Precio más asequible en comparación con otras ofertas. </p><p>- Experiencia en el campo de Due Diligence. </p><p>- Seguridad en el Data Room.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Debilidades</b></td><td colspan="3" valign="top"><p>- Proyecto aún en desarollo. </p><p>- Necesidad de establecer una reputación en el mercado.</p></td><td colspan="3" valign="top"><p>- Competencia en el sector de seguridad privada. </p><p>- Riesgos asociados con la ciberseguridad. </p><p>- Dependencia de la economía y la seguridad del país en el que opera.</p></td><td colspan="3" valign="top"><p>- Diferencias de experiencias de uso entre sus plataformas. </p><p>- El costo de adquirir y mantener una plataforma pueden ser una barrera para ciertas empresas.</p></td><td valign="top">- Limitaciones de cobertura.</td></tr>
<tr><td colspan="3" valign="top"><b>Oportunidades</b></td><td colspan="3" valign="top"><p>- Crecimiento del mercado de seguridad residencial y protección personal. </p><p>- Posibilidad de expansión a nivel internacional.</p></td><td colspan="3" valign="top"><p>- La marca y popularidad le permite crecer fácilmente en Perú. </p><p>- Aumento de la demanda. </p><p>- Expansión de mercados emergentes. </p><p>- Mayor conciencia sobre la seguridad en el mundo empresarial.</p></td><td colspan="3" valign="top"><p>- El crecimiento de su popularidad habilita su posibilidad de crecer. </p><p>- Expandirse a nuevos mercados. </p><p>- Continuar con el desarrollo de nuevas funcionalidades y herramientas para mejorar la experiencia del usuario.</p></td><td valign="top"><p>- La demora de cotización de la competencia. </p><p>- Diversificación de productos y servicios. </p><p>- Innovación en la tecnología de seguridad. </p><p>- Expansión geográfica y alianzas estratégicas.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Amenazas</b></td><td colspan="3" valign="top"><p>- Competencia de nuevas plataformas emergentes. </p><p>- Cambios en la regulación gubernamental. </p><p>- Desafíos en la adopción de tecnología. </p><p>- Problema de seguridad de datos.</p></td><td colspan="3" valign="top"><p>- Cambios en la regulación gubernamental. </p><p>- Riesgos cibernéticos en constante evolución. </p><p>- Competencia de nuevas plataformas emergentes.</p></td><td colspan="3" valign="top"><p>- Cambios en preferencias del consumidor. </p><p>- Ataques de la seguridad de los datos en la plataforma. </p><p>- Cambios en la regulación gubernamental.</p></td><td valign="top"><p>- Competencia creciente en el mercado de servicios integrales. </p><p>- Impacto económico adverso en el entorno empresarial peruano. </p><p>- Cambios en la regulación gubernamental.</p></td></tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<div align="justify">

Según Michael Porter, la estrategia competitiva implica cómo una empresa compite en su mercado específico. Porter identificó tres estrategias generales que las empresas pueden emplear para competir con éxito: liderazgo en costos, diferenciación y enfoque. La estrategia de liderazgo en costos implica ofrecer productos o servicios a precios más bajos que los de los competidores, mientras que la diferenciación se basa en ofrecer productos y servicios únicos y distintivos. Por otro lado, una estrategia de enfoque se centra en un segmento de mercado específico. Para llevar a cabo eficazmente estas estrategias, las empresas necesitan tener un profundo conocimiento de sus mercados y competidores para desarrollar y mantener una ventaja competitiva sostenible a largo plazo.

Teniendo en cuenta el análisis SWOT previamente presentado para DiligenceTech, proponemos las siguientes estrategias competitivas:

**Estrategias Competitivas para** ***DiligenceTech:***

1. **Liderazgo en Costos:**

**Estrategia:** *DiligenceTech* puede buscar optimizar sus procesos internos para reducir costos operativos y ofrecer sus servicios a precios más competitivos que los de sus competidores.

**Tácticas:**
* Implementar tecnologías eficientes que reduzcan los gastos de infraestructura y operativos.
* Negociar acuerdos favorables con proveedores y socios para obtener mejores precios en servicios y herramientas necesarios.
* Ofrecer modelos de precios flexibles y descuentos opr volumen para atraer a clientes sensibles al costo.

2. **Diferenciación a través de la Innovación:**

**Estrategia:** *DiligenceTech* puede enfocarse en desarrollar características y funcionalidades únicas que destaquen su plataforma como líder en innovación en el proceso de *Due Diligence*.

**Tácticas:**
* Realizar investigaciones de mercado para identificar necesidades no cubiertas y oportunidades de mejora.
* Invertir en I+D para desarrollar herramientas avanzadas de análisis financiero y presentación de informes.
* Promocionar activamente las nuevas características a través de campañas de marketing destacando la vanguardia tecnológica de DiligenceTech.


3. **Enfoque en segmentos específicos del mercado:**

**Estrategia:** *DiligenceTech* puede especializarse en atender a segmentos específicos del mercado donde pueda ofrecer un valor diferenciado y adaptado.

**Tácticas:**
* Identificar sectores de la industria con necesidades únicas de debida diligencia, como startups en crecimiento, empresas de tecnología emergente, o industrias reguladas.
* Desarrollar soluciones personalizadas y paquetes de servicios adaptados a las necesidades específicas de cada segmento.
* Colaborar con asociaciones y grupos de la industria para fortalecer la presencia en estos segmentos y generar confianza.

**Tácticas Específicas para** ***DiligenceTech:***

1. **Monitoreo Competitivo Continuo:**

**Táctica:** Realizar análisis periódicos de las estrategias, precios y ofertas de la competencia para identificar oportunidades y amenazas.

**Acciones:**
* Mantenerse al tanto de los movimientos de los competidores en cuanto a lanzamientos de productos, cambios de precios y campañas de marketing.
* Utilizar herramientas de seguimiento de competidores y análisis de mercado para obtener información valiosa.

2. **Estrategias de Precios y Paquetes Competitivos:**

**Táctica:** Ajustar estratégicamente los precios y paquetes de servicios para competir de manera efectiva en el mercado.

**Acciones:**
* Realizar análisis de precios comparativos y ajustar los precios de acuerdo con el valor percibido por los clientes.
* Ofrecer paquetes personalizados que se ajusten a las necesidades específicas de diferentes tipos de clientes, como empresas grandes, medianas y startups.

3. **Inversión en Marketing Diferenciado:**

**Táctica:** Desarrollar mensajes y campañas de marketing que resalten las fortalezas únicas y la propuesta de valor de DiligenceTech.

**Acciones:**
* Crear contenido educativo y de valor que demuestre cómo DiligenceTech aborda los desafíos específicos de la debida diligencia.
* Utilizar estudios de casos y testimonios de clientes para respaldar los beneficios y resultados de la plataforma.

4) **Alianzas Estratégicas y Colaboraciones:**

**Táctica:** Establecer asociaciones estratégicas con empresas complementarias o instituciones que puedan ampliar el alcance y la oferta de DiligenceTech.

**Acciones:**
* Colaborar con firmas de consultoría reconocidas para ofrecer servicios combinados de asesoramiento y tecnología.
* Formar alianzas con organizaciones financieras o legales para ofrecer paquetes completos de servicios de debida diligencia.

</div>

## 2.2. Entrevistas

<div align="justify">

Para acceder al video de las entrevistas, haga click en la ([URL](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b380_upc_edu_pe/Eee1M6-Jg-dImBVzG5oLzDABSq0nZPG4Tgj0we3EL3ufaA?e=65BOJ8))

### 2.2.1. Diseño de entrevistas

Entrevista a personas referentes a nuestro segmentos objetivo, las preguntas varían dependiendo del segmento debido a las diferentes situaciones:

**Segmento 1:** Contadores Financieros

**Preguntas de introducción:**

1. ¿Cuántos años tiene?
2. ¿En qué ciudad del Perú reside?
3. ¿Cuál considera que es su estatus social limitando la descripción a Clase Baja, Clase Media, Clase Media-Alta y Clase Alta?
4. ¿Cúal es su profesión?
5. ¿Cuánto tiempo lleva ejerciendo esta profesión?
6. ¿Está familiarizado con el concepto y proceso de diligencia debida?

**Preguntas principales:**

1. ¿Cómo lleva a cabo usted su trabajo para un proceso de diligencia debida?
2. ¿Podría mencionar su participación en la diligencia debida en base a las etapas que tiene?
3. ¿Cómo son los procesos más comunes de obtener documentos financieros de las empresas investigadas y cuanto tiempo demoran?
4. ¿Cuáles son los documentos de las empresas que dan más problemas en obtener?
5. ¿Qué indicador o análisis financiero considera el más importante para calificar una empresa?
6. ¿Cual ha sido la mayor cantidad de empresas que ha consultado a la vez?
7. ¿Usted mismo realiza el análisis financiero?
8. ¿Qué tipo de problemas se encuentran a la hora de analizar los datos de la empresa?
9. ¿Qué medidas de seguridad se llevan para garantizar la confidencialidad de los datos?
10. ¿Cuáles son los procesos más importantes que usted rinde para la diligencia debida?
11. ¿Cómo se guardan y se comparten los documentos financieros en el proceso de diligencia debida?
12. ¿Usualmente cuánto demora un proceso de *Due Diligence*?
13. ¿Qué herramientas conoce o utiliza durante este proceso?
14. ¿Qué partes le parecen tediosas del proceso de diligencia debida?
15. ¿Cómo colabora con otros participantes en el proceso de diligencia debida?
16. ¿Qué problemas suelen ocurrir mediante el proceso de diligencia debida y cómo los resuelve?
17. ¿Ve factible contener los documentos financieros en un servicio de alojamiento en la web como Google Drive?
    * En caso sí, ¿Qué funcionalidades cree que vendrían útil para complementar el servicio? ¿Algo que tenga que ver con seguridad, análisis automático o edición de los documentos?
    * En caso no, ¿Qué funcionalidades cree que debería tener para que sea posible tenerlo en uno de estos sistemas?
18. En los documentos financieros se suele presentar censura de elementos que no se desea que sean revelados: ¿Le parece que le sería sencillo que en la aplicación misma sea posible hacer este proceso?
19. Para mantener la seguridad del proceso el dueño de la empresa va a agregar a diversos contadores los cuales solo tendrán acceso a subir archivos en cada request que haga el inversor. ¿Piensa que esta limitación es suficiente para mantener la integridad de la empresa a vender?
20. ¿Existen documentos financieros que obtiene, como contador, del internet? ¿Nos podría decir en donde se consiguen normalmente? ¿Me gustaría que nuestro sistema haga automáticamente la recolección de estos documentos al brindar el nombre de la compañía? ¿Tiene alguna opinión complementaria a esta funcionalidad?
21. Debido a la sensibilidad y debida discreción que deben tener los documentos privados de la empresa nuestro modelo ha implementado una vista previa de los mismos que no podrán descargarse ni apropiarse de algún modo. ¿Qué opina sobre esta funcionalidad?
22. Nuestra aplicación web usará el análisis de datos en base a lo que el contador envía y mostrará de manera intuitiva y digerible la proyección a largo plazo de la empresa. ¿Qué opina sobre esta implementación?

**Segmento 2:** Inversores

**Preguntas de introducción:**

1. ¿Cuántos años tiene?
2. ¿En qué ciudad del Perú reside?
3. ¿Cuál es su ocupación principal?
4. ¿Cuál es su nivel de experiencia en inversiones?
5. ¿Con qué frecuencia realiza inversiones?
6. ¿Cuál es su principal objetivo al invertir? (por ejemplo, crecimiento de capital, ingresos pasivos, diversificación, impacto social, etc.)
7. ¿En qué sectores o industrias prefiere invertir?
8. ¿Prefiere invertir en empresas nuevas y emergentes o en empresas establecidas?
9. ¿Ha participado anteriormente en procesos de *Due Diligence* antes de invertir en una empresa?
10. ¿Qué información financiera y empresarial considera más importante al evaluar una oportunidad de inversión?

**Preguntas principales:**

1. ¿Qué experiencia tiene en procesos de *Due Diligence* al evaluar una empresa?
2. ¿Cuáles son los aspectos clave que busca en un informe de *Due Diligence* antes de tomar una decisión de inversión?
3. ¿Qué indicadores financieros o métricas considera cruciales al evaluar la salud financiera de una empresa?
4. ¿Qué tipo de riesgos financieros le preocupan más al considerar una inversión?
5. ¿Qué papel juega la reputación y el historial de la empresa en su decisión de inversión?
6. ¿Cuál es su enfoque para diversificar su cartera de inversiones?
7. ¿Qué herramientas o plataformas utiliza para realizar análisis financiero y seguimiento de inversiones?
8. ¿Cómo es el proceso de una diligencia debida desde su experiencia? ¿Cómo participa en ella?
9. ¿En algún momento durante el proceso la empresa le ha hecho una serie de preguntas o detalles para poder llevar a cabo el proceso?
10. ¿En qué formato es el que recibe los resultados de la diligencia debida? ¿Le parece eficiente? ¿Desearía tenerlo en formato virtual?
11. ¿Ve factible contener los resultados de los documentos financieros en un servicio de alojamiento en la web como Google Drive donde se le comparte?
    * En caso sí, ¿Qué funcionalidades cree que vendrían útil para complementar el servicio? ¿Algo que tenga que ver con seguridad, análisis automático o edición de los documentos?
    * En caso no, ¿Qué funcionalidades cree que debería tener para que sea posible tenerlo en uno de estos sistemas?

**Preferencias y comportamientos de inversión:**

1. ¿Prefiere invertir en empresas locales o internacionales?
2. ¿Qué tamaño de empresa prefiere para sus inversiones? (por ejemplo, startups, PYMES, grandes corporaciones)
3. ¿Cuál es su horizonte de tiempo típico para una inversión? (corto plazo, mediano plazo, largo plazo)
4. ¿Qué factores externos (económicos, políticos, sociales) considera al tomar decisiones de inversión?
5. ¿Qué grado de involucramiento espera tener esn las empresas en las que invierte? (por ejemplo, pasivo, activo, asesoramiento)
6. ¿Cómo valora la transparencia y la comunicación de una empresa con sus inversores?
7. ¿Ha tenido experiencias previas de éxito o fracaso en inversiones que le gustaría compartir?

**Tecnología y preferencias de información:**

1. ¿Qué tipo de información financiera y empresarial prefiere recibir durante un proceso de diligencia debida?
2. ¿Cómo prefiere acceder a esta información? (documentos físicos, plataformas en línea, informes interactivos, etc.)
3. ¿Qué funcionalidades o herramientas tecnológicas le gustaría ver en una plataforma de *Due Diligence* para facilitar sus decisiones de inversión?
4. ¿Está familiarizado con el uso de análisis de datos y tecnologías de inteligencia artificial en procesos de inversión o diligencia debida?
5. ¿Qué medidas de seguridad considera esenciales al compartir información financiera y empresarial durante un proceso de inversión?

**Objetivos y desafíos:**

1. ¿Cuáles son sus principales objetivos financieros a corto, mediano y largo plazo?
2. ¿Cuáles son los desafíos más grandes que enfrenta al tomar decisiones de inversión?
3. ¿Qué información le gustaría tener disponible para tomar decisiones de inversión más informadas?
4. ¿Cómo evalúa el éxito de una inversión?

**Preferencias y comportamientos:**

1. ¿Qué factores le llevan a confiar en una empresa para invertir?
2. ¿Cuáles son sus preferencias de comunicación y cómo le gusta recibir actualizaciones sobre sus inversiones?
3. ¿Cuál es su nivel de tolerancia al riesgo en sus inversiones?
4. ¿Qué actividades o intereses adicionales tiene fuera de sus inversiones financieras?

**Tecnología y preferencias digitales:**

1. ¿Cuáles son sus hábitos de uso de tecnología y medios digitales?
2. ¿Utiliza aplicaciones o plataformas financieras para realizar transacciones o seguimiento de inversiones?
3. ¿Qué funcionalidades considera esenciales en una plataforma de inversión en línea?

</div>

### 2.2.2. Registro de entrevistas

<div align="justify">

Para el registro de entrevistas se realizará una entrevista por segmento, dando un total de 6 entrevistas. Además, el formato de las entrevistas es mp4, cada entrevista es independiente debido a las diferentes preguntas y respuestas dadas por los entrevistados de cada segmento.

**Segmento 1: Contadores financieros trabajando en sell-side en empresas financieras con la necesidad de agilizar el proceso de análisis de debida diligencia**

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"> <div align="center">Entrevista #1<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Guisella</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Díaz</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>51 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Asegurar que el proceso de Due Diligence sea eficiente, seguro y práctico, especialmente en la entrega y manejo de documentos confidenciales.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>La posibilidad de seleccionar una empresa con intenciones maliciosas en el proceso de Due Diligence, lo que puede llevar a la creación de competidores indeseados.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Luis Eduardo Herrera González</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/luis-Guisella.png" alt="Entrevista Guisella Díaz"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>00:00 min - 30:28 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">Guisella Bravo, contadora pública con más de 25 años de experiencia, ha participado en procesos de Due Diligence en roles de Sell-side y Buy-side, utilizando herramientas como Dropbox y Excel. Aunque su conocimiento tecnológico es limitado a estas herramientas y al correo electrónico, considera que la solución propuesta es “muy buena” debido a la falta de alternativas especializadas en la interacción entre empresas compradoras y vendedoras en el Perú. Explica que el proceso de Due Diligence se divide en tres etapas: Entrega de Requerimientos de Información, Due Diligence, y el Informe Final, destacando la importancia de un sistema de Q&A. Señala que la funcionalidad de evitar la descarga de archivos es innecesaria, pero considera útil un análisis financiero dentro del sistema. También destaca la importancia de la seguridad en la gestión de documentos y menciona que seleccionar una empresa con intenciones maliciosas es un riesgo que ha enfrentado, lo que llevó a la creación de un competidor. Finalmente, Guisella se mostró como una persona práctica y lógica, con interés en la eficiencia y seguridad de los procesos. Utiliza un celular Android, Chrome como navegador y Windows en su ambiente laboral.
</td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #2<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Jorge Andres</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Valdivia Moche</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>21 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Lima, Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Está motivado por seguir creciendo de manera profesional en la compañía donde se encuentra realizando sus prácticas profesionales.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>Disconformidad con los procesos y trámites actuales del proceso de Diligencia Debida, y desea encontrar una manera de automatizar o mejorar estos procesos para hacerlos más sencillos.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Diego Anderson Criollo De La Cruz</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/diego-jorge.png"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>30:28 min - 42:10 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">Jorge Valdivia Moche es un estudiante de 9no ciclo de la carrera de Contabilidad en la Universidad Peruana de Ciencias Aplicadas. Actualmente se encuentra realizando practicas profesionales en EY y está trabajando de manera continua en el proceso de Diligencia Debida. Participa activamente en todos los procesos respectivos junto con su equipo de trabajo, sin embargo ha hecho saber su disconformidad con los procesos y tramites que se realizan, haciendonos conocer que le gustaría que hubiera una forma de poder automatizar o mejorar ciertos procesos para hacerlo mucho más sencillos. Nos comentó también que le gustaría una plataforma que permita gestionar de manera óptima todo el proceso de diligenica debida, desde la concepción del proyecto hasta la finalización de este mismo. La motivación más grande que tiene Jorge es poder seguir creciendo de manera profesional en la compañía que se encuentra y a su vez facilitarse las labores que corresponden todo el trabajo que tiene que hacer día a día.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #3<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Patricia</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>González</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>58 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Lima, La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar la eficiencia y precisión del proceso de Due Diligence, especialmente en la organización y análisis de documentos financieros.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>La necesidad de utilizar múltiples herramientas para completar informes y gestionar documentos, lo que puede fragmentar el proceso.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop Windows, Smartphone Apple</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Luis Eduardo Herrera González</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/luis-patricia.png" alt="Entrevista Patrica González"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>42:10 min - 1:07:43 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">Patricia González es contadora pública colegiada, lo cual significa que se dedica a ámbitos financieros de, en su caso, una empresa, que ejerce esta profesión por más de 27 años. Tiene experiencia con el proceso de *Due Diligence* como participante Sell-side en labores pasadas para una empresa trujillana. En su opinión, la propuesta de solución tiene mucho mercado interesado y mucho alcance también. Para ella el proceso de *Due Diligence* se divide en 3 etapas: Obtención de Información de Requerimientos, *Due Diligence* e Informe Final. El *Due Diligence* son Ítems de Información divido en áreas de especialización que suele restringirse a Laboral, Legal, Financiera y Tributaria. Cada Ítem es un contenedor de documentos y se reconocen por número. Cada ítem tiene como atributo el requerimiento completa y formalmente escrito. El proceso de *Due Diligence* no le parece tedioso. Opina que una herramienta para censura es una buena idea para segmentos como el RUC y razones sociales en documentos financieros. Por otro lado, no descarta el uso de herramientas que utiliza en su laptop Windows como Excel, Word hasta PowerPoint para ciertos informes que realiza habitualmente durante la *Due Diligence*. O el uso poco habitual de Drive, una herramienta de fácil acceso a través de Chrome.  Cree que el análisis financiero puede ser apoyado por la misma solución yayudaría mucho. Es favorable su opinión en cuanto a la agregación de la funcionalidad de recolección de documentos en páginas públicas específicas y acreditadas. Por último, nos mencionó que usa un iPhone.
</td>
  </tr>
</tbody>
</table>


**Segmento 2: Inversores trabajando en el Buy-side de empresas que busquen agilizar sus procesos de** ***Due Diligence***

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #1<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Beth</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Oneglio</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>28 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Lima, San Borja</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Optimizar la efectividad y exactitud del procedimiento de Due Diligence, particularmente en la estructuración y revisión de registros financieros.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>La incertidumbre del mercado y la falta de información verdadera y completa para elaborar reportes e investigaciones le dificulta tomar mejores decisiones al momento de invertir.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Computadora Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Abel Andrés Valle Zuta</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/andres-beth.PNG" alt="Entrevista Beth Oneglio"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>1:07:43 min - 1:19:01 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">Beth Oneglio es una empresaria e inversora peruana de 28 años con experiencia moderada en inversiones. Su principal objetivo al invertir es el crecimiento de capital, y se enfoca en invertir en tecnología y energías renovables, prefiriendo empresas emergentes y startups. Beth tiene experiencia en procesos de Due Diligence, valorando la claridad en la información financiera, la viabilidad del modelo de negocio y la solidez del equipo gestor. Considera cruciales los indicadores financieros como EBITDA y los márgenes de utilidad, y se preocupa por los riesgos de liquidez y la volatilidad del mercado. La reputación de la empresa y la diversificación de su cartera son aspectos clave en sus decisiones de inversión. Además, mencionó que utiliza plataformas como Bloomberg para análisis financiero, y prefiere informes interactivos en línea. Valora la transparencia y comunicación regular, y se involucra activamente en sus inversiones. Su horizonte de inversión es a mediano y largo plazo, considerando el entorno económico y la estabilidad política. Se enfrenta a desafíos como la incertidumbre del mercado y la falta de información clara, y busca herramientas de análisis automático y simulaciones para tomar decisiones más informadas. Por último, Beth comentó que prefiere recibir actualizaciones mensuales por correo electrónico, y tiene una tolerancia moderada al riesgo. Fuera de las inversiones, le interesan la sostenibilidad, la tecnología y el deporte. Además, añadió que utiliza aplicaciones financieras diariamente y que considera de gran valor las funcionalidades como análisis en tiempo real y alertas personalizadas.
</td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #2<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Rodrigo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Carrascal</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>29 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Lima, La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Microsoft Edge, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Optimizar la efectividad y exactitud del procedimiento de Due Diligence, particularmente en la estructuración y revisión de registros financieros.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>El requerimiento de usar varias herramientas para generar informes y administrar archivos puede dificultar y desorganizar el flujo de trabajo.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop Windows, Computadora Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Microsoft Edge</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Abel Andrés Valle Zuta</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/AppMoviles-MobiLoom-SW63/Informe/main/Resources/cap2/andres-rodrigo.PNG" alt="Entrevista Rodrigo Carrascal"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>1:19:01 min - 1:34:35 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">En la entrevista logramos conocer a Rodrigo Carrascal, quien es un administrador peruano de 29 años que se dedica a las inversiones. Tiene experiencia con el uso de Due Diligence en inversiones que ha realizado en gran frecuencia a lo largo de su carrera profesional. Su objetivo es poder generar ingresos pasivos, y suele invertir en empresas grandes y consolidadas ya que le brindan mayor seguridad. Rodrigo considera que la propuesta planteada tiene muchas opciones que le facilitaría realizar mejores inversiones y a estar más seguro y tranquilo al invertir. Opina que le gustaría poder acceder a documentos financieros fundamentales y a información sobre la seguridad de las empresas al realizar inversiones y le gustaría poder tener un apartado donde vea las gráficas de cómo se va moviendo el mercado. También indicó que le gustaría que fuera intuitivo para que varias personas puedan usarlo sin la necesidad de ser expertos. También considera que la implementación de una aplicación móvil facilitaría y mejoraría sus experiencias al momento de realizar inversiones, por lo que estaría dispuesto a utilizarlo y recomendarlo.
</td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #3<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Yasmin Susana</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Calderón Céspedes</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>45 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Lima, San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Google Meet</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar la eficiencia y precisión del proceso de Due Diligence, especialmente en la organización y análisis de documentos financieros.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>La necesidad de utilizar múltiples herramientas para completar informes y gestionar documentos, lo que puede fragmentar el proceso.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop Windows, Smartphone Apple</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Hernan Emilio Morales Calderón</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/user-attachments/assets/4459cb2d-4b44-49a9-9eba-8661debce6d6" alt="Entrevista Patrica González"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218227_upc_edu_pe/ETDvbGNsfTtPu3SprXtTpj8BxgjAb-tCNDGqu5BaRT13qg?e=YZdpP5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>1:34:35 min  - 1:48:37 min  </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">Yasmin Calderón es una inversionista de 42 años, residente en Lima, Perú, con más de 15 años de experiencia en el mundo financiero. Como asesora especializada en mercados emergentes y tecnologías disruptivas, realiza inversiones regularmente, enfocándose en el crecimiento de capital, diversificación e impacto social. Su cartera se centra en sectores como tecnología, energías renovables y el sector financiero, equilibrando entre startups con alto potencial y empresas establecidas con un historial sólido. Con una vasta experiencia en procesos de Due Diligence, ha liderado y participado en más de 50 evaluaciones exhaustivas, donde analiza la viabilidad financiera, la estructura de deuda, proyecciones de crecimiento y posibles contingencias legales. Los indicadores financieros que considera cruciales incluyen el EBITDA, la razón de deuda sobre capital, el ROI y la liquidez de la empresa. Valora enormemente la reputación y el historial de la empresa, así como la transparencia y la comunicación constante con los inversores. Prefiere recibir información detallada a través de plataformas en línea y utiliza herramientas como Bloomberg y Reuters para realizar análisis en tiempo real y seguir sus inversiones. Además de su vida profesional, es una apasionada del montañismo y la fotografía de naturaleza, disfrutando de explorar los paisajes peruanos. También participa activamente en iniciativas de conservación ambiental y es una ávida lectora de temas de historia y filosofía. Su enfoque en la tecnología la lleva a utilizar aplicaciones y plataformas digitales diariamente para gestionar tanto su vida personal como profesional, considerando esenciales las funcionalidades de análisis en tiempo real, herramientas de simulación de escenarios y medidas de seguridad robustas en cualquier plataforma de inversión en línea que utilice.
</td>
  </tr>
</tbody>
</table>

</div>

### 2.2.3. Análisis de entrevistas

<div align="justify">

**Segmento de Contadores:**

**Perfil Demográfico**

* Edades: Promedio de 44 años.
* Ubicación Geográfica: Principalmente Lima, Perú.
* Profesión: Contadores Públicos Colegiados.
* Experiencia Laboral: Más de 25 años en promedio.

**Experiencia y Conocimientos en** ***Due Diligence***

* Todos los contadores públicos entrevistados tienen una experiencia considerable en el proceso de *Due Diligence*, con más de 25 años de experiencia en promedio.
* Algunos tienen experiencia en ambos lados de la transacción (sell-side y buy-side).

**Herramientas y Tecnologías utilizadas**

* Todos tienen experiencia con herramientas virtuales como Dropbox y Excel para Due Diligence.
* Valoran las plataformas en la nube que ofrecen seguridad y facilidad de uso para almacenar y analizar documentos financieros.

**Intereses y Necesidades en Plataformas de** ***Due Diligence***

* Consideran importante la automatización del análisis de datos financieros para agilizar el proceso.
* Valorizan la seguridad de los datos financieros sensibles, buscando cifrado de extremo a extremo y medidas de seguridad robustas.
* Prefieren una interfaz intuitiva y fácil de usar para facilitar la navegación y el acceso a la información relevante.
* Algunos encuentran útil la posibilidad de realizar análisis financieros dentro de la plataforma, especialmente al tratar con una gran cantidad de documentos.
* Opinan que la herramienta de recolección de información de la internet sería valiosa para complementar los documentos recibidos.

**Preferencias y Comportamientos**

* Tienen un enfoque meticuloso y analítico en el proceso de Due Diligence.
* Valorizan la eficiencia y la precisión en el análisis de datos financieros.
* Algunos contadores consideran que evitar la descarga de archivos durante el proceso no es necesario, ya que la confidencialidad es clave.
* Prefieren la seguridad en las plataformas de Due Diligence sobre otras funcionalidades menos relevantes.
* Reconocen la importancia de sesiones presenciales en algunos aspectos de su trabajo, aunque la tecnología como realidad virtual es vista como una herramienta complementaria.

**Estadísticas y Porcentajes**

* El 100% de los contadores considera que nuestra propuesta de una plataforma en la nube especializada en Due Diligence es muy favorable y tiene un mercado interesante.
* El 100% valora la seguridad de los datos financieros sensibles como una prioridad.
* El proceso de Due Diligence, según el 100% de los contadores entrevistados, se divide en tres etapas: Entrega de Requerimientos de la Información, Due Diligence y el Informe Final.
* El 100% de los contadores menciona que el Due Diligence se centra en áreas específicas como laboral, legal, financiera y tributaria, dividiendo la información en ítems numerados con requerimientos formales.
* El 100% de los contadores opina que una herramienta de censura para documentos financieros sería beneficiosa, especialmente para información sensible como el RUC y razones sociales.
  Todos los contadores entrevistados consideran que la inclusión de un análisis financiero dentro de la plataforma sería una herramienta útil y novedosa.
* El 100% de los contadores está a favor de la funcionalidad de recolección de documentos desde páginas públicas específicas y acreditadas como una característica valiosa para agilizar el proceso de obtención de información clave.
  Todos los contadores destacan la importancia de la seguridad y confidencialidad de los datos financieros en el proceso de Due Diligence, enfatizando la necesidad de medidas robustas.
* El 100% de los contadores menciona que la plataforma debe ser intuitiva y fácil de usar, considerando la diversidad de usuarios que podrían interactuar con ella.
* En cuanto a los problemas más comunes atendidos durante el Due Diligence, el 100% de los contadores menciona áreas como laboral, legal, financiera y tributaria.
* El 100% los contadores consideran que la eficiencia y efectividad del proceso de Due Diligence son clave para garantizar resultados precisos y completos en las transacciones empresariales.
* El 100% mostraron ser personas racionales a lo largo de la entrevista.

Con base en estas entrevistas, se puede concluir que los contadores públicos entrevistados tienen una vasta experiencia en *Due Diligence*, valoran la eficiencia, la seguridad y la facilidad de uso en una plataforma especializada, y consideran que herramientas como el análisis financiero integrado y la recolección de documentos desde fuentes públicas serían de gran utilidad. Además, se resalta la importancia de la seguridad de los datos, la segmentación por áreas específicas en el *Due Diligence*, y la necesidad de una interfaz intuitiva para facilitar la navegación y el uso de la plataforma.

**Segmento de Inversores:**

**Perfil Demográfico**

* Edades: Promedio de 25 años.
* Ubicación Geográfica: Principalmente Lima, Perú.
* Profesión: Inversores con formación en áreas como Economía, Ingeniería de Sistemas, entre otros.
* Experiencia Laboral: Alrededor de 3 a 8 años en el campo de las finanzas e inversiones.

**Objetivos e Intereses en Inversiones**

* Todos buscan principalmente el crecimiento de capital en sus inversiones.
* Algunos tienen interés en la diversificación de sus carteras y el impacto social de sus inversiones.
* Prefieren empresas nuevas y emergentes, especialmente en sectores tecnológicos y de energía renovable.

**Conocimientos y Participación en** ***Due Diligence***

* Todos tienen experiencia en el proceso de *Due Diligence*, enfocándose en la información financiera y empresarial.
* Participan activamente en el proceso para comprender los riesgos y oportunidades.

**Uso de Herramientas y Plataformas**

* Utilizan herramientas avanzadas de análisis financiero y plataformas en línea para monitorear sus inversiones.
* Valoran la seguridad de los datos financieros y aprecian funcionalidades como el análisis predictivo y simulaciones de escenarios.
* Buscan plataformas con interfaces interactivas y generación de informes eficiente.
* Mencionan el uso de herramientas más cotidianas como Google Drive y DropBox.

**Preferencias y Estrategias de Inversión**

* Prefieren un enfoque activo en la inversión, buscando empresas con modelos de negocio claros y equipos directivos sólidos.
* Su tolerancia al riesgo varía, pero buscan oportunidades con un equilibrio entre riesgo y retorno.
* Valoran la transparencia y la comunicación de las empresas en las que invierten.

**Estadísticas y Porcentajes**

* El 100% tiene experiencia en el proceso de Due Diligence.
* El 66% ha participado en consultoría sell-side para empresas financieras.
* El 100% busca principalmente el crecimiento de capital en sus inversiones.
* El 66% tiene interés en la diversificación de sus carteras.
* El 66% valora el impacto social de sus inversiones.
* El 100% utiliza herramientas avanzadas de análisis financiero y plataformas en línea.
* El 100% valora la seguridad de los datos financieros en las plataformas de Due Diligence.
* El 100% busca interfaces interactivas y generación de informes eficiente.
* El 100% prefiere un enfoque activo en la inversión.
* El 100% busca empresas con modelos de negocio claros y equipos directivos sólidos.
* El 66% tiene una tolerancia moderada al riesgo
* El 100% de los entrevistados mostraron ser personas racionales.

Con base en estas entrevistas, se puede concluir que los inversores tienen un enfoque estratégico en sus inversiones, buscando el crecimiento de capital en empresas con potencial de crecimiento y un impacto social positivo. Valorando la seguridad y las herramientas tecnológicas en el proceso de Due Diligence, buscan plataformas que les proporcionen información clara, análisis efectivo y una gestión eficiente de sus inversiones. También, se destaca su interés en modelos de negocio sólidos y equipos directivos confiables en las empresas en las que invierten.

</div>

## 2.3. *Needfinding*

<div align="justify">

En el cambiante mundo de las transacciones empresariales y la diligencia debida, DiligenceTech se ha comprometido con la excelencia en el servicio a través de un enfoque dedicado para comprender las necesidades específicas de sus usuarios. Esta sección, denominada Needfinding, representa nuestra firme convicción en la importancia de escuchar y comprender a fondo las demandas de nuestros usuarios y clientes.

En DiligenceTech, creemos que el éxito de nuestra plataforma radicará en nuestra capacidad de responder de manera efectiva a las necesidades del mercado. A través de investigaciones detalladas y la recopilación de valiosas entrevistas, hemos desarrollado una profunda comprensión de las necesidades y deseos de los profesionales involucrados en el proceso de *Due Diligence*. Este conocimiento nos impulsa a ofrecer características y funcionalidades que se alinean perfectamente con las expectativas de nuestros usuarios, asegurando que DiligenceTech, se desarrolle con el objetivo de ser una herramienta esencial en la simplificación y mejora del proceso de evaluación empresarial.

En la siguiente sección de Needfinding, profundizaremos en cómo DiligenceTech se compromete a entender y abordar de manera proactiva las cambiantes necesidades de nuestros usuarios, permitiéndoles realizar el proceso de  *Due Diligence* más eficiente y preciso que nunca.

</div>

![Imagen extraída de Canva](Resources/cap2/needfind-baner.png)

### 2.3.1. *User Personas*

<div align="justify">

Presentaremos los User Persona por cada segmento objetivo, en los cuales nos basamos en los usuarios ideales de cada segmento. A continuación, los presentamos:

User Persona 1 - Segmento de Contadores: Marta Díaz

</div>

![Artefacto creado en UXPressia](Resources/cap2/Marta-Díaz.png)

Gráfico sobre la sistema operativo mas usado:
![Creado en Excel](Resources/cap2/contador-sistema-op.png)

Gráfico sobre dispositivo móvil mas usado:
![Creado en Excel](Resources/cap2/contador-disp-movil.png)

Gráfico sobre browser mas usado:
![Creado en Excel](Resources/cap2/contador-browser.png)

User Persona 2 - Segmento de Inversores: Christian Pinto

![Artefacto creado en UXPressia](Resources/cap2/Christian-Pinto.png)

Gráfico sobre la sistema operativo mas usado:
![Creado en Excel](Resources/cap2/inversor-sistema-op.png)

Gráfico sobre dispositivo móvil mas usado:
![Creado en Excel](Resources/cap2/inversor-disp-movil.png)

Gráfico sobre browser mas usado:
![Creado en Excel](Resources/cap2/inversor-browser.png)

### 2.3.2. *User Task Matrix*

User Task Matrix: Marta Díaz y Christian Pinto

Con el fin de elaborar un Task Matrix adecuado para el proyecto, se han considerado los dos segmentos objetivo, producto del análisis de entrevistas, es decir, Contador e Inversionista.



<b>Usuario Contador</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Contador <br>Marta Díaz<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Realizar evaluaciones de riesgos financieros<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Analizar estados financieros de potenciales inversiones<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Exportar informes y resultado de Due Diligence<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Mantener actualizado el registro de Due Diligence<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Revisar informes de Due Diligence<br></td>
    <td>Baja</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Buscar oportunidades de inversión<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Participar en reuniones con startups<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Realizar el seguimiento de inversiones<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Exportar informes para revisión personal<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Colaborar<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
</tbody>
</table>
</div><br><br>

<b>Usuario Inversionista</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Inversionista<br>Christian Pinto<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Realizar evaluaciones de riesgos financieros<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Analizar estados financieros de potenciales inversiones<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Exportar informes y resultado de Due Diligence<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Mantener actualizado el registro de Due Diligence<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Revisar informes de Due Diligence<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Buscar oportunidades de inversión<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar en reuniones con startups<br></td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar el seguimiento de inversiones<br></td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Exportar informes para revisión personal<br></td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Colaborar<br></td>
    <td>Baja</td>
    <td>Baja</td>
  </tr>
</tbody>
</table>
</div>


### 2.3.3. *User Journey Mapping*

User Journey Mapping: Marta Díaz

![Artefacto creado en UXPressia](Resources/cap2/Customer-journey-Marta-Díaz.png)

User Journey Mapping: Christian Pinto

![Artefacto creado en UXPressia](Resources/cap2/Customer-journey-Christian-Pinto.png)

### 2.3.4. *Empathy Mapping*

Empathy Mapping: Marta Díaz

![Artefacto creado en UXPressia](Resources/cap2/empaty-map-Marta-Díaz.png)

Empathy Mapping: Christian Pinto

![Artefacto creado en UXPressia](Resources/cap2/empaty-map-Christian-Pinto.png)

### 2.3.5. *As-is Scenario Mapping*

<div align="justify">

El As-Is Scenario Mapping es una herramienta para identificar los pensamientos que tendrán los usuarios a la hora de utilizar la aplicación actual.

</div>

***As-Is Scenario Map:*** **Contador Financiero**

![Recurso creado en Miro](Resources/cap2/AsIsSM_Cont.png)

***As-Is Scenario Map:*** **Inversor**

![Recurso creado en Miro](Resources/cap2/AsIsSM_Inv.png)


## 2.4. *Requirements specification*

En este capítulo, nos adentramos en la identificación detallada de los requisitos esenciales que permitirán a los usuarios interactuar de manera efectiva y satisfactoria con nuestra aplicación. Es fundamental comprender las necesidades y expectativas de quienes utilizarán nuestra *web application*, lo que nos guiará en la creación de una experiencia de usuario óptima.

![Requirements specification](Resources/cap2/requeriments-specification-baner.png)

### 2.4.1. *To-Be Scenario Mapping*

El *To-Be Scenario Mapping* es una herramienta para identificar cómo se sentirán los usuarios con los nuevos cambios que deberían haber solucionado los problemas planteados en los *As-Is scenario maps.*

![Recurso creado en Miro](Resources/cap2/ToBeSM.png)

### 2.4.2. *User Stories:*

***Epics***

| EP01 (Gestión de Cuentas de Usuario) | Como usuario, quiero registrarme, iniciar sesión y mantener control sobre mi cuenta para acceder de manera segura a la aplicación y gestionar mis datos personales. |
| :-: | :-: |
| US01                                 | Registro de inversor                                                                                                                                                |
| US02                                 | Confirmación de creación de cuenta                                                                                                                                  |
| US03                                 | Verificación de cuenta                                                                                                                                              |
| US04                                 | Registro de empresa                                                                                                                                                 |
| US05                                 | Verificación de cuenta empresa                                                                                                                                      |
| US06                                 | Recuperación de cuenta                                                                                                                                              |


| EP02 (Gestión de Empresas y Solicitudes) | Como usuario, quiero poder gestionar empresas y solicitudes, desde su registro hasta su cierre, para realizar procesos de due diligence de manera efectiva y eficiente. |
| :-: | :-: |
| US07                                     | Visualización de empresas                                                                                                                                               |
| US08                                     | Filtro de empresas                                                                                                                                                      |
| US09                                     | Ordenamiento de empresas                                                                                                                                                |
| US10                                     | Interfaz de búsqueda sencilla                                                                                                                                           |
| US11                                     | Visualización de solicitudes                                                                                                                                            |
| US12                                     | Filtro de solicitudes                                                                                                                                                   |
| US13                                     | Ordenamiento de solicitudes                                                                                                                                             |
| US14                                     | Admisión de solicitudes                                                                                                                                                 |
| US15                                     | Creación de la solicitud                                                                                                                                                |
| US16                                     | Consulta de orden de solicitud                                                                                                                                          |
| US17                                     | Actualizaciones sobre la solicitud                                                                                                                                      |
| US18                                     | Respuesta de solicitud                                                                                                                                                  |
| US19                                     | Razón de la respuesta otorgada                                                                                                                                          |
| US20                                     | Creación de queja                                                                                                                                                       |
| US22                                     | Cierre de solicitud                                                                                                                                                     |


| EP03 (Seguridad y Confidencialidad) | Como usuario, quiero que mis datos y la información de las empresas sean seguros y confidenciales, evitando fugas de seguridad y limitando el acceso no autorizado, para proteger la integridad de la información. |
| :-: | :-: |
| US23                                | Seguridad de entrega                                                                                                                                                                                               |
| US24                                | Limitación al entregar datos                                                                                                                                                                                       |
| US25                                | Alertas de fugas de seguridad                                                                                                                                                                                      |


| EP04 (Análisis Financiero) | Como usuario, quiero realizar análisis financieros con los datos recibidos para evaluar adecuadamente las empresas y tomar decisiones informadas sobre mis inversiones. |
| :-: | :-: |
| US26                       | Visualización de análisis financieros disponibles                                                                                                                       |
| US27                       | Eficacia de los algoritmos de análisis financiero                                                                                                                       |
| US28                       | conclusión del análisis financiero                                                                                                                                      |
| US21                       | Visualización de datos recibidos                                                                                                                                        |


| EP05 (Optimización de la API) | Como desarrollador, quiero implementar funcionalidades de paginación y filtrado en los endpoints de la API para mejorar la eficiencia en la entrega de recursos y optimizar el rendimiento del sistema. |
| :-: | :-: |
| US29                          | RESTful API Registro de usuario                                                                                                                                                                         |
| US30                          | RESTful API Inicio de sesión de usuario                                                                                                                                                                 |
| US31                          | Autenticación basada en token JWT                                                                                                                                                                       |
| US32                          | Recuperación de contraseña                                                                                                                                                                              |
| US33                          | CRUD para recursos principales                                                                                                                                                                          |
| US34                          | Paginación y filtrado de resultados                                                                                                                                                                     |


| EP06 (Landing Page Optimizada) | Como usuario interesado, deseo una landing page intuitiva y optimizada que proporcione información clara y accesible sobre la aplicación, para facilitar la toma de decisiones informadas y la interacción con el equipo de la aplicación. |
| :-: | :-: |
| US35                           | Descubrimiento intuitivo                                                                                                                                                                                                                   |
| US36                           | Contenido informativo                                                                                                                                                                                                                      |
| US37                           | Compatibilidad móvil                                                                                                                                                                                                                       |
| US38                           | Formulario de contacto                                                                                                                                                                                                                     |
| US39                           | Contenido multimedia                                                                                                                                                                                                                       |
| US40                           | Call-to-action claro                                                                                                                                                                                                                       |
| US41                           | Menú superior funcional                                                                                                                                                                                                                    |
| US42                           | Call to action button funcional                                                                                                                                                                                                            |

**User Stories**

<div align="justify">

|User Story ID|Título|Descripción|Criterios de Aceptación|Relación (EPIC ID)|
| :-: | :-: | :-: | :-: | :-: |
|US01|Registro de inversor|**Como** usuario inversionista, **quiero** crear una cuenta con el uso de mi correo electrónico **para** representarme en la aplicación.|<p>**Escenario 1: “Creación de cuenta”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de creación de cuenta,</p><p>**cuando** ingresa una dirección de correo electrónico **y** una contraseña,</p><p>**entonces** se registra con su cuenta y lo redirige a la página de inicio.</p><p></p><p></p><p>**Escenario 2: “Intento de creación de cuenta sin datos”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de creación de cuenta</p><p>**cuando** no ingresa una dirección de correo electrónico ni contraseña</p><p>**entonces** se muestra un mensaje de error indicando que no se han ingresado datos.</p><p></p><p></p><p>**Escenario 3: “Creación de cuenta con un correo ya usado”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de creación de cuenta</p><p>**cuando** ingresa una dirección de correo electrónico y una contraseña,</p><p>**entonces** se muestra un mensaje de error indicando que la dirección de correo ya está siendo usada.</p>|EP01|
|US02|Confirmación de creación de cuenta|**Como** usuario, **quiero** recibir una confirmación de la creación de mi cuenta a través del correo electrónico que proporcioné **para** confirmar la creación de la cuenta.|<p>**Escenario 1: “Correo de confirmación enviado”**</p><p></p><p>**Dado que** el usuario ha creado una cuenta,</p><p>**Cuando** quiere confirmar que su cuenta ha sido creada</p><p>**Entonces** se envía un correo electrónico de confirmación a la dirección proporcionada.</p><p></p><p></p><p>**Escenario 2: “Error al enviar correo de confirmación”**</p><p></p><p>**Dado que** el usuario ha creado una cuenta,</p><p>**Cuando** quiere confirmar si su cuenta ha sido creada,</p><p>**Entonces** no le llega ningún correo de confirmación</p>|EP01|
|US03|Verificación de cuenta|**Como** usuario, **quiero** llenar un formulario en la creación de mi cuenta **para** acreditar mi nombre y mi fiabilidad.|<p>**Escenario 1: “Formulario completado”**</p><p></p><p>**Dado que** el usuario quiere verificar su cuenta</p><p>**Cuando** llena el formulario de verificación con todos sus datos,</p><p>**Entonces** entra al proceso de verificación de cuenta.</p><p></p><p></p><p>**Escenario 2: “Error al completar el formulario”**</p><p></p><p>**Dado que** el usuario quiere verificar su cuenta</p><p>**Cuando** llena el formulario de verificación sin todos sus datos,</p><p>**Entonces** sale un error que pide llenar todos los datos obligatorios.</p>|EP01|
|US04|Registro de empresa|**Como** usuario contador financiero, **quiero** crear una cuenta con el uso de mi correo electrónico empresarial **para** registrar a mi empresa|<p>**Escenario 1: “Registro de empresa”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al formulario de creación de cuenta de empresa,</p><p>**Cuando** ingresa la dirección de correo electrónico proporcionada por la empresa y una contraseña,</p><p>**Entonces** registra a su empresa y es redirigido a la página de inicio.</p><p></p><p></p><p>**Escenario 2: “Registro sin datos”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al formulario de creación de cuenta de empresa,</p><p>**Cuando** no ingresa la dirección de correo electrónico proporcionada por la empresa ni una contraseña,</p><p>**Entonces** aparece un mensaje de error que dice que ingrese los datos.</p><p></p><p></p><p>**Escenario 3: “Registro con contraseña invalida”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al formulario de creación de cuenta de empresa,</p><p>**Cuando** ingresa la dirección de correo electrónico proporcionada por la empresa y una contraseña,</p><p>**Entonces** aparece un mensaje de error que dice que su contraseña es invalida.</p>|EP01|
|US05|Verificación de cuenta de empresa|<p>**Como** usuario contador financiero, **quiero** que se me soliciten los datos de mi empresa **para** verificar la fiabilidad de esta.</p><p></p>|<p>**Escenario 1: “Inicio de proceso de verificación”**</p><p></p><p>**Dado que** el contador financiero quiere verificar la cuenta de la empresa que representa,</p><p>**Cuando** llena el formulario para verificar la cuenta,</p><p>**Entonces** entra al proceso de verificación de cuenta.</p><p></p><p></p><p>**Escenario 2: “Error al completar el formulario”**</p><p></p><p>**Dado que** el contador financiero quiere verificar la cuenta de la empresa que representa,</p><p>**Cuando** llena el formulario para verificar la cuenta sin todos los datos pedidos,</p><p>**Entonces** sale un error que le pide llenar los datos obligatorios.</p>|EP01|
|US06|Recuperación de cuenta|**Como** usuario, **quiero** recuperar mi contraseña por medio del correo vinculado con mi cuenta **para** recuperar el uso de esta.|<p>**Escenario 1: “Solicitud de recuperación de contraseña”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de recuperación de cuenta,</p><p>**Cuando** ingresa su correo electrónico vinculado,</p><p>**Entonces** se genera un enlace de restablecimiento de contraseña único y se envía por correo electrónico a la dirección proporcionada.</p><p></p><p></p><p>**Escenario 2: “Solicitud de recuperación de contraseña con correo no vinculado”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de recuperación de cuenta,</p><p>**Cuando** ingresa un correo electrónico no vinculado,</p><p>**Entonces** aparece un error señalando que el correo ingresado no está vinculado con ninguna cuenta.</p><p></p><p></p><p>**Escenario 3: “Error al enviar correo de recuperación”**</p><p></p><p>**Dado que** el usuario ingresa al formulario de recuperación de cuenta,</p><p>**Cuando** ingresa un correo electrónico vinculado,</p><p>**Entonces** no le llega ningún mensaje al correo proporcionado.</p>|EP01|
|US07|Visualización de proyectos|**Como** usuario, **quiero** visualizar los proyectos creados **para** poder acceder a ellos cuando necesite.|<p>**Escenario 1: “Visualización de proyectos creados”**</p><p></p><p>**Dado que** el usuario a su página principal,</p><p>**Cuando** se desplaza por la sección correspondiente</p><p>**Entonces** se muestra una lista completa y actualizada de todos los proyectos creados.</p><p></p><p></p><p>**Escenario 2: “Carga de proyectos fallida”**</p><p></p><p>**Dado que** el usuario ingresa su página principal,</p><p>**Cuando** se desplaza por la sección correspondiente</p><p>**Entonces** sale error de carga de datos.</p><p></p><p></p><p>**Escenario 3: “Sin proyectos”**</p><p></p><p>**Dado que** el usuario ingresa su página principal,</p><p>**Cuando** se desplaza por la sección correspondiente</p><p>**Entonces** sale un aviso que le indica que no hay proyectos creados.</p>|EP02|
|US08|Filtro de proyectos|**Como** usuario, **quiero** filtrar la lista de proyectos disponibles **para** elegir los que cumplan con mis requisitos.|<p>**Escenario 1: “Filtrado de proyectos”**</p><p></p><p>**Dado que** el usuario desea filtrar la lista de proyectos disponibles,</p><p>**cuando** selecciona los criterios de filtrado deseados,</p><p>**entonces** se muestra una lista de proyectos que cumplen con los criterios de filtrado seleccionados.</p><p></p><p></p><p>**Escenario 2: “Sin resultados de filtrado”**</p><p></p><p>**Dado que** el usuario inversionista desea filtrar la lista de proyectos disponibles</p><p>**cuando** selecciona los criterios de filtrado deseados,</p><p>**entonces** se muestra un mensaje indicando que no se encontraron proyectos que cumplan con los criterios de filtrado seleccionados</p>|EP02|
|US09|Ordenamiento de proyectos|**Como** usuario, **quiero** ordenar la lista de proyectos disponibles **para** elegir las que cumplan con mis requisitos.|<p>**Escenario 1: “Orden por nombre”**</p><p></p><p>**Dado que** el usuario inversionista desea ordenar la lista de proyectos disponibles,</p><p>**cuando** selecciona la opción de ordenar por nombre,</p><p>**entonces** se muestra una lista de proyectos ordenadas alfabéticamente por nombre.</p><p></p><p></p><p>**Escenario 2: “Orden por sector”**</p><p></p><p>**Dado que** el usuario inversionista desea ordenar la lista de proyectos disponibles,</p><p>**cuando** selecciona la opción de ordenar por sector,</p><p>**entonces** se muestra una lista de proyectos ordenadas alfabéticamente por sector.</p><p></p><p></p><p>**Escenario 3: "Error de ordenación"**</p><p></p><p>**Dado que** el usuario inversionista desea ordenar la lista de proyectos disponibles,</p><p>**cuando** intenta ordenarlas,</p><p>**entonces** se muestra un mensaje de error indicando que no se pudo completar la ordenación de los proyectos.</p>|EP02|
|US10|Barra de búsqueda.|**Como** usuario, **quiero** una barra de búsqueda **para** realizar búsquedas más específicas.|<p>**Escenario 1: “Búsqueda de proyectos”**</p><p></p><p>**Dado que** el usuario desea encontrar un proyecto en específico,</p><p>**Cuando** se ingresa el nombre del proyecto en la barra de búsqueda,</p><p>**Entonces** aparece el proyecto que estaba buscando.</p><p></p><p></p><p>**Escenario 2: “Proyecto no encontrado”**</p><p></p><p>**Dado que** el usuario desea encontrar un proyecto en específico,</p><p>**Cuando** se ingresa el nombre del proyecto en la barra de búsqueda,</p><p>**Entonces** aparece un mensaje que menciona que no hay proyectos con el nombre ingresado.</p><p></p><p></p><p>**Escenario 3: “Error de carga”**</p><p></p><p>**Dado que** el usuario desea encontrar un proyecto en específico,</p><p>**Cuando** se ingresa el nombre del proyecto en la barra de búsqueda,</p><p>**Entonces** aparece un mensaje de error que menciona que no se pudo acceder a la base de datos.</p>|EP02|
|US11|Visualización de solicitudes|**Como** usuario contador financiero, **quiero** visualizar las solicitudes que me han llegado **para** acceder a ellas.|<p>**Escenario 1: “Visualización exitosa de solicitudes”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes,</p><p>**cuando** es dirigido al área,</p><p>**entonces** se muestra una lista de las solicitudes recibidas por el contador financiero.</p><p></p><p></p><p>**Escenario 2: “Error al cargar solicitudes”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes,</p><p>**cuando** es dirigido al área,</p><p>**entonces** se muestra un mensaje de error indicando que no se pueden cargar las solicitudes recibidas en este momento.</p>|EP02|
|US12|Filtrado de solicitudes|**Como** usuario contador financiero, **quiero** filtrar las solicitudes recibidas según diferentes criterios **para** mantener un mayor orden.|<p>**Escenario 1: “Filtrado de solicitudes”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes,</p><p>**cuando** selecciona los criterios de filtrado deseados,</p><p>**entonces** se muestra una lista de solicitudes que cumplen con los criterios de filtrado seleccionados.</p><p></p><p></p><p>**Escenario 2: “Sin resultados de filtrado”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes,</p><p>**cuando** selecciona criterios de filtrado que no coinciden con ninguna solicitud en la base de datos,</p><p>**entonces** se muestra un mensaje indicando que no se encontraron solicitudes que cumplan con los criterios de filtrado seleccionados.</p>|EP02|
|US13|Ordenamiento de solicitudes|**Como** usuario contador financiero, **quiero** ordenar las solicitudes recibidas según diferentes criterios **para** mantener un mayor orden.|<p>**Escenario 1: “Ordenación exitosa de solicitudes”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes,</p><p>**cuando** selecciona un criterio de ordenamiento,</p><p>**entonces** se muestra una lista de solicitudes ordenadas según el criterio seleccionado.</p><p></p><p></p><p>**Escenario 2: “Error de ordenación”**</p><p></p><p>**Dado que** el usuario contador financiero ingresa al área de solicitudes</p><p>**cuando** selecciona el criterio de ordenamiento,</p><p>**entonces** se muestra un mensaje de error indicando que no se pudo completar la ordenación de las solicitudes.</p>|EP02|
|US14|Admisión de solicitudes|**Como** usuario contador financiero, **quiero** aceptar o rechazar solicitudes que reciba **para** mantener un control de los datos que estoy permitido entregar.|<p>**Escenario 1: “Admisión de solicitud”**</p><p></p><p>**Dado que** el usuario contador financiero desea aceptar una solicitud recibida,</p><p>**cuando** selecciona la solicitud correspondiente y elige aceptar</p><p>**entonces** se procesa la solicitud y actualiza su estado como aceptada.</p><p></p><p></p><p>**Escenario 2: “Rechazo de solicitud”**</p><p></p><p>**Dado que** el usuario contador financiero desea rechazar una solicitud recibida,</p><p>**cuando** selecciona la solicitud correspondiente y elige rechazar,</p><p>**entonces** se procesa la solicitud y actualiza su estado como rechazada.</p>|EP02|
|US15|Creación de solicitud|**Como** usuario inversionista, **quiero** solicitar los datos que quiero conocer sobre la empresa que elegí **para** realizar los análisis necesarios.|<p>**Escenario 1: “Solicitud de datos”**</p><p></p><p>**Dado que** el usuario inversionista pide datos a una empresa,</p><p>**cuando** selecciona la empresa deseada y especifica los datos que desea obtener,</p><p>**entonces** se registra la solicitud y la envía al contador financiero correspondiente para su procesamiento.</p><p></p><p></p><p>**Escenario 2: “Error al enviar la solicitud”**</p><p></p><p>**Dado que** el usuario inversionista pide datos a una empresa,</p><p>**cuando** selecciona la empresa deseada y especifica los datos que desea obtener,</p><p>**entonces** se muestra un mensaje de error indicando que no se pudo procesar la solicitud en este momento.</p>|EP02|
|US16|Actualizaciones sobre la solicitud|**Como** usuario inversionista, **quiero** recibir notificaciones sobre el estado de mi solicitud **para** mantenerme informado sobre el comportamiento de la empresa.|<p>**Escenario 1: “Notificación de actualización de estado”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado una solicitud,</p><p>**cuando** hay un cambio en el estado de su solicitud,</p><p>**entonces** se envía una notificación al usuario informándole sobre el nuevo estado de su solicitud.</p><p></p><p></p><p>**Escenario 2: “Falta de notificaciones de estado”**</p><p></p><p>**Dado que** el usuario inversionista que ha realizado una solicitud,</p><p>**cuando** hay un cambio en el estado de su solicitud,</p><p>**entonces** no se envía ninguna notificación sobre estado de solicitudes.</p>|EP02|
|US17|Respuesta de solicitud|**Como** usuario inversionista, **quiero** recibir la respuesta sobre mi solicitud realizada **para** conocer si fue aprobada o no.|<p>**Escenario 1: “Recepción de respuesta sobre solicitud”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado una solicitud,</p><p>**cuando** la solicitud ha sido procesada y se ha tomado una decisión de aceptarla o no,</p><p>**entonces** se envía una notificación al usuario informándole sobre el resultado de su solicitud.</p><p></p><p></p><p>**Escenario 2: “Falta de respuesta sobre solicitud”**</p><p></p><p>**Dado que** el usuario inversionista que ha realizado una solicitud,</p><p>**cuando** la solicitud ha sido procesada y se ha tomado una decisión de aceptarla o no,</p><p>**entonces** no se envía una respuesta a pesar de haberse decidido.</p>|EP02|
|US18|Creación de queja|**Como** usuario, **quiero** realizar quejas **para** expresarme sobre mi molestia por cualquier motivo.|<p>**Escenario 1: “Presentación de queja”**</p><p></p><p>**Dado que** el usuario ingresa a la zona de quejas,</p><p>**cuando** presenta una queja,</p><p>**entonces** se registra la queja y notifica al equipo responsable para atenderlo.</p><p></p><p></p><p>**Escenario 2: “Problemas al presentar la queja”**</p><p></p><p>**Dado que** el usuario ingresa a la zona de quejas,</p><p>**cuando** presenta una queja,</p><p>**entonces** se no registra la queja.</p>|EP02|
|US19|Visualización de datos recibidos|**Como** usuario inversionista, **quiero** visualizar los archivos recibidos **para** acceder a los datos que contienen.|<p>**Escenario 1: “Visualización de datos recibidos”**</p><p></p><p>**Dado que** el usuario inversionista tiene los archivos de datos,</p><p>**Cuando** accede a la sección designada de la aplicación para visualizar los archivos de datos,</p><p>**Entonces** se abre un visualizador para el formato del archivo correspondiente.</p><p></p><p></p><p>**Escenario 2: “Error al abrir archivo”**</p><p></p><p>**Dado que** el usuario inversionista tiene los archivos de datos,</p><p>**Cuando** accede a la sección designada de la aplicación para visualizar los archivos de datos,</p><p>**Entonces** aparece un mensaje de error que menciona que no se pudo abrir el archivo.</p>|EP02|
|US20|Cierre de solicitud|**Como** usuario inversionista, **quiero** visualizar los datos obtenidos hasta cerrar y marcar como completada la solicitud **para** tener el tiempo necesario con los datos sin comprometer a la empresa a la cual solicité.|<p>**Escenario 1: “Confirmación de cierre de solicitud”**</p><p></p><p>**Dado que** el usuario inversionista ha terminado su uso con los datos de la empresa,</p><p>**Cuando** decide cerrar la solicitud,</p><p>**Entonces** los datos y archivos se borran y no puede volver a visualizarlos.</p><p></p><p></p><p>**Escenario 2: “Error al cerrar la solicitud”**</p><p></p><p>**Dado que** el usuario inversionista ha terminado su uso con los datos de la empresa,</p><p>**Cuando** decide cerrar la solicitud,</p><p>**Entonces** aparece un mensaje de error que menciona que no se pudo cerrar la solicitud.</p><p></p><p></p><p>**Escenario 3: “Error al eliminar datos”**</p><p></p><p>**Dado que** el usuario inversionista ha terminado su uso con los datos de la empresa,</p><p>**Cuando** decide cerrar la solicitud,</p><p>**Entonces** se marca como cerrada pero no desaparecen los datos.</p>|EP02|
|US21|Recepción de solicitud|**Como** usuario inversionista, **quiero** recibir los datos solicitados **para** verificar que sean los correctos y trabajar con ellos.|<p>**Escenario 1: “Entrega de solicitud”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado una solicitud y ha sido aprobada,</p><p>**Cuando** accede a la sección designada en la aplicación para ver sus solicitudes,</p><p>**Entonces** accede a los documentos que se hayan enviado.</p><p></p><p></p><p>**Escenario 2: “Error de acceso a la entrega de solicitud”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado una solicitud y ha sido aprobada,</p><p>**Cuando** accede a la sección designada en la aplicación para ver sus solicitudes,</p><p>**Entonces** sale un error que menciona que la entrega no se puede abrir.</p><p></p><p></p><p>**Escenario 3: “Entrega vacía”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado una solicitud y ha sido aprobada,</p><p>**Cuando** accede a la sección designada en la aplicación para ver sus solicitudes,</p><p>**Entonces** encuentra que la entrega se encuentra vacía.</p>|EP04|
|US22|Cifrado de datos|**Como** usuario contador financiero, **quiero** la presencia de un sistema de cifrado de datos **para** garantizar la confidencialidad de la compañía que represento.|<p>**Escenario 1: “Entrega segura con cifrado”**</p><p></p><p>**Dado que** el usuario contador financiero desea entregar los datos solicitados,</p><p>**cuando** procede con la entrega de los datos a través del canal designado por la aplicación,</p><p>**entonces** se entregan los datos con un método de cifrado.</p><p></p><p></p><p>**Escenario 2: “Error de cifrado”**</p><p></p><p>**Dado que** el usuario contador financiero desea entregar los datos solicitados,</p><p>**cuando** procede con la entrega de los datos a través del canal designado por la aplicación,</p><p>**entonces** aparece un error mencionando que no se pudo realizar el cifrado de datos.</p><p></p><p></p><p>**Escenario 3: “Error de cifrado”**</p><p></p><p>**Dado que** el usuario contador financiero desea entregar los datos solicitados,</p><p>**cuando** procede con la entrega de los datos a través del canal designado por la aplicación,</p><p>**entonces** se envían los datos sin el cifrado sin que el contador se entere.</p>|EP02|
|US23|Confidencialidad de la entrega|**Como** usuario contador financiero, **quiero** que no se permita descargar ni tomar captura de pantalla de los datos compartidos **para** mantener la confidencialidad de la empresa.|<p>**Escenario 1: “Restricción de descarga de datos”**</p><p></p><p>**Dado que** el usuario contador financiero desea mantener la confidencialidad de los datos compartidos,</p><p>**Cuando** envía los archivos solicitados por algún usuario inversor</p><p>**Entonces** se implementa medidas de seguridad que impiden la descarga de los archivos abiertos.</p><p></p><p></p><p>**Escenario 2: “Restricción de captura de pantalla”**</p><p></p><p>**Dado que** el usuario contador financiero desea mantener la confidencialidad de los datos compartidos,</p><p>**Cuando** envía los archivos solicitados por algún usuario inversor</p><p>**Entonces** se implementa medidas de seguridad que impiden la captura de pantalla de los archivos abiertos.</p><p></p><p></p><p>**Escenario 3: “Error de descarga no restringida”**</p><p></p><p>**Dado que** el usuario contador financiero desea mantener la confidencialidad de los datos compartidos,</p><p>**Cuando** envía los archivos solicitados por algún usuario inversor</p><p>**Entonces** no se implementan medidas de seguridad que impidan la descarga de los archivos abiertos.</p><p></p><p></p><p>**Escenario 4: “Error de captura de pantalla habilitada”**</p><p></p><p>**Dado que** el usuario contador financiero desea mantener la confidencialidad de los datos compartidos,</p><p>**Cuando** envía los archivos solicitados por algún usuario inversor</p><p>**Entonces** no se implementan medidas de seguridad que impidan la captura de pantalla de los archivos abiertos.</p>|EP03|
|US24|Alertas de fugas de seguridad|**Como** usuario contador financiero, **quiero** recibir alertas de violaciones de seguridad **para** informar a la empresa sobre el problema.|<p>**Escenario 1: “Recepción de alerta de violación de seguridad”**</p><p></p><p>**Dado que** el usuario contador financiero desea estar al tanto de posibles violaciones de seguridad,</p><p>**cuando** se detecta una actividad sospechosa o una violación de seguridad en la aplicación,</p><p>**entonces** se envía una alerta inmediata al usuario contador financiero, notificándole sobre el problema y proporcionando detalles pertinentes para que pueda informar rápidamente a la empresa y tomar las medidas necesarias para abordar la situación.</p><p></p><p></p><p>**Escenario 2: “Falta de alertas de violaciones de seguridad”**</p><p></p><p>**Dado que** el usuario contador financiero desea estar al tanto de posibles violaciones de seguridad,</p><p>**cuando** ocurre una violación de seguridad, pero se no envía ninguna alerta al usuario,</p><p>**entonces** no es consciente del incidente y la empresa puede no ser informada oportunamente, lo que aumenta el riesgo de daños adicionales o pérdida de datos.</p>|EP03|
|US25|Visualización de análisis financieros disponibles|**Como** usuario inversionista, **quiero** disponer de una gama de análisis financieros **para** realizar el proceso de Due Diligence sin problemas.|<p>**Escenario 1: “Análisis financieros”**</p><p></p><p>**Dado que** el usuario inversionista desea utilizar los análisis financieros disponibles,</p><p>**cuando** accede a la sección correspondiente en la aplicación,</p><p>**entonces** se muestra una lista completa de los análisis financieros disponibles.</p><p></p><p></p><p>**Escenario 2: “Error al mostrar análisis financieros”**</p><p></p><p>**Dado que** el usuario inversionista desea revisar los análisis financieros disponibles,</p><p>**cuando** accede a la sección correspondiente en la aplicación,</p><p>**entonces** no se muestra ningún análisis financiero.</p><p></p><p></p><p>**Escenario 3: “Error al seleccionar análisis financiero”**</p><p></p><p>**Dado que** el usuario inversionista desea seleccionar algún análisis financiero disponible,</p><p>**cuando** intenta ingresar a alguno de los disponibles</p><p>**entonces** aparece un mensaje de error que menciona que no se puede ingresar al análisis seleccionado.</p>|EP03|
|US26|Eficacia de los algoritmos de análisis financiero|<p>**Como** usuario inversionista, **quiero** realizar cualquier análisis financiero disponible de manera rápida y sencilla **para** agilizar el proceso de evaluación.</p><p></p>|<p>**Escenario 1: “Eficacia de análisis financiero”**</p><p></p><p>**Dado que** el usuario inversionista desea realizar un análisis financiero,</p><p>**cuando** accede a la herramienta de análisis financiero disponible en la aplicación,</p><p>**entonces** se ejecuta de acuerdo con las expectativas sin demorarse ni dar resultados erróneos.</p><p></p><p></p><p>**Escenario 2: “Problemas de eficacia en la herramienta de análisis financiero”**</p><p></p><p>**Dado que** el usuario inversionista desea realizar un análisis financiero,</p><p>**cuando** intenta utilizar la herramienta de análisis financiero</p><p>**entonces** se ejecuta con problemas tardándose y dando resultados erróneos.</p><p></p><p></p><p>**Escenario 3: “Error de ejecución”**</p><p></p><p>**Dado que** el usuario inversionista desea realizar un análisis financiero,</p><p>**cuando** intenta utilizar la herramienta de análisis financiero</p><p>**entonces** no se ejecuta y da error.</p>|EP04|
|US27|Informe de análisis financiero|**Como** usuario inversionista, **quiero** recibir un informe en base a los análisis que se realizaron **para** tener una segunda opinión o utilizarlo como un informe final.|<p>**Escenario 1: “Veredicto claro y fundamentado”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado análisis utilizando la aplicación,</p><p>**cuando** finaliza los análisis financieros,</p><p>**entonces** se proporciona un veredicto claro y fundamentado basado en los resultados de los análisis.</p><p></p><p></p><p>**Escenario 2: “Falta de veredicto o información insuficiente”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado análisis utilizando la aplicación,</p><p>**cuando** finaliza los análisis financieros,</p><p>**entonces** se entrega un informe con información vaga y sin sentido.</p><p></p><p></p><p>**Escenario 3: “Error al generar el informe”**</p><p></p><p>**Dado que** el usuario inversionista ha realizado análisis utilizando la aplicación,</p><p>**cuando** finaliza los análisis financieros,</p><p>**entonces** produce un error y no se genera ningún informe.</p>|EP04|
|US28|RESTful API – Registro de usuario|**Como** desarrollador, **quiero** implementar un endpoint de registro de usuario **para** permitir que los usuarios se registren en la aplicación mediante la API RESTful.|<p>**Escenario 1: “Registro exitoso”**</p><p></p><p>**Dado que** el usuario que desea registrarse en la aplicación a través de la API RESTful,</p><p>**cuando** envía una solicitud de registro con la información requerida al endpoint correspondiente,</p><p>**entonces** se procesa la solicitud y se crea la cuenta</p><p></p><p></p><p>**Escenario 2: “Fallo en el registro”**</p><p></p><p>**Dado que** el usuario que intenta registrarse en la aplicación a través de la API RESTful,</p><p>**cuando** envía una solicitud de registro al endpoint correspondiente, **entonces** no se registra la solicitud y regresa un mensaje de error.</p>|EP04|
|US29|RESTful API – Inicio de sesión de usuario|**Como** desarrollador, **quiero** implementar un endpoint de inicio de sesión **para** permitir que los usuarios accedan a sus cuentas mediante la API RESTful.|<p>**Escenario 1: “Inicio de sesión exitoso”**</p><p></p><p>**Dado que** el usuario que desea iniciar,</p><p>**cuando** envía una solicitud de inicio de sesión con las credenciales al endpoint correspondiente,</p><p>**entonces** se autentica al usuario, genera un token de acceso válido y devuelve una respuesta junto con el token de acceso para la sesión.</p><p></p><p></p><p>**Escenario 2: “Fallo en el inicio de sesión”**</p><p></p><p>**Dado que** el usuario que intenta iniciar sesión en la aplicación a través de la API RESTful,</p><p>**cuando** envía una solicitud de inicio de sesión al endpoint correspondiente con credenciales incorrectas</p><p>**entonces** se devuelve un mensaje de error indicando que el inicio de sesión ha fallado.</p>|EP05|
|US30|Autenticación basada en token JWT|**Como** desarrollador, **quiero** implementar la funcionalidad de autenticación basada en el token JWT **para** mejorar la seguridad de la API.|<p>**Escenario 1: “Generación de token JWT”**</p><p></p><p>**Dado que** el usuario autenticado desea acceder a recursos protegidos en la API RESTful,</p><p>**cuando** se valida las credenciales,</p><p>**entonces** se genera un token JWT válido que contiene la información de autenticación y tiene una fecha de expiración adecuada.</p><p></p><p></p><p>**Escenario 2: “Token JWT inválido”**</p><p></p><p>**Dado que** el usuario que intenta acceder a recursos protegidos en la API RESTful,</p><p>**cuando** incluye un token JWT inválido en el encabezado de autorización de la solicitud,</p><p>**entonces** se rechaza la solicitud indicando que la autenticación ha fallado.</p>|EP05|
|US31|Recuperación de contraseña|**Como** desarrollador, **quiero** implementar un endpoint de recuperación de contraseña **para** permitir que los usuarios restablezcan sus contraseñas mediante la API RESTful.|<p>**Escenario 1: “Solicitud de restablecimiento de contraseña”**</p><p></p><p>**Dado que** el usuario olvidó su contraseña y desea restablecerla,</p><p>**cuando** envía una solicitud POST al endpoint de recuperación de contraseña con su dirección de correo electrónico registrada,</p><p>**entonces** se verifica la existencia del correo electrónico en la base de datos, genera un token de restablecimiento de contraseña único asociado a la cuenta y lo envía al correo asociado de la cuenta.</p><p></p><p></p><p>**Escenario 2: “Error en solicitud de restablecimiento de contraseña”**</p><p></p><p>**Dado que** el usuario olvidó su contraseña y desea restablecerla,</p><p>**cuando** envía una solicitud POST al endpoint de recuperación de contraseña con su dirección de correo electrónico registrada,</p><p>**entonces** se verifica la existencia del correo electrónico en la base de datos, pero no obtiene respuesta.</p>|EP05|
|US32|CRUD para recursos principales|**Como** desarrollador, **quiero** implementar endpoint CRUD **para** la gestión de recursos principales de la aplicación.|<p>**Escenario 1: “Creación de recursos”**</p><p></p><p>**Dado que** el usuario que desea crear un nuevo recurso en la aplicación,</p><p>**cuando** envía una solicitud POST al endpoint correspondiente con los datos del nuevo recurso,</p><p>**entonces** se procesa la solicitud y crea el recurso en la base de datos.</p><p></p><p></p><p>**Escenario 2: “Error en la creación de recursos”**</p><p></p><p>**Dado que** el usuario que desea crear un nuevo recurso en la aplicación,</p><p>**cuando** envía una solicitud POST al endpoint correspondiente con los datos del nuevo recurso,</p><p>**entonces** no se crea el recurso solicitado.</p><p></p><p></p><p>**Escenario 3: “Eliminación de recursos”**</p><p></p><p>**Dado que** el usuario que desea eliminar un nuevo recurso en la aplicación,</p><p>**cuando** envía una solicitud POST al endpoint correspondiente con los datos del recurso,</p><p>**entonces** se procesa la solicitud y elimina el recurso en la base de datos.</p><p></p><p></p><p>**Escenario 4: “Error en la eliminación de recursos”**</p><p></p><p>**Dado que** el usuario que desea crear un nuevo recurso en la aplicación,</p><p>**cuando** envía una solicitud POST al endpoint correspondiente con los datos del nuevo recurso,</p><p>**entonces** no se elimina el recurso solicitado.</p>|EP05|
|US33|Landing page organizada|**Como** visitante de la landing page, **quiero** encontrar una navegación intuitiva que me permita acceder fácilmente a la información **para** informarme sobre sus características.|<p>**Escenario 1: “Organización correcta e intuitiva”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** accedo a la página principal,</p><p>**entonces** encuentro todas las funcionalidades y servicios que ofrece sin problemas.</p><p></p><p></p><p>**Escenario 2: “Organización no intuitiva”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** accedo a la página principal no entiendo nada.</p><p>**entonces** me siento frustrado y es menos probable que continúe explorando la página o considere utilizar la aplicación.</p>|EP05|
|US34|Contenido de la landing page|**Como** visitante de la landing page, **quiero** encontrar contenido detallado y fácil de entender sobre las funcionalidades y beneficios de la aplicación **para** tomar una decisión informada sobre su uso.|<p>**Escenario 1: “Contenido claro”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** navega por la landing page</p><p>**entonces** encuentra contenido detallado y fácil de entender que describe claramente las funcionalidades y beneficios de la aplicación.</p><p></p><p></p><p>**Escenario 2: “Contenido confuso o insuficiente”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** navega por la landing page,</p><p>**entonces** no encuentra información relevante o suficiente.</p>|EP05|
|US35|Landing page - Compatibilidad móvil|**Como** visitante de la landing page, **quiero** que sea responsiva **para** utilizarla en cualquier dispositivo.|<p>**Escenario 1: “Compatibilidad con**</p><p>**dispositivos móviles”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** visita la landing page de la aplicación desde su dispositivo móvil,</p><p>**entonces** navega la landing page sin problemas.</p><p></p><p></p><p>**Escenario 2: “Problemas de visualización o navegación”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** visita la landing page de la aplicación desde su dispositivo móvil,</p><p>**entonces** encuentra problemas de visualización o navegación.</p>|EP06|
|US36|Landing page - Formulario de contacto|**Como** visitante de la landing page, **quiero** encontrar un formulario de contacto en la landing page **para** poder comunicarme con el equipo de la aplicación.|<p>**Escenario 1: “Acceso al formulario de contacto”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** quiera contactarse con el equipo de la aplicación,</p><p>**entonces** encuentra un formulario de contacto.</p><p></p><p></p><p>**Escenario 2: “Falta de formulario de contacto”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** quiera contactarse con el equipo de la aplicación,</p><p>**entonces** no encuentra un formulario de contacto o cualquier medio claro para comunicarme con el equipo de la aplicación.</p>|EP06|
|US37|Landing page - Contenido multimedia|**Como** visitante de la landing page, **quiero** encontrar contenido multimedia **para** obtener más información.|<p>**Escenario 1: “Contenido multimedia disponible”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** navega por la página,</p><p>**entonces** encuentra contenido multimedia que ilustran las características y beneficios de la aplicación.</p><p></p><p></p><p>**Escenario 2: “Falta de contenido multimedia”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** navega por la página,</p><p>**entonces** no encuentra ningún contenido multimedia.</p>|EP06|
|US38|Landing page - Call-to-action|**Como** visitante de la landing page, **quiero** encontrar call-to-action´s **para** solicitar una demo.|<p>**Escenario 1: "call-to-action presente"**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** quiera descargar la demo de la aplicación,</p><p>**entonces** encuentra el call-to-action visible.</p><p></p><p></p><p>**Escenario 2: "Falta de call-to-action´s"**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page,</p><p>**cuando** quiera descargar la demo de la aplicación,</p><p>**entonces** no encuentra ningún call-to-action.</p>|EP06|
|US39|Landing page - menú superior|**Como** visitante de la landing page, **quiero** un menú superior, **para** desplazarme rápidamente a través de la landing page.|<p>**Escenario 1: “Menú superior”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page.</p><p>**Cuando** quiere visitar otros segmentos de la página y utiliza el menú superior.</p><p>**Entonces** se desplaza a otros segmentos.</p><p></p><p></p><p>**Escenario 2: “Error de vinculo menú superior”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page.</p><p>**Cuando** quiere visitar otros segmentos de la página y utiliza el menú superior.</p><p>**Entonces** no ocurre nada.</p><p></p><p></p><p>**Escenario 3: “Vinculo equivocado en menú superior”**</p><p></p><p>**Dado que** el visitante se encuentra en la landing page.</p><p>**Cuando** quiere visitar otros segmentos de la página y utiliza el menú superior.</p><p>**Entonces** lo lleva a un segmento incorrecto.</p>|EP06|
|US40|Ingresar proyecto|**Como** usuario, **quiero** ingresar a los proyectos creados **para** acceder a su contenido.|<p>**Escenario 1: “Ingreso de proyecto”**</p><p></p><p>**Dado que** el usuario selecciona un proyecto existente.</p><p>**Cuando** intenta ingresar a su contenido.</p><p>**Entonces** ingresa al proyecto.</p><p></p><p></p><p>**Escenario 2: “Error en ingreso”**</p><p></p><p>**Dado que** el usuario selecciona un proyecto existente.</p><p>**Cuando** intenta ingresar a su contenido.</p><p>**Entonces** un error impide que ingrese al proyecto.</p>|EP06|
|US41|Explorar information ítems|**Como** usuario, **quiero** visualizar los information ítems que contengan los proyectos **para** ingresar a su contenido.|<p>**Escenario 1: “Visualizar information item”**</p><p></p><p>**Dado que** el usuario ingresa a un proyecto.</p><p>**Cuando** quiere visualizar los information item que contiene el proyecto.</p><p>**Entonces** se cargan y los puede visualizar.</p><p></p><p></p><p>**Escenario 2: “Error de carga de information item”**</p><p></p><p>**Dado que** el usuario ingresa a un proyecto.</p><p>**Cuando** quiere visualizar los information item que contiene el proyecto.</p><p>**Entonces** se produce un error de carga y no logra ver los information items.</p><p></p><p></p><p>**Escenario 3: “Proyecto vacío”**</p><p></p><p>**Dado que** el usuario ingresa a un proyecto.</p><p>**Cuando** quiere visualizar los information item que contiene el proyecto.</p><p>**Entonces** no encuentra ningún information item debido a que no se ha creado ninguno aún.</p>|EP06|
|US42|Crear documento en information item como Sell Side Agent|**Como** usuario contador financiero **quiero** crear documentos dentro de los information ítems **para** compartirlos con el Buy Side.|<p>**Escenario 1: “Creación de documento”**</p><p></p><p>**Dado que** el usuario contador financiero crea un documento en el information item.</p><p>**Cuando** ingresa los inputs que corresponden.</p><p>**Entonces** se crea un documento.</p><p></p><p></p><p>**Escenario 2: “Error en la creación de documento”**</p><p></p><p>**Dado que** el usuario contador financiero crea un documento en el information item.</p><p>**Cuando** ingresa los inputs que corresponden.</p><p>**Entonces** se produce un error y no se crea un documento.</p>|EP06|
|US43|Crear information item como Buy Side Agent|**Como** usuario inversionista **quiero** crear information ítems **para** compartirlos con el Sell Side.|<p>**Escenario 1: “Creación de information item”**</p><p></p><p>**Dado que** el usuario inversionista crea un un information item.</p><p>**Cuando** ingresa los inputs que corresponden.</p><p>**Entonces** se crea el information item.</p><p></p><p></p><p>**Escenario 2: “Error en la creación de information item”**</p><p></p><p>**Dado que** el usuario inversionista crea un information item.</p><p>**Cuando** ingresa los inputs que corresponden.</p><p>**Entonces** se produce un error y no se crea el information item.</p>||
|US44|Visualizar preguntas de proyecto|**Como** usuario, **quiero** visualizar las preguntas del proyecto **para** interactuar e ingresar a ellas.|<p>**Escenario 1: “Visualizar preguntas”**</p><p></p><p>**Dado que** el usuario se encuentra en la zona de preguntas de proyecto.</p><p>**Cuando** quiere visualizar las preguntas que se encuentren.</p><p>**Entonces** aparecen las preguntas anteriormente realizadas.</p><p></p><p></p><p>**Escenario 2: “Error de carga”**</p><p></p><p>**Dado que** el usuario se encuentra en la zona de preguntas de proyecto.</p><p>**Cuando** quiere visualizar las preguntas que se encuentren.</p><p>**Entonces** aparece un mensaje de error de carga de datos.</p><p></p><p></p><p>**Escenario 3: “Sin preguntas previas”**</p><p>**Dado que** el usuario se encuentra en la zona de preguntas de proyecto.</p><p>**Cuando** quiere visualizar las preguntas que se encuentren.</p><p>**Entonces** no aparece ninguna pregunta pues no se han creado aún.</p>||
|US45|⁠Crear pregunta como Buy Side Agent|**Como** usuario inversor, **quiero** crear preguntas **para** intercambiar dudas con el Sell Side.|<p>**Escenario 1: “Creación de pregunta”**</p><p></p><p>**Dado que** el usuario inversor crea una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos.</p><p>**Entonces** se sube su pregunta.</p><p></p><p></p><p>**Escenario 2: “Error en la creación de pregunta”**</p><p></p><p>**Dado que** el usuario inversor crea una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos.</p><p>**Entonces** ocurre un error y no se sube la pregunta.</p><p></p><p></p><p>**Escenario 3: “Pregunta vacía”**</p><p></p><p>**Dado que** el usuario inversor crea una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos, pero no pone ningún contenido.</p><p>**Entonces** se le pide ingresar una cantidad de texto mínimo en la pregunta.</p>||
|US46|Crear respuesta como Sell Side Agent|**Como** usuario contador financiero, **quiero** responder a las preguntas recibidas por el lado Buy Side **para** resolver cualquiera de sus dudas.|<p>**Escenario 1: “Creación de respuesta”**</p><p></p><p>**Dado que** el usuario contador financiero responde una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos.</p><p>**Entonces** se sube su respuesta</p><p></p><p></p><p>**Escenario 2: “Error en la creación de respuesta”**</p><p></p><p>**Dado que** el usuario contador financiero responde una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos.</p><p>**Entonces** ocurre un error y no se sube la respuesta.</p><p></p><p></p><p>**Escenario 3: “Respuesta vacía”**</p><p></p><p>**Dado que** el usuario contador financiero responde una nueva pregunta.</p><p>**Cuando** ingresa todos los inputs requeridos, pero no pone ningún contenido.</p><p>**Entonces** se le pide ingresar una cantidad de texto mínimo en la pregunta.</p>||

</div>

### 2.4.3. *Impact Mapping*

El impact map es una herramienta estratégica que permite identificar de manera precisa las características de una aplicación que pueden ser utilizadas o mejoradas para cumplir con un objetivo empresarial específico. Al partir del objetivo clave, se desglosan los comportamientos necesarios de los usuarios, se definen las acciones que deben realizar en la aplicación, se identifican las características necesarias para habilitar esas acciones, se evalúa el impacto potencial de cada característica en el logro del objetivo, y finalmente se crea un plan de acción detallado que guía el desarrollo y mejora continua de la aplicación, alineando así las acciones de los usuarios con los objetivos estratégicos de la empresa.

![Artefacto creado en UXPressia](Resources/cap2/impact-map.png)

### 2.4.4. *Product Backlog*

Utilizaremos la escala de Fibonacci (1/2/3/5/8/13/21) para realizar este valorización de User Stories por Story Points.

|**# Orden**|**User Story ID**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8 / 13 /…)**|
| :-: | :-: | :-: | :-: | :-: |
|1|US01|Registro de inversor|**Como** usuario inversionista, **quiero** crear una cuenta con el uso de mi correo electrónico **para** representarme en la aplicación.|3|
|2|US02|Confirmación de creación de cuenta|**Como** usuario, **quiero** recibir una confirmación de la creación de mi cuenta a través del correo electrónico que proporcioné **para** confirmar la creación de la cuenta.|2|
|3|US03|Verificación de cuenta|**Como** usuario, **quiero** llenar un formulario en la creación de mi cuenta **para** acreditar mi nombre y mi fiabilidad.|3|
|4|US04|Registro de empresa|**Como** usuario contador financiero, **quiero** crear una cuenta con el uso de mi correo electrónico empresarial **para** registrar a mi empresa|3|
|5|US05|Verificación de cuenta de empresa|<p>**Como** usuario contador financiero, **quiero** que se me soliciten los datos de mi empresa **para** verificar la fiabilidad de esta.</p><p></p>|3|
|6|US06|Recuperación de cuenta|**Como** usuario, **quiero** recuperar mi contraseña por medio del correo vinculado con mi cuenta **para** recuperar el uso de esta.|5|
|7|US07|Visualización de proyectos|**Como** usuario, **quiero** visualizar los proyectos creados **para** poder acceder a ellos cuando necesite.|3|
|8|US08|Filtro de proyectos|**Como** usuario, **quiero** filtrar la lista de proyectos disponibles **para** elegir los que cumplan con mis requisitos.|5|
|9|US09|Ordenamiento de proyectos|**Como** usuario, **quiero** ordenar la lista de proyectos disponibles **para** elegir las que cumplan con mis requisitos.|5|
|10|US10|Barra de búsqueda.|**Como** usuario, **quiero** una barra de búsqueda **para** realizar búsquedas más específicas.|5|
|11|US11|Visualización de solicitudes|**Como** usuario contador financiero, **quiero** visualizar las solicitudes que me han llegado **para** acceder a ellas.|8|
|12|US12|Filtrado de solicitudes|**Como** usuario contador financiero, **quiero** filtrar las solicitudes recibidas según diferentes criterios **para** mantener un mayor orden.|5|
|13|US13|Ordenamiento de solicitudes|**Como** usuario contador financiero, **quiero** ordenar las solicitudes recibidas según diferentes criterios **para** mantener un mayor orden.|5|
|14|US14|Admisión de solicitudes|**Como** usuario contador financiero, **quiero** aceptar o rechazar solicitudes que reciba **para** mantener un control de los datos que estoy permitido entregar.|5|
|15|US15|Creación de solicitud|**Como** usuario inversionista, **quiero** solicitar los datos que quiero conocer sobre la empresa que elegí **para** realizar los análisis necesarios.|8|
|16|US16|Actualizaciones sobre la solicitud|**Como** usuario inversionista, **quiero** recibir notificaciones sobre el estado de mi solicitud **para** mantenerme informado sobre el comportamiento de la empresa.|5|
|17|US17|Respuesta de solicitud|**Como** usuario inversionista, **quiero** recibir la respuesta sobre mi solicitud realizada **para** conocer si fue aprobada o no.|5|
|18|US18|Creación de queja|**Como** usuario, **quiero** realizar quejas **para** expresarme sobre mi molestia por cualquier motivo.|5|
|19|US19|Visualización de datos recibidos|**Como** usuario inversionista, **quiero** visualizar los archivos recibidos **para** acceder a los datos que contienen.|5|
|20|US20|Cierre de solicitud|**Como** usuario inversionista, **quiero** visualizar los datos obtenidos hasta cerrar y marcar como completada la solicitud **para** tener el tiempo necesario con los datos sin comprometer a la empresa a la cual solicité.|3|
|21|US21|Recepción de solicitud|**Como** usuario inversionista, **quiero** recibir los datos solicitados **para** verificar que sean los correctos y trabajar con ellos.|5|
|22|US22|Cifrado de datos|**Como** usuario contador financiero, **quiero** la presencia de un sistema de cifrado de datos **para** garantizar la confidencialidad de la compañía que represento.|8|
|23|US23|Confidencialidad de la entrega|**Como** usuario contador financiero, **quiero** que no se permita descargar ni tomar captura de pantalla de los datos compartidos **para** mantener la confidencialidad de la empresa.|8|
|24|US24|Alertas de fugas de seguridad|**Como** usuario contador financiero, **quiero** recibir alertas de violaciones de seguridad **para** informar a la empresa sobre el problema.|8|
|25|US25|Visualización de análisis financieros disponibles|**Como** usuario inversionista, **quiero** disponer de una gama de análisis financieros **para** realizar el proceso de Due Diligence sin problemas.|8|
|26|US26|Eficacia de los algoritmos de análisis financiero|<p>**Como** usuario inversionista, **quiero** realizar cualquier análisis financiero disponible de manera rápida y sencilla **para** agilizar el proceso de evaluación.</p><p></p>|21|
|27|US27|Informe de análisis financiero|**Como** usuario inversionista, **quiero** recibir un informe en base a los análisis que se realizaron **para** tener una segunda opinión o utilizarlo como un informe final.|13|
|28|US28|RESTful API – Registro de usuario|**Como** desarrollador, **quiero** implementar un endpoint de registro de usuario **para** permitir que los usuarios se registren en la aplicación mediante la API RESTful.|8|
|29|US29|RESTful API – Inicio de sesión de usuario|**Como** desarrollador, **quiero** implementar un endpoint de inicio de sesión **para** permitir que los usuarios accedan a sus cuentas mediante la API RESTful.|5|
|30|US30|Autenticación basada en token JWT|**Como** desarrollador, **quiero** implementar la funcionalidad de autenticación basada en el token JWT **para** mejorar la seguridad de la API.|5|
|31|US31|Recuperación de contraseña|**Como** desarrollador, **quiero** implementar un endpoint de recuperación de contraseña **para** permitir que los usuarios restablezcan sus contraseñas mediante la API RESTful.|5|
|32|US32|CRUD para recursos principales|**Como** desarrollador, **quiero** implementar endpoint CRUD **para** la gestión de recursos principales de la aplicación.|13|
|33|US33|Landing page organizada|**Como** visitante de la landing page, **quiero** encontrar una navegación intuitiva que me permita acceder fácilmente a la información **para** informarme sobre sus características.|8|
|34|US34|Contenido de la landing page|**Como** visitante de la landing page, **quiero** encontrar contenido detallado y fácil de entender sobre las funcionalidades y beneficios de la aplicación **para** tomar una decisión informada sobre su uso.|5|
|35|US35|Landing page - Compatibilidad móvil|**Como** visitante de la landing page, **quiero** que sea responsiva **para** utilizarla en cualquier dispositivo.|8|
|36|US36|Landing page - Formulario de contacto|**Como** visitante de la landing page, **quiero** encontrar un formulario de contacto en la landing page **para** poder comunicarme con el equipo de la aplicación.|5|
|37|US37|Landing page - Contenido multimedia|**Como** visitante de la landing page, **quiero** encontrar contenido multimedia **para** obtener más información.|3|
|38|US38|Landing page - Call-to-action|**Como** visitante de la landing page, **quiero** encontrar call-to-action´s **para** solicitar una demo.|3|
|39|US39|Landing page - menú superior|**Como** visitante de la landing page, **quiero** un menú superior, **para** desplazarme rápidamente a través de la landing page.|3|
|40|US40|Ingresar proyecto|**Como** usuario, **quiero** ingresar a los proyectos creados **para** acceder a su contenido.|13|
|41|US41|Explorar information ítems|**Como** usuario, **quiero** visualizar los information ítems que contengan los proyectos **para** ingresar a su contenido.|13|
|42|US42|Crear documento en information item como Sell Side Agent|**Como** usuario contador financiero **quiero** crear documentos dentro de los information ítems **para** compartirlos con el Buy Side.|8|
|43|US43|Crear information item como Buy Side Agent|**Como** usuario inversionista **quiero** crear information ítems **para** compartirlos con el Sell Side.|13|
|44|US44|Visualizar preguntas de proyecto|**Como** usuario, **quiero** visualizar las preguntas del proyecto **para** interactuar e ingresar a ellas.|21|
|45|US45|⁠Crear pregunta como Buy Side Agent|**Como** usuario inversor, **quiero** crear preguntas **para** intercambiar dudas con el Sell Side.|13|
|46|US46|Crear respuesta como Sell Side Agent|**Como** usuario contador financiero, **quiero** responder a las preguntas recibidas por el lado Buy Side **para** resolver cualquiera de sus dudas.|13|

### [Conclusiones](#conclusiones-1)
### [Bibliografía](#bibliografia-1)
### [Anexos](#anexos-1)

