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
| **Güere Calero, Fernando Julio - u202413169** | Escribe aquí | <img src="Resources/Profiles/Fernando.jpeg?raw=true" alt="Imagen de Güere Calero, Fernando Julio"/> |
| **León Morales, Johan Yonel - u20231h055** | Soy Johan Yonel León Morales, estudiante del 5to ciclo de la carrera de Ingeniería de Software, identificado con el código u20231h055. Cuento con conocimientos en programación en C++, así como en el desarrollo de interfaces web utilizando HTML, CSS y JavaScript. Mi enfoque se basa en el aprendizaje continuo y la atención al detalle, complementado con habilidades de comunicación, empatía y adaptabilidad. Estas competencias me permiten integrarme de manera efectiva en equipos de trabajo, aportar en el desarrollo de soluciones y colaborar activamente en el cumplimiento de los objetivos del proyecto. | <img src="Resources/Profiles/Johan.png?raw=true" alt="Imagen de León Morales, Johan Yonel"/> |
| **Garcia Villanueva, Leonardo Rafael - u20231h059** | Escribe aquí | <img src="Resources/Profiles/Leonardo.jpg?raw=true" alt="Imagen de Garcia Villanueva, Leonardo Rafael"/> |
| **Lozano Leon, Richard Enrique - u20241d990** | Soy Richard Enrique Lozano León, con código U20241D990, estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, cursando el cuarto ciclo. Me interesa fortalecer mis competencias en el área tecnológica y actualmente me encuentro enfocado en el aprendizaje y práctica del lenguajes de programación. | <img src="Resources/Profiles/Richard.png?raw=true" alt="Imagen de Lozano Leon, Richard Enrique"/> |

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

+ **S1**<br>

    + **Características demográficas:** <br>
    + **Características geográficas:** <br><br>

+ **S2**<br>

    + **Características demográficas:** <br>
    + **Características geográficas:** <br><br>

---

# Capítulo II: Requirements Elicitation & Analysis


## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron apps webs y/o aplicaciones similares. Sin embargo, estamos considerando cuatro competidores directos o indirectos que se parezcan más a nuestra startup.

* **C1**<br>


* **C2**<br>


* **C3**<br>


* **C4**<br>


### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
	<thead>
		<tr><th colspan="7">Competitive Analysis Landscape</th></tr>
	</thead>
	<tbody>
		<tr>
			<td colspan="2">¿Por qué llevar a cabo este análisis?</td>
			<td colspan="5"> - </td>
		</tr>
		<tr>
			<td colspan="2">
				<div align="center">Nombre</div>
			</td>
			<td><div align="center"><b>VitalWatch</b></div></td>
			<td><div align="center"><b>C1</b></div></td>
			<td><div align="center"><b>C2</b></div></td>
			<td><div align="center"><b>C3</b></div></td>
			<td><div align="center"><b>C4</b></div></td>
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
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Ventaja Competitiva</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="2">Marketing</td>
			<td>Mercado Objetivo</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Estrategias</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="3">Producto</td>
			<td>Servicios</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Precios</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Canales</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="4">SWOT</td>
			<td>Fortalezas</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

**Estrategia de Diferenciación:**
**Estrategia de Liderazgo en Costos:**
**Estrategia de Marketing:**
**Tácticas:**

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
