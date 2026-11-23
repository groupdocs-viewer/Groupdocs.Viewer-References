---
title: "ICache"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Определяет методы, необходимые для хранения отрендеренного документа и ресурсов документа в кэше."
type: docs
weight: 1000
url: /ru/net/groupdocs.viewer.caching/icache/
---

## ICache interface

Определяет методы, необходимые для хранения отрендеренного документа и ресурсов документа в кэше.

```csharp
public interface ICache
```

## Методы

| Имя | Описание |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Возвращает все ключи, соответствующие фильтру. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Вставляет запись кэша в кэш. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Получает запись, связанную с этим ключом, если она присутствует. |

### См. также

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
