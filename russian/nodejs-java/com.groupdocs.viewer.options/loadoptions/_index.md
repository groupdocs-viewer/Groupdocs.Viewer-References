---
title: "LoadOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры, используемые для открытия файла."
type: docs
weight: 18
url: /ru/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Предоставляет параметры, используемые для открытия файла.

Класс LoadOptions инкапсулирует различные настройки и параметры, которые можно использовать для указания того, как файл должен быть открыт и загружен в компоненте GroupDocs.Viewer. Для подробностей см. эту [page][] и её дочерние элементы.

Пример использования:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Инициализирует новый экземпляр класса LoadOptions. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Инициализирует новый экземпляр класса LoadOptions. |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | Когда включено, GroupDocs.Viewer пытается исправить структурные повреждения в PDF‑документах. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Когда включено, GroupDocs.Viewer пытается исправить структурные повреждения в PDF‑документах. |
| [getFileType()](#getFileType--) | Получает тип файла для открытия. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Устанавливает тип файла для открытия. |
| [getPassword()](#getPassword--) | Получает пароль для открытия зашифрованного файла. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает пароль для открытия зашифрованного файла. |
| [getCharset()](#getCharset--) | Кодировка, используемая при открытии текстовых файлов или электронных сообщений, таких как [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) и [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Кодировка, используемая при открытии текстовых файлов или электронных сообщений, таких как [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) и [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [isDetectCharset()](#isDetectCharset--) | Эта опция включает определение кодировки файлов [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) и [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Эта опция включает определение кодировки файлов [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) и [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Получает тайм‑аут загрузки внешних ресурсов. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Устанавливает тайм‑аут загрузки внешних ресурсов, например графики. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Получает тайм‑аут соединения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Устанавливает тайм‑аут соединения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | Получает тайм‑аут чтения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Устанавливает тайм‑аут чтения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Получает параметры безопасности для контроля процесса извлечения архивов. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Устанавливает параметры безопасности для контроля процесса извлечения архивов. |
| [isSkipExternalResources()](#isSkipExternalResources--) | Когда установлено в true, все внешние ресурсы, такие как изображения, не будут загружаться, за исключением \#getWhitelistedResources().getWhitelistedResources(). |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Когда установлено в true, все внешние ресурсы, такие как изображения, не будут загружаться, за исключением \#getWhitelistedResources().getWhitelistedResources(). |
| [getWhitelistedResources()](#getWhitelistedResources--) | Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда \#isSkipExternalResources().isSkipExternalResources() установлен в `true`. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Устанавливает список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда \#isSkipExternalResources().isSkipExternalResources() установлен в `true`. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Инициализирует новый экземпляр класса LoadOptions.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Инициализирует новый экземпляр класса LoadOptions.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла для открытия. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


При включении GroupDocs.Viewer пытается исправить структурные повреждения в PDF‑документах. Значение по умолчанию — false.

Эта функция решает следующие проблемы в PDF‑документе:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


При включении GroupDocs.Viewer пытается исправить структурные повреждения в PDF‑документах. Значение по умолчанию — false.

Эта функция решает следующие проблемы в PDF‑документе:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Получает тип файла для открытия.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Устанавливает тип файла для открытия.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает пароль для открытия зашифрованного файла.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String — пароль для открытия файла.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Устанавливает пароль для открытия зашифрованного файла.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Пароль для открытия файла. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Кодировка, используемая при открытии текстовых файлов или электронных сообщений, таких как [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) и [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Значение по умолчанию — java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Пример кода см. в [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Кодировка, используемая при открытии текстовых файлов или электронных сообщений, таких как [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) и [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Значение по умолчанию — java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Пример кода см. в [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Эта опция включает определение кодировки файлов [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) и [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Если кодировка не может быть определена, используется значение по умолчанию из [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Если кодировка не может быть определена, используется значение по умолчанию. Пример кода см. в [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Эта опция включает определение кодировки файлов [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) и [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Если кодировка не может быть определена, используется значение по умолчанию из [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Если кодировка не может быть определена, используется значение по умолчанию. Пример кода см. в [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Получает тайм‑аут загрузки внешних ресурсов.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

Значение по умолчанию — 30 секунд. Пример кода см. в [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Устанавливает тайм‑аут загрузки внешних ресурсов, например графики.

***Note:** The default value is 30 seconds.*

Эта опция поддерживается для документов обработки текста, содержащих внешние ресурсы. Значение по умолчанию — 30 секунд. Пример кода см. в [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceLoadingTimeout | int | Таймаут загрузки, миллисекунды. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Получает тайм‑аут соединения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа.

***Note:** The default value is 5 seconds.*

**Returns:**
int — таймаут соединения.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Устанавливает тайм‑аут соединения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа.

***Note:** The default value is 5 seconds.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| urlConnectTimeout | int | Таймаут соединения. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Получает тайм‑аут чтения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа.

***Note:** The default value is 30 seconds.*

**Returns:**
int — таймаут чтения.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Устанавливает тайм‑аут чтения для создания [Viewer](../../com.groupdocs.viewer/viewer) с использованием java.net.URL для загрузки документа.

***Note:** The default value is 30 seconds.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| urlReadTimeout | int | Тайм-аут чтения. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Получает параметры безопасности для контроля процесса извлечения архивов.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - объект параметров для настройки процесса извлечения архивов.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Устанавливает параметры безопасности для контроля процесса извлечения архивов.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Объект параметров для настройки процесса извлечения архивов. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Когда установлено в true, все внешние ресурсы, такие как изображения, не будут загружаться, за исключением \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Когда установлено в true, все внешние ресурсы, такие как изображения, не будут загружаться, за исключением \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| skipExternalResources | boolean | Флаг для включения или отключения загрузки внешних ресурсов. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда \#isSkipExternalResources().isSkipExternalResources() установлен в `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Устанавливает список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда \#isSkipExternalResources().isSkipExternalResources() установлен в `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены. |

