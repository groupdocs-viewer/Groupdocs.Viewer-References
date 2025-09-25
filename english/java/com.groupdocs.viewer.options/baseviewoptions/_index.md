---
title: BaseViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Contains the base rendering options.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Contains the base rendering options.

The  BaseViewOptions  class serves as the base for rendering options in GroupDocs.Viewer. It allows you to customize the rendering behavior of the output HTML, PDF, PNG, and JPEG files when rendering specific document formats.

***Note:** For internal usage.*
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | Retrieves the options for splitting text files into pages. |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Sets the options for splitting text files into pages. |
| [isRenderComments()](#isRenderComments--) | Enables rendering comments. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | Enables rendering comments. |
| [isRemoveComments()](#isRemoveComments--) | Disables rendering comments when set to true. |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Disables rendering comments when set to true. |
| [isRenderNotes()](#isRenderNotes--) | Enables rendering notes. |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Enables rendering notes. |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | Enables rendering of hidden pages. |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Enables rendering of hidden pages. |
| [getDefaultFontName()](#getDefaultFontName--) | Default font to be used when a particular font used in the document can't be found. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Default font to be used when a particular font used in the document can't be found. |
| [getArchiveOptions()](#getArchiveOptions--) | Retrieves the archive files view options. |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Sets the archive files view options. |
| [getCadOptions()](#getCadOptions--) | Retrieves the CAD drawing view options. |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Sets the CAD drawing view options. |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | Retrieves the email messages view options. |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Sets the email messages view options. |
| [getOutlookOptions()](#getOutlookOptions--) | Retrieves the MS Outlook data files view options. |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Sets the MS Outlook data files view options. |
| [getPdfOptions()](#getPdfOptions--) | Retrieves the PDF documents view options. |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Retrieves the PDF documents view options. |
| [getMailStorageOptions()](#getMailStorageOptions--) | Retrieves the Lotus Notes storage data files view options. |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Sets the Lotus Notes storage data files view options. |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | Retrieves the project management files view options. |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Sets the project management files view options. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Retrieves the spreadsheet files view options. |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Sets the spreadsheet files view options. |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | The Word processing files view options. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | The Word processing files view options. |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Retrieves the rendering options for processing Visio files when viewing documents. |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Sets the rendering options for processing Visio files when viewing documents. |
| [getPresentationOptions()](#getPresentationOptions--) | Retrieves the view options for processing presentation documents. |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Sets the view options for processing presentation documents. |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | Gets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents. |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Sets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents. |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Retrieves the options for splitting text files into pages.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Sets the options for splitting text files into pages.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | The text file splitting options. |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Enables rendering comments.

By default, GroupDocs.Viewer does not render comments. To do this, set this property to true. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
boolean -  true  if comments should be rendered,  false  otherwise.
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Enables rendering comments.

By default, GroupDocs.Viewer does not render comments. To do this, set this property to true. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if comments should be rendered,  false  otherwise. |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Disables rendering comments when set to true. By default is false \\u2014 all comments are displayed.

Some document formats like PDF and WordProcessing may contain comments. By default the GroupDocs.Viewer renders them. With this option set to true the comments may be excluded from the resultant document. This option replaces the obsolete 'RenderComments' property.

**Returns:**
boolean -  true  if comments should be rendered,  false  otherwise.
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Disables rendering comments when set to true. By default is false \\u2014 all comments are displayed.

Some document formats like PDF and WordProcessing may contain comments. By default the GroupDocs.Viewer renders them. With this option set to true the comments may be excluded from the resultant document. This option replaces the obsolete 'RenderComments' property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if comments should be rendered,  false  otherwise. |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Enables rendering notes.

Some files, such as presentations or Microsoft project files, may contain notes. By default, GroupDocs.Viewer does not render notes. To do this, set this property to true. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
boolean -  true  if notes should be rendered,  false  otherwise.
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Enables rendering notes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if notes should be rendered,  false  otherwise. |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Enables rendering of hidden pages.

Some files, such as presentations or spreadsheets, may contain hidden pages. By default, GroupDocs.Viewer does not render these pages. To do this, set this property to true. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
boolean -  true  if hidden pages should be rendered,  false  otherwise.
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Enables rendering of hidden pages.

Some files, such as presentations or spreadsheets, may contain hidden pages. By default, GroupDocs.Viewer does not render these pages. To do this, set this property to true. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if hidden pages should be rendered,  false  otherwise. |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Default font to be used when a particular font used in the document can't be found.

Use this property to set the default font for a document. GroupDocs.Viewer uses this font during rendering instead of any not installed fonts. For code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - the name of the default font.
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Default font to be used when a particular font used in the document can't be found.

Use this property to set the default font for a document. GroupDocs.Viewer uses this font during rendering instead of any not installed fonts. For code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the default font. |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Retrieves the archive files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Sets the archive files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | The archive files view options. |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Retrieves the CAD drawing view options.

For more information and code examples, see the [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] and [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Sets the CAD drawing view options.

For more information and code examples, see the [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] and [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | The CAD drawing view options. |

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


Retrieves the email messages view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Sets the email messages view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Email messages view options. |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Retrieves the MS Outlook data files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Sets the MS Outlook data files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | The MS Outlook data files view options to set. |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Retrieves the PDF documents view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Retrieves the PDF documents view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | The PDF documents view options. |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Retrieves the Lotus Notes storage data files view options.

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Sets the Lotus Notes storage data files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | The Lotus Notes storage data files view options. |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Retrieves the project management files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Sets the project management files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | The project management files view options to be set. |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Retrieves the spreadsheet files view options.

For more information and code examples, see the [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], and [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Sets the spreadsheet files view options.

For more information and code examples, see the [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], and [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | The spreadsheet files view options. |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


The Word processing files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


The Word processing files view options.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | The Word processing options for rendering Word documents. |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Retrieves the rendering options for processing Visio files when viewing documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Sets the rendering options for processing Visio files when viewing documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | The Visio rendering options for processing Visio files. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Retrieves the view options for processing presentation documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - the presentation view options for processing presentation documents.
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Sets the view options for processing presentation documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | The presentation view options for processing presentation documents. |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Gets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - The WebDocumentOptions object for customizing the rendering options.
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Sets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents.

For more information and code examples, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | The WebDocumentOptions object for customizing the rendering options. |

