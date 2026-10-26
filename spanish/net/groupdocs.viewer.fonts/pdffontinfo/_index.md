---
title: "PdfFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Encapsula metainformación y datos binarios de una fuente del documento PDF cargado en la instancia Viewer../groupdocs.viewer/viewer. Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer."
type: docs
weight: 840
url: /es/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

Encapsula metainformación y datos binarios de una fuente del documento PDF, cargada en la instancia [`Viewer`](../../groupdocs.viewer/viewer). Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo, donde se ejecuta GroupDocs.Viewer.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Contenido de esta fuente como una matriz de bytes. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Nombre de familia de la fuente, sin estilo, nunca es nulo ni una cadena vacía |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Formato de esta fuente. Los documentos pueden usar fuentes en los siguientes formatos: TrueType, TrueType Collection, OpenType, Embedded OpenType. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve un valor Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Indica si esta fuente está incrustada dentro del documento PDF, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer) (`true`), o no. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Indica si esta fuente está presente (instalada) en el sistema operativo donde se ejecuta GroupDocs.Viewer |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Estilo de la fuente — puede ser Regular, Negrita, Cursiva o Negrita Cursiva. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |

### Ver también

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
