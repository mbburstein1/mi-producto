---
status: framed
segment: Product Owners y gerencias de producto digital de prestadores de salud privados en Chile con productos digitales propios (app, portal, agendamiento, resultados), junto con los equipos de UX y soporte de producto que hoy codifican a mano la voz del paciente
personas: rodrigo-valenzuela, camila-ortuzar, benjamin-araya, francisca-lagos, soledad-irarrazaval, andres-bittencourt
---

# Opportunity: La voz del paciente entra al backlog sin prioridad ni forma de competir

Los ítems de mejora que nacen de la voz del paciente entran al backlog de producto sin prioridad y sin un criterio que defina cómo compiten con las iniciativas nuevas —features y pedidos de stakeholders que impulsan las gerencias digital y de TI, dueñas del desarrollo de producto—, así que pierden por omisión. No hay comité ni instancia formal donde se comparen: hay una reunión bisemanal que sigue cómo se llenan los datos y una revisión a fin de mes de si cambia la priorización del mes anterior, hecha en Excel, que no se traduce en decisiones del backlog. Además llegan consolidados a mano, sin volumen ni tendencia y sin un argumento que muestre qué le cuesta al negocio el problema. Es el momento porque el proceso ya existe y está estandarizado (diccionario común, cinco fuentes identificadas, seguimiento bisemanal), pero sigue sin cambiar decisiones.

## Segment and personas

- Rodrigo Valenzuela (primary, la más relevante) — la sufre y decide: cada fin de mes recibe la voz del paciente consolidada y la compara contra las iniciativas nuevas que él comprometió, sin un número de costo; decide qué entra al sprint y qué no.
- Camila Ortúzar (primary) — la sufre: sus ítems de experiencia quedan en el backlog sin prioridad mientras las iniciativas nuevas llegan con proyección de ingreso.
- Benjamín Araya (primary) — la sufre sin herramientas para enfrentarla: PO novato que deja de llevar ítems a la revisión cuando no puede responder cuánto cuestan.
- Francisca Lagos (secondary) — sufre su consecuencia: codifica a mano, junto con soporte de producto, la voz del paciente (mensual en Usabilla/CSAT, bisemanal en NPS y reclamos) y los ítems que produce quedan sin prioridad.
- Soledad Irarrázaval (tertiary) — no usa el producto: aprueba la compra y la línea de presupuesto. Responde la creencia de viabilidad.
- Andrés Bittencourt (negative) — no la sufre: sin equipo de producto no hay backlog donde competir.

**Sin persona propia:** soporte de producto (co-codifica con UX), experiencia del paciente/SAC (dueña de NPS y reclamos), contact center (dueño del costo por contacto) y gerencia de TI (co-prioriza el roadmap con la gerencia digital). Francisca representa en parte a soporte; el acceso a los datos de contact center y SAC se valida con conversaciones reales.

## Signals

| Signal                                                                                                                                                                    | Provenance | Source                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------------------------------------------------- |
| No existe comité ni instancia formal de priorización para la voz del paciente                                                                                             | real       | Prestador de referencia — observación directa, 2026-09-23 |
| Hay una reunión bisemanal que sigue cómo se llenan los datos de voz del paciente, y a fin de mes se revisa si cambia la priorización definida el mes anterior en un Excel | real       | Prestador de referencia — observación directa, 2026-09-23 |
| Los ítems priorizados entran al backlog de producto sin prioridad y sin un criterio de cómo compiten con una iniciativa nueva                                             | real       | Prestador de referencia — observación directa, 2026-09-23 |
| La codificación es mensual en Usabilla/CSAT y bisemanal en NPS y reclamos                                                                                                 | real       | Prestador de referencia — observación directa, 2026-09-23 |
| Existe un diccionario común de códigos construido a mano por soporte, contact center y SAC                                                                                | real       | Prestador de referencia — diccionario (documento interno) |
| La voz del paciente viene de cinco fuentes con formatos distintos: contact center, NPS, CSAT, Usabilla, SAC en Salesforce                                                 | real       | Prestador de referencia — fuentes del informe mensual     |
| La consolidación toma 6–8 días-persona al mes y la de Usabilla/CSAT llega 4–6 semanas después del reclamo                                                                 | synthetic  | `product/personas/francisca-lagos.md`                     |
| La PO tarda una semana en armar un argumento cuantificado; dos trimestres sin ítems de experiencia en el sprint                                                           | synthetic  | `product/personas/camila-ortuzar.md`                      |
| El sponsor ya aprobó herramientas de "insights" que terminaron como dashboards que nadie abre                                                                             | synthetic  | `product/personas/soledad-irarrazaval.md`                 |
| Las compras de herramientas exigen un caso de ROI a 12 meses ante el comité de inversiones                                                                                | synthetic  | `product/personas/soledad-irarrazaval.md`                 |

