---
title: "IsSearchTermRegEx"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Obtiene o establece un valor que indica si el término de búsqueda debe tratarse como una expresión regular o como un texto literal. El valor predeterminado es false, tratar como texto literal."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

Obtiene o establece un valor que indica si el término de búsqueda debe tratarse como una expresión regular o como un texto literal. Por defecto es `false` — tratar como texto literal.

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### Observaciones

Si `true`, [`SearchTerm`](../searchterm) se interpreta como un patrón Regex de .NET.

Si `false`, [`SearchTerm`](../searchterm) se busca como un texto literal en el documento.

### Ver también

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
