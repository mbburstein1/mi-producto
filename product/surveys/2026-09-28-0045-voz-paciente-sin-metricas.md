---
opportunity: voz-paciente-sin-metricas
brief: product/opportunities/2026-09-22-1815-voz-paciente-sin-metricas.md
created: 2026-09-28
status: draft
gate: publicar solo si el análisis del backlog de Jira (2026-10-06) no descarta la creencia de valor
---

# Encuesta: cómo compite la voz del paciente en el backlog de producto

- **Objetivos de aprendizaje:**
  1. **Frecuencia de la competencia** — con qué frecuencia un ítem de voz del paciente compite con una iniciativa nueva y cuántos llegan a un sprint frente a las iniciativas nuevas. → *Decide si el problema es frecuente o anecdótico, y si la brecha que reporta la gente es coherente con lo que muestre Jira.*
  2. **Causa de la no ejecución** — evidencia/criterio vs. capacidad vs. gobierno vs. otra. → *Si la mayoría atribuye la no ejecución a capacidad o gobierno y no a evidencia o criterio, la creencia [opportunity] [value] cae.*
  3. **Evidencia pedida vs. evidencia disponible** — qué les preguntan cuando llevan un ítem y qué pueden responder con datos. → *Qué tiene que traer una señal de Veta (volumen, tendencia, paso del journey, costo) para competir.*
  - Además: **reclutar** 5–7 PO/PM con baja ejecución (incluidos algunos con menos de un año en el rol) y 1–2 que sí logran ejecutar ítems de experiencia, para las entrevistas del 2026-10-23.
- **Respondentes:** Product Owners, Product Managers/subgerentes de producto, UX y soporte de producto de productos digitales (app, portal, agendamiento, resultados) de prestadores de salud privados en Chile. Personas: [[rodrigo-valenzuela]], [[camila-ortuzar]], [[benjamin-araya]], [[francisca-lagos]]. Fuera: sponsors/gerentes (su creencia es de viabilidad y va a conversación, no a encuesta), CX, contact center, TI, y organizaciones sin equipo de producto ([[andres-bittencourt]]).
- **Duración estimada:** 3 de screening + 11 preguntas + 3 de opt-in, ~5–6 min.

## Texto de inicio (para el respondente)

> Estamos investigando cómo los equipos de producto digital de prestadores de salud deciden qué entra a sus sprints cuando compiten mejoras que vienen de los pacientes con iniciativas nuevas. Son 5 minutos. No te pedimos datos de pacientes ni de tu organización. Tus respuestas son anónimas salvo que, al final, quieras dejar un contacto.

## Screening

S1. ¿Dónde trabajas hoy? [opción única]
   - Prestador de salud privado en Chile (clínica, red de salud, centro médico)
   - Prestador de salud público
   - Isapre, seguro o aseguradora
   - Consultora o proveedor de tecnología
   - Otra industria
   → **descalificar** si no es "Prestador de salud privado en Chile"

S2. ¿Cuál de estos describe mejor tu rol actual? [opción única]
   - Product Owner
   - Product Manager, jefe/a o subgerente/a de producto digital
   - UX, diseño o research
   - Soporte de producto / soporte digital
   - Experiencia del paciente / CX
   - Contact center o atención de reclamos
   - TI o desarrollo
   - Gerente/a (digital, transformación, TI u otra)
   - Otro
   → **continuar** solo con PO, PM/jefatura de producto, UX o soporte de producto; **descalificar** el resto

S3. En los últimos 3 meses, ¿participaste en proponer o decidir qué entra al backlog de un producto digital para pacientes (app, portal, agendamiento, resultados u otro)? [sí / no]
   → **descalificar** si "no"

## Preguntas

*En esta encuesta, "ítem de voz del paciente" es una mejora que nace de lo que dicen los pacientes: reclamos, NPS, CSAT, comentarios en la app o la web, o motivos de contacto del contact center. "Iniciativa nueva" es un feature o un pedido de stakeholders o de las gerencias.*

Q1. En el último trimestre, ¿cuántos ítems de voz del paciente propusiste tú, o viste proponer en tu equipo, para el backlog de tus productos? [opción única]
   - Ninguno · 1–2 · 3–5 · 6–10 · Más de 10 · No sé
   > Goal: 1 — frecuencia (denominador de Q2)

