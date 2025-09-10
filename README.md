# report

<div align="center">

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img alt="upc-logo" src="assets/upc_logo.png" width="200"/><br>

<strong>Ingeniería de Software - 2025-2</strong><br>
<strong>1ASI0730 - Aplicaciones Web</strong><br>
<strong>NRC: 7432<br>
<strong>Profesor: Oscar Ivan Villafuerte Bazan</strong><br>

<br><strong>Informe del Trabajo Final</strong><br><br>

<strong>Startup: FijasDev</strong><br>
<strong>Producto: PuntoSabor</strong><br>



### Team Members:

|             Member              |   Code    |
|:-------------------------------:|:---------:|
|  Delgado Carrasco, Schneider  | u202321843 |
|  Lopez Goitia, Carlos Alberto  | u202312700 |
|  Tumi Oliden Manuel Ignacio  | u20241c134 |
|  Vega Coronado Fabricio Samir   | u202317000 |
|  Villanueva Andrade Ysaac Ligorio  | u20231c168 |

<strong> Setiembre 2025</strong><br>
</div>

# Registro de Versiones del Informe

| Versión | Fecha      | Autor        | Descripción de modificación                   |
|---------|------------|--------------|-----------------------------------------------|
| 1.0     | 10/09/2025 | Fabricio Vega | Creación de la estructura inicial del reporte |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |

# Project Report Collaboration Insights

---

