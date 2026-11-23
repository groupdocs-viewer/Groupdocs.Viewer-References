---
title: "FontsToExclude"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Список названий шрифтов, исключаемых из HTML‑документа."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

Список названий шрифтов, исключаемых из HTML‑документа.

```csharp
public List<string> FontsToExclude { get; set; }
```

### Примечания

Шрифты, добавленные в HTML‑документ, повышают стабильность отображаемого результата, но одновременно увеличивают размер рендеринга. Эта опция позволяет сбалансировать стабильность и размер вывода. Укажите имена шрифтов, которые популярны и установлены на большинстве систем.

Обратите внимание, это свойство активно только когда параметр [`ExcludeFonts`](../excludefonts) отключён.

Для получения подробностей и примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/exclude-fonts/).

### См. также

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
