---
title: "UnlinkTableOfContents"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Al renderizar a HTML o PDF, puede establecer esta opción en true para desactivar la navegación desde la tabla de contenidos. En el renderizado HTML, las etiquetas <a> con enlaces relativos se reemplazarán por etiquetas <span>, eliminando la funcionalidad pero conservando la apariencia visual. En el renderizado PDF, la tabla de contenidos se renderizará como texto plano sin enlaces a las secciones del documento."
type: docs
weight: 110
url: /es/net/groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents/
---

## WordProcessingOptions.UnlinkTableOfContents property

Al renderizar a HTML o PDF, puede establecer esta opción en `true` para desactivar la navegación desde la tabla de contenido. Para la renderización HTML, las etiquetas `a` con enlaces relativos se reemplazarán por etiquetas `span`, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, la tabla de contenido se renderizará como texto plano sin enlaces a secciones del documento.

```csharp
public bool UnlinkTableOfContents { get; set; }
```

### Observaciones

El valor predeterminado es `false`.

Para obtener más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-word-documents/#unlink-table-of-contents).

### Ver también

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
