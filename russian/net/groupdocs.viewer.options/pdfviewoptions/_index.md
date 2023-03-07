---
title: PdfViewOptions
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Предоставляет параметры для преобразования документов в формат PDF.
type: docs
weight: 420
url: /ru/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Предоставляет параметры для преобразования документов в формат PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Инициализирует новый экземпляр[`PdfViewOptions`](../pdfviewoptions) класс. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Инициализирует новый экземпляр[`PdfViewOptions`](../pdfviewoptions) класс. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Инициализирует новый экземпляр[`PdfViewOptions`](../pdfviewoptions) класс. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Инициализирует новый экземпляр[`PdfViewOptions`](../pdfviewoptions) класс. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Инициализирует новый экземпляр[`PdfViewOptions`](../pdfviewoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры вида чертежа САПР. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Шрифт по умолчанию, который будет использоваться, если конкретный шрифт, используемый в документе, не может быть найден. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра сообщений электронной почты. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Высота выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Максимальная высота выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Максимальная ширина выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Ширина выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Качество изображений JPG, содержащихся в выходном PDF-документе; Допустимые значения от 1 до 100; Значение по умолчанию: 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Уменьшите размер выходного файла, исключив распространенные шрифты, такие как Times New Roman и Arial, и применив другие методы оптимизации. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF-документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра документов обработки презентации. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектом. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Включает визуализацию комментариев. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает визуализацию заметок. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Параметры безопасности выходного PDF-документа. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры разделения текстовых файлов на страницы. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра документов обработки файлов Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Текстовый водяной знак, применяемый к каждой странице. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге веб-документов. |
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
* пространство имен [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* сборка [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
