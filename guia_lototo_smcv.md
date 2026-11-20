# Guía LOTOTO – SMCV (curso TECSUP, estándar SSOst0036 v.01)

**Fuente principal:** *Estándar de Bloqueo (LOTOTO)*, código SSOst0036, versión 01, elaborado nov-2019, aprobado 19/12/2019 (reemplaza al SGIpr0015 Procedimiento General de Bloqueo v05). Referencias "p." = página del PDF (el PDF trae 15 págs. + 2 págs. de Hoja de Resumen, Anexo 04).
**Complemento:** diapositivas del curso (fotos del usuario): "Plan de bloqueo", "Puntos de bloqueo", "Tarjeta: Bloqueo personal".
Pie del documento: *"El usuario es responsable de verificar, previo a su uso, la vigencia del presente documento en el Servidor de SMCV. Las versiones impresas son copias 'No Controladas'."* No se halló v.02/v.03 pública; verifica vigencia en el servidor de SMCV.

Las citas entre comillas son textuales del estándar. Lo que va fuera de comillas es resumen mío.

---

## 1. Objetivo y alcance (p. 2)

> **Objetivo:** "Bloquear las energías peligrosas para la ejecución segura de actividades donde la energización o la liberación de energía sin control puedan causar un incidente."

> **Alcance:** "…cualquier forma de energía que incluye, pero no se limita a: mecánica, neumática, hidráulica, química, eléctrica, térmica, nuclear, electromagnética, cinética, potencial, gravitacional, atmosférica residual o almacenada, o una combinación de éstas."
> "Este estándar es de cumplimiento obligatorio para todo el personal propio y contratistas."
> **No aplica** al "trabajo en herramientas y equipos portátiles eléctricas con cable y enchufe para las cuales la exposición o peligros de energización o partida inesperada del equipo está controlada por la desconexión del equipo de la fuente de energía y mantener el enchufe bajo el control de la persona que realiza el trabajo."

**Referencias:** Política FCX-04 Bloqueo/Tarjeteo/Prueba; DS 024-2016-EM y DS 023-2017-EM; RM-111-2013-EM; NFPA 70E:2018; OSHA 29 CFR 1910.147; Política FCX-HS03.

---

## 2. Definiciones textuales (pp. 2–3)

| Término | Definición textual |
|---|---|
| **CBE** | "Coordinador de Bloqueo de Energía, aplica en cambio de turno y en bloqueo grupal." |
| **LOTOTO** | "Método de bloqueo de energía aprobado para aislar y controlar las fuentes de energía peligrosa (Lock out, Tag out, Try out)." |
| **Bloqueo simple** | "Se ejecuta colocando la tarjeta y candado personal en un dispositivo de bloqueo que está instalado directamente en un dispositivo de aislamiento." |
| **Bloqueo grupal** | "Se ejecuta colocando la tarjeta y candado personal en una caja de bloqueo grupal. En bloqueo grupal se requiere CBE. Se aplica por decisión del supervisor quien usa como criterio: ✓ Cantidad de puntos de bloqueo y energías a bloquear. ✓ Cantidad de personas autorizadas involucradas. ✓ El periodo de aislamiento de energía se extiende. ✓ Cuando personal autorizado no pueda acceder a colocar su candado y tarjeta en el dispositivo de aislamiento. **No se permite anidar cajas de bloqueo grupal.**" |
| **Dispositivo de aislamiento de energía** | "Dispositivo mecánico que interrumpe el flujo de energía, por ejemplo: seccionadores, interruptores, válvulas o cualquier dispositivo adecuado para interrumpir el flujo de la energía. **No son dispositivos de aislamiento los dispositivos de control como: botoneras de parada de emergencia, selectores, sistemas de supervisión (PCs, DCS, PLC) y otros.** En casos donde los dispositivos de aislamiento de energía no están disponibles, se debe usar otro control efectivo (guardas, puertas, tapas, etc) al cual se le pueda aplicar efectivamente el LOTOTO." |
| **Dispositivo de bloqueo** | "Dispositivo mecánico que es usado para impedir la operación del Dispositivo de Aislamiento de Energía (pinza, cadena, u otros). Este dispositivo permite instalar candados de bloqueo en él." |
| **Puntos de bloqueo** | "Lista de dispositivos de aislamiento necesarios para realizar una actividad específica, que permiten aislar las fuentes de energía peligrosa." (Diapositiva del curso: "Es una LISTA DE DISPOSITIVOS DE AISLAMIENTO necesarios para realizar una actividad específica, que permiten aislar las fuentes de energía peligrosa.") |
| **Tarjeta fuera de servicio** | "Se usa para identificar equipos que se encuentran inoperativos, la forma y contenido se encuentra en el anexo 03 del presente estándar. Para su aplicación usar un candado distinto (etiquetado para ese fin) al candado de bloqueo, la llave queda en control del supervisor. La tarjeta fuera de servicio no debe ser usada como parte del Proceso de Lototo, debe indicar fecha de expiración (máximo 6 meses)." |

### Plan de bloqueo – aclaración (diapositiva n.º 8 del curso, textual)
> "El 'Plan de bloqueo' *no elimina* la identificación de fuentes de energía que se debe realizar en campo (IPERC Continuo, Formato de CBE)."

