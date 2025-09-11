# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/md-images/upc-logo.png" alt="Logo UPC" width="150px" /></p>
  <p align="center"><b>Informe de Trabajo Final</b></p>
  <p align="center">Facultad de Ingeniería</p>
  <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
  <p align="center">Ingeniería de Software</p>
  <p align="center">Aplicaciones Web - 1ASI0730</p>
  <p align="center">NRC: 7414</p>
  <p align="center">Alex Humberto Sánchez Ponce</p>
  <p align="center">Startup: NeuroDraw</p>
  <p align="center">Producto: NeuroZen</p>
</div>

---

## Team members:

| **Nombre**                         | **Código** |
| ---------------------------------- | ---------- |
| Manuel Fernando, Joao Castro Picón | U20231G159 |
| Solis Chang, Santiago Valentino    | U20231B475 |
| Vila Guillen, Miguel Angel         | U20231G054 |
| Requena Gutiérrez, Diego Gabriel   | U202321774 |
| Abud Angulo, Juan Carlos           | U202317692 |

<div>
  <p align="center"><b>Ciclo 2025 - 2</b></p>
</div>

---

# Contenido

1. **[Capítulo I: Introducción](#1-capítulo-i-introducción)**  
   &nbsp;&nbsp;&nbsp;&nbsp;1.1. [Startup Profile](#11-startup-profile)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.1. [Descripción del startup](#111-descripción-del-startup)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2. [Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)  
   &nbsp;&nbsp;&nbsp;&nbsp;1.2. [Solution Profile](#12-solution-profile)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.1. [Antecedentes y Problemática](#121-antecedentes-y-problemática)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2. [Lean UX Process](#122-lean-ux-process)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.1. [Lean UX Problem Statement](#1221-lean-ux-problem-statement)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)  
   &nbsp;&nbsp;&nbsp;&nbsp;1.3. [Segmentos objetivos](#13-segmentos-objetivos)

2. **[Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)**  
   &nbsp;&nbsp;&nbsp;&nbsp;2.1. [Competidores](#21-competidores)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.1. [Análisis competitivo](#211-análisis-competitivo)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2. [Entrevistas](#22-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.3. [Needfinding](#23-needfinding)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.1. [User Personas](#231-user-personas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.2. [User Task Matrix](#232-user-task-matrix)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.3. [User Journey Mapping](#233-user-journey-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.4. [Empathy Mapping](#234-empathy-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4. [Ubiquitous Language](#24-ubiquitous-language)

3. **[Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)**  
   &nbsp;&nbsp;&nbsp;&nbsp;3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.2. [User Stories](#32-user-stories)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.3. [Impact Mapping](#33-impact-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.4. [Product Backlog](#34-product-backlog)

4. **[Capítulo IV: Product Design](#4-capítulo-iv-product-design)**  
   &nbsp;&nbsp;&nbsp;&nbsp;4.1. [Style Guidelines](#41-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.1. [General Style Guidelines](#411-general-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.2. [Web Style Guidelines](#412-web-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.2. [Information Architecture](#42-information-architecture)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.1. [Organization Systems](#421-organization-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.2. [Labeling Systems](#422-labeling-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.4. [Searching Systems](#424-searching-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.5. [Navigation Systems](#425-navigation-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.3. [Landing Page UI Design](#43-landing-page-ui-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.5. [Web Applications Prototyping](#45-web-applications-prototyping)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.1. [Class Diagrams](#471-class-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.2. [Class Dictionary](#472-class-dictionary)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.8. [Database Design](#48-database-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.8.1. [Database Diagram](#481-database-diagram)

5. **[Capítulo V: Product Implementation, Validation & Deployment](#5-capítulo-v-product-implementation-validation--deployment)**  
   &nbsp;&nbsp;&nbsp;&nbsp;5.1. [Software Configuration Management](#51-software-configuration-management)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.2. [Source Code Management](#512-source-code-management)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1. [Sprint 1](#521-sprint-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3. [Validation Interviews](#53-validation-interviews)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.1. [Diseño de Entrevistas](#531-diseño-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.2. [Registro de Entrevistas](#532-registro-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.3. [Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.4. [Video About-the-Product](#54-video-about-the-product)

6. **[Conclusiones](#6-conclusiones)**  
   &nbsp;&nbsp;&nbsp;&nbsp;6.1. [Conclusiones](#61-conclusiones)  
   &nbsp;&nbsp;&nbsp;&nbsp;6.2. [Recomendaciones](#62-recomendaciones)

7. **[Bibliografía](#7-bibliografía)**

8. **[Anexos](#8-anexos)**

---

# 1. Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestro startup llamado NeuroDraw está enfocado en una rápida detección del estrés en el ámbito
laboral de personas entre 20 a 50 años de edad. Abarcando temas como salud mental, presión laboral
y servicios, el software facilita el tratamiento del estrés laboral.
Los usuarios pueden realizar un test que recabará información de salud, comportamiento, actitudes y
patrones en la persona. La plataforma permite el contacto con un psicólogo. Además, fomenta
diversas actividades para complementar el tratamiento contra el estrés.

### 1.1.2. Perfiles de los integrantes del equipo

### 1.1.2.1. Joao Castro Picón Manuel Fernando

Mi nombre es Joao Castro Picón
tengo 19 anos, actualmente estoy
cursando el 5to ciclo de la carrera de
ingeniería de Software en la
Universidad Peruana de Ciencia
Aplicadas. En mis tiempos libre me gusta
entrenar como hacer calistenia,
escuchar música y practicar deporte
como el futbol. Me considero una
persona dispuesta a lograr sus
metas, soy responsable y me adapto
al trabajo en equipo. Mi meta es ser
un gran profesional.

<div>
  <p><img src="assets/md-images/members/Joao.png" alt="Joao" width="150px" /></p>
</div>

### 1.1.2.1. Santiago Valentino Solis Chang

Mi nombre es Santiago Valentino
Solis Chang, tengo 20 años,
actualmente estoy cursando el
5to ciclo de la carrera de
Ingeniería de Software en la
Universidad Peruana de Ciencias
Aplicadas. En mis tiempos libres me gusta
jugar videojuegos, practicar tenis
y aprender mas sobre la
programación web. Me
considero una persona capaz de
trabajar en equipo, alguien
responsable y comprometida
con las necesidades del equipo.

<div>
  <p><img src="assets/md-images/members/Valentino.png" alt="Valentino" width="150px" /></p>
</div>

### 1.1.2.1. Miguel Angel Vila Guillen

Mi nombre es Miguel Angel Vila
Guillen, tengo 19 años, actualmente
estoy cursando el 5to ciclo de la
carrera de Ingeniería de Software en
la Universidad Peruana de Ciencias
Aplicadas. En mis horas libres me gusta jugar
videojuegos, tocar la guitarra, ver y
jugar futbol. Me considero una
persona capaz para trabajar en
equipo, aspiro ser un profesional
competente.

<div>
  <p><img src="assets/md-images/members/Miguel.png" alt="Miguel" width="150px" /></p>
</div>

### 1.1.2.1. Diego Gabriel Requena Gutiérrez

Mi nombre es Diego Requena
Gutiérrez, tengo 19 años y actualmente
estoy cursando el quinto ciclo de la
carrera de Ingeniería de Software en la
Universidad Peruana de Ciencias
Aplicadas. Me considero una persona
comprometida con mis objetivos y con
un enfoque constante en mejorar mi
rendimiento, tanto personal como
académico. Busco siempre optimizar
mi tiempo y los proyectos en los que
me involucro, manteniendo un
equilibrio entre la perfección y una
perspectiva saludable.

<div>
  <p><img src="assets/md-images/members/Diego.png" alt="Diego" width="150px" /></p>
</div>

### 1.1.2.1. Juan Carlos Abud Angulo



<div>
  <p><img src="assets/md-images/members/JuanCarlos.png" alt="JuanCarlos" width="150px" /></p>
</div>
