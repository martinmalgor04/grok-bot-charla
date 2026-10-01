# Guion — Qué es Grok Bot + Workshop
## Grok Bot Meetup · Corrientes · 16 Sep 2026

**Bloque:** 18:35 – 18:55 (20 minutos)  
**Formato:** charla corta + demos en vivo (sin hands-on individual)  
**Presenta:** Martín (lead) · Tobías (apoyo AV / si se traba, salva)  
**Pantalla:** laptop macOS con Grok Bot abierto, zoom UI 125–150%  
**Objetivo de la sala:** que en 20 min entiendan *qué es*, *para qué sirve*, y *lo vean hacer algo real* — no que se instalen nada en el momento.

---

## Antes de salir a escena (T-30)

### Checklist técnico
- [ ] Grok Bot logueado en la cuenta de demo (Martín).
- [ ] Agente **Grok Bot meetup** abierto en el chat.
- [ ] Drive `GROKBOT MEETUP` abierto en una pestaña (backlog + agenda).
- [ ] Un segundo agente simple listo (ej. Coach o uno “demo”) por si quieren mostrar multi-agente same-account.
- [ ] HDMI probado; notificaciones OFF; Do Not Disturb ON.
- [ ] Brillo al máximo; tamaño de fuente grande.
- [ ] Plan B: carpeta local `Desktop/Meetup-Demo-Backup/` con 4–6 screenshots del flujo (por si cae wifi/API).
- [ ] Timer visible (reloj del Mac o teléfono en silencio con cuenta regresiva 20:00).

### Qué NO abrir en vivo
- Settings profundos, billing, experimentos a medias.
- Chats privados con datos sensibles de clientes.
- El Inbox de agentes con mails reales de terceros.

---

## Estructura minuto a minuto

| Min | Bloque | Quién |
| --- | --- | --- |
| 0:00–2:00 | Hook + promesa | Martín |
| 2:00–5:00 | Modelo mental (sin slides eternos) | Martín |
| 5:00–12:00 | Demo A — agente del meetup (caso local) | Martín |
| 12:00–17:00 | Demo B — segundo caso rápido | Martín (+ Tobías si ayuda) |
| 17:00–19:00 | Reglas de oro + anti-patrones | Martín |
| 19:00–20:00 | Cierre + puente al Q&A Cursor | Martín |

Si se atrasan: **cortar Demo B**, no el cierre.

---

## 0:00–2:00 — Hook

**Decir (casi textual):**

> En los próximos 20 minutos no vamos a ver otro chatbot de preguntas. Vamos a ver un **compañero de trabajo con computadora propia**: se conecta a tus herramientas, recuerda el contexto, y termina tareas.
> Caso real: este meetup. Parte de la organización la está haciendo un Grok Bot con nosotros.

**Mostrar:** ventana de Grok Bot (sidebar con el agente meetup).

**Promesa de la demo:**

> Al final van a haber visto: (1) qué es un agente, (2) cómo usa Drive de verdad, (3) cómo coordinar trabajo de un evento.

---

## 2:00–5:00 — Modelo mental (3 ideas, no 30)

Solo **tres** conceptos. Contarlos con los dedos:

1. **Agente = rol**  
   No es “el chat de Grok”. Es un rol con memoria, estilo y tareas (meetup, coach, compras…).

2. **Tiene computadora**  
   Navega, lee archivos, usa conectores (Drive, Calendar, Gmail…). No es solo texto.

3. **Rutinas + skills**  
   Puede repetir trabajo solo (schedule) y seguir recetas reutilizables.

**Frase puente:**

> La magia no es que conteste lindo. Es que **haga el trabajo** y vuelva cuando necesita tu OK.

**Evitar:** arquitectura interna, nombres de tools, jerga de agents/MCP.

---

## 5:00–12:00 — Demo A (caso local #1): organizar el meetup

### Setup en pantalla
Chat del agente **Grok Bot meetup** + Drive backlog al lado (dos ventanas).

### Historia (10 s)

> Con Tobías co-organizamos este evento. Las cuentas de Grok Bot son distintas, así que los agentes no se chatean nativo entre cuentas. Resolvimos con un **protocolo en Drive**: backlog + inbox entre agentes.

