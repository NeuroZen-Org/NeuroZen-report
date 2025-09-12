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

Mi nombre es Joao Castro Picón tengo 19 anos, actualmente estoy cursando el 5to ciclo de la carrera de ingeniería de Software en la Universidad Peruana de Ciencia Aplicadas. En mis tiempos libre me gusta entrenar como hacer calistenia, escuchar música y practicar deporte como el futbol. Me considero una persona dispuesta a lograr sus metas, soy responsable y me adapto al trabajo en equipo. Mi meta es ser un gran profesional.

<div>
  <p><img src="assets/md-images/members/Joao.png" alt="Joao" width="150px" /></p>
</div>

### 1.1.2.1. Santiago Valentino Solis Chang

Mi nombre es Santiago Valentino Solis Chang, tengo 20 años, actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. En mis tiempos libres me gusta jugar videojuegos, practicar tenis y aprender mas sobre la programación web. Me considero una persona capaz de trabajar en equipo, alguien responsable y comprometida con las necesidades del equipo.

<div>
  <p><img src="assets/md-images/members/Valentino.png" alt="Valentino" width="150px" /></p>
</div>

### 1.1.2.1. Miguel Angel Vila Guillen

Mi nombre es Miguel Angel Vila Guillen, tengo 19 años, actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. En mis horas libres me gusta jugar videojuegos, tocar la guitarra, ver y jugar futbol. Me considero una persona capaz para trabajar en equipo, aspiro ser un profesional competente.

<div>
  <p><img src="assets/md-images/members/Miguel.png" alt="Miguel" width="150px" /></p>
</div>

### 1.1.2.1. Diego Gabriel Requena Gutiérrez

Mi nombre es Diego Requena Gutiérrez, tengo 19 años y actualmente estoy cursando el quinto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona comprometida con mis objetivos y con un enfoque constante en mejorar mi rendimiento, tanto personal como académico. Busco siempre optimizar mi tiempo y los proyectos en los que me involucro, manteniendo un equilibrio entre la perfección y una perspectiva saludable.

<div>
  <p><img src="assets/md-images/members/Diego.png" alt="Diego" width="150px" /></p>
</div>

### 1.1.2.1. Juan Carlos Abud Angulo

<div>
  <p><img src="assets/md-images/members/JuanCarlos.png" alt="JuanCarlos" width="150px" /></p>
</div>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El proyecto Neuro Zen consiste en desarrollar un sistema de identificación y gestión del estrés laboral
dirigido específicamente a adultos entre 20 y 50 años, mediante la observación y registro de señales
corporales visibles como postura corporal, tensión muscular facial, cambios en la respiración,
sudoración visible, temblores, rojeces en la piel y otros indicadores físicos detectables a simple vista,
integrando estos datos en una aplicación que permita a los usuarios auto-evaluar sus niveles de estrés
en el entorno laboral, recibir recomendaciones personalizadas y estrategias prácticas para la gestión
del estrés, mejorando así el bienestar de los trabajadores y la productividad organizacional, mientras
se previenen problemas de salud asociados al estrés crónico en la población económicamente activa.

#### 1.2.1.1. What

**¿Cuál es el problema?**

El problema es el estrés laboral que afecta negativamente la salud física y mental de los trabajadores
adultos, reduciendo su productividad, aumentando el ausentismo y deteriorando su calidad de vida.

**¿Cuál es la relación con la persona en cuestión?**

La relación es directa, ya que el sistema ayudará a los usuarios a identificar sus propios niveles de
estrés mediante señales corporales observables o técnicas de respiración, permitiéndoles tomar
medidas preventivas y correctivas oportunas.

#### 1.2.1.2. Who

**¿Quiénes están involucrados?**

Están involucrados principalmente los trabajadores adultos de 20 a 50 años, así como las empresas u
organizaciones interesadas en mejorar la salud ocupacional de sus empleados.

**¿A quiénes le sucede el problema?**

El problema afecta a profesionales en edad productiva que experimentan presión laboral,
especialmente en sectores con altas exigencias, responsabilidades o ambientes competitivos.

**¿Quién lo utilizará?**

Lo utilizarán adultos profesionales de 20 a 50 años con acceso a dispositivos móviles, interesados en
monitorear y gestionar su estrés laboral de manera proactiva

#### 1.2.1.3. Where

**¿Dónde está el cliente cuando usa el producto?**
El cliente estará principalmente en su entorno laboral: oficina, teletrabajo desde casa, o cualquier
espacio donde desarrolle su actividad profesional.

**¿A dónde se dirige?**

Se dirige hacia un mejor estado de autoconocimiento y manejo del estrés, buscando mejorar su
bienestar laboral y calidad de vida.

**¿Dónde surge el problema?**

El problema surge en el entorno laboral, donde factores como la carga de trabajo, las relaciones
interpersonales, el clima organizacional o las condiciones físicas generan situaciones de estrés.

#### 1.2.1.4. When

**¿Cuándo sucede el problema?**

El problema del estrés laboral sucede principalmente durante la jornada laboral, en momentos de alta
presión, plazos ajustados, conflictos interpersonales, sobrecarga de trabajo o cuando existe un
desequilibrio entre las exigencias y los recursos disponibles.

**¿Cuándo utiliza el cliente el producto?**

El cliente utilizará la aplicación tanto durante su jornada laboral para detectar señales tempranas de
estrés, como en momentos específicos de auto evaluación programados durante el día o cuando sienta
síntomas de tensión.

#### 1.2.1.5. Why

**¿Cuál es la causa del problema?**

Las causas incluyen: altas exigencias laborales, recursos insuficientes, inseguridad laboral, conflictos
interpersonales, desequilibrio entre vida personal y profesional, falta de control sobre las tareas, y
ausencia de herramientas efectivas para detectar y gestionar el estrés tempranamente.

#### 1.2.1.6. How

**¿En qué condiciones los clientes usan nuestro producto?**

Los clientes usarán la aplicación en condiciones variadas: durante momentos de calma para establecer
una línea base, en situaciones de tensión para recibir orientación inmediata, y como herramienta de
seguimiento diario para monitorear patrones de estrés a lo largo del tiempo.

**¿Cómo nos conocieron los compradores?**

Los compradores conocerán el producto a través de campañas digitales enfocadas en bienestar laboral,
recomendaciones de profesionales de salud ocupacional, programas corporativos de bienestar, y
marketing dirigido en plataformas usadas por profesionales.

**¿Cómo prefieren los lectores acceder a nuestro contenido?**

Prefieren acceder al contenido mediante una aplicación móvil intuitiva, con notificaciones
personalizadas, dashboard visual simple y recomendaciones prácticas que puedan implementar
inmediatamente.

**¿Qué llevó a la persona a llegar a esta situación?**

Las personas llegan a situaciones de estrés por la combinación de factores externos (presiones
laborales, clima organizacional) e internos (hábitos personales, estrategias de afrontamiento), sumado
a la falta de herramientas efectivas para identificar y manejar el estrés de manera preventiva.

#### 1.2.1.7. How much

El impacto se puede cuantificar considerando que según un estudio en seis países de Latinoamérica,
hasta el 63% de los trabajadores sufre estrés laboral, especialmente mujeres. Este problema impacta a
las organizaciones por baja productividad, ausentismo y rotación, y a nivel personal, aumenta el riesgo
de enfermedades físicas y mentales, generando altos costos en salud y calidad de vida (Mejía, 2019).

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statement

Nuestra app permite a los usuarios identificar y gestionar su estrés laboral mediante un
test de autoevaluación y la observación de señales físicas visibles como la postura, la
respiración y la tensión facial. Además, brinda acceso a psicólogos y actividades
prácticas para mejorar el bienestar.
Hemos observado que muchos adultos entre 20 y 50 años sufren niveles elevados de
estrés en el trabajo, pero no cuentan con herramientas simples, accesibles y efectivas
para reconocer estos niveles a tiempo ni saber cómo actuar al respecto.
¿Cómo pueden los trabajadores detectar y manejar su estrés de forma temprana y
efectiva en su entorno laboral, usando una herramienta accesible, fácil de usar e
integrada en su rutina diaria?

