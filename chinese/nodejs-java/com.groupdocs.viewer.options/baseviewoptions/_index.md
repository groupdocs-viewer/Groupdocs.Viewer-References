---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "包含基础渲染选项。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

包含基础渲染选项。

BaseViewOptions 类作为 GroupDocs.Viewer 中渲染选项的基础。它允许您在渲染特定文档格式时自定义输出 HTML、PDF、PNG 和 JPEG 文件的渲染行为。

***Note:** For internal usage.*
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | 检索将文本文件拆分为页面的选项。 |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | 设置将文本文件拆分为页面的选项。 |
| [isRenderComments()](#isRenderComments--) | 启用渲染注释。 |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | 启用渲染注释。 |
| [isRemoveComments()](#isRemoveComments--) | 当设置为 true 时禁用渲染注释。 |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | 当设置为 true 时禁用渲染注释。 |
| [isRenderNotes()](#isRenderNotes--) | 启用渲染备注。 |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | 启用渲染备注。 |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | 启用渲染隐藏页面。 |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | 启用渲染隐藏页面。 |
| [getDefaultFontName()](#getDefaultFontName--) | 当文档中使用的特定字体未找到时使用的默认字体。 |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | 当文档中使用的特定字体未找到时使用的默认字体。 |
| [getArchiveOptions()](#getArchiveOptions--) | 检索存档文件视图选项。 |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | 设置存档文件视图选项。 |
| [getCadOptions()](#getCadOptions--) | 检索 CAD 绘图视图选项。 |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | 设置 CAD 绘图视图选项。 |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | 检索电子邮件消息视图选项。 |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | 设置电子邮件消息视图选项。 |
| [getOutlookOptions()](#getOutlookOptions--) | 检索 MS Outlook 数据文件视图选项。 |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | 设置 MS Outlook 数据文件视图选项。 |
| [getPdfOptions()](#getPdfOptions--) | 检索 PDF 文档的视图选项。 |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | 检索 PDF 文档的视图选项。 |
| [getMailStorageOptions()](#getMailStorageOptions--) | 检索 Lotus Notes 存储数据文件的视图选项。 |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | 设置 Lotus Notes 存储数据文件的视图选项。 |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | 检索项目管理文件的视图选项。 |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | 设置项目管理文件的视图选项。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 检索电子表格文件的视图选项。 |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | 设置电子表格文件的视图选项。 |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | Word 处理文件的视图选项。 |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Word 处理文件的视图选项。 |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | 检索在查看文档时处理 Visio 文件的渲染选项。 |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | 设置在查看文档时处理 Visio 文件的渲染选项。 |
| [getPresentationOptions()](#getPresentationOptions--) | 检索处理演示文稿文件的视图选项。 |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | 设置处理演示文稿文件的视图选项。 |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | 获取在渲染 Web 文档时允许自定义输出 HTML/PDF/PNG/JPEG 外观的渲染选项。 |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | 设置在渲染 Web 文档时允许自定义输出 HTML/PDF/PNG/JPEG 外观的渲染选项。 |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


检索将文本文件拆分为页面的选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


设置将文本文件拆分为页面的选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | 文本文件拆分选项。 |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


启用渲染注释。

默认情况下，GroupDocs.Viewer 不渲染注释。要实现此功能，请将此属性设为 true。代码示例请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
布尔 -  true  如果应渲染注释，  false  否则。
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


启用渲染注释。

默认情况下，GroupDocs.Viewer 不渲染注释。要实现此功能，请将此属性设为 true。代码示例请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true  如果应渲染注释，  false  否则。 |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


当设置为 true 时禁用渲染注释。默认情况下为 false \\u2014 显示所有注释。

某些文档格式，如 PDF 和 WordProcessing，可能包含注释。默认情况下，GroupDocs.Viewer 会渲染它们。将此选项设为 true 时，注释可能会从生成的文档中排除。此选项取代了已废弃的 'RenderComments' 属性。

**Returns:**
布尔 -  true  如果应渲染注释，  false  否则。
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


当设置为 true 时禁用渲染注释。默认情况下为 false \\u2014 显示所有注释。

某些文档格式，如 PDF 和 WordProcessing，可能包含注释。默认情况下，GroupDocs.Viewer 会渲染它们。将此选项设为 true 时，注释可能会从生成的文档中排除。此选项取代了已废弃的 'RenderComments' 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true  如果应渲染注释，  false  否则。 |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


启用渲染备注。

某些文件，如演示文稿或 Microsoft 项目文件，可能包含备注。默认情况下，GroupDocs.Viewer 不渲染备注。要实现此功能，请将此属性设为 true。代码示例请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
布尔 -  true  如果应渲染备注，  false  否则。
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


启用渲染备注。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true  如果应渲染备注，  false  否则。 |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


启用渲染隐藏页面。

某些文件，如演示文稿或电子表格，可能包含隐藏页面。默认情况下，GroupDocs.Viewer 不渲染这些页面。要实现此功能，请将此属性设为 true。代码示例请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
布尔型 -  true  如果应渲染隐藏页面，则为 true；否则为 false。
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


启用渲染隐藏页面。

某些文件，如演示文稿或电子表格，可能包含隐藏页面。默认情况下，GroupDocs.Viewer 不渲染这些页面。要实现此功能，请将此属性设为 true。代码示例请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 如果应渲染隐藏页面，则为 true；否则为 false。 |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


当文档中使用的特定字体未找到时使用的默认字体。

使用此属性设置文档的默认字体。GroupDocs.Viewer 在渲染时使用此字体，而不是任何未安装的字体。有关代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - 默认字体的名称。
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


当文档中使用的特定字体未找到时使用的默认字体。

使用此属性设置文档的默认字体。GroupDocs.Viewer 在渲染时使用此字体，而不是任何未安装的字体。有关代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 默认字体的名称。 |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


检索存档文件视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


设置存档文件视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | 存档文件的视图选项。 |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


检索 CAD 绘图视图选项。

有关更多信息和代码示例，请参阅 [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] 和 [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


设置 CAD 绘图视图选项。

有关更多信息和代码示例，请参阅 [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] 和 [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD 绘图的视图选项。 |

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


检索电子邮件消息视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


设置电子邮件消息视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | 电子邮件消息的视图选项。 |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


检索 MS Outlook 数据文件视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


设置 MS Outlook 数据文件视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | 要设置的 MS Outlook 数据文件视图选项。 |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


检索 PDF 文档的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


检索 PDF 文档的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF 文档的视图选项。 |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


检索 Lotus Notes 存储数据文件的视图选项。

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


设置 Lotus Notes 存储数据文件的视图选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes 存储数据文件的视图选项。 |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


检索项目管理文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


设置项目管理文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | 要设置的项目管理文件视图选项。 |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


检索电子表格文件的视图选项。

有关更多信息和代码示例，请参阅 [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]、[Split a worksheet into pages][] 和 [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


设置电子表格文件的视图选项。

有关更多信息和代码示例，请参阅 [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]、[Split a worksheet into pages][] 和 [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | 电子表格文件的视图选项。 |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Word 处理文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Word 处理文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | 用于渲染 Word 文档的文字处理选项。 |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


检索在查看文档时处理 Visio 文件的渲染选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


设置在查看文档时处理 Visio 文件的渲染选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | 用于处理 Visio 文件的 Visio 渲染选项。 |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


检索处理演示文稿文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - 用于处理演示文稿的演示视图选项。
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


设置处理演示文稿文件的视图选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | 用于处理演示文稿的演示视图选项。 |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


获取在渲染 Web 文档时允许自定义输出 HTML/PDF/PNG/JPEG 外观的渲染选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - 用于自定义渲染选项的 WebDocumentOptions 对象。
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


设置在渲染 Web 文档时允许自定义输出 HTML/PDF/PNG/JPEG 外观的渲染选项。

有关更多信息和代码示例，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | 用于自定义渲染选项的 WebDocumentOptions 对象。 |