### Plan de bloqueo (diapositiva del curso)
> "Documento que detalla: *tareas a ejecutar, asignación de CBE* y la *lista de referencia de los puntos de bloqueo para cada tarea*."
> ¿Quién lo elabora? "Elaborado con anterioridad por el *Supervisor del área y CBE asignados* para *detenciones de planta planifica[das]* (obligatorio) y para *actividades complejas* (cuan[do el] supervisor lo considere)." *(Palabras entre [ ] tapadas en la foto.)*

### Roles (pp. 3–5)

**Persona calificada (6.3.3):** "Persona que puede o no estar trabajando en el equipo bloqueado, pero que tiene las calificaciones para realizar el aislamiento de energía para el sistema específico que se está desenergizando." Debe seguir procedimientos seguros de desenergización, aislamiento y liberación de energía; es "responsable de verificar la efectividad del aislamiento de energía y la realización de pruebas de arranque"; apoya al CBE. "En caso de personal de EE.CC debe existir una lista de personal calificado con la validación del Gerente General del Área."

**Personal Calificado (diapositiva n.º 18 del curso, textual):**
> "Persona capacitada que conoce los sistemas/equipos donde se realizará el bloqueo, es la persona que realiza el aislamiento y disipación de energía (En caso aplique)."
> ✓ "Tener vigente el curso de Lototo."
> ✓ "Debe seguir procedimientos seguros para el aislamiento y la liberación de energía (Drenaje)."
> ✓ "Responsable de verificar la efectividad del aislamiento de energía."

**Persona autorizada / Personal autorizado (6.3.4):** "Persona que bloquea y etiqueta dispositivos de aislamiento para realizar servicio o mantenimiento." Realiza trabajos en el equipo bloqueado o en su zona de influencia ("aquella en la que hay exposición a riesgos asociados al funcionamiento de un equipo"); "debe mantener el control de la llave de su candado"; es "responsable de devolver el equipo a condiciones de servicio antes de retirar cualquier dispositivo de aislamiento de energía o candado"; apoya al CBE; al culminar retira su candado y tarjeta y, en bloqueo grupal, firma la lista del Formato de bloqueo de energía. "Personal autorizado puede realizar un bloqueo sin que sea necesaria la participación de un CBE cuando exista un solo punto de bloqueo." Toda persona autorizada "se reserva el derecho de verificar el aislamiento despejando el área e intentado encender el equipo."

**Coordinador de Bloqueo de Energía – CBE (diapositiva del curso, textual):**
> "Es quien *lidera* el proceso de bloqueo grupal."
> **Requisitos:** "• Estar acreditado en LOTOTO y CBE. • 1 año como mínimo de experiencia [...] área de trabajo."
> *(Una o dos palabras entre "experiencia" y "área de trabajo" quedaron tapadas por una cabeza en la foto. El estándar, p. 3, dice: "antigüedad mínima un año de experiencia y conocimiento del área".)*

**Líder de Personal Autorizado (diapositiva del curso, textual):**
> "*Personal Autorizado* acreditado en Lototo, *designado por el supervisor* del equipo de trabajo, quien debe *realizar la prueba de arranque con el CBE* y *firmar el formato de CBE* en señal de conformidad."
> **¡IMPORTANTE!** "Puede ser personal de SMCV o personal de empresa contratista."

*(La diapositiva "Líder de Personal Autorizado" es la n.º 15 del PPT del curso.)*

**Notas del instructor en pantalla (hoja de Excel proyectada, transcripción literal):**
- "supervisor determina tipo de bloqueo: Bloqueo simple o bloqueo grupa[l]"
- Encabezados de columnas: "LPA", "SMCV", "CBE" (LPA = Líder de Personal Autorizado, según la diapositiva 15; la hoja no lo desarrolla).
- "P. autorizado trabajo, candado y tarjeta personal" (en la fila aparece "LPA" bajo la columna CBE; la foto no permite saber con certeza cómo se asignan las filas a las columnas).
- "CBE responsable, tarjeta CBE, Formato CBE"
- "P. autorizado designado por supervisor"
- "P. afectado opera, a cargo del equipo"
- "P. calificado aisla, repone, disipa"

**Personal Afectado (diapositiva del curso, textual):**
> "Es la persona que *opera o tiene a su cargo el equipo* en el que se va a ejecutar un trabajo."
> ✓ "Autoriza la detención y aislamiento del equipo o sistema que se desea intervenir."
> ✓ "Detiene los equipos a intervenir."
> ✓ "Realiza la prueba de arranque del equipo bajo su responsabilidad solicitada por el CBE o Personal Autorizado."

**Persona afectada (6.3.5):** "Persona que opera o usa el equipo que va a recibir mantenimiento. No realiza trabajos en el equipo que está bloqueado. Incluye personal que está presente en el área de trabajo."

**Superintendente del área (p. 3):** asegura la correcta aplicación; "tener y aprobar una lista de su área de trabajo designando a los CBE y Personal Calificado tomando en cuenta antigüedad mínima un año de experiencia y conocimiento del área."
**Supervisor (p. 3):** designa al CBE de la lista (o, si el bloqueo es simple, al personal autorizado que lidera el bloqueo) y "definir la aplicación y dispositivos de bloqueo simple o grupal."

