---
title: "PdfOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга PDF‑документов."
type: docs
weight: 22
url: /ru/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Предоставляет параметры для рендеринга PDF‑документов.

Класс PdfOptions инкапсулирует различные настройки и параметры, которые могут использоваться для управления рендерингом PDF‑документов в компоненте GroupDocs.Viewer. Для подробностей см. [documentation][].

Пример использования:

```

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Инициализирует новый экземпляр класса PdfOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Отключает защиту от копирования содержимого при рендеринге в HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Отключает защиту от копирования содержимого при рендеринге в HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Определяет, отображается ли текст из источника как изображение в HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Устанавливает, будет ли текст из источника отображаться как изображение в HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Проверяет, отключена ли группировка символов для поддержания максимальной точности при позиционировании символов во время рендеринга страницы. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Устанавливает параметр отключения группировки символов, обеспечивая максимальную точность при позиционировании символов во время рендеринга страницы. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Проверяет, следует ли рендерингу текста и графики соблюдать порядок z в оригинальном PDF‑документе при рендеринге в HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Включает или отключает рендеринг текста и графики в соответствии с порядком z в оригинальном PDF‑документе при рендеринге в HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Определяет, включена ли подсказка шрифтов. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Включает подсказку шрифтов. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе. |
| [getImageQuality()](#getImageQuality--) | Получает качество выходных изображений для графических ресурсов при рендеринге в HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Устанавливает качество выходных изображений для графических ресурсов при рендеринге в HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Пытается исправить проблему, когда всё содержимое HTML‑страницы является ссылкой. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Пытается исправить проблему, когда всё содержимое HTML‑страницы является ссылкой. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Отключает любые лицензионные ограничения для всех шрифтов в текущем документе XPS/OXPS. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Установите флаг, чтобы отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Инициализирует новый экземпляр класса PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Отключает защиту от копирования содержимого при рендеринге в HTML.

При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML, GroupDocs.Viewer добавляет атрибут HTML 'inert' к тегу BODY. Значение параметра по умолчанию — false.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Отключает защиту от копирования содержимого при рендеринге в HTML.

При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML, GroupDocs.Viewer добавляет атрибут HTML 'inert' к тегу BODY. Значение параметра по умолчанию — false.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Определяет, отображается ли текст из источника как изображение в HTML.

Когда этот параметр установлен в true, текст отображается как изображение в выводимом HTML. Включите этот параметр, чтобы сделать текст нечитаемым для выделения или исправить отображение символов и заставить HTML выглядеть как PDF. Этот параметр поддерживается при рендеринге в HTML.

***Note:** The default value is  false .*

**Returns:**
логический — true, если текст отображается как изображение в HTML, false — в противном случае.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Устанавливает, будет ли текст из источника отображаться как изображение в HTML.

Когда этот параметр установлен в true, текст отображается как изображение в выводимом HTML. Включите этот параметр, чтобы сделать текст нечитаемым для выделения или исправить отображение символов и заставить HTML выглядеть как PDF. Этот параметр поддерживается при рендеринге в HTML.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderTextAsImage | boolean | true — отображать текст как изображение в HTML, false — в противном случае. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Проверяет, отключена ли группировка символов для поддержания максимальной точности позиционирования символов при рендеринге страницы. Когда этот параметр включён, символы отображаются без какой‑либо группировки, что обеспечивает максимальную точность.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
логический — true, если группировка символов отключена, false — в противном случае.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Устанавливает параметр отключения группировки символов, обеспечивая максимальную точность позиционирования символов при рендеринге страницы. Когда этот параметр включён, задав значение true, группировка символов отключается, что гарантирует максимальную точность.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true — отключить группировку символов, false — включить её. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Проверяет, следует ли при рендеринге в HTML соблюдать порядок слоёв (z‑order) текста и графики, как в оригинальном PDF‑документе. Когда этот параметр включён (true), текст и графика рендерятся согласно их z‑order в оригинальном PDF‑документе.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
логический — true, если включён многослойный рендеринг, false — в противном случае.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Включает или отключает рендеринг текста и графики в соответствии с порядком z в оригинальном PDF‑документе при рендеринге в HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true — включить многослойный рендеринг, false — отключить его. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Определяет, включена ли подсказка шрифтов. Подсказка шрифтов корректирует отображение контурного шрифта. Этот параметр поддерживается только для шрифтов TrueType (TTF), используемых в исходном документе.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
логический — true, если подсказка шрифтов включена, false — в противном случае.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Включает подсказку шрифтов. Подсказка шрифтов корректирует отображение контурного шрифта и поддерживается только для шрифтов TrueType (TTF), используемых в исходном документе.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true — включить подсказку шрифтов, false — отключить её. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
логический — true, если параметр включён, false — в противном случае.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true — включить рендеринг с оригинальным размером страницы, false — в противном случае. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Получает качество выводимых изображений для ресурсов изображений при рендеринге в HTML. Значение по умолчанию — Low.

Когда этот параметр установлен в true, GroupDocs.Viewer отображает текст как изображение в выводимом HTML. Это делает текст нечитаемым для выделения и улучшает отображение символов, обеспечивая внешний вид, похожий на PDF, в HTML. Значение по умолчанию — false. Этот параметр доступен при рендеринге в HTML. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Устанавливает качество выводимых изображений для ресурсов изображений при рендеринге в HTML. Значение по умолчанию — Low.

Когда этот параметр установлен в true, GroupDocs.Viewer отображает текст как изображение в выводимом HTML. Это делает текст нечитаемым для выделения и улучшает отображение символов, обеспечивая внешний вид, похожий на PDF, в HTML. Значение по умолчанию — false. Этот параметр доступен при рендеринге в HTML. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Качество выводимых изображений для ресурсов изображений при рендеринге в HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. Чтобы гарантировать, что выводимый HTML выглядит так же, как исходный PDF, документы по умолчанию рендерятся в HTML с фиксированным макетом. При рендеринге с фиксированным макетом выводимый HTML имеет фиксированный размер, поэтому элементы остаются на тех же местах независимо от размера окна. Чтобы рендерить HTML с гибким макетом, установите это свойство в false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Пример использования:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean — true, если используется фиксированный макет
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. Чтобы гарантировать, что выводимый HTML выглядит так же, как исходный PDF, документы по умолчанию рендерятся в HTML с фиксированным макетом. При рендеринге с фиксированным макетом выводимый HTML имеет фиксированный размер, поэтому элементы остаются на тех же местах независимо от размера окна. Чтобы рендерить HTML с гибким макетом, установите это свойство в false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Пример использования:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fixedLayout | boolean | true, если используется фиксированный макет |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода.

Эта опция поддерживается при рендеринге [PDF and Page Layout file formats][] в HTML с встроенными и внешними ресурсами.

По умолчанию при рендеринге в PDF и файлы Page Layout все изображения объединяются в одно PNG‑изображение. Сгенерированное PNG‑изображение используется как фон для выводимого HTML‑документа.

Узнать больше:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean —  true, если изображения обернуты в SVG,  false — в противном случае.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода.

Эта опция поддерживается при рендеринге [PDF and Page Layout file formats][] в HTML с встроенными и внешними ресурсами.

По умолчанию при рендеринге в PDF и файлы Page Layout все изображения объединяются в одно PNG‑изображение. Сгенерированное PNG‑изображение используется как фон для выводимого HTML‑документа.

Узнать больше:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true, если изображения должны быть обернуты в SVG, false — в противном случае. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Пытается исправить проблему, когда всё содержимое HTML‑страницы является ссылкой. Работает только когда входной формат — PDF, а выходной — HTML (с встроенными или внешними ресурсами). По умолчанию отключено (false). Включайте только если точно знаете, что делаете и зачем. Включение этой опции увеличивает время обработки документа.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Пытается исправить проблему, когда всё содержимое HTML‑страницы является ссылкой. Работает только когда входной формат — PDF, а выходной — HTML (с встроенными или внешними ресурсами). По умолчанию отключено (false). Включайте только если точно знаете, что делаете и зачем. Включение этой опции увеличивает время обработки документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fixLinkIssue | boolean | true, если проблему следует исправить, false — в противном случае. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| analyzeFonts | boolean | true, если шрифты должны отображаться, false — в противном случае. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Отключает любые лицензионные ограничения для всех шрифтов в текущем документе XPS/OXPS.

Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта. Например, некоторые шрифты нельзя встраивать в PDF‑документ, если правила лицензии запрещают встраивание этого шрифта. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторские права. По умолчанию false. Пример кода см. в [documentation][].

Пример использования:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Установите флаг, чтобы отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS.

Многие операции со шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта. Например, некоторые шрифты нельзя встраивать в PDF‑документ, если правила лицензии запрещают встраивание этого шрифта. Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторские права. По умолчанию false. Пример кода см. в [documentation][].

Пример использования:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

