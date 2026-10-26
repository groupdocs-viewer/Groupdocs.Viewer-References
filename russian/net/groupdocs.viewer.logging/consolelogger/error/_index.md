---
title: "Ошибка"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Записывает сообщение об ошибке в консоль. Сообщения журнала ошибок предоставляют информацию о непоправимых событиях в работе приложения."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer.logging/consolelogger/error/
---

## ConsoleLogger.Error method

Записывает сообщение об ошибке в консоль. Сообщения журнала ошибок предоставляют информацию о непоправимых событиях в работе приложения.

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

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