**Supervisor (diapositiva n.º 19 del curso, textual):**
> ✓ "Cuando se requiera el *apoyo de un CBE de otra área*, el SUPERVISOR debe encargarse de realizar una capacitación presencial previa en los puntos de bloqueo de el (los) equipo(s), sistema(s) para el trabajo específico. El tiempo de capacitación será *como mínimo de 5 horas*, este tiempo puede ser mayor de acuerdo con la complejidad del bloqueo u otras consideraciones que tenga en cuenta el supervisor. Se deberá tener un registro de la capacitación brindada."

**Funciones del CBE (6.3.2 – p. 4):** asignado por el supervisor con "plena responsabilidad por el proceso de bloqueo"; capacitado y competente; lidera la identificación de fuentes de energía y de puntos de bloqueo (PETS, ATS, IPERC continuo, planos unifilares); define si se requiere drenaje; define necesidad de personas calificadas; "junto con la persona calificada, aísla y bloquea todas las fuentes de energía peligrosas utilizando los candados y tarjetas de CBE"; mantiene lista de puntos de bloqueo y responsables; "Las llaves de los candados usados por el CBE para aislar las fuentes de energía se deben colocar dentro de una caja grupal la cual será cerrada con un candado y tarjeta de CBE. **El CBE coloca el primer bloqueo y retira el último bloqueo de la caja de bloqueo grupal.**" "**El bloqueo de CBE no es un bloqueo personal.** El CBE debe aplicar su bloqueo y tarjeta personal al dispositivo de bloqueo de grupo si está realizando trabajos en el proceso/equipo." "Para trabajos complejos pueden ser necesarios múltiples CBE." Gestiona cambios de turno y la puesta en funcionamiento.

---

## 3. Cuadro comparativo: DA / DB / Ninguno

Basado en las definiciones textuales de la sección 2 (pp. 2–3).

| Elemento | ¿Dispositivo de Aislamiento (DA)? | ¿Dispositivo de Bloqueo (DB)? | ¿Ninguno? | Base |
|---|:-:|:-:|:-:|---|
| Seccionador | ✅ | | | Ejemplo textual de DA |
| Interruptor | ✅ | | | Ejemplo textual de DA |
| Válvula | ✅ | | | Ejemplo textual de DA |
| Pinza (para candados) | | ✅ | | Ejemplo textual de DB |
| Cadena | | ✅ | | Ejemplo textual de DB |
| Guardas, puertas, tapas | ➖ "otro control efectivo" cuando no hay DA, al que se le pueda aplicar el LOTOTO | | | Def. DA |
| Botonera de parada de emergencia | | | ✅ | "No son dispositivos de aislamiento… control" |
| Selectores | | | ✅ | idem |
| Sistemas de supervisión (PCs, DCS, PLC) | | | ✅ | idem |
| Candado de bloqueo (personal o de CBE) | | | (no es DA ni DB; es el candado que se instala *en* el DB) | "permite instalar candados de bloqueo en él" |
| Caja de bloqueo grupal | | | (elemento del bloqueo grupal; el estándar no la clasifica como DA/DB) | 6.4.4 |
| Tarjeta personal / de CBE / Fuera de servicio | | | ✅ (identificación; no aísla) | Anexos 01–03 |

> Nota: el estándar solo define DA y DB con ejemplos. La clasificación de candado, caja y tarjetas como "ninguno" es mi lectura: no aparecen definidos como DA ni DB.

---

## 4. Candados, tarjetas, cajas, cambio de turno y retiro forzado

### 4.1 Candados (6.4.1 – p. 6)
- "Los candados de bloqueo deben ser únicos y diferenciables para SMCV y EE.CC."
- "Todos los candados de bloqueo deben ser de llave única, ésta llave debe estar bajo control exclusivo del empleado que coloque el candado."
- "Solo debe usarse para el bloqueo (Lototo)."
- "Los candados deben ser resistentes y de una sola llave."

**Diapositiva del curso "Candado de bloqueo personal: EECC"** (textual):
- ✓ Resistentes.
- ✓ Fácil instalación en los dispositivos de bloqueo.
- ✓ Distintos al candado de SMCV.
- ✓ Llave única.
- ✓ Bajo control exclusivo del empleado que colocó el candado.

### 4.2 Tarjetas (6.4.2 – p. 6)
- Deben soportar 50 libras (23 kg) de fuerza.
- Tener los datos de la persona que bloquea (nombres y apellidos).
- Incluir información de su supervisor.
- Ser legibles.
- Soportar la exposición a condiciones como clima adverso, ácido, etc.
- Tener mensaje de "PELIGRO" y "un aviso que prohíba el retiro de la tarjeta sin autorización y que su manipulación no autorizada constituye una falta grave."
- "Las tarjetas de CBE deben indicar CBE."

**Tarjeta "Bloqueo personal" (Anexo 02 y diap. 9):** Frente: PELIGRO / NO ENERGIZAR (foto, empresa, nombre, teléfono). Reverso: "NO RETIRE ESTA TARJETA. SI LO HACE SIN AUTORIZACIÓN SERÁ SANCIONADO. EL CANDADO QUE ESTÁ BLOQUEANDO ES DE USO PERSONAL." Según la diapositiva: apellidos/nombres y teléfono; legibles; soportar clima; mensaje "PELIGRO"; aviso de no retiro; campo "Empresa": "CONTRATISTA" o "SMCV"; espacio bajo Teléfono: "Cada trabajador contratista debe escribir el nombre de su empresa."

