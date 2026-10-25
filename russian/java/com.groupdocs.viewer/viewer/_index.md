---
title: "Viewer"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет основной класс, который управляет процессом рендеринга документа."
type: docs
weight: 12
url: /ru/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Представляет основной класс, который управляет процессом рендеринга документа.


Класс Viewer является точкой входа для рендеринга документов с использованием компонента GroupDocs.Viewer.
Он предоставляет методы и параметры для загрузки документов из различных источников, настройки процесса рендеринга и получения отрендеренного вывода в разных форматах.


Пример использования:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Инициализирует новый экземпляр класса Viewer. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Возвращает информацию о представлении и о специфической информации документа. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | Возвращает информацию о представлении и о специфической информации документа. |
|
|  | [getAttachments()](#getAttachments--) | Возвращает вложения, содержащиеся в документе. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | Возвращает вложения, содержащиеся в документе. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Сохраняет файл вложения в целевой поток. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | Сохраняет файл вложения в целевой поток. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Создаёт представление всех страниц документа. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | Создаёт представление всех страниц документа. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | Создаёт представление конкретной страницы документа. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Создаёт представление конкретных страниц документа. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | Создаёт представление конкретных страниц документа. |
|
|  | [getAllFonts()](#getAllFonts--) | Возвращает все шрифты, используемые в загруженных документах, включая встроенные в сам документ и системные шрифты, установленные в ОС и использованные в документе. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Выполняет поиск текста и выделяет совпадения (если найдены) в загруженном документе в соответствии с предоставленными параметрами. |
|
|  | [getFileInfo()](#getFileInfo--) | Возвращает информацию о файле, такую как тип файла и флаг, указывающий, зашифрован ли файл. |
|
|  | [close()](#close--) | Освобождает поток файла и управляемые внутренние ресурсы. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Инициализирует новый экземпляр класса Viewer.


Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Метод, который возвращает читаемый поток. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | leaveOpen | boolean | true, чтобы оставить поток открытым после освобождения объекта Viewer; иначе false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Читаемый поток. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | leaveOpen | boolean | true, чтобы оставить поток открытым после освобождения объекта Viewer; иначе false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|
|  | leaveOpen | boolean | true, чтобы оставить поток открытым после освобождения объекта Viewer; иначе false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Поток файла. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|
|  | leaveOpen | boolean | true, чтобы оставить поток открытым после освобождения объекта Viewer; иначе false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Инициализирует новый экземпляр класса Viewer.


Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | url | java.net.URL | URL-адрес файла, который должен быть загружен в Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | url | java.net.URL | URL-адрес файла, который должен быть загружен в Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | url | java.net.URL | URL-адрес файла, который должен быть загружен в Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | url | java.net.URL | URL-адрес файла, который должен быть загружен в Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.


Этот конструктор позволяет создать объект Viewer для просмотра документа из [FileReader](../../com.groupdocs.viewer.interfaces/filereader) с указанными [ViewerSettings](../../com.groupdocs.viewer/viewersettings).
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Объект [FileReader](../../com.groupdocs.viewer.interfaces/filereader), содержащий документ, который будет загружен в Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Объект [ViewerSettings](../../com.groupdocs.viewer/viewersettings), который будет применён к Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.


Предоставляет возможность загружать и просматривать документы с помощью GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Читатель файла. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу для отображения. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу для отображения. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу для отображения. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу для отображения. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу для отображения. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу для отображения. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу для отображения. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Инициализирует новый экземпляр класса Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу для отображения. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Параметры загрузки документа. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Настройки Viewer. |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


Возвращает информацию о представлении и о специфической информации документа.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Параметры информации представления. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


Возвращает информацию о представлении и о специфической информации документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Параметры информации представления. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Токен отмены для прерывания операции. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Возвращает вложения, содержащиеся в документе.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - вложения, содержащиеся в документе.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


Возвращает вложения, содержащиеся в документе.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Токен отмены для прерывания операции. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - вложения, содержащиеся в документе.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Сохраняет файл вложения в целевой поток.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Вложение. |
|
|  | назначение | java.io.OutputStream | Записываемый поток. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


Сохраняет файл вложения в целевой поток.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Вложение. |
|
|  | назначение | java.io.OutputStream | Записываемый поток. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Токен отмены для прерывания операции. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Создаёт представление всех страниц документа.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Параметры представления. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


Создаёт представление всех страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Параметры представления. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Токен отмены для прерывания процесса рендеринга. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


Создаёт представление конкретной страницы документа.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Параметры представления. |
|
|  | pageNumber | int | Номер страницы для просмотра. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Создаёт представление конкретных страниц документа.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Параметры представления. |
|
|  | pageNumbers | int[] | Номера страниц для просмотра. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


Создаёт представление конкретных страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Параметры представления. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Токен отмены для прерывания процесса рендеринга. |
|
|  | pageNumbers | int[] | Номера страниц для просмотра. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Возвращает все шрифты, используемые в загруженных документах, включая встроенные в сам документ и системные шрифты, установленные в ОС и использованные в документе.

Для получения подробностей см.
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - непустой список всех шрифтов, используемых в документе, загруженном в этот экземпляр [Viewer](../../com.groupdocs.viewer/viewer).

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Выполняет поиск текста и выделяет совпадения (если найдены) в загруженном документе в соответствии с предоставленными параметрами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | опции | com.groupdocs.viewer.options.SearchHighlightOptions | Параметры поиска и выделения, включая текстовую фразу для поиска. Не может быть null. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Возвращает информацию о файле, такую как тип файла и флаг, указывающий, зашифрован ли файл.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


Освобождает поток файла и управляемые внутренние ресурсы.


