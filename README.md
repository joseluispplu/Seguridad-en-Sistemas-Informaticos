# Seguridad en Sistemas Informáticos

Materiales de la asignatura **Seguridad en Sistemas Informáticos** (Universidad de
Castilla-La Mancha). Cada tema cuelga de su propia carpeta, con las transparencias en
LaTeX/Beamer (formato 16:9) y el PDF compilado.

## Estructura

Cada tema es una carpeta autocontenida (fuente `.tex`, plantilla, imágenes y PDF):

```
Seguridad-en-Sistemas-Informaticos/
├── tema-1.1/          Presentación de la Asignatura
│   ├── presentacion_1.1.tex
│   ├── beamertemplate.sty
│   ├── img/
│   └── presentacion_1.1.pdf
└── ...                (se irán añadiendo el resto de temas)
```

## Índice de temas

| Tema | Título | Carpeta |
|------|--------|---------|
| 1.1 | Presentación de la Asignatura | [`tema-1.1/`](tema-1.1/) |
| 1.2 | Introducción a la Seguridad Informática y de la Información | [`tema-1.2/`](tema-1.2/) |
| 1.3 | Montaje de un Laboratorio de Ciberseguridad | [`tema-1.3/`](tema-1.3/) |

*(el resto de temas se irán publicando conforme se conviertan a LaTeX)*

## Compilar un tema

Requiere una distribución TeX con Beamer (TeX Live / MacTeX):

```bash
cd tema-1.1
latexmk -pdf presentacion_1.1.tex
```

## Licencia

© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.

El **texto, las transparencias y los diagramas de elaboración propia** se publican bajo
**[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** (ver [`LICENSE`](LICENSE)):
compartir y adaptar **citando la autoría**, **sin uso comercial** y con **share-alike**.
Las imágenes de terceros incrustadas conservan la licencia de sus autores originales
(ver el README de cada tema).
