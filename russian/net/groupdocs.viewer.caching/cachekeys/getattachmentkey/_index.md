---
title: "GetAttachmentKey"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает уникальный идентификатор для записи кэша, представляющей файл вложения."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

Возвращает уникальный идентификатор для записи кэша, представляющей файл вложения.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| attachmentId | String | Уникальный (в контексте одного файла) идентификатор вложения. |

### Возвращаемое значение

Уникальный идентификатор записи кэша, представляющей файл вложения.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *attachmentId* равен null или пуст. |

### См. также

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