**Tarjeta de CBE (Anexo 01):** PELIGRO – NO OPERAR – EQUIPO BLOQUEADO – CBE; nombre, teléfono, supervisor de SMCV, fecha; casillas: verificación del proceso de bloqueo, prueba de arranque, drenaje (opcional). Reverso: "NO RETIRAR ESTA TARJETA"; equipo y actividad.

### 4.3 Candados y tarjetas "Fuera de servicio" (6.4.3 – p. 6)
- "no pueden ser utilizados para el bloqueo (Lototo)."
- "Las llaves… deben ser administrados por el supervisor del área."
- "Se aplica cuando el equipo se considera inseguro."
- "Se utiliza para proteger las máquinas y los equipos de daños debidos a arranques accidentales."
- "Las tarjetas deben indicar FUERA DE SERVICIO."
- Además (p. 3): fecha de expiración, máximo 6 meses.
- Anexo 03: tarjeta amarilla "PELIGRO – NO OPERAR – Hombres Trabajando" (nombre, área, supervisor, teléfono).

### 4.4 Cajas de bloqueo (6.4.4 – p. 6)
Deben estar identificadas; implementar estaciones fijas de bloqueo ubicadas "en la zona más cercana al equipo"; si no es posible, el grupo define una posición fija donde quedará la caja durante el trabajo. No se anidan cajas.

### 4.5 Cambio de turno = Relevo de CBE (6.3.2 – pp. 4–5)
- "El CBE entrante agregará su información al formato de CBE."
- "El CBE saliente y entrante deben confirmar verbalmente los detalles del trabajo y el bloqueo, y pueden confirmar visualmente los dispositivos de bloqueo en uso."
- "Cuando la entrega de llave al CBE entrante no sea posible esta llave debe ser entregada al supervisor a cargo."
- "**La única llave de bloqueo que puede ser transferida para cambios de turnos es la de CBE que cierra una caja de bloqueo grupal**, siguiendo el procedimiento específico."
- "El CBE entrante asumirá la responsabilidad… una vez que tomen posesión de la llave y pongan su información de contacto en la tarjeta de CBE."
- "El CBE saliente eliminará su bloqueo personal del dispositivo de bloqueo grupal antes de retirarse del área."
- El formulario de CBE se mantiene junto a la caja, salvo durante el relevo.
- "Ninguna persona autorizada nueva se unirá a LOTOTO en proceso hasta que se complete el relevo de CBE y se haya devuelto el formato."
- Quienes ya firmaron la lista individual "pueden continuar el trabajo mientras la transferencia de CBE está en proceso."

### 4.6 Corte de candado = retiro forzado (6.7 – p. 8, Formato 02 – p. 15)
> "Si un personal autorizado no está disponible para retirar su Candado de bloqueo o no se puede identificar al propietario de un dispositivo de bloqueo se puede eliminar el bloqueo usando el formato de corte de candado de bloqueo."

Formato 02: checklist (revisar info del bloqueo y tarjeta en formato CBE; inspección exhaustiva del equipo; verificar tierras temporales y dispositivos retirados; área libre de herramientas y materiales; equipo en condiciones operativas; guardas reinstaladas; personal despejado). Si el propietario **no** es contactado: registrar esfuerzo de contacto (¿por quién?, ¿cuándo?, ubicación del propietario) y **autorización verbal del Supervisor Senior o Superintendente**; contactar a Supervisor del Área, Personal Calificado, CBE (si aplica) y Salud & Seguridad. Notificación: "El empleado ha sido notificado de la eliminación de su dispositivo de bloqueo **antes de que retome al trabajo**." Entregar el documento al Superintendente de Área o responsable.
Registro (p. 9): "Formato de Autorización para el retiro o corte de un candado personal": responsable Supervisor del área (copia 1 Salud y Seguridad, copia 2 Recursos Humanos, Administrador de Contratos solo contratistas); conservación **1 año**.

### 4.7 Restauración de energía (6.6 – p. 8)
1. **Inspeccionar el área:** sin personas, herramientas ni equipos; protectores/guardas reinstalados; equipo operacionalmente intacto.
2. **Retirar todos los bloqueos (candados).**
3. **Notificar** al propietario del equipo/sistema y al personal afectado.
4. **Personal calificado restaura la energía** según procedimientos.

---

## 5. Controles Críticos obligatorios (6.1 – p. 3 y Hoja de Resumen)

| # | Control crítico (textual) |
|---|---|
| 1 | "Personal acreditado y Coordinador de Bloqueo de Energía (CBE) apropiado asignado de acuerdo al estándar de Bloqueo (Lototo)." |
| 2 | "Identificación de todas las fuentes de energía (aguas arriba y aguas abajo) de los equipos o circuitos a intervenir." |
| 3 | "Aislamiento y bloqueo efectivo de las fuentes de energía." |
| 4 | "Todas las personas involucradas en la tarea han realizado el bloqueo personal." |

