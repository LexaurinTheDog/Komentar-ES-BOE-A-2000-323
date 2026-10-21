# Fuentes y trazabilidad

La fuente normativa es el BOE. [verification.json](sources/verification.json) registra solicitudes, resultados HTTP, fechas de acceso, formatos XML validados y huellas SHA-256. [source-manifest.json](source-manifest.json) inventaría los archivos conservados. La captura original y el XML de versiones se mantienen junto al texto canónico seleccionado.

- [HTML oficial capturado](sources/boe-act.html) y [XML de versiones](sources/boe-text.xml).
- [Metadatos](sources/boe-metadata.xml), [análisis oficial](sources/boe-analysis.xml) y [selección por bloque](sources/version-selection.json).
- [Texto canónico](sources/canonical-2026-10-19.txt), [captura de entrada preservada](sources/intake-2026-10-01.md) y [cambios desde 30 de septiembre](sources/change-map.json).
- [Real Decreto-ley 29/2026](sources/BOE-A-2026-20823.xml), [derogación del 26/2026](sources/BOE-A-2026-20526.xml) y [versión intermedia conservada](sources/BOE-A-2026-20266.xml).
- [Ley Orgánica 1/2025](sources/BOE-A-2025-76.xml) y [LOPJ, XML de apoyo para remisiones](sources/LOPJ-text.xml).
- [Diferencias iniciales detectadas](sources/initial-selection-differences.json), [cotejo final](text-agreement-report.json) y [cobertura independiente](coverage-evidence.json).
- [STC 34/2019](cases/STC-34-2019.md), [STC 15/2020](cases/STC-15-2020.md), [STC 30/2014](cases/STC-30-2014.md) y [registro de búsqueda](sources/case-search-log.json).

La búsqueda utilizó metadatos del corpus nacional local del Tribunal Constitucional y contrastó identificadores, texto y fallo con las publicaciones oficiales. El intento web sobre STC 58/2016 no aportó un resultado primario utilizable; no se ha citado una fuente comercial en sustitución. Un candidato BOE ajeno a la sentencia buscada se conserva identificado como rechazado y no sirve de autoridad. No se afirma investigación jurisprudencial exhaustiva ni selección de casos para todas las unidades técnicas.

La ausencia de anexos se comprobó en los encabezados de los 1.083 bloques oficiales. Las 49 disposiciones complementarias no se han omitido ni confundido con notas. Se conserva también el preámbulo y la fórmula de promulgación como documentación no operativa, sin incluirlos en el recuento de preceptos.


Lote 248–263: [XML BOE actualizado](sources/author-a248-a263-official.xml), [auditoría de selección y cobertura](author-a248-a263-audit.json), [STC 222/2012](cases/TC-222-2012.md) y [búsqueda selectiva con corpus local](sources/case-search-a248-a263.json). La sentencia inadmite la cuestión, sin resolver la constitucionalidad material del registro; se distingue su legislación histórica.


Lote 264–282: [XML oficial recién descargado](sources/author-a264-a282-official.xml), [selección y cobertura](author-a264-a282-audit.json), [STC 107/2005](cases/STC-107-2005.md) y [búsqueda selectiva](sources/case-search-a264-a282.json). Se conserva el texto completo de la sentencia y el ejemplar del corpus nacional; no se atribuye al fallo la postura desestimatoria del fiscal ni una subsanación ilimitada.
