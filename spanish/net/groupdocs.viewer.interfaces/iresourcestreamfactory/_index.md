---
title: "IResourceStreamFactory"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Define los métodos que se requieren para crear la URL del recurso, instanciar y liberar el flujo de recursos HTML de salida."
type: docs
weight: 770
url: /es/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Define los métodos necesarios para crear la URL del recurso, instanciar y liberar el flujo del recurso HTML de salida.

```csharp
public interface IResourceStreamFactory
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Crea el flujo utilizado para escribir los datos de recursos HTML de salida. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Crea la URL para el recurso HTML. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Libera el flujo creado por el método [`CreateResourceStream`](./createresourcestream). |

### Ver también

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
