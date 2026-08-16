# Seguridad en Sistemas Informáticos — Tema 3.3

Transparencias (Beamer/LaTeX, 16:9) del **Tema 3.3: Hacking con Metasploit** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: **motivación** y fundamentos de Metasploit, **arquitectura y uso del framework**
(msfconsole, módulos, payloads, Meterpreter), **pentesting con Metasploit** paso a paso,
**vulnerabilidades bien conocidas**, **exploits *in the wild*** y **tips** prácticos.

## Contenido
- `presentacion_3.3.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_3.3.pdf` — presentación compilada (sin metadatos).

> Convertido (texto + **todas** las imágenes + **todos** los hipervínculos) desde el
> `.pptx` original (*4.1 - Hacking con Metasploit*), conservando todas las diapositivas.
> Las imágenes TIFF se convierten a PNG y los comandos con fuente monoespaciada se maquetan
> en formato *script* (`\texttt`). El PDF se genera sin metadatos (build reproducible).

## Compilar
```bash
latexmk -pdf presentacion_3.3.tex
```

> **Nota (Dropbox):** si compilas desde un directorio sincronizado con Dropbox, configura la
> salida de los temporales fuera de Dropbox (`latex-workshop.latex.outDir` → `%TMPDIR%`)
> para evitar errores de E/S.

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
- **Rapid7 / Metasploit** — capturas de msfconsole, módulos y Meterpreter
  ([metasploit.com](https://www.metasploit.com)).
- **Hacking Articles / Ignite Technologies** — capturas de guías de explotación
  ([hackingarticles.in](https://www.hackingarticles.in)).
- **Exploit-DB, Rapid7 y CVE/NVD** — referencias de exploits y vulnerabilidades.
- Capturas de terminal y de laboratorios (Metasploitable2), propiedad de sus autores.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
