# Ley 1581 de 2012: protección de datos personales en Colombia y su impacto en la Inteligencia Artificial

> **Ficha rápida**<br>
> **Norma:** Ley Estatutaria 1581 del 17 de octubre de 2012<br>
> **Título oficial:** "Por la cual se dictan disposiciones generales para la protección de datos personales"<br>
> **Derecho que desarrolla:** Habeas Data (artículo 15 de la Constitución Política de 1991)<br>
> **Autoridad de control:** Superintendencia de Industria y Comercio (SIC) — Delegatura para la Protección de Datos Personales<br>
> **Reglamentación principal:** Decreto 1377 de 2013, compilado en el Decreto 1074 de 2015<br>
> **Instrumento clave para IA:** Circular Externa 002 del 21 de agosto de 2024 (SIC)<br>
> **Dimensión de IA responsable que toca:** Privacidad y gobernanza de datos (con efectos transversales sobre transparencia, equidad, seguridad y rendición de cuentas)

---

## 1. ¿De qué trata la ley? Explicación en lenguaje simple

Imagina que tus datos personales —tu cédula, tu correo, tu historial médico, tus huellas, tus fotos, tu ubicación— son **objetos que te pertenecen**, aunque estén guardados en el computador de otra persona.

La Ley 1581 de 2012 parte exactamente de esa idea. Su punto de partida no es "¿quién tiene el archivo?", sino **"¿de quién son los datos?"**. La respuesta es: son tuyos. Tú eres el **Titular**. Quien los guarda y los usa es apenas un **custodio** con obligaciones, no un dueño.

De ahí sale el nombre técnico del derecho: **Habeas Data**, que se traduce aproximadamente como *"que tengas tus datos"*. Es primo del más conocido *habeas corpus* ("que tengas tu cuerpo"): así como nadie puede detenerte arbitrariamente, nadie puede tener y usar información sobre ti arbitrariamente.

La ley desarrolla el artículo 15 de la Constitución de 1991, que reconoce a toda persona el derecho a **conocer, actualizar y rectificar** las informaciones recogidas sobre ella en bases de datos y archivos.

### Los tres personajes de la ley

Para entender cualquier caso, basta identificar quién es quién:

| Personaje | Quién es | Ejemplo cotidiano |
|---|---|---|
| **Titular** | La persona natural dueña de los datos | Tú, cuando te registras en una app |
| **Responsable del Tratamiento** | Quien decide **por qué y para qué** se usan los datos | La empresa dueña de la app |
| **Encargado del Tratamiento** | Quien procesa los datos **por cuenta del Responsable** | El proveedor de nube o de analítica que contrata la empresa |

Y la actividad regulada se llama **Tratamiento**: cualquier operación sobre datos personales —recolección, almacenamiento, uso, circulación o supresión—. Es una definición deliberadamente amplia: **casi todo lo que se puede hacer con un dato personal es "Tratamiento"**.

### Los 8 principios (artículo 4)

Son el corazón de la ley. Si un proyecto viola uno solo, ya es ilegal.

| Principio | Qué exige, en una frase |
|---|---|
| **Legalidad** | El tratamiento es una actividad reglada: se hace conforme a la ley, no según le parezca a cada quien. |
| **Finalidad** | Los datos se recogen para un propósito **legítimo, específico e informado al Titular**. No vale "por si acaso". |
| **Libertad** | Solo se tratan datos con el **consentimiento previo, expreso e informado** del Titular (salvo las excepciones legales). |
| **Veracidad o calidad** | La información debe ser veraz, completa, exacta, actualizada, comprobable y comprensible. **Se prohíben los datos parciales, incompletos, fraccionados o que induzcan a error.** |
| **Transparencia** | El Titular puede, en cualquier momento y sin restricciones, obtener información sobre sus propios datos. |
| **Acceso y circulación restringida** | Los datos no están disponibles en internet ni en otros medios de divulgación masiva, salvo que el acceso sea técnicamente controlable. |
| **Seguridad** | Se adoptan medidas técnicas, humanas y administrativas para evitar adulteración, pérdida, consulta, uso o acceso no autorizado. |
| **Confidencialidad** | Todos los que intervienen deben guardar reserva, incluso después de terminada su relación con el tratamiento. |

