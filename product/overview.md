# Veta

Veta convierte la voz del cliente que una empresa ya recoge —contact center, encuestas NPS/CSAT, feedback en la app o la web, reclamos en el CRM— en señales codificadas y con métricas (volumen, tendencia, impacto en el journey) que los product owners pueden priorizar frente a las solicitudes del negocio. Reemplaza el proceso manual y periódico con que hoy se arma la "voz del cliente" por uno continuo. Aprende solo de la información interna de la empresa sobre sus productos digitales. Es agnóstico a industria; el primer segmento es salud.

## Para quién

**Comprador y usuario principal:** gerencias de producto/digital y sus product owners/managers en empresas de cualquier industria con productos digitales propios y volumen relevante de atención a clientes finales.

**Usuarios operativos:** equipos de experiencia del cliente, soporte, contact center y atención de reclamos, que hoy construyen a mano el proceso de voz del cliente (diccionario común de códigos → backlog de mejora).

**Primer segmento:** prestadores de salud privados en Chile, con Clínica Alemana Santiago como caso de referencia (app, portal, agendamiento, resultados). Ahí la voz del cliente es la "voz del paciente" y sus fuentes son contact center, NPS, CSAT, Usabilla y reclamos SAC en Salesforce.

**Contexto del problema:** el roadmap de producto se define por solicitudes del negocio. Las señales de clientes sí llegan a los PO, pero por un proceso manual y periódico, sin métricas de volumen, tendencia ni impacto, así que la mejora de experiencia siempre pierde contra el desarrollo.

## Decisiones

- **2026-09-22 — Veta es el valor que agrega a producto.** El producto se define por convertir la voz del cliente en oportunidades de mejora priorizables. El soporte agéntico N1/N2 que resolvía casos y escalaba a personas sale del producto, junto con sus creencias.
- **2026-09-22 — Producto agnóstico, entrada por salud.** El producto se describe sin industria; salud es el primer segmento porque ahí hay acceso a datos reales (Clínica Alemana). La primera oportunidad es [voz-paciente-sin-metricas](opportunities/2026-09-22-1815-voz-paciente-sin-metricas.md).
- **2026-09-22 — La investigación de otras industrias se posterga.** La investigación secundaria de la creencia [market] [viability] (qué industrias en Chile tienen equipos de producto y volumen de atención, quién les vende voz del cliente, si ya compran herramientas como Enterpret) se hace después del 2026-10-30, y solo si la oportunidad de salud se sostiene. Motivo: no tiene sentido dimensionar la expansión antes de validar el primer segmento, aunque el universo de salud en Chile (~8–10 redes) es chico para sostener el negocio solo ([research](research/2026-09-22-voz-paciente-sin-metricas-mercado.md)).

## Creencias no verificadas

- **[opportunity: voz-paciente-sin-metricas] [value]** En el último semestre, la tasa de aprobación en el comité de priorización de los ítems originados en voz del paciente es menos de la mitad que la de las solicitudes del negocio, y en las actas o en las entrevistas el rechazo se atribuye a falta de cuantificación (volumen, tendencia, impacto), no a falta de mandato ni de capacidad.
- **[product] [value]** Si los códigos de voz del cliente llegaran con métricas (volumen, tendencia, impacto en el journey), los PO lograrían priorizarlos frente a las solicitudes del negocio.
- **[product] [value]** La consolidación manual y periódica es el cuello de botella: automatizarla y hacerla continua cambiaría decisiones de priorización, no solo ahorraría horas.
- **[product] [feasibility]** Un modelo puede clasificar las interacciones de las fuentes existentes contra el diccionario común de voz del cliente con calidad suficiente para reemplazar la codificación manual.
- **[product] [feasibility]** Veta puede acceder de forma continua a las fuentes (CRM, contact center, encuestas, feedback digital) aunque pertenezcan a gerencias distintas de la de producto.
- **[business] [viability]** El comprador es la gerencia de producto/digital, y experiencia del cliente, contact center y atención de reclamos aceptarían que la codificación automática reemplace la que hoy hacen ellos.
- **[market] [viability]** El patrón "desarrollo le gana a experiencia por falta de métricas" no es exclusivo de salud: lo que funcione en el primer segmento se generaliza a otras industrias.
- **[opportunity: voz-paciente-sin-metricas] [viability]** La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.
