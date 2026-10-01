# Guion — Grok Bot · charla del viernes 2 oct 2026

**Duración:** 30–40 min (base: guion del meetup del 16/09, de 20 min; ese archivo no se toca)
**Formato:** charla + demos en vivo, sin hands-on individual
**Presentan:** Martín Manuel Malgor (SpaceXAI / Cursor Ambassador, Corrientes) · Tobías Insaurralde (Cursor Ambassador)
**Proyección:** deck oficial Grok Bot **en inglés** (Google Slides). Se narra en español con este guion. No existe deck oficial en español.
**Deck EN:** https://docs.google.com/presentation/d/1IPXSSmoHyRdj_KXaHumtAsuekV08TgqO3zrMgZ7DjcA/edit?usp=sharing

> **A confirmar antes del viernes:** venue, horario, si hay Q&A después y quién lo da, y el reparto final de bloques entre Martín y Tobías. No se reusan datos del 16/09 (UNNE, Q&A Cursor 19:05, Tero y Dylo).

---

## Reparto propuesto (confirmar con Tobías)

| Bloque | Lead | Apoyo |
| --- | --- | --- |
| Hook | Martín | — |
| Modelo mental | Tobías | Martín avanza slides |
| Demo A | Martín (teclado) | Tobías narra y vigila el reloj |
| Demo B | Tobías o Martín, según la opción | el otro hace de Plan B |
| Reglas de oro | Tobías | — |
| Cierre + CTA | Martín | Tobías |

Regla de reloj: Tobías avisa "últimos 10" al minuto 30 y "últimos 5" al minuto 35.

---

## Estructura minuto a minuto

| Min | Bloque | Versión 30 min |
| --- | --- | --- |
| 0:00–4:00 | Hook + promesa | 3 |
| 4:00–10:00 | Modelo mental (3 ideas) | 5 |
| 10:00–20:00 | Demo A: agente + Drive | 10 |
| 20:00–30:00 | Demo B: elegir una de tres | 6 |
| 30:00–36:00 | Reglas de oro + anti-patrón | 4 |
| 36:00–40:00 | Cierre + CTA | 2 |

**Si se atrasan, se corta la Demo B, no el cierre.**

---

## 0:00–4:00 — Hook (Martín)

**Slide:** portada del deck EN.

> Buenas. Soy Martín, y conmigo está Tobías. Somos Cursor Ambassadors.
> En los próximos minutos no vamos a ver otro chatbot de preguntas. Vamos a ver un **compañero de trabajo con computadora propia**: se conecta a tus herramientas, recuerda el contexto y termina tareas.

**Caso real (30 s):**

> Hace dos semanas organizamos un meetup en Corrientes. Una parte de la organización la hizo un Grok Bot junto con nosotros. Hoy les mostramos ese mismo tablero.

**Pregunta a la sala (opcional, sirve para romper el hielo):**

> ¿A quién le pasó perder media hora pasando tareas de WhatsApp a una planilla? Bueno, de eso va esto.

**Promesa:**

> Al final van a haber visto tres cosas: qué es un agente, cómo usa Drive de verdad y cómo coordina un trabajo concreto.

---

## 4:00–10:00 — Modelo mental (Tobías)

Tres ideas, contadas con los dedos. Sin arquitectura interna, sin nombres de tools y sin jerga de MCP.

1. **Agente = rol**
   > No es "el chat de Grok". Es un rol con memoria, estilo y tareas: el que organiza un meetup, el coach, el de compras.
   > Ejemplo: no le decís "sos mi IA"; le decís "organizás el meetup de Corrientes".

2. **Tiene computadora**
   > Navega, lee archivos y usa conectores como Drive, Calendar o Gmail. No es solo texto: hace cosas.

3. **Rutinas + skills**
   > Puede repetir un trabajo solo, con un horario, y seguir recetas reutilizables. No tenés que acordarte de pedirle.

**Frase puente (la dice Tobías y le pasa a Martín):**

> La magia no es que conteste lindo. Es que **haga el trabajo** y vuelva cuando necesita tu OK. Martín, mostrales.

**Si hay aire (+1 min):** comparar chat vs agente en una línea:

> Un chat te contesta. Un agente agarra un outcome, lo trabaja con tus herramientas y vuelve con evidencia.

---

## 10:00–20:00 — Demo A: el agente del meetup con Drive (Martín al teclado)

**Setup:** chat del agente del meetup a la izquierda, Drive con el backlog a la derecha. Cuenta de demo.

**Historia (15 s):**