### Datos sensibles: la categoría de máximo riesgo (artículos 5 y 6)

La ley define como **sensibles** aquellos datos que afectan la intimidad del Titular **o cuyo uso indebido puede generar discriminación**:

- Origen racial o étnico
- Orientación política
- Convicciones religiosas o filosóficas
- Pertenencia a sindicatos, organizaciones sociales o de derechos humanos
- Datos relativos a la **salud**, a la **vida sexual** y **datos biométricos**

La regla general es la **prohibición** de tratarlos. Solo se permite en casos tasados (autorización **explícita**, interés vital del Titular, finalidad histórica/estadística/científica con medidas de anonimización, entre otros). Fíjate en el criterio: la ley protege estas categorías **precisamente porque son las que producen discriminación** — el mismo problema que la literatura de IA llama *fairness*.

El artículo 7 añade una protección reforzada para los datos de **niños, niñas y adolescentes**.

### Tus derechos como Titular (artículo 8)

1. Conocer, actualizar y rectificar tus datos.
2. Solicitar **prueba de la autorización** que otorgaste.
3. Ser informado sobre el uso que se le ha dado a tus datos.
4. Presentar **quejas ante la SIC** por infracciones.
5. **Revocar la autorización** y/o solicitar la **supresión** del dato.
6. Acceder **gratuitamente** a tus datos.

### Consecuencias de incumplir (artículo 23)

La SIC puede imponer:

- **Multas de hasta 2.000 SMLMV** (salarios mínimos legales mensuales vigentes) por infracción.
- **Suspensión** de las actividades relacionadas con el tratamiento, hasta por 6 meses.
- **Cierre temporal** de las operaciones.
- **Cierre inmediato y definitivo** de la operación que involucre tratamiento de **datos sensibles**.

> El valor en pesos de las multas cambia cada año con el SMLMV; conviene verificar el salario mínimo vigente del año en curso.

---

## 2. ¿Por qué importa para la Inteligencia Artificial?

Aquí está el punto central de todo este documento, y se resume en una frase:

> **Colombia no necesitó esperar una "ley de IA" para tener reglas vinculantes sobre IA.** La Ley 1581 ya aplica, porque casi toda IA relevante funciona con datos personales.

### 2.1 La ley es tecnológicamente neutra

La Ley 1581 nunca menciona la palabra "algoritmo", "modelo" o "inteligencia artificial". Y eso es una **fortaleza de diseño**, no un vacío: fue redactada de forma neutra, de modo que aplica a cualquier tratamiento de datos personales **sin importar el medio, manual o tecnológico**.

La Corte Constitucional lo confirmó expresamente en la **Sentencia T-323 de 2024** (caso sobre el uso de IA generativa en una decisión judicial):

> *"[L]as leyes estatutarias 1266 de 2008 y 1581 de 2012 fueron redactadas neutralmente, en el sentido que sus disposiciones aplican al Tratamiento de datos que se realice mediante cualquier herramienta manual o tecnológica. En este sentido, cualquier sistema de IA debe garantizar el cumplimiento de estas normatividades."*

Traducido: **entrenar, probar, desplegar o monitorear un sistema de IA con datos personales es "Tratamiento"** y queda sujeto a los 8 principios, a la autorización del Titular y a la vigilancia de la SIC.

### 2.2 La Circular Externa 002 de 2024: el puente explícito entre la ley y la IA

El 21 de agosto de 2024, la SIC expidió la **Circular Externa 002 de 2024**, titulada *"Lineamientos sobre el Tratamiento de Datos personales en Sistemas de Inteligencia Artificial"*. Es el documento **más importante** para quien construye IA en Colombia, y es de obligatorio cumplimiento para los vigilados por la SIC.

Sus instrucciones concretas:

**I. Test de ponderación en cuatro criterios.** Antes de tratar datos personales en IA hay que justificar:

| Criterio | Pregunta que debes poder responder |
|---|---|
| **Idoneidad** | ¿El tratamiento realmente sirve para alcanzar el objetivo propuesto? |
| **Necesidad** | ¿Existe otra medida **igual de eficaz pero menos invasiva**? Si existe, debes usar esa. |
| **Razonabilidad** | ¿La finalidad es constitucionalmente legítima? |
| **Proporcionalidad en sentido estricto** | ¿Las ventajas del sistema superan el daño al derecho al Habeas Data? |

