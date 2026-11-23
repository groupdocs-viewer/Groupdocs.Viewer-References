---
title: "PresentationFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из документа Presentation, загруженного в экземпляр Viewer../groupdocs.viewer/viewer. Этот шрифт используется в содержимом документа и встроен в сам документ или установлен в операционной системе, где работает GroupDocs.Viewer."
type: docs
weight: 850
url: /ru/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Инкапсулирует метаданные и бинарные данные одного шрифта из документа Presentation, загруженного в экземпляр [`Viewer`](../../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ или установлен в операционной системе, где работает GroupDocs.Viewer.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Содержимое этого шрифта в виде массива байтов. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Имя семейства шрифта без стиля, никогда не является null или пустой строкой. |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Формат этого шрифта. Документы могут использовать шрифты следующих форматов: TrueType, TrueType Collection, OpenType, Embedded OpenType. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает значение Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Указывает, встроен ли этот шрифт в документ, загруженный в экземпляр [`Viewer`](../../groupdocs.viewer/viewer) (`true`), или это системный шрифт (`false`). Таблицы не могут содержать встроенные шрифты, поэтому для них это свойство всегда возвращает `false`. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Стиль шрифта — может быть Regular, Bold, Italic или Bold Italic |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |

### См. также

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
