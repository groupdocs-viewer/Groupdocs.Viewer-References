---
title: GetPageKey
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Возвращает уникальный идентификатор записи кэша представляющей файл подкачки.
type: docs
weight: 50
url: /ru/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---
## CacheKeys.GetPageKey method

Возвращает уникальный идентификатор записи кэша, представляющей файл подкачки.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| extension | String | Суффикс имени файла (включая точку "."), например, ".doc". |

### Возвращаемое значение

Уникальный идентификатор записи кэша, представляющей файл подкачки.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*pageNumber* меньше или равно нулю. |
| ArgumentException | Брошен, когда*extension* является нулевым или пустым. |

### Смотрите также

* class [CacheKeys](../../cachekeys)
* пространство имен [GroupDocs.Viewer.Caching](../../cachekeys)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
