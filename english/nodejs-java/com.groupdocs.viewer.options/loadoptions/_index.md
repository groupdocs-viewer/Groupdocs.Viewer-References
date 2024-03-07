---
title: LoadOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options that are used to open a file.
type: docs
weight: 18
url: /nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Provides options that are used to open a file.

The LoadOptions class encapsulates various settings and parameters that can be used to specify how a file should be opened and loaded in the GroupDocs.Viewer component.

Example usage:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes a new instance of the  LoadOptions  class. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initializes a new instance of the  LoadOptions  class. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Gets the type of the file to open. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Sets the type of the file to open. |
| [getPassword()](#getPassword--) | Gets the password for opening an encrypted file. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets the password for opening an encrypted file. |
| [getCharset()](#getCharset--) | The charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | The charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(String charsetName)](#setCharset-java.lang.String-) |  |
| [isDetectCharset()](#isDetectCharset--) | This option enables [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), and [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) files charset detection. |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | This option enables [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), and [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) files charset detection. |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Gets the timeout for loading external resources, such as graphics. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Sets the timeout for loading external resources, such as graphics. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Gets the connection timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Sets the connection timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | Gets the read timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Sets the read timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Gets the security options to control the process of extracting archives. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Sets the security options to control the process of extracting archives. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of the  LoadOptions  class.

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initializes a new instance of the  LoadOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The type of the file to open. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Gets the type of the file to open.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Sets the type of the file to open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets the password for opening an encrypted file.

**Returns:**
java.lang.String - the password for opening the file.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets the password for opening an encrypted file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The password for opening the file. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


The charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Default value is java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8.

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


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


The charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Default value is java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8.

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


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setCharset(String charsetName) {#setCharset-java.lang.String-}
```
public final void setCharset(String charsetName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| charsetName | java.lang.String |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


This option enables [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), and [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) files charset detection. In case the charset can't be detected the default [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) is used.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

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

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


This option enables [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), and [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) files charset detection. In case the charset can't be detected the default [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) is used.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Gets the timeout for loading external resources, such as graphics.

***Note:** The default value is 30 seconds.*

This option is supported for Word Processing documents that contain external resources.

**Returns:**
int - the loading timeout, milliseconds.
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Sets the timeout for loading external resources, such as graphics.

***Note:** The default value is 30 seconds.*

This option is supported for Word Processing documents that contain external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceLoadingTimeout | int | The loading timeout, milliseconds. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Gets the connection timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document.

***Note:** The default value is 5 seconds.*

**Returns:**
int - the connection timeout.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Sets the connection timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document.

***Note:** The default value is 5 seconds.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| urlConnectTimeout | int | The connection timeout. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Gets the read timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document.

***Note:** The default value is 30 seconds.*

**Returns:**
int - the read timeout.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Sets the read timeout for creating a [Viewer](../../com.groupdocs.viewer/viewer) using java.net.URL to load a document.

***Note:** The default value is 30 seconds.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| urlReadTimeout | int | The read timeout. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Gets the security options to control the process of extracting archives.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - the options object to configure the process of extracting archives.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Sets the security options to control the process of extracting archives.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | The options object to configure the process of extracting archives. |

