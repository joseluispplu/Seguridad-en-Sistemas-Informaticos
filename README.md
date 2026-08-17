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
| 1.1 | Presentación de la Asignatura | [`Tema-1.1 - Presentación de la Asignatura/`](Tema-1.1%20-%20Presentación%20de%20la%20Asignatura/) |
| 1.2 | Introducción a la Seguridad Informática y de la Información | [`Tema-1.2 - Introducción a la Seguridad Informática y de la Información/`](Tema-1.2%20-%20Introducción%20a%20la%20Seguridad%20Informática%20y%20de%20la%20Información/) |
| 1.3 | Montaje de un Laboratorio de Ciberseguridad | [`Tema-1.3 - Montaje de un Laboratorio de Ciberseguridad/`](Tema-1.3%20-%20Montaje%20de%20un%20Laboratorio%20de%20Ciberseguridad/) |
| 2.1 | Footprinting y OSINT | [`Tema-2.1 - Footprinting y OSINT/`](Tema-2.1%20-%20Footprinting%20y%20OSINT/) |
| 2.2 | Escaneo y Técnicas de Evasión | [`Tema-2.2 - Escaneo y Técnicas de Evasión/`](Tema-2.2%20-%20Escaneo%20y%20Técnicas%20de%20Evasión/) |
| 2.3 | Enumeración | [`Tema-2.3 - Enumeración/`](Tema-2.3%20-%20Enumeración/) |
| 3.1 | Ataques a las credenciales | [`Tema-3.1 - Ataques a las credenciales/`](Tema-3.1%20-%20Ataques%20a%20las%20credenciales/) |
| 3.2 | Ingeniería Social | [`Tema-3.2 - Ingeniería Social/`](Tema-3.2%20-%20Ingeniería%20Social/) |
| 3.3 | Hacking con Metasploit | [`Tema-3.3 - Hacking con Metasploit/`](Tema-3.3%20-%20Hacking%20con%20Metasploit/) |
| 3.4 | Denegación de Servicio (DoS) | [`Tema-3.4 - Denegación de Servicio (DoS)/`](Tema-3.4%20-%20Denegación%20de%20Servicio%20%28DoS%29/) |

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
