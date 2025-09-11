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

## 2.1 Competidores

### 2.1.1. Análisis competitivo
