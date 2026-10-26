---
title: "ReleasePageStream"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Libera el flujo que fue instanciado por el método asociado con el delegado CreatePageStream./createpagestream."
type: docs
weight: 710
url: /es/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

Libera el flujo que fue instanciado por el método asociado con el delegado [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de la página. |
| pageStream | Stream | El flujo creado por el método asociado con el delegado [`CreatePageStream`](../createpagestream). |

### Ver también

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