## Contenido
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
        - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
        - [4.7.2. Class Dictionary](#472-class-dictionary)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**
**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

| Criterio específico                                                                              | Acciones realizadas | Conclusiones |
|--------------------------------------------------------------------------------------------------|---------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.                                  |                     |              |
| Comunica por escrito con efectividad a diferentes rangos de audiencia |                     |              |


# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

FijasDev es una startup orientada al desarrollo de soluciones tecnológicas innovadoras que potencian la visibilidad y el crecimiento de pequeños negocios locales, especialmente en el sector gastronómico. Su proyecto principal, PuntoSabor, es una plataforma web diseñada para conectar a los usuarios con huariques, que son establecimientos de comida tradicional y casera, poco conocidos pero con una oferta culinaria auténtica y de alta calidad.

PuntoSabor nace con el propósito de llenar un vacío existente en el mercado digital, donde los huariques suelen quedar invisibilizados ante las grandes aplicaciones de comida que priorizan restaurantes consolidados y cadenas. A través de una experiencia intuitiva y funcional, la aplicación facilita a los usuarios descubrir, valorar y recomendar estos espacios, generando una comunidad sólida y un canal de promoción eficaz para los dueños de estos negocios.

Esta iniciativa no solo busca promover la cultura gastronómica local y accesible, sino también fomentar un modelo de negocio sostenible para los pequeños emprendedores mediante la incorporación de membresías y planes publicitarios, beneficiando a todos los actores involucrados en el ecosistema.
    
### 1.1.2. Perfiles de integrantes del equipo

    

|                             Miembro                             |                                                                                                                                                                                   Descripción                                                                                                                                                                                   |
|:---------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  |  <br>  |
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Las 5W's y 2H's

#### What? (¿Qué?)
El problema principal es la falta de visibilidad y accesibilidad de los huariques, pequeños negocios de comida tradicional o poco conocidos, en las plataformas digitales actuales. Esto dificulta que los consumidores encuentren opciones económicas y auténticas fuera de los restaurantes populares.

#### Why? (¿Por qué?)
Las plataformas comerciales de comida priorizan grandes establecimientos por su capacidad de inversión y volumen de clientes, dejando fuera a huariques que no pueden competir en marketing digital. Esto genera un vacío donde el usuario no puede encontrar estos lugares de forma fácil y los huariques pierden oportunidades de crecimiento.

#### Where? (¿Dónde?)
Esta problemática se presenta en áreas urbanas y comunidades donde los huariques son comunes pero poco promocionados, especialmente en mercados hispanohablantes donde la cultura gastronómica local es muy rica pero poco digitalizada.

#### When? (¿Dónde?)
La falta de opciones digitales efectivas para huariques es una problemática constante, agudizada con la digitalización acelerada del mercado gastronómico en los últimos años.

#### Who? (¿Quién?)
Los afectados son dos grupos principales:

1. Los dueños de huariques, quienes luchan por atraer clientes y competir en un mercado dominado por grandes restaurantes y cadenas.

2. Los usuarios que desean descubrir comida local sabrosa, económica y auténtica pero no cuentan con un canal especializado para ello.

#### How? (¿Cómo?)
El problema se manifiesta a través de la falta de promoción digital, escasa o nula presencia en mapas y apps de comida, baja interacción con potenciales clientes y ausencia de una comunidad que recomiende estos lugares.

#### How much? (¿Cuánto?)
Este vacío representa una gran oportunidad económica desaprovechada para los dueños de huariques y una pérdida cultural gastronómica para el público. A nivel de mercado, millones de usuarios y miles de pequeños negocios quedan fuera del ecosistema digital gastronómico.

##### 1.2.2.1. Lean UX Problem Statements

- Los pequeños huariques carecen de una plataforma digital accesible y especializada para promocionar sus negocios, lo que limita su capacidad para atraer nuevos clientes y crecer.

- Los usuarios interesados en descubrir comida local auténtica y económica enfrentan dificultades para encontrar opciones fuera de las grandes apps convencionales, donde los huariques rara vez aparecen.

- La ausencia de un sistema confiable de reseñas y calificaciones enfocado en huariques dificulta la creación de confianza y comunidad entre usuarios y dueños de estos negocios.

- Las grandes aplicaciones de comida priorizan restaurantes y cadenas consolidadas, dejando una brecha para los huariques en términos de visibilidad y alcance de mercado.

- Los dueños de huariques, generalmente con recursos limitados, requieren una solución práctica y eficiente que les permita gestionar su presencia digital sin complicaciones técnicas ni costos excesivos.

##### 1.2.2.2. Lean UX Assumptions
#### Business Assumptions
- Se asume que la plataforma PuntoSabor atraerá a un número significativo de dueños de huariques interesados en aumentar su visibilidad digital mediante la membresía o planes publicitarios.

- Se espera que la implementación de un modelo de membresía o planes promocionales genere un flujo constante de ingresos recurrentes para la startup.

- Se considera que el mercado gastronómico local está dispuesto a adoptar una solución digital accesible que potencie negocios pequeños y mejore la experiencia de descubrimiento gastronómico para los usuarios.

- Se supone que una comunidad activa de usuarios y dueños de huariques facilitará el crecimiento orgánico y la retención en la plataforma.
#### User Assumptions
- Se asume que los usuarios valoran encontrar opciones de comida local auténtica, económica y poco convencional que no aparecen en apps masivas.

- Se espera que los usuarios utilicen la app no solo para descubrir huariques, sino también para calificar y dejar reseñas que ayuden a otros usuarios.

- Se considera que la facilidad de uso, el acceso a fotos, especialidades, rango de precios y mapas integrados incentivarán la utilización frecuente de la plataforma por parte de los usuarios.

- Se supone que la posibilidad de guardar favoritos y consultar rankings motivará a los usuarios a regresar y recomendar PuntoSabor dentro de su comunidad.

- Se asume que los dueños o administradores de huariques encontrarán sencillo y valioso el proceso de registrar y gestionar su negocio en la app para aumentar su visibilidad y atraer clientes.

- Se espera que estos usuarios aporten información completa y actualizada de sus huariques, incluyendo fotos, especialidades y precios, para mejorar la experiencia de los visitantes.

- Se considera que incentivos como la membresía y la interacción con la comunidad fomentarán un compromiso activo por parte de los dueños para mantener su presencia digital actualizada y atractiva.

##### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que ofrecer una plataforma fácil e intuitiva para descubrir huariques auténticos y económicos aumentará la cantidad de usuarios que visitan estos negocios. Sabremos que esto es cierto cuando al menos el 60% de los usuarios activos reporten haber visitado un huarique recomendado en la plataforma durante el primer mes de uso.

- Creemos que permitir a los dueños de huariques registrar y gestionar su negocio con fotos, especialidades y precios incentivará su participación activa y mejorará la calidad del contenido disponible. Sabremos que esto es cierto cuando al menos el 50% de los huariques registrados actualicen su información o respondan a reseñas dentro de los primeros tres meses tras su registro.

- Creemos que la integración de mapas y funciones de geolocalización facilitará a los usuarios encontrar huariques cercanos, aumentando la interacción y el uso recurrente de la app. Sabremos que esto es cierto cuando al menos el 70% de las búsquedas y accesos diarios incluyan el uso del mapa durante el primer mes de lanzamiento.

- Creemos que un sistema confiable de reseñas y calificaciones incentivará la confianza en los usuarios y motivará a más personas a utilizar PuntoSabor como su app de referencia para descubrir huariques. Sabremos que esto es cierto cuando el 80% de los huariques tengan al menos cinco reseñas activas y una valoración promedio superior a 4 estrellas en los primeros tres meses.

- Creemos que la oferta de planes de membresía y publicidad atraerá a suficientes dueños de huariques para generar ingresos recurrentes sostenibles. Sabremos que esto es cierto cuando el 30% de los huariques registrados contraten al menos un plan pago durante los primeros seis meses.

##### 1.2.2.4. Lean UX Canvas
![alt text](<assets/Lean UX Canvas - PuntoSabor.jpg>)

## 1.3. Segmentos objetivo
##Exploradores Gastronómicos

- Edad: 18 a 40 años.

- Estilo de vida: Activos, curiosos, buscan descubrir comida auténtica y económica.

- Uso de tecnología: Frecuente, usuarios habituales de apps móviles y web para buscar lugares para comer.

- Necesidad principal: Encontrar huariques poco conocidos con buena sazón y precios accesibles.

- Beneficios buscados: Acceso a recomendaciones confiables, mapas con ubicación cercana, y sistema de reseñas para tomar decisiones informadas.

##Dueños y Administradores de Huariques

- Perfil: Emprendedores y pequeños negocios de comida tradicional o casera.

- Necesidad principal: Promocionar su negocio, aumentar la visibilidad y atraer nuevos clientes de manera sencilla, accesible y rentable.

- Beneficios buscados: Herramienta accesible para gestionar su información en la plataforma, recibir retroalimentación valiosa y utilizar planes de membresía o publicidad para crecer.


# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores


### 2.1.1. Análisis competitivo


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas



### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint  



# Conclusiones

# Bibliografía

# Anexos