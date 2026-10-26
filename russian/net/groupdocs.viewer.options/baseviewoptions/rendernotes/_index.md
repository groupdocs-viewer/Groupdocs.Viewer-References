---
title: "RenderNotes"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Включает отображение заметок и аннотаций для некоторых форматов"
type: docs
weight: 120
url: /ru/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

Включает отображение заметок и аннотаций для некоторых форматов

```csharp
public bool RenderNotes { get; set; }
```

### Примечания

Некоторые форматы, такие как презентации или файлы Microsoft Project, могут содержать заметки. Кроме того, PDF‑файлы могут иметь всплывающие аннотации (всплывающие подсказки), которые по умолчанию скрыты и видны в PDF‑просмотрщике только при наведении курсора мыши. По умолчанию GroupDocs.Viewer не отображает такие заметки и аннотации (`false`). Чтобы включить их, установите это свойство в `true`.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### См. также

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
