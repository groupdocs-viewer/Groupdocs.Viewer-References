---
title: "DisableCharsGrouping"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Отключает группировку символов для точного позиционирования символов при рендеринге страницы."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer.options/pdfoptions/disablecharsgrouping/
---

## PdfOptions.DisableCharsGrouping property

Отключает группировку символов для точного позиционирования символов при рендеринге страницы.

```csharp
public bool DisableCharsGrouping { get; set; }
```

### Примечания

При конвертации PDF‑файлов GroupDocs.Viewer группирует отдельные символы в слова для повышения производительности рендеринга. Если ваш документ содержит иероглифы или специальные символы, вы можете запретить группировку символов, чтобы обеспечить более точное расположение. Значение по умолчанию — `false`.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-character-grouping).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
