---
title: "ViewInfoOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для получения информации о представлении."
type: docs
weight: 580
url: /ru/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Содержит параметры для получения информации о представлении.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры просмотра чертежей CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Устанавливает шрифт по умолчанию для документа. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра электронных сообщений. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Включает извлечение текста. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Устанавливает максимальную высоту выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Устанавливает максимальную ширину выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
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
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Параметры просмотра веб‑файлов. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Параметры просмотра файлов обработки текста. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) для получения информации о представлении при рендеринге в PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) на основе объекта [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) на основе объекта [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) на основе объекта [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Инициализирует экземпляр класса [`ViewInfoOptions`](../viewinfooptions) на основе объекта [`PngViewOptions`](../pngviewoptions). |

### См. также

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
