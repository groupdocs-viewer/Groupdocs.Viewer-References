---
title: ReleaseResourceStream
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Libera el flujo creado porCreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream método.
type: docs
weight: 30
url: /es/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---
## IResourceStreamFactory.ReleaseResourceStream method

Libera el flujo creado por[`CreateResourceStream`](../createresourcestream) método.

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de una página. |
| resource | Resource | El recurso HTML como fuente, estilo, imagen o gráficos. |
| resourceStream | Stream | Transmisión creada por[`CreateResourceStream`](../createresourcestream) método. |

### Ver también

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* espacio de nombres [GroupDocs.Viewer.Interfaces](../../iresourcestreamfactory)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
