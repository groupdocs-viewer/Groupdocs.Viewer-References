---
title: "FileCache"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет локальный дисковый кэш."
type: docs
weight: 990
url: /ru/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Представляет локальный кэш на диске.

```csharp
public class FileCache : ICache
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Создаёт новый экземпляр класса [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | Создаёт новый экземпляр класса [`FileCache`](../filecache). |

## Свойства

| Имя | Описание |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | Относительный или абсолютный путь к папке кэша. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | Подпапка, добавляемая к [`CachePath`](./cachepath). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Возвращает все имена файлов, содержащие фильтр в имени файла. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Сериализует данные на локальный диск. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Десериализует данные, связанные с этим ключом, если они присутствуют. |

### См. также

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
