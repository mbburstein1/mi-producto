# Veta

Veta convierte la voz del cliente que la empresa ya recoge —contact center, NPS, CSAT, Usabilla, reclamos SAC en Salesforce— en señales codificadas y con métricas (volumen, tendencia, impacto en el journey) que los product owners pueden priorizar frente a las solicitudes del negocio. Reemplaza el proceso manual y mensual con que hoy se arma la "voz del paciente" por uno continuo. Aprende solo de la información interna de la empresa sobre sus productos digitales. La visión es agnóstica a industria; el primer caso es salud.

## Para quién

**Comprador y usuario principal:** gerencias de producto/digital y sus product owners/managers en empresas con productos digitales propios y volumen relevante de atención a clientes finales. Primer segmento: prestadores de salud en Chile, con Clínica Alemana Santiago como caso de referencia (app, portal, agendamiento, resultados).

**Usuarios operativos:** equipos de experiencia del paciente, contact center y SAC, que hoy construyen a mano el proceso de "voz del paciente" (diccionario común de códigos → backlog de mejora).

**Contexto del problema:** el roadmap de producto se define por solicitudes del negocio. Las señales de pacientes sí llegan a los PO vía un proceso manual y mensual, pero sin métricas de volumen, tendencia ni impacto, por lo que la mejora de experiencia siempre pierde contra el desarrollo.

## Decisiones

- **2026-09-22 — Veta es el valor que agrega a producto.** El producto se define por convertir la voz del paciente en oportunidades de mejora priorizables ([voz-paciente-sin-metricas](opportunities/2026-09-22-1815-voz-paciente-sin-metricas.md)). El soporte agéntico N1/N2 que resolvía casos y escalaba a personas sale del producto, junto con sus creencias.

## Creencias no verificadas

- **[product] [value]** Si los códigos de voz del paciente llegaran con métricas (volumen, tendencia, impacto en el journey), los PO lograrían priorizarlos frente a las solicitudes del negocio. Hoy pierden por falta de evidencia, no por falta de mandato.
- **[product] [value]** La consolidación manual y mensual es el cuello de botella: automatizarla y hacerla continua cambiaría decisiones de priorización, no solo ahorraría horas.
- **[product] [feasibility]** Un modelo puede clasificar las interacciones de las fuentes existentes contra el diccionario común de voz del paciente con calidad suficiente para reemplazar la codificación manual.
- **[product] [feasibility]** Veta puede acceder de forma continua a las fuentes (Salesforce, contact center, NPS/CSAT, Usabilla) aunque pertenezcan a gerencias distintas de la de producto.
- **[business] [viability]** El comprador es la gerencia de producto/digital, y experiencia del paciente, contact center y SAC aceptarían que la codificación automática reemplace la que hoy hacen ellos.
- **[market] [viability]** El patrón "desarrollo le gana a experiencia por falta de métricas" no es exclusivo de salud: lo que funcione en Clínica Alemana se generaliza a otras industrias.
- **[opportunity: voz-paciente-sin-metricas] [value]** Los ítems de voz del paciente pierden en el comité de priorización por falta de cuantificación, no por falta de mandato ni de capacidad: en el último semestre, menos de 1 de cada 5 ítems de experiencia presentados a comité fue aprobado, los PO atribuyen el rechazo a no poder mostrar volumen o impacto, y armar un caso cuantificado les toma más de 3 días hábiles.
- **[opportunity: voz-paciente-sin-metricas] [viability]** La gerencia de producto/digital tiene la autoridad y el presupuesto para pagar por resolverlo: en al menos 3 de 5 prestadores de salud privados con equipo de producto, el gerente o subgerente pone este problema entre sus 3 prioridades del año y tiene una línea de presupuesto de herramientas donde cabría una solución.
