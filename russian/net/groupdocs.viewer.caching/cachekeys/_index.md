---
title: "CacheKeys"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Предоставляет методы для получения уникального идентификатора записи кэша."
type: docs
weight: 980
url: /ru/net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

Предоставляет методы для получения уникального идентификатора записи кэша.

```csharp
public static class CacheKeys
```

## Методы

| Имя | Описание |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | Возвращает уникальный идентификатор для записи кэша, представляющей файл вложения. |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | Возвращает уникальный идентификатор для записи кэша, представляющей коллекцию объектов [`Attachment`](../../groupdocs.viewer.results/attachment). |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | Возвращает уникальный идентификатор для записи кэша, представляющей объект [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | Возвращает уникальный идентификатор для записи кэша, представляющей файл. |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | Возвращает уникальный идентификатор для записи кэша, представляющей файл страницы. |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | Возвращает строку фильтра для поиска записей кэша, представляющих объекты [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | Возвращает уникальный идентификатор для записи кэша, представляющей объект [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | Возвращает уникальный идентификатор для записи кэша, представляющей объект [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |

### См. также

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
