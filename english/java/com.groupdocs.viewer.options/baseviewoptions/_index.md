---
title: BaseViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides base rendering options.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Provides base rendering options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | Text files splitting to pages options. |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Text files splitting to pages options. |
| [isRenderComments()](#isRenderComments--) | Enables rendering comments. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | Enables rendering comments. |
| [isRenderNotes()](#isRenderNotes--) | Enables rendering notes. |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Enables rendering notes. |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | Enables rendering of hidden pages. |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Enables rendering of hidden pages. |
| [getDefaultFontName()](#getDefaultFontName--) | Default font to be used when particular font used in document can't be found. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Default font to be used when particular font used in document can't be found. |
| [getArchiveOptions()](#getArchiveOptions--) | The archive files view options. |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | The archive files view options. |
| [getCadOptions()](#getCadOptions--) | The CAD drawing view options. |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | The CAD drawing view options. |
| [getEmailOptions()](#getEmailOptions--) | The email messages view options. |
| [isEmailOptionsInitialized_Internal()](#isEmailOptionsInitialized-Internal--) |  |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | The email messages view options. |
| [getOutlookOptions()](#getOutlookOptions--) | The MS Outlook data files view options. |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | The MS Outlook data files view options. |
| [getPdfOptions()](#getPdfOptions--) | The PDF documents view options. |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | The PDF documents view options. |
| [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes storage data files view options. |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes storage data files view options. |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | The project management files view options. |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | The project management files view options. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | The spreadsheet files view options. |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | The spreadsheet files view options. |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | The word processing documents view options. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | The word processing documents view options. |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | The Visio files processing documents view options. |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Sets the Visio files processing documents view options. |
| [getPresentationOptions()](#getPresentationOptions--) | The presentation processing documents view options. |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | The presentation processing documents view options. |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Text files splitting to pages options.

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions)
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Text files splitting to pages options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) |  |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Enables rendering comments.

**Returns:**
boolean
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Enables rendering comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Enables rendering notes.

**Returns:**
boolean
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Enables rendering notes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Enables rendering of hidden pages.

**Returns:**
boolean
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Enables rendering of hidden pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Default font to be used when particular font used in document can't be found.

**Returns:**
java.lang.String
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Default font to be used when particular font used in document can't be found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


The archive files view options.

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions)
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


The archive files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) |  |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


The CAD drawing view options.

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions)
### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


The CAD drawing view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) |  |

### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


The email messages view options.

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions)
### isEmailOptionsInitialized_Internal() {#isEmailOptionsInitialized-Internal--}
```
public boolean isEmailOptionsInitialized_Internal()
```




**Returns:**
boolean
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


The email messages view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) |  |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


The MS Outlook data files view options.

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions)
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


The MS Outlook data files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


The PDF documents view options.

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


The PDF documents view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) |  |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes storage data files view options.

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions)
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes storage data files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) |  |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


The project management files view options.

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions)
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


The project management files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


The spreadsheet files view options.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions)
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


The spreadsheet files view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) |  |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


The word processing documents view options.

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions)
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


The word processing documents view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) |  |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


The Visio files processing documents view options.

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions)
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Sets the Visio files processing documents view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | The Visio files processing documents view options. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


The presentation processing documents view options.

**Returns:**
com.groupdocs.viewer.options.PresentationOptions
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


The presentation processing documents view options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions |  |

