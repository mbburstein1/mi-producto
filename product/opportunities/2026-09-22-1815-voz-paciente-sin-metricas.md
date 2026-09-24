---
status: framed
segment: Product Owners y gerencias de producto digital de prestadores de salud privados en Chile con productos digitales propios (app, portal, agendamiento, resultados), junto con los equipos de UX y soporte de producto que hoy codifican a mano la voz del paciente
personas: camila-ortuzar, rodrigo-valenzuela, francisca-lagos, veronica-sepulveda, andres-bittencourt
---

# Opportunity: La voz del paciente entra al backlog sin prioridad ni forma de competir

Los ítems de mejora que nacen de la voz del paciente entran al backlog de producto sin prioridad y sin un criterio que defina cómo compiten con las iniciativas nuevas —features y pedidos de stakeholders que impulsan las gerencias digital y de TI, dueñas del desarrollo de producto—, así que pierden por omisión. No hay comité ni instancia formal donde se comparen: hay una reunión bisemanal que sigue cómo se llenan los datos y una revisión a fin de mes de si cambia la priorización del mes anterior, hecha en Excel, que no se traduce en decisiones del backlog. Además llegan consolidados a mano, sin volumen ni tendencia y sin un argumento que muestre qué le cuesta al negocio el problema. Es el momento porque el proceso ya existe y está estandarizado (diccionario común, cinco fuentes identificadas, seguimiento bisemanal), pero sigue sin cambiar decisiones.

## Segment and personas

- Camila Ortúzar (primary) — la sufre: sus ítems de experiencia quedan en el backlog sin prioridad mientras las iniciativas nuevas llegan con proyección de ingreso.
- Rodrigo Valenzuela (primary) — la sufre: no tiene una regla ni datos para justificar un sprint de experiencia frente a una iniciativa nueva que él comprometió. Responde la creencia de viabilidad.
- Francisca Lagos (secondary) — sufre su consecuencia: codifica a mano, junto con soporte de producto, la voz del paciente (mensual en Usabilla/CSAT, bisemanal en NPS y reclamos) y los ítems que produce quedan sin prioridad.
- Verónica Sepúlveda (tertiary) — no usa el producto: sufre las llamadas evitables y habilita o bloquea el acceso a la fuente más grande.
- Andrés Bittencourt (negative) — no la sufre: sin equipo de producto no hay backlog donde competir.
- Missing: soporte de producto (co-codifica con UX) y experiencia del paciente/SAC (dueña de NPS y reclamos) no tienen persona propia, para mantener el set en 2-1-1-1; Francisca y Verónica las representan en parte. La contraparte en la priorización son las gerencias digital y de TI, que priorizan features nuevos; no tienen persona propia y su postura la representa en parte Rodrigo, que es parte de la gerencia digital.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| No existe comité ni instancia formal de priorización para la voz del paciente | real | Clínica Alemana — corrección de Marcelo, 2026-09-23 |
| Hay una reunión bisemanal que sigue cómo se llenan los datos de voz del paciente, y a fin de mes se revisa si cambia la priorización definida el mes anterior en un Excel | real | Clínica Alemana — corrección de Marcelo, 2026-09-23 |
| Los ítems priorizados entran al backlog de producto sin prioridad y sin un criterio de cómo compiten con una iniciativa nueva | real | Clínica Alemana — corrección de Marcelo, 2026-09-23 |
| La codificación es mensual en Usabilla/CSAT y bisemanal en NPS y reclamos | real | Clínica Alemana — corrección de Marcelo, 2026-09-23 |
| Existe un diccionario común de códigos construido a mano por soporte, contact center y SAC | real | Clínica Alemana — diccionario (documento interno) |
| La voz del paciente viene de cinco fuentes con formatos distintos: contact center, NPS, CSAT, Usabilla, SAC en Salesforce | real | Clínica Alemana — fuentes del informe mensual |
| La consolidación toma 6–8 días-persona al mes y la de Usabilla/CSAT llega 4–6 semanas después del reclamo | synthetic | `product/personas/francisca-lagos.md` |
| La PO tarda una semana en armar un argumento cuantificado; dos trimestres sin ítems de experiencia en el sprint | synthetic | `product/personas/camila-ortuzar.md` |
| El comprador ya compró herramientas de "insights" que terminaron como dashboards que nadie abre | synthetic | `product/personas/rodrigo-valenzuela.md` |
| Casi un tercio de las llamadas se tipifica como "consulta general" | synthetic | `product/personas/veronica-sepulveda.md` |

