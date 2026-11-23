---
title: "RemoveComments"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Отключает отображение комментариев, когда установлено в true. По умолчанию false, все комментарии отображаются."
type: docs
weight: 100
url: /ru/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

Отключает отображение комментариев, когда установлено `true`. По умолчанию `false` — все комментарии отображаются.

```csharp
public bool RemoveComments { get; set; }
```

### Примечания

Некоторые форматы документов, такие как PDF и WordProcessing, могут содержать комментарии. По умолчанию GroupDocs.Viewer их отображает. При установке этой опции в `true` комментарии могут быть исключены из результирующего документа.

Эта опция заменяет устаревшее свойство 'RenderComments'.

### См. также

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