Riesgo potencial: "Liberación descontrolada de Energía."

### Generalidades (6.2 – pp. 3–4)
- "Sólo personal calificado puede realizar aislamiento de energía peligrosa."
- "El personal autorizado debe colocar su bloqueo personal en cada dispositivo de aislamiento de energía o dispositivo de bloqueo grupal."
- "Cuando personal autorizado no pueda acceder a colocar su candado y tarjeta en el dispositivo de aislamiento se debe aplicar bloqueo grupal (que requiere CBE)."
- "El personal autorizado puede realizar bloqueo, sin que sea necesaria la participación de un CBE cuando el bloqueo se considera simple."
- "Cada trabajador tiene el derecho de verificar el bloqueo de energía peligrosa con el CBE, personal calificado o supervisión."
- Acceso limitado a dispositivos: la persona autorizada será escoltada por una persona calificada o se utilizará el proceso de CBE.
- Si no se puede cumplir el estándar: proceso de variación; o aplicar el Estándar de Control de Energías Peligrosas; otros métodos (p. ej., alta tensión) requieren PETS específico.

### Proceso de bloqueo (6.5 – pp. 7–8)
**Planificación (diapositiva n.º 21 del curso, textual):**
> **1 – Supervisor:**
> 1) "*Asigna* el responsable para cada bloqueo."
> 2) "*Define* el tipo de bloqueo (simple o grupal)"
> 3) "*Actividades complejas:*"
> ✓ "*Supervisor:* Junto con el CBE elaboran el 'Plan de bloqueo' y lo difunden."
> ✓ "*Supervisor senior:* Revisa y aprueba el plan."
>
> **2 – CBE (B. Grupal) / P. Autorizado (B. Simple):**
> 1) "*Identifica* fuentes de energías."
> 2) "*Preparación* de dispositivos y accesorios de bloqueo."
> 3) "*Ejecución* del bloqueo"

**Planificación (estándar):** entender el alcance; asignar CBE y personal calificado; identificar fuentes/puntos de bloqueo (planos, etiquetado); el CBE define secuencia de bloqueo; reunir dispositivos y materiales.
**Fase 2: Ejecución (Bloqueo Simple) (diapositiva del curso, textual; el inicio del título "[Fa]se" estaba tapado en la foto):**
> Las 6 etapas, en el orden numerado de la diapositiva: **1** Notificación y coordinación → **2** Aislamiento → **3** Colocación → **4** Bloqueo → **5** Prueba de arranque → **6** Drenaje.

> ⚠️ **Ojo con el orden:** en la diapositiva, la Prueba de arranque (5) va antes del Drenaje (6). En el estándar (6.5.2, p. 7) el orden es: notificar y coordinar → aislar → bloquear → **drenar o disipar energía remanente** → **ejecutar prueba de arranque** → colocar bloqueo de personal autorizado. Si el examen pregunta el orden, usa el de la diapositiva del instructor y confírmalo con él; el estándar pone el drenaje antes de la prueba de arranque.

**Fase 2: Ejecución (Bloqueo Grupal) (diapositiva n.º 31 del curso, textual):**
> Las 6 etapas, en el orden numerado de la diapositiva: **1** Notificación y coordinación → **2** Aislamiento → **3** Bloqueo y tarjeteo → **4** Prueba de arranque → **5** Drenaje → **6** Candado y tarjeta personal.

> ⚠️ Igual que en bloqueo simple, la diapositiva pone la Prueba de arranque (4) antes del Drenaje (5). El estándar (6.5.3, p. 7–8) ordena: notificar y coordinar → aislar → bloquear (el CBE coloca dispositivo, candado y tarjeta de CBE) → **drenar o disipar energía remanente** → **ejecutar prueba de arranque** → el personal autorizado coloca su candado y tarjeta personal en la caja. Como las dos diapositivas del instructor coinciden entre sí, confirma con él cuál orden toma el examen.

**Etapa 1: Notificación – Bloqueo Grupal (diapositiva n.º 32 del curso, textual):**
> **CBE**
> 1) "Completa el 'Formato de CBE' y 'Tarjetas CBE'."
> 2) "Coordina con el 'Personal Afectado' la detención del equipo."
> 3) "Coordina la participación del 'Personal Calificado' en el proceso."
> 4) "Indica al 'Personal Calificado' los puntos a aislar de acuerdo al 'Formato de CBE'."

**Etapa 1: Notificación y Coordinación – Bloqueo Simple (diapositiva del curso, textual):**
> **Personal Autorizado**
> 1) "Notifica y coordina con el 'Personal Afectado' la detención del equip[o]" *(última letra tapada por una cabeza en la foto)*.
> 2) "Coordina la participación del 'Personal Calificado'."

