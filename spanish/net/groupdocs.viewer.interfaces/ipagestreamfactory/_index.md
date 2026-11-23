---
title: "IPageStreamFactory"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Define los métodos necesarios para instanciar y liberar el flujo de página de salida."
type: docs
weight: 760
url: /es/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

Define los métodos necesarios para instanciar y liberar el flujo de página de salida.

```csharp
public interface IPageStreamFactory
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | Crea el flujo utilizado para escribir los datos de página de salida. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | Libera el flujo creado por el método [`CreatePageStream`](./createpagestream). |

### Ver también

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
