---
title: "PdfViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации документов в формате PDF."
type: docs
weight: 23
url: /ru/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Предоставляет параметры для визуализации документов в формате PDF.


Класс PdfViewOptions инкапсулирует дополнительные настройки и параметры.
которые могут использоваться для управления рендерингом документов в формат PDF в компоненте GroupDocs.Viewer.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


Пример использования:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Инициализирует новый экземпляр |
PdfViewOptions
класса.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Инициализирует новый экземпляр |
PdfViewOptions
класса.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Инициализирует новый экземпляр класса PdfViewOptions. |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | Инициализирует новый экземпляр класса PdfViewOptions с настройками по умолчанию. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Инициализирует новый экземпляр |
PdfViewOptions
класса.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Инициализирует новый экземпляр |
PdfViewOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Уменьшает размер выходного PDF‑файла, применяя техники оптимизации с различными параметрами. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Уменьшает размер выходного PDF‑файла, применяя техники оптимизации с различными параметрами. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Возвращает максимальную ширину выходного изображения в пикселях. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Устанавливает максимальную ширину выходного изображения в пикселях. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Возвращает максимальную высоту выходного изображения в пикселях. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Устанавливает максимальную высоту выходного изображения в пикселях. |
|
|  | [getImageWidth()](#getImageWidth--) | Возвращает ширину выходного изображения в пикселях. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Устанавливает ширину выходного изображения в пикселях. |
|
|  | [getImageHeight()](#getImageHeight--) | Получает высоту выходного изображения в пикселях. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Устанавливает высоту выходного изображения в пикселях. |
|
|  | [getSecurity()](#getSecurity--) | Получает параметры безопасности для выходного PDF‑документа. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Устанавливает параметры безопасности для выходного PDF‑документа. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Получает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Инициализирует новый экземпляр
PdfViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Инициализирует новый экземпляр
PdfViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Метод, используемый для создания потока записи данных выходного файла. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Метод, используемый для освобождения потока, созданного методом  createFileStream . |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Инициализирует новый экземпляр класса PdfViewOptions.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Фабрика, реализующая методы создания и освобождения потока выходного файла. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Инициализирует новый экземпляр класса PdfViewOptions с настройками по умолчанию.


Этот конструктор создает новый
PdfViewOptions
объект с "output.pdf" в качестве формата пути к файлу для выходного файла.
Выходной файл будет помещён в текущий рабочий каталог приложения.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Инициализирует новый экземпляр
PdfViewOptions
класса.


Этот конструктор создает новый
PdfViewOptions
объект с указанным
outputFilePath
параметр
представляющий путь к выходному PDF‑файлу.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | Путь к выходному PDF‑файлу. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Инициализирует новый экземпляр
PdfViewOptions
класса.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | Путь к выходному PDF‑файлу. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Уменьшает размер выходного PDF‑файла, применяя техники оптимизации с различными параметрами.


Эта опция поддерживается для любых входных форматов файлов, поддерживаемых для конвертации в PDF: [Поддерживаемые форматы документов](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Для получения деталей и примеров кода см. эту [страницу](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) и её дочерние элементы.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Уменьшает размер выходного PDF‑файла, применяя техники оптимизации с различными параметрами.


Эта опция поддерживается для любых входных форматов файлов, поддерживаемых для конвертации в PDF: [Поддерживаемые форматы документов](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Для получения деталей и примеров кода см. эту [страницу](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) и её дочерние элементы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Объект PdfOptimizationOptions или null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Получает максимальную ширину выходного изображения в пикселях. Этот параметр применяется только при конвертации одного изображения в HTML.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для получения деталей см. [документацию](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаёте это свойство, оно игнорируется.


**Returns:**
int - максимальная ширина выходного изображения в пикселях.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Устанавливает максимальную ширину выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать максимальную ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Для получения деталей см. [документацию](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаёте это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageMaxWidth | int | Максимальная ширина выходного изображения в пикселях. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Получает максимальную высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаёте это свойство, оно игнорируется.


**Returns:**
int - максимальная высота выходного изображения в пикселях.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Устанавливает максимальную высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать максимальную высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаёте это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageMaxHeight | int | Максимальная высота выходного изображения в пикселях. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Получает ширину выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать ширину выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство при рендеринге одного изображения в PDF. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаете это свойство, оно игнорируется.


**Returns:**
int - ширина выходного изображения в пикселях.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Устанавливает ширину выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в PDF.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageWidth | int | Ширина выходного изображения в пикселях. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Получает высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаете это свойство, оно игнорируется.


**Returns:**
int - высота выходного изображения в пикселях.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Устанавливает высоту выходного изображения в пикселях. Этот параметр применяется только при преобразовании одного изображения в HTML.


Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге одного изображения в HTML. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Если вы задаете это свойство, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageHeight | int | Высота выходного изображения в пикселях. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Получает параметры безопасности для выходного PDF‑документа.


Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Устанавливает параметры безопасности для выходного PDF‑документа.


Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | Параметры безопасности для выходного PDF‑документа. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Получает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - обратный вызов для оценки прогресса сохранения документа.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Устанавливает обратный вызов, используемый для оценки прогресса сохранения документа Words или Email.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Обратный вызов для оценки прогресса сохранения документа. |
|

