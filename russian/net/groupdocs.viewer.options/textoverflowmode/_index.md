---
title: "TextOverflowMode"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Устанавливает режим переполнения текста при рендеринге электронных таблиц в HTML."
type: docs
weight: 550
url: /ru/net/groupdocs.viewer.options/textoverflowmode/
---

## TextOverflowMode enumeration

Устанавливает режим переполнения текста при рендеринге электронных таблиц в HTML.

```csharp
public enum TextOverflowMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Overlay | `0` | Накладывать следующие ячейки, даже если они не пусты. |
| OverlayIfNextIsEmpty | `1` | Накладывать следующие ячейки только если они пусты. Значение по умолчанию. |
| AutoFitColumn | `2` | Расширять столбцы, чтобы вместить текст. |
| HideText | `3` | Скрывать переполняющий текст. |

### Примечания

Для подробностей см. [документацию](https://docs.groupdocs.com/viewer/net/specify-rendering-options/#control-cell-text-overflow).

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
