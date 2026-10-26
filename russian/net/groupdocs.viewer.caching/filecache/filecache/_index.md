---
title: "FileCache"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Создаёт новый экземпляр класса FileCachegroupdocs.viewer.caching/filecache."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

Создаёт новый экземпляр класса [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| cachePath | String | Относительный или абсолютный путь, где будет храниться кэш документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *cachePath* равно null. |

### См. также

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

Создаёт новый экземпляр класса [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| cachePath | String | Относительный или абсолютный путь, где будет храниться кэш документа. |
| cacheSubFolder | String | Подпапка, которую следует добавить к *cachePath*. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *cachePath* равно null. |
| ArgumentNullException | Выбрасывается, когда *cacheSubFolder* равно null. |

### См. также

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