#### 1.2.2.2. Lean UX Assumptions

**Feature:** Sistema de identificación y gestión del estrés laboral en NeuroZen

**Registro Bio-métrico y Perfil del Usuario:**
Creemos que nuestros usuarios (adultos de 20 a 50 años en el ámbito laboral) necesitan una forma sencilla y segura de registrar sus parámetros bio-métricos (por medio de la cámara o sensores de sus dispositivos móviles) junto con información de salud y comportamiento. Esto permitirá personalizar el seguimiento y el manejo del estrés en función de las características individuales.

**Detección Temprana de Estrés mediante Patrones Físicos:**
Creemos que la identificación de señales bio-métricas observables (postura, tensión muscular, patrones de respiración y sudoración) permitirá detectar de forma temprana niveles de estrés. Esto facilitará la intervención oportuna antes de que se agraven los síntomas, impactando positivamente en la salud mental y física de los usuarios.

**Integración de Evaluaciones Psicológicas y Recomendaciones Personalizadas:**
Creemos que los usuarios se beneficiarán al combinar la autoevaluación bio-métrica con tests emocionales y recomendaciones personalizadas (ejercicios de respiración, pausas activas, contacto con especialistas). Esta integración permitirá al usuario conocer su estado en tiempo real y acceder a soluciones prácticas y adaptadas a su contexto.

**Seguimiento y Análisis de Datos de Estrés:**
Creemos que disponer de un registro histórico del nivel de estrés y obtener estadísticas personalizadas ayudará al usuario a identificar patrones y cambios en su salud, promoviendo acciones preventivas y
mejoras en su entorno laboral y personal.

**Business Outcomes (Resultados del negocio)**

- Se aumentará la productividad laboral y se reducirá el ausentismo, ya que los trabajadores podrán identificar y gestionar su estrés de manera proactiva.

- Se generarán ingresos a través de planes de suscripción individuales y acuerdos corporativos con empresas interesadas en el bienestar de sus empleados.

- NeuroZen se posicionará como una herramienta innovadora y confiable para la salud mental en el ámbito laboral, ampliando su alcance en el mercado latinoamericano.

**Users (Usuarios)**

- Profesionales y empleados de 20 a 50 años que desarrollan sus actividades en ambientes laborales exigentes y de alta presión.

- Personas que desean mejorar sus niveles de bienestar integral mediante el monitoreo de señales físicas y emocionales.

- Usuarios que utilizan dispositivos móviles y buscan soluciones digitales para la autogestión de su salud mental.

**User Outcomes (Beneficios para el usuario)**

- Identificar sus niveles de estrés de manera temprana y objetiva, mediante el análisis de patrones bio-métricos.

- Acceder a recomendaciones personalizadas que les ayuden a manejar y reducir los síntomas de estrés.

- Visualizar estadísticas y tendencias de su bienestar, facilitando el seguimiento a lo largo del tiempo.

- Mejorar su calidad de vida laboral y personal gracias a estrategias adaptadas a sus necesidades específicas.

**Features (Características)**

- **Registro de Datos Biométricos:** Herramienta de captura de señales físicas a través de la cámara y sensores del móvil.

- **Autoevaluación Integral:** Tests combinados que evalúan tanto aspectos emocionales como físicos del estrés.

- **Recomendaciones Personalizadas:** Sugerencias de ejercicios, pausas activas y consejos de salud mental basados en el perfil del usuario.

- **Historial y Seguimiento:** Dashboard interactivo que muestra evolución, tendencias y alertas de niveles de estrés.

- **Integración con Profesionales:** Opción de contactar con psicólogos o especialistas en bienestar para intervenciones personalizadas.

#### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 01

**Creemos** que la implementación de un sistema de registro biométrico y autoevaluación permitirá a los usuarios identificar tempranamente sus niveles de estrés laboral.

**Sabemos** la hipótesis se confirma cuando se observe una correlación significativa entre los datos bio-métricos capturados y las autoevaluaciones realizadas por los usuarios.

**Cuando** al menos el 65% de los usuarios completen de forma regular la evaluación en la plataforma y se detecten cambios relevantes en sus patrones bio-métricos.

Hypothesis Statement 02

**Creemos** que al ofrecer recomendaciones personalizadas basadas en el análisis del estrés, los usuarios
adoptarán prácticas de autogestión más efectivas para reducir sus síntomas.

**Sabemos** que la hipótesis es correcta cuando los usuarios reporten mejoras en su bienestar y se
registre una disminución en los indicadores de estrés en los seguimientos mensuales.

**Cuando** se logre una reducción del 20% en la frecuencia e intensidad de síntomas reportados durante
los primeros seis meses de uso.

Hypothesis Statement 03

**Creemos** que la visualización de un historial interactivo y tendencias de estrés motivará a los usuarios a llevar un control continuo de su salud mental.

**Sabemos** que esto es cierto cuando se registre un aumento en la interacción con el dashboard y una mayor adherencia a las recomendaciones sugeridas

**Cuando** el uso constante de las herramientas de seguimiento genere datos que indiquen una mayor
consciencia y manejo proactivo del estrés en el entorno laboral.

#### 1.2.2.4. Lean UX Canvas

Lean UX Canvas es una de las herramientas que hemos utilizado para conmprender a nuestros posibles usuarios y sus necesidades. Esta es usada en el campo del diseño centrado en el usuario y la metodología Lean con la intención de desarrollar productos de forma eficientes y práctica para los usuarios. A su vez, esta puede ser utilizada por equipos multidisciplinarios para que colaboración de forma ordenada dentro un marco estructurado.

<div>
  <p align="center"><img src="assets/md-images/ux_canvas.png" alt="Canvas" width="700px" /></p>
</div>

## 1.3. Segmentos Objetivos

#### Segmento objetivo #1: Personas activas en el ámbito laboral:

Este segmento está compuesto por personas con horario de trabajo extensos, de más de 8 horas laborales. Estos ciudadanos suelen experimentar una presión psicológica alta en sus trabajos lo cuál termina en generar un cuadro de estrés que puede perjudicar su rendimiento y su calidad de vida. Según estudios realizados en distintos campos laborales, un 70% del personal presenta un estrés
agudo en sus actividades personales y laborales (Estudio LATAM, 2020). Este grupo ves clave para el éxito de la plataforma, ya que son los principales beneficiarios de las capacidades que propone este startup

#### Segmento objetivo #2: Adultos entre 20 y 50 años de edad:

Este segmento incluye personas que no necesariamente sean trabajadores formales. A menudo, son las que más experimentan grados de estrés, ya que no se rigen a un horario de trabajo, sino que su trabajo está presente a todas horas del día. Según un estudio realizado a 250 trabajadores informales se expresa que el 56% de ellos muestran nivel medio de estrés, mientras que el 33.3% está en un nivel bajo y solo el 10.6% está en un nivel alto (Porcayo, 2022). Este grupo obtendrá los mismos beneficios que el otro segmento objetivo, pero este tiene más potencial de expandir el tema del estrés laboral y por consecuencia el uso de esta plataforma.

# 2. Capítulo II: Requirements Elicitation & Analysis

---

## 2.1 Competidores

En este apartado analizaremos las posibles competencias para nuestra página web, 
viendo en ello sus descripciones y planes de negocios. 

