---
title: "ReleaseResourceStream"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Libera el flujo creado por el método CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream."
type: docs
weight: 30
url: /es/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

Libera el flujo creado por el método [`CreateResourceStream`](../createresourcestream).

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de una página. |
| resource | Recurso | El recurso HTML como fuente, estilo, imagen o gráficos. |
| resourceStream | Stream | Flujo creado por el método [`CreateResourceStream`](../createresourcestream). |

### Ver también

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
