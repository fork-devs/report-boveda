# ***CONTENIDO*** {#contenido}

[**REGISTRO DE VERSIONES DEL INFORME	2**](#registro-de-versiones-del-informe)

[**STUDENT OUTCOME	4**](#student-outcome)

[**CONTENIDO	7**](#contenido)

[**CAPÍTULO I: Introducción	11**](#capítulo-i:-introducción)

[1.1. Startup Profile	11](#1.1.-startup-profile)

[1.1.1. Descripción de la startup	11](#1.1.1.-descripción-de-la-startup)

[1.1.2. Perfiles de integrantes del equipo	13](#1.1.2.-perfiles-de-integrantes-del-equipo)

[1.2. Solution Profile	15](#1.2.-solution-profile)

[1.2.1. Nombre del producto	15](#1.2.1.-nombre-del-producto)

[1.2.2. Antecedentes y problemática	15](#1.2.2.-antecedentes-y-problemática)

[1.2.3. Lean UX Process	19](#1.2.3.-lean-ux-process)

[1.2.3.1. Lean UX Problem Statement	19](#1.2.3.1.-lean-ux-problem-statement)

[1.2.3.2. Lean UX Assumptions	19](#1.2.3.2.-lean-ux-assumptions)

[1.2.3.3. Lean UX Hypothesis Statements	21](#1.2.3.3.-lean-ux-hypothesis-statements)

[1.2.3.4. Lean UX Canvas	23](#1.2.3.4.-lean-ux-canvas)

[1.3. Segmentos objetivo	23](#1.3.-segmentos-objetivo)

[**Capítulo II: Requirements  & Analysis	25**](#capítulo-ii:-requirements-&-analysis)

[2.1. Competidores	25](#2.1.-competidores)

[2.2.3 Análisis de entrevistas	38](#2.2.3-análisis-de-entrevistas)

[2.2.3.1. Segmento 1: Personal de Gestión y Propietarios del Taller	38](#2.2.3.1.-segmento-1:-personal-de-gestión-y-propietarios-del-taller)

[2.2.3.2. Segmento 2: Personal Operativo del Taller	39](#2.2.3.2.-segmento-2:-personal-operativo-del-taller)

[2.3. Needfinding	41](#2.3.-needfinding)

[2.3.1. User Persona	41](#2.3.1.-user-persona)

[2.3.2. User task matrix	44](#2.3.2.-user-task-matrix)

[2.3.3. Empathy Maps	47](#2.3.3.-empathy-maps)

[2.3.4. As-Is Scenario Mapping	49](#2.3.4.-as-is-scenario-mapping)

[2.3.4.1. As-Is Scenario Map del Gestor o Propietario del Taller	49](#2.3.4.1.-as-is-scenario-map-del-gestor-o-propietario-del-taller)

[2.3.4.2. As-Is Scenario Map del Técnico Mecánico	50](#2.3.4.2.-as-is-scenario-map-del-técnico-mecánico)

[CAPÍTULO III: Requirements Specification	50](#capítulo-iii:-requirements-specification)

[3.1. To-Be Scenario Mapping	51](#heading=)

[3.1.1. To-Be Scenario Map del gestor o propietario del taller	51](#heading=)

[3.1.2. To-Be Scenario Map del técnico mecánico	51](#heading=)

[3.2. User Stories	52](#heading=)

[3.2.1. Epics	52](#heading=)

[3.2.2. User Stories y criterios de aceptación	53](#heading=)

[3.3. Impact Map	61](#heading=)

[3.4. Product Backlog	64](#heading=)

[CAPÍTULO IV: Diseño de la Arquitectura de Software	68](#capítulo-iv:-diseño-de-la-arquitectura-de-software)

[4.1. Design Concepts, ViewPoints & ER Diagrams	68](#4.1.-design-concepts,-viewpoints-&-er-diagrams)

[4.1.1. Principles Statements	68](#4.1.1.-principles-statements)

[4.1.1.1. Diseño Guiado por Atributos (Attribute-Driven Design, ADD)	71](#4.1.1.1.-diseño-guiado-por-atributos-\(attribute-driven-design,-add\))

[4.1.1.2. Diseño Guiado por el Dominio (Domain-Driven Design, DDD)	72](#4.1.1.2.-diseño-guiado-por-el-dominio-\(domain-driven-design,-ddd\))

[4.1.1.3. Principios SOLID	72](#4.1.1.3.-principios-solid)

[4.1.1.4. API First (API primero)	73](#4.1.1.4.-api-first-\(api-primero\))

[4.1.1.5. Asíncrono sobre síncrono	73](#4.1.1.5.-asíncrono-sobre-síncrono)

[4.1.1.6. Programación funcional para datos, objetos para el negocio	73](#4.1.1.6.-programación-funcional-para-datos,-objetos-para-el-negocio)

[4.1.1.7. Solo software confiable (gestión de riesgos y selección de tecnología)	74](#4.1.1.7.-solo-software-confiable-\(gestión-de-riesgos-y-selección-de-tecnología\))

[4.1.1.8. Cada taller ve solo lo suyo (multi-tenant seguro)	74](#4.1.1.8.-cada-taller-ve-solo-lo-suyo-\(multi-tenant-seguro\))

[4.1.1.9. Capa Anticorrupción para lo externo (Anti-Corruption Layer, ACL)	74](#4.1.1.9.-capa-anticorrupción-para-lo-externo-\(anti-corruption-layer,-acl\))

[4.1.1.10. Observabilidad	75](#4.1.1.10.-observabilidad)

[4.1.1.11. Seguridad por Diseño (Security by Design)	75](#4.1.1.11.-seguridad-por-diseño-\(security-by-design\))

[4.1.1.12. Resiliencia	75](#4.1.1.12.-resiliencia)

[4.1.1.13. Cómo elegiremos tecnología	76](#4.1.1.13.-cómo-elegiremos-tecnología)

[4.1.2. Approaches Statements Architectural Styles & Patterns	76](#4.1.2.-approaches-statements-architectural-styles-&-patterns)

[4.1.2.1. Approaches Statements	76](#4.1.2.1.-approaches-statements)

[4.1.2.2. Architectural Styles & Patterns	77](#4.1.2.2.-architectural-styles-&-patterns)

[4.1.3. Context Diagram	77](#4.1.3.-context-diagram)

[4.1.4. Approach Driven ViewPoints Diagrams	79](#4.1.4.-approach-driven-viewpoints-diagrams)

[4.1.4.1. Flujos de Actividad por Bounded Context	79](#4.1.4.1.-flujos-de-actividad-por-bounded-context)

[4.1.4.2. Máquinas de Estados por Bounded Context	79](#4.1.4.2.-máquinas-de-estados-por-bounded-context)

[4.1.4.3. Clases de Dominio (DDD) por Bounded Context	80](#4.1.4.3.-clases-de-dominio-\(ddd\)-por-bounded-context)

[4.1.4.4. Diagrama de Contenedores C4	80](#4.1.4.4.-diagrama-de-contenedores-c4)

[4.1.4.5. Diagrama de Componentes C4	82](#4.1.4.5.-diagrama-de-componentes-c4)

[4.1.4.6. Estandarización de Herramientas de Modelado	83](#4.1.4.6.-estandarización-de-herramientas-de-modelado)

[4.1.4. Approach driven ViewPoints Diagrams	84](#4.1.4.-approach-driven-viewpoints-diagrams-1)

[4.1.4.1. Diagrama de Actividad UML	84](#4.1.4.1.-diagrama-de-actividad-uml)

[4.1.4.2. Diagrama de Estado UML	87](#4.1.4.2.-diagrama-de-estado-uml)

[4.1.4.3. Diagrama de Clases UML	88](#4.1.4.3.-diagrama-de-clases-uml)

[4.1.4.4. Diagrama de Contenedores	88](#4.1.4.4.-diagrama-de-contenedores)

[4.1.5. Relational/Non Relational Database Diagram	90](#4.1.5.-relational/non-relational-database-diagram)

[4.1.6. Design Patterns	97](#4.1.6.-design-patterns)

[4.1.6.1. Patrón Gateway: ApiGateway, JwtValidator y PlanRateLimiter	100](#4.1.6.1.-patrón-gateway:-apigateway,-jwtvalidator-y-planratelimiter)

[4.1.6.2. Patrón Repository: RepositorioDeOrdenes, RepositorioDeStock y RepositorioDeComprobantes	101](#4.1.6.2.-patrón-repository:-repositoriodeordenes,-repositoriodestock-y-repositoriodecomprobantes)

[4.1.6.3. Patrón Puertos y Adaptadores: EmisorTributario, PasarelaDePago y ValidadorIdentidad	102](#4.1.6.3.-patrón-puertos-y-adaptadores:-emisortributario,-pasareladepago-y-validadoridentidad)

[4.1.6.4. Patrón Adapter y Capa Anticorrupción: NubefactAdapter, StripeAdapter y ReniecAdapter	102](#4.1.6.4.-patrón-adapter-y-capa-anticorrupción:-nubefactadapter,-stripeadapter-y-reniecadapter)

[4.1.6.5. Patrón Observer con eventos de dominio: OrdenTerminada, FacturaEmitida y AnomaliaDetectada	103](#4.1.6.5.-patrón-observer-con-eventos-de-dominio:-ordenterminada,-facturaemitida-y-anomaliadetectada)

[4.1.6.6. Patrón Outbox: WorkOrderOutboxRelay, BillingOutboxRelay y TenantOutboxRelay	104](#4.1.6.6.-patrón-outbox:-workorderoutboxrelay,-billingoutboxrelay-y-tenantoutboxrelay)

[4.1.6.7. Patrón Saga coreografiada: ReservaStock/LiberaStock y EmisionPendiente/Anulacion	105](#4.1.6.7.-patrón-saga-coreografiada:-reservastock/liberastock-y-emisionpendiente/anulacion)

[4.1.6.8. Patrón Receptor idempotente: IdempotencyFilter e idempotency\_keys	105](#4.1.6.8.-patrón-receptor-idempotente:-idempotencyfilter-e-idempotency_keys)

[4.1.6.9. Patrón Reintento con espera y DLQ: RetryPolicy e integration\_attempts	106](#4.1.6.9.-patrón-reintento-con-espera-y-dlq:-retrypolicy-e-integration_attempts)

[4.1.6.10. Patrón Interruptor de Circuito: StockCircuitBreaker y HubCircuitBreakers	107](#4.1.6.10.-patrón-interruptor-de-circuito:-stockcircuitbreaker-y-hubcircuitbreakers)

[4.1.6.11. Patrón CQRS: IotIngestionWriter y AnalyticsReader	108](#4.1.6.11.-patrón-cqrs:-iotingestionwriter-y-analyticsreader)

[4.1.6.12. Patrón Caché lateral: RucCache y PlacaCache	109](#4.1.6.12.-patrón-caché-lateral:-ruccache-y-placacache)

[4.1.6.13. Patrón Mamparo: TenantBulkheads y pools por servicio	110](#4.1.6.13.-patrón-mamparo:-tenantbulkheads-y-pools-por-servicio)

[4.1.6.14. Patrón Límite de peticiones: PlanRateLimiter con Redis	111](#4.1.6.14.-patrón-límite-de-peticiones:-planratelimiter-con-redis)

[4.1.7. Tactics	112](#4.1.7.-tactics)

[4.1.7.1. Usabilidad (QA-12):	112](#4.1.7.1.-usabilidad-\(qa-12\):)

[4.1.7.2. Disponibilidad (QA-03 y QA-04):	113](#4.1.7.2.-disponibilidad-\(qa-03-y-qa-04\):)

[4.1.7.3. Seguridad (QA-05, QA-06 y QA-07):	113](#4.1.7.3.-seguridad-\(qa-05,-qa-06-y-qa-07\):)

[4.1.7.4. Desempeño (QA-01 y QA-02):	113](#4.1.7.4.-desempeño-\(qa-01-y-qa-02\):)

[4.1.7.5. Interoperabilidad (QA-08):	113](#4.1.7.5.-interoperabilidad-\(qa-08\):)

[4.1.7.6. Tolerancia a Fallos (QA-09):	113](#4.1.7.6.-tolerancia-a-fallos-\(qa-09\):)

[4.1.7.7. Modificabilidad (QA-10):	113](#4.1.7.7.-modificabilidad-\(qa-10\):)

[4.1.7.8. Testabilidad (QA-11):	113](#4.1.7.8.-testabilidad-\(qa-11\):)

[4.2. Architectural Drivers	114](#4.2.-architectural-drivers)

[4.2.1. Design Purpose	114](#4.2.1.-design-purpose)

[4.2.2. Primary Functionality (Primary User Stories)	115](#4.2.2.-primary-functionality-\(primary-user-stories\))

[4.2.3. Quality Attribute Scenarios	117](#4.2.3.-quality-attribute-scenarios)

[4.2.4. Constraints	121](#4.2.4.-constraints)

[4.2.5. Architectural Concerns	122](#4.2.5.-architectural-concerns)

[4.3 ADD Iterations	123](#4.3-add-iterations)

[4.3.1 Iteration 1: Global System Structure & Domain Decomposition	124](#heading=)

[4.3.1.1 Architectural Design Backlog 1	124](#heading=)

[4.3.1.2 Establish Iteration Goal by Selecting Drivers	125](#heading=)

[4.3.1.3 Choose One or More Elements of the System to Refine	125](#heading=)

[4.3.1.4 Choose One or More Design Concepts That Satisfy the Selected Drivers	126](#heading=)

[4.3.1.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces	126](#heading=)

[4.3.1.6 Sketch Views (C4 & UML) and Record Design Decisions	127](#heading=)

[4.3.1.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)	130](#4.3.1.7-analysis-of-current-design-and-review-iteration-goal-\(kanban-board\))

[4.3.2 Iteration 2: Asynchronous Integration, Real-Time IoT Ingestion & Resilience Architecture	132](#4.3.2-iteration-2:-asynchronous-integration,-real-time-iot-ingestion-&-resilience-architecture)

[4.3.2.1 Architectural Design Backlog 2	132](#4.3.2.1-architectural-design-backlog-2)

[4.3.2.2 Establish Iteration Goal by Selecting Drivers	132](#4.3.2.2-establish-iteration-goal-by-selecting-drivers)

[4.3.2.3 Choose One or More Elements of the System to Refine	133](#4.3.2.3-choose-one-or-more-elements-of-the-system-to-refine)

[4.3.2.4 Choose One or More Design Concepts That Satisfy the Selected Drivers	134](#4.3.2.4-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)

[4.3.2.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces	135](#4.3.2.5-instantiate-architectural-elements,-allocate-responsibilities,-and-define-interfaces)

[4.3.2.6 Sketch Views (C4 & UML) and Record Design Decisions	136](#4.3.2.6-sketch-views-\(c4-&-uml\)-and-record-design-decisions)

[4.3.2.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)	138](#4.3.2.7-analysis-of-current-design-and-review-iteration-goal-\(kanban-board\))

[4.3.3. Iteración 3: Seguridad Centralizada, Autenticación/Autorización IAM y Aislamiento Multi-Inquilino (Multi-Tenancy)	139](#4.3.3.-iteración-3:-seguridad-centralizada,-autenticación/autorización-iam-y-aislamiento-multi-inquilino-\(multi-tenancy\))

[4.3.3.1 Architectural Design Backlog 3	140](#4.3.3.1-architectural-design-backlog-3)

[4.3.3.2 Establish Iteration Goal by Selecting Drivers	140](#4.3.3.2-establish-iteration-goal-by-selecting-drivers)

[4.3.3.3 Choose One or More Elements of the System to Refine	140](#4.3.3.3-choose-one-or-more-elements-of-the-system-to-refine)

[4.3.3.4 Choose One or More Design Concepts That Satisfy the Selected Drivers	141](#4.3.3.4-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)

[4.3.3.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces	142](#4.3.3.5-instantiate-architectural-elements,-allocate-responsibilities,-and-define-interfaces)

[4.3.3.6 Sketch Views (C4 & UML) and Record Design Decisions	143](#4.3.3.6-sketch-views-\(c4-&-uml\)-and-record-design-decisions)

[4.3.3.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)	145](#4.3.3.7-analysis-of-current-design-and-review-iteration-goal-\(kanban-board\))

[4.3.4 Iteración 4: Observabilidad Distribuida, Trazabilidad de Extremo a Extremo (OpenTelemetry), Métricas en Tiempo Real y Resiliencia Avanzada (Circuit Breaker & Rate Limiting)	146](#4.3.4-iteración-4:-observabilidad-distribuida,-trazabilidad-de-extremo-a-extremo-\(opentelemetry\),-métricas-en-tiempo-real-y-resiliencia-avanzada-\(circuit-breaker-&-rate-limiting\))

[4.3.4.1 Architectural Design Backlog 4	147](#4.3.4.1-architectural-design-backlog-4)

[4.3.4.2 Establish Iteration Goal by Selecting Drivers	147](#4.3.4.2-establish-iteration-goal-by-selecting-drivers)

[4.3.4.3 Choose One or More Elements of the System to Refine	147](#4.3.4.3-choose-one-or-more-elements-of-the-system-to-refine)

[4.3.4.4 Choose One or More Design Concepts That Satisfy the Selected Drivers	148](#4.3.4.4-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)

[4.3.4.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces	149](#4.3.4.5-instantiate-architectural-elements,-allocate-responsibilities,-and-define-interfaces)

[4.3.4.6 Sketch Views (C4 & UML) and Record Design Decisions	150](#4.3.4.6-sketch-views-\(c4-&-uml\)-and-record-design-decisions)

[4.3.4.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)	152](#4.3.4.7-analysis-of-current-design-and-review-iteration-goal-\(kanban-board\))

[4.3.5 Iteration 5: Real-Time Analytics Rules Engine, Automated FIFO Costing & SUNAT Fiscal Sync	154](#heading=)

[4.3.5.1 Architectural Design Backlog 5	154](#heading=)

[4.3.5.2 Establish Iteration Goal by Selecting Drivers	155](#heading=)

[4.3.5.3 Choose One or More Elements of the System to Refine	155](#heading=)

[4.3.5.4 Choose One or More Design Concepts That Satisfy the Selected Drivers	155](#heading=)

[4.3.5.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces	156](#4.3.5.5-instantiate-architectural-elements,-allocate-responsibilities,-and-define-interfaces)

[4.3.5.6 Sketch Views (C4 & UML) and Record Design Decisions	157](#heading=)

[4.3.5.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)	160](#4.3.5.7-analysis-of-current-design-and-review-iteration-goal-\(kanban-board\))

[Capítulo V: Product Implementation, Validation & Deployment	162](#capítulo-v:-product-implementation,-validation-&-deployment)

[5.1. Testing Suites & General Patterns	162](#5.1.-testing-suites-&-general-patterns)

[5.1.1. Backend Application Core Testing Suite	162](#5.1.1.-backend-application-core-testing-suite)

[5.1.2. Pattern Based Backend Application(s)	164](#5.1.2.-pattern-based-backend-application\(s\))

[5.1.2. Pattern Based Backend Application(s)	165](#5.1.2.-pattern-based-backend-application\(s\)-1)

[5.1.3. Pattern Based Custom Software Library	166](#5.1.3.-pattern-based-custom-software-library)

[5.1.4. Framework Pattern Driven Refactoring Report	167](#5.1.4.-framework-pattern-driven-refactoring-report)

[5.2 Software Configuration Management	168](#5.2-software-configuration-management)

[5.2.1 Software Development Environment Configuration	169](#5.2.1-software-development-environment-configuration)

[5.2.2 Source Code Management	172](#5.2.2-source-code-management)

[5.2.3 Source Code Style Guide & Conventions	174](#5.2.3-source-code-style-guide-&-conventions)

[5.2.4 Software Deployment Configuration	174](#5.2.4-software-deployment-configuration)

[5.3 Microservices Implementation	176](#5.3-microservices-implementation)

[5.3.1 Sprint 1	176](#5.3.1-sprint-1)

[5.3.1.1 Sprint Backlog 1	176](#5.3.1.1-sprint-backlog-1)

[5.3.1.2 Development Evidence for Sprint Review	178](#5.3.1.2-development-evidence-for-sprint-review)

[5.3.1.3 Testing Suite Evidence for Sprint Review	180](#5.3.1.3-testing-suite-evidence-for-sprint-review)

[5.3.1.4 Execution Evidence for Sprint Review	180](#5.3.1.4-execution-evidence-for-sprint-review)

[5.3.1.5 Microservices Documentation Evidence for Sprint Review	182](#5.3.1.5-microservices-documentation-evidence-for-sprint-review)

[5.3.1.6 Software Deployment Evidence for Sprint Review	186](#5.3.1.6-software-deployment-evidence-for-sprint-review)

[5.3.1.7 Team Collaboration Insights during Sprint	187](#5.3.1.7-team-collaboration-insights-during-sprint)

[5.3.1.8 Kanban Board	188](#5.3.1.8-kanban-board)

[Anexo A: Student Outcome 7	189](#anexo-a:-student-outcome-7)

[Anexo B: Informe Individual de Rendimiento:	190](#anexo-b:-informe-individual-de-rendimiento:)

[Anexo C: Exposición del Trabajo Parcial	193](#anexo-c:-exposición-del-trabajo-parcial)

[Bibliografía:	193](#bibliografía:)

## Relaciones

- Hijos:
  - [[anexos/anexo-a-student-outcome-7|Anexo A: Student Outcome 7]]
  - [[anexos/anexo-b-informe-individual-de-rendimiento|Anexo B: Informe Individual de Rendimiento:]]
  - [[anexos/anexo-c-exposicion-del-trabajo-parcial|Anexo C: Exposición del Trabajo Parcial]]
  - [[cierre/bibliografia|Bibliografía:]]
  - [[capitulo-i/capitulo-i-introduccion|CAPÍTULO I: Introducción]]
  - [[capitulo-ii/capitulo-ii-requirements-analysis|Capítulo II: Requirements  & Analysis]]
  - [[capitulo-iii/capitulo-iii-requirements-specification|CAPÍTULO III: Requirements Specification]]
  - [[capitulo-iv/capitulo-iv-diseno-de-la-arquitectura-de-software|CAPÍTULO IV: Diseño de la Arquitectura de Software]]
  - [[capitulo-v/capitulo-v-product-implementation-validation-deployment|Capítulo V: Product Implementation, Validation & Deployment]]
  - [[preliminares/registro-de-versiones-del-informe|REGISTRO DE VERSIONES DEL INFORME]]
  - [[preliminares/student-outcome|STUDENT OUTCOME]]

## Notas del vault

- [[anexos/anexo-a-student-outcome-7|Anexo A: Student Outcome 7]]
- [[anexos/anexo-b-informe-individual-de-rendimiento|Anexo B: Informe Individual de Rendimiento:]]
- [[anexos/anexo-c-exposicion-del-trabajo-parcial|Anexo C: Exposición del Trabajo Parcial]]
- [[cierre/bibliografia|Bibliografía:]]
- [[capitulo-i/capitulo-i-introduccion|CAPÍTULO I: Introducción]]
- [[capitulo-ii/capitulo-ii-requirements-analysis|Capítulo II: Requirements  & Analysis]]
- [[capitulo-iii/capitulo-iii-requirements-specification|CAPÍTULO III: Requirements Specification]]
- [[capitulo-iv/capitulo-iv-diseno-de-la-arquitectura-de-software|CAPÍTULO IV: Diseño de la Arquitectura de Software]]
- [[capitulo-v/capitulo-v-product-implementation-validation-deployment|Capítulo V: Product Implementation, Validation & Deployment]]
- [[preliminares/registro-de-versiones-del-informe|REGISTRO DE VERSIONES DEL INFORME]]
- [[preliminares/student-outcome|STUDENT OUTCOME]]
