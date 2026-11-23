---
title: "WordProcessingOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для отрисовки Word‑документов. Подробнее см. документацию https://docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /ru/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Содержит параметры для рендеринга документов Word. Для подробностей см. [документацию](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Содержит параметры для отрисовки документов обработки текста. Подробнее см. [документацию](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Устанавливает нижнее поле страницы. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Эта опция включает кернинг и другие функции OpenType при рендеринге арабских, ивритских, индийских латинских или кириллических скриптов. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Устанавливает левый отступ страницы. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Позволяет принудительно применить нумерацию страниц к загруженному документу WordProcessing. По умолчанию — NotApply, документ остаётся неизменным. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | Размер выходной страницы. Значение по умолчанию — Unspecified, что означает, что используется размер страницы, заданный в настройках страницы (Page Setup). При рендеринге файлов HTM и HTML размер страницы по умолчанию устанавливается как Letter 792 × 612 пунктов. В результате часть содержимого может не помещаться в рамку страницы. Установите больший размер страницы, например A3, чтобы разместить содержимое. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Включает рендеринг отслеживаемых изменений (ревизий). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Устанавливает правый отступ страницы. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Устанавливает верхний отступ страницы. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | При рендеринге в HTML или PDF вы можете установить эту опцию в `true`, чтобы отключить навигацию из оглавления. При рендеринге HTML теги `a` с относительными ссылками будут заменены на теги `span`, что удалит функциональность, но сохранит визуальный вид. При рендеринге PDF оглавление будет выводиться как простой текст без ссылок на разделы документа. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Получает или задает значение, определяющее, должны ли поля определённых типов обновляться перед сохранением входного документа WordProcessing в форматы HTML, PDF, PNG или JPEG. Значение по умолчанию для этого свойства — `true`, поля будут обновлены перед сохранением. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Получает или задает вертикальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Создаёт и возвращает полную глубокую копию этих параметров |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Определяет, равен ли указанный экземпляр [`WordProcessingOptions`](../wordprocessingoptions) текущему |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