| Competidores | Características | Diferencias | Limitaciones |
|--------------|----------------|-------------|--------------|
| **Calm** | - Contiene un ejercicio de respiración para reducir el estrés.<br>- Cursos de 10 minutos al día para reducir el estrés.<br>- Ejercicios físicos tipo meditaciones para relajar el cuerpo.<br>- Historias en audiolibro para dormir mejor. | - Enfoque multimedia de alta producción con audios narrados por celebridades y música profesional.<br>- Contenido especializado por necesidad (estrés, concentración, sueño). | - La mayoría del contenido requiere suscripción de pago.<br>- No tiene controles parentales para gestionar el uso infantil. |
| **Wysa** | - Chatbot de apoyo emocional impulsado por IA.<br>- Ejercicios como respiraciones guiadas, meditaciones y relajación muscular.<br>- Privacidad: no requiere nombre real y las conversaciones son anónimas.<br>- Versión de pago con acceso a terapeutas profesionales. | - Interfaz conversacional con IA (diferente a Calm con audio y Equoo con juegos).<br>- Incorpora técnicas de CBT y DBT guiadas.<br>- Modelo freemium claro (chatbot gratuito + coaching humano de pago). | - No puede atender emergencias de salud mental ni sustituir atención profesional.<br>- Limitaciones técnicas para comprender lenguaje complejo y matices emocionales. |
| **Equoo** | - Usa Terapia Cognitiva Conductual y psicología positiva para enseñar habilidades emocionales.<br>- Juego con 52 niveles sobre neuroticismo, amabilidad y reciprocidad.<br>- Chatbot personalizado de apoyo.<br>- Estudios clínicos respaldan su eficacia para reducir ansiedad y depresión. | - Experiencia gamificada con misiones y recompensas.<br>- Orientación a jóvenes con narrativa adaptada.<br>- Progresión tipo “nivel” con estadísticas, ausente en Calm y Wysa. | - Variedad limitada de juegos emocionales, lo que puede volverse repetitivo.<br>- El enfoque gamificado puede no resonar con quienes prefieren métodos más directos. |


### 2.1.1. Análisis competitivo

| Criterio | Calm | Wysa | Equoo |
| :--- | :--- | :--- | :--- |
| **Perfil: Descripción** | Aplicación de bienestar mental para relajarse, dormir mejor y reducir el estrés. Ofrece meditaciones guiadas, historias para dormir, música relajante, ejercicios de respiración y clases de mindfulness. | Asistente de bienestar emocional basado en IA que ofrece terapia cognitivo-conductual (CBT), terapia dialéctica conductual (DBT), journaling y meditaciones, disponible 24/7. | Plataforma gamificada que desarrolla inteligencia emocional mediante juegos interactivos basados en psicología. |
| **Ventaja Competitiva** | Diversidad de maneras para relajarse; efectivo para cualquier necesidad. | Combina un chatbot accesible 24/7 con técnicas terapéuticas validadas, y la opción de coaching humano para apoyo más profundo. | Combina entretenimiento con técnicas psicológicas efectivas, aumentando la adherencia y el compromiso en el desarrollo emocional. |
| **Perfil de Marketing: Mercado Objetivo** | Adultos entre 30 y 35 años con ingresos medio-altos que puedan pagar una suscripción. | Adultos jóvenes (18-35) y empresas que buscan herramientas de salud mental accesibles 24/7. | Adultos jóvenes (18-35), profesionales estresados, empresas e instituciones educativas. |
| **Perfil de Marketing: Estrategias de marketing** | Modelo freemium, marketing con celebridades y alianzas con empresas. | Marketing de contenidos, alianzas B2B y ASO con campañas en Instagram y LinkedIn. | Contenido educativo, partnerships B2B, campañas en redes sociales y pruebas gratuitas. |
| **Perfil de Producto: Productos & Servicios** | Meditaciones guiadas, historias para dormir, música relajante, ejercicios de respiración, clases de movimientos. | Chatbot gratuito con CBT/DBT y "pathways" temáticos; sesiones premium con coaches humanos. | App de entrenamiento emocional, versión empresarial y evaluaciones personalizadas. |
| **Perfil de Producto: Precios & Costos** | **Freemium**; plan mensual **15 USD**, anual **70 USD**, familiar **100 USD**, de por vida **400 USD**. | **Freemium**; plan mensual **12 USD**, anual **19 USD**; tarifas corporativas variables. | **Freemium**; plan individual **$5-10/mes**, planes corporativos por volumen. |
| **Perfil de Producto: Canales de Distribución** | App móvil (iOS/Android); plataforma web para empresas y coaching. | App móvil (iOS/Android); plataforma web para empresas y coaching. | Apps móviles (iOS/Android); plataforma web; integración con sistemas corporativos. |
| **Análisis SWOT: Fortalezas** | Disponible 24/7, diversidad de opciones en la aplicación. | Disponible 24/7, técnicas terapéuticas validadas e interfaz intuitiva. | Base científica sólida, formato atractivo, enfoque preventivo. |
| **Análisis SWOT: Debilidades** | Precio elevado, no ofrece sesiones en vivo, enfoque principal para angloparlantes. | No reemplaza terapia presencial, contenido gratuito limitado, calidad dependiente de la IA. | Alta competencia, creación continua de contenido, percepción de ser una solución "ligera". |
| **Análisis SWOT: Oportunidades** | Expansión internacional, integración con servicios de salud mental profesional. | Expansión en nuevos mercados, alianzas con telemedicina y wearables, localización cultural. | Creciente interés en salud mental, expansión internacional, integraciones tecnológicas. |
| **Análisis SWOT: Amenazas** | Competencia intensa, precios más asequibles en otras apps. | Competencia intensa, regulaciones de salud digital, preocupaciones por privacidad de datos. | Saturación del mercado, cambios en políticas de privacidad, escepticismo sobre la eficacia digital. |

## 2.1.2. Estrategias y tácticas frente a competidores

**FODA de nuestra empresa: "NeuroZen"**

F: Sistema de detección rápida de estrés laboral con test personalizados y conexión directa a 
profesionales de salud mental. 

O: Creciente conciencia sobre salud mental en empresas y mayor disposición a invertir en bienestar 
laboral. 

D: Posible resistencia de los usuarios a reconocer problemas de estrés y dependencia de la honestidad 
en las respuestas al test. 

A: Aparición de soluciones similares en el mercado y preocupaciones sobre confidencialidad de datos 
sensibles de salud mental. 

Para aprovechar las fortalezas y oportunidades de "NeuroZen", y al mismo tiempo enfrentar las 
debilidades y contrarrestar las amenazas del entorno competitivo, podemos considerar las siguientes 
estrategias y tácticas: 

● Desarrollar programas de implementación corporativa que incluyan talleres de sensibilización 
sobre la importancia de la salud mental. 

● Establecer alianzas con empresas de seguros médicos para ofrecer descuentos a 
organizaciones que implementen nuestro sistema preventivo. 

● Implementar tecnología de análisis de comportamiento que complemente las respuestas 
subjetivas del test con indicadores objetivos. 

● Crear un sólido programa de certificación en privacidad de datos y comunicarlo claramente a 
usuarios y empresas clientes. 

● Generar reportes anónimos agregados para departamentos de RR.HH. que muestren el ROI en 
términos de reducción de ausentismo y mejora de productividad. 

## 2.2. Entrevistas.  

---

## 2.2.1. Diseño de entrevistas.

**Segmento: Personas activas en el ámbito laboral con jornadas extendidas**

Para evaluar las necesidades y experiencias de profesionales con horarios laborales extensos que 
enfrentan altos niveles de estrés, hemos desarrollado una serie de preguntas enfocadas en comprender 
su rutina diaria, factores estresantes, y estrategias actuales para manejar la presión laboral. Esta 
información nos permitirá identificar oportunidades para que nuestra plataforma ofrezca soluciones 
efectivas que mejoren su calidad de vida y rendimiento profesional. 

Introducción: 

