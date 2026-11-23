---
title: "IFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов PDF, WordProcessing, Spreadsheet и Presentation."
type: docs
weight: 820
url: /ru/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов: PDF, WordProcessing, Spreadsheet и Presentation.

```csharp
public interface IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Бинарное содержимое шрифта в виде массива байтов, если доступно, или `null`, если нет. |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Имя семейства шрифта в виде строки. |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Формат этого шрифта как перечисление — TrueType, TrueType Collection, OpenType, Embedded OpenType или Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Стиль шрифта как перечисление — Regular, Bold, Italic или Bold Italic. Некоторые форматы документов могут иметь шрифты только со стилем [`Regular`](../fontstyles/regular). |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |

### См. также

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