## Business outcome

Comercial: que gerencias de producto/digital de prestadores de salud paguen por Veta. El prestador de referencia es el primer cliente o piloto. Para el comprador: que los ítems de experiencia entren al roadmap con prioridad y evidencia comparables a las de una iniciativa nueva.

## Constraints

- Datos de salud sensibles: Ley 20.584 (derechos y deberes del paciente) y Ley 19.628 de protección de datos, reemplazada por la Ley 21.719, que entra en vigencia el 2026-12-01 y crea la Agencia de Protección de Datos Personales (`product/research/2026-09-22-voz-paciente-sin-metricas-mercado.md`).
- Las fuentes reportan a gerencias distintas de producto, y acceder a sus datos exige negociarlo entre gerencias. (synthetic, `rodrigo-valenzuela.md`, `soledad-irarrazaval.md`)
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
| value | **1. Datos propios (gratis):** backlog de Jira de los productos del prestador de referencia, últimos 2–3 trimestres: tasa de ejecución de ítems de voz del paciente vs. iniciativas nuevas; tiempos de señal → priorizado → en sprint → released; lag de codificación por fuente; más los Excel de priorización mensual | Si la tasa de ejecución de voz del paciente no es menor que la mitad de la de iniciativas nuevas, la oportunidad se reformula o descarta antes de encuestar | 2026-10-06 |
| value | **2. Encuesta breve (cuantificar y reclutar)** a PO, PM y UX del prestador de referencia y de otros prestadores con equipo de producto: con qué frecuencia un ítem de voz del paciente compite con una iniciativa nueva, qué evidencia les piden, causa principal de que no se ejecute (opción múltiple: evidencia o criterio, capacidad, gobierno, otra) y "¿aceptas una entrevista de 30 minutos?" | Si la mayoría atribuye la no ejecución a capacidad o gobierno y no a evidencia o criterio, la creencia de valor cae. Da la lista de entrevistados, incluidos quienes contradicen la hipótesis | 2026-10-13 |
| market | **Investigación secundaria de competencia** (`/research-market`): si Qualtrics, Medallia u otros ya cruzan lo que el cliente dice, hace y vale en salud, y si lo conectan al backlog | Cómo se posiciona Veta frente al sponsor; si el cruce ya existe, la diferenciación pasa a ser la conexión con la decisión de backlog | 2026-10-16 |
| value | **3. Entrevistas** (`/design-interview`) a 5–7 PO/PM que reportan baja ejecución —incluidos algunos con menos de un año en el rol— y a 1–2 que sí logran ejecutar ítems de experiencia | Contrastar criterios, evidencia mínima y workarounds: si el cuello de botella es la evidencia o la falta de criterio, y si el problema se generaliza más allá del prestador de referencia | 2026-10-23 |
| viability | **4. Conversación con el sponsor** (subgerencia o gerencia digital/producto) del prestador de referencia y de 2–3 prestadores más: prioridad anual, umbral de ROI o evidencia que destraba una compra y línea de presupuesto (CAPEX/OPEX), mostrando una señal armada a mano con datos reales de la app del prestador ("no abre el PDF del examen": volumen, paso del journey, costo de los contactos). TI participa solo para ownership e integración | Si hay sponsor real: si el problema no está en su top 3 o no hay línea de presupuesto ni reubicación en 12 meses, no es viable como producto de venta. Condiciona el pricing | 2026-10-30 |

La encuesta va antes de las entrevistas aunque el universo sea chico: sirve para cuantificar y para reclutar, incluidos quienes contradicen la hipótesis. Las creencias de valor las responden los PO/PM y los datos; las de viabilidad, el sponsor, no los usuarios.

Research secundario hecho:

- [Mercado de voz del cliente en salud](../research/2026-09-22-voz-paciente-sin-metricas-mercado.md) (2026-09-22): quién compra, a qué precio y contra quién se compite.
- [Cómo se estima el impacto de negocio de una señal](../research/2026-09-23-impacto-negocio-senales.md) (2026-09-23): tres métodos en uso (ingreso por cuenta, brecha de conversión, costo de contactos evitables), el dato externo que necesita cada uno y que ningún proveedor publica su precisión.

## Candidate ideas (not evaluated)

- Clasificación automática contra el diccionario común.
- Métricas continuas por código: volumen, tendencia, etapa del journey.
- Estimación del impacto de negocio por señal (conversión perdida, costo de contactos evitables).
- Un criterio común para comparar un ítem de experiencia con una iniciativa nueva, con prioridad asignada al entrar al backlog.
- Un one-pager por ítem, listo para la revisión de fin de mes.
- Circuito de vuelta: qué pasó con cada ítem y si el reclamo bajó.
- Señales dentro de las herramientas que ya usan (Jira, Power BI, Salesforce).
