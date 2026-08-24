# Prompt Toolkit

Sistema de trabajo con IA para equipos B2B. No es una lista de prompts: son tres capas.

1. **Perfil de empresa** — ICP, tono de voz, oferta, pruebas citables y frases prohibidas.
   Se rellena una vez y se inyecta solo en cada prompt. Se exporta como archivo JSON para que
   todo un equipo trabaje con el mismo contexto, sin servidor y sin cuentas.
2. **Flujos encadenados** — «Lanzar una campaña» son cinco pasos (brief → mensajes clave → post
   → email → one-pager) donde cada paso hereda automáticamente lo que produjo el anterior.
3. **Criterio de calidad** — cada una de las 17 salidas trae su lista de comprobación y un prompt
   revisor que audita el texto contra esos mismos criterios.

17 prompts en cinco categorías: campaña, contenido, comunicación interna, reuniones y estrategia.

Bilingüe (ES/EN). Un solo `index.html`, sin paso de compilación. Todo lo que escribe quien la
usa se queda en su navegador.

- **Versión actual:** https://sarauter.com/Prompt-Toolkit/
- **Versión 1, archivada:** https://sarauter.com/Prompt-Toolkit/v1/ — 16 prompts sueltos con
  formulario y botón de copiar. Se conserva viva porque la comparación entre las dos es
  parte de lo que la herramienta cuenta.
