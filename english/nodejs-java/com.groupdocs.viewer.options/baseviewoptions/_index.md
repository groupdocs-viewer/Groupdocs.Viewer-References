---
title: BaseViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Class that provides base rendering options.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Class that provides base rendering options.

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
| [getWordProcessingOptions()](#getWordProcessingOptions--) | Retrieves the rendering options for customizing the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Sets the rendering options for customizing the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents. |
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

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Sets the options for splitting text files into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | The text file splitting options. |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Enables rendering comments.

**Returns:**
boolean -  true  if comments should be rendered,  false  otherwise.
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Enables rendering comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if comments should be rendered,  false  otherwise. |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Enables rendering notes.

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

**Returns:**
boolean -  true  if hidden pages should be rendered,  false  otherwise.
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Enables rendering of hidden pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if hidden pages should be rendered,  false  otherwise. |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Default font to be used when a particular font used in the document can't be found.

**Returns:**
java.lang.String - the name of the default font.
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Default font to be used when a particular font used in the document can't be found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the default font. |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Retrieves the archive files view options.

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Sets the archive files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | The archive files view options. |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Retrieves the CAD drawing view options.

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Sets the CAD drawing view options.

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

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Sets the email messages view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Email messages view options. |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Retrieves the MS Outlook data files view options.

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Sets the MS Outlook data files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | The MS Outlook data files view options to set. |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Retrieves the PDF documents view options.

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Retrieves the PDF documents view options.

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

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Sets the project management files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | The project management files view options to be set. |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Retrieves the spreadsheet files view options.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Sets the spreadsheet files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | The spreadsheet files view options. |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Retrieves the rendering options for customizing the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents.

***Note:** See also [Render Word documents as HTML, PDF, or image files][Render Word documents as HTML_ PDF_ or image files]*


[Render Word documents as HTML_ PDF_ or image files]: https://docs.groupdocs.com/viewer/java/how-to-view-word-documents-using-java/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Sets the rendering options for customizing the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents.

***Note:** See also [Render Word documents as HTML, PDF, or image files][Render Word documents as HTML_ PDF_ or image files]*


[Render Word documents as HTML_ PDF_ or image files]: https://docs.groupdocs.com/viewer/java/how-to-view-word-documents-using-java/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | The Word processing options for rendering Word documents. |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Retrieves the rendering options for processing Visio files when viewing documents.

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Sets the rendering options for processing Visio files when viewing documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | The Visio rendering options for processing Visio files. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Retrieves the view options for processing presentation documents.

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - the presentation view options for processing presentation documents.
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Sets the view options for processing presentation documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | The presentation view options for processing presentation documents. |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Gets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents.

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - The WebDocumentOptions object for customizing the rendering options.
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Sets the rendering options that allow customization of the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | The WebDocumentOptions object for customizing the rendering options. |

