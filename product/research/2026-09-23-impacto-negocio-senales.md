---
source: secondary
method: mixed
date: 2026-09-23
question: ¿Cómo cuantifican hoy las herramientas de voz del cliente y de analítica digital el impacto de negocio de un problema (ingresos, costo de contactos, fuga), con qué datos externos lo cruzan y con qué precisión declarada?
opportunity: voz-paciente-sin-metricas
---

# Research: cómo se estima el impacto de negocio de una señal de voz del cliente

Research acotado a una sola creencia: `[product] [feasibility]` *Veta puede estimar el impacto de negocio de una señal cruzándola con datos que viven fuera de las fuentes de voz del cliente, con una precisión que las gerencias digital y de TI acepten al priorizar.* No cubre competidores, precios ni tamaño de mercado; eso está en [el research del 2026-09-22](2026-09-22-voz-paciente-sin-metricas-mercado.md).

Hay tres formas establecidas de poner un problema en términos de negocio, y cada una depende de un dato que no está en la voz del cliente: **ingreso por cliente** (CRM), **conversión del funnel** (analítica digital) o **costo por contacto** (contact center). Ninguna herramienta revisada publica la precisión de sus estimaciones: son ayudas para ordenar prioridades, no cifras auditadas. Para Veta, el método es factible y conocido. La incógnita es si la clínica tiene el dato externo que cada método necesita y si las gerencias digital y de TI aceptan una estimación sin intervalo de confianza. Eso no se responde desde afuera.

## Tres métodos para cuantificar impacto