Q2. De esos ítems de voz del paciente, ¿cuántos llegaron a un sprint? [opción única]
   - Ninguno · Menos de la mitad · Más o menos la mitad · Más de la mitad · Todos · No sé
   > Goal: 1 — tasa de ejecución de voz del paciente (autorreportada; se contrasta con Jira)

Q3. En el mismo trimestre y en los mismos productos, de las iniciativas nuevas que se propusieron, ¿cuántas llegaron a un sprint? [opción única]
   - Ninguna · Menos de la mitad · Más o menos la mitad · Más de la mitad · Todas · No sé
   > Goal: 1 — tasa de ejecución de iniciativas nuevas; la brecha Q2 vs. Q3 por respondente es el dato

Q4. En el último trimestre, ¿cuántas veces tuviste que elegir, o viste elegir, entre un ítem de voz del paciente y una iniciativa nueva para el mismo espacio en un sprint? [opción única]
   - Nunca · 1–2 veces · 3–5 veces · Más de 5 veces · No sé
   > Goal: 1 — frecuencia de la competencia directa

Q5. Piensa en el **último** ítem de voz del paciente que propusiste o viste proponer y que **no** entró a un sprint. ¿Cuál fue la razón principal? [opción única; orden aleatorio de las 6 primeras]
   - No había datos de cuánto le costaba el problema al negocio
   - No había una regla o criterio para compararlo con una iniciativa nueva
   - El sprint ya estaba lleno con compromisos previos (capacidad del equipo)
   - Lo decidió otra instancia o área (gerencia digital, TI, comité, stakeholders)
   - Dependía de otro equipo, de un proveedor o era técnicamente difícil
   - Se consideró poco importante o poco frecuente
   - No sé por qué no entró
   - Otra: ______
   - No recuerdo ningún caso así
   > Goal: 2 — causa de la no ejecución. Mapeo para el análisis: evidencia/criterio = opciones 1–2; capacidad = 3; gobierno = 4; otras = 5–8. "Poco importante" (6) es la lectura que contradice la oportunidad: el ítem perdió con criterio.

Q6. La última vez que se llevó un ítem de voz del paciente a una revisión de priorización en la que estuviste, ¿qué preguntaron sobre él? [selección múltiple]
   - A cuántos pacientes o casos afecta (volumen)
   - Si está creciendo o bajando (tendencia)
   - En qué paso del journey ocurre
   - Cuánto le cuesta al negocio (contactos, agendamientos perdidos, ingresos)
   - Cuánto cuesta arreglarlo (esfuerzo)
   - Cómo se compara con otra iniciativa
   - No preguntaron nada: se dejó para después sin discutirlo
   - No he estado en una revisión donde se llevara uno
   - Otra: ______
   > Goal: 3 — evidencia pedida

Q7. Y en esa misma ocasión, ¿cuáles de estas cosas se pudieron responder **con datos**? [selección múltiple; mostrar solo si Q6 no es "No he estado…"]
   - Volumen · Tendencia · Paso del journey · Costo para el negocio · Costo de arreglarlo · Comparación con otra iniciativa
   - Ninguna: el argumento fue cualitativo (comentarios, casos, opinión)
   > Goal: 3 — evidencia disponible; la brecha Q6 vs. Q7 es el hallazgo

Q8. La última vez que tú armaste el argumento para un ítem de voz del paciente, ¿cuánto tiempo te tomó reunir los datos? [opción única]
   - Menos de una hora · Hasta un día · 2 a 5 días · Más de una semana · No encontré los datos que necesitaba · No he armado ninguno
   > Goal: 3 — costo de producir la evidencia (toca también la creencia [product] [value] de la consolidación manual)

Q9. ¿Qué es lo más difícil de lograr que un ítem de voz del paciente entre a un sprint? [abierta, opcional]
   > Goal: 2 — causa en sus palabras; codificar contra las categorías de Q5 y abrir las que no estén

