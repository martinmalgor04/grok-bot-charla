# Prompt — pack completo Grok Bot (media + charla)

Copiá todo desde “INSTRUCCIÓN” hacia abajo y pegalo en Claude Code / Cursor / ChatGPT.

---

## INSTRUCCIÓN

Sos mi productor de la charla **Grok Bot** (viernes 2 oct 2026, Argentina). Tenés que armar / adaptar material usando SOLO los recursos listados abajo. No inventes logos, paleta, taglines ni un deck “oficial” en español: **no existe deck oficial ES**. Usá el deck EN + guión ES.

### Contexto
- Presentador: Martín Manuel Malgor (SpaceXAI / Cursor Ambassador, Corrientes).
- Idioma: español Argentina (vos).
- Duración objetivo: 30–40 min (base: guión meetup 16/09 de 20 min).
- Repo de trabajo: https://cursor.com/codebase/martinmmalgor/grok-bot-charla (privado Origin).
- Estrategia viernes: proyectar **deck oficial EN (Google Slides)** y narrar con **guión ES** + outline ES.

### Qué quiero que hagas (elegí según mi pedido del momento)
1. Adaptar el guión 20 min → 30–40 min (archivo nuevo al lado del original; no pisar el del meetup).
2. Pulir `slides/OUTLINE.md` alineado al guión del viernes.
3. Checklist demos en vivo + prompts listos (sin datos de clientes).
4. Si pido piezas gráficas: usar solo tools/links oficiales o community de abajo; no inventar branding.
5. Entregar en markdown listo para usar (guión, outline, prompts). Nada de PPTX inventado.

### Reglas duras
- No inventar PPTX/PDF “oficiales”.
- No inventar branding Cursor/Grok Bot fuera de los assets listados.
- No asumir venue/Q&A del meetup 16/09 (UNNE, Q&A Cursor 19:05, Tero/Dylo) para el viernes sin confirmar.
- Demos: cuenta limpia, sin billing, sin mails de terceros, sin settings.
- Si falta un asset: decir qué falta y el link; no fabricarlo.

---

## PRESENTACIONES Y DOCS OFICIALES

- Hub assets Ambassadors (Notion público): https://cursorambassadors.notion.site/Grok-Bot-assets-3c5ba798b53c8080a44ae0b7d93f19c2
- Sección slides Ben (Notion app): https://app.notion.com/p/cursorambassadors/Grok-Bot-assets-3c5ba798b53c8080a44ae0b7d93f19c2?source=copy_link#3d3ba798b53c801b9603fbb417d8bdde
- **Deck oficial Grok Bot (Google Slides, EN):** https://docs.google.com/presentation/d/1IPXSSmoHyRdj_KXaHumtAsuekV08TgqO3zrMgZ7DjcA/edit?usp=sharing
- Deck general ambassadors (Google Slides): https://docs.google.com/presentation/d/1iUeO2H-NlcfEzl5Z1Yf66tUlJ3Q58gSf1lTBzPKPAbM/edit
- Guion workshop (Google Doc): https://docs.google.com/document/d/1drd8svveVFhc-SnG8uzdsUeZhFqkKXLqOc_VN18aQL0/edit
- Cards Notion (anchor): `#3c5ba798b53c803d8fc0e1f6c303f0b7` en el hub
- Thumbnails Luma (Figma): https://www.figma.com/design/3PcKyybEoc6SAqysnCb5HA/Grok-Bot-thumbnails--temp-?node-id=0-1
- Credit QR time-based: Ben manda URL tipo `cursor.com/grokbot{ciudad}` (pedir si falta)

---

## HERRAMIENTAS / GENERADORES

- Thumbnail tool (oficial-ish): https://grok-bot-thumbnail-tool.vercel.app/
- Thumbnail tool (alt community): https://cursor-thumbnail-tool.vercel.app/
- xaievents graphics (fotos/stories SpaceXAI): https://xaievents.vercel.app/
- Landing meetup template: https://grok-bot-meetup.vercel.app/
- Cafe Cursor asset generator: https://cafe-cursor-two.vercel.app
- Welcome screen: https://spacexai-welcome.vercel.app/
- grokbot-wall: https://github.com/bchewy/grokbot-wall
- Deck template community: https://github.com/agrimsingh/cursor-deck-template
- Ejemplo credit claim Floripa: https://cursorfloripa.space/ + https://github.com/ArturoRiosMock/cafe-cursor

