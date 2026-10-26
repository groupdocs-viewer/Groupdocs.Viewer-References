---
title: "MaxItemsInFolder"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "El número máximo de mensajes o elementos que se pueden renderizar desde una carpeta."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

El número máximo de mensajes o elementos que pueden renderizarse desde una carpeta.

```csharp
public int MaxItemsInFolder { get; set; }
```

### Observaciones

Los archivos de datos de Outlook pueden ser grandes y recuperar todos los mensajes puede llevar tiempo significativo. Esta propiedad limita el número máximo de mensajes o elementos que se renderizan. El valor predeterminado es `50`. Para renderizar todos los mensajes, establezca el valor en `0`.

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).

### Ver también

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
