---
title: "SearchHighlightOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Предоставляет параметры для поиска и выделения текста в документах, загруженных в класс Viewer../groupdocs.viewer/viewer."
type: docs
weight: 500
url: /ru/net/groupdocs.viewer.options/searchhighlightoptions/
---

## SearchHighlightOptions class

Предоставляет параметры для поиска и выделения текста в документах, загруженных в класс [`Viewer`](../../groupdocs.viewer/viewer).

```csharp
public sealed class SearchHighlightOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SearchHighlightOptions](searchhighlightoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/searchhighlightoptions/backgroundcolor) { get; set; } | Получает или задаёт цвет фона для выделения. |
| [ForegroundColor](../../groupdocs.viewer.options/searchhighlightoptions/foregroundcolor) { get; set; } | Получает или задаёт цвет переднего плана (текста) для выделения. |
| [IsSearchTermRegEx](../../groupdocs.viewer.options/searchhighlightoptions/issearchtermregex) { get; set; } | Получает или задаёт значение, указывающее, следует ли рассматривать поисковый запрос как регулярное выражение или как буквальный текст. По умолчанию `false` — рассматривать как буквальный текст. |
| [SearchTerm](../../groupdocs.viewer.options/searchhighlightoptions/searchterm) { get; set; } | Получает или задаёт текст (или шаблон регулярного выражения, если свойство [`IsSearchTermRegEx`](./issearchtermregex) равно `true`) для поиска. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
