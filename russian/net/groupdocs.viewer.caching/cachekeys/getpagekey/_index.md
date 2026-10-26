---
title: "GetPageKey"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает уникальный идентификатор для записи кэша, представляющей файл страницы."
type: docs
weight: 50
url: /ru/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Возвращает уникальный идентификатор для записи кэша, представляющей файл страницы.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| extension | String | Суффикс имени файла (включая точку \".\"), например \".doc\". |

### Возвращаемое значение

Уникальный идентификатор записи кэша, представляющей файл страницы.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *pageNumber* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *extension* равно null или пустой строке. |

### См. также

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
