# Seguridad en Sistemas Informáticos — Tema 1.3

Transparencias (Beamer/LaTeX, 16:9) del **Tema 1.3: Montaje de un Laboratorio de
Ciberseguridad** de *Seguridad en Sistemas Informáticos* (UCLM).

Cubre: distribuciones (Kali), hipervisores, Metasploitable2, personalización del terminal,
**Docker** y **docker-compose**, y **aplicaciones web vulnerables** para practicar
(DVWA, Juice Shop, WebGoat, SQLi-Labs, bWAPP/Mutillidae, APIs vulnerables).

## Contenido
- `presentacion_1.3.tex` — fuente LaTeX (Beamer, plantilla del centro).
- `beamertemplate.sty` — plantilla (base *Madrid*, paleta azul marino).
- `img/` — imágenes del tema.
- `presentacion_1.3.pdf` — presentación compilada.

> Convertido (texto + imágenes + hipervínculos) desde el `.pptx` original. Algunos títulos
> auto-detectados pueden requerir un retoque manual fino.

## Compilar
```bash
latexmk -pdf presentacion_1.3.tex
```

## Licencia
© 2026 José Luis Martínez — Universidad de Castilla-La Mancha.
Texto y materiales propios bajo **CC BY-NC-SA 4.0** (ver [`LICENSE`](LICENSE)); las
imágenes de terceros conservan la licencia de sus autores originales.

## Créditos de imágenes (material de terceros)
Estas transparencias, con fines **exclusivamente docentes**, incluyen imágenes y capturas
cuya autoría corresponde a terceros. Se citan sus fuentes; **cada una conserva los derechos
de su autor** y **no** queda cubierta por la licencia CC de este repositorio. Si algún
titular de derechos desea que se retire su material, se hará de inmediato.

Fuentes principales:
- **Hacking Articles / Ignite Technologies** — capturas de las guías de despliegue de las
  aplicaciones vulnerables ([hackingarticles.in](https://www.hackingarticles.in)).
- **OWASP Foundation** — Juice Shop y WebGoat (logos/capturas) ([owasp.org](https://owasp.org)).
- **Proyectos open source** — DVWA, SQLi-Labs, bWAPP/Mutillidae, Kali Linux, Docker,
  Metasploitable (marcas y capturas de sus respectivos autores).
- **Guías de la comunidad** citadas: Guadalupe Cano (chuleta de Docker), Rubén Apablaza (ram-ozone).
- Capturas de VirtualBox / VMware / terminal, propiedad de sus titulares.

> Nota: algunas atribuciones son aproximadas (fuente inferida). Para uso público completo,
> lo más seguro es sustituir el material con copyright por imágenes propias o con licencia
> libre, u obtener permiso de los titulares.