| Método | Quién lo usa | Cómo calcula | Dato externo que necesita | Precisión declarada |
|---|---|---|---|---|
| **Ingreso expuesto por cuenta** | Enterpret | Asocia cada comentario a un usuario o cuenta y suma el ingreso (ARR) de las cuentas que mencionan el tema: "mencionado por $X de ARR" en vez de "mencionado N veces" | CRM o data warehouse con ID de usuario o cuenta (Salesforce, Snowflake, Census, webhook) [verificado: [Enterpret blog](https://www.enterpret.com/blog/connect-customer-feedback-to-revenue-with-synced-users-and-accounts) — 2026-09-23] | No publicada. Es una suma de ingreso asociado, no una pérdida causal |
| **Brecha de conversión entre cohortes** | Contentsquare, Quantum Metric, Medallia (analítica digital) | Compara usuarios que vivieron la fricción contra usuarios que hicieron lo mismo sin vivirla: diferencia de conversión × tráfico afectado × valor por conversión | Analítica de sesiones del sitio o la app, y un valor asignado a cada conversión | No publicada. Quantum Metric habla de un "algoritmo patentado" que "infiere" el costo de oportunidad [verificado: [Quantum Metric](https://www.quantummetric.com/blog/one-touch-quantification-identify-opportunities-quantify-issues-prioritize) — 2026-09-23]; Medallia no explica su margen de error [verificado: [Medallia](https://www.medallia.com/products/digital-experience-analytics/revenue-impact/) — 2026-09-23] |
| **Costo de contactos evitables** | Qualtrics (XM Discover) | Identifica el motivo de los contactos evitables y calcula su costo operativo: volumen × costo por contacto | Volumen de contactos por motivo y costo por contacto del contact center | No publicada. Qualtrics lo presenta como "the evidence they need to prioritize investment" [verificado: [Qualtrics Healthcare](https://www.qualtrics.com/industries/healthcare/) — 2026-09-23] |

Detalles que importan para Veta:

- **Medallia permite asignar valor a cualquier evento del funnel**, no solo a una compra; su ejemplo es "signing up for a consultation" [verificado: [Medallia](https://www.medallia.com/products/digital-experience-analytics/revenue-impact/) — 2026-09-23]. Es el mismo caso que un agendamiento abandonado.
- **Contentsquare calcula la oportunidad** a partir del tráfico del segmento con peor desempeño, su diferencia de conversión y el ingreso mediano del segmento con mejor desempeño [verificado: resultado de búsqueda sobre [Contentsquare Impact Quantification](https://contentsquare.com/platform/capabilities/impact-quantification/) — 2026-09-23; la documentación de soporte devolvió 403]. Esto es una correlación: el método no aísla la causa.
- **Enterpret exige configuración con el CSM** para conectar las cuentas [verificado: [Enterpret blog](https://www.enterpret.com/blog/connect-customer-feedback-to-revenue-with-synced-users-and-accounts) — 2026-09-23]. El cruce no es automático.
- **Unwrap, competidor directo en voz del cliente, no hace atribución de ingresos**: ordena temas por volumen y tendencia [fuente de terceros: [aicxstack](https://www.aicxstack.com/blog/unwrap-review) y [The CX Lead](https://thecxlead.com/tools/unwrap-review/) vía resultado de búsqueda — 2026-09-23]. Su guía de ROI cuantifica el ahorro de horas de los PM, no el impacto de cada tema [verificado: [Unwrap](https://www.unwrap.ai/post/unwrap-roi) — 2026-09-23].

## Qué prueba y qué no

- **Prueba** que traducir problemas de experiencia a dinero es una práctica que se vende, con tres métodos conocidos, y que se usa para priorizar.
- **Prueba** que entre las herramientas de voz del cliente no es universal: Enterpret lo hace y Unwrap no. Entre las de analítica digital sí es estándar, pero ellas no leen voz del cliente, sino comportamiento en sesiones.
- **No prueba** que esas cifras sean precisas. Ningún proveedor publica margen de error, y los métodos de cohorte y de ingreso expuesto son correlacionales. La aceptación de la cifra depende de quién la mira, no del método.
- **No prueba** que funcione en salud B2C chilena. El método de ingreso por cuenta nace en SaaS B2B, donde cada cliente tiene un ARR. En un prestador, el equivalente sería el ingreso por paciente, que exige unir la voz del paciente con su identidad (RUT o ID de ficha): dato de salud sensible bajo la Ley 20.584 y la Ley 21.719.

## Referencias en salud (solo órdenes de magnitud)

Las cifras de fuga de pacientes que circulan vienen de proveedores estadounidenses y no se trasladan a Chile. Ejemplos: "$294 in lost revenue over the next year" por interacción perdida en agendamiento [fuente de proveedor: [Sequence Health](https://www.sequencehealth.com/appointment-scheduling/scheduling-leakage-downstream-revenue/) vía resultado de búsqueda — 2026-09-23]; entre 10% y 30% de los ingresos de un hospital perdidos por fuga de derivaciones [fuente de proveedor: [WebMD Ignite](https://webmdignite.com/faq/patient-referral-leakage) vía resultado de búsqueda — 2026-09-23]. Sirven para mostrar que el argumento existe, no como supuesto de cálculo.

El costo por contacto telefónico se ubica en torno a US$4–10 en referencias de la industria [fuente de terceros: [Klipfolio](https://www.klipfolio.com/resources/kpi-examples/call-center/cost-per-contact) vía resultado de búsqueda — 2026-09-23], muy dependiente de salarios y país. El de un contact center de salud en Chile es desconocido.

## Implicancia para Veta

Los tres métodos se corresponden con los impactos que nombra el overview:

| Impacto en el overview | Método | Dato que Veta tendría que conseguir en la clínica | Dueño probable |
|---|---|---|---|
| Costo de contactos evitables | Costo de contactos evitables | Volumen por motivo y costo por contacto | Contact center (Verónica), con parte de los datos en el proveedor externalizado |
| Agendamientos abandonados | Brecha de conversión | Analítica del funnel de agendamiento web/app | Gerencia digital o TI; si existe una herramienta, es desconocida |
| Pacientes que se van | Ingreso expuesto | Unión de la voz del paciente con la identidad y el ingreso por paciente | Finanzas o TI; restricción legal fuerte |

El más directo es el costo de contactos evitables: la aritmética es simple y el dato es operativo, no sensible. Su debilidad es la calidad de la tipificación del contact center (en la persona, casi un tercio termina en "consulta general" — synthetic, `veronica-sepulveda.md`). El más difícil es "pacientes que se van", por la unión de identidades.

Esto suma una dependencia que la creencia de acceso no nombra: además de las fuentes de voz del cliente, Veta necesitaría datos de negocio (costo por contacto, analítica del funnel, ingreso) que tampoco controla producto.

## Impacto en creencias

Primero la creencia que motivó este research:

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| [product] [feasibility] Veta puede estimar el impacto de negocio cruzando la señal con datos fuera de la voz del cliente, con precisión que las gerencias acepten | apoya (método) / no dice nada (precisión) | Hay tres métodos en uso, verificados en Enterpret, Contentsquare, Quantum Metric, Medallia y Qualtrics. Ninguno publica su precisión, y todos dependen de un dato externo cuya existencia en la clínica es desconocida. La parte de "precisión aceptable" es una pregunta de aceptación del comprador y solo se responde con entrevistas |
| [product] [value] Si la señal llega en impacto de negocio, los PO logran priorizarla | apoya (débil) | Los proveedores venden la cuantificación como herramienta de priorización (Enterpret, Qualtrics, verificado). No hay evidencia de que cambie decisiones en un comité o backlog de salud |
| [product] [feasibility] Acceso continuo a fuentes de otras gerencias | no dice nada, pero amplía el alcance | Estimar impacto agrega fuentes que no son de voz del cliente (costo por contacto, analítica, ingreso por paciente), con otros dueños. El problema de acceso es más grande de lo que la creencia describe |
| [opportunity: voz-paciente-sin-metricas] [viability] La gerencia de producto/digital tiene autoridad y presupuesto | no dice nada | Las herramientas de analítica digital que cuantifican impacto se venden a equipos digitales y de producto (Quantum Metric tiene una página para equipos de producto) [conocimiento del modelo — verificar], pero eso no dice nada de presupuesto en prestadores chilenos |

**Nueva pregunta que surge:** si la clínica ya tiene analítica del funnel de agendamiento, la gerencia digital podría estar viendo el costo de la fricción sin Veta. ¿Qué agrega Veta ahí? Probablemente el *por qué* (lo que dice el paciente) unido al *cuánto* (lo que muestra el funnel), pero hay que confirmarlo.

## Qué sigue necesitando research primario

**Verificable dentro de Clínica Alemana, sin entrevistas:**
- Si existe analítica de sesiones o funnel en el agendamiento web/app (GA4, Contentsquare, Medallia DXA u otra) y quién la administra.
- Si el contact center conoce su costo por contacto y si la tipificación permite separar los motivos relacionados con productos digitales.
- Si legal permitiría unir la voz del paciente con su identidad para calcular ingreso por paciente.

**Solo entrevistas pueden explicarlo:**
- Qué moneda de impacto aceptan las gerencias digital y de TI al comparar con una iniciativa nueva (costo, conversión o ingreso) y cuánta imprecisión toleran: ¿basta un orden de magnitud o piden el mismo rigor que la proyección de ingresos de una iniciativa?
- Cómo se construye hoy la proyección de ingresos de las iniciativas nuevas. Si también es una estimación sin intervalo, la vara que debe cumplir Veta es más baja de lo que parece.
