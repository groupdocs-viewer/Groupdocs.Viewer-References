---
title: "JpgViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для рендеринга документов в формат JPG."
type: docs
weight: 17
url: /ru/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Предоставляет параметры для рендеринга документов в формат JPG.


Класс JpgViewOptions инкапсулирует дополнительные настройки и параметры, которые могут использоваться для управления рендерингом документов.
в формат JPG в компоненте GroupDocs.Viewer.


Пример использования:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Инициализирует новый экземпляр |
JpgViewOptions
класса.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Инициализирует новый экземпляр |
JpgViewOptions
класса.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Инициализирует новый экземпляр |
JpgViewOptions
класса.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Инициализирует новый экземпляр |
JpgViewOptions
с "p_{0}.jpg" в качестве формата пути к файлам вывода.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Инициализирует новый экземпляр |
JpgViewOptions
класса.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Инициализирует новый экземпляр |
JpgViewOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Получает максимальную ширину выходного изображения в пикселях. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Получает максимальную высоту выходного изображения в пикселях. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
|
|  | [getQuality()](#getQuality--) | Получает качество выходного изображения. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Устанавливает качество выходного изображения. |
|
|  | [isExtractText()](#isExtractText--) | Позволяет извлекать текст. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Включает или отключает извлечение текста. |
|
|  | [getWidth()](#getWidth--) | Получает ширину выходного изображения в пикселях. |
|
|  | [setWidth(int value)](#setWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
|
|  | [getHeight()](#getHeight--) | Получает высоту выходного изображения в пикселях. |
|
|  | [setHeight(int value)](#setHeight-int-) | Устанавливает высоту выходного изображения в пикселях. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Получает фабрику, реализующую методы создания и освобождения потока выходной страницы. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов для оценки прогресса сохранения документа Words или Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов для оценки прогресса сохранения документа Words или Email. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Инициализирует новый экземпляр
JpgViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Инициализирует новый экземпляр
JpgViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходной страницы. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Метод, освобождающий поток, созданный методом, назначенным делегату, переданному параметру  createPageStream . |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Инициализирует новый экземпляр
JpgViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходной страницы. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Инициализирует новый экземпляр
JpgViewOptions
с "p_{0}.jpg" в качестве формата пути к файлам вывода.
Выходные файлы будут размещены в текущем рабочем каталоге приложения.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Инициализирует новый экземпляр
JpgViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Формат пути к файлу, например, 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Инициализирует новый экземпляр
JpgViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Формат пути к файлу, например, 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Получает максимальную ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если установить свойство #setWidth(int).setWidth(int), это свойство игнорируется.


**Returns:**
int - максимальная ширина выходного изображения.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если установить свойство #setWidth(int).setWidth(int), это свойство игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxWidth | int | Максимальная ширина выходного изображения. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Получает максимальную высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если установить свойство #setHeight(int).setHeight(int), это свойство игнорируется.


**Returns:**
int - максимальная высота выходного изображения.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Если установить свойство #setHeight(int).setHeight(int), это свойство игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxHeight | int | Максимальная высота выходного изображения. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Получает качество выходного изображения.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte - качество выходного изображения.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Устанавливает качество выходного изображения.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | byte | Качество выходного изображения. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Позволяет извлекать текст.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean —  true  если извлечение текста включено,  false  в противном случае.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Включает или отключает извлечение текста.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  чтобы включить извлечение текста,  false  чтобы отключить его. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если установить это свойство, свойство #setMaxWidth(int).setMaxWidth(int) игнорируется.


**Returns:**
int - ширина выходного изображения.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину выходного изображения в пикселях.


Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если установить это свойство, свойство #setMaxWidth(int).setMaxWidth(int) игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Ширина выходного изображения. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если установить это свойство, свойство #setMaxHeight(int).setMaxHeight(int) игнорируется.


**Returns:**
int — высота выходного изображения.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту выходного изображения в пикселях.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Если установить это свойство, свойство #setMaxHeight(int).setMaxHeight(int) игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Высота выходного изображения. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Получает фабрику, реализующую методы создания и освобождения потока выходной страницы.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов для оценки прогресса сохранения документа Words или Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - обратный вызов для оценки прогресса сохранения документа.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов для оценки прогресса сохранения документа Words или Email.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов для оценки прогресса сохранения документа. |
|

