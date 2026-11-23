---
title: "GetResourceKey"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает уникальный идентификатор записи кэша, представляющей объект Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 70
url: /ru/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

Возвращает уникальный идентификатор записи кэша, представляющей объект [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| resource | Ресурс | HTML-ресурс. |

### Возвращаемое значение

Уникальный идентификатор записи кэша, представляющей объект [`Resource`](../../../groupdocs.viewer.results/resource).

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *pageNumber* меньше или равен нулю. |
| ArgumentNullException | Выбрасывается, когда *resource* равен null. |

### См. также

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
