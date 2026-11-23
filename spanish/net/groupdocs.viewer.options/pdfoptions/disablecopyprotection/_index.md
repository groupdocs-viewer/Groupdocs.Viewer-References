---
title: "DisableCopyProtection"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Desactiva la protección contra copia de contenido al renderizar a HTML."
type: docs
weight: 30
url: /es/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

Desactiva la protección contra copia de contenido al renderizar a HTML.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Observaciones

Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML 'inert' a la etiqueta BODY del HTML. El valor predeterminado de esta opción es `false`, lo que indica que el atributo HTML 'intent' se agrega solo si el documento PDF está protegido.

Para ver un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
