---
title: "TryGetValue"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Получает запись, связанную с этим ключом, если она присутствует."
type: docs
weight: 30
url: /ru/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

Получает запись, связанную с этим ключом, если она присутствует.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Параметр | Описание |
| --- | --- |
| TEntry | Тип записи. |
| ключ | Ключ, идентифицирующий запрашиваемую запись. |
| value | Найденное значение или null. |

### Возвращаемое значение

```csharp
True
```

если ключ был найден.

### См. также

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
