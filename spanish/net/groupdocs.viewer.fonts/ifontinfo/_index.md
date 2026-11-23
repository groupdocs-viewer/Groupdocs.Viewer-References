---
title: "IFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Interfaz común para todas las fuentes que pueden extraerse de todas las familias compatibles de formatos de documento PDF, WordProcessing, Spreadsheet y Presentation."
type: docs
weight: 820
url: /es/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Interfaz común para todas las fuentes, que pueden extraerse de todas las familias de formatos de documento compatibles: PDF, WordProcessing, Spreadsheet y Presentation.

```csharp
public interface IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Contenido binario de la fuente como matriz de bytes, si está disponible, o `null`, si no lo está |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Nombre de familia de la fuente como cadena |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Formato de esta fuente como enumeración — TrueType, TrueType Collection, OpenType, Embedded OpenType o Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Estilo de la fuente como enumeración — Regular, Bold, Italic o Bold Italic. Algunos formatos de documento pueden tener fuentes solo con estilo [`Regular`](../fontstyles/regular). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |

### Ver también

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
