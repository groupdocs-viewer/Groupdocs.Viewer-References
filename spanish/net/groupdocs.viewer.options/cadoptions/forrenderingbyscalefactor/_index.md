---
title: "ForRenderingByScaleFactor"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase CadOptionsgroupdocs.viewer.options/cadoptions para renderizar por factor de escala."
type: docs
weight: 20
url: /es/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

Inicializa una instancia de la clase [`CadOptions`](../../cadoptions) para renderizar por factor de escala.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| scaleFactor | Single | Un valor mayor que 1 amplía el resultado de salida; un valor entre 0 y 1 reduce el resultado de salida. |

### Valor devuelto

Nueva instancia de la clase [`CadOptions`](../../cadoptions) para renderizar por factor de escala.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *scaleFactor* es menor o igual a cero. |

### Observaciones

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Ver también

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