**Bloqueo simple (estándar):** notificar/coordinar con el afectado → aislar (el calificado solicita la detención al afectado, confirma y aísla) → el autorizado coloca su dispositivo de bloqueo, candado y tarjeta personal → drenar/disipar energía remanente → ejecutar prueba de arranque → colocar bloqueo de personal autorizado. *Bloqueos simples adicionales:* otra persona autorizada sigue todos los pasos **excepto la prueba de arranque**, que de requerirse se coordina con todos los que ya bloquearon.
**Bloqueo grupal:** igual, pero el **CBE** coordina, coloca dispositivo de bloqueo, candado y tarjeta de CBE, coordina el drenaje y las pruebas de arranque; luego cada autorizado coloca su candado y tarjeta personal en la caja. Si el CBE participa de la tarea, también coloca su tarjeta y candado personal. Quien se une a un bloqueo ya armado debe solicitar autorización al personal autorizado (simple) o al CBE (grupal), "quién debe verificar si los puntos de bloqueo son los correctos."

### Capacitación (7 – p. 8)
Capacitación inicial y refrescamiento **anual**; entrenamiento en PETS; entrenamiento cuando se instalen nuevos equipos o procesos; re-entrenamiento si fuera necesario.

### Registros (p. 9)
| Registro | Responsable | Conservación |
|---|---|---|
| Formato de autorización para retiro/corte de candado personal | Supervisor del área (copias a S&S, RR.HH., Adm. de Contratos) | 1 año |
| Tarjetas de CBE | Supervisores de área | 1 mes |
| Tarjetas de bloqueo | Superintendentes de Área / Empresas Contratistas | Permanente |
| Formato de Coordinador de Bloqueo de Energías | Superintendentes de Área / Empresas Contratistas | Permanente |

Formato CBE (Formato 01, pp. 13–14): advertencia "Si el equipo NO está en la lista, ¡no está bloqueado!"; lista de equipos, personal calificado que aisló y que drenó, fechas; transferencia de CBE; lista de bloqueo individual (nombre, fecha, hora de bloqueo aplicado, firma, hora de retiro).

---

## 6. Balotario (20 preguntas)

**1. (V/F)** El estándar aplica al trabajo en herramientas portátiles eléctricas con cable y enchufe cuando el enchufe permanece bajo control de quien realiza el trabajo.
**Respuesta: F.** El Alcance (p. 2) dice que **no se aplica** en ese caso: la energización está controlada por la desconexión del equipo y el enchufe bajo control de la persona.

**2. (MC)** ¿Cuál **NO** es un dispositivo de aislamiento de energía según SSOst0036?
a) Seccionador b) Interruptor c) Válvula d) **Botonera de parada de emergencia**
**Respuesta: d.** Definición (p. 2): "No son dispositivos de aislamiento los dispositivos de control como: botoneras de parada de emergencia, selectores, sistemas de supervisión (PCs, DCS, PLC)…"

**3. (V/F)** Un PLC es un dispositivo de aislamiento válido.
**Respuesta: F.** Es un sistema de supervisión/control (p. 2).

**4. (MC)** El dispositivo de bloqueo es:
a) Un dispositivo eléctrico de control b) **Un dispositivo mecánico (pinza, cadena u otros) usado para impedir la operación del dispositivo de aislamiento y que permite instalar candados** c) La tarjeta personal d) La llave del CBE
**Respuesta: b.** Definición, p. 3.

**5. (V/F)** Los Puntos de bloqueo son la lista de dispositivos de aislamiento necesarios para realizar una actividad específica.
**Respuesta: V.** Definición (p. 3) y diapositiva "Puntos de bloqueo".

**6. (MC)** ¿Quién elabora con anterioridad el Plan de bloqueo, que es obligatorio para detenciones de planta planificadas?
a) El operador b) **El Supervisor del área y los CBE asignados** c) El contratista d) El área de Seguridad
**Respuesta: b.** Diapositiva "Plan de bloqueo". Para actividades complejas, cuando el supervisor lo considere.

**7. (MC)** En el bloqueo simple, la tarjeta y el candado personal se colocan:
a) En una caja de bloqueo grupal b) **En un dispositivo de bloqueo instalado directamente en un dispositivo de aislamiento** c) Solo el CBE d) En el tablero de control
**Respuesta: b.** Definición, p. 2.

**8. (V/F)** En el bloqueo grupal no se requiere CBE.
**Respuesta: F.** "En bloqueo grupal se requiere CBE." (p. 2)

**9. (V/F)** Se permite anidar cajas de bloqueo grupal cuando hay muchos puntos.
**Respuesta: F.** "No se permite anidar cajas de bloqueo grupal." (p. 2)

**10. (V/F)** El bloqueo de CBE es un bloqueo personal.
**Respuesta: F.** "El bloqueo de CBE no es un bloqueo personal." El CBE debe colocar además su tarjeta y candado personal en la caja si trabaja en el equipo (p. 4).

**11. (MC)** En bloqueo grupal, ¿quién coloca el primer bloqueo y retira el último de la caja?
a) El supervisor b) El último trabajador en llegar c) **El CBE** d) El personal calificado
**Respuesta: c.** 6.3.2, p. 4.

**12. (MC)** ¿Qué llave puede transferirse en un cambio de turno?
a) La de cualquier candado personal b) **Solo la del CBE que cierra la caja de bloqueo grupal** c) La del supervisor d) Ninguna
**Respuesta: b.** 6.3.2 Relevo de CBE, p. 5. Si no se puede entregar al CBE entrante, va al supervisor a cargo.

**13. (V/F)** Al relevar al CBE, el CBE saliente debe eliminar su bloqueo personal del dispositivo de bloqueo grupal antes de retirarse del área.
**Respuesta: V.** p. 5.

