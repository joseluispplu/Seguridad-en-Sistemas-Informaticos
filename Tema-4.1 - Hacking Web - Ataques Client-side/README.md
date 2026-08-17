# Seguridad en Sistemas Informáticos — Tema 4.1

Transparencias (Beamer/LaTeX, 16:9) del **Tema 4.1: Hacking Web — Ataques Client-side** de
*Seguridad en Sistemas Informáticos* (UCLM).

Es la **parte cliente** del antiguo tema de Hacking de Aplicaciones Web (dividido en 4.1
cliente / 4.2 servidor). Incluye además los **fundamentos y herramientas** comunes
(introducción, OWASP Top 10, footprinting web, Burp Suite, HackBar, laboratorio).

Ataques cubiertos: **XSS** (reflejado, almacenado, DOM, CSP, avanzados, RCE vía XSS, captura
de credenciales/NTLM, session hijacking), **CSRF**, **Clickjacking**, **vulnerabilidades
basadas en DOM** (postMessage, DOM clobbering), **Open Redirect**, **CORS**, **HTML
Injection**, **Prototype Pollution (cliente)** y **WebSockets**.

## Contenido
- `presentacion_4.1.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla · `img/` — imágenes · `presentacion_4.1.pdf` — PDF.

> Convertido desde el `.pptx` original conservando texto, **todas** las imágenes e
> hipervínculos. PDF sin metadatos.

## Compilar
```bash
latexmk -pdf presentacion_4.1.tex
```

## Licencia
© 2026 José Luis Martínez — UCLM. Texto propio bajo **CC BY-NC-SA 4.0** (ver `LICENSE`);
las imágenes de terceros conservan la licencia de sus autores.
