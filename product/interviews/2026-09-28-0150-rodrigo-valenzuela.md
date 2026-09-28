# Entrevista — Rodrigo Valenzuela

- **Persona:** [Rodrigo Valenzuela](../personas/rodrigo-valenzuela.md) — Subgerente de Producto Digital en un prestador de salud privado
- **type:** primary
- **source:** synthetic
- **Modo:** exploración
- **Tema:** cómo llega la voz del paciente a la priorización y cómo compite con las iniciativas nuevas
- **Fecha:** 2026-09-28

---

*Rodrigo entra a la videollamada desde el celular, con el audífono puesto. Se nota que viene de otra reunión.*

**Rodrigo:** Hola, hola… perdón, venía saliendo de una revisión con TI que se alargó, como siempre. Tengo unos cuarenta minutos, ¿te sirve? Dale, pregunta nomás.

**Entrevistador:** Cuéntame de tu rol hoy: ¿qué productos digitales manejas y hace cuánto estás en el puesto?

**Rodrigo:** Ya van a ser… tres años, un poco más, entré a mediados del 2023. Antes estuve harto tiempo en banca y un rato en retail, así que salud era nuevo para mí. Tengo la app de pacientes y el portal web, que son casi lo mismo pero por dentro no, más el agendamiento online, resultados de exámenes y telemedicina. Tengo cuatro PO y más o menos cada uno tiene un pedazo de eso. Y bueno, en la práctica mi pega es mucho más reuniones con TI y con mi gerente que producto propiamente tal, pero ya me acostumbré.

**Entrevistador:** ¿Cómo te llega hoy la voz del paciente — reclamos, NPS, comentarios en la app?

**Rodrigo:** Uf… me llega por pedazos, esa es la verdad. Lo más concreto es lo que me traen los PO a fin de mes: un Excel donde el equipo de UX ya juntó comentarios de Usabilla, del NPS y algo de reclamos, con categorías. El NPS lo maneja experiencia del paciente, que es otra gerencia, y los reclamos van por SAC, que también es otro mundo. A veces me entero de algo por ahí, por un correo o porque alguien lo menciona en un pasillo.

*Hace una pausa.*

Y lo otro, que es medio triste, es que muchas veces me entero por arriba: cuando algo llega a redes o a mi gerente le escribe un conocido. Ahí te toca salir apagando el incendio, y lo peor es que muchas veces el problema estaba en el Excel hace dos meses, perdido entre cuarenta filas más.

**Entrevistador:** Cuéntame de la última vez que se decidió qué entraba al sprint o al mes — donde sea que eso se decida en tu equipo — y había un ítem de voz del paciente sobre la mesa. Camina conmigo por lo que pasó, paso a paso.

**Rodrigo:** Ya… a ver, la de fin de agosto, que la tengo fresca porque no me dejó muy tranquilo.

*Se acomoda, deja de mirar el otro monitor.*

Es la revisión de fin de mes. Una hora, a veces menos, con los cuatro PO, y proyectamos el Excel de priorización del mes anterior para ver si algo cambia. Ese día la Carolina, que tiene agendamiento, trajo un ítem: los pacientes no encontraban cómo cancelar o cambiar una hora desde la app. El botón estaba escondido dentro del detalle de la cita, y ella tenía hartos comentarios de Usabilla sobre eso y un par de reclamos que le había pasado SAC. Ella decía que la gente terminaba llamando al contact center para algo que se podía hacer sola.

Y al frente estaba… bueno, lo que estaba ese mes era la integración con una isapre para el bono electrónico. Eso lo comprometí yo con mi gerente y con TI en el roadmap del semestre, TI ya tenía gente asignada, había una fecha dicha arriba.

*Se ríe un poco, incómodo.*

Entonces le pregunto a la Carolina: ¿cuántas llamadas son? ¿Cuánto nos cuesta? Y ella tenía los comentarios, que eran bien claros, pero no tenía un número. Tenía algo como "hartos". Y yo sé que si voy donde mi gerente a decirle "oye, movamos la isapre dos semanas porque hay comentarios de que el botón de cancelar está escondido", me va a mirar raro. Y con razón, igual.

