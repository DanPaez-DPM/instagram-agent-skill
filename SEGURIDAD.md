# Revisión de seguridad (Estudio PotenciArg, 2026-10-21)

Esta rama es una reescritura a mano de cuatro skills del repo original (MIT, Jakeschincariol/instagram-agent-skill). Se eliminaron los scripts Python, el plugin y las listas de datos del original: no se instala nada que no se haya leído línea por línea.

Qué se revisó y qué se encontró en el original: ver `tablero/criterios-skills-externas.md` del estudio.

En esta rama:
- Solo archivos de texto (`SKILL.md`, `rubric.json`). Sin código ejecutable, sin red, sin credenciales.
- Ninguna skill publica, envía ni inicia sesión. Todo pasa por el OK de Dani.
- Cada skill se limita a redactar o analizar texto que una persona pega.
