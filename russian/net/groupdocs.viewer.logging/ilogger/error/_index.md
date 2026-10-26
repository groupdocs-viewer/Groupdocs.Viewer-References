---
title: "Ошибка"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Записывает сообщение об ошибке. Сообщения журнала ошибок предоставляют информацию о необратимых событиях в потоке приложения."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Записывает сообщение об ошибке. Сообщения журнала ошибок предоставляют информацию о необратимых событиях в потоке приложения.

```csharp
public void Error(string message, Exception exception)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| сообщение | String | Сообщение об ошибке. |
| исключение | Исключение | Исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *message* равно null. |
| ArgumentNullException | Выбрасывается, когда *exception* равно null. |

### См. также

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
