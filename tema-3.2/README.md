# Seguridad en Sistemas Informáticos — Tema 3.2

Transparencias (Beamer/LaTeX, 16:9) del **Tema 3.2: Ingeniería Social** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: **vectores de ataque**, ataques **basados en humanos** y **basados en computadores**,
**phishing** (y sus variantes), **phishing avanzado** (AiTM, *device code*, BitB, ClickFix,
*deepfakes*), **protección frente al phishing** y **educación y concienciación**.

Incluye además una tabla comparativa de las variantes de phishing, una transparencia de
**casos reales** (RSA, Ubiquiti, Twitter, MGM, Arup, Storm-2372), una guía de **respuesta
ante el incidente** con los canales de denuncia en España (INCIBE-CERT, 017, AEPD, Policía)
y un **glosario** español–inglés de los anglicismos del tema.

## Contenido
- `presentacion_3.2.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_3.2.pdf` — presentación compilada.

> Convertido (texto + **todas** las imágenes + **todos** los hipervínculos y referencias)
> desde el `.pptx` original, conservando todas las diapositivas.

### Convenciones de estilo
- `\cmd{...}` — comandos, rutas, ficheros y literales, en monoespaciado y color de la plantilla.
- `\cmdbox{...}` — líneas de comando completas, en un recuadro destacado.
- `\term{...}` — anglicismos y términos técnicos en inglés (cursiva). Centraliza el estilo:
  cambiando esa única definición se recolorea o recompone todo el tema.
- `\lead{...}` — encabezado de apartado dentro de una transparencia.
- `\fuente{...}` — nota de fuente o referencia al pie, en cuerpo pequeño.

Las imágenes se dimensionan con `keepaspectratio` y un límite de altura relativo a
`\textheight`. El máximo aprovechable en una transparencia con título es **`0.845\textheight`**
(por encima de ese valor LaTeX avisa con `Overfull \vbox`); las transparencias sin título
(`[plain]`) admiten `\textheight` completo.

## Compilar
```bash
latexmk -pdf presentacion_3.2.tex
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
- **Hacking Articles / Ignite Technologies** — capturas de guías de ingeniería social y
  phishing ([hackingarticles.in](https://www.hackingarticles.in)).
- **Herramientas** (capturas): SET (Social-Engineer Toolkit), Gophish, SocialFish, EvilURL,
  msfvenom y otras — marcas y capturas de sus respectivos autores.
- Capturas de campañas y de resultados de las herramientas, propiedad de sus autores.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
