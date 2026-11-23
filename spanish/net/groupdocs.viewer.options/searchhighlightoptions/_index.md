---
title: "SearchHighlightOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Proporciona opciones para buscar y resaltar texto en los documentos cargados en la Viewer../groupdocs.viewer/viewer class."
type: docs
weight: 500
url: /es/net/groupdocs.viewer.options/searchhighlightoptions/
---

## SearchHighlightOptions class

Proporciona opciones para buscar y resaltar texto en los documentos, cargados en la clase [`Viewer`](../../groupdocs.viewer/viewer).

```csharp
public sealed class SearchHighlightOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SearchHighlightOptions](searchhighlightoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/searchhighlightoptions/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo para el resaltado. |
| [ForegroundColor](../../groupdocs.viewer.options/searchhighlightoptions/foregroundcolor) { get; set; } | Obtiene o establece el color de primer plano (texto) para el resaltado. |
| [IsSearchTermRegEx](../../groupdocs.viewer.options/searchhighlightoptions/issearchtermregex) { get; set; } | Obtiene o establece un valor que indica si el término de búsqueda debe tratarse como una expresión regular o como un texto literal. Por defecto es `false` — tratar como texto literal. |
| [SearchTerm](../../groupdocs.viewer.options/searchhighlightoptions/searchterm) { get; set; } | Obtiene o establece el texto (o patrón de expresión regular, si la propiedad [`IsSearchTermRegEx`](./issearchtermregex) es `true`) a buscar. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
