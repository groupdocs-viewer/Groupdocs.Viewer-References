---
title: "FileLogger"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Escribe mensajes de registro en el archivo."
type: docs
weight: 660
url: /es/net/groupdocs.viewer.logging/filelogger/
---

## FileLogger class

Escribe mensajes de registro en el archivo.

```csharp
public class FileLogger : ILogger
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileLogger](filelogger)(string) | Crear un registrador en archivo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/filelogger/error)(string, Exception) | Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación. |
| [Trace](../../groupdocs.viewer.logging/filelogger/trace)(string) | Escribe un mensaje de traza en la consola. Los mensajes de registro de traza proporcionan información generalmente útil sobre el flujo de la aplicación. |
| [Warning](../../groupdocs.viewer.logging/filelogger/warning)(string) | Escribe un mensaje de advertencia en la consola. Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación. |

### Ver también

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
