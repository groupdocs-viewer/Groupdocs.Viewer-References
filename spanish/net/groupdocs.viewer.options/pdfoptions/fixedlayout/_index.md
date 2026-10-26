---
title: "FixedLayout"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Habilita el renderizado de los documentos PDF y EPUB a HTML con un diseño fijo."
type: docs
weight: 70
url: /es/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

Habilita el renderizado de los documentos PDF y EPUB a HTML con un diseño fijo.

```csharp
public bool FixedLayout { get; set; }
```

### Observaciones

Los documentos PDF y EPUB se renderizan inicialmente a HTML con un diseño fijo para mantener la apariencia del documento original. Este diseño fijo significa que todos los elementos HTML tienen posiciones precisas dentro de un contenedor con un tamaño definido. Cambiar el tamaño de la ventana del navegador no afecta la posición ni el tamaño de los elementos en el documento.

Esta opción solo está disponible al renderizar a HTML. El valor predeterminado es `true`. Para renderizar con un diseño fluido, establezca esta propiedad en `false`.

Al renderizar con un diseño fluido, se omiten las imágenes. Utilice el diseño fluido al renderizar documentos PDF con contenido de texto.

Para ver un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
