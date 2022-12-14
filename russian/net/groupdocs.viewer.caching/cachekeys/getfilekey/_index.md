---
title: GetFileKey
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Возвращает уникальный идентификатор записи кэша представляющей файл.
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---
## CacheKeys.GetFileKey method

Возвращает уникальный идентификатор записи кэша, представляющей файл.

```csharp
public static string GetFileKey(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extension | String | Суффикс имени файла (включая точку "."), например, ".doc". |

### Возвращаемое значение

Уникальный идентификатор записи кэша, представляющей файл.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*extension* является нулевым или пустым. |

### Смотрите также

* class [CacheKeys](../../cachekeys)
* пространство имен [GroupDocs.Viewer.Caching](../../cachekeys)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
