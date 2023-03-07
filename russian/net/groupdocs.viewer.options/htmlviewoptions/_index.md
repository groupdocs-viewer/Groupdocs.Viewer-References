---
title: HtmlViewOptions
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Предоставляет параметры для преобразования документов в формат HTML.
type: docs
weight: 330
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Предоставляет параметры для преобразования документов в формат HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры вида чертежа САПР. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Шрифт по умолчанию, который будет использоваться, если конкретный шрифт, используемый в документе, не может быть найден. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра сообщений электронной почты. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Когда включено, запрещает добавлять какие-либо шрифты в документ HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Список имен шрифтов, которые необходимо исключить из документа HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Указывает, следует ли оптимизировать вывод HTML для печати. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Высота выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Максимальная высота выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Максимальная ширина выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Ширина выходного изображения в пикселях. (только при преобразовании одного изображения в HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Включает минимизацию содержимого HTML и ресурсов HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF-документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра документов обработки презентации. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектом. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Включает визуализацию комментариев. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает визуализацию заметок. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Включает адаптивный рендеринг; Адаптивные веб-страницы хорошо отображаются на устройствах с разным размером экрана. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Включает визуализацию всего документа в один файл HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры разделения текстовых файлов на страницы. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра документов обработки файлов Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Текстовый водяной знак, применяемый к каждой странице. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге веб-документов. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Эти параметры рендеринга позволяют настроить внешний вид выходного HTML/PDF/PNG/JPEG при рендеринге документов Word. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML со встроенными ресурсами. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML со встроенными ресурсами. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML со встроенными ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Инициализирует новый экземпляр[`HtmlViewOptions`](../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами. |
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
