# Seguridad en Sistemas Informáticos — Tema 1.1

Presentación de la asignatura **Seguridad en Sistemas Informáticos** (Curso 2026/27),
Universidad de Castilla-La Mancha.

Transparencias en LaTeX/Beamer, formato 16:9.

## Contenido

| Fichero | Descripción |
|---|---|
| `presentacion_1.1.tex` | Fuente principal de las transparencias |
| `beamertemplate.sty` | Plantilla Beamer del centro (base Madrid, paleta azul marino) |
| `img/` | Imágenes y diagramas |
| `presentacion_1.1.pdf` | Presentación compilada |

## Compilación

Requiere una distribución TeX con Beamer (TeX Live, MacTeX…):

```sh
latexmk -pdf presentacion_1.1.tex
```

Para limpiar los ficheros auxiliares:

```sh
latexmk -c
```

## Licencia

© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.

El **texto, las transparencias y los diagramas de elaboración propia** se publican bajo
**[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)**
(ver [`LICENSE`](LICENSE)): puedes **compartir y adaptar** el material **citando la autoría**,
**sin uso comercial** y **compartiendo los derivados con la misma licencia**.

**Atribución sugerida:**
> José Luis Martínez (UCLM) — *Seguridad en Sistemas Informáticos, Tema 1.1*, CC BY-NC-SA 4.0.

### Material de terceros (no cubierto por esta licencia)
Algunas imágenes incrustadas **no son de elaboración propia** y **conservan la licencia de
sus autores originales**; la CC BY-NC-SA 4.0 de este repositorio **no** se les aplica. En
concreto `img/s7_2.jpg` e `img/s17_2.jpg`, y cualquier material adaptado de fuentes externas.
Si reutilizas el contenido, respeta los derechos de esos terceros.
