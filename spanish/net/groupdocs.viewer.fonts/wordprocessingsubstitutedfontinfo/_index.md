---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Encapsula metainformación y datos binarios de una fuente del documento WordProcessing que originalmente no se utiliza en el documento cargado en la instancia del Viewer../groupdocs.viewer/viewer, pero sirve como fuente de sustitución para aquellas que no pueden encontrarse en la máquina objetivo. Las fuentes sustituidas existen solo para la familia de formatos WordProcessing."
type: docs
weight: 890
url: /es/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

Encapsula metainformación y datos binarios de una fuente del documento WordProcessing, que originalmente no se utiliza en el documento cargado en la instancia del [`Viewer`](../../groupdocs.viewer/viewer), pero sirve como fuente de sustitución para aquellas que no pueden encontrarse en la máquina objetivo. Las fuentes sustituidas existen solo para la familia de formatos WordProcessing.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Contenido de esta fuente sustituta como una matriz de bytes. Nunca es `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | Nombre de familia de la fuente **sustituida**, sin estilo, nunca es nulo ni una cadena vacía |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Formato de esta fuente sustituta (no original). Puede ser TrueType, TrueType Collection, OpenType, Embedded OpenType. Para la fuente sustituta, dado que su contenido binario está disponible por definición, esta propiedad nunca devuelve un valor Unknown. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Nombre de familia de la fuente original, que no puede encontrarse en una máquina objetivo, sin estilo, nunca es nulo ni una cadena vacía. |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Estilo de la fuente original — puede ser Regular, Negrita, Cursiva o Negrita Cursiva. La fuente sustituta suele (pero no siempre) tener el mismo estilo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Devuelve información de depuración sobre estos datos de fuente con la siguiente plantilla: "original-name -&gt; substituted-name style, format" |

### Observaciones

Estructura inmutable. Sus instancias son producidas y devueltas por la API pública de GroupDocs.Viewer y normalmente no deben ser creadas por el usuario. Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Ver también

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
