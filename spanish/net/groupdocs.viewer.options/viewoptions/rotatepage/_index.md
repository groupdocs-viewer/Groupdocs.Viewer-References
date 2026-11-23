---
title: "RotatePage"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Aplica la rotación en sentido horario a una página."
type: docs
weight: 30
url: /es/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Aplica la rotación en sentido horario a una página.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de página, debe ser estrictamente mayor que 0. |
| rotation | Rotation | El valor de rotación. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | Lanzada cuando *pageNumber* es menor o igual a cero. |
| ArgumentException | Lanzada cuando la rotación para la página con número *pageNumber* ya había sido añadida. |

### Observaciones

Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### Ver también

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
