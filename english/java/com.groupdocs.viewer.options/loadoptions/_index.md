---
title: LoadOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options that used to open the file.
type: docs
weight: 17
url: /java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Provides options that used to open the file.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes new instance of [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) class. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initializes new instance of [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | The type of the file to open. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | The type of the file to open. |
| [getPassword()](#getPassword--) | The password for opening encrypted file. |
| [setPassword(String value)](#setPassword-java.lang.String-) | The password for opening encrypted file. |
| [getCharset()](#getCharset--) | The Charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | The Charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | The external resources e.g. graphics loading timeout. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | The external resources e.g. graphics loading timeout. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes new instance of [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) class.

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The type of the file to open. |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


The type of the file to open.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


The type of the file to open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


The password for opening encrypted file.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


The password for opening encrypted file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


The Charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). Default value is (Charset\#defaultCharset().defaultCharset()\}).

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


The Charset used when opening text-based files or email messages such as [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), and [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). Default value is (Charset\#defaultCharset().defaultCharset()).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


The external resources e.g. graphics loading timeout. The default value is 30 seconds. This option is supported for Word Processing documents that contain external resources.

**Returns:**
int - loading timeout
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


The external resources e.g. graphics loading timeout. The default value is 30 seconds. This option is supported for Word Processing documents that contain external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceLoadingTimeout | int | loading timeout |

