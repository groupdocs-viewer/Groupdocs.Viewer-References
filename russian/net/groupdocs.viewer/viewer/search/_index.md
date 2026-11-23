---
title: "Search"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Выполняет текстовый поиск и его выделение, если найдено в загруженном документе, в соответствии с загруженными параметрами."
type: docs
weight: 80
url: /ru/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

Выполняет поиск текста и его подсветку (если найден) в загруженном документе в соответствии с загруженными параметрами.

```csharp
public void Search(SearchHighlightOptions options)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | SearchHighlightOptions | Параметры поиска и подсветки, включающие фразу текста для поиска. Не может быть `null`. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда аргумент *options* равен `null` |

### См. также

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