**14. (MC)** Una tarjeta "Fuera de servicio" debe indicar fecha de expiración de máximo:
a) 1 mes b) 3 meses c) **6 meses** d) 12 meses
**Respuesta: c.** Definición, p. 3.

**15. (V/F)** La tarjeta "Fuera de servicio" puede usarse como parte del proceso LOTOTO si el equipo está inoperativo.
**Respuesta: F.** "La tarjeta fuera de servicio no debe ser usada como parte del Proceso de Lototo" (p. 3; también 6.4.3, p. 6). Sus llaves las administra el supervisor del área.

**16. (MC)** Los candados de bloqueo deben ser:
a) Idénticos para SMCV y contratistas b) **Únicos y diferenciables para SMCV y EE.CC., de llave única bajo control exclusivo de quien lo coloca** c) De llave maestra del supervisor d) De uso general
**Respuesta: b.** 6.4.1, p. 6. "Solo debe usarse para el bloqueo (Lototo)."

**17. (MC)** Las tarjetas de bloqueo deben soportar una fuerza de:
a) 10 lb b) 25 lb c) **50 lb (23 kg)** d) 100 lb
**Respuesta: c.** 6.4.2, p. 6. Deben además incluir información del supervisor y el aviso de que su manipulación no autorizada constituye falta grave.

**18. (V/F)** Cuando el dueño de un candado no está disponible, puede cortarse el candado usando el formato de corte, y si el propietario no es contactado se requiere autorización verbal del Supervisor Senior o Superintendente.
**Respuesta: V.** 6.7, p. 8 y Formato 02, p. 15. El empleado debe ser notificado antes de retomar el trabajo.

**19. (V/F)** Un bloqueo simple adicional, en un equipo ya bloqueado, debe seguir todos los pasos incluida la prueba de arranque por cuenta propia.
**Respuesta: F.** Debe seguir todos los pasos **excepto la prueba de arranque**, que de requerirse se coordina con todos los que ya bloquearon (6.5.2, p. 7).

**20. (MC)** ¿Cuál es el orden de la restauración de energía?
a) Retirar candados → notificar → inspeccionar → restaurar b) **Inspeccionar el área → retirar todos los bloqueos → notificar → personal calificado restaura la energía** c) Restaurar → inspeccionar d) Notificar → restaurar → retirar candados
**Respuesta: b.** 6.6, p. 8.

---

### Preguntas adicionales (respaldadas por diapositivas del curso)

**21. (MC)** El Líder de Personal Autorizado es designado por:
a) El CBE b) **El supervisor del equipo de trabajo** c) El superintendente de seguridad d) Los propios trabajadores
**Respuesta: b.** Diapositiva "Líder de Personal Autorizado": personal autorizado acreditado en Lototo, designado por el supervisor del equipo de trabajo.

**22. (V/F)** El Líder de Personal Autorizado puede ser personal de una empresa contratista.
**Respuesta: V.** "¡IMPORTANTE! Puede ser personal de SMCV o personal de empresa contratista."

**23. (MC)** El Líder de Personal Autorizado debe:
a) Reemplazar al CBE b) **Realizar la prueba de arranque con el CBE y firmar el formato de CBE en señal de conformidad** c) Retirar los candados ajenos d) Elaborar el Plan de bloqueo
**Respuesta: b.** Misma diapositiva.

**24. (MC)** El CBE es quien:
a) Elabora el Plan de bloqueo solo b) **Lidera el proceso de bloqueo grupal** c) Retira los candados ajenos d) Opera el equipo
**Respuesta: b.** Diapositiva "Coordinador de Bloqueo de Energía – CBE".

**25. (MC)** Un requisito para ser CBE es:
a) Ser personal de SMCV exclusivamente b) **Estar acreditado en LOTOTO y CBE y tener como mínimo 1 año de experiencia en el área de trabajo** c) Ser supervisor d) No tener experiencia previa
**Respuesta: b.** Diapositiva CBE y estándar p. 3 (el superintendente designa a los CBE considerando antigüedad mínima de un año).

**26. (MC)** El Personal Afectado es la persona que:
a) Aísla las fuentes de energía b) **Opera o tiene a su cargo el equipo en el que se va a ejecutar un trabajo** c) Coloca la tarjeta de CBE d) Retira los candados
**Respuesta: b.** Diapositiva "Personal Afectado".

**27. (V/F)** El Personal Afectado autoriza la detención y aislamiento del equipo, detiene los equipos a intervenir y realiza la prueba de arranque de su equipo cuando la solicita el CBE o el Personal Autorizado.
**Respuesta: V.** Diapositiva "Personal Afectado".

**28. (MC)** El Personal Calificado es la persona que:
a) Opera el equipo b) **Realiza el aislamiento y la disipación de energía (en caso aplique) y conoce los sistemas/equipos donde se realizará el bloqueo** c) Elabora el Plan de bloqueo d) Lidera el bloqueo grupal
**Respuesta: b.** Diapositiva "Personal Calificado".

**29. (V/F)** El Personal Calificado debe tener vigente el curso de Lototo y es responsable de verificar la efectividad del aislamiento de energía.
**Respuesta: V.** Diapositiva "Personal Calificado" y estándar 6.3.3 (p. 5).

