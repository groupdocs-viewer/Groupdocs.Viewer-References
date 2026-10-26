---
title: "CreateResourceStream"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa el método que instancia el flujo utilizado para escribir los datos del recurso HTML de salida."
type: docs
weight: 720
url: /es/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Representa el método que instancia el flujo utilizado para escribir los datos del recurso HTML de salida.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de la página. |
| resource | Recurso | Recurso HTML como fuente, estilo, imagen o gráficos. |

### Valor devuelto

El flujo utilizado para escribir los datos de recursos HTML de salida.

### Ver también

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
