---
title: JpgViewOptions
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Предоставляет параметры для рендеринга документов в формате JPG.
type: docs
weight: 360
url: /ru/net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

Предоставляет параметры для рендеринга документов в формате JPG.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Инициализирует новый экземпляр[`JpgViewOptions`](../jpgviewoptions) класс. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Инициализирует новый экземпляр[`JpgViewOptions`](../jpgviewoptions) класс. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Инициализирует новый экземпляр[`JpgViewOptions`](../jpgviewoptions) класс. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Инициализирует новый экземпляр[`JpgViewOptions`](../jpgviewoptions) класс. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр[`JpgViewOptions`](../jpgviewoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры вида чертежа САПР. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Шрифт по умолчанию, который будет использоваться, если конкретный шрифт, используемый в документе, не может быть найден. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра сообщений электронной почты. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Включает извлечение текста. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Высота выходного изображения в пикселях. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Максимальная высота выходного изображения в пикселях. |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Максимальная ширина выходного изображения в пикселях. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF-документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра документов обработки презентации. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектом. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Качество выходного изображения; Допустимые значения от 1 до 100; Значение по умолчанию: 90. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Включает визуализацию комментариев. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает визуализацию заметок. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры разделения текстовых файлов на страницы. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра документов обработки файлов Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Текстовый водяной знак, применяемый к каждой странице. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге веб-документов. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Ширина выходного изображения в пикселях. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге документов Word. |

## Методы

| Имя | Описание |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Применяет вращение страницы по часовой стрелке. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Повороты страниц. |

### Смотрите также

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* пространство имен [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* сборка [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