Así que quedó para el próximo mes. Que en la práctica… espera, no, en realidad lo movimos a "pendiente", que es peor, porque "pendiente" no tiene fecha. Sigue ahí. Y lo que me molesta es que yo sospecho que esas llamadas sí nos cuestan plata, y mi KPI es justamente el costo de atención por canal digital. O sea, me estoy pegando un tiro en el pie, pero no lo puedo probar. Y la Carolina se fue de la reunión medio desanimada. No me lo dijo, pero se notó.

**Entrevistador:** ¿Alguien intentó conseguir el dato que faltó? ¿Quién, y qué llegó?

**Rodrigo:** Sí, la Carolina. A mí me da un poco de vergüenza decirlo, pero yo no lo pedí, lo pidió ella.

Le escribió directo a una supervisora del contact center que conoce, porque si lo pides formal tienes que ir por la jefatura de ellos y eso tiene su gerencia. Se demoró como tres semanas y le llegó un Excel con los motivos de llamada del mes. El problema es que ellos lo tienen codificado a su manera: había una categoría que decía algo como "Agendamiento – modificación o anulación", con unas… no me acuerdo bien, varios miles de llamadas en el mes. Pero ahí adentro está todo: la gente que no tiene app, los adultos mayores que siempre llaman, los que cambian una hora con un médico que se enfermó… No hay cómo saber cuántas de esas son porque el botón está escondido.

*Suspira.*

Entonces llegó un número, pero no el número. Si yo llevo "varios miles de llamadas" arriba, lo primero que me van a preguntar es cuántas son culpa nuestra, y no tengo la respuesta. Y si lo inflo y después alguien lo revisa, ahí sí que quedo mal. Ya me ha pasado con otras cosas.

Ah, y lo otro. Tenemos analítica en la app, con eventos y todo eso. Nadie la cruzó. Supongo que se podía ver cuánta gente entraba al detalle de la cita y después no hacía nada… pero eso lo ve otro equipo, y tampoco sé si está bien marcado ese evento. Honestamente no sé. Habría que preguntarle al que lleva la analítica, y ahí son otras dos semanas.

**Entrevistador:** ¿Qué pasó al final — entró, quedó pendiente, se descartó?

**Rodrigo:** Sigue pendiente. En la revisión de septiembre, que fue la semana pasada, ni siquiera se habló. La Carolina no lo volvió a traer, y yo tampoco lo pregunté, para ser honesto. Creo que ella entendió que sin número no pasaba, y no tenía uno mejor.

*Piensa un momento.*

Si miras Jira debe estar ahí, en el backlog, con prioridad "media" o sin prioridad, junto con otros treinta así. Ninguno está descartado, pero tampoco van a entrar. Mi apuesta es que va a entrar el día que alguien de arriba intente cancelar una hora y no pueda, o que salga en redes. Ahí sí se hace en una semana.

**Entrevistador:** ¿Te ha tocado que un ítem de voz del paciente llegara con un número de costo o de impacto? ¿Qué pasó con él?

**Rodrigo:** Una vez, sí. Y no fue tan limpio como uno quisiera.

Fue el año pasado, con resultados de exámenes. La gente no podía abrir el PDF desde la app porque le pedía una clave que no sabía cuál era, y terminaban llamando o escribiendo. Esa vez tuvimos suerte, porque el que llevaba soporte de producto tenía un conteo propio de tickets por ese motivo, bien específico, y alguien del contact center nos dio un costo por llamada. Multiplicamos, dio algo como… no me acuerdo exacto, varios millones al mes. Con eso fui donde mi gerente.

*Levanta las cejas.*

Y sí entró, pero me costó dos reuniones. En la primera, el gerente de TI preguntó de dónde salía el costo por llamada, porque el contact center usa uno para su presupuesto y finanzas tiene otro, y ahí se fue media hora discutiendo el número y no el problema. Tuve que volver con el costo que usa finanzas, que era más bajo, y aun así daba. Y siendo muy honesto, creo que lo que terminó de convencer a mi gerente fue que a su señora le había pasado lo mismo esa semana.

