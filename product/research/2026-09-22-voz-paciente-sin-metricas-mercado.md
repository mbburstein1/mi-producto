---
source: secondary
method: mixed
date: 2026-09-22
question: ¿Quién compra herramientas de voz del cliente/paciente, en particular en salud en Chile y LatAm, a qué precio, y qué hace hoy el segmento en su lugar?
opportunity: voz-paciente-sin-metricas
---

# Research: mercado de voz del cliente para priorizar producto en salud (Chile)

La promesa de Veta ("feedback cuantificado para priorizar el roadmap") **ya existe y se vende**, pero afuera y a equipos de producto SaaS: Enterpret y Unwrap prometen justamente conectar el feedback con impacto para decidir qué construir, a US$24k–64k al año. En Chile, los actores visibles de voz del cliente en salud **le venden a CX y operaciones, no a producto**, lo que tensiona la creencia de que paga la gerencia de producto. Y la clasificación con IA se está volviendo commodity: el mercado se está repreciando hacia quien integra el insight en el flujo de decisión, así que el valor defendible de Veta estaría en el punto de decisión de la priorización, no en codificar.

> **Corrección 2026-09-23:** en Clínica Alemana no hay comité de priorización. Los ítems de voz del paciente entran al backlog sin prioridad ni criterio frente a las iniciativas nuevas. Donde este documento dice "comité", léase "el punto de decisión de la priorización", que hoy no existe formalmente. Los hallazgos de mercado no cambian.

Todas las fuentes se consultaron el 2026-09-22.

## Competidores directos

