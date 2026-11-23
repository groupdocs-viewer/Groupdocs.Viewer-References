---
title: "PdfOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации PDF‑документов."
type: docs
weight: 22
url: /ru/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Предоставляет параметры для визуализации PDF‑документов.


Класс PdfOptions инкапсулирует различные настройки и параметры, которые могут быть использованы
для управления рендерингом PDF‑документов в компоненте GroupDocs.Viewer.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Пример использования:

````

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
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Инициализирует новый экземпляр |
PdfOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Отключает защиту от копирования контента при рендеринге в HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Отключает защиту от копирования контента при рендеринге в HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Определяет, отображается ли текст из источника как изображение в HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Устанавливает, отображается ли текст из источника как изображение в HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Проверяет, отключена ли группировка символов для поддержания максимальной точности при позиционировании символов при рендеринге страницы. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Устанавливает параметр отключения группировки символов, обеспечивая максимальную точность при позиционировании символов при рендеринге страницы. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Проверяет, должен ли рендеринг текста и графики следовать порядку z в оригинальном PDF‑документе при рендеринге в HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Включает или отключает рендеринг текста и графики в соответствии с порядком z в оригинальном PDF‑документе при преобразовании в HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Определяет, включено ли сглаживание шрифтов. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Включает сглаживание шрифтов. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе. |
|
|  | [getImageQuality()](#getImageQuality--) | Получает качество выходных изображений для ресурсов изображений при рендеринге в HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Устанавливает качество выходных изображений для ресурсов изображений при рендеринге в HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Установите флаг, чтобы отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Инициализирует новый экземпляр
PdfOptions
класса.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Отключает защиту от копирования контента при рендеринге в HTML.


При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML, GroupDocs.Viewer добавляет атрибут HTML 'inert' к тегу BODY.
Значение по умолчанию для этой опции равно
false
.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Отключает защиту от копирования контента при рендеринге в HTML.


При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML, GroupDocs.Viewer добавляет атрибут HTML 'inert' к тегу BODY.
Значение по умолчанию для этой опции равно
false
.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Определяет, отображается ли текст из источника как изображение в HTML.


Когда эта опция установлена в
true
, текст рендерится как изображение в выходном HTML.
Включите эту опцию, чтобы сделать текст нечитаемым для выделения или исправить рендеринг символов и заставить HTML выглядеть как PDF.
Эта опция поддерживается при рендеринге в HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если текст рендерится как изображение в HTML,  false  в противном случае.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Устанавливает, отображается ли текст из источника как изображение в HTML.


Когда эта опция установлена в
true
, текст рендерится как изображение в выходном HTML.
Включите эту опцию, чтобы сделать текст нечитаемым для выделения или исправить рендеринг символов и заставить HTML выглядеть как PDF.
Эта опция поддерживается при рендеринге в HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  для отображения текста как изображения в HTML,  false  в противном случае. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Проверяет, отключена ли группировка символов для поддержания максимальной точности при позиционировании символов при рендеринге страницы.
Когда эта опция включена, символы отображаются без группировки, что обеспечивает максимальную точность.


***Note:** By default, character grouping is enabled.*
При конвертации PDF‑файлов GroupDocs.Viewer группирует отдельные символы в слова для повышения производительности рендеринга. Если ваш документ содержит иероглифы или специальные символы, вы можете запретить группировку символов, чтобы обеспечить более точную разметку. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean —  true  если группировка символов отключена,  false  в противном случае.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Устанавливает параметр отключения группировки символов, обеспечивая максимальную точность при позиционировании символов при рендеринге страницы.
Когда эта опция включена установкой значения в
true
, группировка символов отключена, что обеспечивает максимальную точность.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
При конвертации PDF‑файлов GroupDocs.Viewer группирует отдельные символы в слова для повышения производительности рендеринга. Если ваш документ содержит иероглифы или специальные символы, вы можете запретить группировку символов, чтобы обеспечить более точную разметку. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для отключения группировки символов,  false  для её включения. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Проверяет, должен ли рендеринг текста и графики следовать порядку z в оригинальном PDF‑документе при рендеринге в HTML.
Когда эта опция включена возвратом
true
, текст и графика рендерятся в соответствии с их z‑порядком в оригинальном PDF‑документе.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
По умолчанию GroupDocs.Veiewer отображает текст и графику как один слой в HTML. Эта опция позволяет расположить объекты в том же порядке, что и в исходном файле. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean —  true  если многослойный рендеринг включён,  false  в противном случае.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Включает или отключает рендеринг текста и графики в соответствии с порядком z в оригинальном PDF‑документе при преобразовании в HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
По умолчанию GroupDocs.Veiewer отображает текст и графику как один слой в HTML. Эта опция позволяет расположить объекты в том же порядке, что и в исходном файле. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения многослойного рендеринга,  false  для его отключения. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Определяет, включена ли подсказка шрифтов. Подсказка шрифтов корректирует отображение контурного шрифта.
Эта опция поддерживается только для шрифтов TrueType (TTF), используемых в исходном документе.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Подсказка шрифтов корректирует отображение контурного шрифта. Применяется только к TTF‑шрифтам, используемым в исходном документе. Эта опция доступна при рендеринге в форматы PNG или JPG. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean —  true  если подсказка шрифтов включена,  false  в противном случае.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Включает подсказку шрифтов. Подсказка шрифтов корректирует отображение контурного шрифта и поддерживается только для шрифтов TrueType (TTF), используемых в исходном документе.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Подсказка шрифтов корректирует отображение контурного шрифта. Применяется только к TTF‑шрифтам, используемым в исходном документе. Эта опция доступна при рендеринге в форматы PNG или JPG. Значение по умолчанию — false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения подсказки шрифтов,  false  для её отключения. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
По умолчанию GroupDocs.Viewer рассчитывает размер страниц выходного изображения для лучшего качества рендеринга. Включите эту опцию, чтобы гарантировать, что выходные страницы имеют тот же размер, что и страницы исходного PDF‑документа (в пикселях). Значение по умолчанию — false.
Эта опция доступна при рендеринге в форматы PNG или JPG.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean —  true  если опция включена,  false  в противном случае.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Включает рендеринг страниц с тем же размером в пикселях, что и размер страницы в исходном PDF‑документе.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
По умолчанию GroupDocs.Viewer рассчитывает размер страниц выходного изображения для лучшего качества рендеринга. Включите эту опцию, чтобы гарантировать, что выходные страницы имеют тот же размер, что и страницы исходного PDF‑документа (в пикселях). Значение по умолчанию — false.
Эта опция доступна при рендеринге в форматы PNG или JPG.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  чтобы включить рендеринг с оригинальным размером страницы,  false  в противном случае. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Получает качество выходного изображения для ресурсов изображений при рендеринге в HTML. Значение по умолчанию — Low.


Когда эта опция установлена в true, GroupDocs.Viewer рендерит текст как изображение в HTML‑выводе. Это делает текст нечитаемым для выделения и улучшает рендеринг символов, обеспечивая внешний вид, похожий на PDF, в HTML. Значение по умолчанию — false.
Эта опция доступна при рендеринге в HTML.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Устанавливает качество выходного изображения для ресурсов изображений при рендеринге в HTML. Значение по умолчанию — Low.


Когда эта опция установлена в true, GroupDocs.Viewer рендерит текст как изображение в HTML‑выводе. Это делает текст нечитаемым для выделения и улучшает рендеринг символов, обеспечивая внешний вид, похожий на PDF, в HTML. Значение по умолчанию — false.
Эта опция доступна при рендеринге в HTML.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Качество выходного изображения для ресурсов изображений при рендеринге в HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице.
Чтобы гарантировать, что выходной HTML выглядит так же, как исходный PDF, документы по умолчанию рендерятся в HTML с фиксированным макетом.
При рендеринге с фиксированным макетом выходной HTML имеет фиксированный размер, поэтому элементы остаются на тех же местах независимо от размера окна.
Чтобы рендерить в HTML с гибким макетом, установите это свойство в false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF и EPUB документы изначально рендерятся в HTML с фиксированным макетом, чтобы сохранить внешний вид исходного документа. Этот фиксированный макет означает, что все HTML‑элементы имеют точные позиции внутри контейнера с заданным размером. Изменение размера окна браузера не влияет на позицию и размер элементов в документе.
Эта опция доступна только при рендеринге в HTML. Значение по умолчанию — true. Чтобы рендерить с гибким макетом, установите это свойство в false.


Пример использования:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean — true, если это фиксированный макет

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF — фиксированный формат, поэтому все элементы имеют определённое место на странице.
Чтобы гарантировать, что выходной HTML выглядит так же, как исходный PDF, документы по умолчанию рендерятся в HTML с фиксированным макетом.
При рендеринге с фиксированным макетом выходной HTML имеет фиксированный размер, поэтому элементы остаются на тех же местах независимо от размера окна.
Чтобы рендерить в HTML с гибким макетом, установите это свойство в false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF и EPUB документы изначально рендерятся в HTML с фиксированным макетом, чтобы сохранить внешний вид исходного документа. Этот фиксированный макет означает, что все HTML‑элементы имеют точные позиции внутри контейнера с заданным размером. Изменение размера окна браузера не влияет на позицию и размер элементов в документе.
Эта опция доступна только при рендеринге в HTML. Значение по умолчанию — true. Чтобы рендерить с гибким макетом, установите это свойство в false.


Пример использования:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fixedLayout | boolean | true, если это фиксированный макет |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода.


Эта опция поддерживается при рендеринге [PDF и форматов Page Layout](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) в HTML с внедрёнными и внешними ресурсами.


По умолчанию при рендеринге в файлы PDF и Page Layout все изображения объединяются в одно PNG‑изображение. Полученное PNG‑изображение используется как фон для выходного HTML‑документа.


Узнать больше:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean —  true  если изображения обернуты в SVG,  false  в противном случае.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Включите эту опцию, чтобы обернуть каждое изображение в выходном HTML‑документе в тег SVG для повышения качества вывода.


Эта опция поддерживается при рендеринге [PDF и форматов Page Layout](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) в HTML с внедрёнными и внешними ресурсами.


По умолчанию при рендеринге в файлы PDF и Page Layout все изображения объединяются в одно PNG‑изображение. Полученное PNG‑изображение используется как фон для выходного HTML‑документа.


Узнать больше:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  если изображения должны быть обернуты в SVG,  false  в противном случае. |
|

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
|  | analyzeFonts | boolean | true, если шрифты должны отображаться, false в противном случае. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS.


Многие операции с шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта.
Например, некоторый шрифт нельзя встроить в PDF‑документ, если правила лицензии отключают встраивание этого шрифта.
Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий этот флаг, берёт на себя всю ответственность
за возможные нарушения лицензий/законов на себя. Поэтому они берут на себя весь риск. Настоятельно рекомендуется использовать
этот флаг только тогда, когда вы полностью уверены, что не нарушаете закон об авторском праве. По умолчанию false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Пример использования:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Установите флаг, чтобы отключить любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS.


Многие операции с шрифтом не могут быть выполнены, если эти операции запрещены лицензией данного шрифта.
Например, некоторый шрифт нельзя встроить в PDF‑документ, если правила лицензии отключают встраивание этого шрифта.
Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий этот флаг, берёт на себя всю ответственность
за возможные нарушения лицензий/законов на себя. Поэтому они берут на себя весь риск. Настоятельно рекомендуется использовать
этот флаг только тогда, когда вы полностью уверены, что не нарушаете закон об авторском праве. По умолчанию false.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Пример использования:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

