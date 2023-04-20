---
title: Viewer
second_title: GroupDocs.Viewer for Java API Reference
description: Represents main class that controls document rendering process.
type: docs
weight: 12
url: /java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Represents main class that controls document rendering process.
## Constructors

| Constructor | Description |
| --- | --- |
| [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream inputStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream inputStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Initializes new instance of  class. |
| [Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(URL url)](#Viewer-java.net.URL-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(String filePath)](#Viewer-java.lang.String-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
| [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class. |
## Fields

| Field | Description |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Methods

| Method | Description |
| --- | --- |
| [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Returns information about view and document specific information. |
| [getAttachments()](#getAttachments--) | Returns attachments contained by the document. |
| [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Saves attachment file to destination stream. |
| [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Creates view of all document pages. |
| [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Creates view of specific document pages. |
| [getFileInfo()](#getFileInfo--) | Returns information about file such as file-type and flag that indicates if file is encrypted. |
| [close()](#close--) | Releases file stream and managed internal resources. |
| [getLoadOptionsInternal()](#getLoadOptionsInternal--) |  |
| [setLoadOptionsInternal(LoadOptions mLoadOptionsInternal)](#setLoadOptionsInternal-com.groupdocs.viewer.options.LoadOptions-) |  |
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.InputStream | The method that returns readable stream. |

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.InputStream | The file stream. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.InputStream | The readable stream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.InputStream | The file stream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |

### Viewer(InputStream inputStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream inputStream, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The file stream |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(InputStream inputStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream inputStream, ViewerSettings settings, boolean leaveOpen)
```


Initializes new instance of  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The file stream. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |

### Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The file stream |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream inputStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The file stream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URL | A url to a file that should be loaded into Viewer. |

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URL | A url to a file that should be loaded into Viewer. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URL | A url to a file that should be loaded into Viewer. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.net.URL | A url to a file that should be loaded into Viewer. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | The file reader |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | The file reader. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to render. |

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The path to the file to render. |

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to render. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The path to the file to render. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to render. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The path to the file to render. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to render. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initializes new instance of [Viewer](../../com.groupdocs.viewer/viewer) class.

**Note:** 
**Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.nio.file.Path | The path to the file to render. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | The document load options. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | The Viewer settings. |

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


Returns information about view and document specific information.

**Learn more**

 *  Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer][]


[How to get file information using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+file+information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | The view info options. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about view and document specific information.
### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Returns attachments contained by the document.

**Learn more**

 *  Learn more about getting document attachments in Java: [How to get list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - Attachments contained by the document.
### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Saves attachment file to destination stream.

**Learn more**

 *  Learn more about getting document attachments in Java: [How to get list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | The attachment. |
| destination | java.io.OutputStream | The writable stream. |

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Creates view of all document pages.

**Learn more**

 *  More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | The view options. |

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Creates view of specific document pages.

**Learn more**

 *  More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | The view options. |
| pageNumbers | int[] | The page numbers to view. |

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Returns information about file such as file-type and flag that indicates if file is encrypted. Learn more about file information: [How to check if file is encrypted][]


[How to check if file is encrypted]: https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - The file information.
### close() {#close--}
```
public final void close()
```


Releases file stream and managed internal resources.

### getLoadOptionsInternal() {#getLoadOptionsInternal--}
```
public LoadOptions getLoadOptionsInternal()
```




**Returns:**
[LoadOptions](../../com.groupdocs.viewer.options/loadoptions)
### setLoadOptionsInternal(LoadOptions mLoadOptionsInternal) {#setLoadOptionsInternal-com.groupdocs.viewer.options.LoadOptions-}
```
public void setLoadOptionsInternal(LoadOptions mLoadOptionsInternal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mLoadOptionsInternal | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) |  |

