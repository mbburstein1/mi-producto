---
status: framed
segment: Product Owners y gerencias de producto digital de prestadores de salud privados en Chile con productos digitales propios (app, portal, agendamiento, resultados), junto con los equipos de experiencia del paciente que les entregan la voz del paciente
personas: camila-ortuzar, patricia-fuenzalida, rodrigo-valenzuela, veronica-sepulveda, andres-bittencourt
---

# Opportunity: La voz del paciente pierde la priorización por falta de métricas

Los PO de prestadores de salud reciben las señales de pacientes una vez al mes, consolidadas a mano y sin volumen, tendencia ni impacto. Por eso pierden sistemáticamente contra las solicitudes del negocio en el comité de priorización, y la mejora de experiencia no entra al roadmap.

## Segment and personas

- Camila Ortúzar (primary) — la sufre: lleva anécdotas al comité, pierde contra proyecciones de ingreso y no puede cerrar el ciclo de lo que sí salió.
- Patricia Fuenzalida (secondary) — la sufre: produce a mano el informe mensual que llega tarde, sin métricas y sin respuesta de vuelta.
- Rodrigo Valenzuela (primary) — la sufre en parte: elige entre defender a sus PO sin datos o dejar ganar al negocio. Es quien responde la creencia de viabilidad (compra y presupuesto).
- Verónica Sepúlveda (tertiary) — no la sufre directamente: sufre sus consecuencias, las llamadas evitables que producto no prioriza. Responde la viabilidad por el lado de los datos: habilita o bloquea el acceso a la fuente más grande y decide si acepta la codificación automática.
- Andrés Bittencourt (negative) — no la sufre: no tiene PO, roadmap ni proceso de voz del paciente. Delimita el segmento: sin equipo de producto no hay oportunidad.
- Missing: none. Falta, eso sí, la contraparte que gana hoy en el comité (gerencia comercial/negocio): no sufre el problema, pero condiciona qué evidencia basta para ganarle.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| El roadmap se define por solicitudes del negocio; las señales de pacientes llegan por un proceso manual y mensual, sin métricas de volumen, tendencia ni impacto | unverified | `product/overview.md` (brief del curso / caso Clínica Alemana) |
| Existe un diccionario común de códigos de voz del paciente construido a mano por soporte, contact center y SAC | unverified | `product/overview.md` |
| La voz del paciente viene de cinco fuentes con formatos distintos: contact center, NPS, CSAT, Usabilla, reclamos SAC en Salesforce | unverified | `product/overview.md` |
| Dos trimestres seguidos sin ítems de experiencia en el sprint; la PO tarda una semana en armar un argumento cuantificado | synthetic | `product/personas/camila-ortuzar.md` |
| La consolidación mensual toma 6–8 días-persona y el informe llega 4–6 semanas después del reclamo, sin circuito de vuelta | synthetic | `product/personas/patricia-fuenzalida.md` |
| El comprador ya compró herramientas de "insights" que terminaron como dashboards que nadie abre | synthetic | `product/personas/rodrigo-valenzuela.md` |
| No se sabe qué porcentaje de los contactos al contact center son problemas de productos digitales | synthetic | `product/personas/rodrigo-valenzuela.md` |
| Casi un tercio de las llamadas se tipifica como "consulta general"; los releases sin aviso generan peaks de llamadas que producto no ve | synthetic | `product/personas/veronica-sepulveda.md` |

Todas las señales son `unverified` o `synthetic`: hay razones para creer que el problema existe, pero ninguna prueba todavía.

## Business outcome

Para Veta (producto comercial): que gerencias de producto/digital de prestadores de salud paguen por resolver esto; el primer ingreso es Clínica Alemana como caso de referencia.

Para el comprador: que ítems de experiencia entren al roadmap con evidencia comparable a la del negocio, y que su KPI (costo de atención por canal digital sin caída de satisfacción) mejore al atacar las causas de los contactos.

## Constraints

- Datos de salud son datos sensibles: aplican la Ley 20.584 (derechos y deberes del paciente) y la Ley 19.628 de protección de datos, reemplazada por la Ley 21.719 (verificar fecha de entrada en vigencia).
- Los reclamos ante la Superintendencia de Salud tienen plazos legales de respuesta; la responsabilidad es de la jefatura de experiencia, no del proveedor. (synthetic, `patricia-fuenzalida.md`)
- Las fuentes (contact center, SAC, experiencia del paciente) reportan a gerencias distintas de la de producto. (synthetic, `rodrigo-valenzuela.md`)
- Toda iniciativa con IA pasa por revisión de legal y seguridad de la información, que puede tomar meses. (synthetic, `rodrigo-valenzuela.md`)
- Parte de la operación de contact center puede estar externalizada: grabaciones y registros quedan en la plataforma del proveedor y su acceso depende del contrato. (synthetic, `veronica-sepulveda.md`)

## Beliefs

Registradas en `product/overview.md`:

- [opportunity: voz-paciente-sin-metricas] [value] Los ítems de voz del paciente pierden en el comité de priorización por falta de cuantificación, no por falta de mandato ni de capacidad: en el último semestre, menos de 1 de cada 5 ítems de experiencia presentados a comité fue aprobado, los PO atribuyen el rechazo a no poder mostrar volumen o impacto, y armar un caso cuantificado les toma más de 3 días hábiles.
- [opportunity: voz-paciente-sin-metricas] [viability] La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| value | **Datos existentes** en Clínica Alemana: actas del comité de priorización de los últimos 2 trimestres (ítems de experiencia presentados vs. aprobados, motivo) y horas reales del proceso mensual de voz del paciente | Si la tasa de aprobación no es baja o el rechazo no se explica por falta de datos, la oportunidad cae o se reformula antes de gastar en entrevistas | Propuesto: 2026-10-02 |
| value | **Entrevistas** (`/design-interview`) a 4–6 PO y 2–3 jefaturas de experiencia del paciente, en Clínica Alemana y al menos otros 2 prestadores | Confirma si el cuello de botella es la evidencia (lo que Veta ataca) o la política del comité (lo que Veta no resuelve) | Propuesto: 2026-10-16 |
| viability | **Investigación secundaria** (`/research-market`): herramientas de voz del cliente y CX analytics usadas en salud en Chile y LatAm, quién las compra y a qué precio | Muestra si el problema ya se paga y quién lo paga (producto vs. experiencia vs. contact center) | Propuesto: 2026-10-09 |
| viability | **Entrevistas** a 3–5 gerentes/subgerentes de producto digital de prestadores de salud | Decide si el comprador es producto/digital (según el overview) o hay que ir por otra gerencia; condiciona el pricing | Propuesto: 2026-10-23 |

Fechas propuestas: ajustarlas al calendario del curso.

## Candidate ideas (not evaluated)

- Clasificación automática de cada interacción contra el diccionario común de voz del paciente (el núcleo de Veta).
- Métricas continuas por código: volumen, tendencia, etapa del journey.
- Un one-pager por ítem, listo para llevar al comité, con el formato de los casos del negocio.
- Circuito de vuelta: qué pasó con cada ítem del backlog y si el reclamo bajó después del release.
- Entregar las señales dentro de lo que ya usan (Jira, Power BI, Salesforce) en vez de una plataforma nueva.
