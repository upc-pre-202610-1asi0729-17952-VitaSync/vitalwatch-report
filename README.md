<div align="center">
<img src="Resources/UPC_logo.png"></img><br>


<h3>Universidad Peruana de Ciencias Aplicadas</h3>
<h4>Facultad de Ingeniería</h4>
<h4>Carrera de Ingeniería de Software</h4>
<h4>Ciclo: 2026-10</h4>
<h4>Código y Nombre del Curso: 1ASI0729 - Desarrollo de Aplicaciones Open Source</h4>
<h4>NRC 17952</h4>
<h4>Docente: Ivan Robles Fernández</h4>
<h4>Informe del Trabajo Final</h4>
<h4>Startup: VitaSync</h4>
<h4>Producto: VitalWatch</h4>

#### Relación de integrantes 
| Integrante                              | Código     |
|---------------------------------|----------------|
| Montes Zamora, Edgar Alexander Mauricio | u20241e126 |
| Güere Calero, Fernando Julio            | u202413169 |
| León Morales, Johan Yonel               | u20231h055 |
| Garcia Villanueva, Leonardo Rafael      | u20231h059 |
| Lozano Leon, Richard Enrique            | u20241d990 |

</div>

<br><div align="center"><h3>Abril 2026</h3></div><br>
<div style="text-align: justify;">

<br><br>

### Registro de Versiones del Informe

<div align="justify">

|**Versión**|**Fecha**|**Autor**|**Descripción de modificación**|
| - | - | - | - |
|1\.0|10/04/2026|Johan Yonel León Morales|Se agregó la estructura inicial del proyecto|
|1\.1\.1|10/04/2026|Johan Yonel León Morales|Se agregaron los perfiles de los integrantes del equipo|
</div><br><br>


<div align="justify">

# Project Report Collaboration Insights

URL de Organización de GITHUB del equipo VitaSync:
https://github.com/upc-pre-202610-1asi0729-17952-VitaSync

URL de Repositorio del Project Report: https://github.com/upc-pre-202610-1asi0729-17952-VitaSync/vitalwatch-report

<strong>*Entrega TB1:*</strong>


# Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming.](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming.](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3 Validation Interviews.](#53-validation-interviews)
    - [5.3.1 Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2 Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3 Evaluaciones Según Heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4 Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:<br><br>
**ABET – EAC - Student Outcome 3**<br>
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.<br><br>
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.<br><br>

<table >
  <thead>
    <tr>
      <th colspan="3"><b>Criterio específico</b></th>
      <th colspan="3"><b>Acciones realizadas</b></th>
      <th colspan="3"><b>Conclusiones</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
	<td colspan="3">Comunica oralmente con efectividad a diferentes rangos de audiencia.</td>
      <td colspan="3" align = "justify">
      <h3>Montes Zamora, Edgar Alexander Mauricio</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Güere Calero, Fernando Julio</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>León Morales, Johan Yonel</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Garcia Villanueva, Leonardo Rafael</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Lozano Leon, Richard Enrique</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
          <br>
      </td>
      <td colspan="3">
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      </td>
    </tr>
    <tr>
      <td colspan="3">Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
      <td colspan="3" align = "justify">
      <h3>Montes Zamora, Edgar Alexander Mauricio</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Güere Calero, Fernando Julio</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>León Morales, Johan Yonel</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Garcia Villanueva, Leonardo Rafael</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Lozano Leon, Richard Enrique</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
		  <br>
      </td>
      <td colspan="3">
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      </td>
    </tr>
  </tbody>
</table>



# Capítulo I: Introducción
## 1.1 Startup Profile
### 1.1.1 Descripción de la Startup

**Nombre:**  

**Área:**  


* **Misión:**


* **Visión:**


* **Valores:**


  ### 1.1.2 Perfiles de integrantes del equipo
  
| **Integrante**  | **Perfil**  | **Imagen** |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Montes Zamora, Edgar Alexander Mauricio - u20241e126** | Buenas, soy Edgar Alexander Mauricio Montes Zamora, con codigo u20241e126 y actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software. Por el momento tengo conocimientos en programación como C++ y Python, además de saber HTML, CSS y también tener conocimientos en bases de datos SQL como Microsoft SQL Server. Considero que poseo habilidades blandas como la comunicación, trabajo en equipo o la adaptabilidad a distintos cambios que puedan presentarse tanto en proyectos como en otras situaciones, intento que en trabajos grupales todos puedan colaborar y ayudarse unos a otros, además de colaborar con ideas creativas.| <img src="Resources/Profiles/Mauricio.jpg" alt="Foto de Montes Zamora, Edgar Alexander Mauricio" width="150"/> |
| **Güere Calero, Fernando Julio - u202413169** | Soy Fernando Julio Güere Calero (u202413169), estudiante del 5to ciclo de la carrera de Ingeniería de Software. Cuento con los conocimientos para programar en C++, Python y gestión de base de datos SQL. Además, tengo conocimiento para el desarrollo de páginas web usando HTML, CSS y JavaScript. Siempre estoy interesado en expandir mis conocimientos con otros lenguajes de programación para fortalecer mis competencias técnicas y enfrentar retos en la industria. | <img src="Resources/Profiles/Fernando.jpeg?raw=true" alt="Imagen de Güere Calero, Fernando Julio"/> |
| **León Morales, Johan Yonel - u20231h055** | Soy Johan Yonel León Morales, estudiante del 5to ciclo de la carrera de Ingeniería de Software, identificado con el código u20231h055. Cuento con conocimientos en programación en C++, así como en el desarrollo de interfaces web utilizando HTML, CSS y JavaScript. Mi enfoque se basa en el aprendizaje continuo y la atención al detalle, complementado con habilidades de comunicación, empatía y adaptabilidad. Estas competencias me permiten integrarme de manera efectiva en equipos de trabajo, aportar en el desarrollo de soluciones y colaborar activamente en el cumplimiento de los objetivos del proyecto. | <img src="Resources/Profiles/Johan.png?raw=true" alt="Imagen de León Morales, Johan Yonel"/> |
| **Garcia Villanueva, Leonardo Rafael - u20231h059** | Soy Leonardo Rafael Garcia Villanueva, actualmente estudiante en quinto ciclo de la carrera de Ingeniería de Software. Tengo conocimientos del lenguaje C++, asi como HTML, CSS y JavaScript. Me interesa resolver problemas que requieran de creatividad y pensamiento lógico mediante el desarrollo de software. En los trabajos en equipo frecuentemente busco resolver cualquier dificultad que se presente y me adapto rápidamente a las situaciones que se presentan. | <img src="Resources/Profiles/Leonardo.jpg?raw=true" alt="Imagen de Garcia Villanueva, Leonardo Rafael"/> |
| **Lozano Leon, Richard Enrique - u20241d990** | Soy Richard Enrique Lozano León, con código U20241D990, estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, cursando el quinto ciclo. Me interesa fortalecer mis competencias en el área tecnológica y actualmente me encuentro enfocado en el aprendizaje y práctica del lenguajes de programación. | <img src="Resources/Profiles/Richard.png?raw=true" alt="Imagen de Lozano Leon, Richard Enrique"/> |

## 1.2 Solution Profile


### 1.2.1 Antecedentes y problemática


**5W's y 2H's**
<br>

* **What?**

<br><br>
* **Why?**

<br><br>
* **Who?**

<br><br>
* **When?**

<br><br>
* **Where?**

<br><br>
* **How?**

<br><br>
* **How much?**

<br><br>

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statement



#### 1.2.2.2 Lean UX Assumptions

 + **User Assumptions:** 

    + **¿Quién es el usuario?** <br> Escribe aquí <br>

    + **¿Dónde encaja nuestro producto en su trabajo o en su vida?** <br> Escribe aquí <br>

    + **¿Cuándo y cómo se utiliza nuestro producto?** <br> Escribe aquí <br>

    + **¿Qué problemas resuelve nuestro producto?** <br> Escribe aquí <br>

    + **¿Qué características son importantes?** <br> Escribe aquí <br>

    + **¿Cómo debe verse y comportarse nuestro producto?** <br> Escribe aquí <br>

 + **Business Outcomes:** 

    1. **Creo que nuestros usuarios necesitan** 

    2. **Estas necesidades se pueden resolver con** 

    3. **Nuestros usuarios iniciales son** 

    4. **El valor #1 que un cliente quiere de nuestro servicio es que** 

    5. **El usuario también puede obtener beneficios adicionales como** 

    6. **Vamos a adquirir la mayoría de nuestros clientes a través de** 

    7. **Haremos dinero a través de** 

    8. **Nuestras competencias principales son** 

    9. **Los venceremos debido a** 

    10. **Nuestro mayor riesgo es** 

    11. **Resolveremos esto a través de** 
    
    13. **¿Qué otras suposiciones tenemos?**

#### 1.2.2.3 Lean UX Hypothesis Statements
###### Hipótesis 1:
Escribe aquí

-   **Business Outcome:** 
    
-   **Users:** 
    
-   **User Outcome:** 
    
-   **Feature:** .

###### Hipótesis 2:
Escribe aquí

-   **Business Outcome:** 
    
-   **Users:** 
    
-   **User Outcome:** 
    
-   **Feature:** 


###### Hipótesis 3:
Escribe aquí

-   **Business Outcome:** 
    
-   **Users:** 
    
-   **User Outcome:** 
    
-   **Feature:** 


#### 1.2.2.4 Lean UX Canvas

<table>
    <tr>
        <td valign="top" >
            <div align="center"> <br><b>Buiness Problem</b> </div><br>
            <p>- <br> - </p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>Solutions</b> </div><br>
            <p>- <br> - 
            </p><br>
        </td>
            <td valign="top">
            <div align="center"> <br><b>Business Outcomes</b> </div><br>
            <p>- <br>- </p><br>
            </td>
        </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Users</b></div><br>
            <p>- .<br> - </p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>User Outcomes & Benefits</b></div><br>
            <p>- <br> - <br> - </p><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"> <br><b>Hypotheses</b> </div><br>
            <p>- <br> - </p> <br>
        </td>
        <td valign="top">
            <div align="center"> <br><b>What’s the most important thing we need to learn first?</b> </div><br><p>- <br> - </p> <br>
        </td>
        <td valign="top">
            <div align="center">  <br><b>What's the least amount of work we need to do to learn the next most important thing?</b> </div><br><p>- <br> - </p> <br>
        </td>
    </tr>
</table>


## 1.3 Segmentos Objetivo

Los segmentos objetivo son grupos específicos de usuarios a los que se dirige un producto o servicio en particular.

Los segmentos objetivos identificados para nuestra plataforma VitalWatch, orientada al monitoreo del nivel de fatiga del personal médico, se presentan a continuación:
+ **S1: Personal administrativo de clínicas y hospitales**<br>
  + **Características demográficas:**<br>
    Edad: 30 a 60 años.<br>
    Género: Variado.<br>
    Cargo: Directores, administradores, jefes de área y supervisores de turnos.<br>
    Formación: Gestión hospitalaria o administración.<br>
    Tecnología: Uso frecuente de sistemas digitales.<br>
    Necesidad: Toma de decisiones y reducción de riesgos operativos.<br>

  + **Características geográficas:**<br>
    Ubicación: Clínicas y hospitales en zonas urbanas y semiurbanas.<br>
    Entorno: Instituciones con alta demanda y carga operativa.<br><br>

+ **S2: Personal clínico**<br>
  + **Características demográficas:**<br>
    Edad: 22 a 60 años.<br>
    Género: Variado.<br>
    Cargo: Médicos, enfermeros y técnicos de salud.<br>
    Condición laboral: Turnos prolongados o rotativos.<br>
    Tecnología: Uso básico/intermedio de sistemas hospitalarios.<br>
    Necesidad: Monitorear fatiga y prevenir agotamiento.<br>

  + **Características geográficas:**<br>
    Ubicación: Hospitales y centros de salud en zonas urbanas y semiurbanas.<br>
    Entorno: Alta carga laboral y demanda de atención.<br><br>

---

# Capítulo II: Requirements Elicitation & Analysis


## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron apps webs y/o aplicaciones similares. Sin embargo, estamos considerando cuatro competidores directos o indirectos que se parezcan más a nuestra startup.

* **Readi**<br>


* **Smartcap**<br>


* **Pulsar Informatics**<br>


* **Optalert**<br>


### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
	<thead>
		<tr><th colspan="7">Competitive Analysis Landscape</th></tr>
	</thead>
	<tbody>
		<tr>
			<td colspan="2">¿Por qué llevar a cabo este análisis?</td>
			<td colspan="5">Realizamos este análisis para detectar qué es lo que le falta a las soluciones actuales y asegurar que VitalWatch ofrezca algo único, pensado exclusivamente para el ritmo de un centro de salud. Conocer a fondo a la competencia nos ayuda a construir una herramienta que realmente proteja al personal médico y evite negligencias evitables por cansancio.</td>
		</tr>
		<tr>
			<td colspan="2">
				<div align="center">Nombre</div>
			</td>
			<td><div align="center"><b>VitalWatch</b></div></td>
			<td><div align="center"><b>Readi (Fatigue science)</b></div></td>
			<td><div align="center"><b>Smartcap</b></div></td>
			<td><div align="center"><b>Pulsar Informatics</b></div></td>
			<td><div align="center"><b>Optalert</b></div></td>
		</tr>
		<tr>
			<td colspan="2">
				<div align="center">Logo</div>
			</td>
			<td><div align="center">
				<img src="Resources/Competitors/vitalwatch.png?raw=true" alt="VitalWatch logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/C1.png?raw=true" alt="C1 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/C2.png?raw=true" alt="C2 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/C3.png?raw=true" alt="C3 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/C4.png?raw=true" alt="C4 logo"/>
			</div></td>
		</tr>
		<tr>
			<td rowspan="2">Perfil</td>
			<td>Overview</td>
			<td>Herramienta predictiva para que directores clínicos prevengan errores antes de que ocurran.</td>
			<td>IA que predice el riesgo de fatiga con 18 horas de antelación.</td>
			<td>Banda EEG que mide ondas cerebrales para detectar sueño al instante.</td>
			<td>Software que analiza horarios para hallar "huecos" peligrosos de sueño.</td>
			<td>Tecnología que mide el parpadeo para detectar somnolencia temprana.</td>
		</tr>
		<tr>
			<td>Ventaja Competitiva</td>
			<td>Algoritmo "Fatigue Score" que cruza biometría con carga laboral real.</td>
			<td>Predicción a largo plazo basada en tendencias históricas de sueño.</td>
			<td>Precisión del 94.7% al usar el estándar de oro médico (EEG).</td>
			<td>Validación por la NASA y el Departamento de Defensa de EE. UU..</td>
			<td>Detección de microsueños vital para cirugías de alta precisión.</td>
		</tr>
		<tr>
			<td rowspan="2">Marketing</td>
			<td>Mercado Objetivo</td>
			<td>Clínicas, hospitales y centros de salud especializados.</td>
			<td>Minería pesada, transporte y deportes de élite.</td>
			<td>Operadores de maquinaria pesada y minería a cielo abierto.</td>
			<td>Aerolíneas, defensa y redes hospitalarias académicas.</td>
			<td>Logística, automotriz y grupos de cirugía avanzada.</td>
		</tr>
		<tr>
			<td>Estrategias</td>
			<td>Enfoque humano: reducir estrés médico y evitar demandas legales.</td>
			<td>Liderazgo científico mediante estudios de "higiene del sueño".</td>
			<td>Pruebas de concepto directas en sitios de alto riesgo industrial.</td>
			<td>Cumplimiento normativo y estándares de seguridad gubernamental.</td>
			<td>Integración nativa en equipos médicos y vehículos de fábrica.</td>
		</tr>
		<tr>
			<td rowspan="3">Producto</td>
			<td>Servicios</td>
			<td>Dashboard predictivo, Fatigue Score y alertas en tiempo real.</td>
			<td>App Readi, análisis predictivo y consultoría técnica.</td>
			<td>LifeBand (wearable), pantallas de cabina y monitoreo nube.</td>
			<td>Fatigue Meter y herramientas de evaluación de horarios.</td>
			<td>Gafas inteligentes y cámaras infrarrojas de cabina.</td>
		</tr>
		<tr>
			<td>Precios</td>
			<td>Suscripción SaaS escalable por número de personal.</td>
			<td>Suscripción mensual por usuario + costo de hardware.</td>
			<td>Inversión inicial en bandas EEG + licencia de monitoreo.</td>
			<td>Licencias corporativas anuales según tamaño de flota.</td>
			<td>Contratos de integración técnica o venta de hardware.</td>
		</tr>
		<tr>
			<td>Canales</td>
			<td>Plataforma Web SaaS.</td>
			<td>Venta directa B2B y aplicaciones móviles.</td>
			<td>Venta directa y distribuidores de seguridad industrial.</td>
			<td>Venta consultiva a grandes instituciones y partners.</td>
			<td>Canales B2B directos a fabricantes de equipo original.</td>
		</tr>
		<tr>
			<td rowspan="4">SWOT</td>
			<td>Fortalezas</td>
			<td>Diseñado específicamente para el caos de una guardia médica.</td>
			<td>Algoritmo predictivo validado a nivel mundial.</td>
			<td>Datos de alerta objetivos basados en el cerebro.</td>
			<td>Líder en estándares de seguridad crítica y aviación.</td>
			<td>Previene accidentes segundos antes de que ocurran.</td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td>Startup nueva en fase de validación del algoritmo.</td>
			<td>Requiere el uso constante de un wearable externo.</td>
			<td>El hardware puede resultar incómodo en turnos largos.</td>
			<td>Curva de aprendizaje muy técnica para los usuarios.</td>
			<td>Implementación costosa por cada puesto de trabajo.</td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td>Crisis de burnout médico post-pandemia en hospitales.</td>
			<td>Expansión a logística ligera y servicios de entrega.</td>
			<td>Miniaturización de sensores EEG para mayor confort.</td>
			<td>Nuevas leyes globales de seguridad ocupacional médica.</td>
			<td>Alianzas con fabricantes de monitores hospitalarios.</td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td>Nuevas leyes de privacidad de datos biométricos de salud.</td>
			<td>Dispositivos genéricos con sensores de bajo costo.</td>
			<td>Relojes inteligentes que añadan funciones de fatiga.</td>
			<td>Cambios bruscos en regulaciones gubernamentales.</td>
			<td>Tecnologías de visión artificial de código abierto.</td>
		</tr>
	</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

#### **Estrategia de Diferenciación**
A diferencia de los gigantes del sector que se enfocan en la minería o el transporte pesado, nuestra principal diferencia es la especialización en el sector salud. No nos limitamos a medir el sueño; nuestro algoritmo "Fatigue Score" está diseñado para entender el ritmo real de una guardia médica y la carga laboral acumulada del personal de salud.

#### **Estrategia de Liderazgo en Costos**
Nuestra ventaja competitiva en costos se basa en un modelo SaaS altamente flexible. Mientras que competidores como SmartCap obligan a las instituciones a comprar hardware costoso y propietario, VitalWatch permite que el centro de salud utilice dispositivos que ya posee o integre datos biométricos de forma digital, eliminando las barreras económicas de entrada.

#### **Estrategia de Marketing**
Nuestra narrativa no vende solo un monitor de fatiga, sino también seguridad del paciente y tranquilidad legal para los directores de clínicas y hospitales. Nos posicionamos como la herramienta definitiva para combatir el cansancio médico y prevenir negligencias antes de que ocurran, enfocando nuestro mensaje en el cuidado del personal que cuida a los demás.

#### **Tácticas**
* **Validación Abierta:** Publicaremos partes del algoritmo en GitHub para que la comunidad médica y de software audite su precisión, generando confianza técnica inmediata.
* **Programas Piloto Dirigidos:** Implementaremos el sistema en clínicas pequeñas para validar el "Fatigue Score" con datos reales de guardias antes de escalar a grandes hospitales.
* **Integración Ágil:** Desarrollaremos conectores (APIs) para importar automáticamente los turnos desde los sistemas de gestión que las clínicas ya utilizan.

## 2.2 Entrevistas

En esta sección se abordará la investigación en base a la información que se obtendrá de los segmentos entrevistados con el objetivo de conocer mejor a nuestros segmentos objetivos y aprender de ellos y sus procesos.

### 2.2.1 Diseño de entrevistas

### 2.2.2 Registro de entrevistas

### 2.2.3 Análisis de entrevistas

## 2.3 Needfinding

### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.

## 2.4. Big Picture Event Storming.

Explicacion 

**Metodología aplicada**

**Big Picture Event Storming - Leyenda**

**Big Picture Event Storming - Mapa**

**Interpretación de hallazgos clave**

## 2.5. Ubiquitous Language

---
# Capítulo III: Requirements Specification

## 3.1. User Stories.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US-XX** | | | **Escenario 1:** <br>Dado que <br>Cuando <br>Entonces | **EP-XX** |
| | | | | |

## 3.2. Impact Mapping

## 3.3. Product Backlog

---
# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.3. Web Applications Mock-ups.
### 4.4.4. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
### 4.6.2. Software Architecture Context Diagram.
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams.

---
# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog 1.
#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.
## 5.4. Video About-the-Product.
---
# Conclusiones
# Bibliografía
# Anexos