> Tobías y yo tenemos cuentas de Grok Bot distintas, y los agentes no se chatean entre cuentas. Lo resolvimos con un **protocolo en Drive**: un backlog y un inbox entre agentes. La planilla es la fuente de verdad.

**Pasos:**

1. **Backlog (1 min).** Mostrar las columnas Hecho y Pendiente. Señalar fecha, speakers y lo que faltaba.
2. **Pedido en vivo:** copiar y pegar este prompt:

   ```
   Resumí en 5 viñetas qué está Hecho y qué es P0 pendiente en el backlog del meetup. Sé brutalmente concreto. Sin links.
   ```

3. **Mientras responde (Tobías narra):**
   > Fíjense que está leyendo Drive. No está inventando de memoria.
4. **Contrastar (1 min):** poner la respuesta al lado de la planilla y verificar un ítem en voz alta. Esto es la regla de **pedir evidencia** en acción.
5. **Inbox entre agentes (30 s):** mostrar una fila SYNC y el protocolo.
   > Así se coordinan dos organizadores con bots en cuentas distintas: comparten la misma fuente de verdad.
6. **Si hay aire (+2 min):** pedido de seguimiento:

   ```
   De los P0 pendientes, ¿cuál bloquea a los otros? Respondé en 2 líneas.
   ```

**Cierre de la demo:**

> Esto no es un slide de "IA que agenda eventos". Es el tablero con el que corrimos un meetup de verdad.

**Si falla la red:** pasar a los screenshots de `demos/backup/` y seguir narrando. No pelear más de 30 s con el spinner.

---

## 20:00–30:00 — Demo B: elegir UNA

Se preparan las tres. La elección se hace en la previa, según la energía de la sala y el wifi. En la versión de 30 min dura 6.

### B1 — De la idea al artefacto (recomendada)

```
Creá un checklist imprimible de recepción para un meetup: staff 30 min antes, check-in con ticket de 58 mm, roles, qué llevar. Corto, en markdown.
```

> Un pedido en lenguaje natural se convierte en algo que podés usar en la puerta.

### B2 — Multi-agente en la misma cuenta

Mostrar el sidebar con varios agentes.

> Dentro de tu cuenta, los bots sí se hablan y pueden trabajar en un group chat. Entre cuentas distintas, la coordinación va por Drive o Slack.

### B3 — Rutina

Mostrar o bosquejar:

```
Cada mañana a las 9, revisá el inbox del meetup y avisame solo si hay algo marcado como Needs Human.
```

> No tenés que acordarte de pedirle. Vuelve solo.

---

## 30:00–36:00 — Reglas de oro (Tobías)

1. **Rol claro.** "Organizás X", no "sos mi IA genérica".
2. **Una herramienta de verdad.** Drive, Calendar o mail. Si no, es un chat lindo.
3. **Fuente de verdad afuera del chat.** Planilla, doc o repo.
4. **Pedí evidencia.** Links, archivos, resultados. Lo hicimos recién en la Demo A.
5. **El humano decide lo irreversible.** Publicar, pagar, mandar mails masivos.

**Anti-patrón:**

> No es "hacé todo mi laburo mientras scrolleo". Es "tomá este outcome y volvé con el draft, el tablero o el blocker".

---

## 36:00–40:00 — Cierre + CTA (Martín, con Tobías)

> Acaban de ver un Grok Bot coordinando un trabajo real, con Drive como fuente de verdad, no una definición.

**CTA:**

> La tarea para esta semana: un agente, una semana, conectado a Drive o Calendar. Empiecen chico.

**Créditos:** este evento no tiene créditos. No mencionar QR ni prometer créditos.

**Puente:** completar cuando esté confirmado el programa del viernes (Q&A, siguiente speaker o cierre).

---

## Frases de rescate

| Situación | Qué decir |
| --- | --- |
| Spinner eterno | "Mientras vuelve, miren el backlog: esta es la fuente de verdad." |
| Drive falló | "Plan B: les muestro la captura de ayer." |
| Pregunta muy técnica | "Buenísima, la anotamos y la vemos al final." |
| Sala fría | "¿A quién le pasó perder media hora pasando tareas de WhatsApp a una planilla?" |
| Se nos fue el tiempo | Saltar a Reglas de oro y cerrar. Demo B queda afuera. |

---

## Ensayo

1. Demo A completa en voz alta con cronómetro.
2. Elegir B1, B2 o B3 y ensayar solo esa.
3. Grabar una toma de pantalla como backup.
4. Con Tobías: pasar los cambios de lead (min 4, 10, 30, 36) y las señales de reloj.

---

*Guion viernes v1 · 01/10/2026 · deriva de `GUION-workshop-grok-bot.md` (v1, 12/09)*
