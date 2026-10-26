---
title: "DisableCharsGrouping"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página."
type: docs
weight: 20
url: /es/net/groupdocs.viewer.options/pdfoptions/disablecharsgrouping/
---

## PdfOptions.DisableCharsGrouping property

Desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página.

```csharp
public bool DisableCharsGrouping { get; set; }
```

### Observaciones

Al convertir archivos PDF, GroupDocs.Viewer agrupa caracteres individuales en palabras para mejorar el rendimiento del renderizado. Si su documento incluye jeroglíficos o símbolos especiales, es posible que desee prohibir el agrupamiento de caracteres para garantizar un diseño más preciso. El valor predeterminado es `false`.

Para ver un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-character-grouping).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
