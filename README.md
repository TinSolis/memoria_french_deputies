# Memoria — informe final (LaTeX, plantilla FCFM/UChile)

> **Estado: cerrada.** Memoria de Ingeniería Civil en Computación defendida el 16-nov-2026 y aprobada por la comisión. El PDF final defendido vive en el repo de análisis, [TinSolis/tesis-french-deputies-analysis](https://github.com/TinSolis/tesis-french-deputies-analysis) (`memoria_agustin_solis_meza.pdf`). El `main.pdf` de este repo es una compilación antigua.

Fuente LaTeX de la memoria con la clase `umemoria` de [dccuchile/memoria-tesis-latex](https://github.com/dccuchile/memoria-tesis-latex), que cumple el [Manual de Normalización de Formato y Escritura](https://repositorio.uchile.cl/handle/2250/185276) de la FCFM (tamaño carta, márgenes 3/2/2/2 cm, portada, numeración romana/arábiga, etc.).

Este repo está sincronizado con Overleaf (*Import from GitHub*; compilador `pdfLaTeX`, documento principal `main.tex`). Localmente vive clonado en `memoria_ing_civil/manuscrito/`.

## Estructura de archivos


| Archivo                 | Contenido                                                                        |
| ----------------------- | -------------------------------------------------------------------------------- |
| `main.tex`              | Documento maestro: metadatos de portada, resumen, índice, `\input` de capítulos. |
| `intro.tex`             | Capítulo 1 — Introducción (contexto, problema, objetivos, alcances, estructura). |
| `cap_marco_teorico.tex` | Capítulo 2 — Marco teórico y revisión de la literatura.                          |
| `cap_metodologia.tex`   | Capítulo 3 — Materiales y métodos (fuentes, normalización, modelos, métricas).   |
| `cap_resultados.tex`    | Capítulo 4 — Resultados.                                                         |
| `cap_discusion.tex`     | Capítulo 5 — Discusión (optativo según el manual).                               |
| `conclu.tex`            | Capítulo 6 — Conclusiones.                                                       |
| `anexoA.tex`            | Anexo A — material complementario.                                               |
| `bibliografia.bib`      | Referencias en BibTeX (sembradas desde `contexto/referencias.md` del repo de análisis). |
| `umemoria.cls`          | Clase LaTeX de la FCFM (no editar).                                              |
| `imagenes/`             | Escudo U. de Chile y logo FCFM para la portada.                                  |


## Pendientes antes de la entrega

- [ ] Completar los integrantes de la comisión en `main.tex` (`\comision{...}`), con
  ```
  **nombre y los dos apellidos** de cada uno (Biblioteca lo revisa).
  ```
- [ ] Confirmar el título definitivo y el alcance (Francia, o Francia + Chile).
- [ ] Redactar el resumen ejecutivo (1 página) al final.
- [ ] Reemplazar los comentarios guía de cada sección por el texto real.
- [ ] Revisar las citas de `bibliografia.bib` (las de cohesión partidaria están por confirmar).