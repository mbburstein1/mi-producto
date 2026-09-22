---
status: framed
segment: Product Owners y gerencias de producto digital de prestadores de salud privados en Chile con productos digitales propios (app, portal, agendamiento, resultados), junto con los equipos de experiencia del paciente que les entregan la voz del paciente
personas: camila-ortuzar, rodrigo-valenzuela, patricia-fuenzalida, veronica-sepulveda, andres-bittencourt
---

# Opportunity: La voz del paciente pierde la priorización por falta de métricas

Los ítems de mejora que nacen de la voz del paciente pierden en el comité de priorización frente a las solicitudes del negocio, porque llegan una vez al mes, consolidados a mano y sin volumen, tendencia ni impacto. Es el momento porque el proceso ya existe y está estandarizado (diccionario común, cinco fuentes identificadas), pero sigue sin cambiar decisiones.

## Segment and personas

- Camila Ortúzar (primary) — la sufre: lleva anécdotas al comité y pierde contra proyecciones de ingreso.
- Rodrigo Valenzuela (primary) — la sufre: elige entre defender a sus PO sin datos o dejar ganar al negocio. Responde la creencia de viabilidad.
- Patricia Fuenzalida (secondary) — sufre su consecuencia: produce el backlog de mejora y no se usa.
- Verónica Sepúlveda (tertiary) — no la sufre: habilita o bloquea el acceso a la fuente más grande.
- Andrés Bittencourt (negative) — no la sufre: sin equipo de producto no hay comité que perder.
- Missing: none. Fuera del set queda la gerencia comercial, que hoy gana en el comité y condiciona qué evidencia basta.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| Hay ítems de experiencia que se presentaron al comité de priorización y perdieron contra solicitudes del negocio | real | Clínica Alemana — actas del comité (documento interno) |
| Existe un informe mensual de voz del paciente armado a mano, sin volumen, tendencia ni impacto | real | Clínica Alemana — informe mensual (documento interno) |
| Existe un diccionario común de códigos construido a mano por soporte, contact center y SAC | real | Clínica Alemana — diccionario (documento interno) |
| La voz del paciente viene de cinco fuentes con formatos distintos: contact center, NPS, CSAT, Usabilla, SAC en Salesforce | real | Clínica Alemana — fuentes del informe mensual |
| La consolidación toma 6–8 días-persona al mes y llega 4–6 semanas después del reclamo | synthetic | `product/personas/patricia-fuenzalida.md` |
| La PO tarda una semana en armar un argumento cuantificado; dos trimestres sin ítems de experiencia en el sprint | synthetic | `product/personas/camila-ortuzar.md` |
| El comprador ya compró herramientas de "insights" que terminaron como dashboards que nadie abre | synthetic | `product/personas/rodrigo-valenzuela.md` |
| Casi un tercio de las llamadas se tipifica como "consulta general" | synthetic | `product/personas/veronica-sepulveda.md` |

## Business outcome

Comercial: que gerencias de producto/digital de prestadores de salud paguen por Veta. Clínica Alemana es el primer cliente o piloto. Para el comprador: que los ítems de experiencia entren al roadmap con evidencia comparable a la del negocio.

## Constraints

- Datos de salud sensibles: Ley 20.584 (derechos y deberes del paciente) y Ley 19.628 de protección de datos, reemplazada por la Ley 21.719 (verificar fecha de vigencia).
- Plazos legales de respuesta a reclamos ante la Superintendencia de Salud. (synthetic, `patricia-fuenzalida.md`)
- Las fuentes reportan a gerencias distintas de producto; parte del contact center puede estar externalizado, con los datos en la plataforma del proveedor. (synthetic, `rodrigo-valenzuela.md`, `veronica-sepulveda.md`)
- Toda iniciativa con IA pasa por revisión de legal y seguridad de la información. (synthetic, `rodrigo-valenzuela.md`)
- La decisión sobre esta oportunidad se toma el 2026-10-30 (hito del curso).

## Beliefs

Registradas en `product/overview.md`:

- [opportunity: voz-paciente-sin-metricas] [value] En el último semestre, la tasa de aprobación en el comité de priorización de los ítems originados en voz del paciente es menos de la mitad que la de las solicitudes del negocio, y en las actas o en las entrevistas el rechazo se atribuye a falta de cuantificación (volumen, tendencia, impacto), no a falta de mandato ni de capacidad.
- [opportunity: voz-paciente-sin-metricas] [viability] La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.
- Relacionadas, a nivel producto: [product] [value] métricas → priorización; [product] [value] consolidación como cuello de botella; [business] [viability] el comprador es producto.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| value | **Datos existentes:** actas del comité de Clínica Alemana del último semestre (tasa de aprobación experiencia vs. negocio y motivo del rechazo) | Si la tasa no es menor que la mitad o el motivo no es la cuantificación, la oportunidad se reformula o descarta antes de entrevistar | 2026-10-09 |
| viability | **Investigación secundaria** (`/research-market`): quién compra herramientas de voz del cliente en salud en Chile y LatAm, y a qué precio | Si el presupuesto suele estar en experiencia y no en producto, cambia el comprador | 2026-10-16 |
| value | **Entrevistas** (`/design-interview`) a 4–6 PO y 2–3 jefaturas de experiencia en al menos otros 2 prestadores | Si el problema se generaliza más allá de Clínica Alemana, y si el cuello de botella es la evidencia o la política del comité | 2026-10-23 |
| viability | **Entrevistas** a 3–5 gerentes/subgerentes de producto digital | Si producto tiene prioridad y presupuesto; condiciona el pricing | 2026-10-30 |

Sin encuesta: el universo de prestadores con equipo de producto en Chile es chico, así que las entrevistas rinden más.

## Candidate ideas (not evaluated)

- Clasificación automática contra el diccionario común.
- Métricas continuas por código: volumen, tendencia, etapa del journey.
- Un one-pager por ítem, listo para el comité.
- Circuito de vuelta: qué pasó con cada ítem y si el reclamo bajó.
- Señales dentro de las herramientas que ya usan (Jira, Power BI, Salesforce).
