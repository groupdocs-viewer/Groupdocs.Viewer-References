---
title: "PngViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации документов в формате PNG."
type: docs
weight: 25
url: /ru/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Предоставляет параметры для визуализации документов в формате PNG.


Класс PngViewOptions инкапсулирует дополнительные параметры и настройки, которые могут быть использованы
для управления рендерингом документов в формате PNG в компоненте GroupDocs.Viewer.


Пример использования:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Для получения подробностей см. эту [страницу](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) и её дочерние элементы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
|  | [PngViewOptions()](#PngViewOptions--) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Инициализирует новый экземпляр |
PngViewOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Возвращает максимальную ширину выходного изображения в пикселях. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Возвращает максимальную высоту выходного изображения в пикселях. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
|
|  | [isExtractText()](#isExtractText--) | Определяет, включено ли извлечение текста. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Включает или отключает извлечение текста. |
|
|  | [getWidth()](#getWidth--) | Возвращает ширину выходного изображения в пикселях. |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
|
|  | [getHeight()](#getHeight--) | Возвращает высоту выходного изображения в пикселях. |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту выходного изображения в пикселях. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов для оценки прогресса сохранения документа. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов для оценки прогресса сохранения документа. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Метод, который освобождает поток, созданный методом, назначенным параметру createPageStream. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходной страницы. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Этот конструктор инициализирует новый экземпляр
PngViewOptions

с "p_{0}.png" в качестве формата пути к файлам вывода.
Файлы вывода будут помещены в текущий рабочий каталог приложения.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Например, если формат пути к файлам — 'page_{0}.png', файлы вывода будут
именоваться 'page_1.png', 'page_2.png' и так далее, в зависимости от номера страницы.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Формат пути к файлам, например, 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Инициализирует новый экземпляр
PngViewOptions
класса.


Например, если формат пути к файлам — 'page_{0}.png', файлы вывода будут
именоваться 'page_1.png', 'page_2.png' и так далее, в зависимости от номера страницы.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Формат пути к файлам, например, 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Возвращает максимальную ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если вы задаёте это свойство, оно игнорируется.


**Returns:**
int — максимальная ширина выходного изображения.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если вы задаёте это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxWidth | int | Максимальная ширина выходного изображения. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Возвращает максимальную высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если вы задаёте это свойство, оно игнорируется.


**Returns:**
int — максимальная высота выходного изображения.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если вы задаёте это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxHeight | int | Максимальная высота выходного изображения. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Определяет, включено ли извлечение текста.


Эта опция может быть полезна, когда вы хотите добавить слой выделяемого текста поверх изображения.
Используйте это свойство, чтобы получить текст, содержащийся в исходном документе, и его координаты. Затем вы можете использовать эти данные для добавления выделяемого текста поверх изображения или для реализации поиска текста в рендеринге на основе изображений.
Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean —  true  если извлечение текста включено,  false  в противном случае.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Включает или отключает извлечение текста.


Эта опция может быть полезна, когда вы хотите добавить слой выделяемого текста поверх изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  чтобы включить извлечение текста,  false  чтобы отключить его. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Возвращает ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если вы задаете это свойство, оно игнорируется.


**Returns:**
int - ширина выходного изображения.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если вы задаете это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Ширина выходного изображения. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Возвращает высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если вы задаете это свойство, оно игнорируется.


**Returns:**
int — высота выходного изображения.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если вы задаете это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Высота выходного изображения. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов для оценки прогресса сохранения документа.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - обратный вызов для оценки прогресса сохранения документа.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов для оценки прогресса сохранения документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов для оценки прогресса сохранения документа. |
|

