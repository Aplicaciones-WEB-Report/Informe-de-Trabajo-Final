<div align="center">

<img src="img/logo_upc.png" alt="Logo UPC" width="100"/>

# Universidad Peruana De Ciencias Aplicadas

## Ingeniería de Software

### Informe de Trabajo Final

### Aplicaciones Web

**Sección:** 
4364

**Profesor:**  

Sánchez Ponce, Alex Humberto

**Integrantes:**
<div style="text-align: left; display: inline-block;">
    <ul>
        <li>Peralta Chipa Ronald Joel - U202224619</li>
        <li>Bustamante Leveau Cameron Charlotte - U20231A804</li>
        <li>Lapa de la Cruz Gabriel Omar - U202216831</li>
        <li>Urrutia Peña Jasmin Adriana - U202310008</li>
        <li>Mauro Fabricio Lopez de la Cruz</li>
    </ul>
</div>

**2025 - 01**

</div>

---

# <font color="red">**Registro de Versiones del Informe**</font>

| Versión | Fecha      | Autor                          | Descripción de modificación      |
|---------|------------|--------------------------------|----------------------------------|
| TB1     | 26/01/2025 | Ronald Joel Peralta Chipa      | (Descripción de los cambios)     |
| TB2     |            |                                |                                  |
| TB3     |            |                                |                                  |

# <font color="red">**Project Report Collaboration Insights**</font>

# <font color="red">**Contenido**</font>

### Tabla de contenidos

