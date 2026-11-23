---
title: "Error"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación."
type: docs
weight: 20
url: /es/net/groupdocs.viewer.logging/filelogger/error/
---

## FileLogger.Error method

Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

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

* class [FileLogger](../../filelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
