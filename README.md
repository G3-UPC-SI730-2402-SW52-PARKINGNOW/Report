# **COURSE PROJECT**

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong><br>
Aplicaciones Web - SW52 <br>
Ciclo: 5to <br>
<strong>Profesor:</strong> Juan Carlos Tinoco Licas</p>

<h2 align="center">INFORME</h2>

<h3 align="center">Startup:</h3>
<p align="center"><strong>Producto:</strong></p>

<h3 align="center">Team Members:</h3>

<div align="center">

| **Member**                    | **Code**     |
|-------------------------------|--------------|
| Loechle Arias Mateo Italo     | U202223990   |
| Rodrigo Liberato Saldaña      | U202215623   |
| Samuel Elias Molina Asencios  | U20191A456   |
| Omar Harold Rivera Ticllacuri | U202214214   |
| Diego Ulises Soto Quispe      | U202214477   |

</div>

<p align="center"><strong>Agosto 2024</strong></p>

# Índice

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#chapter-1)
    - [1.1. Startup Profile](#startup-profile)
        - [1.1.1. Descripción de la Startup](#startup-description)
        - [1.1.2. Perfiles de integrantes del equipo](#profile-members)
    - [1.2. Solution Profile](#solution-profile)
        - [1.2.1. Antecedentes y problemática](#background-and-problems)
        - [1.2.2. Lean UX Process](#lean-ux)
            - [1.2.2.1. Lean UX Problem Statements](#lean-ux-problem)
            - [1.2.2.2. Lean UX Assumptions](#lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#lean-ux-hypothesis)
            - [1.2.2.4. Lean UX Canvas](#lean-ux-canvas)
    - [1.3. Segmentos objetivo](#target-segments)
- [Capítulo II: Requirements Elicitation & Analysis](#chapter-2)
    - [2.1. Competidores](#competitors)
        - [2.1.1. Análisis competitivo](#competitive-analysis)
        - [2.1.2. Estrategias y tácticas frente a competidores](#strategy-tactics)
    - [2.2. Entrevistas](#interviews)
        - [2.2.1. Diseño de entrevistas](#interviews-design)
        - [2.2.2. Registro de entrevistas](#interviews-registry)
        - [2.2.3. Análisis de entrevistas](#interviews-analysis)
    - [2.3. Needfinding](#needfinding)
        - [2.3.1. User Personas](#user-personas)
        - [2.3.2. User Task Matrix](#user-task-matrix)
        - [2.3.3. User Journey Mapping](#user-journey-mapping)
        - [2.3.4. Empathy Mapping](#empathy-mapping)
        - [2.3.5. As-is Scenario Mapping](#as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#chapter-3)
    - [3.1. To-Be Scenario Mapping](#to-be-scenario-mapping)
    - [3.2. User Stories](#user-stories)
    - [3.3. Impact Mapping](#impact-mapping)
    - [3.4. Product Backlog](#product-backlog)
- [Capítulo IV: Product Design](#chapter-4)
    - [4.1. Style Guidelines](#style-guidelines)
        - [4.1.1. General Style Guidelines](#general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#web-style-guidelines)
    - [4.2. Information Architecture](#information-architecture)
        - [4.2.1. Organization Systems](#organization-systems)
        - [4.2.2. Labeling Systems](#labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#searching-systems)
        - [4.2.5. Navigation Systems](#navigation-systems)
    - [4.3. Landing Page UI Design](#landing-page-ui)
        - [4.3.1. Landing Page Wireframe](#landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#landing-page-mockup)
    - [4.4. Web Applications UX/UI Design](#web-application-ux-ui)
        - [4.4.1. Web Applications Wireframes](#web-application-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#web-application-wireflow)
        - [4.4.2. Web Applications Mock-ups](#web-appliaction-mockups)
        - [4.4.3. Web Applications User Flow Diagrams](#user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#software-object-oriented-design)
        - [4.7.1. Class Diagrams](#class-diagrams)
        - [4.7.2. Class Dictionary](#class-dictionary)
    - [4.8. Database Design](#database-design)
        - [4.8.1. Database Diagram](#database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#chapter-5)
    - [5.1. Software Configuration Management](#software-configuration)
        - [5.1.1. Software Development Environment Configuration](#software-development)
        - [5.1.2. Source Code Management](#source-code)
        - [5.1.3. Source Code Style Guide & Conventions](#source-code-style-guide-and-conventions)
        - [5.1.4. Software Deployment Configuration](#software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#landing-page-services-applications-implementation)
        - [5.2.X. Sprint n](#sprint-x)
            - [5.2.X.1. Sprint Planning n](#sprint-planning-x)
            - [5.2.X.2. Sprint Backlog n](#spring-backlog-x)
            - [5.2.X.3. Development Evidence for Sprint Review](#development-evidence-for-sprint-review-x)
            - [5.2.X.4. Testing Suite Evidence for Sprint Review](#testing-suite-evidence-for-sprint-review)
            - [5.2.X.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
            - [5.2.X.6. Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
            - [5.2.X.7. Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
            - [5.2.X.8. Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
    - [5.3. Validation Interviews](#validation-interviews)
        - [5.3.1. Diseño de Entrevistas](#interview-design-2)
        - [5.3.2. Registro de Entrevistas](#interview-registry-2)
        - [5.3.3. Evaluaciones según heurísticas](#heuristic-exam)
    - [5.4. Video About-the-Product](#about-the-productions)
- [Conclusiones](#conclusions)
- [Conclusiones y recomendaciones](#recomendations)
- [Video About-the-Team](#about-the-team)
- [Bibliografía](#bibliography)
- [Anexos](#links)


<h4 id="student-outcome"> Student Outcome</h4>
<h3 id="chapter-1">Capítulo I: Introducción</h3>
<h4 id="startup-profile">1.1. Startup Profile</h4>
<h4 id="startup-description"> 1.1.1. Descripción de la Startup</h4>
<h4 id="profile-members">1.1.2. Perfiles de integrantes del equipo</h4>
<h4 id="solution-profile">1.2. Solution Profile</h4>
<h4 id="background-and-problems">1.2.1 Antecedentes y problemática</h4>
<h4 id="lean-ux">1.2.2 Lean UX Process.</h4>
<h4 id="lean-ux-problem">1.2.2.1. Lean UX Problem Statements.</h4>
<h4 id="lean-ux-assumptions">1.2.2.2. Lean UX Assumptions.</h4>
<h4 id="lean-ux-hypothesis">1.2.2.3. Lean UX Hypothesis Statements.</h4>
<h4 id="lean-ux-canvas">1.2.2.4. Lean UX Canvas.</h4>
<h4 id="target-segments">1.3. Segmentos objetivo.</h4>
<h3 id="chapter-2">Capítulo II: Requirements Elicitation & Analysis</h3>
<h4 id="competitors">2.1. Competidores.</h4>
<h4 id="competitive-analysis">2.1.1. Análisis competitivo.</h4>
<h4 id="strategy-tactics">2.1.2. Estrategias y tácticas frente a competidores.</h4>
<h4 id="interviews">2.2. Entrevistas.</h4>
<h4 id="interviews-design">2.2.1. Diseño de entrevistas.</h4>
<h4 id="interviews-registry">2.2.2. Registro de entrevistas.</h4>
<h4 id="interviews-analysis">2.2.3. Análisis de entrevistas.</h4>
<h4 id="needfinding">2.3. Needfinding.</h4>
<h4 id="user-personas">2.3.1. User Personas.</h4>
<h4 id="user-task-matrix">2.3.2. User Task Matrix.</h4>
<h4 id="user-journey-mapping">2.3.3. User Journey Mapping.</h4>
<h4 id="empathy-mapping">2.3.4. Empathy Mapping.</h4>
<h4 id="as-is-scenario-mapping">2.3.5. As-is Scenario Mapping.</h4>
<h4 id="ubiquitous-language">2.4. Ubiquitous Language.</h4>
<h3 id="chapter-3">Capítulo III: Requirements Specification</h3>
<h4 id="to-be-scenario-mapping">3.1. To-Be Scenario Mapping.</h4>
<h4 id="user-stories">3.2. User Stories.</h4>
<h4 id="impact-mapping">3.3. Impact Mapping.</h4>
<h4 id="product-backlog">3.4. Product Backlog.</h4>
<h3 id="chapter-4">Capítulo IV: Product Design</h3>
<h4 id="style-guidelines">4.1. Style Guidelines.</h4>
<h4 id="general-style-guidelines">4.1.1. General Style Guidelines.</h4>
<h4 id="web-style-guidelines">4.1.2. Web Style Guidelines.</h4>
<h4 id="information-architecture">4.2. Information Architecture.</h4>
<h4 id="organization-systems">4.2.1. Organization Systems.</h4>
<h4 id="labeling-systems">4.2.2. Labeling Systems.</h4>
<h4 id="seo-tags-and-meta-tags">4.2.3. SEO Tags and Meta Tags</h4>
<h4 id="searching-systems">4.2.4. Searching Systems.</h4>
<h4 id="navigation-systems">4.2.5. Navigation Systems.</h4>
<h4 id="landing-page-ui">4.3. Landing Page UI Design.</h4>
<h4 id="landing-page-wireframe">4.3.1. Landing Page Wireframe.</h4>
<h4 id="landing-page-mockup">4.3.2. Landing Page Mock-up.</h4>
<h4 id="web-application-ux-ui">4.4. Web Applications UX/UI Design.</h4>
<h4 id="web-application-wireframes">4.4.1. Web Applications Wireframes.</h4>
<h4 id="web-application-wireflow">4.4.2. Web Applications Wireflow Diagrams.</h4>
<h4 id="web-appliaction-mockups">4.4.2. Web Applications Mock-ups.</h4>
<h4 id="user-flow-diagrams">4.4.3. Web Applications User Flow Diagrams.</h4>
<h4 id="web-applications-prototyping">4.5. Web Applications Prototyping.</h4>
<h4 id="domain-driven-software-architecture">4.6. Domain-Driven Software Architecture.</h4>
<h4 id="software-architecture-context-diagram">4.6.1. Software Architecture Context Diagram.</h4>
<h4 id="software-architecture-container-diagrams">4.6.2. Software Architecture Container Diagrams.</h4>
<h4 id="software-architecture-components-diagrams">4.6.3. Software Architecture Components Diagrams.</h4>
<h4 id="software-object-oriented-design">4.7. Software Object-Oriented Design.</h4>
<h4 id="class-diagrams">4.7.1. Class Diagrams.</h4>
<h4 id="class-dictionary">4.7.2. Class Dictionary.</h4>
<h4 id="database-design">4.8. Database Design.</h4>
<h4 id="database-diagram">4.8.1. Database Diagram.</h4>
<h3 id="chapter-5">Capítulo V: Product Implementation, Validation & Deployment</h3>
<h4 id="software-configuration">5.1. Software Configuration Management.</h4>
<h4 id="software-development">5.1.1. Software Development Environment Configuration.</h4>
<h4 id="source-code">5.1.2. Source Code Management.</h4>
<h4 id="source-code-style-guide-and-conventions">5.1.3. Source Code Style Guide & Conventions.</h4>
<h4 id="software-deployment-configuration">5.1.4. Software Deployment Configuration.</h4>
<h4 id="landing-page-services-applications-implementation">5.2. Landing Page, Services & Applications Implementation.</h4>
<h4 id="sprint-x">5.2.X. Sprint n</h4>
<h4 id="sprint-planning-x">5.2.X.1. Sprint Planning n.</h4>
<h4 id="spring-backlog-x">5.2.X.2. Sprint Backlog n.</h4>
<h4 id="development-evidence-for-sprint-review-x">5.2.X.3. Development Evidence for Sprint Review.</h4>
<h4 id="testing-suite-evidence-for-sprint-review">5.2.X.4. Testing Suite Evidence for Sprint Review.</h4>
<h4 id="execution-evidence-for-sprint-review">5.2.X.5. Execution Evidence for Sprint Review.</h4>
<h4 id="services-documentation-evidence-for-sprint-review">5.2.X.6. Services Documentation Evidence for Sprint Review.</h4>
<h4 id="software-deployment-evidence-for-sprint-review">5.2.X.7. Software Deployment Evidence for Sprint Review.</h4>
<h4 id="team-collaboration-insights-during-sprint">5.2.X.8. Team Collaboration Insights during Sprint.</h4>
<h4 id="validation-interviews">5.3. Validation Interviews.</h4>
<h4 id="interview-design-2">5.3.1. Diseño de Entrevistas.</h4>
<h4 id="interview-registry-2">5.3.2. Registro de Entrevistas.</h4>
<h4 id="heuristic-exam">5.3.3. Evaluaciones según heurísticas.</h4>
<h4 id="about-the-productions">5.4. Video About-the-Product.</h4>
<h4 id="conclusions">Conclusiones</h4>
<h4 id="recomendations">Conclusiones y recomendaciones.</h4>
<h4 id="about-the-team">Video About-the-Team.</h4>
<h4 id="bibliography">Bibliografía</h4>
<h4 id="links">Anexos</h4>