### Pasos en vivo

1. **Mostrar el backlog** (planilla): Hecho vs Pendiente.  
   Señalar fecha, venue UNNE, speakers, lo que falta (roles, bebidas, check-in…).

2. **Pedirle algo chico al agente en vivo** — prompt listo:

```
Resumí en 5 viñetas qué está Hecho y qué es P0 pendiente en el backlog del meetup. Sé brutalmente concreto. Sin links.
```

3. Mientras responde, narrar:  
   > Está leyendo Drive, no inventando de memoria fría.

4. **Mostrar Inbox agentes** (1 fila SYNC) y el Protocolo (10 s).  
   > Así se coordinan dos organizers con bots en cuentas distintas: misma fuente de verdad.

5. Cierre Demo A:  
   > Esto no es un slide de “AI agenda eventos”. Es el tablero con el que estamos corriendo *este* meetup.

### Si falla la red
- Screenshots previos del backlog / respuesta.
- Seguir narrando; no pelear 2 minutos con el spinner.

---

## 12:00–17:00 — Demo B (caso local #2): elegir UNA

Preparar las tres; el día del evento elegir según energía/wifi.

### Opción B1 — De la idea al artefacto (recomendada)

**Prompt:**

```
Creá un checklist imprimible de recepción para el 16/09 en el Parque Tecnológico UNNE: staff 17:30, check-in 58mm, roles, qué llevar. Corto, markdown.
```

Mostrar el resultado → pedido en lenguaje natural → artefacto usable en la puerta.

### Opción B2 — Multi-agente same-account
Sidebar con varios agentes. En 20 s:  
> Dentro de *tu* cuenta, los bots sí se hablan y pueden laburar en group chat. Entre cuentas distintas, Drive o Slack.

### Opción B3 — Rutina
Mostrar o bosquejar:  
> Cada mañana mirar Inbox del meetup y avisarme solo si hay Needs Human.

> No tenés que recordar pedirle. Él vuelve solo.

---

## 17:00–19:00 — Reglas de oro

1. **Empezá con un rol claro** — “organizás X”, no “sos mi AI genérico”.
2. **Conectá una herramienta de verdad** (Drive, Calendar, mail) o es solo chat bonito.
3. **Fuente de verdad afuera del chat** — planilla, doc, repo.
4. **Pedí evidencia** — links, archivos, resultados.
5. **Vos decidís lo irreversible** — publicar, pagar, mails masivos.

**Anti-patrón:**  
> No es “hacé todo mi laburo mientras scrolleo Instagram”. Es “tomá este outcome, volvé con el draft / el tablero / el blocker”.

---

## 19:00–20:00 — Cierre + puente

> Acaban de ver Grok Bot organizando un meetup real en Corrientes.
> Ahora, a las 19:05, alguien del equipo de **Cursor** para el Q&A.
> Nosotros después seguimos con Tero y Dylo.

**CTA suave (sin hands-on):**  
> Si quieren probar: créense un agente con un rol de *una* semana y conéctenle Drive o Calendar. Empiecen chico.

---

## Frases de rescate

| Situación | Qué decir |
| --- | --- |
| Spinner eterno | Mientras vuelve, miren el backlog — esta es la fuente de verdad. |
| Drive falló | Plan B: les muestro el export de ayer. (screenshot) |
| Pregunta muy técnica | La aparcamos: a las 19:05 está Cursor para eso. |
| Sala fría | ¿A quién le pasó perder media hora pasando tareas de WhatsApp a una planilla? |

---

## Ensayo sugerido

1. Correr Demo A completa en voz alta con cronómetro.
2. Elegir B1/B2/B3 y ensayar solo esa.
3. Un take de pantalla = backup si falla el vivo.
4. Con Tobías: quién salva AV; a los 15:00 avisar “últimos 5”.

---

## Criterio de éxito

- Vieron trabajo real (Drive + agente), no solo definición.
- Quedó clara la diferencia chat vs agente con herramientas.
- El recreo arranca a tiempo para el Q&A Cursor (19:05).

---

*Guion v1 · 12/09/2026 · Grok Bot meetup*
