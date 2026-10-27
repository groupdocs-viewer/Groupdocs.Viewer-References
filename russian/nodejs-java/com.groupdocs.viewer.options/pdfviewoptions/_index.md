---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга документов в формате PDF."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Предоставляет параметры для рендеринга документов в формате PDF.

Класс PdfViewOptions инкапсулирует дополнительные настройки и параметры, которые можно использовать для управления рендерингом документов в формат PDF в компоненте GroupDocs.Viewer. Для подробностей см. [documentation][].

Пример использования:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Инициализирует новый экземпляр класса  PdfViewOptions . |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Инициализирует новый экземпляр класса  PdfViewOptions . |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Инициализирует новый экземпляр класса  PdfViewOptions . |
| [PdfViewOptions()](#PdfViewOptions--) | Инициализирует новый экземпляр класса  PdfViewOptions  с настройками по умолчанию. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Инициализирует новый экземпляр класса  PdfViewOptions . |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Инициализирует новый экземпляр класса  PdfViewOptions . |
## Методы

| Метод | Описание |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Уменьшить размер выходного PDF-файла, применяя методы оптимизации с различными параметрами. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Уменьшить размер выходного PDF-файла, применяя методы оптимизации с различными параметрами. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Получает максимальную ширину выходного изображения в пикселях. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Получает максимальную высоту выходного изображения в пикселях. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
| [getImageWidth()](#getImageWidth--) | Получает ширину выходного изображения в пикселях. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
| [getImageHeight()](#getImageHeight--) | Получает высоту выходного изображения в пикселях. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Устанавливает высоту выходного изображения в пикселях. |
| [getSecurity()](#getSecurity--) | Получает параметры безопасности для выходного PDF‑документа. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Устанавливает параметры безопасности для выходного PDF‑документа. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Инициализирует новый экземпляр класса  PdfViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Инициализирует новый экземпляр класса  PdfViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Метод, используемый для создания потока записи данных выходного файла. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Метод, используемый для освобождения потока, созданного методом  createFileStream . |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Инициализирует новый экземпляр класса  PdfViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходного файла. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Инициализирует новый экземпляр класса  PdfViewOptions  с настройками по умолчанию.

Этот конструктор создает новый объект  PdfViewOptions  с "output.pdf" в качестве формата пути к файлу выходного документа. Выходной файл будет помещён в текущий рабочий каталог приложения. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Инициализирует новый экземпляр класса  PdfViewOptions .

Этот конструктор создает новый объект  PdfViewOptions  с указанным параметром  outputFilePath , представляющим путь к выходному PDF‑файлу. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFilePath | java.lang.String | Путь к выходному PDF‑файлу. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Инициализирует новый экземпляр класса  PdfViewOptions .

Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Путь к выходному PDF‑файлу. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Уменьшить размер выходного PDF-файла, применяя методы оптимизации с различными параметрами.

Эта опция поддерживается для всех форматов входных файлов, которые поддерживаются для конвертации в PDF: [Поддерживаемые форматы документов][] Подробности и примеры кода см. на этой [странице][] и её дочерних страницах.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Уменьшить размер выходного PDF-файла, применяя методы оптимизации с различными параметрами.

Эта опция поддерживается для всех форматов входных файлов, которые поддерживаются для конвертации в PDF: [Поддерживаемые форматы документов][] Подробности и примеры кода см. на этой [странице][] и её дочерних страницах.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Объект PdfOptimizationOptions или null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Получает максимальную ширину выходного изображения в пикселях. Этот параметр применяется только при конвертации одного изображения в HTML.

Используйте это свойство, чтобы установить максимальную ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для подробностей см. [документацию][]. Если вы задаёте свойство  property , это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int — максимальная ширина выходного изображения в пикселях.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях. Этот параметр применяется только при конвертации одного изображения в HTML.

Используйте это свойство, чтобы установить максимальную ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для подробностей см. [документацию][]. Если вы задаёте свойство  property , это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageMaxWidth | int | Максимальная ширина выходного изображения в пикселях. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Получает максимальную высоту выходного изображения в пикселях. Этот параметр применяется только при конвертации одного изображения в HTML.

Используйте это свойство, чтобы установить максимальную высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для подробностей см. [документацию][]. Если вы задаёте свойство  property , это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int — максимальная высота выходного изображения в пикселях.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.

Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Для получения подробностей см. [documentation][]. Если вы задаете свойство  , это свойство игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageMaxHeight | int | Максимальная высота выходного изображения в пикселях. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Получает ширину выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.

Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для получения подробностей см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int — ширина выходного изображения в пикселях.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Устанавливает ширину выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения PDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageWidth | int | Ширина выходного изображения в пикселях. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Получает высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Для получения подробностей см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int — высота выходного изображения в пикселях.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Устанавливает высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Для получения подробностей см. [documentation][]. Если вы задаете это свойство, свойство  игнорируется.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageHeight | int | Высота выходного изображения в пикселях. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Получает параметры безопасности для выходного PDF‑документа.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Устанавливает параметры безопасности для выходного PDF‑документа.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Параметры безопасности выходного PDF‑документа. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback — обратный вызов для оценки прогресса сохранения документа.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов для оценки прогресса сохранения документа. |

