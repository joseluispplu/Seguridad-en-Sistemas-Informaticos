# Seguridad en Sistemas Informáticos — Tema 3.1

Transparencias (Beamer/LaTeX, 16:9) del **Tema 3.1: Ataques a las credenciales** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: **ataques basados en diccionario** (Hydra, Medusa…), **fuerza bruta**, **ataques
offline** (cracking de hashes con John the Ripper / Hashcat, reglas, máscaras, PassGAN),
y **malware** de robo de credenciales.

## Contenido
- `presentacion_3.1.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_3.1.pdf` — presentación compilada.

> Convertido (texto + **todas** las imágenes + **todos** los hipervínculos) desde el
> `.pptx` original, conservando todas las diapositivas. Los **comandos** se detectan por su
> fuente monoespaciada y se maquetan en formato *script* (`\texttt`). Algunos títulos
> auto-detectados pueden requerir un retoque manual fino.

## Compilar
```bash
latexmk -pdf presentacion_3.1.tex
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
- **Hacking Articles / Ignite Technologies** — capturas de guías de cracking de credenciales
  ([hackingarticles.in](https://www.hackingarticles.in)).
- **Herramientas** (capturas): Hydra, Medusa, John the Ripper, Hashcat, PassGAN y otras —
  marcas y capturas de sus respectivos autores.
- Capturas de terminal y de resultados de las herramientas, propiedad de sus autores.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
