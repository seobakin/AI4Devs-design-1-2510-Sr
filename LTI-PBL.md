# LTI - Applicant Tracking System del Futuro para Startups

## Índice

1. [Descripción del Software](#1-descripción-del-software)
2. [Funciones Principales](#2-funciones-principales)
3. [Lean Canvas](#3-lean-canvas)
4. [Casos de Uso Principales](#4-casos-de-uso-principales)
5. [Modelo de Datos](#5-modelo-de-datos)
6. [Diseño del Sistema a Alto Nivel](#6-diseño-del-sistema-a-alto-nivel)
7. [Diagrama C4 - Componente de IA](#7-diagrama-c4---componente-de-ia)

---

## 1. Descripción del Software

### ¿Qué es LTI?

**LTI (Leading Talent Intelligence)** es un Applicant Tracking System (ATS) de nueva generación diseñado específicamente para startups en fase de crecimiento. A diferencia de los ATS tradicionales que fueron construidos para grandes corporaciones y luego simplificados, LTI nace desde cero con la mentalidad startup: simplicidad radical, IA nativa y pricing transparente.

### Valor Añadido

LTI resuelve los tres problemas fundamentales que enfrentan las startups al contratar:

1. **Tiempo escaso**: Los founders y equipos pequeños no pueden dedicar horas a aprender sistemas complejos. LTI ofrece onboarding en menos de 30 minutos con una interfaz que no requiere formación.

2. **Presupuesto limitado**: Mientras los ATS enterprise cuestan $35,000+/año, LTI es gratuito hasta 10 contrataciones anuales y escala con el éxito de la empresa, no con el número de usuarios.

3. **Competencia por talento tech**: Las startups compiten contra Google y Meta por los mismos desarrolladores. LTI nivela el campo con herramientas de IA que automatizan el sourcing, personalizan el outreach y optimizan cada etapa del funnel.

### Ventajas Competitivas

| Característica | LTI | Greenhouse | Lever | Workable |
|----------------|-----|------------|-------|----------|
| **Onboarding** | < 30 min | Semanas | Días | Días |
| **Precio inicial** | Gratis | $6,500/año | Custom | $299/mes |
| **IA nativa** | ✅ Integrada | ❌ Plugins | ❌ Básica | ❌ Add-on |
| **Pricing transparente** | ✅ Público | ❌ Llamada ventas | ❌ Llamada ventas | ✅ Público |
| **Mobile-first** | ✅ Completo | ⚠️ Limitado | ⚠️ Limitado | ⚠️ Limitado |
| **Slack nativo** | ✅ Workflow completo | ⚠️ Notificaciones | ⚠️ Notificaciones | ⚠️ Notificaciones |

**Diferenciadores únicos de LTI:**

- **AI Agent 24/7**: Mientras el equipo duerme, el agente de IA sourcea candidatos, envía mensajes personalizados y programa screenings iniciales.
- **GitHub/Portfolio Import**: Enriquecimiento automático de perfiles técnicos con análisis de repositorios y proyectos.
- **Interview Copilot**: Sugerencias de preguntas en tiempo real durante entrevistas basadas en el CV y respuestas anteriores.
- **Candidate Rediscovery**: IA que automáticamente resurface candidatos pasados cuando abres un nuevo rol compatible.
- **One-Click Job Post**: La IA genera la descripción del puesto y la publica en 15+ job boards simultáneamente.

---

## 2. Funciones Principales

### 2.1 Gestión de Ofertas de Empleo

**Creación asistida por IA**: El usuario describe el rol en lenguaje natural y la IA genera una job description optimizada para SEO y conversión, incluyendo requisitos, responsabilidades, beneficios y cultura.

**Multi-posting automático**: Publicación simultánea en LinkedIn, Indeed, Glassdoor, Stack Overflow Jobs, AngelList, y job boards especializados por sector.

**Career Site Builder**: Constructor drag-and-drop de páginas de carreras con templates modernos, testimonios de empleados auto-generados y analytics de conversión.

### 2.2 Sourcing Inteligente

**AI Agent de Sourcing**: Agente autónomo que busca candidatos en LinkedIn, GitHub, Stack Overflow y otras fuentes 24/7, evaluando fit técnico y cultural.

**Outreach Personalizado**: Generación automática de mensajes de contacto que mencionan proyectos específicos del candidato, papers publicados o contribuciones open source.

**Talent Pool CRM**: Base de datos de candidatos pasados con nurturing automatizado, scoring dinámico y alertas de disponibilidad.

### 2.3 Pipeline de Candidatos

**Kanban Visual**: Vista de pipeline drag-and-drop con stages personalizables por rol (Applied → Screening → Technical → Culture → Offer → Hired).

**Automatizaciones**: Workflows configurables que mueven candidatos, envían emails, notifican al equipo y programan entrevistas automáticamente.

**Bulk Actions**: Acciones masivas sobre candidatos con filtros avanzados (rechazar, mover stage, enviar template, añadir tags).

### 2.4 Evaluación y Entrevistas

**Scorecards Estructurados**: Templates de evaluación por competencias con escalas configurables, campos de evidencia y recomendación final.

**Interview Scheduling**: Self-scheduling para candidatos con disponibilidad del equipo, integración con Google Calendar/Outlook y recordatorios automáticos.

**Interview Copilot**: Durante la entrevista, sugerencias de preguntas follow-up basadas en respuestas, gaps detectados en CV y criterios del scorecard.

**Video Interviews**: Entrevistas asíncronas con preguntas predefinidas, límites de tiempo y transcripción automática con análisis de IA.

### 2.5 Colaboración en Tiempo Real

**Slack/Teams Native**: Workflow completo sin salir del chat - aprobar candidatos, ver CVs resumidos, dar feedback, recibir alertas.

**Feedback Consolidado**: La IA sintetiza todos los scorecards en un resumen ejecutivo con fortalezas, debilidades y recomendación.

**Hiring Manager Portal**: Vista simplificada para managers no-recruiters con acciones one-click y dashboards de sus posiciones.

**@Mentions y Comentarios**: Comunicación contextual en cada candidato con historial completo y notificaciones inteligentes.

### 2.6 Analytics y Reporting

**Dashboard en Tiempo Real**: Métricas clave (time-to-hire, source effectiveness, pipeline velocity, offer acceptance rate) con comparativas históricas.

**Funnel Analytics**: Análisis de conversión por stage, identificación de cuellos de botella y predicciones de tiempo de contratación.

**DE&I Reporting**: Métricas de diversidad en pipeline con anonymización opcional y detección de bias en proceso.

**Custom Reports**: Builder de reportes con filtros avanzados, exportación a Excel/PDF y scheduling de envío automático.

### 2.7 Ofertas y Onboarding

**Offer Management**: Templates de cartas de oferta con variables dinámicas, firma electrónica integrada y tracking de estado.

**Salary Benchmarking**: Datos de mercado integrados con recomendaciones de rango salarial por rol, ubicación y seniority.

**Pre-boarding**: Checklist automatizado post-aceptación con documentación, accesos y welcome package.

---

## 3. Lean Canvas

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'fontSize': '14px'}}}%%
flowchart TB
    subgraph canvas[" "]
        direction TB
        
        subgraph row1[" "]
            direction LR
            subgraph problem["🔴 PROBLEMA"]
                p1["1. ATS enterprise muy caros<br/>($35K+/año)"]
                p2["2. Curva aprendizaje<br/>pronunciada"]
                p3["3. IA añadida como plugin,<br/>no nativa"]
            end
            
            subgraph solution["🟢 SOLUCIÓN"]
                s1["1. Gratis hasta 10<br/>contrataciones/año"]
                s2["2. Onboarding < 30 min,<br/>zero-training"]
                s3["3. IA integrada desde<br/>arquitectura"]
            end
            
            subgraph uvp["⭐ PROPUESTA DE VALOR ÚNICA"]
                uvp1["El ATS que contrata<br/>mientras duermes"]
                uvp2["IA nativa + Simplicidad radical<br/>+ Pricing transparente"]
            end
            
            subgraph advantage["🏰 VENTAJA COMPETITIVA"]
                a1["AI Agent autónomo 24/7"]
                a2["GitHub/Portfolio enrichment"]
                a3["Interview Copilot único"]
            end
            
            subgraph segments["👥 SEGMENTOS"]
                seg1["Startups tech 10-200<br/>empleados"]
                seg2["Series A-B en<br/>scaling"]
                seg3["Founders/COOs sin<br/>dept. RRHH"]
            end
        end
        
        subgraph row2[" "]
            direction LR
            subgraph metrics["📊 MÉTRICAS CLAVE"]
                m1["• MRR / ARR"]
                m2["• Contrataciones/mes"]
                m3["• NPS usuarios"]
                m4["• Time-to-hire clientes"]
            end
            
            subgraph channels["📢 CANALES"]
                c1["• Product Hunt launch"]
                c2["• Partnerships YC/Techstars"]
                c3["• Content marketing SEO"]
                c4["• Referrals de VCs"]
            end
        end
        
        subgraph row3[" "]
            direction LR
            subgraph costs["💰 ESTRUCTURA DE COSTES"]
                cost1["• Infraestructura cloud (AWS/GCP)"]
                cost2["• APIs de IA (OpenAI, Anthropic)"]
                cost3["• Integraciones (LinkedIn, job boards)"]
                cost4["• Equipo desarrollo y soporte"]
            end
            
            subgraph revenue["💵 FUENTES DE INGRESOS"]
                rev1["• Freemium: Gratis hasta 10 hires/año"]
                rev2["• Growth: $299/mes (50 hires/año)"]
                rev3["• Scale: $599/mes (unlimited)"]
                rev4["• Enterprise: Custom + SLA"]
            end
        end
    end
    
    style problem fill:#ffebee
    style solution fill:#e8f5e9
    style uvp fill:#fff3e0
    style advantage fill:#e3f2fd
    style segments fill:#f3e5f5
    style metrics fill:#e0f7fa
    style channels fill:#fce4ec
    style costs fill:#efebe9
    style revenue fill:#e8f5e9
```

### Explicación del Lean Canvas

**Problema**: El mercado de ATS tiene menos del 50% de satisfacción. Las startups enfrentan herramientas caras diseñadas para enterprises, interfaces complejas que requieren semanas de training, y funcionalidades de IA que son plugins superficiales sin integración real.

**Solución**: LTI ataca cada problema directamente con modelo freemium agresivo, UX obsesivamente simple, e IA como ciudadano de primera clase en la arquitectura.

**Propuesta de Valor Única**: "El ATS que contrata mientras duermes" captura la esencia del AI Agent autónomo que sourcea, contacta y pre-filtra candidatos 24/7.

**Ventaja Competitiva**: Ningún competidor ofrece simultáneamente un agente de IA autónomo, integración profunda con ecosistemas de desarrollo (GitHub), y asistencia en tiempo real durante entrevistas.

**Segmentos**: Focus láser en startups tech en fase de scaling donde cada contratación es crítica y los recursos de HR son limitados o inexistentes.

**Métricas Clave**: MRR como norte financiero, contrataciones exitosas como métrica de valor entregado, NPS para product-market fit, y time-to-hire de clientes como prueba de eficacia.

**Canales**: Go-to-market product-led con virality en comunidades startup (Product Hunt, YC, Techstars) complementado con content marketing para SEO.

**Estructura de Costes**: Modelo SaaS típico con costes variables por uso de APIs de IA y fijos de infraestructura y equipo.

**Fuentes de Ingresos**: Freemium para adquisición, tiers claros por volumen de contratación, y enterprise para grandes cuentas con necesidades custom.

---

## 4. Casos de Uso Principales

### 4.1 Caso de Uso 1: Publicación de Oferta de Empleo con IA

**Actor Principal**: Recruiter / Hiring Manager

**Descripción**: El usuario necesita publicar una nueva oferta de empleo. En lugar de escribir manualmente la job description y publicarla en cada job board individualmente, utiliza el sistema de IA de LTI para generar el contenido y publicar automáticamente en múltiples plataformas.

**Precondiciones**:
- Usuario autenticado con permisos de creación de ofertas
- Al menos un departamento configurado en el sistema
- Integraciones con job boards activas

**Flujo Principal**:
1. Usuario accede a "Nueva Oferta"
2. Usuario introduce título del puesto y descripción básica en lenguaje natural
3. Sistema genera job description completa con IA (requisitos, responsabilidades, beneficios)
4. Usuario revisa y edita el contenido generado
5. Usuario selecciona job boards de destino
6. Sistema publica simultáneamente en todos los canales seleccionados
7. Sistema confirma publicación y muestra enlaces

**Flujos Alternativos**:
- 3a. Usuario no está satisfecho con la generación → Regenera con instrucciones adicionales
- 5a. Integración con job board falla → Sistema notifica y permite reintentar
- 6a. Usuario quiere programar publicación → Sistema permite fecha/hora futura

**Postcondiciones**:
- Oferta activa en el sistema y visible en career site
- Publicaciones activas en job boards seleccionados
- Pipeline de candidatos creado para la oferta

```mermaid
sequenceDiagram
    autonumber
    actor R as Recruiter
    participant UI as LTI Frontend
    participant API as LTI API
    participant AI as AI Service
    participant JB as Job Boards API
    participant DB as Database

    R->>UI: Accede a "Nueva Oferta"
    UI->>R: Muestra formulario simplificado
    
    R->>UI: Introduce título y descripción básica
    UI->>API: POST /jobs/generate
    API->>AI: Genera job description
    AI-->>API: JD completa (requisitos, responsabilidades, beneficios)
    API-->>UI: Muestra preview de JD
    
    R->>UI: Revisa y aprueba contenido
    R->>UI: Selecciona job boards (LinkedIn, Indeed, etc.)
    
    UI->>API: POST /jobs/publish
    API->>DB: Guarda oferta
    DB-->>API: Job ID
    
    par Publicación paralela
        API->>JB: Publica en LinkedIn
        API->>JB: Publica en Indeed
        API->>JB: Publica en Glassdoor
    end
    
    JB-->>API: Confirmaciones de publicación
    API->>DB: Actualiza estado publicaciones
    API-->>UI: Resumen de publicaciones
    UI-->>R: Muestra confirmación con enlaces
```

---

### 4.2 Caso de Uso 2: Screening Automatizado de Candidatos

**Actor Principal**: Sistema (AI Agent) / Recruiter (supervisión)

**Descripción**: Cuando llegan nuevas aplicaciones, el AI Agent de LTI analiza automáticamente los CVs, evalúa el fit con los requisitos del puesto, enriquece los perfiles con datos externos (GitHub, LinkedIn), y pre-filtra candidatos clasificándolos por prioridad. El recruiter supervisa y puede ajustar las decisiones del sistema.

**Precondiciones**:
- Oferta de empleo activa con requisitos definidos
- AI Agent de screening activado para la oferta
- Permisos de auto-screening configurados

**Flujo Principal**:
1. Candidato aplica a través de career site o job board
2. Sistema recibe aplicación y CV
3. AI Agent parsea CV extrayendo datos estructurados
4. AI Agent busca perfiles públicos del candidato (LinkedIn, GitHub)
5. AI Agent evalúa match con requisitos del puesto
6. Sistema clasifica candidato (Hot/Warm/Cold) y asigna score
7. Sistema mueve candidato al stage correspondiente del pipeline
8. Sistema notifica al recruiter de candidatos prioritarios

**Flujos Alternativos**:
- 3a. CV en formato no soportado → Sistema solicita re-upload
- 4a. No se encuentran perfiles públicos → Continúa solo con datos del CV
- 6a. Score bajo umbral → Sistema rechaza automáticamente con email personalizado
- 8a. Candidato Hot → Sistema programa screening call automáticamente

**Postcondiciones**:
- Candidato en pipeline con score y clasificación
- Perfil enriquecido con datos externos
- Recruiter notificado si es candidato prioritario
- Métricas de funnel actualizadas

```mermaid
sequenceDiagram
    autonumber
    actor C as Candidato
    participant CS as Career Site
    participant API as LTI API
    participant AI as AI Agent
    participant EXT as APIs Externas
    participant DB as Database
    participant N as Notifications
    actor R as Recruiter

    C->>CS: Aplica a oferta
    CS->>API: POST /applications
    API->>DB: Guarda aplicación
    API->>AI: Trigger screening
    
    rect rgb(240, 248, 255)
        Note over AI: Proceso de Screening Automático
        AI->>AI: Parsea CV (NLP)
        AI->>EXT: Busca perfil LinkedIn
        EXT-->>AI: Datos LinkedIn
        AI->>EXT: Busca perfil GitHub
        EXT-->>AI: Repos y contribuciones
        AI->>AI: Evalúa match con requisitos
        AI->>AI: Calcula score (0-100)
    end
    
    AI->>DB: Actualiza perfil enriquecido
    AI->>DB: Guarda score y clasificación
    
    alt Score >= 80 (Hot)
        AI->>DB: Mueve a "Screening" stage
        AI->>N: Alerta prioritaria
        N->>R: Push notification + Slack
    else Score 50-79 (Warm)
        AI->>DB: Mantiene en "Applied"
        AI->>N: Notificación estándar
        N->>R: Email resumen diario
    else Score < 50 (Cold)
        AI->>DB: Mueve a "Rejected"
        AI->>N: Email rechazo personalizado
        N->>C: Email de agradecimiento
    end
    
    R->>API: GET /candidates/{id}
    API-->>R: Perfil completo con score y análisis
```

---

### 4.3 Caso de Uso 3: Evaluación Colaborativa Post-Entrevista

**Actor Principal**: Entrevistadores (múltiples) / Hiring Manager

**Descripción**: Después de una ronda de entrevistas, múltiples entrevistadores deben completar sus scorecards de forma independiente. El sistema consolida el feedback, la IA genera un resumen ejecutivo con análisis de consenso/discrepancias, y el hiring manager toma la decisión final de avanzar o rechazar al candidato.

**Precondiciones**:
- Entrevista completada con múltiples entrevistadores
- Scorecards configurados para el tipo de entrevista
- Todos los entrevistadores con acceso al sistema

**Flujo Principal**:
1. Sistema envía recordatorio post-entrevista a entrevistadores
2. Cada entrevistador accede a su scorecard pendiente
3. Entrevistador completa evaluación por competencias
4. Entrevistador añade notas y recomendación final
5. Sistema detecta cuando todos los scorecards están completos
6. AI consolida feedback y genera resumen ejecutivo
7. Sistema notifica al Hiring Manager
8. Hiring Manager revisa resumen y toma decisión
9. Sistema actualiza estado del candidato y notifica al equipo

**Flujos Alternativos**:
- 2a. Entrevistador no completa en 24h → Sistema envía recordatorio
- 4a. Evaluaciones muy discrepantes → Sistema alerta para calibración
- 8a. Hiring Manager solicita entrevista adicional → Sistema programa nueva ronda
- 8b. Decisión es avanzar → Sistema genera y envía oferta

**Postcondiciones**:
- Scorecards completos y consolidados
- Resumen ejecutivo disponible
- Candidato movido al siguiente stage o rechazado
- Historial de decisión documentado para compliance

```mermaid
sequenceDiagram
    autonumber
    participant S as Sistema
    participant N as Notifications
    actor E1 as Entrevistador 1
    actor E2 as Entrevistador 2
    actor E3 as Entrevistador 3
    participant API as LTI API
    participant AI as AI Service
    participant DB as Database
    actor HM as Hiring Manager

    Note over S: Entrevista finalizada
    S->>N: Trigger recordatorios
    
    par Notificaciones paralelas
        N->>E1: Email + Slack: Completar scorecard
        N->>E2: Email + Slack: Completar scorecard
        N->>E3: Email + Slack: Completar scorecard
    end
    
    rect rgb(255, 248, 240)
        Note over E1,E3: Evaluación independiente (sin ver otros scores)
        E1->>API: POST /scorecards (competencias + notas + recomendación)
        E2->>API: POST /scorecards (competencias + notas + recomendación)
        E3->>API: POST /scorecards (competencias + notas + recomendación)
    end
    
    API->>DB: Guarda scorecards
    API->>S: Verifica completitud
    
    S->>AI: Consolidar feedback
    AI->>AI: Analiza consenso/discrepancias
    AI->>AI: Genera resumen ejecutivo
    AI->>AI: Calcula score promedio ponderado
    AI-->>DB: Guarda análisis consolidado
    
    S->>N: Notifica a Hiring Manager
    N->>HM: Email + Slack: Feedback listo para revisión
    
    HM->>API: GET /candidates/{id}/feedback-summary
    API-->>HM: Resumen ejecutivo + scorecards individuales
    
    alt Decisión: Avanzar
        HM->>API: POST /candidates/{id}/advance
        API->>DB: Actualiza stage
        API->>N: Notifica equipo
    else Decisión: Rechazar
        HM->>API: POST /candidates/{id}/reject
        API->>DB: Actualiza estado
        API->>N: Email rechazo a candidato
    else Decisión: Más entrevistas
        HM->>API: POST /interviews/schedule
        API->>S: Programa nueva ronda
    end
```

---

## 5. Modelo de Datos

### 5.1 Diagrama Entidad-Relación

```mermaid
erDiagram
    ORGANIZATION ||--o{ USER : "tiene"
    ORGANIZATION ||--o{ DEPARTMENT : "tiene"
    ORGANIZATION ||--o{ JOB : "publica"
    ORGANIZATION ||--o{ CANDIDATE : "almacena"
    
    USER ||--o{ JOB : "crea"
    USER ||--o{ INTERVIEW : "realiza"
    USER ||--o{ SCORECARD : "completa"
    USER ||--o{ COMMENT : "escribe"
    USER ||--o{ ACTIVITY_LOG : "genera"
    
    DEPARTMENT ||--o{ JOB : "pertenece"
    
    JOB ||--o{ APPLICATION : "recibe"
    JOB ||--o{ JOB_POSTING : "se publica en"
    JOB ||--o{ PIPELINE_STAGE : "tiene"
    JOB ||--o{ SCORECARD_TEMPLATE : "usa"
    
    CANDIDATE ||--o{ APPLICATION : "envía"
    CANDIDATE ||--o{ CANDIDATE_TAG : "tiene"
    CANDIDATE ||--o{ CANDIDATE_SOURCE : "viene de"
    CANDIDATE ||--o{ ENRICHMENT_DATA : "se enriquece con"
    
    APPLICATION ||--o{ INTERVIEW : "programa"
    APPLICATION ||--o{ SCORECARD : "evalúa"
    APPLICATION ||--o{ COMMENT : "recibe"
    APPLICATION ||--o{ OFFER : "genera"
    APPLICATION ||--o{ ACTIVITY_LOG : "registra"
    APPLICATION }o--|| PIPELINE_STAGE : "está en"
    
    INTERVIEW ||--o{ SCORECARD : "produce"
    
    OFFER ||--o{ OFFER_APPROVAL : "requiere"
    
    JOB_BOARD ||--o{ JOB_POSTING : "recibe"

    ORGANIZATION {
        uuid id PK
        string name
        string slug
        string plan_type
        jsonb settings
        timestamp created_at
        timestamp updated_at
    }
    
    USER {
        uuid id PK
        uuid organization_id FK
        string email
        string name
        string role
        string avatar_url
        jsonb preferences
        timestamp last_login_at
        timestamp created_at
    }
    
    DEPARTMENT {
        uuid id PK
        uuid organization_id FK
        string name
        uuid parent_id FK
        timestamp created_at
    }
    
    JOB {
        uuid id PK
        uuid organization_id FK
        uuid department_id FK
        uuid created_by FK
        string title
        text description
        text requirements
        string employment_type
        string location_type
        string location
        string salary_range
        string status
        integer openings
        timestamp published_at
        timestamp closed_at
        timestamp created_at
        timestamp updated_at
    }
    
    CANDIDATE {
        uuid id PK
        uuid organization_id FK
        string email
        string first_name
        string last_name
        string phone
        string linkedin_url
        string github_url
        string portfolio_url
        text resume_text
        string resume_url
        jsonb parsed_resume
        integer ai_score
        timestamp created_at
        timestamp updated_at
    }
    
    APPLICATION {
        uuid id PK
        uuid job_id FK
        uuid candidate_id FK
        uuid current_stage_id FK
        string source
        string status
        integer ai_match_score
        jsonb ai_analysis
        timestamp applied_at
        timestamp updated_at
    }
    
    PIPELINE_STAGE {
        uuid id PK
        uuid job_id FK
        string name
        integer order_index
        string stage_type
        boolean is_rejection
        jsonb automation_rules
    }
    
    INTERVIEW {
        uuid id PK
        uuid application_id FK
        uuid interviewer_id FK
        string interview_type
        timestamp scheduled_at
        integer duration_minutes
        string location
        string meeting_url
        string status
        timestamp completed_at
    }
    
    SCORECARD {
        uuid id PK
        uuid interview_id FK
        uuid application_id FK
        uuid user_id FK
        uuid template_id FK
        jsonb ratings
        text notes
        string recommendation
        integer overall_score
        timestamp submitted_at
    }
    
    SCORECARD_TEMPLATE {
        uuid id PK
        uuid job_id FK
        string name
        string interview_type
        jsonb competencies
        jsonb rating_scale
    }
    
    COMMENT {
        uuid id PK
        uuid application_id FK
        uuid user_id FK
        text content
        boolean is_private
        timestamp created_at
    }
    
    OFFER {
        uuid id PK
        uuid application_id FK
        uuid created_by FK
        decimal salary
        string currency
        date start_date
        text terms
        string status
        string document_url
        timestamp sent_at
        timestamp responded_at
    }
    
    OFFER_APPROVAL {
        uuid id PK
        uuid offer_id FK
        uuid approver_id FK
        string status
        text comments
        timestamp responded_at
    }
    
    JOB_BOARD {
        uuid id PK
        string name
        string api_type
        jsonb credentials
        boolean is_active
    }
    
    JOB_POSTING {
        uuid id PK
        uuid job_id FK
        uuid job_board_id FK
        string external_id
        string external_url
        string status
        timestamp posted_at
        timestamp expires_at
    }
    
    CANDIDATE_TAG {
        uuid id PK
        uuid candidate_id FK
        string tag_name
        string tag_color
    }
    
    CANDIDATE_SOURCE {
        uuid id PK
        uuid candidate_id FK
        string source_type
        string source_detail
        timestamp sourced_at
    }
    
    ENRICHMENT_DATA {
        uuid id PK
        uuid candidate_id FK
        string data_type
        jsonb data
        timestamp fetched_at
    }
    
    ACTIVITY_LOG {
        uuid id PK
        uuid organization_id FK
        uuid user_id FK
        uuid application_id FK
        string action_type
        jsonb metadata
        timestamp created_at
    }
```

### 5.2 Descripción de Entidades

#### Entidades Principales

| Entidad | Descripción | Atributos Clave |
|---------|-------------|-----------------|
| **ORGANIZATION** | Empresa cliente de LTI (tenant) | id, name, slug, plan_type, settings |
| **USER** | Usuario del sistema (recruiter, hiring manager, admin) | id, email, name, role, organization_id |
| **DEPARTMENT** | Departamento/área de la organización | id, name, organization_id, parent_id |
| **JOB** | Oferta de empleo/posición abierta | id, title, description, status, department_id |
| **CANDIDATE** | Persona que aplica o es sourceada | id, email, name, resume, ai_score |
| **APPLICATION** | Candidatura de un candidato a un job específico | id, job_id, candidate_id, status, ai_match_score |

#### Entidades de Proceso

| Entidad | Descripción | Atributos Clave |
|---------|-------------|-----------------|
| **PIPELINE_STAGE** | Etapa del proceso de selección | id, job_id, name, order_index, automation_rules |
| **INTERVIEW** | Entrevista programada | id, application_id, interviewer_id, scheduled_at, status |
| **SCORECARD** | Evaluación de entrevista completada | id, interview_id, ratings, recommendation, overall_score |
| **SCORECARD_TEMPLATE** | Plantilla de evaluación por tipo de entrevista | id, job_id, competencies, rating_scale |
| **OFFER** | Oferta de trabajo generada | id, application_id, salary, status, document_url |
| **OFFER_APPROVAL** | Aprobación requerida para oferta | id, offer_id, approver_id, status |

#### Entidades de Soporte

| Entidad | Descripción | Atributos Clave |
|---------|-------------|-----------------|
| **JOB_BOARD** | Integración con portal de empleo externo | id, name, api_type, credentials |
| **JOB_POSTING** | Publicación de job en job board específico | id, job_id, job_board_id, external_url, status |
| **COMMENT** | Comentario/nota en una aplicación | id, application_id, user_id, content, is_private |
| **CANDIDATE_TAG** | Etiqueta asignada a candidato | id, candidate_id, tag_name, tag_color |
| **CANDIDATE_SOURCE** | Origen del candidato | id, candidate_id, source_type, source_detail |
| **ENRICHMENT_DATA** | Datos externos enriquecidos (LinkedIn, GitHub) | id, candidate_id, data_type, data |
| **ACTIVITY_LOG** | Registro de actividad para auditoría | id, action_type, user_id, application_id, metadata |

### 5.3 Relaciones Principales

1. **Organization → Users/Jobs/Candidates**: Multi-tenancy donde cada organización tiene sus propios datos aislados.

2. **Job → Applications → Candidate**: Una oferta recibe múltiples aplicaciones, cada una vinculada a un candidato. Un candidato puede tener múltiples aplicaciones (a diferentes jobs).

3. **Application → Pipeline_Stage**: Cada aplicación está en exactamente una etapa del pipeline en un momento dado.

4. **Application → Interviews → Scorecards**: Una aplicación puede tener múltiples entrevistas, y cada entrevista produce uno o más scorecards (uno por entrevistador).

5. **Job → Scorecard_Templates**: Cada job tiene templates de scorecard configurados para diferentes tipos de entrevista (technical, cultural, etc.).

6. **Candidate → Enrichment_Data**: Un candidato puede tener múltiples registros de enriquecimiento de diferentes fuentes (LinkedIn, GitHub, etc.).

---

## 6. Diseño del Sistema a Alto Nivel

### 6.1 Descripción de la Arquitectura

LTI sigue una arquitectura de **microservicios moderada** con un **API Gateway** como punto de entrada único. Esta decisión balancea la simplicidad de un monolito (apropiada para una startup) con la flexibilidad de escalar componentes críticos de forma independiente.

**Principios arquitectónicos:**

1. **API-First**: Toda funcionalidad se expone a través de APIs RESTful documentadas, permitiendo integraciones y un frontend desacoplado.

2. **Event-Driven para procesos asíncronos**: Operaciones como parsing de CVs, enriquecimiento de datos y notificaciones se manejan mediante colas de mensajes.

3. **Multi-tenancy con Row Level Security**: Base de datos compartida con aislamiento a nivel de fila usando políticas de PostgreSQL.

4. **Separation of Concerns**: El AI Service es independiente para poder escalar según demanda y actualizar modelos sin afectar el core.

**Componentes principales:**

- **API Gateway**: Autenticación, rate limiting, routing y logging centralizado.
- **Core API**: Lógica de negocio principal (jobs, candidates, applications, interviews).
- **AI Service**: Procesamiento de IA (parsing CVs, scoring, generación de contenido, AI Agent).
- **Integration Service**: Conexiones con sistemas externos (job boards, calendarios, HRIS).
- **Notification Service**: Gestión de emails, push notifications y webhooks.
- **Real-time Service**: WebSockets para actualizaciones en tiempo real y colaboración.

### 6.2 Diagrama de Arquitectura

```mermaid
flowchart TB
    subgraph clients["Clientes"]
        WEB["🌐 Web App<br/>(Next.js)"]
        MOBILE["📱 Mobile App<br/>(React Native)"]
        SLACK["💬 Slack Bot"]
        EXT_API["🔌 API Externa<br/>(Integraciones)"]
    end
    
    subgraph edge["Edge Layer"]
        CDN["☁️ CDN<br/>(CloudFront)"]
        LB["⚖️ Load Balancer<br/>(ALB)"]
    end
    
    subgraph gateway["API Gateway Layer"]
        APIGW["🚪 API Gateway<br/>(Kong/AWS API GW)"]
        AUTH["🔐 Auth Service<br/>(Clerk/Auth0)"]
    end
    
    subgraph services["Application Services"]
        CORE["📋 Core API<br/>(NestJS)"]
        AI["🤖 AI Service<br/>(Python/FastAPI)"]
        INTEGRATION["🔗 Integration Service<br/>(NestJS)"]
        NOTIFICATION["📧 Notification Service<br/>(NestJS)"]
        REALTIME["⚡ Real-time Service<br/>(Socket.io)"]
    end
    
    subgraph ai_components["AI Components"]
        LLM["🧠 LLM Provider<br/>(OpenAI/Anthropic)"]
        PARSER["📄 CV Parser<br/>(Custom NLP)"]
        SCORER["📊 Match Scorer<br/>(ML Model)"]
        AGENT["🤖 AI Agent<br/>(Autonomous)"]
    end
    
    subgraph data["Data Layer"]
        PG[("🐘 PostgreSQL<br/>(Primary DB)")]
        REDIS[("⚡ Redis<br/>(Cache/Sessions)")]
        ES[("🔍 OpenSearch<br/>(Full-text Search)")]
        S3["📁 S3<br/>(File Storage)"]
    end
    
    subgraph queue["Message Queue"]
        BULL["📬 BullMQ<br/>(Job Queue)"]
    end
    
    subgraph external["Servicios Externos"]
        LINKEDIN["LinkedIn API"]
        INDEED["Indeed API"]
        GMAIL["Gmail/Calendar"]
        GITHUB["GitHub API"]
    end
    
    %% Client connections
    WEB --> CDN
    MOBILE --> CDN
    SLACK --> LB
    EXT_API --> LB
    CDN --> LB
    LB --> APIGW
    
    %% Gateway connections
    APIGW --> AUTH
    APIGW --> CORE
    APIGW --> REALTIME
    
    %% Service connections
    CORE --> PG
    CORE --> REDIS
    CORE --> ES
    CORE --> S3
    CORE --> BULL
    
    AI --> LLM
    AI --> PARSER
    AI --> SCORER
    AI --> AGENT
    AI --> PG
    AI --> REDIS
    
    INTEGRATION --> external
    INTEGRATION --> BULL
    
    NOTIFICATION --> BULL
    
    REALTIME --> REDIS
    
    %% Queue connections
    BULL --> AI
    BULL --> INTEGRATION
    BULL --> NOTIFICATION
    
    %% Styling
    classDef clientStyle fill:#e1f5fe,stroke:#01579b
    classDef edgeStyle fill:#f3e5f5,stroke:#7b1fa2
    classDef gatewayStyle fill:#fff3e0,stroke:#e65100
    classDef serviceStyle fill:#e8f5e9,stroke:#2e7d32
    classDef aiStyle fill:#fce4ec,stroke:#c2185b
    classDef dataStyle fill:#e0f2f1,stroke:#00695c
    classDef queueStyle fill:#fff8e1,stroke:#f57f17
    classDef externalStyle fill:#f5f5f5,stroke:#616161
    
    class WEB,MOBILE,SLACK,EXT_API clientStyle
    class CDN,LB edgeStyle
    class APIGW,AUTH gatewayStyle
    class CORE,AI,INTEGRATION,NOTIFICATION,REALTIME serviceStyle
    class LLM,PARSER,SCORER,AGENT aiStyle
    class PG,REDIS,ES,S3 dataStyle
    class BULL queueStyle
    class LINKEDIN,INDEED,GMAIL,GITHUB externalStyle
```

### 6.3 Descripción de Componentes

#### Frontend Layer
- **Web App (Next.js)**: SPA con SSR para SEO en career sites. Dashboard principal para recruiters.
- **Mobile App (React Native)**: Versión móvil para gestión on-the-go, notificaciones push, quick actions.
- **Slack Bot**: Interfaz conversacional para aprobar candidatos, dar feedback, recibir alertas.

#### Edge Layer
- **CDN (CloudFront)**: Caché de assets estáticos, career sites, y respuestas de API frecuentes.
- **Load Balancer (ALB)**: Distribución de tráfico, health checks, terminación SSL.

#### Gateway Layer
- **API Gateway**: Punto de entrada único. Rate limiting por tenant, logging centralizado, routing.
- **Auth Service**: Autenticación (email, Google, SSO SAML), gestión de sesiones, RBAC.

#### Application Services
- **Core API**: CRUD de entidades principales, lógica de negocio, validaciones, permisos.
- **AI Service**: Procesamiento de IA aislado para escalar independientemente.
- **Integration Service**: Conectores con sistemas externos, manejo de webhooks entrantes/salientes.
- **Notification Service**: Templates de email, envío multicanal, preferencias de usuario.
- **Real-time Service**: WebSockets para actualizaciones live, presencia, colaboración.

#### Data Layer
- **PostgreSQL**: Base de datos principal con Row Level Security para multi-tenancy.
- **Redis**: Cache de sesiones, rate limiting, pub/sub para real-time.
- **OpenSearch**: Búsqueda full-text de candidatos, jobs, notas.
- **S3**: Almacenamiento de CVs, documentos, archivos adjuntos.

#### Message Queue
- **BullMQ**: Cola de trabajos para procesos asíncronos (parsing, emails, integraciones).

---

## 7. Diagrama C4 - Componente de IA

He seleccionado el **AI Service** para el diagrama C4 en profundidad porque es el componente más diferenciador y complejo de LTI.

### 7.1 C4 - Nivel 1: Contexto del Sistema

```mermaid
flowchart TB
    subgraph boundary[" "]
        LTI["🏢 LTI System<br/><br/>ATS con IA nativa para<br/>startups en crecimiento"]
    end
    
    RECRUITER["👤 Recruiter<br/><br/>Publica ofertas, gestiona<br/>candidatos, realiza entrevistas"]
    CANDIDATE["👤 Candidato<br/><br/>Aplica a ofertas,<br/>completa assessments"]
    HM["👤 Hiring Manager<br/><br/>Revisa candidatos,<br/>aprueba ofertas"]
    
    LINKEDIN["🔗 LinkedIn<br/><br/>Sourcing de candidatos,<br/>publicación de ofertas"]
    JOBBOARDS["📋 Job Boards<br/><br/>Indeed, Glassdoor,<br/>portales especializados"]
    CALENDAR["📅 Calendar<br/><br/>Google Calendar,<br/>Outlook"]
    LLM_EXT["🧠 LLM Providers<br/><br/>OpenAI, Anthropic<br/>para generación de IA"]
    
    RECRUITER -->|"Gestiona proceso<br/>de selección"| LTI
    CANDIDATE -->|"Aplica y<br/>entrevista"| LTI
    HM -->|"Revisa y<br/>decide"| LTI
    
    LTI -->|"Sourcea candidatos<br/>publica ofertas"| LINKEDIN
    LTI -->|"Publica ofertas<br/>recibe aplicaciones"| JOBBOARDS
    LTI -->|"Programa<br/>entrevistas"| CALENDAR
    LTI -->|"Genera contenido<br/>analiza CVs"| LLM_EXT
    
    style LTI fill:#1168bd,stroke:#0b4884,color:white
    style RECRUITER fill:#08427b,stroke:#052e56,color:white
    style CANDIDATE fill:#08427b,stroke:#052e56,color:white
    style HM fill:#08427b,stroke:#052e56,color:white
    style LINKEDIN fill:#999999,stroke:#666666,color:white
    style JOBBOARDS fill:#999999,stroke:#666666,color:white
    style CALENDAR fill:#999999,stroke:#666666,color:white
    style LLM_EXT fill:#999999,stroke:#666666,color:white
```

### 7.2 C4 - Nivel 2: Contenedores

```mermaid
flowchart TB
    subgraph users["Usuarios"]
        RECRUITER["👤 Recruiter"]
        HM["👤 Hiring Manager"]
    end
    
    subgraph lti["LTI System"]
        WEB["🌐 Web Application<br/><br/>Next.js, TypeScript<br/>Dashboard de reclutamiento"]
        
        APIGW["🚪 API Gateway<br/><br/>Kong<br/>Routing, Auth, Rate Limiting"]
        
        CORE["📋 Core API<br/><br/>NestJS, TypeScript<br/>Lógica de negocio principal"]
        
        AI_SVC["🤖 AI Service<br/><br/>Python, FastAPI<br/>Procesamiento de IA"]
        
        NOTIF["📧 Notification Service<br/><br/>NestJS<br/>Emails, Push, Webhooks"]
        
        PG[("🐘 PostgreSQL<br/><br/>Base de datos principal")]
        
        REDIS[("⚡ Redis<br/><br/>Cache, Colas")]
        
        S3["📁 S3<br/><br/>Archivos, CVs"]
    end
    
    subgraph external["Sistemas Externos"]
        LLM["🧠 OpenAI/Anthropic"]
        LINKEDIN["🔗 LinkedIn API"]
        GITHUB["🐙 GitHub API"]
    end
    
    RECRUITER -->|"HTTPS"| WEB
    HM -->|"HTTPS"| WEB
    
    WEB -->|"JSON/HTTPS"| APIGW
    APIGW -->|"JSON/HTTPS"| CORE
    APIGW -->|"JSON/HTTPS"| AI_SVC
    
    CORE -->|"SQL"| PG
    CORE -->|"Pub/Sub"| REDIS
    CORE -->|"Async Jobs"| AI_SVC
    CORE -->|"Events"| NOTIF
    
    AI_SVC -->|"SQL"| PG
    AI_SVC -->|"Cache"| REDIS
    AI_SVC -->|"Files"| S3
    AI_SVC -->|"API Calls"| LLM
    AI_SVC -->|"API Calls"| LINKEDIN
    AI_SVC -->|"API Calls"| GITHUB
    
    NOTIF -->|"SQL"| PG
    
    style WEB fill:#438dd5,stroke:#2e6295,color:white
    style APIGW fill:#438dd5,stroke:#2e6295,color:white
    style CORE fill:#438dd5,stroke:#2e6295,color:white
    style AI_SVC fill:#438dd5,stroke:#2e6295,color:white
    style NOTIF fill:#438dd5,stroke:#2e6295,color:white
    style PG fill:#438dd5,stroke:#2e6295,color:white
    style REDIS fill:#438dd5,stroke:#2e6295,color:white
    style S3 fill:#438dd5,stroke:#2e6295,color:white
```

### 7.3 C4 - Nivel 3: Componentes del AI Service

```mermaid
flowchart TB
    subgraph external_in["Entradas"]
        CORE_API["📋 Core API"]
        QUEUE["📬 Job Queue<br/>(BullMQ)"]
    end
    
    subgraph ai_service["AI Service (Python/FastAPI)"]
        
        subgraph api_layer["API Layer"]
            ROUTER["🚦 API Router<br/><br/>FastAPI endpoints<br/>Validación de requests"]
            WORKER["⚙️ Queue Worker<br/><br/>Procesa jobs async<br/>Retry logic"]
        end
        
        subgraph processing["Processing Components"]
            CV_PARSER["📄 CV Parser<br/><br/>Extrae datos estructurados<br/>de CVs (PDF, DOCX)"]
            
            ENRICHER["🔍 Profile Enricher<br/><br/>Obtiene datos de LinkedIn,<br/>GitHub, portfolio"]
            
            SCORER["📊 Match Scorer<br/><br/>Evalúa fit candidato-job<br/>ML + heurísticas"]
            
            GENERATOR["✍️ Content Generator<br/><br/>Genera JDs, emails,<br/>preguntas entrevista"]
            
            AGENT["🤖 AI Agent<br/><br/>Sourcing autónomo<br/>Outreach automatizado"]
        end
        
        subgraph llm_layer["LLM Abstraction Layer"]
            LLM_CLIENT["🧠 LLM Client<br/><br/>Abstracción multi-provider<br/>OpenAI, Anthropic, local"]
            
            PROMPT_MGR["📝 Prompt Manager<br/><br/>Templates versionados<br/>A/B testing"]
            
            CACHE["💾 Response Cache<br/><br/>Cachea respuestas<br/>similares"]
        end
        
        subgraph data_layer["Data Layer"]
            REPO["🗃️ Repository<br/><br/>Acceso a PostgreSQL<br/>SQLAlchemy"]
            
            VECTOR_STORE["🎯 Vector Store<br/><br/>Embeddings de candidatos<br/>Búsqueda semántica"]
            
            FILE_STORE["📁 File Store<br/><br/>Acceso a S3<br/>CVs procesados"]
        end
    end
    
    subgraph external_out["Servicios Externos"]
        OPENAI["OpenAI API"]
        ANTHROPIC["Anthropic API"]
        LINKEDIN["LinkedIn API"]
        GITHUB["GitHub API"]
        PG[("PostgreSQL")]
        S3["S3"]
    end
    
    %% Input connections
    CORE_API -->|"HTTP sync"| ROUTER
    QUEUE -->|"Job events"| WORKER
    
    %% Router connections
    ROUTER --> CV_PARSER
    ROUTER --> SCORER
    ROUTER --> GENERATOR
    
    %% Worker connections
    WORKER --> CV_PARSER
    WORKER --> ENRICHER
    WORKER --> AGENT
    
    %% Processing to LLM
    CV_PARSER --> LLM_CLIENT
    SCORER --> LLM_CLIENT
    GENERATOR --> LLM_CLIENT
    AGENT --> LLM_CLIENT
    
    %% LLM layer connections
    LLM_CLIENT --> PROMPT_MGR
    LLM_CLIENT --> CACHE
    
    %% Processing to Data
    CV_PARSER --> REPO
    CV_PARSER --> FILE_STORE
    ENRICHER --> REPO
    SCORER --> VECTOR_STORE
    AGENT --> REPO
    
    %% External connections
    LLM_CLIENT --> OPENAI
    LLM_CLIENT --> ANTHROPIC
    ENRICHER --> LINKEDIN
    ENRICHER --> GITHUB
    REPO --> PG
    FILE_STORE --> S3
    
    %% Styling
    classDef apiStyle fill:#6c8ebf,stroke:#5a7aa8,color:white
    classDef processingStyle fill:#82b366,stroke:#6d9b51,color:white
    classDef llmStyle fill:#d79b00,stroke:#b88200,color:white
    classDef dataStyle fill:#b85450,stroke:#9c4641,color:white
    classDef externalStyle fill:#f5f5f5,stroke:#666666
    
    class ROUTER,WORKER apiStyle
    class CV_PARSER,ENRICHER,SCORER,GENERATOR,AGENT processingStyle
    class LLM_CLIENT,PROMPT_MGR,CACHE llmStyle
    class REPO,VECTOR_STORE,FILE_STORE dataStyle
```

### 7.4 Descripción de Componentes del AI Service

#### API Layer

| Componente | Responsabilidad | Tecnología |
|------------|-----------------|------------|
| **API Router** | Endpoints REST para operaciones síncronas (scoring rápido, generación de contenido). Validación con Pydantic. | FastAPI |
| **Queue Worker** | Procesa jobs asíncronos de la cola (parsing de CVs, enriquecimiento, AI Agent). Maneja retries y dead-letter queue. | BullMQ + Python |

#### Processing Components

| Componente | Responsabilidad | Input → Output |
|------------|-----------------|----------------|
| **CV Parser** | Extrae datos estructurados de CVs en múltiples formatos. Usa OCR si es necesario. | PDF/DOCX → JSON estructurado |
| **Profile Enricher** | Obtiene datos adicionales de fuentes públicas (LinkedIn, GitHub). Unifica en perfil único. | Candidate ID → Enriched Profile |
| **Match Scorer** | Calcula score de compatibilidad candidato-job. Combina ML (embeddings) con reglas de negocio. | (Candidate, Job) → Score 0-100 |
| **Content Generator** | Genera contenido usando LLMs: JDs, emails de outreach, preguntas de entrevista. | Prompt + Context → Generated Text |
| **AI Agent** | Agente autónomo que ejecuta workflows de sourcing: busca → filtra → contacta → agenda. | Job Requirements → Sourced Candidates |

#### LLM Abstraction Layer

| Componente | Responsabilidad | Beneficio |
|------------|-----------------|-----------|
| **LLM Client** | Abstracción sobre múltiples providers (OpenAI, Anthropic, modelos locales). Fallback automático. | Evita vendor lock-in |
| **Prompt Manager** | Gestiona templates de prompts versionados. Permite A/B testing de prompts. | Iteración rápida |
| **Response Cache** | Cachea respuestas para prompts idénticos/similares. TTL configurable por tipo. | Reduce costes de API |

#### Data Layer

| Componente | Responsabilidad | Tecnología |
|------------|-----------------|------------|
| **Repository** | Acceso a base de datos principal. Implementa patrón repository con SQLAlchemy. | PostgreSQL |
| **Vector Store** | Almacena y busca embeddings de candidatos para búsqueda semántica y matching. | pgvector / Pinecone |
| **File Store** | Gestiona archivos (CVs originales, procesados, reportes). Interface sobre S3. | AWS S3 |

### 7.5 Flujos de Datos Principales

**Flujo 1: Parsing de CV (Asíncrono)**
```
1. Core API encola job "parse_cv" con file_id
2. Queue Worker recibe job
3. File Store descarga CV de S3
4. CV Parser extrae texto (PyPDF2/python-docx)
5. LLM Client envía a OpenAI para estructuración
6. Repository guarda datos parseados en PostgreSQL
7. Vector Store genera y almacena embedding del candidato
8. Worker marca job como completado
```

**Flujo 2: Generación de Job Description (Síncrono)**
```
1. Core API llama a POST /ai/generate-jd con título y contexto
2. API Router valida request
3. Content Generator construye prompt con Prompt Manager
4. Cache verifica si existe respuesta cacheada
5. LLM Client llama a OpenAI/Anthropic
6. Response se cachea y retorna al Core API
```

**Flujo 3: AI Agent Sourcing (Autónomo)**
```
1. Job programado trigger cada 6 horas para jobs activos
2. AI Agent recibe job requirements
3. Agent busca en LinkedIn via API (o scraping autorizado)
4. Match Scorer evalúa cada candidato encontrado
5. Content Generator crea outreach personalizado
6. Agent envía mensajes via LinkedIn/email
7. Repository registra candidatos sourceados
8. Notification Service alerta al recruiter de hot leads
```

---

## Anexo: Stack Tecnológico Recomendado

### Backend
- **Runtime**: Node.js 20 LTS
- **Framework**: NestJS 10 (TypeScript)
- **AI Service**: Python 3.11 + FastAPI
- **ORM**: Prisma (Node), SQLAlchemy (Python)

### Frontend
- **Framework**: Next.js 14 (App Router)
- **UI**: shadcn/ui + Tailwind CSS
- **State**: TanStack Query + Zustand
- **Real-time**: Socket.io client

### Data
- **Primary DB**: PostgreSQL 16 con pgvector
- **Cache**: Redis 7
- **Search**: OpenSearch
- **Storage**: AWS S3

### Infrastructure
- **Cloud**: AWS (alternativa: GCP)
- **Containers**: Docker + ECS Fargate
- **CI/CD**: GitHub Actions
- **Monitoring**: Datadog / Grafana

### AI/ML
- **LLM Primary**: OpenAI GPT-4o
- **LLM Fallback**: Anthropic Claude
- **Embeddings**: OpenAI text-embedding-3-large
- **CV Parsing**: Custom + LLM enhancement

---

*Documento generado para el ejercicio de diseño de sistemas - LTI ATS*
*Autor: Pablo (LTI-PBL)*
*Fecha: Noviembre 2025*