**II. Principio de precaución.** Si hay **incertidumbre** sobre los daños potenciales y el riesgo es de un daño grave e irreversible, se debe **abstenerse de tratar los datos** o adoptar medidas precautorias. Nota lo fuerte que es esto: la carga de la duda juega **contra** el desarrollador, no a su favor.

**III. Gestión de riesgos.** Deben implementarse sistemas para **identificar, medir, controlar y monitorear** los riesgos. La circular menciona expresamente entre las contingencias a considerar: *"sesgos humanos, fallas técnicas, vulnerabilidades de seguridad, fallas en la implementación"* y riesgos de diseño.

**IV. Estudio de impacto de privacidad (PIA), previo y documentado**, cuando sea probable que el producto entrañe **alto riesgo** para los Titulares. Contenido mínimo:
- a. Descripción detallada de las operaciones de tratamiento.
- b. Evaluación de riesgos específicos para derechos y libertades, con identificación y clasificación.
- c. Medidas para evitar la materialización de los riesgos: seguridad, diseño de software, tecnologías y mecanismos de protección.

**V–VI. Calidad de datos y privacidad desde el diseño.** Los datos usados en IA deben ser veraces, completos, exactos, actualizados, comprobables y comprensibles. La circular menciona explícitamente la **privacidad diferencial** como técnica matemática válida para cumplir *privacy by design and by default*, e incluye referencias académicas (Dwork & Roth, 2014).

**VII. Derecho de información.** El Titular puede obtener, **en cualquier momento y sin restricciones**, información sobre el tratamiento de sus datos dentro del sistema de IA.

**VIII. Seguridad auditable.** Medidas tecnológicas, humanas, administrativas, físicas y contractuales para evitar acceso indebido, manipulación, destrucción, uso no autorizado y circulación a terceros no autorizados. Y algo crucial: **las medidas de seguridad deben ser auditables por las autoridades**.

**IX. "Público" no significa "libre".** Esta instrucción es la más relevante para el *scraping* de datos de entrenamiento:

> La información personal *"accesible al público"* **no es**, por sí sola, información *"de naturaleza pública"*. Que un dato esté disponible en internet **no significa** que cualquiera pueda tratarlo sin autorización previa, expresa e informada del Titular.

La SIC cita como precedente su **Resolución 71406 del 15 de noviembre de 2023**, mediante la cual impartió órdenes administrativas a **LinkedIn**.

**X. Estrategias demostrables** para garantizar los derechos de los Titulares.

### 2.3 Responsabilidad demostrada (*accountability*)

El artículo 2.2.2.25.6.1 del Decreto 1074 de 2015 establece que los Responsables deben ser capaces de **demostrar**, a petición de la SIC, que implementaron medidas apropiadas y efectivas de cumplimiento.

Esto invierte la lógica intuitiva: **no basta con cumplir; hay que poder probar que se cumplió**. Para un equipo de IA, esto significa que la documentación (*model cards*, *datasheets for datasets*, registros de linaje de datos, actas de comité de ética, PIAs) deja de ser una buena práctica opcional y se convierte en **material probatorio**.

---

## 3. ¿Qué dimensión de la IA responsable toca?

La respuesta corta es **privacidad y gobernanza de datos**. Pero la respuesta útil es que, en el caso colombiano, esa dimensión funciona como **puerta de entrada a casi todas las demás**, porque la SIC —usando la Ley 1581— es hoy el regulador con dientes más afilados sobre IA en el país.

