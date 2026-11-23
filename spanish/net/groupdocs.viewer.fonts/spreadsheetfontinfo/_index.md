---
title: "SpreadsheetFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Encapsula metainformación y datos binarios de una fuente del documento Spreadsheet cargada en la instancia Viewer../groupdocs.viewer/viewer. Los documentos de hoja de cálculo no pueden tener fuentes incrustadas, por lo que esta fuente en particular, si fue devuelta por el método GetAllFonts../groupdocs.viewer/viewer/getallfonts, está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer."
type: docs
weight: 870
url: /es/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Encapsula metainformación y datos binarios de una fuente del documento Spreadsheet, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer). Los documentos de hoja de cálculo no pueden tener fuentes incrustadas, por lo que esta fuente en particular, si fue devuelta por el método [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts), está instalada en el sistema operativo, donde se ejecuta GroupDocs.Viewer.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Conjunto de caracteres de esta fuente |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Color de esta fuente |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Contenido de esta fuente como una matriz de bytes. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Nombre de familia de la fuente, sin estilo, nunca es nulo ni una cadena vacía |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Formato de esta fuente |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Indica si la fuente tiene un tachado simple |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Indica si la fuente tiene subrayado |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Estilo de esta fuente — puede ser Regular, Bold, Italic o Bold Italic |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |

### Ver también

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