- [**Registro de Versiones del Informe**](#registro-de-versiones-del-informe)
- [**Project Report Collaboration Insights**](#project-report-collaboration-insights)
- [**Contenido**](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- [ **Capítulo I: Introducción** ](#-capítulo-i-introducción-)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1 Antecedentes y problemática**](#121-antecedentes-y-problemática)
    - [What (¿Qué?)](#what-qué)
    - [Who (¿Quién?)](#who-quién)
    - [Where (¿Dónde?)](#where-dónde)
    - [When (¿Cuándo?)](#when-cuándo)
    - [Why (¿Por qué?)](#why-por-qué)
    - [How (¿Cómo?)](#how-cómo)
    - [How much (¿Cuánto?)](#how-much-cuánto)
    - [**1.2.2 Lean UX Process**](#122-lean-ux-process)
    - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
    - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
    - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
    - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
- [ **Capítulo II: Requirements Elicitation \& Analysis**](#-capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores**](#21-competidores)
    - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- [ **Capítulo III: Requirements Specification**](#-capítulo-iii-requirements-specification)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
  - [**4.1. Style Guidelines**](#41-style-guidelines)
    - [**4.1.1. General Style Guidelines**](#411-general-style-guidelines)
    - [**4.1.2. Web Style Guidelines**](#412-web-style-guidelines)
  - [**4.2. Information Architecture**](#42-information-architecture)
    - [**4.2.1. Organization Systems**](#421-organization-systems)
    - [**4.2.2. Labeling Systems**](#422-labeling-systems)
    - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
    - [**4.2.4. Searching Systems**](#424-searching-systems)
    - [**4.2.5. Navigation Systems**](#425-navigation-systems)
  - [**4.3. Landing Page UI Design**](#43-landing-page-ui-design)
    - [**4.3.1. Landing Page Wireframe**](#431-landing-page-wireframe)
    - [**4.3.2. Landing Page Mock-up**](#432-landing-page-mock-up)
  - [**4.4. Web Applications UX/UI Design**](#44-web-applications-uxui-design)
    - [**4.4.1. Web Applications Wireframes**](#441-web-applications-wireframes)
    - [**4.4.2. Web Applications Wireflow Diagrams**](#442-web-applications-wireflow-diagrams)
    - [**4.4.3. Web Applications Mock-ups**](#443-web-applications-mock-ups)
    - [**4.4.4. Web Applications User Flow Diagrams**](#444-web-applications-user-flow-diagrams)
  - [**4.5. Web Applications Prototyping**](#45-web-applications-prototyping)
  - [**4.6. Domain-Driven Software Architecture**](#46-domain-driven-software-architecture)
    - [**4.6.1. Software Architecture Context Diagram**](#461-software-architecture-context-diagram)
    - [**4.6.2. Software Architecture Container Diagrams**](#462-software-architecture-container-diagrams)
    - [**4.6.3. Software Architecture Components Diagrams**](#463-software-architecture-components-diagrams)
  - [**4.7. Software Object-Oriented Design**](#47-software-object-oriented-design)
    - [**4.7.1. Class Diagrams**](#471-class-diagrams)
    - [**4.7.2. Class Dictionary**](#472-class-dictionary)
  - [**4.8. Database Design**](#48-database-design)
    - [**4.8.1. Database Diagram**](#481-database-diagram)

# <font color="red">**Student Outcome**</font>

El curso contribuye al cumplimiento del Student Outcome ABET: </br> 
**ABET – EAC - Student Outcome 3** 
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias. 
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

</br>

<table style="border-collapse:collapse;border-spacing:0" class="tg"><thead><tr><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Criterio específico</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Acciones realizadas</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Conclusiones</span></th></tr></thead>
<tbody>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">1.c1. Identifica problemas complejos de ingeniería de software. </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"> <br> <b>TB1:</b> <br>
Cameron Charllotte Bustamante Leveau: 
    <br>
Ronald Joel Peralta Chipa:
    <br>
Jasmin Adriana Urrutia Peña:

<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">
    
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">1.c2. Formula problemas complejos de ingeniería de software aplicando ciencias, matemáticas e ingeniería</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><br> <b>TB1:</b> <br>
Cameron Charllotte Bustamante Leveau: 
    <br>
Ronald Joel Peralta Chipa:
    <br>
Jasmin Adriana Urrutia Peña:

    
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">  
</tr>


<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">1.c3. Resuelve problemas complejos de ingeniería de software aplicando ciencias, matemáticas e ingeniería</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><br> <b>TB1:</b> <br>
Cameron Charllotte Bustamante Leveau: 
    <br>
Ronald Joel Peralta Chipa:
    <br>
Jasmin Adriana Urrutia Peña:

    
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">
</tr>

</tbody></table>
</br></br>

# <font color="red"> **Capítulo I: Introducción** </font>

## **1.1. Startup Profile**
### **1.1.1. Descripción de la Startup**
### **1.1.2. Perfiles de integrantes del equipo**

## **1.2. Solution Profile**
### **1.2.1. Antecedentes y problemática**
### **What (¿Qué?)**
### **Who (¿Quién?)**
### **Where (¿Dónde?)**
### **When (¿Cuándo?)**
### **Why (¿Por qué?)**
### **How (¿Cómo?)**
### **How much (¿Cuánto?)**

### **1.2.2. Lean UX Process**
#### **1.2.2.1. Lean UX Problem Statements**
<p align="justify">
Nuestra Startup fue diseñada para optimizar y modernizar los procesos de selección de personal, brindando a las empresas una plataforma centralizada, automatizada e intuitiva que permite realizar contrataciones más rápidas, precisas y efectivas.
Hemos observado que el proceso de reclutamiento no está cumpliendo con estos objetivos en muchas empresas, ya que los equipos de Recursos Humanos enfrentan dificultades al gestionar manualmente grandes volúmenes de postulaciones, coordinar entrevistas en múltiples canales y tomar decisiones sin datos claros o centralizados.
Esto está causando retrasos en las contrataciones, errores humanos y una experiencia poco satisfactoria tanto para los candidatos como para los reclutadores, lo cual impacta negativamente en la eficiencia operativa y en la capacidad de atraer talento de calidad.
¿Cómo podemos mejorar la eficiencia operativa y la calidad de las contrataciones, proporcionando una plataforma web que automatice el filtrado de CVs, centralice todas las etapas del proceso y ofrezca métricas útiles para una toma de decisiones estratégicas basada en datos objetivos?
</p>

#### **1.2.2.2. Lean UX Assumptions**

<b>- Business Outcomes:</b><br>
<p align="justify">
Nuestra plataforma está diseñada para automatizar las tareas críticas del área de Recursos Humanos, mejorando su productividad y reduciendo los costos operativos asociados a los métodos tradicionales. Al ofrecer una solución moderna, accesible y basada en datos, aspiramos a posicionarnos como una herramienta esencial para empresas grandes, medianas y pequeñas que buscan profesionalizar su gestión de talento.
Suponemos que al ofrecer Jobsy como una solución innovadora, confiable y enfocada en optimizar el proceso de contratación, lograremos ventas directas a empresas medianas interesadas en planes mensuales o anuales. Esto nos permitirá generar ingresos sostenibles, alcanzar una rentabilidad y recuperar la inversión inicial dentro del primer año tras el despliegue de la aplicación.
</p>

<b>- User Outcomes:</b><br>
<p align="justify">
Cuando los equipos de Recursos Humanos utilicen Jobsy, experimentarán una mejora significativa en la eficiencia de sus procesos de reclutamiento. Al centralizar herramientas clave como el filtrado automático de CVs y la programación de entrevistas, podrán ahorrar tiempo, tomar decisiones más informadas y reducir la carga operativa. Esto les permitirá enfocarse en tareas más estratégicas, mejorar la experiencia del candidato y aumentar la calidad general de las contrataciones, sintiéndose más satisfechos con su trabajo y sus resultados.
</p>

<b>Features y Assumptions:</b><br>
<p align="justify">
<b> - Filtrado inteligente de CVs con IA:</b> Suponemos que los reclutadores confían en algoritmos para preseleccionar candidatos de forma precisa, según el cumplimiento de aptitudes registradas para el puesto. <br><br>
<b> - Panel interactivo de gestión de postulaciones:</b> El usuario desea tener control visual y rápido del estado de cada postulación. <br><br>
<b> - Envío automatizado de pruebas técnicas:</b> Suponemos que los usuarios prefieren automatizar esta etapa para reducir la carga operativa y garantizar una evaluación estandarizada de los postulantes. <br><br>
<b> - Agendamiento de entrevistas desde la plataforma:</b> Suponemos que los reclutadores valoran poder coordinar entrevistas desde un solo lugar, sin depender de herramientas externas. <br><br>
<b> - Generación de contratos digitales y gestión del onboarding:</b> Suponemos que las empresas desean digitalizar completamente el proceso de incorporación para hacerlo más ágil y ordenado. <br><br>
<b> - Publicación automatizada de vacantes:</b> Suponemos que los usuarios valoran poder publicar vacantes de manera rápida y sugerida. <br><br>
<b> - Sistema de seguimiento de candidatos:</b> Suponemos que los reclutadores necesitan una línea de tiempo clara del proceso de cada candidato para evitar confusiones. <br><br>
<b> - Gamificación para evaluar habilidades blandas:</b> Suponemos que los reclutadores estarán abiertos a utilizar dinámicas interactivas para detectar rasgos como liderazgo, comunicación o trabajo en equipo de manera más natural y divertida. <br><br>
<b> - Organizador de evaluación y entrevistas programadas:</b> Suponemos que los usuarios valorarán tener una agenda donde puedan gestionar fechas y recordatorios de todos los candidatos en un solo lugar.
</p>

#### **1.2.2.3. Lean UX Hypothesis Statements**
<ol>
  <li>
    <p align="justify"><b>Hipótesis 1:</b><br>
    Creemos que los reclutadores preferirán el filtrado inteligente por IA frente a la revisión manual de CVs.<br>
    <i>Sabremos que esta hipótesis es cierta</i> cuando veamos que al menos el 70% de los usuarios usa el filtrado automático.
    </p>
  </li>

  <li>
    <p align="justify"><b>Hipótesis 2:</b><br>
    Creemos que la publicación automatizada de vacantes facilitará una mayor difusión de las ofertas laborales y reducirá el tiempo de publicación.<br>
    <i>Sabremos que esta hipótesis es cierta</i> cuando veamos una reducción del 50% en el tiempo promedio que toma publicar las vacantes en otros portales.
    </p>
  </li>

  <li>
    <p align="justify"><b>Hipótesis 3:</b><br>
    Creemos que el sistema de seguimiento de candidatos permitirá una gestión más ordenada y eficiente del proceso de selección.<br>
    <i>Sabremos que esta hipótesis es cierta</i> cuando los usuarios consulten y actualicen el estado de los candidatos frecuentemente dentro del sistema.
    </p>
  </li>

  <li>
    <p align="justify"><b>Hipótesis 4:</b><br>
    Creemos que la gamificación para evaluar habilidades blandas mejorará el nivel de engagement de los postulantes y facilitará la evaluación de competencias sociales.<br>
    <i>Sabremos que esta hipótesis es cierta</i> cuando más del 50% de los candidatos completen las pruebas gamificadas y los reclutadores tomen en cuenta esto en su decisión final.
    </p>
  </li>

  <li>
    <p align="justify"><b>Hipótesis 5:</b><br>
    Creemos que los usuarios valorarán tener una agenda donde puedan gestionar fechas y recordatorios de todos los candidatos en un solo lugar.<br>
    <i>Sabremos que esta hipótesis es cierta</i> cuando veamos que al menos el 75% de los usuarios utilizan activamente la agenda para programar entrevistas y establecer recordatorios durante el proceso de evaluación.
    </p>
  </li>
</ol>

#### **1.2.2.4. Lean UX Canvas**
<img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeChJjk9rz2GE1ZGx9Ik6Tb2uyG76_3iCMBSgNx_56x-wLz8njRZFbxBwEusDlFwnuKPwRoafOCOr-3Gel2mIydUgrVS_oD7YuV2xB7ZQwZMzZ-YPhR7Z-8BW5X_t1aKGwy3WIMGw?key=gvlLacgsz9NCnDkMVc0Umifa" />

#### **1.3. Segmentos objetivo** 
<b>Segmento 1: Equipos de Recursos Humanos encargados del proceso de contratación</b>
<ul>
  <li><p align="justify">Empresas medianas (entre 50 y 250 empleados) que no cuentan con soluciones completas de automatización.</p></li>
  <li><p align="justify">Equipos de Recursos Humanos conformados por 1 a 5 personas, que gestionan múltiples vacantes al mes.</p></li>
  <li><p align="justify">Profesionales con entre 25 y 45 años de edad, con experiencia en selección de personal, reclutamiento y gestión de talento.</p></li>
  <li><p align="justify">Sectores como tecnología, servicios, comercio y educación, donde la rotación de personal suele ser más alta.</p></li>
  <li><p align="justify">Ubicadas en contextos urbanos, con cierta familiaridad con herramientas digitales, pero que aún utilizan procesos manuales o poco integrados.</p></li>
</ul>

<b>Segmento 2: Postulantes (Candidatos para el empleo)</b>
<ul>
  <li><p align="justify">Jóvenes profesionales y técnicos entre 22 y 35 años, egresados de universidades o institutos técnicos.</p></li>
  <li><p align="justify">Personas con experiencia laboral previa de entre 1 y 5 años, principalmente en áreas como tecnología, diseño, administración, ventas o atención al cliente.</p></li>
  <li><p align="justify">Residentes de zonas urbanas con acceso a internet y familiarizados con el uso de plataformas digitales para postularse (como LinkedIn, Computrabajo, etc.).</p></li>
  <li><p align="justify">Personas que valoran una experiencia de postulación clara, ágil y moderna, con comunicación rápida y procesos más transparentes.</p></li>
  <li><p align="justify">Interesados en empresas que tengan procesos actualizados, con posibilidad de seguimiento de su postulación, evaluaciones claras y entrevistas organizadas.</p></li>
</ul>

# <font color="red"> **Capítulo II: Requirements Elicitation & Analysis**</font>

## **2.1. Competidores**
### **2.1.1. Análisis competitivo**
### **2.1.2. Estrategias y tácticas frente a competidores**

## **2.2. Entrevistas**
### **2.2.1. Diseño de entrevistas**
### **2.2.2. Registro de entrevistas**
### **2.2.3. Análisis de entrevistas**

## **2.3. Needfinding**
### **2.3.1. User Personas**
### **2.3.2. User Task Matrix**
### **2.3.3. User Journey Mapping**
### **2.3.4. Empathy Mapping**
### **2.3.5. As-is Scenario Mapping**

## **2.4. Ubiquitous Language**

# <font color="red"> **Capítulo III: Requirements Specification**</font>

## **3.1. To-Be Scenario Mapping**
## **3.2. User Stories**
## **3.3. Impact Mapping**
## **3.4. Product Backlog**

# <font color="red">**Capítulo IV: Product Design**</font>

## **4.1. Style Guidelines**
### **4.1.1. General Style Guidelines**
### **4.1.2. Web Style Guidelines**

## **4.2. Information Architecture**
### **4.2.1. Organization Systems**
### **4.2.2. Labeling Systems**
### **4.2.3. SEO Tags and Meta Tags**
### **4.2.4. Searching Systems**
### **4.2.5. Navigation Systems**

## **4.3. Landing Page UI Design**
### **4.3.1. Landing Page Wireframe**
### **4.3.2. Landing Page Mock-up**

## **4.4. Web Applications UX/UI Design**
### **4.4.1. Web Applications Wireframes**
### **4.4.2. Web Applications Wireflow Diagrams**
### **4.4.3. Web Applications Mock-ups**
### **4.4.4. Web Applications User Flow Diagrams**

## **4.5. Web Applications Prototyping**

## **4.6. Domain-Driven Software Architecture**
### **4.6.1. Software Architecture Context Diagram**
### **4.6.2. Software Architecture Container Diagrams**
### **4.6.3. Software Architecture Components Diagrams**

## **4.7. Software Object-Oriented Design**
### **4.7.1. Class Diagrams**
### **4.7.2. Class Dictionary**

## **4.8. Database Design**
### **4.8.1. Database Diagram**


