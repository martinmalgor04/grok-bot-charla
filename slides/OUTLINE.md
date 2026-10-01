# Outline de slides — Grok Bot

Charla del viernes 2 oct 2026 · español (Argentina) · 30–40 min.

Base: `guion/GUION-workshop-grok-bot.md` (meetup Corrientes, 16/09, bloque de 20 min). Este outline estira esa columna. No reemplaza el deck oficial de Ambassadors: ese archivo todavía no está en el repo (`refs/ASSETS-oficiales.md`).

Si hay que comprimir a 30 min: hook 3, modelo 5, demo A 10, demo B 6, reglas 4, cierre 2. Si hay aire hasta 40, usá los tiempos de abajo. Si se atrasan, cortá la Demo B, no el cierre.

Los datos de sala del 16/09 (UNNE, Q&A de Cursor a las 19:05, Tero y Dylo, Tobías en AV) quedan marcados para reescribir. No inventar el programa del viernes.

---

## 1. Hook (0:00–4:00)

### No es otro chatbot

- En los próximos minutos no vemos un chatbot de preguntas.
- Vemos un compañero de trabajo con computadora propia.
- Se conecta a tus herramientas, recuerda el contexto y termina tareas.

### El caso que abre

- Parte de organizar un evento real la hizo un Grok Bot junto con el equipo.
- En el guión del 16/09 el caso es el meetup de Corrientes. Para el viernes, usar el mismo mecanismo con el ejemplo que esté vivo ese día.

### Promesa

Al final van a haber visto tres cosas:

1. Qué es un agente.
2. Cómo usa una herramienta de verdad (Drive).
3. Cómo se coordina un trabajo concreto, no un slide de “AI para eventos”.

Mostrar la ventana de Grok Bot con el agente en el sidebar. Nada de settings ni de billing.

---

## 2. Modelo mental — 3 ideas (4:00–10:00)

### Solo tres conceptos

Contarlos con los dedos. Sin arquitectura interna, sin nombres de tools y sin jerga de MCP.

### 1. Agente = rol

- No es “el chat de Grok”.
- Es un rol con memoria, estilo y tareas: meetup, coach, compras.

### 2. Tiene computadora

- Navega, lee archivos y usa conectores (Drive, Calendar, Gmail).
- No es solo texto.

### 3. Rutinas + skills

- Puede repetir trabajo solo (un schedule).
- Sigue recetas reutilizables.

### Frase puente

- La magia no es que conteste lindo.
- Es que haga el trabajo y vuelva cuando necesita tu OK.

---

## 3. Demo A — agente con una fuente de verdad (10:00–20:00)

### Setup

- Chat del agente con rol claro, y el Drive (backlog) al lado.
- Historia, en diez segundos: dos cuentas de Grok Bot no se chatean entre sí. La coordinación es un protocolo en Drive: backlog + inbox.

### Qué se ve en pantalla

1. Backlog: Hecho vs P0 pendiente (fecha, venue, speakers, lo que falta).
2. Un pedido chico, en vivo, con este prompt:

   > Resumí en 5 viñetas qué está Hecho y qué es P0 pendiente en el backlog del meetup. Sé brutalmente concreto. Sin links.

3. Mientras responde: está leyendo Drive, no inventando de memoria fría.
4. Una fila del inbox de agentes y el protocolo (10 s): misma fuente de verdad para organizers con cuentas distintas.

### Cierre de la demo

- No es un slide de “AI agenda eventos”.
- Es el tablero con el que se está corriendo el trabajo.

### Si falla la red

- No pelear dos minutos con el spinner.
- Plan B: screenshots en `demos/backup/` (fuera de git).
- Datos de la demo: nada de clientes, nada de mails de terceros.

---

## 4. Demo B — elegir una (20:00–30:00)

Preparar las tres. El día de la charla se elige una, según energía y wifi.

### B1 — De la idea al artefacto (recomendada)

Pedido en lenguaje natural → markdown usable en la puerta.

> Creá un checklist imprimible de recepción: staff, check-in 58 mm, roles, qué llevar. Corto, markdown.

En el guión del 16/09 el venue es Parque Tecnológico UNNE. Cambiá fecha y lugar solo cuando estén confirmados para el viernes.

### B2 — Multi-agente en la misma cuenta

- En el sidebar, varios agentes.
- Dentro de tu cuenta se hablan y pueden laburar en un group chat.
- Entre cuentas distintas, Drive o Slack.

### B3 — Rutina

- Cada mañana mira el inbox y avisa solo si hay algo que necesita un humano.
- No tenés que recordar pedirle. Vuelve solo.

---

## 5. Reglas de oro (30:00–36:00)

### Cinco reglas

1. Empezá con un rol claro. “Organizás X”, no “sos mi AI genérico”.
2. Conectá una herramienta de verdad (Drive, Calendar, mail) o es solo un chat lindo.
3. La fuente de verdad vive afuera del chat: planilla, doc o repo.
4. Pedí evidencia: links, archivos, resultados.
5. Vos decidís lo irreversible: publicar, pagar, mails masivos.

### Anti-patrón

- No es “hacé todo mi laburo mientras scrolleo”.
- Es “tomá este outcome y volvé con el draft, el tablero o el blocker”.

---

## 6. Cierre (36:00–40:00)

### Qué acaban de ver

- Trabajo real (Drive + agente), no solo una definición.
- La diferencia entre un chat y un agente con herramientas.

### CTA

- Créense un agente con el rol de una semana.
- Conéctenle Drive o Calendar.
- Empiecen chico.

### Puente a reescribir

El guión del 16/09 cierra con el Q&A de Cursor a las 19:05 y nombra a Tero y Dylo. Esa frase es de ese meetup. Para el viernes 2/10, reemplazarla cuando exista el programa de la sala. No inventar el cierre.

---

## Qué no va en estas slides

- Settings, billing, experimentos a medias.
- Chats con datos de clientes o inbox con mails de terceros.
- Logos, paleta o taglines oficiales que no estén en `refs/` o `assets/`.
- Un PPTX presentado como el deck de Ambassadors.
