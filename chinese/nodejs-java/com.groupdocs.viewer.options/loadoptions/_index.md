---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于打开文件的选项。"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

提供用于打开文件的选项。

LoadOptions 类封装了各种设置和参数，可用于指定如何在 GroupDocs.Viewer 组件中打开和加载文件。详情请参见此 [page][] 及其子项。

示例用法：

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 初始化 LoadOptions 类的新实例。 |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | 初始化 LoadOptions 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | 启用后，GroupDocs.Viewer 将尝试修复 PDF 文档中的结构损坏。 |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | 启用后，GroupDocs.Viewer 将尝试修复 PDF 文档中的结构损坏。 |
| [getFileType()](#getFileType--) | 获取要打开的文件类型。 |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | 设置要打开的文件类型。 |
| [getPassword()](#getPassword--) | 获取打开加密文件的密码。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置打开加密文件的密码。 |
| [getCharset()](#getCharset--) | 打开基于文本的文件或电子邮件（如 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) 和 [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)）时使用的字符集。 |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | 打开基于文本的文件或电子邮件（如 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) 和 [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)）时使用的字符集。 |
| [isDetectCharset()](#isDetectCharset--) | 此选项启用对 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) 和 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 文件的字符集检测。 |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | 此选项启用对 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) 和 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 文件的字符集检测。 |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 获取加载外部资源的超时时间。 |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | 设置加载外部资源（如图形）的超时时间。 |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | 获取使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的连接超时时间。 |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | 设置使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的连接超时时间。 |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | 获取使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的读取超时时间。 |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | 设置使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的读取超时时间。 |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | 获取用于控制解压存档过程的安全选项。 |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | 设置安全选项以控制解压归档的过程。 |
| [isSkipExternalResources()](#isSkipExternalResources--) | 当设置为 true 时，所有外部资源（如图像）将不会被加载，除非 \#getWhitelistedResources().getWhitelistedResources()。 |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | 当设置为 true 时，所有外部资源（如图像）将不会被加载，除非 \#getWhitelistedResources().getWhitelistedResources()。 |
| [getWhitelistedResources()](#getWhitelistedResources--) | 当 \#isSkipExternalResources().isSkipExternalResources() 设置为 `true` 时，应加载的外部资源对应的 URL 片段列表。 |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | 设置当 \#isSkipExternalResources().isSkipExternalResources() 被设为 `true` 时，应加载的外部资源对应的 URL 片段列表。 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


初始化 LoadOptions 类的新实例。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


初始化 LoadOptions 类的新实例。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 要打开的文件类型。 |

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


启用后，GroupDocs.Viewer 将尝试修复 PDF 文档中的结构损坏。默认值为 false。

此功能解决 PDF 文档中的以下问题：

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


启用后，GroupDocs.Viewer 将尝试修复 PDF 文档中的结构损坏。默认值为 false。

此功能解决 PDF 文档中的以下问题：

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


获取要打开的文件类型。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


设置要打开的文件类型。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取打开加密文件的密码。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - 打开文件的密码。
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置打开加密文件的密码。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 打开文件的密码。 |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


打开基于文本的文件或电子邮件（如 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) 和 [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)）时使用的字符集。

默认值为 java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8。代码示例请参见 [documentation][].

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


打开基于文本的文件或电子邮件（如 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) 和 [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)）时使用的字符集。

默认值为 java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8。代码示例请参见 [documentation][].

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


此选项启用对 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) 和 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 文件的字符集检测。如果无法检测字符集，则使用默认的 [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--)。

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

如果无法检测到编码，则使用默认值。代码示例请参见 [documentation][].

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


此选项启用对 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) 和 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 文件的字符集检测。如果无法检测字符集，则使用默认的 [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--)。

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

如果无法检测到编码，则使用默认值。代码示例请参见 [documentation][].

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


获取加载外部资源的超时时间。

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

默认值为 30 秒。代码示例请参见 [documentation][].

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


设置加载外部资源（如图形）的超时时间。

***Note:** The default value is 30 seconds.*

此选项支持包含外部资源的文字处理文档。默认值为 30 秒。代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceLoadingTimeout | int | 加载超时时间（毫秒）。 |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


获取使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的连接超时时间。

***Note:** The default value is 5 seconds.*

**Returns:**
int - 连接超时时间。
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


设置使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的连接超时时间。

***Note:** The default value is 5 seconds.*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| urlConnectTimeout | int | 连接超时时间。 |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


获取使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的读取超时时间。

***Note:** The default value is 30 seconds.*

**Returns:**
int - 读取超时时间。
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


设置使用 java.net.URL 加载文档时创建 [Viewer](../../com.groupdocs.viewer/viewer) 的读取超时时间。

***Note:** The default value is 30 seconds.*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| urlReadTimeout | int | 读取超时。 |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


获取用于控制解压存档过程的安全选项。

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - 用于配置解压归档过程的选项对象。
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


设置安全选项以控制解压归档的过程。

***Note:** Not each archive type supports all options.*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | 用于配置解压归档过程的选项对象。 |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


当设置为 true 时，所有外部资源（如图像）将不会被加载，除非 \#getWhitelistedResources().getWhitelistedResources()。

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


当设置为 true 时，所有外部资源（如图像）将不会被加载，除非 \#getWhitelistedResources().getWhitelistedResources()。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| skipExternalResources | boolean | 用于启用或禁用加载外部资源的标志。 |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


当 \#isSkipExternalResources().isSkipExternalResources() 设置为 `true` 时，应加载的外部资源对应的 URL 片段列表。

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


设置当 \#isSkipExternalResources().isSkipExternalResources() 被设为 `true` 时，应加载的外部资源对应的 URL 片段列表。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | 应加载的外部资源对应的 URL 片段列表。 |

