# Veta

Veta convierte la voz del cliente que una empresa ya recoge —contact center, encuestas NPS/CSAT, feedback en la app o la web, reclamos en el CRM— en señales codificadas y con métricas (volumen, tendencia, impacto en el journey) expresadas en impacto de negocio —agendamientos abandonados, costo de contactos evitables, pacientes que se van, riesgo regulatorio—, para que los product owners puedan priorizarlas frente a los features nuevos y los pedidos de stakeholders. Reemplaza el proceso manual y periódico con que hoy se arma la "voz del cliente" por uno continuo. Aprende solo de la información interna de la empresa sobre sus productos digitales. Es agnóstico a industria; el primer segmento es salud.

## Para quién

**Comprador y usuario principal:** gerencias de producto/digital y sus product owners/managers en empresas de cualquier industria con productos digitales propios y volumen relevante de atención a clientes finales.

**Usuarios operativos:** los equipos de UX y de soporte de producto, que hoy codifican a mano la voz del cliente contra el diccionario común y arman el backlog de mejora.

**Fuentes y beneficiarios:** experiencia del cliente, contact center y atención de reclamos. No usan Veta: son dueños de las fuentes y les interesa el resultado, que la experiencia mejore y los contactos bajen por las mejoras que se implementan.

**Primer segmento:** prestadores de salud privados en Chile, con Clínica Alemana Santiago como caso de referencia (app, portal, agendamiento, resultados). Ahí la voz del cliente es la "voz del paciente" y sus fuentes son contact center, NPS, CSAT, Usabilla y reclamos SAC en Salesforce.

**Contexto del problema:** el roadmap de producto se define por solicitudes del negocio: features nuevos y pedidos de stakeholders que impulsan la gerencia digital y la gerencia de TI, dueñas del desarrollo de producto. Las señales de clientes sí llegan a los PO, pero por un proceso manual y periódico, entran al backlog sin prioridad y no hay un criterio de cómo compiten con una iniciativa nueva; llegan sin métricas de volumen ni tendencia y, sobre todo, sin un argumento que muestre qué le cuesta al negocio. Por eso la mejora de experiencia siempre pierde contra el desarrollo de features nuevos.

## Decisiones

- **2026-09-22 — Veta es el valor que agrega a producto.** El producto se define por convertir la voz del cliente en oportunidades de mejora priorizables. El soporte agéntico N1/N2 que resolvía casos y escalaba a personas sale del producto, junto con sus creencias.
- **2026-09-22 — Producto agnóstico, entrada por salud.** El producto se describe sin industria; salud es el primer segmento porque ahí hay acceso a datos reales (Clínica Alemana). La primera oportunidad es [voz-paciente-sin-metricas](opportunities/2026-09-22-1815-voz-paciente-sin-metricas.md).
- **2026-09-22 — La investigación de otras industrias se posterga.** La investigación secundaria de la creencia [market] [viability] (qué industrias en Chile tienen equipos de producto y volumen de atención, quién les vende voz del cliente, si ya compran herramientas como Enterpret) se hace después del 2026-10-30, y solo si la oportunidad de salud se sostiene. Motivo: no tiene sentido dimensionar la expansión antes de validar el primer segmento, aunque el universo de salud en Chile (~8–10 redes) es chico para sostener el negocio solo ([research](research/2026-09-22-voz-paciente-sin-metricas-mercado.md)).
- **2026-09-22 — Quién usa Veta y quién solo aporta datos.** La codificación manual la hacen UX y soporte de producto, no experiencia del cliente ni contact center. Ellos son los usuarios operativos; experiencia, contact center y reclamos son fuentes y beneficiarios que no usan el producto y solo esperan menos contactos y mejor experiencia.
- **2026-09-22 — El problema es la falta de argumento de negocio.** Las señales no pierden solo por falta de volumen o tendencia, sino porque no muestran qué le cuesta al negocio el problema. "El negocio" son la gerencia digital y la gerencia de TI, dueñas del desarrollo de producto, que priorizan features nuevos y pedidos de stakeholders. Las señales de Veta tienen que hablar en ese idioma.

- **2026-09-23 — No hay comité: el problema es que la voz del paciente no tiene cómo competir.** En Clínica Alemana no existe comité de priorización ni informe mensual. Hay una reunión bisemanal que sigue los datos y una revisión a fin de mes, en Excel, de si cambia la priorización del mes anterior; los ítems entran al backlog sin prioridad ni criterio frente a las iniciativas nuevas. La codificación es mensual en Usabilla/CSAT y bisemanal en NPS y reclamos. La oportunidad se reformula, la creencia de valor se mide con el backlog de Jira en vez de actas, y las personas se corrigen puntualmente, sin rehacerlas.

## Creencias no verificadas

- **[opportunity: voz-paciente-sin-metricas] [value]** En el último semestre, la proporción de ítems de voz del paciente que entraron al backlog y se ejecutaron es menos de la mitad que la de las iniciativas nuevas, y quienes priorizan atribuyen la diferencia a que no hay criterio ni evidencia para comparar un ítem de experiencia con una iniciativa nueva, no a falta de capacidad del equipo.
- **[product] [value]** Si una señal de voz del cliente llega expresada en impacto de negocio (ingresos perdidos, costo de atención, pacientes que se van), los PO logran priorizarla frente a los features nuevos y los pedidos de stakeholders que impulsan las gerencias digital y de TI.
- **[product] [value]** La consolidación manual y periódica es el cuello de botella: automatizarla y hacerla continua cambiaría decisiones de priorización, no solo ahorraría horas.
- **[product] [feasibility]** Un modelo puede clasificar las interacciones de las fuentes existentes contra el diccionario común de voz del cliente con calidad suficiente para reemplazar la codificación manual.
- **[product] [feasibility]** Veta puede acceder de forma continua a las fuentes (CRM, contact center, encuestas, feedback digital) aunque pertenezcan a gerencias distintas de la de producto.
- **[product] [feasibility]** Veta puede estimar el impacto de negocio de una señal cruzándola con datos que viven fuera de las fuentes de voz del cliente (funnels de conversión, costo por contacto, ingreso por atención), con una precisión que las gerencias digital y de TI acepten al priorizar.
- **[business] [viability]** El comprador es la gerencia de producto/digital, y UX y soporte de producto aceptan que la codificación automática reemplace la manual si pueden revisarla y corregirla.
- **[business] [feasibility]** Contact center, experiencia del cliente y atención de reclamos dan acceso continuo a sus datos si Veta les muestra qué mejoras bajaron sus contactos y reclamos.
- **[market] [viability]** El patrón "desarrollo le gana a experiencia por falta de métricas" no es exclusivo de salud: lo que funcione en el primer segmento se generaliza a otras industrias.
- **[opportunity: voz-paciente-sin-metricas] [viability]** La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.
