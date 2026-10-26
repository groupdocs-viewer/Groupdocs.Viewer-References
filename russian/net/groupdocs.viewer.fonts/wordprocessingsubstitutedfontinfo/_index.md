---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в документе, загруженном в экземпляр Viewer../groupdocs.viewer/viewer, но служит заменяющим шрифтом для тех, которые не могут быть найдены на целевой машине. Заменяющие шрифты существуют только для семейства форматов WordProcessing."
type: docs
weight: 890
url: /ru/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в документе, загруженном в экземпляр [`Viewer`](../../groupdocs.viewer/viewer), но служит заменяющим шрифтом для тех, которые не могут быть найдены на целевой машине. Заменяющие шрифты существуют только для семейства форматов WordProcessing.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Содержимое этого заменяющего шрифта в виде массива байтов. Никогда не `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | Имя семейства **substituted** шрифта без стиля, никогда не null и не пустая строка. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Формат этого заменяющего (не оригинального) шрифта. Может быть TrueType, TrueType Collection, OpenType, Embedded OpenType. Для заменяющего шрифта, поскольку его бинарное содержимое доступно по определению, это свойство никогда не возвращает значение Unknown. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Имя семейства оригинального шрифта, который не может быть найден на целевой машине, без стиля, никогда не null и не пустая строка. |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Стиль оригинального шрифта — может быть Regular, Bold, Italic или Bold Italic. Заменяющий шрифт обычно (но не всегда) имеет тот же стиль. |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Возвращает отладочную информацию об этих данных шрифта в виде шаблона: "original-name -> substituted-name style, format" |

### Примечания

Неизменяемая структура. Ее экземпляры создаются и возвращаются публичным API GroupDocs.Viewer и обычно не должны создаваться пользователем. Подробнее см. [документацию](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### См. также

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
