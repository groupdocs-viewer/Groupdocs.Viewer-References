---
title: "ForRenderingByWidthAndHeight"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase CadOptionsgroupdocs.viewer.options/cadoptions para renderizar por ancho y alto."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

Inicializa una instancia de la clase [`CadOptions`](../../cadoptions) para renderizar por ancho y alto.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho del resultado de salida (en píxeles). |
| height | Int32 | La altura del resultado de salida (en píxeles). |

### Valor devuelto

Nueva instancia de la clase [`CadOptions`](../../cadoptions) para renderizar por ancho y alto.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |

### Observaciones

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Ver también

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