Q10. ¿Cuánto tiempo llevas en tu rol actual? [opción única]
   - Menos de 1 año · 1 a 3 años · Más de 3 años
   > Goal: 1–2 — corte novato vs. experto ([[benjamin-araya]] vs. [[rodrigo-valenzuela]]); reclutamiento

Q11. ¿En qué red o prestador trabajas? [opción única, opcional]
   - UC Christus · Clínica Alemana · Clínica Santa María · Clínica Dávila · Clínica Las Condes · RedSalud · MEDS · Bupa / Integramédica · Indisa · Otro: ______ · Prefiero no decir
   > Goal: 1–2 — si el patrón se repite fuera del prestador de referencia (cuántas redes distintas responden)

## Screening + opt-in (reclutamiento para entrevistas)

R1. En los últimos 6 meses, ¿propusiste tú mismo/a al menos un ítem de voz del paciente para priorización? [sí / no]
   → **no es candidato/a** si "no", o si S2 no es PO ni PM/jefatura de producto (las entrevistas del 2026-10-23 son a PO/PM)

R2. ¿Aceptarías una conversación de 30 minutos sobre cómo priorizan en tu equipo? [sí / no]

R3. Si respondiste que sí, ¿cómo te contactamos? Nombre y correo o perfil de LinkedIn. [abierta, opcional; mostrar solo si R2 = sí]
   > *Texto al respondente:* "Usaremos este dato solo para coordinar la conversación y lo guardaremos separado de tus respuestas."

> Para el análisis: etiquetar a cada candidato/a según confirme o contradiga la creencia de valor. **Contradice** si Q2 ≥ Q3 o si Q5 es capacidad, gobierno o "poco importante"; **confirma** si Q2 < Q3 y Q5 es evidencia o criterio. Entrevistar primero a quienes contradicen, y reservar 1–2 cupos para quienes reportan buena ejecución (Q2 "más de la mitad" o "todos").

## Distribución

| Canal | A quién llega y su sesgo | Alcance aprox. | Link |
|---|---|---|---|
| Teams/correo directo — prestador de referencia | PO, PM, UX y soporte de producto de los productos digitales del prestador ([[rodrigo-valenzuela]], [[camila-ortuzar]], [[benjamin-araya]], [[francisca-lagos]]). **Sobrerrepresenta** a quienes conocen la iniciativa y ya participan del proceso de voz del paciente; pueden responder lo que creen que se espera. Tasa de respuesta alta. | 10–20 | `?canal=interno` |
| Contactos personales en otras redes | PO/PM/UX de otros prestadores con quienes hay relación. **Sesgo de afinidad**: tienden a responder con más detalle y a coincidir con quien pregunta; sobrerrepresenta a equipos de producto más maduros. | 5–10 | `?canal=personal` |
| LinkedIn directo a otras redes (lista armada a mano por red y rol: UC Christus, Santa María, Dávila, Las Condes, RedSalud, MEDS, Bupa/Integramédica, Indisa) | PO/PM/UX que no conocen la iniciativa. **Sobrerrepresenta** a los más activos en LinkedIn y a quienes el tema les importa (autoselección por interés); tasa de respuesta en frío baja. | 20–40 | `?canal=linkedin` |

- **Meta de n:** ≥15 PO/PM y ≥8 UX/soporte de producto en total, con ≥8 respuestas de fuera del prestador de referencia. Con menos de 30 por segmento, **todos los resultados son direccionales**: se reportan como conteos, no como porcentajes.
- **Factibilidad:** el alcance sumado es 35–70 personas. Con tasas razonables (interno ~60–80%, personal ~50–70%, LinkedIn en frío ~10–20%) se esperan entre ~11 y ~31 respuestas calificadas. La meta de 23 solo se alcanza en el escenario optimista, y ≥15 PO/PM es lo más frágil. Para cubrirla: seguimiento a los 3–4 días en los tres canales y pedir a cada contacto personal que reenvíe a su equipo (con su propio link de canal personal).
- **Compuerta:** publicar solo después del análisis del backlog de Jira (2026-10-06), si la tasa de ejecución de voz del paciente resulta menor que la mitad de la de iniciativas nuevas.
- **Primera revisión:** 2026-10-09
- **Cierre:** 2026-10-13
