# Seguridad en Sistemas Informáticos — Tema 2.2

Transparencias (Beamer/LaTeX, 16:9) del **Tema 2.2: Escaneo y Técnicas de Evasión** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: **escaneo y fingerprinting pasivo y activo**, **Nmap** y el **Nmap Scripting Engine
(NSE)**, **netcat** (banner grabbing, transferencia de ficheros, shells) y **técnicas de
evasión** de firewalls/IDS.

## Contenido
- `presentacion_2.2.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_2.2.pdf` — presentación compilada.

> Convertido (texto + **todas** las imágenes + **todos** los hipervínculos) desde el
> `.pptx` original, conservando todas las diapositivas. Algunos títulos auto-detectados
> pueden requerir un retoque manual fino.

## Compilar
```bash
latexmk -pdf presentacion_2.2.tex
```

> **Nota (Dropbox):** si compilas desde un directorio sincronizado con Dropbox, configura la
> salida de los temporales fuera de Dropbox (ver `.vscode/settings.json` en la raíz del
> repositorio: `latex-workshop.latex.outDir` → `%TMPDIR%`) para evitar errores de E/S.

## Licencia
© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.
Texto y materiales propios bajo **CC BY-NC-SA 4.0** (ver [`LICENSE`](LICENSE)); las
imágenes de terceros conservan la licencia de sus autores originales.

## Créditos de imágenes (material de terceros)
Estas transparencias, con fines **exclusivamente docentes**, incluyen capturas de
herramientas y guías cuya autoría corresponde a terceros. Se citan sus fuentes; **cada una
conserva los derechos de su autor** y **no** queda cubierta por la licencia CC de este
repositorio. Si algún titular desea que se retire su material, se hará de inmediato.

Fuentes principales:
- **Hacking Articles / Ignite Technologies** — capturas de guías de Nmap/netcat/evasión
  ([hackingarticles.in](https://www.hackingarticles.in)).
- **Nmap** (Gordon Lyon) — capturas de la herramienta y del NSE ([nmap.org](https://nmap.org)).
- Capturas de terminal (netcat, escaneos) y de otras herramientas, propiedad de sus autores.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