Así que el número ayudó a abrir la conversación, eso sí. Pero no basta con tener un número: tiene que ser uno que nadie arriba pueda desarmar en cinco minutos. Si te lo desarman, pierdes ese ítem y además la próxima vez que llegues con un número te miran con desconfianza.

**Entrevistador:** Ahora cuéntame de una vez que un ítem de voz del paciente SÍ entró a un sprint — uno que llevaste tú, o que se decidió en una revisión donde estabas. ¿Qué pasó?

*Se queda pensando un rato.*

**Rodrigo:** Déjame pensar en uno que no haya sido el de exámenes… Ya, uno de telemedicina, de este año, como en abril.

Los pacientes entraban a la teleconsulta y no se daban cuenta de que el navegador les pedía permiso para la cámara, entonces el médico los esperaba y ellos veían una pantalla negra. Había comentarios, y los médicos también reclamaban por su lado. Pero no entró por eso, para ser honesto. Entró porque ese mes TI se atrasó con una integración que teníamos comprometida y nos quedó medio sprint libre. El PO tenía el ítem a mano, el desarrollador dijo que eran dos o tres días, y lo metimos. O sea, entró de relleno, no porque haya ganado.

Y hay otro caso que se repite: cuando el arreglo toca la misma pantalla que un feature nuevo, el PO lo mete adentro. "Ya que estamos rediseñando el pago, arreglemos también esto". Eso pasa harto, y de hecho yo lo incentivo un poco, porque así no tengo que defenderlo.

*Se ríe.*

Si lo pienso, los ítems de experiencia no entran por mérito. Entran cuando sobra espacio, cuando van colgados de otra cosa o cuando explotan. Lo de telemedicina lo arreglamos en tres días, pero estuvo como cinco meses en el backlog. En ese tiempo se perdieron consultas, y los médicos de ese servicio no nos creen mucho desde entonces.

**Entrevistador:** Piensa en la última iniciativa nueva — un feature o un pedido de stakeholders — que entró a tu sprint (o a los de tus equipos). ¿Cómo se decidió que entrara?

**Rodrigo:** La última… la sección de chequeos preventivos en la app. Que la gente pueda ver y comprar paquetes de exámenes, tipo chequeo ejecutivo o el de la mujer. Entró en julio.

Eso vino de la gerencia comercial. Lo plantearon en una reunión de gerentes donde estaba mi gerente, y el gerente general dijo algo como "eso debería estar en la app". Con eso ya estaba prácticamente decidido. Después comercial mandó una presentación con una proyección de ventas, que si la app capturaba no sé qué porcentaje de los chequeos se ganaba tanto. Yo la revisé, la llevé a la revisión con TI, le asignamos un PO y entró en el siguiente sprint.

*Se detiene.*

Y ahora que lo cuento… el número de comercial nadie lo desarmó. Era una proyección. Nadie preguntó de dónde salía el porcentaje. Al de exámenes le discutimos el costo por llamada media hora, y esta proyección pasó sin que nadie preguntara nada.

Bueno, ahí está la diferencia, supongo. Cuando lo pide un gerente, el número es un trámite, lo necesitas para dejar registro. Cuando lo trae un PO desde abajo, el número tiene que aguantar un interrogatorio. Y lo de los chequeos, por lo que he visto, ha vendido bastante menos de lo proyectado. Pero nadie lo ha revisado formalmente, y tampoco creo que se revise.

**Entrevistador:** Después de que esa iniciativa salió, ¿alguien volvió a mirar si el número se cumplió?

**Rodrigo:** No, formalmente no. El PO lo mira de vez en cuando en Power BI, las compras que salen de la app, y por eso sé que va bajo. Pero la proyección era sobre ventas totales de chequeos, y esa data la tiene comercial. Ellos no separan bien por canal, o no nos la pasan separada, no sé cuál de las dos.

*Se encoge de hombros.*

