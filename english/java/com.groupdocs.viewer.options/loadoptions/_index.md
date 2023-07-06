---
title: LoadOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options that are used to open a file.
type: docs
weight: 18
url: /java/com.groupdocs.viewer.options/loadoptions/
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
| [getCharset()](#getCharset--) | Gets the charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Sets the charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
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


Gets the charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

***Note:** The default value is Charset\#defaultCharset().defaultCharset().*

**Returns:**
java.nio.charset.Charset - the charset used for opening text-based files or email messages.
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Sets the charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

***Note:** The default value is Charset\#defaultCharset().defaultCharset().*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset | The charset used for opening text-based files or email messages. |

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

