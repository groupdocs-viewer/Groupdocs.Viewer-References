---
title: "PdfFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из PDF‑документа, загруженного в экземпляр Viewer../groupdocs.viewer/viewer. Этот шрифт используется в содержимом документа и встроен в сам документ либо установлен в операционной системе, где работает GroupDocs.Viewer."
type: docs
weight: 840
url: /ru/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

Инкапсулирует метаданные и бинарные данные одного шрифта из PDF‑документа, загруженного в экземпляр [`Viewer`](../../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ либо установлен в операционной системе, где работает GroupDocs.Viewer.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Содержимое этого шрифта в виде массива байтов. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Имя семейства шрифта без стиля, никогда не является null или пустой строкой. |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Формат этого шрифта. Документы могут использовать шрифты следующих форматов: TrueType, TrueType Collection, OpenType, Embedded OpenType. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает значение Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Указывает, встроен ли этот шрифт в PDF‑документ, загруженный в экземпляр [`Viewer`](../../groupdocs.viewer/viewer) (`true`), или нет. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Указывает, присутствует ли этот шрифт (установлен) в операционной системе, где запущен GroupDocs.Viewer |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Стиль шрифта — может быть Regular, Bold, Italic или Bold Italic. |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |

### См. также

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
