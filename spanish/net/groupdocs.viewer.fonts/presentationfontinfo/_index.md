---
title: "PresentationFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Encapsula metainformación y datos binarios de una fuente del documento Presentation cargada en la instancia Viewer../groupdocs.viewer/viewer. Esta fuente se usa en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer."
type: docs
weight: 850
url: /es/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Encapsula metainformación y datos binarios de una fuente del documento Presentation, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer). Esta fuente se usa en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo, donde se ejecuta GroupDocs.Viewer.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Contenido de esta fuente como una matriz de bytes. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Nombre de familia de la fuente, sin estilo, nunca es nulo ni una cadena vacía |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Formato de esta fuente. Los documentos pueden usar fuentes en los siguientes formatos: TrueType, TrueType Collection, OpenType, Embedded OpenType. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve un valor Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Indica si esta fuente está incrustada dentro del documento, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer) (`true`), o es una fuente del sistema (`false`). Los documentos de hoja de cálculo no pueden contener fuentes incrustadas, por lo que para ellos esta propiedad siempre devuelve `false`. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Estilo de la fuente — puede ser Regular, Bold, Italic o Bold Italic |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |

### Ver también

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