---

## ASSETS LOCALES YA BAJADOS (oficiales Ambassadors)

Pack `Grok Bot Assets_Ambassador` (stickers + banner + colores):

- Colores producción: `GrokBot_Colors_for Production.pdf`
- Stickers pre-selected (AI master + exports):
  - Color SVGs: `GrokBot_StickerSet_GrokBot-01` … `-12.svg`
  - Wordmark Part01 / Part02 (color y B/W)
  - B/W set completo
  - Master: `PreSelected_GrokBot_StickerSet.ai`
- Banner 2×6 ft:
  - `GrokBot-Banner-2x6ft.ai` + `.fig`
  - Fonts trial UniversalSansGrokTest (Display/Text pesos 250–600 + italics)
- Zip Notion: `Grok Bot Assets_Ambassador.zip`

## ASSETS PÚBLICOS YA BAJADOS (no oficiales Ambassadors)

- xaievents: logos SpaceXAI (color/black), upload UI, placeholders story/post
- Cafe Cursor: `cafe-horizontal_cafe_cursor_logo.svg`, `cafe-small_cursor_logo.svg`
- Landing meetup: favicons
- Nota: los bots Grok de xaievents se renderizan en canvas; no hay PNG del bot público descargable

---

## CONTENIDO DE CHARLA YA ESCRITO (usar como fuente)

### Modelo mental (3 ideas)
1. Agente = rol (memoria, estilo, tareas), no “el chat de Grok”.
2. Tiene computadora (Drive, Calendar, Gmail, archivos).
3. Rutinas + skills.

Frase puente: la magia no es contestar lindo; es **hacer el trabajo** y volver cuando necesita OK.

### Estructura sugerida 30–40 min
| Bloque | Min (40) | Min (30) |
| --- | --- | --- |
| Hook | 0–4 | 0–3 |
| Modelo mental | 4–10 | 3–8 |
| Demo A (fuente de verdad) | 10–20 | 8–18 |
| Demo B (elegir una) | 20–30 | 18–24 |
| Reglas de oro | 30–36 | 24–28 |
| Cierre | 36–40 | 28–30 |

Si se atrasan: cortar Demo B, no el cierre.

### Demo A — prompt en vivo
```
Resumí en 5 viñetas qué está Hecho y qué es P0 pendiente en el backlog del meetup. Sé brutalmente concreto. Sin links.
```

### Demo B — opciones
- B1 (recomendada): idea → checklist recepción markdown
- B2: multi-agente same-account
- B3: rutina matutina “solo si Needs Human”

### Reglas de oro
1. Rol claro.
2. Conectar una herramienta real.
3. Fuente de verdad afuera del chat.
4. Pedir evidencia.
5. Humano decide lo irreversible.

### Anti-patrón
No es “hacé todo mi laburo mientras scrolleo”. Es “tomá este outcome y volvé con draft / tablero / blocker”.

### CTA
Crear un agente con rol de una semana + Drive o Calendar. Empezar chico.

---

## REPO / ARCHIVOS CLAVE

- `guion/GUION-workshop-grok-bot.md` — guión meetup 16/09 (20 min)
- `slides/OUTLINE.md` — outline ES 30–40 min (en Origin main; puede faltar en clones viejos)
- `demos/CHECKLIST-demo.md`
- `refs/ASSETS-oficiales.md`
- `CLAUDE.md` — instrucciones cortas para el agente del repo
- `PROMPT-pack-completo.md` — este archivo

---

## FORMATO DE RESPUESTA
Empezá por el entregable pedido. Español Argentina. Corto cuando se pueda; largo solo en guión/outline. Marcá claramente qué es oficial EN vs guión ES vs community.