| Dimensión de IA responsable | ¿La toca? | Vía normativa concreta |
|---|---|---|
| **Privacidad y gobernanza de datos** | ★★★ **Dimensión núcleo** | Toda la ley: principios de finalidad, libertad y acceso restringido; autorización previa; Registro Nacional de Bases de Datos (art. 20) |
| **Equidad y no discriminación** | ★★☆ **Fuerte, pero indirecta** | Art. 5 (datos sensibles definidos por su potencial discriminatorio); principio de veracidad/calidad (art. 4 lit. d) que prohíbe datos parciales o que induzcan a error — base para atacar sesgo por datos defectuosos; criterio de **razonabilidad** de la Circular 002; mención expresa a *"sesgos humanos"* en la gestión de riesgos |
| **Transparencia y explicabilidad** | ★★☆ **Parcial** | Principio de transparencia (art. 4 lit. e), deber de informar la finalidad (art. 12), derecho a saber el uso dado a los datos (art. 8), instrucción VII de la Circular 002. **Ojo:** obliga a explicar *qué datos se usan y para qué*, **no** necesariamente a explicar la lógica interna del modelo |
| **Seguridad y robustez** | ★★☆ **Fuerte en seguridad de la información** | Principio de seguridad (art. 4 lit. g), instrucción VIII de la Circular 002, exigencia de auditabilidad |
| **Rendición de cuentas** | ★★★ **Muy fuerte** | Responsabilidad demostrada (Decreto 1074, art. 2.2.2.25.6.1); PIA documentado; régimen sancionatorio del art. 23 con autoridad activa |
| **Supervisión humana / agencia** | ★☆☆ **Débil — brecha identificada** | Existen derechos de revocación, supresión, consulta y reclamo (arts. 8, 14, 15), pero **la Ley 1581 no consagra un derecho explícito a no ser objeto de decisiones exclusivamente automatizadas** |

### La brecha más importante: decisiones automatizadas

Vale la pena subrayarla porque suele ser la conclusión más valiosa de este análisis.

El Reglamento General de Protección de Datos europeo (**GDPR, artículo 22**) reconoce un derecho a **no ser objeto de decisiones basadas únicamente en tratamiento automatizado** que produzcan efectos jurídicos o significativos, junto con un derecho a obtener intervención humana.

**La Ley 1581 de 2012 no tiene un equivalente directo.** Fue escrita cuando el aprendizaje automático a escala no era un problema regulatorio. En Colombia, hoy, ese vacío se cubre por vías indirectas:

- La ponderación de idoneidad/necesidad/razonabilidad/proporcionalidad de la Circular 002.
- El principio de precaución de la misma circular.
- La acción de tutela y la jurisprudencia constitucional (T-323 de 2024).
- El principio de veracidad, si la decisión automatizada se basó en datos incompletos o erróneos.

Es precisamente uno de los puntos que motiva el **proyecto de ley de modernización del régimen de protección de datos** que la SIC ha venido impulsando. *(Conviene verificar su estado de trámite al momento de leer este documento.)*

---

## 4. Ejemplos de aplicación

### Ejemplo 1 — Scoring crediticio con machine learning (fintech)

**Escenario:** Una fintech entrena un modelo para aprobar microcréditos usando historial transaccional, ubicación GPS y datos de comportamiento en la app.

**Qué exige la ley:**
- **Autorización previa, expresa e informada** describiendo la finalidad "evaluación de riesgo crediticio" — no basta un "acepto términos" genérico (principios de libertad y finalidad).
- Si el modelo usa ubicación para inferir el barrio y eso correlaciona con **origen étnico o socioeconómico**, se está creando un *proxy* de dato sensible; hay que aplicar el test de proporcionalidad.
- **PIA obligatorio**: la decisión afecta el acceso al crédito, es alto riesgo.
- Concurre además la **Ley 1266 de 2008** (habeas data financiero).
- Si un usuario reclama que le negaron el crédito por un dato erróneo, aplican los artículos 8 y 15 (rectificación y reclamo).

**Riesgo si se ignora:** multa de la SIC, orden de suspender el modelo, y obligación de rehacer el proceso de autorización de toda la base.

---

### Ejemplo 2 — Filtrado automatizado de hojas de vida

**Escenario:** Una empresa usa IA para preseleccionar candidatos entre 5.000 hojas de vida.

**Qué exige la ley:**
- Las hojas de vida contienen datos sensibles latentes (foto → origen racial; fecha de nacimiento → edad; afiliaciones → sindicato o religión). El art. 6 los protege.
- Debe informarse al candidato la **finalidad** del tratamiento y que hay un componente automatizado (principio de transparencia).
- El principio de **veracidad** obliga a que los datos usados sean exactos y actualizados.
- La SIC ha señalado expresamente que **automatizar contratación es tratamiento de datos personales** sujeto al régimen completo de habeas data.
- **Necesidad:** ¿es indispensable la foto para preseleccionar? Si no lo es, incluirla falla el test.

---

### Ejemplo 3 — Web scraping para entrenar un modelo

