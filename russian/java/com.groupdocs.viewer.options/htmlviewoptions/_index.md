---
title: "HtmlViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для рендеринга документов в формат HTML."
type: docs
weight: 16
url: /ru/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Предоставляет параметры для рендеринга документов в формат HTML.


Класс HtmlViewOptions инкапсулирует дополнительные настройки и параметры
которые могут использоваться для управления рендерингом документов в формате HTML в компоненте GroupDocs.Viewer.


Для деталей см. [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) и его дочерние элементы.


Пример использования:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | Определяет, включен ли адаптивный рендеринг. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Устанавливает, включен ли адаптивный рендеринг. |
|
|  | [isMinify()](#isMinify--) | Проверяет, включена ли минификация HTML‑контента и HTML‑ресурсов. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | Устанавливает, включена ли минификация HTML‑контента и HTML‑ресурсов. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | Включает рендеринг всего документа в один HTML‑файл. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Включает рендеринг всего документа в один HTML‑файл. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Возвращает максимальную ширину выходного изображения в пикселях. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Получает максимальную высоту выходного изображения в пикселях. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
|
|  | [getImageWidth()](#getImageWidth--) | Получает ширину выходного изображения в пикселях. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
|
|  | [getImageHeight()](#getImageHeight--) | Получает высоту выходного изображения в пикселях при конвертации одного изображения в HTML. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Устанавливает высоту выходного изображения в пикселях при конвертации одного изображения в HTML. |
|
|  | [isForPrinting()](#isForPrinting--) | Проверяет, следует ли оптимизировать выходной HTML для печати. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | Устанавливает, следует ли оптимизировать выходной HTML для печати. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | Определяет, следует ли исключать шрифты из HTML‑документа. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Устанавливает, следует ли исключать шрифты из HTML‑документа. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | Получает список названий шрифтов, которые нужно исключить из HTML‑документа. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Устанавливает список названий шрифтов, которые следует исключить из HTML‑документа. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | Позволяет удалять исходный код JavaScript из ссылок в результирующих HTML‑документах при рендеринге входных документов, содержащих скрипты. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Устанавливает разрешение на удаление исходного кода JavaScript из ссылок в результирующих HTML‑документах при рендеринге входных документов, содержащих скрипты. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов, используемый для оценки прогресса сохранения документа Word или Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Word или Email. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | Инициализирует новый экземпляр |
HtmlViewOptions
класса.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Инициализирует новый экземпляр |
HtmlViewOptions
класса.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Инициализирует новый экземпляр |
HtmlViewOptions
класса.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Инициализирует новый экземпляр |
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.
|
|  | [forExternalResources()](#forExternalResources--) | Инициализирует новый экземпляр |
HtmlViewOptions
класса.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр |
HtmlViewOptions
класса.
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Определяет, включен ли адаптивный рендеринг.
Адаптивные веб‑страницы корректно отображаются на устройствах с разными размерами экрана.


Адаптивный дизайн направлен на корректное отображение веб‑страниц на различных устройствах. Чтобы отобразить страницу с адаптивным макетом, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Returns:**
boolean —  true  если адаптивный рендеринг включён,  false  в противном случае.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Устанавливает, включен ли адаптивный рендеринг.
Адаптивные веб‑страницы корректно отображаются на устройствах с разными размерами экрана.


Адаптивный дизайн направлен на корректное отображение веб‑страниц на различных устройствах. Чтобы отобразить страницу с адаптивным макетом, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения адаптивного рендеринга,  false  для его отключения. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Проверяет, включена ли минификация HTML‑контента и HTML‑ресурсов.


Сжатие выходного контента (HTML, CSS и SVG) — один из способов оптимизировать HTML‑файл. Чтобы выполнить это, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Returns:**
boolean —  true  если минификация включена,  false  в противном случае.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Устанавливает, включена ли минификация HTML‑контента и HTML‑ресурсов.


Сжатие выходного контента (HTML, CSS и SVG) — один из способов оптимизировать HTML‑файл. Чтобы выполнить это, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения минификации,  false  для её отключения. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Включает рендеринг всего документа в один HTML‑файл.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Включает рендеринг всего документа в один HTML‑файл.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Возвращает максимальную ширину выходного изображения в пикселях.
***Note:** This value is used when converting a single image to HTML.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - максимальная ширина выходного изображения.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях.
***Note:** This value is used when converting a single image to HTML.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageMaxWidth | int | Максимальная ширина выходного изображения. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Получает максимальную высоту выходного изображения в пикселях.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - максимальная высота выходного изображения.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageMaxHeight | int | Максимальная высота выходного изображения. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Получает ширину выходного изображения в пикселях.


***Note:** This value is applicable only when converting a single image to HTML.*
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - ширина выходного изображения.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Устанавливает ширину выходного изображения в пикселях.


***Note:** This value is applicable only when converting a single image to HTML.*
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageWidth | int | Ширина выходного изображения. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Получает высоту выходного изображения в пикселях при конвертации одного изображения в HTML.


Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - высота выходного изображения в пикселях.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Устанавливает высоту выходного изображения в пикселях при конвертации одного изображения в HTML.


Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageHeight | int | Высота выходного изображения в пикселях. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Проверяет, следует ли оптимизировать выходной HTML для печати.


Включите эту опцию, чтобы преобразовать выходные HTML‑страницы в векторный формат SVG.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  если выходной HTML должен быть оптимизирован для печати,  false  в противном случае.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Устанавливает, следует ли оптимизировать выходной HTML для печати.


Включите эту опцию, чтобы преобразовать выходные HTML‑страницы в векторный формат SVG.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для оптимизации выходного HTML для печати,  false  в противном случае. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Определяет, следует ли исключать шрифты из HTML‑документа.


По умолчанию GroupDocs.Viewer встраивает шрифты, используемые в документе, в HTML. Чтобы предотвратить это, установите это свойство в true.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  если шрифты следует исключить,  false  в противном случае.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Устанавливает, следует ли исключать шрифты из HTML‑документа.


По умолчанию GroupDocs.Viewer встраивает шрифты, используемые в документе, в HTML. Чтобы предотвратить это, установите это свойство в true.
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для исключения шрифтов,  false  в противном случае. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Получает список названий шрифтов, которые нужно исключить из HTML‑документа.


Эта опция поддерживается только для презентаций.
Включение шрифтов в HTML‑документ улучшает стабильность отображения, но увеличивает размер результата рендеринга.
Используйте эту опцию, чтобы найти компромисс между стабильностью и размером вывода.
Включайте названия шрифтов, которые популярны и установлены на большинстве систем.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) опция отключена.*
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> - список названий шрифтов для исключения из HTML‑документа.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Устанавливает список названий шрифтов, которые следует исключить из HTML‑документа.


Эта опция поддерживается только для презентаций.
Включение шрифтов в HTML‑документ улучшает стабильность отображения, но увеличивает размер результата рендеринга.
Используйте эту опцию, чтобы найти компромисс между стабильностью и размером вывода.
Включайте названия шрифтов, которые популярны и установлены на большинстве систем.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) опция отключена.*
Для получения подробностей и примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Список названий шрифтов для исключения из HTML‑документа. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Позволяет удалять исходный код JavaScript из ссылок в результирующих HTML‑документах при рендеринге входных документов, содержащих скрипты. По умолчанию включено (true).


Подробности об удалении JavaScript см. в [документации](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Устанавливает разрешение на удаление исходного кода JavaScript из ссылок в результирующих HTML‑документах при рендеринге входных документов, содержащих скрипты. По умолчанию включено (true).


Подробности об удалении JavaScript см. в [документации](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов, используемый для оценки прогресса сохранения документа Word или Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback — обратный вызов, используемый для оценки прогресса сохранения документа.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Word или Email.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов, используемый для оценки прогресса сохранения документа. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.


***Note:** The method takes a 
CreatePageStream
параметр, представляющий метод, используемый для создания потока записи данных выходной страницы.*
Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Метод, который освобождает поток, созданный методом, назначенным параметру  createPageStream . |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с встроенными ресурсами.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходной страницы. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Инициализирует новый экземпляр
HtmlViewOptions
класса.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Инициализирует новый экземпляр
HtmlViewOptions
класса.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Формат пути к файлу, например, 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Инициализирует новый экземпляр
HtmlViewOptions
класса.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Формат пути к файлу, например, 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Метод, который освобождает поток, созданный методом  createPageStream . |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Метод, который создает URL для HTML‑ресурса. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Метод, который создает поток, используемый для записи данных выходного HTML‑ресурса. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Метод, который создает URL для HTML‑ресурса. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Метод, который освобождает поток, созданный методом  createPageStream . |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Метод, который освобождает поток, созданный методом  createResourceStream . |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Инициализирует новый экземпляр
HtmlViewOptions
класс для рендеринга в HTML с внешними ресурсами.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходной страницы. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Фабрика, реализующая методы создания URL ресурсов и создания/освобождения потока выходного HTML‑ресурса. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Инициализирует новый экземпляр
HtmlViewOptions
класса.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

Выходные файлы будут помещены в текущий рабочий каталог приложения. Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Инициализирует новый экземпляр
HtmlViewOptions
класса.


Для примера кода см. в [документации](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Формат пути к файлу, например, 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | Формат пути к файлу ресурса, например, 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | Формат URL ресурса, например, 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
