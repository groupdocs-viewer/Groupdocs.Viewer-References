---
title: "WordProcessingFontInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer../groupdocs.viewer/viewer. Этот шрифт используется в содержимом документа и встроен в сам документ или установлен в операционной системе, где запущен GroupDocs.Viewer."
type: docs
weight: 880
url: /ru/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр [`Viewer`](../../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ или установлен в операционной системе, где работает GroupDocs.Viewer.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Альтернативное семейное имя шрифта. Если отсутствует, то пустая строка. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Набор символов этого шрифта |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Содержимое этого шрифта в виде массива байтов. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Имя семейства шрифта без стиля, никогда не является null или пустой строкой. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Формат этого шрифта. Документы могут использовать шрифты следующих форматов: TrueType, TrueType Collection, OpenType, Embedded OpenType. Если доступны только метаданные о шрифте, но его бинарное содержимое недоступно, это свойство возвращает значение Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Указывает, встроен ли этот шрифт в документ, загруженный в экземпляр [`Viewer`](../../groupdocs.viewer/viewer) (`true`), или это системный шрифт (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Стиль шрифта — может быть Regular, Bold, Italic или Bold Italic. |

## Методы

| Имя | Описание |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый writer. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Возвращает отладочную информацию о данных этого шрифта в виде следующего шаблона: "name style, embedded/system, format" |

### Примечания

Неизменяемая структура. Ее экземпляры создаются и возвращаются публичным API GroupDocs.Viewer и обычно не должны создаваться пользователем. Подробнее см. [документацию](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### См. также

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
