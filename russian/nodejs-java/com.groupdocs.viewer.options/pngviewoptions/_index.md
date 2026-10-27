---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга документов в формате PNG."
type: docs
weight: 25
url: /ru/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Предоставляет параметры для рендеринга документов в формате PNG.

Класс PngViewOptions инкапсулирует дополнительные настройки и параметры, которые можно использовать для управления рендерингом документов в формат PNG в компоненте GroupDocs.Viewer.

Пример использования:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Инициализирует новый экземпляр класса  PngViewOptions . |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Инициализирует новый экземпляр класса  PngViewOptions . |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Инициализирует новый экземпляр класса  PngViewOptions . |
| [PngViewOptions()](#PngViewOptions--) | Инициализирует новый экземпляр класса  PngViewOptions . |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Инициализирует новый экземпляр класса  PngViewOptions . |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Инициализирует новый экземпляр класса  PngViewOptions . |
## Методы

| Метод | Описание |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Возвращает максимальную ширину выходного изображения в пикселях. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
| [getMaxHeight()](#getMaxHeight--) | Возвращает максимальную высоту выходного изображения в пикселях. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
| [isExtractText()](#isExtractText--) | Определяет, включено ли извлечение текста. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Включает или отключает извлечение текста. |
| [getWidth()](#getWidth--) | Возвращает ширину выходного изображения в пикселях. |
| [setWidth(int value)](#setWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
| [getHeight()](#getHeight--) | Возвращает высоту выходного изображения в пикселях. |
| [setHeight(int value)](#setHeight-int-) | Устанавливает высоту выходного изображения в пикселях. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов для оценки прогресса сохранения документа. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов для оценки прогресса сохранения документа. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Инициализирует новый экземпляр класса  PngViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходных страниц. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Инициализирует новый экземпляр класса  PngViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Метод, который создает поток, используемый для записи данных выходных страниц. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Метод, который освобождает поток, созданный методом, назначенным параметру createPageStream. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Инициализирует новый экземпляр класса  PngViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Инициализирует новый экземпляр класса  PngViewOptions .

Этот конструктор инициализирует новый экземпляр PngViewOptions с форматом пути файла "p\_\{0\}.png" для выходных файлов. Выходные файлы будут размещены в текущем рабочем каталоге приложения. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Инициализирует новый экземпляр класса  PngViewOptions .

Например, если формат пути файла 'page\_\{0\}.png', выходные файлы будут называться 'page\_1.png', 'page\_2.png' и т.д., в зависимости от номера страницы.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути файла, например, 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Инициализирует новый экземпляр класса  PngViewOptions .

Например, если формат пути файла 'page\_\{0\}.png', выходные файлы будут называться 'page\_1.png', 'page\_2.png' и т.д., в зависимости от номера страницы. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Формат пути файла, например, 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Возвращает максимальную ширину выходного изображения в пикселях.

Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int — максимальная ширина выходного изображения.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях.

Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxWidth | int | Максимальная ширина выходного изображения. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Возвращает максимальную высоту выходного изображения в пикселях.

Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int — максимальная высота выходного изображения.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях.

Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете  свойство, это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxHeight | int | Максимальная высота выходного изображения. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Определяет, включено ли извлечение текста.

Эта опция может быть полезна, когда вы хотите добавить слой выделяемого текста поверх изображения. Используйте это свойство, чтобы получить текст, содержащийся в исходном документе, и его координаты. Затем вы можете использовать эти данные, чтобы добавить выделяемый текст поверх изображения или реализовать поиск текста в рендеринге на основе изображения. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

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
| value | boolean | true  для включения извлечения текста,  false  для его отключения. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Возвращает ширину выходного изображения в пикселях.

Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - ширина выходного изображения.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину выходного изображения в пикселях.

Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Ширина выходного изображения. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Возвращает высоту выходного изображения в пикселях.

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int — высота выходного изображения.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту выходного изображения в пикселях.

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). Для примера кода см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Высота выходного изображения. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов для оценки прогресса сохранения документа.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback — обратный вызов для оценки прогресса сохранения документа.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов для оценки прогресса сохранения документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов для оценки прогресса сохранения документа. |