Tampoco tenemos una instancia para eso. En la revisión trimestral de OKR miramos adopción de canales digitales, descargas, usuarios activos, pero no volvemos a abrir el caso de cada cosa que lanzamos. Y además no sé quién querría ir donde comercial a decirle que su proyección no se cumplió. Yo no, la verdad. El costo es que seguimos aprobando cosas con el mismo tipo de proyección, porque nunca se revisa si la anterior se cumplió.

**Entrevistador:** ¿En qué otros prestadores de salud has trabajado?

**Rodrigo:** En ninguno, este es el primero. Antes estuve en un banco harto tiempo y después un par de años en retail. Llegué a salud por el lado digital, no por el lado de salud.

Lo que sí tengo es contacto con gente de otras clínicas, porque nos topamos en eventos o en algún grupo de WhatsApp de gente de producto. Por lo que conversamos, están más o menos igual que nosotros, pero te lo digo de café, no porque lo haya visto adentro.

**Entrevistador:** ¿Qué no te pregunté que debería haber preguntado sobre esto?

*Mira la hora.*

**Rodrigo:** Buena pregunta… Me preguntaste harto por las decisiones, pero no por las herramientas que ya probamos. Yo ya recomendé dos cosas que prometían justamente esto: una de encuestas y otra de analítica que te muestra dónde abandona la gente en la app. Las dos las aprobó mi gerente porque yo se las recomendé, y las dos terminaron siendo dashboards que nadie abre. Te muestran que la gente se va en tal pantalla, pero no por qué, ni qué dice, ni cuánto cuesta. Si mañana llego con una tercera, mi gerente me va a preguntar en qué se diferencia de las otras dos, y más me vale tener una buena respuesta, porque ya gasté bastante crédito.

Lo otro es el tema de los datos. Todo lo que me faltó en las historias que te conté, las llamadas, el costo, las ventas por canal, está en otras gerencias. Pedirlo no es una consulta, es una negociación. Y si además dices "IA" y "datos de pacientes" en la misma frase, te vas a legal y a seguridad de la información por meses, y con la Ley 21.719 encima peor todavía. El último intento que hicimos de cruzar encuestas con datos de pacientes se murió ahí.

Y quizás… no me preguntaste qué me pasa a mí cuando defiendo un ítem de experiencia. Los compromisos de la isapre y de los chequeos los firmé yo. Entonces, cuando un PO me trae algo de experiencia, no es "el negocio contra el paciente". Soy yo contra mí mismo, contra lo que ya prometí arriba.

*Sonríe, cansado.*

Me quedan como cinco minutos, ¿algo más?

**Entrevistador:** ¿Conoces a otro PO o PM — en este prestador o en otro — a quien le pase algo parecido, o muy distinto, con quien valga la pena hablar? ¿Y a alguien a quien sí le entren ítems de voz del paciente? ¿Me lo podrías presentar?

**Rodrigo:** Sí, claro. La primera es la Carolina, obvio. Ella vive esto desde el otro lado, es la que trae el ítem y se va con las manos vacías. Te va a contar cosas que a mí no me cuenta, seguramente. Te la presento, pero conversa con ella sola, sin mí, porque conmigo ahí va a ser más cuidadosa.

Uno muy distinto… hay un gallo en otra clínica, del grupo de WhatsApp que te comenté, que tiene experiencia del paciente dentro de su misma gerencia. Él dice que a él sí le entran cosas de experiencia, y no sé si es por eso o porque su gerente es más de la línea de experiencia. Valdría la pena preguntarle. Le puedo escribir, pero no te prometo nada: está en otra clínica y no sé si quiera contar cómo priorizan adentro.

*Mira el celular.*

Mándame un correo con dos líneas de qué estás haciendo y yo se los reenvío. Oye, me tengo que ir, me están llamando a la otra reunión. Fue buena la conversación, me hizo pensar en cosas que tenía medio escondidas.

---

**[Nota para el entrevistador]** Pedir referidos al final fue una buena práctica. Pero en una entrevista sintética esos contactos (Carolina, el PM de la otra clínica) no existen: sirven como hipótesis de a quién buscar en la vida real. En particular, un prestador donde experiencia del paciente depende de la misma gerencia que producto sería un caso de contraste útil.