## Business outcome

Comercial: que gerencias de producto/digital de prestadores de salud paguen por Veta. Clínica Alemana es el primer cliente o piloto. Para el comprador: que los ítems de experiencia entren al roadmap con prioridad y evidencia comparables a las de una iniciativa nueva.

## Constraints

- Datos de salud sensibles: Ley 20.584 (derechos y deberes del paciente) y Ley 19.628 de protección de datos, reemplazada por la Ley 21.719, que entra en vigencia el 2026-12-01 y crea la Agencia de Protección de Datos Personales (`product/research/2026-09-22-voz-paciente-sin-metricas-mercado.md`).
- Las fuentes reportan a gerencias distintas de producto; parte del contact center puede estar externalizado, con los datos en la plataforma del proveedor. (synthetic, `rodrigo-valenzuela.md`, `veronica-sepulveda.md`)
- Toda iniciativa con IA pasa por revisión de legal y seguridad de la información. (synthetic, `rodrigo-valenzuela.md`)
- La decisión sobre esta oportunidad se toma el 2026-10-30 (hito del curso).

## Beliefs

Registradas en `product/overview.md`:

- [opportunity: voz-paciente-sin-metricas] [value] En el último semestre, la proporción de ítems de voz del paciente que entraron al backlog y se ejecutaron es menos de la mitad que la de las iniciativas nuevas, y quienes priorizan atribuyen la diferencia a que no hay criterio ni evidencia para comparar un ítem de experiencia con una iniciativa nueva, no a falta de capacidad del equipo.
- [opportunity: voz-paciente-sin-metricas] [viability] La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.
- Relacionadas, a nivel producto: [product] [value] impacto de negocio → priorización; [product] [feasibility] estimar impacto de negocio con datos fuera de la voz del cliente; [product] [value] consolidación como cuello de botella; [business] [viability] el comprador es producto.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| value | **Datos existentes:** backlog de Jira de los productos de Clínica Alemana, último semestre: cuántos ítems de voz del paciente entraron, cuántos se ejecutaron y cuánto llevan esperando, contra las iniciativas nuevas; más los Excel de priorización mensual | Si la proporción ejecutada no es menor que la mitad, la oportunidad se reformula o descarta antes de entrevistar | 2026-10-09 |
| viability | **Investigación secundaria** (`/research-market`): quién compra herramientas de voz del cliente en salud en Chile y LatAm, y a qué precio | Si el presupuesto suele estar en experiencia y no en producto, cambia el comprador | 2026-10-16 |
| value | **Entrevistas** (`/design-interview`) a 4–6 PO y 2–3 jefaturas de experiencia en al menos otros 2 prestadores | Si el problema se generaliza más allá de Clínica Alemana; si en otros prestadores existe una instancia o criterio formal para priorizar la voz del paciente; y si el cuello de botella es la evidencia o la falta de ese criterio | 2026-10-23 |
| viability | **Entrevistas** a 3–5 gerentes/subgerentes de producto digital | Si producto tiene prioridad y presupuesto; condiciona el pricing | 2026-10-30 |

Sin encuesta: el universo de prestadores con equipo de producto en Chile es chico, así que las entrevistas rinden más.

## Candidate ideas (not evaluated)

- Clasificación automática contra el diccionario común.
- Métricas continuas por código: volumen, tendencia, etapa del journey.
- Estimación del impacto de negocio por señal (conversión perdida, costo de contactos evitables).
- Un criterio común para comparar un ítem de experiencia con una iniciativa nueva, con prioridad asignada al entrar al backlog.
- Un one-pager por ítem, listo para la revisión de fin de mes.
- Circuito de vuelta: qué pasó con cada ítem y si el reclamo bajó.
- Señales dentro de las herramientas que ya usan (Jira, Power BI, Salesforce).
