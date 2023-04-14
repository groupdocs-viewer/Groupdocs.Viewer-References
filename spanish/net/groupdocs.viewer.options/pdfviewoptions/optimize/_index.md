---
title: Optimize
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Reduzca el tamaño del archivo de salida excluyendo fuentes comunes como Times New Roman y Arial y aplicando otras técnicas de optimización.
type: docs
weight: 70
url: /es/net/groupdocs.viewer.options/pdfviewoptions/optimize/
---
## PdfViewOptions.Optimize property

Reduzca el tamaño del archivo de salida excluyendo fuentes comunes como Times New Roman y Arial, y aplicando otras técnicas de optimización.

```csharp
public bool Optimize { get; set; }
```

### Observaciones

En la versión 23.1, esta opción es compatible con[Formatos de archivo de hoja de cálculo](https://docs.groupdocs.com/viewer/net/supported-document-formats/#spreadsheet-file-formats) solo.

Obtenga más información sobre cómo exportar hojas de cálculo de Excel y Apple Numbers a PDF

* [Renderizar hojas de cálculo como PDF](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/#render-spreadsheets-as-pdf)

### Ejemplos

El ejemplo demuestra un uso típico de esta opción.

```csharp
using (var viewer = new Viewer("employees.xlsx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.Optimize = true;

    viewer.View(viewOptions);
}
```

### Ver también

* class [PdfViewOptions](../../pdfviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../pdfviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->