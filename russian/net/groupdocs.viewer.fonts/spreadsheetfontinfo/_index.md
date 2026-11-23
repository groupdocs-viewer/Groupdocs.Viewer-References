---
title: "SpreadsheetFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer../groupdocs.viewer/viewer. Таблицы не могут иметь встроенные шрифты, поэтому этот конкретный шрифт, если он был возвращён методом GetAllFonts../groupdocs.viewer/viewer/getallfonts, установлен в операционной системе, где работает GroupDocs.Viewer."
type: docs
weight: 870
url: /ru/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Инкапсулирует метаданные и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр [`Viewer`](../../groupdocs.viewer/viewer). Таблицы не могут иметь встроенные шрифты, поэтому этот конкретный шрифт, если он был возвращён методом [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts), установлен в операционной системе, где работает GroupDocs.Viewer.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Набор символов этого шрифта |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Цвет этого шрифта |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Содержимое этого шрифта в виде массива байтов. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Имя семейства шрифта без стиля, никогда не является null или пустой строкой. |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Формат этого шрифта |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Указывает, имеет ли шрифт одиночное зачеркивание |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Указывает, имеет ли шрифт подчеркивание |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Стиль этого шрифта — может быть Regular, Bold, Italic или Bold Italic |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |

### См. также

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
