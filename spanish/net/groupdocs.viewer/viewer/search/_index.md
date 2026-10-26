---
title: "Search"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Realiza una búsqueda de texto y su resaltado si se encuentra en el documento cargado según las opciones cargadas."
type: docs
weight: 80
url: /es/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

Realiza una búsqueda de texto y su resaltado (si se encuentra) en el documento cargado según las opciones cargadas.

```csharp
public void Search(SearchHighlightOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | SearchHighlightOptions | Opciones de búsqueda y resaltado, esto incluye una frase de texto para buscar. No puede ser `null`. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando el argumento *options* es `null` |

### Ver también

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
