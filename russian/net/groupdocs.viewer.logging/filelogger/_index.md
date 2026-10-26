---
title: "FileLogger"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Записывает сообщения журнала в файл."
type: docs
weight: 660
url: /ru/net/groupdocs.viewer.logging/filelogger/
---

## FileLogger class

Записывает сообщения журнала в файл.

```csharp
public class FileLogger : ILogger
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileLogger](filelogger)(string) | Создать логгер в файл. |

## Методы

| Имя | Описание |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/filelogger/error)(string, Exception) | Записывает сообщение об ошибке в консоль. Сообщения журнала ошибок предоставляют информацию о непоправимых событиях в работе приложения. |
| [Trace](../../groupdocs.viewer.logging/filelogger/trace)(string) | Записывает трассировочное сообщение в консоль. Трассировочные сообщения журнала предоставляют общую полезную информацию о работе приложения. |
| [Warning](../../groupdocs.viewer.logging/filelogger/warning)(string) | Записывает предупреждающее сообщение в консоль. Предупреждающие сообщения журнала предоставляют информацию о неожиданных и восстанавливаемых событиях в работе приложения. |

### См. также

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
