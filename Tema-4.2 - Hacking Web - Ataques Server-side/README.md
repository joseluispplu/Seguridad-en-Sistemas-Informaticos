# Seguridad en Sistemas Informáticos — Tema 4.2

Transparencias (Beamer/LaTeX, 16:9) del **Tema 4.2: Hacking Web — Ataques Server-side** de
*Seguridad en Sistemas Informáticos* (UCLM).

Es la **parte servidor** del antiguo tema de Hacking de Aplicaciones Web (dividido en 4.1
cliente / 4.2 servidor), e incluye el cierre común (bypass de WAF/403, escáneres, buenas
prácticas).

Ataques cubiertos: **File Upload**, **Command Injection**, **Path Traversal / LFI / RFI**,
**Log Poisoning**, **XXE**, **NoSQL**, **XPath**, **SSTI**, **SSRF**, **JWT/OAuth/2FA/Auth
Bypass**, **Deserialización**, **Lógica de negocio**, **Host Header**, **HTTP Request
Smuggling**, **Web Cache Poisoning/Deception**, **Race Conditions**, **Control de acceso /
IDOR**, **APIs/GraphQL/LLMs**, **CMS** (WordPress/Joomla/Drupal) y **Cloud (AWS)**.

## Contenido
- `presentacion_4.2.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla · `img/` — imágenes · `presentacion_4.2.pdf` — PDF.

> Convertido desde el `.pptx` original conservando texto, **todas** las imágenes e
> hipervínculos. PDF sin metadatos.

## Compilar
```bash
latexmk -pdf presentacion_4.2.tex
```

## Licencia
© 2026 José Luis Martínez — UCLM. Texto propio bajo **CC BY-NC-SA 4.0** (ver `LICENSE`);
las imágenes de terceros conservan la licencia de sus autores.