**Escenario:** Un equipo raspa perfiles públicos de redes sociales colombianas para entrenar un modelo de lenguaje.

**Qué exige la ley:** Este es el caso que la **instrucción IX de la Circular 002** ataca de frente. Que un perfil sea visible **no** lo convierte en dato público. Sin autorización previa, expresa e informada del Titular, quien recolecta datos privados, semiprivados o sensibles en internet **no está legitimado** para apropiarse de ellos ni tratarlos para la finalidad que considere apropiada.

**Precedente real:** Resolución SIC 71406 del 15 de noviembre de 2023, con órdenes administrativas a LinkedIn.

**Conclusión práctica:** "lo saqué de internet" **no es** una base de legitimación en Colombia.

---

### Ejemplo 4 — Reconocimiento facial en espacios comerciales

**Escenario:** Un centro comercial instala cámaras con reconocimiento facial para medir aforo y detectar personas señaladas por hurto.

**Qué exige la ley:**
- Los datos **biométricos son datos sensibles** (art. 5). Regla general: **prohibido** tratarlos.
- Se requiere **autorización explícita** — técnicamente muy difícil en un espacio abierto, donde nadie consintió antes de entrar.
- **Necesidad:** si el objetivo es contar personas, existen alternativas menos invasivas (sensores anónimos, conteo sin identificación). Al haber una medida igual de eficaz y menos invasiva, el reconocimiento facial **falla el test**.
- Sanción potencial: **cierre inmediato y definitivo** de la operación, por involucrar datos sensibles (art. 23).

---

### Ejemplo 5 — Usar un LLM comercial con datos de clientes

**Escenario:** Un área de servicio al cliente pega conversaciones reales con clientes en una herramienta de IA generativa de un proveedor extranjero para generar resúmenes.

**Qué exige la ley:**
- El proveedor actúa como **Encargado del Tratamiento**: se requiere un contrato de transmisión de datos con obligaciones de seguridad y confidencialidad.
- Aplica el **artículo 26**: prohibición de transferir datos a países que no ofrezcan niveles adecuados de protección, salvo autorización del Titular u otras excepciones legales.
- Si el proveedor usa esos datos para **reentrenar** sus modelos, hay un cambio de finalidad no autorizado (violación del principio de finalidad).
- El **principio de confidencialidad** sigue vinculando al empleado que pegó la conversación.

**Este es el error de cumplimiento más común y menos percibido en las organizaciones colombianas hoy.**

---

### Ejemplo 6 — Contact center con voz sintética

**Escenario:** Una empresa usa IA para generar llamadas automáticas con voz sintética a clientes.

**Qué exige la ley:** La SIC atendió exactamente esta consulta en el **Concepto 25-167843 (27 de junio de 2025)**, señalando que deben respetarse transparencia en el uso de IA, privacidad y seguridad de los datos, responsabilidad en la implementación y protección especial de niños, niñas y adolescentes; además del cumplimiento de la Ley 1581 de 2012, del CONPES 4144 de 2025 y de la Circular Externa 002 de 2024.

---

### Ejemplo 7 — Analítica de aprendizaje en una universidad

**Escenario:** Una institución educativa usa IA para predecir qué estudiantes están en riesgo de deserción, cruzando notas, asistencia, uso del aula virtual y datos socioeconómicos.

**Qué exige la ley:**
- Datos socioeconómicos y de salud mental son **sensibles o cercanos a serlo**.
- Estudiantes menores de edad: protección reforzada del **artículo 7**.
- **Finalidad:** debe estar claramente delimitada a apoyo estudiantil. Si el modelo termina usándose para decisiones de admisión o sanción, hay desviación de finalidad.
- **PIA obligatorio** por el alto riesgo de estigmatización.
- **Transparencia:** el estudiante tiene derecho a saber que existe un puntaje de riesgo sobre él y a acceder a él gratuitamente.

---

## 5. Lista de verificación práctica

Antes de poner un sistema de IA en producción en Colombia:

