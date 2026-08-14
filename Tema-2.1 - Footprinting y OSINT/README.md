# Seguridad en Sistemas Informáticos — Tema 2.1

Transparencias (Beamer/LaTeX, 16:9) del **Tema 2.1: Footprinting y OSINT** de
*Seguridad en Sistemas Informáticos* (UCLM).

Cubre: fases de reconocimiento, **operadores de búsqueda avanzada (Google dorks)**,
**filtraciones de datos** y descubrimiento de correos, **enumeración de usuarios**
(LinkedIn/RRSS), **metadatos**, identificación de tecnologías y sistemas (Shodan),
geolocalización IP y monitorización.

## Contenido
- `presentacion_2.1.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_2.1.pdf` — presentación compilada.

> Convertido (texto + imágenes + hipervínculos) desde el `.pptx` original. Algunos títulos
> auto-detectados pueden requerir un retoque manual fino.

## Compilar
```bash
latexmk -pdf presentacion_2.1.tex
```

## Licencia
© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.
Texto y materiales propios bajo **CC BY-NC-SA 4.0** (ver [`LICENSE`](LICENSE)); las
imágenes de terceros conservan la licencia de sus autores originales.

## Créditos de imágenes (material de terceros)
Estas transparencias, con fines **exclusivamente docentes**, incluyen capturas de
herramientas y servicios cuya autoría corresponde a terceros. Se citan sus fuentes; **cada
una conserva los derechos de su autor** y **no** queda cubierta por la licencia CC de este
repositorio. Si algún titular desea que se retire su material, se hará de inmediato.

Fuentes principales:
- **Hacking Articles / Ignite Technologies** — capturas de guías OSINT ([hackingarticles.in](https://www.hackingarticles.in)).
- **Herramientas y servicios OSINT** (capturas): Shodan, Google (dorks / Hacking Database),
  Have I Been Pwned, theHarvester, Maltego, LinkedIn/RRSS, servicios de metadatos y de
  geolocalización IP — marcas y capturas de sus respectivos titulares.
- Capturas de terminal y de resultados de las herramientas, propiedad de sus autores.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
