---
title: "GetResourceFilter"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает строку фильтра для поиска записей кэша, представляющих объекты Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 60
url: /ru/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

Возвращает строку фильтра для поиска записей кэша, представляющих объекты [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |

### Возвращаемое значение

Строка фильтра для поиска записей кэша, представляющих объекты [`Resource`](../../../groupdocs.viewer.results/resource).

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *pageNumber* меньше или равен нулю. |

### См. также

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