Buenos días/tardes, soy [...], representante de [Nombre del Proyecto]. Estamos 
desarrollando una plataforma destinada a ayudar a profesionales con horarios laborales extensos a 
manejar mejor el estrés y mejorar su calidad de vida. Nos gustaría conocer más sobre tu experiencia 
laboral y los desafíos que enfrentas en tu día a día. Tu perspectiva será muy valiosa para desarrollar 
una solución que realmente responda a las necesidades de personas como tú. 

Preguntas: 
1. Para comenzar, ¿podrías presentarte y contarnos brevemente sobre tu profesión y el sector en 
el que trabajas? 
2. ¿Cómo describirías una jornada laboral típica para ti? ¿Cuántas horas trabajas habitualmente? 
3. ¿Qué aspectos de tu trabajo consideras que generan mayor presión o estrés? 
4. ¿Has notado cambios en tu salud física o mental que atribuyas al estrés laboral? 
5. ¿Cómo suele afectar el estrés laboral a tu rendimiento en el trabajo y a tu vida personal? 
6. ¿Qué estrategias utilizas actualmente para manejar el estrés relacionado con tu trabajo? 
7. ¿Tu empresa o lugar de trabajo ofrece algún programa o recurso para ayudar a los empleados 
a manejar el estrés? 
8. En los momentos de mayor presión laboral, ¿qué tipo de apoyo o herramientas te resultarían 
más útiles? 
9. ¿Utilizas actualmente alguna aplicación o plataforma digital para gestionar el estrés o mejorar 
tu bienestar? Si es así, ¿cuál y qué te parece? 
10. ¿Qué características o funcionalidades consideras importantes en una plataforma diseñada 
para ayudar a reducir el estrés laboral? 

**Segmento: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos**

Para evaluar las necesidades y experiencias de adultos que trabajan en el sector informal o con 
horarios no definidos, hemos desarrollado preguntas orientadas a comprender cómo manejan sus 
tiempos, los factores estresantes específicos de su situación laboral y sus mecanismos actuales para 
gestionar el estrés. Esta información nos permitirá adaptar nuestra plataforma para ofrecer soluciones 
que respondan a las características particulares de este segmento, que según estudios, experimenta 
niveles variables de estrés debido a la naturaleza omnipresente de su trabajo. 

Introducción: 

Buenos días/tardes, soy [...], representante de NeuroZen. Estamos desarrollando una 
plataforma para ayudar a personas que trabajan sin horarios fijos o en el sector informal a manejar 
mejor el estrés y mejorar su calidad de vida. Nos interesa conocer tu experiencia para crear una 
solución que realmente funcione para personas como tú. Agradecemos mucho tu tiempo y sinceridad 
en esta conversación. 

Preguntas: 
1. Para empezar, ¿podrías contarnos a qué te dedicas y cómo es tu rutina de trabajo habitual? 
2. ¿Cómo organizas tu tiempo entre el trabajo y otras actividades? ¿Tienes algún método para 
establecer límites? 
3. ¿Sientes que tu trabajo "te sigue a todas partes"? ¿Puedes describir cómo es esa experiencia? 
4. ¿Cuáles son los principales factores que te generan estrés en tu trabajo? 
5. ¿Cómo describirías el nivel de estrés que experimentas habitualmente (bajo, medio, alto)? 
¿Varía mucho dependiendo de las temporadas o circunstancias? 
6. ¿De qué manera crees que el no tener un horario fijo afecta tu nivel de estrés, en comparación 
con trabajos formales con horarios establecidos? 
7. ¿Has notado algún impacto en tu salud física o mental debido al estrés relacionado con tu 
trabajo? 
8. ¿Qué estrategias o métodos utilizas actualmente para manejar el estrés cuando sientes que el 
trabajo invade todos los aspectos de tu vida? 
9. ¿Utilizas alguna aplicación, plataforma o recurso digital para ayudarte a organizar tu trabajo o 
manejar el estrés? ¿Cuál ha sido tu experiencia? 
10. ¿Qué momentos del día considerarías más apropiados para dedicar tiempo a actividades para 
reducir el estrés? 

## 2.2.2. Registro de entrevistas

**Segmento 1: Personas activas en el ámbito laboral con jornadas extendidas**

Entrevista N°1 

● Nombre: Enzo Joaquín Alatrista Amaya. 

● Sexo: Masculino. 

● Edad: 25. 

● Estado Civil: Soltero. 

● Labor: Ingeniero de Sistemas. 

Detalles de la entrevista: 

● Duración: 03:26 

