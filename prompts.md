# Prompts Utilizados para el Diseño de LTI

Este documento contiene los prompts utilizados durante el proceso de diseño del sistema LTI (Applicant Tracking System).

---

## Prompt 1: Investigación Inicial del Mercado

```
Investigación exhaustiva para diseñar un ATS (Applicant Tracking System) innovador 
llamado "LTI" orientado a startups. Necesito información detallada sobre:

1. **Análisis del mercado de ATS actual (2024-2025)**:
   - Principales competidores orientados a startups y PYMEs (Lever, Greenhouse, 
     Workable, Recruitee, Breezy HR, JazzHR, etc.)
   - Funcionalidades estándar vs diferenciadoras
   - Modelos de pricing típicos
   - Puntos de dolor comunes en usuarios de ATS

2. **Tendencias de IA en reclutamiento**:
   - Uso de IA generativa en ATS (screening automático, generación de descripciones 
     de puesto, chatbots)
   - Parsing de CVs con NLP
   - Matching candidato-puesto con ML
   - Detección de sesgos y fairness en reclutamiento
   - Automatizaciones inteligentes

3. **Mejores prácticas de colaboración en reclutamiento**:
   - Herramientas de colaboración en tiempo real entre recruiters y hiring managers
   - Integraciones más demandadas (Slack, calendarios, LinkedIn, job boards)
   - Flujos de trabajo y pipelines de contratación efectivos

4. **Arquitectura técnica de sistemas ATS modernos**:
   - Componentes principales de un ATS
   - Integraciones API típicas
   - Consideraciones de escalabilidad para startups
   - Modelo de datos común en ATS

5. **Propuesta de valor diferenciadora para startups**:
   - Qué valoran las startups en un ATS (facilidad de uso, precio, rapidez de 
     implementación)
   - Funcionalidades que faltan en el mercado actual
   - Oportunidades de innovación con IA

El objetivo es diseñar un ATS del futuro que destaque por: eficiencia para HR, 
colaboración en tiempo real, automatizaciones avanzadas y asistencia de IA.
```

**Propósito**: Obtener una visión completa del mercado, competidores, tendencias tecnológicas y oportunidades de diferenciación antes de comenzar el diseño del sistema.

---

## Prompt 2: Definición del Alcance del Proyecto

```
En este ejercicio tu misión será diseñar y documentar un sistema de software 
siguiendo las fases de investigación y análisis, casos de uso, modelado de datos, 
y diseño de alto nivel.

¿Y qué sistema? El de LTI.

LTI es una startup que quiere desarrollar el ATS (Applicant-Tracking System) 
del futuro.

Todavía no hay nada creado, así que toca ponerse el gorro de product manager 
y definir esas funcionalidades clave que harán brillar a LTI por encima de los 
competidores: aumentar la eficiencia para los departamentos de HR, mejorar la 
colaboración en tiempo real entre reclutadores y managers, automatizaciones, 
asistencia de IA en diversas tareas...

Tu misión es diseñar la primera versión del sistema, entregando los siguientes 
artefactos:
* Descripción breve del software LTI, valor añadido y ventajas competitivas. 
  Explicación de las funciones principales. Añadir un diagrama Lean Canvas para 
  entender el modelo de negocio
* Descripción de los 3 casos de uso principales, con el diagrama asociado a cada uno
* Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones
* Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto
* Diagrama C4 que llegue en profundidad a uno de los componentes del sistema, 
  el que prefieras

Genera un zip descargable con todo lo propuesto.
```

**Propósito**: Definir claramente los entregables esperados y el alcance del ejercicio de diseño.

---

## Prompt 3: Clarificación de Requisitos

```
1. ¿Cuál es el segmento objetivo de LTI? ¿Startups/PYMEs, empresas medianas, 
   o grandes corporaciones?
2. ¿Hay algún diferenciador específico que te interese explorar?
3. Para los diagramas técnicos (C4, modelo de datos), ¿prefieres usar PlantUML, 
   Mermaid, o te da igual el formato?
```

**Respuestas recibidas**:
1. Para startups
2. No, el que prefieras
3. El que prefieras

**Propósito**: Clarificar decisiones de diseño antes de comenzar la documentación para asegurar que el resultado se ajusta a las expectativas.

---

## Prompt 4: Generación de Documentación Completa

```
necesito que me entregues en un zip descargable:
diseñar la primera versión del sistema, entregando los siguientes artefactos:
* Descripción breve del software LTI, valor añadido y ventajas competitivas. 
  Explicación de las funciones principales. Añadir un diagrama Lean Canvas para 
  entender el modelo de negocio
* Descripción de los 3 casos de uso principales, con el diagrama asociado a cada uno
* Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones
* Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto
* Diagrama C4 que llegue en profundidad a uno de los componentes del sistema, 
  el que prefieras
```

**Propósito**: Solicitud final para generar todos los artefactos de documentación en formato descargable.

---

## Notas sobre el Proceso

### Decisiones de Diseño Tomadas

1. **Formato de diagramas**: Se eligió Mermaid por su compatibilidad nativa con Markdown y renderizado en GitHub.

2. **Componente para C4 profundo**: Se seleccionó el AI Service por ser el componente más diferenciador y complejo del sistema.

3. **Arquitectura**: Se optó por microservicios moderados en lugar de monolito puro, balanceando simplicidad inicial con escalabilidad futura.

4. **Stack tecnológico**: NestJS + Next.js + PostgreSQL como base sólida y moderna para startups.

### Fuentes de Investigación Utilizadas

- Aptitude Research: Análisis del mercado de ATS
- Market Growth Reports: Proyecciones de mercado
- G2/Capterra: Reviews de competidores
- SmartRecruiters, Eightfold AI: Tendencias de IA en reclutamiento
- Deloitte: Tendencias de Talent Acquisition

---

*Documento de prompts para el ejercicio LTI-PBL*
*Noviembre 2025*
