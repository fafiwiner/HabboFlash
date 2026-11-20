# Guía LOTOTO – SMCV (curso TECSUP, estándar SSOst0036)

> **Cómo leer esta guía**
> - 🟢 **VERIFICADO** = transcrito de las diapositivas del curso (fotos del usuario).
> - 🟡 **REFERENCIAL** = redactado desde conocimiento general del LOTOTO de Freeport/SMCV y buenas prácticas. **No es cita textual** del SSOst0036; el PDF oficial no pudo descargarse (`publicportal.fmi.com` bloqueado en el entorno). Contrastar con el estándar antes de usarlo para rendir examen.

## 0. Fuentes
- 🟢 Diapositivas del curso: "Plan de bloqueo", "Puntos de bloqueo", "Tarjeta: Bloqueo personal" (diap. 9).
- [SSOst0036 Estándar de Bloqueo v.01](https://publicportal.fmi.com/sites/publicportal/files/Files/cerro_verde_files/seguridad/estandares/SSOst0036%20Est%C3%A1ndar%20de%20Bloqueo_v.01.pdf) – no leído.
- [SGIpr0015 Procedimiento General de Bloqueo v05](https://publicportal.fmi.com/sites/publicportal/files/Files/cerro_verde_files/seguridad/procedimientos/SGIpr0015_Procedimiento%20General%20de%20Bloqueo_v05.pdf) – no leído.
- No se halló v.02/v.03 pública ni PPT/banco de preguntas público (Scribd/Studocu requieren login y se ignoraron).

## 1. Definiciones

### 🟢 Plan de bloqueo (textual)
> "Documento que detalla: *tareas a ejecutar, asignación de CBE* y la *lista de referencia de los puntos de bloqueo para cada tarea*."
> ¿Quién lo elabora? "Elaborado con anterioridad por el *Supervisor del área y CBE asignados* para *detenciones de planta planifica[das]* (obligatorio) y para *actividades complejas* (cuan[do el] supervisor lo considere)."
> (Las palabras entre `[ ]` estaban tapadas en la foto.)

### 🟢 Puntos de bloqueo (textual)
> "Es una *LISTA DE DISPOSITIVOS DE AISLAMIENTO* necesarios para realizar una actividad específica, que permiten aislar las fuentes de energía peligrosa."

### 🟡 Resto (paráfrasis, no textual)
| Término | Idea del estándar |
|---|---|
| **Dispositivo de Aislamiento (DA)** | Dispositivo físico que **impide la transmisión o liberación de energía** (interruptor/seccionador de potencia, válvula de bloqueo, brida ciega, bloqueo mecánico, etc.). Es lo que se aísla. |
| **Dispositivo de Bloqueo (DB)** | Elemento que, mediante un medio positivo (candado), **mantiene un DA en posición segura** e impide su operación: candados, pinzas multicandado (hasp), cadenas, bloqueadores de válvula/interruptor/enchufe. |
| **Bloqueo Simple** | Aislamiento donde **cada trabajador coloca directamente su propio candado y tarjeta personal** en cada punto de bloqueo. Típico de tareas con pocos puntos/personas. |
| **Bloqueo Grupal** | Muchos trabajadores/puntos: el **CBE** bloquea los puntos con sus candados, deposita las llaves en una **caja de bloqueo grupal** y **cada trabajador pone su candado personal en la caja**. |
| **CBE** | Sigla usada en el curso/Plan de bloqueo (en FMI: *Coordinador de Bloqueo de Energía*); designado para coordinar el bloqueo, verificar puntos y asignado en el Plan de bloqueo. |
| **Persona Calificada** | Persona con formación, entrenamiento y experiencia demostrada para identificar los peligros de la energía y realizar/verificar el aislamiento. |
| **Personal Autorizado** | Persona designada formalmente para ejecutar bloqueos y colocar candado/tarjeta en equipos. |

## 2. Cuadro comparativo (🟡 referencial)

| Elemento | ¿DA? | ¿DB? | ¿Ninguno? |
|---|:-:|:-:|:-:|
| Interruptor/seccionador de potencia, breaker | ✅ | | |
| Válvula de bloqueo (aislamiento de fluido) | ✅ | | |
| Brida ciega / espárrago de aislamiento | ✅ | | |
| Bloqueo mecánico (pin, cuña, tope) que inmoviliza energía almacenada | ✅ | | |
| Candado personal | | ✅ | |
| Pinza multicandado (hasp), cadena, bloqueador de válvula/breaker | | ✅ | |
| Caja de bloqueo grupal | | ✅ | |
| Tarjeta de bloqueo personal / "Fuera de Servicio" | | | ✅ (advertencia, no impide por sí misma) |
| **Botonera de parada de emergencia** | | | ✅ |
| **PLC / controles lógicos / software** | | | ✅ |
| **Selectores, pulsadores de arranque/parada, interruptores de control** | | | ✅ |

Criterio: solo es DA si **aísla físicamente** la fuente de energía; los dispositivos de control/maniobra no son aislamiento confiable.

## 3. Candados, tarjetas, cambio de turno y retiro forzado

### 🟢 Tarjeta "Bloqueo personal" (diap. 9, textual)
Frente: "PELIGRO – NO ENERGIZAR" (foto, empresa, nombre, teléfono). Reverso: "PELIGRO – NO RETIRE ESTA TARJETA. SI LO HACE SIN AUTORIZACIÓN SERÁ SANCIONADO. EL CANDADO QUE ESTÁ BLOQUEANDO ES DE USO PERSONAL."
Características:
- Apellidos/Nombres y Teléfono.
- Legibles.
- Soportar la exposición al clima o ambiente adverso.
- Tener un mensaje de "PELIGRO".
- Tener el aviso que prohíba el retiro de la tarjeta sin autorización y que su manipulación no autorizada constituye una falta grave.
- Campo "Empresa": "CONTRATISTA" o "SMCV".
- Espacio en blanco (debajo del campo TELÉFONO): cada trabajador contratista debe escribir el nombre de su empresa.

### 🟡 Reglas generales (referencial)
- **Candado personal:** uso personal, una sola llave en poder del dueño, no se presta ni se comparte; cada trabajador coloca el suyo y lo retira solo él.
- **Tarjeta personal:** acompaña siempre al candado; nunca se usa sola como bloqueo.
- **Tarjeta "Fuera de Servicio":** advierte que un equipo está inoperativo por falla/condición no operativa (no reemplaza al LOTOTO de trabajo); solo la retira quien la colocó o personal autorizado tras corregir la condición.
- **Cambio de turno:** el trabajador saliente **no retira** su candado hasta que el entrante coloque el suyo; traspaso con comunicación directa y verificación del estado del bloqueo. Si el trabajo continúa, los bloqueos se mantienen.
- **Retiro forzado:** solo cuando el dueño no está disponible (sin retiro posible del lugar), con **autorización del supervisor/nivel definido**, tras **intentar ubicarlo**, **verificar que el equipo es seguro**, y **comunicándole** antes de que reanude trabajo. Queda registrado.
- **Antes de energizar:** retirar herramientas, verificar personal despejado, retirar candados/tarjetas, avisar a los afectados.

## 4. Controles Críticos (🟡 referencial; verificar lista exacta de SMCV)
1. Identificar todas las fuentes de energía peligrosa y los puntos de bloqueo (Plan de bloqueo cuando corresponda).
2. Aislar y bloquear **cada** punto con candado + tarjeta personal de cada trabajador.
3. **Disipar/controlar energía residual o almacenada.**
4. **Prueba de ausencia de energía** (intento de arranque / medición) antes de iniciar el trabajo.
5. Candado personal intransferible; prohibido retirar candado/tarjeta ajenos.
6. Participación obligatoria de personal autorizado/calificado y CBE cuando aplique.
7. Cambio de turno y retiro forzado solo por el procedimiento.
8. Verificación y comunicación antes de reenergizar.

## 5. Balotario (20 preguntas)
Las preguntas 1–4 y las que citan "diapositiva" tienen respaldo 🟢; el resto es 🟡 referencial.

1. **(V/F)** El Plan de bloqueo es obligatorio para detenciones de planta planificadas. **V.** 🟢 Diap. Plan de bloqueo.
2. **(MC)** ¿Quién elabora con anterioridad el Plan de bloqueo? a) Operador b) **Supervisor del área y CBE asignados** c) Contratista d) Seguridad. **b.** 🟢
3. **(MC)** Los Puntos de bloqueo son: a) **Lista de dispositivos de aislamiento necesarios para una actividad específica** b) Candados c) Tarjetas d) PLC. **a.** 🟢
4. **(V/F)** El campo "Empresa" de la tarjeta puede ser "CONTRATISTA" o "SMCV". **V.** 🟢 Diap. 9.
5. **(V/F)** Un contratista debe escribir el nombre de su empresa en el espacio bajo el campo Teléfono. **V.** 🟢 Diap. 9.
6. **(V/F)** La manipulación no autorizada de la tarjeta constituye una falta grave. **V.** 🟢 Diap. 9.
7. **(MC)** Una tarjeta personal debe: a) Ser ilegible b) **Soportar clima adverso y tener el mensaje "PELIGRO"** c) No tener teléfono d) Ser compartida. **b.** 🟢
8. **(MC)** ¿Cuál es un dispositivo de aislamiento? a) Botonera de emergencia b) PLC c) **Interruptor de potencia** d) Selector. **c.** 🟡 Aísla físicamente la energía.
9. **(V/F)** Una botonera de parada de emergencia es un dispositivo de aislamiento. **F.** 🟡 Es de control, no aísla.
10. **(V/F)** Un PLC puede usarse como único medio de aislamiento. **F.** 🟡
11. **(MC)** El candado es un: a) DA b) **DB** c) CBE d) Plan de bloqueo. **b.** 🟡
12. **(MC)** En bloqueo grupal, cada trabajador coloca su candado personal: a) En cada válvula b) **En la caja de bloqueo grupal** c) En su casco d) No lo coloca. **b.** 🟡
13. **(V/F)** En bloqueo simple, cada trabajador coloca su propio candado y tarjeta en los puntos. **V.** 🟡
14. **(V/F)** Se puede prestar el candado personal a un compañero de confianza. **F.** 🟡 Es de uso personal.
15. **(V/F)** La tarjeta sola, sin candado, es suficiente para bloquear. **F.** 🟡
16. **(MC)** Antes de iniciar el trabajo se debe: a) Solo avisar b) **Verificar ausencia de energía (prueba)** c) Quitar tarjetas d) Nada. **b.** 🟡
17. **(MC)** En cambio de turno, el saliente retira su candado: a) Antes de irse b) **Solo cuando el entrante ya colocó el suyo** c) Nunca avisa d) Al azar. **b.** 🟡
18. **(V/F)** El retiro forzado se hace sin intentar ubicar al dueño del candado. **F.** 🟡 Exige intentar ubicarlo, autorización y verificación.
19. **(V/F)** La tarjeta "Fuera de Servicio" reemplaza el bloqueo personal durante el trabajo. **F.** 🟡
20. **(V/F)** Antes de reenergizar se debe verificar que el personal esté despejado y avisar. **V.** 🟡

> ⚠️ Para rendir el examen, confirmar con el PDF o las diapositivas todo lo 🟡.
