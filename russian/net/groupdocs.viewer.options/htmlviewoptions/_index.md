---
title: "HtmlViewOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для рендеринга документов в формате HTML. Подробности см. в теме https//docs.groupdocs.com/viewer/net/renderingtohtml/ и её дочерних элементах."
type: docs
weight: 320
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Содержит параметры для рендеринга документов в формат HTML. Для подробностей см. [тему](https://docs.groupdocs.com/viewer/net/rendering-to-html/) и её дочерние элементы.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Параметры просмотра архивных файлов. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Параметры просмотра чертежей CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Устанавливает шрифт по умолчанию для документа. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Параметры просмотра электронных сообщений. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Отключает добавление любых шрифтов в HTML‑документ. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Список названий шрифтов, исключаемых из HTML‑документа. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Включает оптимизацию выходного HTML для печати. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Высота выходного изображения (в пикселях). Свойство доступно только при преобразовании отдельного изображения в HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Максимальная высота выходного изображения (в пикселях). Свойство доступно только при преобразовании одного изображения в HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Максимальная ширина выходного изображения (в пикселях). Свойство доступно только при преобразовании одного изображения в HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Ширина выходного изображения (в пикселях). Свойство доступно только при преобразовании одного изображения в HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Параметры просмотра файлов данных почтового хранилища. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Включает минификацию HTML‑контента и HTML‑ресурсов. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Параметры просмотра файлов данных Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Параметры просмотра PDF‑документов. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Параметры просмотра файлов презентаций. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Параметры просмотра файлов управления проектами. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Отключает отображение комментариев, когда установлено `true`. По умолчанию `false` — все комментарии отображаются. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Позволяет удалить исходный код JavaScript из ссылок в результирующих HTML‑документах при рендеринге входных документов, содержащих скрипты. По умолчанию включено (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Включает отображение скрытых страниц. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Включает отображение заметок и аннотаций для некоторых форматов |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Включает адаптивный рендеринг. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Включает рендеринг всего документа в один HTML‑файл. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Параметры просмотра файлов электронных таблиц. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Параметры просмотра текстовых файлов. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Параметры просмотра файлов Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Текстовый водяной знак, применяемый к каждой странице. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Параметры просмотра веб‑файлов. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Параметры просмотра файлов обработки текста. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с внешними ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с внешними ресурсами. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Инициализирует экземпляр класса [`HtmlViewOptions`](../htmlviewoptions) для рендеринга в HTML с внешними ресурсами. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Применяет вращение по часовой стрелке к странице. |

## Поля

| Имя | Описание |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Вращение страницы. |

### См. также

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
