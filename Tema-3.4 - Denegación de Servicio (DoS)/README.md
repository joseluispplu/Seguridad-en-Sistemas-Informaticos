# Seguridad en Sistemas Informáticos — Tema 3.4

Transparencias (Beamer/LaTeX, 16:9) del **Tema 3.4: Denegación de Servicio (DoS)** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: **ataques volumétricos**, **ataques de consumo** de recursos, **buffer overflow**,
**botnets** (DDoS), y **herramientas y ejemplos** prácticos.

## Contenido
- `presentacion_3.4.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_3.4.pdf` — presentación compilada (sin metadatos).

> Convertido (texto + **todas** las imágenes + **todos** los hipervínculos) desde el
> `.pptx` original, conservando todas las diapositivas. El PDF se genera sin metadatos
> (build reproducible). Algunos títulos auto-detectados pueden requerir un retoque manual
> fino.

## Compilar
```bash
latexmk -pdf presentacion_3.4.tex
```

> **Nota (Dropbox):** si compilas desde un directorio sincronizado con Dropbox, configura la
> salida de los temporales fuera de Dropbox (`latex-workshop.latex.outDir` → `%TMPDIR%`)
> para evitar errores de E/S.

## Licencia
© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.
Texto y materiales propios bajo **CC BY-NC-SA 4.0** (ver [`LICENSE`](LICENSE)); las
imágenes de terceros conservan la licencia de sus autores originales.

## Créditos de imágenes (material de terceros)
Estas transparencias, con fines **exclusivamente docentes**, incluyen imágenes y capturas
cuya autoría corresponde a terceros. Se citan sus fuentes; **cada una conserva los derechos
de su autor** y **no** queda cubierta por la licencia CC de este repositorio. Si algún
titular desea que se retire su material, se hará de inmediato.

Fuentes principales:
- **Hacking Articles / Ignite Technologies** — capturas de guías de DoS/DDoS
  ([hackingarticles.in](https://www.hackingarticles.in)).
- **Herramientas** (capturas): hping3, LOIC/HOIC, Slowloris, GoldenEye y otras — marcas y
  capturas de sus respectivos autores.
- Diagramas ilustrativos (botnets, tipos de ataque) de sus autores originales.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
