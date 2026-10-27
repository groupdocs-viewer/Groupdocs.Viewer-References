---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры, используемые для получения информации о представлении."
type: docs
weight: 34
url: /ru/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Предоставляет параметры, используемые для получения информации о представлении.

Класс ViewInfoOptions инкапсулирует дополнительные настройки и параметры, которые могут использоваться для получения информации о представлении в компоненте GroupDocs.Viewer.

Пример использования:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Методы

| Метод | Описание |
| --- | --- |
| [isExtractText()](#isExtractText--) | Указывает, включено ли извлечение текста. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Устанавливает флаг, указывающий, включено ли извлечение текста. |
| [getMaxWidth()](#getMaxWidth--) | Возвращает максимальную ширину выходного изображения для рендеринга в PNG/JPG. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [getMaxHeight()](#getMaxHeight--) | Возвращает максимальную высоту выходного изображения для рендеринга в PNG/JPG. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [getWidth()](#getWidth--) | Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [setWidth(int width)](#setWidth-int-) | Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [getHeight()](#getHeight--) | Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [setHeight(int height)](#setHeight-int-) | Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [forHtmlView()](#forHtmlView--) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в HTML. |
| [forJpgView()](#forJpgView--) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в JPG. |
| [forPngView()](#forPngView--) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в PNG. |
| [forPdfView()](#forPdfView--) | Инициализирует новый экземпляр класса ViewInfoOptions для получения информации о представлении при рендеринге в PDF. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions). |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions). |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions). |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Инициализирует новый экземпляр класса [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) на основе объекта PdfViewOptions. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Указывает, включено ли извлечение текста.

Используйте это свойство, чтобы получить текст, содержащийся в исходном документе, и его координаты. Затем вы можете использовать эти данные, чтобы добавить выделяемый текст поверх изображения или реализовать поиск текста в рендеринге на основе изображений. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean — True, если извлечение текста включено, иначе false.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Устанавливает флаг, указывающий, включено ли извлечение текста.

Используйте это свойство, чтобы получить текст, содержащийся в исходном документе, и его координаты. Затем вы можете использовать эти данные, чтобы добавить выделяемый текст поверх изображения или реализовать поиск текста в рендеринге на основе изображений. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| extractText | boolean | True — включить извлечение текста, false — отключить. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Возвращает максимальную ширину выходного изображения для рендеринга в PNG/JPG.

Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int — максимальная ширина выходного изображения.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Устанавливает максимальную ширину выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxWidth | int | Максимальная ширина выходного изображения. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Возвращает максимальную высоту выходного изображения для рендеринга в PNG/JPG.

Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int — максимальная высота выходного изображения.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Устанавливает максимальную высоту выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxHeight | int | Максимальная высота выходного изображения. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int — ширина изображения.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int — высота изображения.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG).

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | int | Высота изображения. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в HTML.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderSinglePage | boolean | Позволяет отобразить HTML‑контент на одной странице. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в JPG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| extractText | boolean | Включает извлечение текста. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Инициализирует новый экземпляр класса  ViewInfoOptions  для получения информации о представлении при рендеринге в PNG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| extractText | boolean | Включает извлечение текста. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Инициализирует новый экземпляр класса ViewInfoOptions для получения информации о представлении при рендеринге в PDF.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Параметры просмотра HTML. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Параметры просмотра PNG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Инициализирует новый экземпляр класса ViewInfoOptions на основе объекта [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Параметры просмотра JPG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Инициализирует новый экземпляр класса [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) на основе объекта PdfViewOptions.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Параметры просмотра PDF. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
