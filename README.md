# Memoria: LaTeX

Este repo tiene el LaTeX de mi memoria de Ingeniería Civil en Computación. La defendí el 16 de noviembre de 2026 y me la aprobaron, así que ya no lo modifico. El PDF final que defendí está en el repo del proyecto, [tesis-french-deputies-analysis](https://github.com/TinSolis/tesis-french-deputies-analysis) (`memoria_agustin_solis_meza.pdf`). El `main.pdf` que está aquí es una compilación antigua.

Usé la clase `umemoria` de [dccuchile/memoria-tesis-latex](https://github.com/dccuchile/memoria-tesis-latex), que cumple el [Manual de Normalización de Formato y Escritura](https://repositorio.uchile.cl/handle/2250/185276) de la FCFM (tamaño carta, márgenes de 3/2/2/2 cm, portada, numeración romana y arábiga, etc.). Lo escribí en Overleaf, importado desde este repo, con el compilador `pdfLaTeX` y `main.tex` como documento principal.

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
| `bibliografia.bib`      | Referencias en BibTeX (partí de `contexto/referencias.md` del repo del proyecto). |
| `umemoria.cls`          | Clase LaTeX de la FCFM (no editar).                                              |
| `imagenes/`             | Escudo U. de Chile y logo FCFM para la portada.                                  |