- [ ] ¿Identifiqué si el sistema trata datos personales? (Casi siempre la respuesta es sí.)
- [ ] ¿Tengo **autorización previa, expresa e informada** con la finalidad de IA descrita explícitamente?
- [ ] ¿Hay **datos sensibles** o *proxies* de datos sensibles en el conjunto de entrenamiento?
- [ ] ¿Documenté el test de **idoneidad, necesidad, razonabilidad y proporcionalidad**?
- [ ] ¿Hice y **documenté** un estudio de impacto de privacidad (PIA)?
- [ ] ¿Puedo **demostrar** el cumplimiento ante la SIC si me lo piden mañana?
- [ ] ¿Mis datos de entrenamiento son veraces, completos, exactos y actualizados?
- [ ] Si usé datos de internet, ¿tengo autorización de los Titulares? (Ser "público" no basta.)
- [ ] ¿Puede un Titular consultar, rectificar, revocar y solicitar supresión — y eso se refleja en el modelo?
- [ ] ¿Registré la base de datos en el **RNBD** cuando corresponde?
- [ ] ¿Mis medidas de seguridad son **auditables** por la autoridad?
- [ ] ¿Hay transferencia internacional de datos? ¿Está cubierta?

---

## 6. Contexto normativo más amplio

| Norma | Contenido |
|---|---|
| **Constitución Política, art. 15** | Derecho fundamental al habeas data, intimidad y buen nombre |
| **Ley 1266 de 2008** | Habeas data **financiero, crediticio y comercial** (régimen especial y anterior) |
| **Ley 1581 de 2012** | Régimen **general** de protección de datos personales |
| **Decreto 1377 de 2013** | Reglamenta parcialmente la Ley 1581 (autorización, políticas de tratamiento, transferencias) |
| **Decreto 1074 de 2015** | Decreto Único Reglamentario del Sector Comercio, Industria y Turismo; compila lo anterior. Su art. 2.2.2.25.6.1 consagra la **responsabilidad demostrada** |
| **Decreto 4886 de 2011** (mod. Decreto 092 de 2022) | Estructura y funciones de la SIC |
| **CONPES 3975** | Política Nacional para la Transformación Digital e Inteligencia Artificial |
| **CONPES 4144 de 2025** | Política nacional de inteligencia artificial |
| **Circular Externa SIC 002 de 2024** | Lineamientos sobre tratamiento de datos personales en sistemas de IA |
| **Sentencia C-748 de 2011** | Revisión de constitucionalidad del proyecto que se convirtió en la Ley 1581 |
| **Sentencia T-323 de 2024** | Reafirma que cualquier sistema de IA debe cumplir el régimen de protección de datos |

---

## 7. Conclusión

Tres ideas para llevarse:

1. **Colombia ya regula la IA, aunque no tenga una "ley de IA".** La Ley 1581 de 2012 es tecnológicamente neutra y por eso alcanza a los sistemas de IA sin necesidad de reforma. La Circular 002 de 2024 lo hizo explícito y operativo.

2. **La dimensión tocada es privacidad y gobernanza de datos, pero opera como palanca sobre las demás.** A través de los datos sensibles llega a la equidad; a través del principio de seguridad llega a la robustez; y a través de la responsabilidad demostrada llega a la rendición de cuentas. En la práctica, la SIC es hoy el regulador de IA más operativo del país.

3. **La brecha real está en la supervisión humana.** No existe un derecho explícito a no ser objeto de decisiones exclusivamente automatizadas, equivalente al artículo 22 del GDPR. Es la principal razón por la que se discute una modernización del régimen.

---

## Referencias

### Fuentes normativas primarias

1. **Ley Estatutaria 1581 de 2012** — "Por la cual se dictan disposiciones generales para la protección de datos personales".
   - SUIN-Juriscol (Ministerio de Justicia): https://www.suin-juriscol.gov.co/viewDocument.asp?ruta=Leyes/1684507
   - Gestor Normativo, Función Pública: https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=49981

2. **Superintendencia de Industria y Comercio. Circular Externa No. 002 del 21 de agosto de 2024** — *"Lineamientos sobre el Tratamiento de Datos personales en Sistemas de Inteligencia Artificial"*. Firmada por Cielo Elainne Rusinque Urrego, Superintendente de Industria y Comercio.
   - PDF oficial: https://sedeelectronica.sic.gov.co/sites/default/files/normativa/Circular%20Externa%20No.%20002%20del%2021%20de%20agosto%20de%202024.pdf
   - Ficha en el portal de normativa de la SIC: https://sedeelectronica.sic.gov.co/transparencia/normativa/circular-externa-2-de-2024-de-la-superintendencia-de-industria-y-comercio-lineamientos-sobre-el-tratamiento-de-datos