[● Link: https://drive.google.com/file/d/13V0bp8f4mNgHBX6nU5c74mhhuCYzXYmT/view?usp=sharing](https://drive.google.com/file/d/13V0bp8f4mNgHBX6nU5c74mhhuCYzXYmT/view?usp=sharing)

Resumen de los puntos clave en la entrevista: 

La entrevista con Enzo, ingeniero de sistemas de 25 años, revela el alto nivel de presión en el 
sector tecnológico. Sus jornadas laborales de hasta 11 horas, sumadas a la disponibilidad 
constante y los cambios de último minuto, han afectado su salud con insomnio, dolores de 
cabeza e irritabilidad. Esto impacta su productividad y vida personal, generando agotamiento 
emocional. Aunque intenta manejar el estrés con caminatas y ejercicios de respiración, su 
rutina no le permite ser constante. Su empresa no ofrece apoyo real para el manejo del estrés, 
más allá de charlas esporádicas. Enzo valora herramientas simples y accesibles, con 
recordatorios para pausas, ejercicios rápidos y la opción de contactar a un profesional desde 
la misma app.


Entrevista N°2 

● Nombre: Andrés Luján Carrión 

● Sexo: Masculino 

● Edad: 40 

● Estado Civil: Soltero 

● Labor: Rector(USL) 

Detalles de la entrevista: 

● Duración: 4min11seg

[● Link: https://drive.google.com/file/d/1aePzhaW86rM-1leKeeb1c65SbWk9Y0yZ/view?usp=sharing](https://drive.google.com/file/d/1aePzhaW86rM-1leKeeb1c65SbWk9Y0yZ/view?usp=sharing)


Resumen de los puntos clave en la entrevista: 

- El entrevistado trabaja entre 10 y 12 horas diarias.
- Su principal fuente de estrés son la necesidad de resultados rápidos frente a cambios que 
requieren tiempo.
- Ha notado fatiga mental, insomnio y tensión muscular.
- Le parecerían útiles herramientas como coaching personalizado y plataformas digitales.
- Le gustaría que la aplicación contase con coaching emocional, seguimiento de estrés y una 
comunidad de apoyo.

**Segmento 2: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos** 

Entrevista N°3 

● Nombre: Cristofer Pablo Paucar 

● Sexo: Masculino 

● Edad: 21 

● Estado Civil: Soltero 

● Labor: Repartidor 

Detalles de la entrevista: 

● Duración: 6:27 

[● Link: https://drive.google.com/file/d/1SRe3Ilrde37SMS8YGALvpk9OqU4jpwh0/view?usp=sharing](https://drive.google.com/file/d/1SRe3Ilrde37SMS8YGALvpk9OqU4jpwh0/view?usp=sharing)

Resumen de los puntos clave en la entrevista:  

La entrevista con Cristofer Paucar, un repartidor delivery de 21 años que trabaja sin un 
horario fijo. Organiza su jornada en función de la demanda y necesidades económicas, lo que 
implica horarios variables que a menudo se extienden hasta la noche. Reconoce que tiene 
dificultades para establecer límites entre su vida personal y laboral, ya que su trabajo "lo 
sigue a todas partes" debido a la constante atención al celular. 
Los principales factores de estrés que enfrenta son la inestabilidad laboral, la incertidumbre 
económica, fallas en las aplicaciones de reparto, el tráfico, clientes exigentes y el desgaste 
físico. Califica su nivel de estrés como medio, aunque se eleva en situaciones específicas 
como fines de mes o días lluviosos. 

Cristofer considera que la falta de un horario fijo agrava el estrés al dificultar la separación 
entre el trabajo y la vida personal. Ha notado efectos negativos en su salud física y mental, 
incluyendo dolores corporales, cansancio, insomnio e irritabilidad. Para manejar el estrés, 
intenta desconectarse ocasionalmente, escuchar música o realizar actividades recreativas, 
aunque no siempre lo logra. Si bien usa aplicaciones básicas para organizar su vida personal, 
no emplea herramientas específicas para el manejo del estrés, pero le gustaría explorar 
alguna. Identifica la mañana y la noche como los momentos más adecuados para realizar 
actividades relajantes, aunque muchas veces depende del flujo de trabajo diario. 

Entrevista N°4 

● Nombre: Laura Méndez 

● Sexo: Mujer 

● Edad: 24 años 

● Estado Civil: Soltera 

● Labor: Freelancer diseñadora gráfica y fotógrafa de eventos 

Detalles de la entrevista: 

● Duración: 8 minutos con 39 segundos  

[● Link: https://drive.google.com/file/d/1UglVUZqgommlzxa7QGvVOpFjeJ5BP8ta/view?usp=sharing](https://drive.google.com/file/d/1UglVUZqgommlzxa7QGvVOpFjeJ5BP8ta/view?usp=sharing)

Resumen de los puntos clave en la entrevista: 

La entrevista con Laura Méndez, una diseñadora gráfica freelance y fotógrafa de 24 años, 
revela los desafíos únicos que enfrenta como trabajadora con horarios irregulares. Su 
situación laboral se caracteriza por la ausencia de límites entre vida personal y profesional, 
con un teléfono que funciona como "oficina móvil" y clientes que esperan disponibilidad 
constante. Los principales factores de estrés identificados incluyen la inestabilidad económica 
que la lleva a sobrecargarse de trabajo, las expectativas poco realistas de los clientes, y la 
imposibilidad de desconectar completamente, resultando en un nivel de estrés medio-alto con 
picos que afectan su salud física y creatividad. Aunque intenta implementar estrategias como 
yoga o ejercicio, estas prácticas son inconsistentes debido a su carga laboral, por lo que 
necesita soluciones flexibles que se adapten a su ritmo caótico: herramientas rápidas 
accesibles desde el móvil, técnicas para establecer límites sin perder clientes y métodos 
efectivos para "apagar" su mente al finalizar la jornada.

## 2.2.3. Análisis de entrevistas

**Segmento 1: Personas activas en el ámbito laboral con jornadas extendidas**

Hallazgos: 

● Los profesionales experimentan jornadas laborales extendidas de 10-12 horas diarias, 
sin límites claros entre vida laboral y personal. 

● Enfrentan presión constante por resultados inmediatos ante cambios que requieren 
tiempo. 

● Presentan síntomas físicos y emocionales similares: fatiga mental, insomnio, tensión 
muscular, irritabilidad y dolores de cabeza. 

● Las empresas ofrecen poco o nulo apoyo real para el manejo del estrés laboral. 

● Aunque intentan implementar técnicas de manejo del estrés, la carga laboral impide 
ser constantes. 

● Valoran soluciones digitales accesibles, rápidas y adaptables a sus horarios saturados. 
Conclusión: 

Los profesionales con jornadas extendidas constituyen un segmento vulnerable al estrés 
crónico debido a la combinación de largas horas de trabajo, disponibilidad permanente y 
presión por resultados inmediatos. Sus intentos individuales de manejar el estrés mediante 
técnicas convencionales resultan insuficientes ante la falta de límites laborales claros y apoyo 
institucional. Este grupo necesita soluciones tecnológicas personalizadas que se integren 
fácilmente a su rutina, ofrezcan intervenciones breves pero efectivas, y proporcionen tanto 
seguimiento automatizado como acceso a apoyo profesional cuando sea necesario. La 
aplicación debe enfocarse en crear micro hábitos de bienestar que puedan sostenerse incluso 
en entornos laborales exigentes, permitiéndoles recuperar el equilibrio sin comprometer su 
desempeño profesional. 

**Segmento 2: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos**

Hallazgos: 

● Ausencia de límites trabajo-vida personal: Ambos experimentan una fusión entre su 
vida laboral y personal, con el teléfono móvil como vínculo constante al trabajo. 

● Horarios irregulares: Ninguno tiene un horario fijo, organizándose según demanda y 
necesidades económicas. 

● Principales factores de estrés: Comparten preocupaciones por la inestabilidad 
económica, las expectativas de disponibilidad constante y la dificultad para 
desconectar. 

● Impacto en la salud: Ambos reportan efectos negativos como dolores físicos, 
cansancio e irritabilidad. 

● Estrategias de afrontamiento inconsistentes: Aunque intentan aplicar métodos para 
manejar el estrés (música, ejercicio, yoga), no logran mantenerlos de forma regular.

● Necesidad de herramientas adaptables: Los dos expresan interés en explorar 
soluciones que se ajusten a sus horarios variables. 

Conclusión: 

Los testimonios de Cristofer y Laura revelan una realidad laboral cada vez más común: 
trabajadores con horarios flexibles que enfrentan una constante disponibilidad laboral 
mediada por dispositivos móviles, generando una difuminación de límites entre trabajo y vida 
personal que impacta negativamente su bienestar. Esta situación crea un ciclo donde la 
inestabilidad económica los impulsa a aceptar más trabajo, intensificando el estrés y 
deteriorando su salud física y mental. Sus casos evidencian la necesidad urgente de 
desarrollar herramientas y estrategias específicamente diseñadas para trabajadores con 
horarios irregulares, que sean accesibles desde dispositivos móviles, requieran poco tiempo 
de implementación y ayuden efectivamente a establecer límites saludables sin comprometer 
su sustento económico. 

## 2.3. Needfinding

Al recopilar toda la información de los segmentos objetivo y realizar las entrevistas se hará 
un análisis de estos mismos haciendo uso de User Persona, Task Matrix, Journey Mapping, 
Empathy Mapping y As-Is Scenario Mapping. 

### 2.3.1. User Personas.

---

### 2.3.2. User Task Matrix.  

---

### 2.3.3. User Journey Mapping.  

---

### 2.3.4. Empathy Mapping.  

---

### 2.3.5. As-is Scenario Mapping.  

---

## 2.4. Ubiquitous Language. 

---

# Capítulo III: Requirements Specification  

---

## 3.1. To-Be Scenario Mapping

**User Journey Mapping – Laura Méndez**

| Fases                                     | Doing                                                                                   | Thinking                                                                         | Feeling                                     |
|------------------------------------------|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------|
| Registrar señales corporales de estrés   | La app detecta automáticamente postura y signos faciales                               | “Es útil que el sistema registre señales sin que yo tenga que hacerlo.”         | Tranquilidad por el monitoreo pasivo        |
| Completar autoevaluación de niveles de estrés | Recibe notificaciones de autoevaluación guiada con IA                                   | “Ahora sé si lo que siento es estrés o solo cansancio.”                         | Alivio por entender rápidamente su estado emocional |
| Consultar análisis de patrones de estrés | Visualiza resúmenes visuales con predicción de picos                                   | “Ya puedo ver cómo ciertos clientes o días afectan mi bienestar.”               | Curiosidad y sensación de control            |
| Acceder a recomendaciones personalizadas | Recibe sugerencias integradas a su rutina diaria                                       | “Esto se adapta a mí y no interrumpe mi día.”                                   | Esperanza al ver opciones viables            |
| Registrar seguimiento de estrategias     | Ve sus avances con ayuda de recordatorios motivacionales                               | “Estoy logrando mantener el hábito, y se nota en mi bienestar.”                 | Orgullo y motivación al ver progresos        |

**User Journey Mapping – Andrés Luján**

| Fases                                     | Doing                                                                                   | Thinking                                                                       | Feeling                                       |
|------------------------------------------|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|-----------------------------------------------|
| Registrar señales corporales de estrés   | El sistema registra tensión y postura automáticamente                                  | “El sistema me ayuda a notar lo que mi cuerpo expresa.”                       | Alivio al no depender solo de su percepción   |
| Completar autoevaluación de niveles de estrés | Usa voz o toques rápidos para autoevaluarse                                             | “Esta evaluación se adapta a mis tiempos.”                                    | Comodidad y sensación de autonomía            |
| Consultar análisis de patrones de estrés | El sistema anticipa picos de estrés según su agenda                                    | “Puedo prever cuándo debo cuidarme más o delegar.”                            | Seguridad al planificar estratégicamente      |
| Acceder a recomendaciones personalizadas | Recibe recomendaciones justo después de momentos clave                                 | “Estas estrategias están hechas para mi rol de liderazgo.”                    | Optimismo por la personalización del sistema  |
| Registrar seguimiento de estrategias     | Revisa un resumen mensual con IA                                                       | “Sé qué funcionó y qué debo ajustar para el próximo mes.”                     | Satisfacción por tener una guía continua      |

---

## 3.2. User Stories

**Epic**

| **EPIC ID** | **Nombre del Epic**                        | **Descripción**                                                                                                                                                                                                  |
| ----------- | ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01        | Registro y Configuración de Cuenta         | Como usuario nuevo, quiero registrarme, configurar mi perfil biométrico y completar un cuestionario inicial de salud, para acceder a la plataforma con un perfil personalizado y preciso.                        |
| EP02        | Detección y Evaluación del Estrés          | Como usuario, quiero evaluar mi nivel de estrés mediante autoevaluaciones, análisis biométricos y registro de síntomas, para obtener un diagnóstico completo de mi estado actual.                                |
| EP03        | Recomendaciones y Gestión del Estrés       | Como usuario diagnosticado con estrés, quiero recibir recomendaciones personalizadas, acceder a ejercicios de respiración y programar pausas activas, para reducir mis niveles de estrés y mejorar mi bienestar. |
| EP04        | Seguimiento y Análisis del Progreso        | Como usuario, quiero visualizar un dashboard personal, generar informes de progreso y registrar desencadenantes de estrés, para dar seguimiento a mi evolución y entender mis patrones de estrés.                |
| EP05        | Conexión con Especialistas en Salud Mental | Como usuario con necesidad de apoyo profesional, quiero buscar psicólogos, agendar citas y compartir informes, para recibir tratamiento especializado dentro de la plataforma.                                   |
| EP06        | Comunidad y Soporte Social                 | Como usuario, quiero participar en grupos de apoyo, acceder a una biblioteca de recursos y unirme a desafíos antiestrés, para sentir acompañamiento social y mantener la motivación en la gestión de mi estrés.  |
| EP07        | Integración con Entorno Laboral            | Como trabajador, quiero analizar mi carga laboral y recibir recordatorios de ergonomía, para prevenir sobrecarga y mejorar mi productividad sin comprometer mi bienestar.                                        |

**EP01 - Registro y Configuración de Cuenta**

| User Story ID | Título                                  |
| ------------: | --------------------------------------- |
|          US01 | Registrar cuenta de usuario             |
|          US02 | Configurar perfil biométrico            |
|          US03 | Completar cuestionario inicial de salud |

**EP02 - Detección y Evaluación del Estrés**

| User Story ID | Título                                    |
| ------------: | ----------------------------------------- |
|          US04 | Realizar test de autoevaluación de estrés |
|          US05 | Análisis biométrico de señales de estrés  |
|          US06 | Registro de síntomas físicos              |

**EP03 - Recomendaciones y Gestión del Estrés**

| User Story ID | Título                                     |
| ------------: | ------------------------------------------ |
|          US07 | Recibir recomendaciones personalizadas     |
|          US08 | Realizar ejercicios de respiración guiados |
|          US09 | Programar pausas activas laborales         |

**EP04 - Seguimiento y Análisis del Progreso**

| User Story ID | Título                                  |
| ------------: | --------------------------------------- |
|          US10 | Visualizar dashboard personal de estrés |
|          US11 | Generar informes de progreso            |
|          US12 | Registrar desencadenantes de estrés     |

**EP05 - Conexión con Especialistas en Salud Mental**

| User Story ID | Título                               |
| ------------: | ------------------------------------ |
|          US13 | Buscar psicólogos especializados     |
|          US14 | Agendar cita con psicólogo           |
|          US15 | Compartir informes con especialistas |

**EP06 - Comunidad y Soporte Social**

| User Story ID | Título                            |
| ------------: | --------------------------------- |
|          US16 | Participar en grupos de apoyo     |
|          US17 | Acceder a biblioteca de recursos  |
|          US18 | Participar en desafíos antiestrés |

**EP07 - Integración con Entorno Laboral**

| User Story ID | Título                             |
| ------------: | ---------------------------------- |
|          US19 | Analizar carga laboral             |
|          US20 | Recibir recordatorios de ergonomía |


| ID Épica | Épica                              | ID HU | Título HU                               | Descripción HU                                                                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                            |
| -------- | ---------------------------------- | ----- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01     | Registro y Configuración de Cuenta | US01  | Registrar cuenta de usuario             | Como nuevo usuario, quiero registrar una cuenta con mi correo o número de teléfono, para acceder a las funciones de la aplicación. | **Escenario 1: Registro exitoso**<br>Dado que el usuario no tiene cuenta,<br>Cuando ingresa sus datos obligatorios y acepta términos,<br>Entonces el sistema crea la cuenta y envía verificación.<br><br>**Escenario 2: Registro fallido**<br>Dado que el usuario ingresa datos inválidos,<br>Cuando intenta registrarse,<br>Entonces el sistema muestra mensaje de error y no crea cuenta.        |
| EP01     | Registro y Configuración de Cuenta | US02  | Configurar perfil biométrico            | Como usuario, quiero registrar mis datos biométricos para personalizar el análisis de estrés.                                      | **Escenario 1: Configuración inicial**<br>Dado que el usuario tiene cuenta activa,<br>Cuando registra o sincroniza datos biométricos,<br>Entonces el sistema los guarda y usa en futuros análisis.<br><br>**Escenario 2: Error de sincronización**<br>Dado que el usuario conecta un dispositivo,<br>Cuando ocurre un error,<br>Entonces el sistema muestra advertencia y permite reintentar.      |
| EP01     | Registro y Configuración de Cuenta | US03  | Completar cuestionario inicial de salud | Como usuario nuevo, quiero completar un cuestionario de salud para generar mi plan inicial.                                        | **Escenario 1: Cuestionario completado**<br>Dado que el usuario accede al cuestionario inicial,<br>Cuando responde todas las preguntas,<br>Entonces el sistema guarda respuestas y genera perfil.<br><br>**Escenario 2: Cuestionario incompleto**<br>Dado que el usuario abandona el cuestionario,<br>Cuando vuelve a ingresar,<br>Entonces el sistema permite retomar desde el progreso guardado. |



| ID Épica | Épica                             | ID HU | Título HU                                 | Descripción HU                                                                                      | Criterios de Aceptación                                                                                                                                                                                                                                                                                                             |
| -------- | --------------------------------- | ----- | ----------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP02     | Detección y Evaluación del Estrés | US04  | Realizar test de autoevaluación de estrés | Como usuario, quiero realizar un test de estrés para conocer mi nivel actual.                       | **Escenario 1: Test completado**<br>Dado que el usuario accede al test,<br>Cuando responde todas las preguntas,<br>Entonces el sistema muestra resultado inmediato.<br><br>**Escenario 2: Test incompleto**<br>Dado que el usuario abandona el test,<br>Cuando regresa,<br>Entonces el sistema guarda progreso y permite retomarlo. |
| EP02     | Detección y Evaluación del Estrés | US05  | Análisis biométrico de señales de estrés  | Como usuario, quiero que la app analice mis datos biométricos para detectar estrés automáticamente. | **Escenario 1: Análisis exitoso**<br>Dado que el usuario sincronizó su dispositivo,<br>Cuando los datos se reciben,<br>Entonces el sistema calcula nivel de estrés.<br><br>**Escenario 2: Datos insuficientes**<br>Dado que faltan datos,<br>Cuando se intenta analizar,<br>Entonces el sistema notifica al usuario.                |
| EP02     | Detección y Evaluación del Estrés | US06  | Registro de síntomas físicos              | Como usuario, quiero registrar manualmente mis síntomas físicos para complementar el análisis.      | **Escenario 1: Registro exitoso**<br>Dado que el usuario accede a “Síntomas”,<br>Cuando ingresa información,<br>Entonces el sistema guarda los datos.<br><br>**Escenario 2: Validación**<br>Dado que el usuario omite un campo obligatorio,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completar el campo.          |



| ID Épica | Épica                                | ID HU | Título HU                                  | Descripción HU                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                           |
| -------- | ------------------------------------ | ----- | ------------------------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP03     | Recomendaciones y Gestión del Estrés | US07  | Recibir recomendaciones personalizadas     | Como usuario, quiero recibir recomendaciones basadas en mi perfil de estrés.  | **Escenario 1: Recomendaciones generadas**<br>Dado que el usuario completó cuestionario y biometría,<br>Cuando accede a recomendaciones,<br>Entonces el sistema muestra sugerencias personalizadas.<br><br>**Escenario 2: Falta de datos**<br>Dado que el usuario no completó su perfil,<br>Cuando intenta ver recomendaciones,<br>Entonces el sistema muestra mensaje indicando datos faltantes. |
| EP03     | Recomendaciones y Gestión del Estrés | US08  | Realizar ejercicios de respiración guiados | Como usuario, quiero realizar ejercicios guiados para reducir el estrés.      | **Escenario 1: Ejercicio completado**<br>Dado que el usuario selecciona un ejercicio,<br>Cuando lo finaliza,<br>Entonces el sistema registra la actividad.<br><br>**Escenario 2: Interrupción**<br>Dado que el usuario abandona el ejercicio,<br>Cuando regresa,<br>Entonces el sistema permite reiniciar o continuar.                                                                            |
| EP03     | Recomendaciones y Gestión del Estrés | US09  | Programar pausas activas laborales         | Como usuario, quiero programar pausas para reducir mi carga laboral y estrés. | **Escenario 1: Pausa programada**<br>Dado que el usuario accede a la agenda,<br>Cuando programa una pausa,<br>Entonces el sistema guarda recordatorio.<br><br>**Escenario 2: Notificación**<br>Dado que se acerca la pausa,<br>Cuando llega la hora,<br>Entonces el sistema envía recordatorio.                                                                                                   |



| ID Épica | Épica                               | ID HU | Título HU                               | Descripción HU                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                                                                               |
| -------- | ----------------------------------- | ----- | --------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP04     | Seguimiento y Análisis del Progreso | US10  | Visualizar dashboard personal de estrés | Como usuario, quiero ver mi estado actual de estrés en un dashboard.               | **Escenario 1: Dashboard con datos**<br>Dado que el usuario tiene registros,<br>Cuando ingresa al dashboard,<br>Entonces el sistema muestra sus métricas.<br><br>**Escenario 2: Sin datos**<br>Dado que no hay registros,<br>Cuando accede,<br>Entonces el sistema indica que aún no hay información.                                 |
| EP04     | Seguimiento y Análisis del Progreso | US11  | Generar informes de progreso            | Como usuario, quiero generar informes para evaluar mis avances.                    | **Escenario 1: Informe generado**<br>Dado que el usuario selecciona un periodo,<br>Cuando solicita un informe,<br>Entonces el sistema genera reporte descargable.<br><br>**Escenario 2: Falta de datos**<br>Dado que el usuario no tiene registros,<br>Cuando intenta generar,<br>Entonces el sistema muestra advertencia.            |
| EP04     | Seguimiento y Análisis del Progreso | US12  | Registrar desencadenantes de estrés     | Como usuario, quiero registrar situaciones que detonan mi estrés para analizarlas. | **Escenario 1: Registro exitoso**<br>Dado que el usuario accede a “Desencadenantes”,<br>Cuando ingresa información,<br>Entonces el sistema guarda el registro.<br><br>**Escenario 2: Registro incompleto**<br>Dado que el usuario no llena campos obligatorios,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completar. |




| ID Épica | Épica                      | ID HU | Título HU                            | Descripción HU                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                  |
| -------- | -------------------------- | ----- | ------------------------------------ | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP05     | Conexión con Especialistas | US13  | Buscar psicólogos especializados     | Como usuario, quiero buscar psicólogos según especialidad para recibir apoyo. | **Escenario 1: Búsqueda exitosa**<br>Dado que el usuario accede a la búsqueda,<br>Cuando ingresa criterios,<br>Entonces el sistema muestra psicólogos disponibles.<br><br>**Escenario 2: Sin resultados**<br>Dado que no hay coincidencias,<br>Cuando busca,<br>Entonces el sistema muestra mensaje indicando que no hay psicólogos.     |
| EP05     | Conexión con Especialistas | US14  | Agendar cita con psicólogo           | Como usuario, quiero agendar una cita en línea con un psicólogo.              | **Escenario 1: Cita agendada**<br>Dado que el usuario selecciona especialista y horario,<br>Cuando confirma,<br>Entonces el sistema guarda la cita.<br><br>**Escenario 2: Conflicto de horario**<br>Dado que ya existe una cita en ese horario,<br>Cuando intenta reservar,<br>Entonces el sistema muestra error y solicita otra opción. |
| EP05     | Conexión con Especialistas | US15  | Compartir informes con especialistas | Como usuario, quiero compartir mis informes de progreso con un psicólogo.     | **Escenario 1: Informe compartido**<br>Dado que el usuario selecciona un informe,<br>Cuando lo envía,<br>Entonces el especialista recibe acceso.<br><br>**Escenario 2: Error de envío**<br>Dado que ocurre una falla,<br>Cuando intenta compartir,<br>Entonces el sistema muestra mensaje de error.                                      |



| ID Épica | Épica                      | ID HU | Título HU                         | Descripción HU                                                               | Criterios de Aceptación                                                                                                                                                                                                                                                                                                   |
| -------- | -------------------------- | ----- | --------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP06     | Comunidad y Soporte Social | US16  | Participar en grupos de apoyo     | Como usuario, quiero unirme a grupos de apoyo para compartir experiencias.   | **Escenario 1: Unión exitosa**<br>Dado que el usuario accede a grupos,<br>Cuando selecciona uno,<br>Entonces el sistema lo agrega.<br><br>**Escenario 2: Grupo cerrado**<br>Dado que el grupo requiere aprobación,<br>Cuando solicita unirse,<br>Entonces el sistema notifica que debe esperar confirmación.              |
| EP06     | Comunidad y Soporte Social | US17  | Acceder a biblioteca de recursos  | Como usuario, quiero acceder a artículos y videos sobre manejo del estrés.   | **Escenario 1: Acceso exitoso**<br>Dado que el usuario accede a la biblioteca,<br>Cuando selecciona un recurso,<br>Entonces el sistema lo abre.<br><br>**Escenario 2: Recurso no disponible**<br>Dado que un recurso fue eliminado,<br>Cuando el usuario lo selecciona,<br>Entonces el sistema notifica indisponibilidad. |
| EP06     | Comunidad y Soporte Social | US18  | Participar en desafíos antiestrés | Como usuario, quiero unirme a retos que me ayuden a mejorar mi salud mental. | **Escenario 1: Unión a desafío**<br>Dado que el usuario accede a desafíos,<br>Cuando selecciona uno,<br>Entonces el sistema lo registra.<br><br>**Escenario 2: Desafío finalizado**<br>Dado que el reto ya concluyó,<br>Cuando intenta unirse,<br>Entonces el sistema notifica que no está disponible.                    |




| ID Épica | Épica                           | ID HU | Título HU                          | Descripción HU                                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------- | ----- | ---------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| EP07     | Integración con Entorno Laboral | US19  | Analizar carga laboral             | Como empleado, quiero registrar y analizar mi carga laboral para identificar estrés laboral.  | **Escenario 1: Registro exitoso**<br>Dado que el usuario ingresa horas trabajadas,<br>Cuando guarda la información,<br>Entonces el sistema calcula carga laboral.<br><br>**Escenario 2: Validación**<br>Dado que el usuario omite datos requeridos,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completarlos.                           |
| EP07     | Integración con Entorno Laboral | US20  | Recibir recordatorios de ergonomía | Como usuario, quiero recibir recordatorios de ergonomía para cuidar mi postura en el trabajo. | **Escenario 1: Recordatorio enviado**<br>Dado que el usuario configuró notificaciones,<br>Cuando llega el horario programado,<br>Entonces el sistema envía recordatorio.<br><br>**Escenario 2: Notificaciones desactivadas**<br>Dado que el usuario desactiva recordatorios,<br>Cuando llega el horario,<br>Entonces el sistema no envía notificación. |

---

## 3.3. Impact Mapping

Impact Mapping - Segmento 1
![ImpactMapping_s1](imgs/impactmapping_s1.png)

Impact Mapping - Segmento 2
![ImpactMapping_s2](imgs/impactmapping_s2.png)

---

## 3.4. Product Backlog

| Prioridad | User Story ID | Título HU                                  | Story Points |
| --------- | ------------- | ------------------------------------------ | ------------ |
| 1         | US01          | Registrar cuenta de usuario                | 3            |
| 2         | US02          | Configurar perfil biométrico               | 5            |
| 3         | US03          | Completar cuestionario inicial de salud    | 3            |
| 4         | US04          | Realizar test de autoevaluación de estrés  | 5            |
| 5         | US05          | Análisis biométrico de señales de estrés   | 8            |
| 6         | US06          | Registro de síntomas físicos               | 3            |
| 7         | US07          | Recibir recomendaciones personalizadas     | 5            |
| 8         | US08          | Realizar ejercicios de respiración guiados | 3            |
| 9         | US09          | Programar pausas activas laborales         | 3            |
| 10        | US10          | Visualizar dashboard personal de estrés    | 5            |
| 11        | US11          | Generar informes de progreso               | 5            |
| 12        | US12          | Registrar desencadenantes de estrés        | 3            |
| 13        | US13          | Buscar psicólogos especializados           | 3            |
| 14        | US14          | Agendar cita con psicólogo                 | 5            |
| 15        | US15          | Compartir informes con especialistas       | 3            |
| 16        | US16          | Participar en grupos de apoyo              | 3            |
| 17        | US17          | Acceder a biblioteca de recursos           | 2            |
| 18        | US18          | Participar en desafíos antiestrés          | 3            |
| 19        | US19          | Analizar carga laboral                     | 5            |
| 20        | US20          | Recibir recordatorios de ergonomía         | 2            |

---

# Capítulo IV: Product Design  

---

## 4.1. Style Guidelines.  

---

### 4.1.1. General Style Guidelines.  

---

### 4.1.2. Web Style Guidelines.  

---

## 4.2. Information Architecture.  

---

## 4.2.1. Organization Systems

La información se organiza de forma lógica para que el usuario encuentre rápido lo que necesita:


Estructura basada en módulos claros: inicio, autoevaluación, recomendaciones, profesionales, comunidad y recursos.

Jerarquización de contenidos: lo más usado (tests y recomendaciones) aparece en posiciones destacadas.

---

## 4.2.2. Labeling Systems

El etiquetado debe ser claro, breve y familiar para los usuarios:

Uso de términos simples como: Inicio, Test de Estrés, Recomendaciones, Comunidad, Psicólogos, Recursos.

Evitar tecnicismos clínicos, priorizando un lenguaje cotidiano.

Consistencia en los nombres en toda la app y web.

---

## 4.2.3. SEO Tags and Meta Tags

Meta títulos: deben incluir palabras clave relacionadas con salud mental, estrés laboral y bienestar.

Meta descripciones: claras, con llamado a la acción (ejemplo: “Evalúa tu nivel de estrés y recibe recomendaciones personalizadas”).

Etiquetas alt en imágenes con descripciones concisas.

Uso de headings (H1, H2, H3) para mejorar la indexación en buscadores.

---

## 4.2.4. Searching Systems

Búsqueda interna intuitiva, con autocompletado y sugerencias rápidas.

Posibilidad de filtrar resultados (ejemplo: artículos, psicólogos, recursos, ejercicios).

Optimización para resultados relevantes según la necesidad del usuario.

---

## 4.2.5. Navigation Systems

Menú principal: siempre visible, con las secciones clave (Inicio, Autoevaluación, Recomendaciones, Comunidad, Contacto).

Breadcrumbs para indicar dónde se encuentra el usuario.

CTA (Call To Action) claros y visibles, guiando al usuario hacia las acciones más importantes (hacer test, contactar especialista, unirse a un grupo).

Compatibilidad responsive, manteniendo la navegación fluida en móviles y escritorio.

---

## 4.3. Landing Page UI Design.  

---

### 4.3.1. Landing Page Wireframe.  

---

### 4.3.2. Landing Page Mock-up.  

---

## 4.4. Web Applications UX/UI Design.  

---

### 4.4.1. Web Applications Wireframes.  

---

### 4.4.2. Web Applications Wireflow Diagrams.  

---

### 4.4.2. Web Applications Mock-ups.  

---

### 4.4.3. Web Applications User Flow Diagrams.  

---

## 4.5. Web Applications Prototyping.  

---

## 4.6. Domain-Driven Software Architecture.  

---

### 4.6.1. Software Architecture Context Diagram.  

---

### 4.6.2. Software Architecture Container Diagrams.  

---

### 4.6.3. Software Architecture Components Diagrams.  

---

## 4.7. Software Object-Oriented Design.  

---

### 4.7.1. Class Diagrams.

---

### 4.7.2. Class Dictionary.  

---

## 4.8. Database Design.  

---

### 4.8.1. Database Diagram.  

---

## 5.1. Software Configuration Management.  

---

### 5.1.1. Software Development Environment Configuration.  

---

### 5.1.2. Source Code Management.  

---

### 5.1.3. Source Code Style Guide & Conventions.  

---

### 5.1.4. Software Deployment Configuration.  

---

## 5.2. Landing Page, Services & Applications Implementation.  

---

## 5.2.X. Sprint n  

---

### 5.2.X.1. Sprint Planning n.  

---

### 5.2.X.2. Aspect Leaders and Collaborators.  

---

### 5.2.X.3. Sprint Backlog n.  

---

### 5.2.X.4. Development Evidence for Sprint Review.  

---

### 5.2.X.5. Execution Evidence for Sprint Review.  

---

### 5.2.X.6. Services Documentation Evidence for Sprint Review.  

---

### 5.2.X.7. Software Deployment Evidence for Sprint Review.  

---

### 5.2.X.8. Team Collaboration Insights during Sprint.  

---