| Producto | Para quién | Propuesta | Precio | Salud / español / LatAm |
|---|---|---|---|---|
| Enterpret | Producto, CX y soporte en empresas mid-market de software [verificado: [G2](https://www.g2.com/products/enterpret-inc-enterpret/pricing) — 2026-09-22] | Taxonomía adaptativa sin etiquetado manual; conecta problemas con retención e ingresos para "decidir qué ignorar, arreglar o construir" [verificado: [enterpret.com/solutions/product](https://www.enterpret.com/solutions/product) — 2026-09-22] | A medida; mediana de contrato ~US$36k/año según terceros, sin cobro por usuario [verificado: resumen de búsqueda sobre G2/Capterra, no confirmado en la fuente — 2026-09-22] | Sin menciones de salud, español ni LatAm en su página de producto [verificado: enterpret.com — 2026-09-22] |
| Unwrap | Producto y CX en empresas grandes (DoorDash, GitHub) | Detección de tendencias y alertas sobre feedback | Desde US$24.000/año, según volumen de feedback e integraciones, sin cobro por usuario [verificado: [unwrap.ai/pricing](https://www.unwrap.ai/pricing) — 2026-09-22] | desconocido |
| Chattermill | CX, insights y producto en empresas grandes [verificado: [chattermill.com](https://chattermill.com/) — 2026-09-22] | Unifica feedback de todos los canales e idiomas | Promedio ~US$63.500/año, con una muestra de al menos 5 compras [verificado: [Vendr](https://www.vendr.com/buyer-guides/chattermill) — 2026-09-22] | desconocido |
| Qualtrics + Press Ganey Forsta | CX y experiencia del paciente en hospitales | Suite de experiencia; Press Ganey tiene análisis de comentarios con NLP en salud | desconocido | Compra cerrada el 2026-05-18 por US$6.750M; Press Ganey mide en más de 41.000 establecimientos de salud, sobre todo en EE. UU. [verificado: [HIT Consultant](https://hitconsultant.net/2026/05/18/qualtrics-acquires-press-ganey-forsta-6b-deal/) — 2026-09-22]. Presencia en Chile: desconocida |
| Medallia | CX empresarial | Captura en tiempo real, fuerte en datos no estructurados, incluido contact center [verificado: [Gartner Peer Insights](https://www.gartner.com/reviews/market/voice-of-the-customer-platforms/compare/medallia-vs-qualtrics) — 2026-09-22] | desconocido | desconocido |
| ExperiencIA CX (Chile) | Equipos de CX y operaciones; declara el vertical salud: post-atención, agendamiento, admisión, call center, reclamos [verificado: [experienciacx.com](https://www.experienciacx.com/) — 2026-09-22] | Consultoría más plataforma; IA que clasifica comentarios, motivos, emociones y criticidad sobre NPS, CSAT y reclamos | No publicado | Chilena, en español, con salud como vertical explícito. **No le habla a producto.** |

**Lo que prueban:** hay demanda pagada por "feedback cuantificado para decidir", al menos en empresas de software de EE. UU. y Europa. En Chile ya hay quien clasifica la voz del paciente con IA en español. **Lo que no prueban:** que un PO de un prestador de salud chileno pague por esto, ni que el espacio esté tomado. Nadie visible combina "equipos de producto + salud + español + el flujo del comité", pero un espacio vacío puede significar que no hay demanda.

## Alternativas y no consumo

- **El proceso manual actual:** exportaciones, Excel y un diccionario propio. Es la alternativa real en Clínica Alemana (señal `real` en el brief).
- **Speech analytics del contact center:** en Chile hay proveedores activos. HaddaCloud declara más de 7 millones de minutos al mes para más de 40 clientes corporativos en Chile, Colombia y EE. UU. [verificado: [haddacloud.com](https://haddacloud.com/blog/auditoria-llamadas-speech-analytics/) — 2026-09-22]; también Siptel Chile [verificado: [siptelchile.cl](https://www.siptelchile.cl/servicios/speech-analytics) — 2026-09-22]. El contact center podría **ya tener** clasificación automática de llamadas: sería a la vez competidor y fuente de datos.
- **Consultoras de CX e investigación** que clasifican con IA como servicio: ADA LAB [verificado: [ada-lab.cl](https://www.ada-lab.cl/en/) — 2026-09-22] y ExperiencIA CX.
- **Plataformas operativas de salud** con encuestas de satisfacción, pero sin análisis de reclamos: Keirón (clientes UC Christus, RedSalud, Clínica Las Condes, Bupa) [verificado: [keironsalud.com](https://www.keironsalud.com/es-cl/) — 2026-09-22].
- **Herramientas de gestión de producto** con extracción de insights por IA incluida: Productboard, con un plan Spark de US$15/maker/mes y créditos de IA [verificado: resumen de búsqueda sobre [featurebase.app](https://www.featurebase.app/blog/what-is-productboard), no confirmado en la fuente — 2026-09-22]. Es una alternativa barata si el PO solo necesita resumir feedback.
- **Usabilla**, que ya es una de las fuentes de Clínica Alemana, es a su vez una herramienta de voz del cliente, hoy parte de SurveyMonkey [conocimiento del modelo — verificar].

## Precios y modelos de negocio

- **Rango de las herramientas nativas de IA:** US$24k a ~64k al año por contrato, con precio según volumen de feedback y número de fuentes, **no por usuario** (Unwrap, Enterpret y Chattermill, con las fuentes de arriba).
- **Productboard** está en otro orden de magnitud (por maker), porque vende gestión de producto con IA como accesorio.
- **Precios de suites CX en Chile y de consultoras locales:** desconocidos. No se publican.
- **Implicancia:** el precio de referencia internacional (US$24–64k/año) es alto para un comprador que, según las personas, ya quemó credibilidad comprando herramientas de insights. Si Veta cobra por volumen, el volumen de un prestador chileno define el techo; ese volumen es desconocido.

## Posicionamiento

| Espacio | Quién está | A quién le habla |
|---|---|---|
| Medir la experiencia (encuestas, NPS, CAHPS) | Qualtrics/Press Ganey, Medallia | CX y experiencia del paciente |
| Analizar feedback con IA para decidir qué construir | Enterpret, Unwrap, Chattermill | Producto y CX, sobre todo en empresas de software, en inglés |
| Consultoría de CX con IA en salud, en Chile | ExperiencIA CX, ADA LAB | CX y operaciones |
| Analizar llamadas | HaddaCloud, Siptel y otros | Contact center |
| **Feedback de pacientes cuantificado para el comité de priorización de producto, en español** | nadie visible | — |

## Tendencias y tamaño

- **El mercado se está repreciando.** Los LLM abaratan el análisis de texto y la detección de tendencias, y "una plataforma que entrega insight sin integración al flujo de trabajo es una suscripción cara de reportes" [verificado: [CMSWire, 2026-05-18](https://www.cmswire.com/customer-experience/medallia-vs-qualtrics-the-voc-market-is-being-repriced/) — 2026-09-22]. El mismo artículo cita investigación de Medallia según la cual entre 30% y 40% de las áreas no actúa sobre los insights de CX.
- **Consolidación en salud:** Qualtrics compró Press Ganey Forsta (ver arriba).
- **Tamaño:** el mercado global de tecnología de experiencia del paciente llegaría a ~US$1.300M en 2031 [verificado: [MarketsandMarkets vía PR Newswire](https://www.prnewswire.com/news-releases/patient-experience-technology-market-worth-1-29-billion-by-2031---exclusive-report-by-marketsandmarkets-302885816.html) — 2026-09-22]. Sirve solo como orden de magnitud y no dice nada sobre Chile.
- **Chile:** en 2025 las clínicas privadas grandes compiten sobre todo con expansión física y nuevas especialidades (Alemana, Santa María, UC Christus, MEDS), no con inversión digital explícita [verificado: [Salud Manager, basado en DF](https://www.saludmanager.cl/guerra-en-el-sector-salud-clinicas-privadas-se-rearman-para-competir-en-2025) — 2026-09-22].
- **Universo del segmento:** los prestadores privados en Chile con equipo de producto digital propio serían del orden de 8 a 10 redes (Alemana, UC Christus, Santa María, Dávila, Las Condes, RedSalud, MEDS, Bupa/Integramédica, Indisa) [conocimiento del modelo — verificar]. La creencia de viabilidad pide 3 de 5, así que el universo alcanza para medirla, pero es chico para un negocio solo en Chile.
- **Regulación:** la Ley 21.719 de protección de datos personales entra en vigencia el **1 de diciembre de 2026** y crea la Agencia de Protección de Datos Personales [verificado: [BCN](https://www.bcn.cl/leychile/navegar?idNorma=1209272), [privacidadweb.cl](https://www.privacidadweb.cl/aprende/ley-21719) — 2026-09-22].

## Impacto en creencias

Primero las que la agenda del brief asignó a esta investigación:

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| [opportunity: voz-paciente-sin-metricas] [viability] La gerencia de producto/digital tiene autoridad y presupuesto (3 de 5 prestadores) | contradice (parcial) | Afuera, producto sí compra (los clientes de Enterpret y Unwrap incluyen PM). En Chile, los actores de voz del cliente en salud le venden a CX y operaciones (ExperiencIA CX, Keirón), y el contact center compra speech analytics. Todo verificado. No prueba que producto no pague, pero sube la prioridad de la pregunta "¿dónde está el presupuesto?" en las entrevistas |
| [opportunity: voz-paciente-sin-metricas] [value] La aprobación de ítems de experiencia es menos de la mitad que la de negocio, por falta de cuantificación (reformulada el 2026-09-23: proporción ejecutada desde el backlog) | no dice nada | La investigación secundaria no llega al comité de un prestador. Como señal general: entre 30% y 40% de las áreas no actúa sobre los insights de CX (Medallia vía CMSWire, verificado), otro segmento |
| [product] [value] Si los códigos llegaran con métricas, los PO lograrían priorizarlos | apoya (débil) | Hay productos pagados cuya promesa central es exactamente esta (Enterpret, Unwrap, verificado), pero para PM de software, no para PO de salud |
| [product] [value] La consolidación manual es el cuello de botella | no dice nada | — |
| [product] [feasibility] Un modelo puede clasificar las fuentes contra el diccionario común | apoya | Varias herramientas clasifican sin etiquetado manual (Enterpret) y en español en salud chilena (ExperiencIA CX), todo verificado. No prueba la calidad contra *su* diccionario |
| [product] [feasibility] Acceso continuo a fuentes de otras gerencias | no dice nada | La integración técnica con más de 50 fuentes es estándar (Enterpret, verificado); el acceso político no se ve desde afuera |
| [business] [viability] El comprador es producto, y experiencia, contact center y SAC aceptan la codificación automática | contradice (parcial) | Igual que la viabilidad de la oportunidad. Además, el contact center puede tener ya su propia clasificación (speech analytics), que Veta tendría que usar o desplazar |
| [market] [viability] El patrón se generaliza a otras industrias | apoya (débil) | Las herramientas nativas de IA son agnósticas a industria y se venden en software, delivery y energía (verificado). No prueba que Veta generalice |

**Nueva pregunta que surge de la investigación:** si la clasificación con IA se está volviendo commodity, ¿qué parte del valor de Veta no se puede copiar con un LLM y el Excel actual? Según la investigación, sería la integración al comité de priorización (el formato de la evidencia, el circuito de vuelta), no la codificación.

## Qué sigue necesitando research primario

**Solo entrevistas pueden explicarlo** (el universo es muy chico para una encuesta):
- En cada prestador, **quién es dueño del presupuesto de voz del cliente**: producto, experiencia o contact center. Qué herramientas ya tienen (Qualtrics, Medallia, speech analytics, consultoras) y quién las compró.
- **Por qué no se ejecutan los ítems de experiencia:** falta de cuantificación, falta de un criterio o instancia de priorización, o capacidad. Es la creencia de valor, y ninguna fuente secundaria llega ahí.
- **Qué evidencia bastaría para ganarle a una solicitud del negocio.** Es la pregunta de la contraparte comercial que está fuera del set de personas.
- **Si el PO de salud pagaría US$24k o más al año** o espera algo más barato. Es una disposición a pagar; se explora cualitativamente.

**Lo que sí se puede contar sin encuesta:** el universo de prestadores con equipo de producto en Chile (hoy es conocimiento del modelo) se puede listar a mano con LinkedIn y los sitios de cada red.

**Lo que se puede verificar dentro de Clínica Alemana sin entrevistas:** si ya existe una suite de voz del cliente o speech analytics con licencia, y quién la paga.
