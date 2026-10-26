---
title: "GetFileKey"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает уникальный идентификатор для записи кэша, представляющей файл."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Возвращает уникальный идентификатор для записи кэша, представляющей файл.

```csharp
public static string GetFileKey(string extension)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| extension | String | Суффикс имени файла (включая точку \".\"), например \".doc\". |

### Возвращаемое значение

Уникальный идентификатор кеш‑записи, представляющей файл.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *extension* равно null или пустой строке. |

### См. также

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
