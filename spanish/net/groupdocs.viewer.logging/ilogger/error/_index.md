---
title: "Error"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Escribe un mensaje de error. Los mensajes de registro de errores proporcionan información sobre eventos irrecuperables en el flujo de la aplicación."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Escribe un mensaje de error. Los mensajes de registro de errores proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

```csharp
public void Error(string message, Exception exception)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| mensaje | String | El mensaje de error. |
| excepción | Excepción | La excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *message* es nulo. |
| ArgumentNullException | Lanzado cuando *exception* es nulo. |

### Ver también

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
