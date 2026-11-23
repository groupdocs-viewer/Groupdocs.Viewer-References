---
title: "PngViewOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для рендеринга документов в формат PNG. Подробнее см. эту страницу https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ и её дочерние элементы."
type: docs
weight: 440
url: /ru/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Содержит параметры для рендеринга документов в формат PNG. Для подробностей см. эту [страницу](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) и её дочерние элементы.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Инициализирует экземпляр класса [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Инициализирует экземпляр класса [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Инициализирует экземпляр класса [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Инициализирует экземпляр класса [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Инициализирует экземпляр класса [`PngViewOptions`](../pngviewoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры просмотра чертежей CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Устанавливает шрифт по умолчанию для документа. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра электронных сообщений. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Включает извлечение текста. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Устанавливает высоту выходного изображения (в пикселях). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Устанавливает максимальную высоту выходного изображения (в пикселях). |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Устанавливает максимальную ширину выходного изображения (в пикселях). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF‑документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра файлов презентаций. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектами. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Отключает отображение комментариев, когда установлено `true`. По умолчанию `false` — все комментарии отображаются. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает отображение заметок и аннотаций для некоторых форматов |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры просмотра текстовых файлов. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра файлов Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Текстовый водяной знак, применяемый к каждой странице. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Параметры просмотра веб‑файлов. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Ширина выходного изображения (в пикселях). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Параметры просмотра файлов обработки текста. |

## Методы

| Имя | Описание |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Применяет вращение по часовой стрелке к странице. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Вращение страницы. |

### См. также

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
