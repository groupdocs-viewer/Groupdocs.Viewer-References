---
title: ViewInfoOptions
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Предоставляет параметры используемые для получения информации о представлении.
type: docs
weight: 570
url: /ru/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Предоставляет параметры, используемые для получения информации о представлении.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры вида чертежа САПР. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Шрифт по умолчанию, который будет использоваться, если конкретный шрифт, используемый в документе, не может быть найден. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра сообщений электронной почты. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Указывает, что извлечение текста включено. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Высота изображения (только для рендеринга в PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Максимальная высота выходного изображения (только для рендеринга в PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Максимальная ширина выходного изображения (только для рендеринга в PNG/JPG) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF-документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра документов обработки презентации. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектом. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Включает визуализацию комментариев. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает визуализацию заметок. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры разделения текстовых файлов на страницы. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра документов обработки файлов Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге веб-документов. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Ширина изображения (только для рендеринга в PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге документов Word. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс для получения информации о представлении при рендеринге в PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс, основанный на[`HtmlViewOptions`](../htmlviewoptions) объект. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс, основанный на[`JpgViewOptions`](../jpgviewoptions) объект. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Инициализирует новый экземпляр[`ViewInfoOptions`](../viewinfooptions) класс, основанный на[`PngViewOptions`](../pngviewoptions) объект. |

### Смотрите также

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* пространство имен [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* сборка [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
