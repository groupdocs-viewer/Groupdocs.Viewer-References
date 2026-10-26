---
title: "WordProcessingFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Encapsula metainformación y datos binarios de una fuente del documento WordProcessing cargado en la instancia del Viewer../groupdocs.viewer/viewer. Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer."
type: docs
weight: 880
url: /es/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

Encapsula metainformación y datos binarios de una fuente del documento WordProcessing, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer). Esta fuente se usa en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Nombre de familia alternativo de la fuente. Si falta, será una cadena vacía. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Conjunto de caracteres de esta fuente |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Contenido de esta fuente como una matriz de bytes. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Nombre de familia de la fuente, sin estilo, nunca es nulo ni una cadena vacía |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Formato de esta fuente. Los documentos pueden usar fuentes en los siguientes formatos: TrueType, TrueType Collection, OpenType, Embedded OpenType. Si solo hay metainformación sobre esta fuente, pero su contenido binario no está disponible, esta propiedad devuelve un valor Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Indica si esta fuente está incrustada dentro del documento, cargada en la instancia del [`Viewer`](../../groupdocs.viewer/viewer) (`true`), o es una fuente del sistema (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Estilo de la fuente — puede ser Regular, Negrita, Cursiva o Negrita Cursiva. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Devuelve información de depuración sobre los datos de esta fuente con la siguiente plantilla: "nombre estilo, incrustada/sistema, formato" |

### Observaciones

Estructura inmutable. Sus instancias son producidas y devueltas por la API pública de GroupDocs.Viewer y normalmente no deben ser creadas por el usuario. Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Ver también

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
