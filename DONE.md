# Panadería Hogaza — completado

Landing estática en index.html, styles.css y script.js. Sin build ni dependencias de ejecución. Servir el directorio con cualquier servidor estático, por ejemplo `python3 -m http.server 8080`.

Incluye navegación, hero, tres fotos de panes/obrador, proceso, horarios explícitamente demo, WhatsApp +54 11 5555-0505 y footer Demo conceptual. Favicon SVG propio, meta noindex/nofollow, robots.txt que permite leer el noindex y _headers con X-Robots-Tag para hosts compatibles (otros servidores deben configurar ese header). Tipografía Google Fonts con fallback local.

Cuatro imágenes creadas con la herramienta integrada imagegen y guardadas en assets/images/: hero-hogaza.png, horno.png, mostrador.png, masa.png. Prompts completos en assets/images/prompts.json. No se usaron imágenes externas ni se publicó el sitio.

QA: Chrome headless con Playwright, vistas 390 y 1280 px, capturas completas y revisión visual. Un h1, sin overflow horizontal, sin errores JS. Control de vapor probado con aria-pressed y reduced-motion oculta animación y control. Imágenes bajo el pliegue usan lazy loading; comprobación tras scroll. Navegación por anclas, skip link, focos visibles y enlaces WhatsApp con destino correcto. No se envió ningún mensaje. No se hizo auditoría exhaustiva de accesibilidad ni se comprobó la existencia del teléfono demo.

Referencias y decisiones: spec.md. No se utilizó git.
