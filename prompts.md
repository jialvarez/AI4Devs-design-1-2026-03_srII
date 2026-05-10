# PROMPTS (Gemini Pro)

## PROMPT 1

Se necesita ser muy amplio y detallado y generar una documentación en formato .md para este proyecto.

## Bloque 1: Producto, Funcionalidades y Negocio
Actúa como un Senior Product Manager experto en SaaS. Tu objetivo es definir el MVP de "LTI", un Applicant Tracking System (ATS) disruptivo para startups.

Genera una respuesta en Markdown con:
1. **Visión del Producto**: Una descripción breve centrada en eficiencia y colaboración.
2. **Valor Añadido**: 5 ventajas competitivas (ej: IA semántica, automatización de feedback).
3. **Funcionalidades Core**: Define 7 funciones (Creación de ofertas, Publicación multicanal, Recepción/Parsing, Revisión con IA, Tests online, Agenda inteligente y Onboarding). Justifica cada una.
4. **Diagrama de Proceso**: Un `flowchart TD` en Mermaid que conecte estas 7 funciones.
5. **Lean Canvas**: Un diagrama de bloques en Mermaid (`block-beta`) que cubra todo el modelo de negocio (Problema, Solución, Métricas, Propuesta de Valor, Ventaja Injusta, Canales, Segmentos, Costos e Ingresos).

---

## Bloque 2: Casos de Uso Detallados
Basado en las funciones anteriores, actúa como un Analista de Sistemas y detalla los 3 casos de uso críticos:
1. Creación de Ofertas de Empleo.
2. Publicación Automática en Portales.
3. Recepción y Procesamiento de Solicitudes (Parsing).

Para cada caso, incluye:
- Descripción, Actores, Precondiciones, Flujo Principal y Postcondiciones.
- Una justificación técnica/negocio de por qué es vital.
- Un diagrama de secuencia en Mermaid (`sequenceDiagram`) que muestre la interacción entre el Reclutador/Candidato, el Sistema LTI y las APIs externas (LinkedIn, Servicio de IA).

---

## Bloque 3: Modelo de Datos y Arquitectura de Sistema
Ahora, actúa como un Arquitecto de Software para definir la estructura técnica.

1. **Modelo de Datos**: Crea un diagrama Entidad-Relación en Mermaid (`erDiagram`) que incluya CANDIDATE, JOB_POST, APPLICATION, RECRUITER, PUBLICATION_CHANNEL y JOB_PUBLICATION. Define atributos clave y tipos de datos.
2. **Decisión de Arquitectura**: Compara Monolito vs Microservicios vs Arquitectura Hexagonal. Justifica la elección de una **Arquitectura Hexagonal Modular** para este proyecto.
3. **Diagrama de Alto Nivel**: Un diagrama en Mermaid (`flowchart TB`) que visualice las capas de la arquitectura hexagonal: Dominio (Entidades/Reglas), Aplicación (Servicios/Casos de Uso), Adaptadores de Entrada (API/Web) y Adaptadores de Salida (DB, IA, Mail).

---

## Bloque 4: Inmersión Técnica (Diagramas C4)
Finalmente, genera la documentación técnica profunda siguiendo el estándar C4 Model.

1. **Nivel 1 (Contexto)**: Diagrama C4Context en Mermaid sobre cómo LTI interactúa con usuarios y sistemas externos.
2. **Nivel 2 (Contenedores)**: Diagrama C4Container que muestre la Web App, la API (Node.js/Python), la Base de Datos (PostgreSQL) y sistemas de colas (RabbitMQ/Redis).
3. **Nivel 3 (Componentes)**: Diagrama C4Component que desglose el interior de la API.
4. **Nivel 4 (Código)**: Un diagrama de clases en Mermaid (`classDiagram`) que detalle los componentes, sus métodos, DTOs y cómo se relacionan con el repositorio y el motor de IA.

## PROMPT 2 

Más allá de las clases core, me puedes dar el nivel 4 del resto de entidades?

## PROMPT 3

CAMBIO A DEEPSEEK, GEMINI EN BUCLE DANDO RESPUESTAS DE MALA CALIDAD.

¿Cómo mejorarías esta especificación?