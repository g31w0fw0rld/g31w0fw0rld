# Hi / Hola 👋

I'm **g31w0fw0rld**. I make software and userscripts, and share guides and content about games and programs (maybe streams someday). I'm just starting out and growing. I'll do what I can for you —support me if you want—; and if a cause needs it more than I do, help that one instead.

Soy **g31w0fw0rld**. Hago software y userscripts, y comparto guías y contenido sobre juegos y programas (quizá streams a futuro). Estoy empezando y creciendo. Haré lo que pueda por ti —apóyame si quieres—; y si hay una causa que lo necesite más que yo, ayúdala a ella.

---

## 🧩 Userscripts

Install with [Tampermonkey](https://www.tampermonkey.net/). Each one ships screenshots and a full description of what it does in its README, in English and Spanish, and the ones with a panel explain the same inside the page. / Instálalos con [Tampermonkey](https://www.tampermonkey.net/). Cada uno trae capturas y la descripción completa de sus funciones en su README, en inglés y español, y los que tienen panel explican lo mismo dentro de la página.

### 🎮 Stores & prices / Tiendas y precios

All of them link to the exact product page rather than a search, except where the destination only offers a search. / Todos enlazan a la ficha del producto exacto, no a una búsqueda, salvo donde el destino solo ofrece buscador.

- **[Steam to SteamDB Button](https://github.com/g31w0fw0rld/steam-to-steamdb-button)** — SteamDB button on games, bundles and packages. / Botón a SteamDB en juegos, bundles y paquetes.
- **[GOG to GOGDB Button](https://github.com/g31w0fw0rld/gog-to-gogdb-button)** — GOGDB button on game pages. / Botón a GOGDB en las páginas de juego.
- **[Epic Games Store to EGData](https://github.com/g31w0fw0rld/epic-games-store-to-egdata)** — EGData button under every purchase button, plus a discount filter, remembered sort and a shareable link on your wishlist. / Botón a EGData bajo cada botón de compra, más filtro de ofertas, orden recordado y enlace compartible en la lista de deseos.
- **[GGDeals → PCGamingWiki](https://github.com/g31w0fw0rld/ggdeals-to-pcgamingwiki)** — PCGamingWiki button on games, packs and DLC, PC only. / Botón a PCGamingWiki en juegos, packs y DLC, solo en PC.
- **[PCGamingWiki → GGDeals](https://github.com/g31w0fw0rld/pcgamingwiki-to-ggdeals)** — direct link and title search on GG.deals, next to "Availability". / Enlace directo y búsqueda en GG.deals junto a «Availability».
- **[Humble Bundle Tools](https://github.com/g31w0fw0rld/humble-bundle-tools)** — wishlist sorting and filters, plus GG.deals and PCGamingWiki buttons on PC products. / Orden y filtros en la lista de deseos, más botones a GG.deals y PCGamingWiki en productos de PC.
- **[Microsoft Store Locale Redirect](https://github.com/g31w0fw0rld/microsoft-store-locale-redirect)** — 21 locales to see prices in the region you pick, plus wishlist tools. / 21 locales para ver precios en la región que elijas, y herramientas de lista de deseos.
- **[Xbox Store Locale Redirect](https://github.com/g31w0fw0rld/xbox-store-locale-redirect)** — the same for the Xbox Store. / Lo mismo para Xbox Store.

### 📺 Streaming & drops / Streaming y drops

Both work the same way: they highlight the campaigns matching your keywords on the page itself, tell you exactly how much watch time is left —something neither site gives you— and flag what changed. Kick also handles the daily reward chest, which is not a drop. / Los dos funcionan igual: resaltan en la propia página las campañas que coinciden con tus palabras clave, te dicen el tiempo de visualización que falta exactamente —dato que ninguna de las dos webs da— y avisan de lo que cambió. Kick lleva además el cofre de recompensa diaria, que no es un drop.

- **[Twitch Drops Highlighter](https://github.com/g31w0fw0rld/twitch-drops-highlighter)** — 16 languages, read-only queries. / 16 idiomas, consultas de solo lectura.
- **[Kick Drops Highlighter](https://github.com/g31w0fw0rld/kick-drops-highlighter)** — 16 languages, read-only queries. / 16 idiomas, consultas de solo lectura.

### 🧰 Others / Otros

- **[YouTube Channel Tools](https://github.com/g31w0fw0rld/youtube-channel-tools)** — favorite and avoid channel lists on videos, Shorts and mobile, with the dislike count restored and three privacy modes. Auto-actions are optional and off by default. ⚠️ / Canales favoritos y a evitar en vídeos, Shorts y móvil, con el conteo de dislikes recuperado y tres modos de privacidad. Las auto-acciones son opcionales y vienen apagadas. ⚠️
- **[Indiegala Giveaway Bulk Tools](https://github.com/g31w0fw0rld/indiegala-bulk-join)** — a reorderable ticket queue that queues beyond your balance, a GalaSilver widget, prize checking and wheel alerts. ⚠️ / Cola de boletos reordenable que encola aunque no te alcance el saldo, widget de GalaSilver, revisión de premios y avisos de la ruleta. ⚠️
- **[Bing Rewards Auto Search](https://github.com/g31w0fw0rld/bing-rewards-auto-search)** — daily searches for Microsoft Rewards, with your own keywords and humanised pacing. ⚠️ / Búsquedas diarias para Microsoft Rewards, con palabras clave propias y ritmo humanizado. ⚠️

⚠️ = automates an action the site's terms may not permit; the full warning is in its README. / Automatiza una acción que las condiciones del sitio pueden no permitir; el aviso completo está en su README.

Also on / También en: **[GreasyFork](https://greasyfork.org/es-419/users/1590477-g31w)** · **[OpenUserJS](https://openuserjs.org/users/g31w0fw0rldgmail.com/scripts)**

---

## 🔒 Privacy & security / Privacidad y seguridad

Everything runs in your browser: no script sends data to me, and none carries telemetry
or analytics. Each one states in its README —and in its info panel, where it has one—
what it stores and where it connects, and requests the minimum permissions (`@grant`,
`@connect`) it needs. The ones that talk to the site's own API do so **read-only**,
reusing your session: *Kick Drops Highlighter* makes a single `GET` to the progress
endpoint and *Twitch Drops Highlighter* sends three GraphQL queries and no mutation, so
neither writes anything to your account. Where something is claimed or pressed for you,
it is done on the site's own buttons, never through an API. Where a third party is
involved I name it: *YouTube Channel Tools* queries Return YouTube Dislike (and you can
turn it off), and *Twitch Drops Highlighter* falls back to a public drops API only if the
Twitch query fails. The scripts are meant to be read top to bottom: they are commented
and carry no dead code. Found a security problem? Open an issue.

Todo se procesa en tu navegador: ningún script me envía datos a mí, y ninguno lleva
telemetría ni analítica. Cada uno declara en su README —y en su panel de información,
si lo tiene— qué guarda y a dónde se conecta, y pide los permisos (`@grant`, `@connect`)
mínimos que necesita. Los que hablan con la API del propio sitio lo hacen **solo para
leer**, reusando tu sesión: *Kick Drops Highlighter* hace un único `GET` al endpoint de
progreso y *Twitch Drops Highlighter* manda tres consultas GraphQL y ninguna mutación,
así que no escriben nada en tu cuenta. Donde algo se reclama o se pulsa por ti, se hace
sobre los botones del propio sitio, nunca por API. Cuando hace falta un tercero lo digo
con nombre: *YouTube Channel Tools* consulta Return YouTube Dislike (y puedes
desactivarlo), y *Twitch Drops Highlighter* recurre a una API pública de drops solo si
falla la consulta a Twitch. Los scripts se pueden leer de arriba abajo a propósito: van
comentados y sin código muerto. Si encuentras un problema de seguridad, ábreme un issue.

---

## 🔜 Coming soon / Próximamente
A **multi-tool for PSP and PS Vita**. / Una **multiherramienta para PSP y PS Vita**.

## ☕ Support / Apoyar
If something helps you and you'd like to support it: **[ko-fi.com/g31w0fw0rld](https://ko-fi.com/g31w0fw0rld)** —only if you want—.
Si algo te sirve y quieres apoyar: **[ko-fi.com/g31w0fw0rld](https://ko-fi.com/g31w0fw0rld)** —solo si quieres—.
