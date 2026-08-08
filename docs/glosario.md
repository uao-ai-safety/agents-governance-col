# Glosario de conceptos

## Índice

- [Gobernanza de IA](#gobernanza-de-ia)
- [Agente de IA](#agente-de-ia)
- [Nube pública](#nube-pública)
- [Diferencias: gobernanza de IA, IA segura y seguridad informática](#diferencias-gobernanza-de-ia-ia-segura-y-seguridad-informática)
- [Otros términos clave](#otros-términos-clave)
  - [Riesgo](#riesgo)
  - [Brecha](#brecha)
  - [Control](#control)
  - [Madurez](#madurez)
  - [Auditoría](#auditoría)
  - [Supervisión humana](#supervisión-humana)
  - [Rendición de cuentas (accountability)](#rendición-de-cuentas-accountability)

## Gobernanza de IA

La gobernanza de IA es el conjunto de políticas, roles, procesos y controles que una organización define para decidir cómo se diseña, adquiere, despliega y supervisa la inteligencia artificial dentro de ella. No se trata de una herramienta técnica puntual, sino de la estructura de decisión: quién autoriza el uso de un modelo, qué riesgos se evalúan antes de ponerlo en producción, cómo se documentan las decisiones y quién responde si algo falla.

**¿Por qué no es solo seguridad?** La seguridad informática busca proteger sistemas y datos de accesos o usos no autorizados (confidencialidad, integridad, disponibilidad). La gobernanza de IA es más amplia: además de la seguridad, cubre preguntas que la seguridad por sí sola no responde — ¿es ético este uso?, ¿el modelo es justo o discrimina?, ¿cumple con la normativa aplicable?, ¿alguien puede explicar por qué el sistema tomó una decisión?, ¿quién es responsable si el sistema se equivoca? Un sistema puede estar perfectamente asegurado (sin brechas técnicas) y aun así estar mal gobernado si nadie evaluó sus riesgos éticos, normativos u organizacionales antes de usarlo.

## Agente de IA

Un agente de IA es un sistema que, a partir de un objetivo, puede percibir su entorno, tomar decisiones y ejecutar acciones de forma autónoma o semi-autónoma, sin que un humano apruebe cada paso individual. A diferencia de un modelo que solo responde a una pregunta puntual (por ejemplo, un chatbot que contesta un mensaje), un agente puede encadenar varias acciones por sí mismo: consultar información, invocar herramientas o sistemas externos, y actuar sobre esos resultados para avanzar hacia su objetivo.

**¿Qué riesgos aparecen cuando una IA puede actuar como agente?** Al quitarle al humano la aprobación de cada paso, aumentan los riesgos de: acciones no deseadas o irreversibles ejecutadas sin supervisión directa; errores que se propagan porque el agente sigue actuando sobre resultados incorrectos de un paso previo; uso de credenciales o permisos más amplios de los necesarios para que el agente pueda "hacer su trabajo"; dificultad para explicar o auditar después por qué el agente tomó una secuencia de decisiones particular; y pérdida de control si el agente interactúa con sistemas externos que no estaban previstos.

## Nube pública

La nube pública es un modelo de cómputo en el que un proveedor externo (ej. AWS, Microsoft Azure, Google Cloud) ofrece infraestructura, plataformas o software como servicio, compartido entre múltiples clientes (arquitectura multi-tenant) y accesible por internet, en lugar de que la organización mantenga sus propios servidores físicos. La organización paga por lo que usa y no es dueña de la infraestructura, lo que trae ventajas de escalabilidad y costo, pero también implica ceder parte del control técnico y depender de los controles de seguridad y cumplimiento que ofrezca el proveedor.

## Diferencias: gobernanza de IA, IA segura y seguridad informática

| Concepto | Pregunta que responde | Alcance |
|---|---|---|
| **Seguridad informática** | ¿El sistema y los datos están protegidos de accesos o usos no autorizados? | Técnico: infraestructura, redes, datos, accesos |
| **IA segura (AI safety)** | ¿El modelo se comporta como se espera, sin causar daños no intencionados, incluso en casos límite? | Técnico/comportamental: robustez, alineación, comportamiento del modelo |
| **Gobernanza de IA** | ¿Quién decide, autoriza, supervisa y responde por el uso de la IA en la organización? | Organizacional: políticas, roles, cumplimiento normativo, ética, rendición de cuentas |

La gobernanza de IA no reemplaza a la seguridad informática ni a la IA segura — las necesita como insumo, pero añade la capa de decisión y responsabilidad organizacional que ninguna de las dos cubre por sí sola.

## Otros términos clave

### Riesgo

La posibilidad de que ocurra un evento que afecte negativamente los objetivos de la organización (ej. un modelo que discrimina, una filtración de datos), combinando probabilidad e impacto.

### Brecha

La diferencia entre el estado actual de la organización (lo que hace hoy) y el estado deseado o exigido (lo que debería hacer según el marco, la norma o el estándar de referencia).

### Control

Una medida (política, proceso, mecanismo técnico) que se implementa para reducir un riesgo o cerrar una brecha.

### Madurez

El nivel de desarrollo y consistencia con el que una organización aplica sus procesos de gobernanza — desde ausencia total de controles hasta procesos formalizados, medidos y mejorados continuamente.

### Auditoría

La revisión formal e independiente de si los controles declarados realmente se están aplicando y son efectivos.

### Supervisión humana

La capacidad de una persona de entender, intervenir, corregir o detener una decisión o acción de un sistema de IA.

### Rendición de cuentas (accountability)

La obligación de una persona o rol dentro de la organización de responder por las decisiones y los efectos de un sistema de IA, incluyendo poder explicar por qué se tomó una decisión.