**30. (MC)** Cuando se requiere el apoyo de un CBE de otra área, el supervisor debe realizar una capacitación presencial previa en los puntos de bloqueo, de duración mínima:
a) 1 hora b) 2 horas c) **5 horas** d) 8 horas
**Respuesta: c.** Diapositiva "Supervisor" (n.º 19): "como mínimo de 5 horas", pudiendo ser mayor según la complejidad del bloqueo.

**31. (V/F)** La capacitación al CBE de otra área no requiere registro.
**Respuesta: F.** "Se deberá tener un registro de la capacitación brindada." (diap. 19)

**32. (MC)** En la etapa de Planificación, ¿quién define el tipo de bloqueo (simple o grupal)?
a) El CBE b) **El supervisor** c) El personal calificado d) El supervisor senior
**Respuesta: b.** Diapositiva "Planificación" (n.º 21): el supervisor asigna el responsable para cada bloqueo y define el tipo de bloqueo.

**33. (MC)** En actividades complejas, ¿quién revisa y aprueba el Plan de bloqueo?
a) El CBE b) El supervisor c) **El supervisor senior** d) El personal afectado
**Respuesta: c.** El supervisor, junto con el CBE, elabora el Plan de bloqueo y lo difunde; el supervisor senior lo revisa y aprueba (diap. 21).

**34. (V/F)** En bloqueo simple, quien identifica las fuentes de energía, prepara los dispositivos y ejecuta el bloqueo es el Personal Autorizado; en bloqueo grupal, es el CBE.
**Respuesta: V.** Diapositiva "Planificación", columna 2: "CBE (B. Grupal)/P. Autorizado (B. Simple)".

**35. (MC)** Según la diapositiva "Ejecución (Bloqueo Simple)", ¿cuál es la primera etapa?
a) Aislamiento b) Bloqueo c) **Notificación y coordinación** d) Prueba de arranque
**Respuesta: c.** Etapa 1 de las 6 de la diapositiva. Coincide con el estándar (6.5.2, p. 7): "Notificar y Coordinar con el afectado / Obtener permiso / Coordinar con el Calificado".

**36. (V/F)** La Ejecución del Bloqueo Simple tiene 6 etapas: notificación y coordinación, aislamiento, colocación, bloqueo, prueba de arranque y drenaje.
**Respuesta: V** según la diapositiva del curso. *(El estándar pone el drenaje antes de la prueba de arranque; ver nota en la sección 5.)*

**37. (MC)** En la etapa de Notificación y Coordinación del bloqueo simple, el Personal Autorizado:
a) Aísla la fuente de energía b) **Notifica y coordina con el Personal Afectado la detención del equipo y coordina la participación del Personal Calificado** c) Realiza el drenaje d) Firma el formato de CBE
**Respuesta: b.** Diapositiva "Notificación y Coordinación". Coincide con el estándar (6.5.2, p. 7).

**38. (MC)** Según la diapositiva "Ejecución (Bloqueo Grupal)", la etapa 6 es:
a) Drenaje b) Prueba de arranque c) **Candado y tarjeta personal** d) Aislamiento
**Respuesta: c.** En el estándar (6.5.3): el personal autorizado coloca su candado y tarjeta personal en la caja de bloqueo grupal, siguiendo las indicaciones del CBE.

**39. (V/F)** En bloqueo grupal, la etapa 3 es "Bloqueo y tarjeteo", y en el estándar es el CBE quien coloca el dispositivo de bloqueo, el candado y la tarjeta de CBE.
**Respuesta: V.** Diapositiva n.º 31 y estándar 6.5.3 (p. 8).

**40. (MC)** En la etapa de Notificación del bloqueo grupal, el CBE:
a) Coloca su candado personal en la caja b) **Completa el Formato de CBE y las Tarjetas CBE, coordina con el Personal Afectado y el Personal Calificado, e indica al Personal Calificado los puntos a aislar según el Formato de CBE** c) Realiza el drenaje d) Opera el equipo
**Respuesta: b.** Diapositiva n.º 32 "Notificación".

**41. (V/F)** En bloqueo grupal, quien indica los puntos a aislar al Personal Calificado es el Personal Afectado.
**Respuesta: F.** Es el CBE, de acuerdo con el Formato de CBE (diap. 32).

**42. (V/F)** Si existe un Plan de bloqueo, ya no es necesario identificar las fuentes de energía en campo.
**Respuesta: F.** "El Plan de bloqueo *no elimina* la identificación de fuentes de energía que se debe realizar en campo (IPERC Continuo, Formato de CBE)." (diap. 8)

### Datos adicionales útiles para examen
- Controles críticos: **4** (ver sección 5).
- Capacitación previa al CBE de otra área: **mínimo 5 horas**, presencial, con registro (diap. 19).
- Antigüedad mínima para ser CBE/Personal calificado en la lista del superintendente: **1 año**.
- Capacitación: inicial y **refrescamiento anual**.
- Conservación: tarjetas de CBE **1 mes**; formato de corte de candado **1 año**; tarjetas de bloqueo y formato CBE **permanente**.
- Lototo = Lock out, Tag out, Try out.
