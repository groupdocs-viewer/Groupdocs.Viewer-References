---
title: "ReleaseResourceStream"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Libera el flujo que fue instanciado por el método asociado con el delegado CreateResourceStream./createresourcestream."
type: docs
weight: 730
url: /es/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

Libera el flujo que fue instanciado por el método asociado al delegado [`CreateResourceStream`](../createresourcestream).

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de la página. |
| resource | Recurso | Recurso HTML como fuente, estilo, imagen o gráficos. |
| resourceStream | Stream | El flujo creado por el método asociado al delegado [`CreateResourceStream`](../createresourcestream). |

### Ver también

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
