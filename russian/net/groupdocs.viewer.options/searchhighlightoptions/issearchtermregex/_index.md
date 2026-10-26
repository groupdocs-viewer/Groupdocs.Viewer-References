---
title: "IsSearchTermRegEx"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Получает или задает значение, указывающее, следует ли рассматривать поисковый запрос как регулярное выражение или как буквальный текст. По умолчанию — false, то есть как буквальный текст."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

Получает или задаёт значение, указывающее, следует ли рассматривать поисковый запрос как регулярное выражение или как буквальный текст. По умолчанию `false` — рассматривать как буквальный текст.

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### Примечания

Если `true`, [`SearchTerm`](../searchterm) интерпретируется как шаблон .NET Regex.

Если `false`, [`SearchTerm`](../searchterm) ищется как буквальный текст в документе.

### См. также

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