3. **SIC. Concepto 25-167843** (publicado el 27 de junio de 2025) — *"El uso de la inteligencia artificial en actividades comerciales debe respetar el habeas data"*.
   - https://sedeelectronica.sic.gov.co/publicaciones/boletin-juridico/concepto/el-uso-de-la-inteligencia-artificial-en-actividades-comerciales-debe-respetar-el-habeas-data

4. **SIC. "ABC del Proyecto de Ley de Protección de Datos Personales en Colombia"** — sobre la propuesta de modernización del régimen.
   - https://sedeelectronica.sic.gov.co/noticias/abc-del-proyecto-de-ley-de-proteccion-de-datos-personales-en-colombia

5. **SIC. Resolución No. 71406 del 15 de noviembre de 2023** — órdenes administrativas a LinkedIn. (Citada en la nota al pie 13 de la Circular Externa 002 de 2024.)

### Jurisprudencia

6. **Corte Constitucional de Colombia. Sentencia C-748 de 2011** — control de constitucionalidad del proyecto de ley estatutaria que se convirtió en la Ley 1581 de 2012.
   - Relatoría: https://www.corteconstitucional.gov.co/relatoria/2011/C-748-11.htm

7. **Corte Constitucional de Colombia. Sentencia C-1011 de 2008** — control de constitucionalidad del proyecto correspondiente a la Ley 1266 de 2008; define la naturaleza de las facultades de vigilancia de la SIC.
   - Relatoría: https://www.corteconstitucional.gov.co/relatoria/2008/C-1011-08.htm

8. **Corte Constitucional de Colombia. Sentencia T-323 de 2024** — neutralidad tecnológica del régimen de datos personales y su aplicación a sistemas de IA.
   - Relatoría: https://www.corteconstitucional.gov.co/relatoria/2024/T-323-24.htm

### Documentos de política pública

9. **DNP. Documento CONPES 3975** — *Política Nacional para la Transformación Digital e Inteligencia Artificial*. (Citado en la Circular Externa 002 de 2024 como fuente de la definición oficial de IA en Colombia.) Disponible en el portal del Departamento Nacional de Planeación: https://www.dnp.gov.co/

10. **DNP. Documento CONPES 4144 de 2025** — política nacional de inteligencia artificial. (Citado en el Concepto SIC 25-167843.)

### Fuentes técnicas citadas por la propia SIC

11. **OCDE (2024).** *Explanatory Memorandum on the Updated OECD Definition of an AI System.* — definición de "sistema de IA" adoptada por la Circular 002 de 2024.

12. **Dwork, C. & Roth, A. (2014).** *The Algorithmic Foundations of Differential Privacy.* Foundations and Trends in Theoretical Computer Science.
    - https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf

13. **Sierra Cadena, G. (2024).** *Implementación de la Inteligencia Artificial en las Altas Cortes de Colombia: los casos de la Corte Constitucional y el Consejo de Estado.* Revista Eurolatinoamericana de Derecho Administrativo, vol. 11, n. 1, e253. DOI: 10.14409/redoeda.v11i1.13824

---

### Nota metodológica

El contenido de la **Circular Externa 002 de 2024** en este documento se extrajo directamente del **PDF oficial publicado por la SIC**, incluyendo sus instrucciones I a X y sus notas al pie; las citas textuales provienen de esa fuente. El **Concepto SIC 25-167843** se consultó directamente en el portal de la Superintendencia.

Los portales SUIN-Juriscol y Función Pública fueron identificados como las fuentes oficiales del texto de la ley, pero no pudieron descargarse en esta sesión por problemas de certificado TLS de esos servidores; los enlaces se incluyen para consulta directa. Las sentencias de la Corte Constitucional se citan a partir de las **transcripciones textuales contenidas en la propia Circular 002 de 2024** (fuente oficial de la SIC); los enlaces a la relatoría siguen el formato estándar del portal de la Corte y conviene verificarlos al consultarlos.

El estado de trámite del proyecto de ley de modernización del régimen de datos personales **debe verificarse** al momento de leer este documento, ya que puede haber cambiado.

---

*Documento elaborado el 3 de agosto de 2026.*
