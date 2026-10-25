---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Innehåller de grundläggande renderingsalternativen."
type: docs
weight: 12
url: /sv/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Innehåller de grundläggande renderingsalternativen.


Den
BaseViewOptions
klassen fungerar som bas för renderingsalternativ i GroupDocs.Viewer.
Den låter dig anpassa renderingsbeteendet för de genererade HTML-, PDF-, PNG- och JPEG-filerna vid rendering
specifika dokumentformat.


***Note:** For internal usage.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Hämtar alternativen för att dela textfiler i sidor. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Ställer in alternativen för att dela textfiler i sidor. |
|
|  | [isRenderComments()](#isRenderComments--) | Aktiverar rendering av kommentarer. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Aktiverar rendering av kommentarer. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Inaktiverar rendering av kommentarer när den är satt till true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Inaktiverar rendering av kommentarer när den är satt till true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Aktiverar rendering av anteckningar. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Aktiverar rendering av anteckningar. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Aktiverar rendering av dolda sidor. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Aktiverar rendering av dolda sidor. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Standardteckensnitt som ska användas när ett specifikt teckensnitt i dokumentet inte kan hittas. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Standardteckensnitt som ska användas när ett specifikt teckensnitt i dokumentet inte kan hittas. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Hämtar visningsalternativen för arkivfiler. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Ställer in visningsalternativen för arkivfiler. |
|
|  | [getCadOptions()](#getCadOptions--) | Hämtar visningsalternativen för CAD-ritningar. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Ställer in visningsalternativen för CAD-ritningar. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Hämtar visningsalternativen för e‑postmeddelanden. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Ställer in visningsalternativen för e‑postmeddelanden. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Hämtar visningsalternativen för MS Outlook-datafiler. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Ställer in visningsalternativen för MS Outlook-datafiler. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Hämtar visningsalternativen för PDF-dokument. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Hämtar visningsalternativen för PDF-dokument. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Hämtar visningsalternativen för Lotus Notes lagringsdatafiler. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Ställer in visningsalternativen för Lotus Notes lagringsdatafiler. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Hämtar visningsalternativen för projektledningsfiler. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Ställer in visningsalternativen för projektledningsfiler. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Hämtar visningsalternativen för kalkylbladsfiler. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Ställer in visningsalternativen för kalkylbladsfiler. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Visningsalternativen för Word‑behandlingsfiler. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Visningsalternativen för Word‑behandlingsfiler. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Hämtar renderingsalternativen för bearbetning av Visio‑filer vid visning av dokument. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Ställer in renderingsalternativen för bearbetning av Visio‑filer vid visning av dokument. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Hämtar visningsalternativen för bearbetning av presentationsdokument. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Ställer in visningsalternativen för bearbetning av presentationsdokument. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Hämtar renderingsalternativen som möjliggör anpassning av utdataformatens utseende för HTML/PDF/PNG/JPEG |
vid rendering av webb‑dokument.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Ställer in renderingsalternativen som möjliggör anpassning av utdataformatens utseende för HTML/PDF/PNG/JPEG |
vid rendering av webb‑dokument.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Hämtar alternativen för att dela textfiler i sidor.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Ställer in alternativen för att dela textfiler i sidor.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Alternativen för delning av textfiler. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Aktiverar rendering av kommentarer.


Som standard renderar GroupDocs.Viewer inte kommentarer. För att göra detta, sätt denna egenskap till true.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  om kommentarer ska renderas,  false  annars.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Aktiverar rendering av kommentarer.


Som standard renderar GroupDocs.Viewer inte kommentarer. För att göra detta, sätt denna egenskap till true.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  om kommentarer ska renderas,  false  annars. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Inaktiverar rendering av kommentarer när den är satt till true. Som standard är den false \\u2014 alla kommentarer visas.


Vissa dokumentformat som PDF och WordProcessing kan innehålla kommentarer. Som standard renderar GroupDocs.Viewer dem. Med detta alternativ satt till true kan kommentarer uteslutas från det resulterande dokumentet.
Detta alternativ ersätter den föråldrade egenskapen 'RenderComments'.


**Returns:**
boolean -  true  om kommentarer ska renderas,  false  annars.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Inaktiverar rendering av kommentarer när den är satt till true. Som standard är den false \\u2014 alla kommentarer visas.


Vissa dokumentformat som PDF och WordProcessing kan innehålla kommentarer. Som standard renderar GroupDocs.Viewer dem. Med detta alternativ satt till true kan kommentarer uteslutas från det resulterande dokumentet.
Detta alternativ ersätter den föråldrade egenskapen 'RenderComments'.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  om kommentarer ska renderas,  false  annars. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Aktiverar rendering av anteckningar.


Vissa filer, såsom presentationer eller Microsoft‑projektfiler, kan innehålla anteckningar. Som standard renderar GroupDocs.Viewer inte anteckningar. För att göra detta, sätt denna egenskap till true.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  om anteckningar ska renderas,  false  annars.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Aktiverar rendering av anteckningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  om anteckningar ska renderas,  false  annars. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Aktiverar rendering av dolda sidor.


Vissa filer, såsom presentationer eller kalkylblad, kan innehålla dolda sidor. Som standard renderar GroupDocs.Viewer inte dessa sidor. För att göra detta, sätt denna egenskap till true.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  om dolda sidor ska renderas,  false  annars.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Aktiverar rendering av dolda sidor.


Vissa filer, såsom presentationer eller kalkylblad, kan innehålla dolda sidor. Som standard renderar GroupDocs.Viewer inte dessa sidor. För att göra detta, sätt denna egenskap till true.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  om dolda sidor ska renderas,  false  annars. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Standardteckensnitt som ska användas när ett specifikt teckensnitt i dokumentet inte kan hittas.


Använd den här egenskapen för att ange standardteckensnittet för ett dokument. GroupDocs.Viewer använder detta teckensnitt under rendering istället för eventuella icke‑installerade teckensnitt.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - namnet på standardteckensnittet.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Standardteckensnitt som ska användas när ett specifikt teckensnitt i dokumentet inte kan hittas.


Använd den här egenskapen för att ange standardteckensnittet för ett dokument. GroupDocs.Viewer använder detta teckensnitt under rendering istället för eventuella icke‑installerade teckensnitt.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Namnet på standardteckensnittet. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Hämtar visningsalternativen för arkivfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Ställer in visningsalternativen för arkivfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Visningsalternativen för arkivfiler. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Hämtar visningsalternativen för CAD-ritningar.


För mer information och kodexempel, se [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) och [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Ställer in visningsalternativen för CAD-ritningar.


För mer information och kodexempel, se [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) och [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Visningsalternativen för CAD-ritning. |
|

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


Hämtar visningsalternativen för e‑postmeddelanden.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Ställer in visningsalternativen för e‑postmeddelanden.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Visningsalternativ för e-postmeddelanden. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Hämtar visningsalternativen för MS Outlook-datafiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Ställer in visningsalternativen för MS Outlook-datafiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Visningsalternativen för MS Outlook-datafiler att ange. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Hämtar visningsalternativen för PDF-dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Hämtar visningsalternativen för PDF-dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Visningsalternativen för PDF-dokument. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Hämtar visningsalternativen för Lotus Notes lagringsdatafiler.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Ställer in visningsalternativen för Lotus Notes lagringsdatafiler.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Visningsalternativen för Lotus Notes lagringsdatafiler. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Hämtar visningsalternativen för projektledningsfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Ställer in visningsalternativen för projektledningsfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Visningsalternativen för projektledningsfiler att ställa in. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Hämtar visningsalternativen för kalkylbladsfiler.


För mer information och kodexempel, se [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), och [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Ställer in visningsalternativen för kalkylbladsfiler.


För mer information och kodexempel, se [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), och [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Visningsalternativen för kalkylbladsfiler. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Visningsalternativen för Word‑behandlingsfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Visningsalternativen för Word‑behandlingsfiler.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word‑behandlingsalternativen för rendering av Word‑dokument. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Hämtar renderingsalternativen för bearbetning av Visio‑filer vid visning av dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Ställer in renderingsalternativen för bearbetning av Visio‑filer vid visning av dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio‑renderingsalternativen för bearbetning av Visio‑filer. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Hämtar visningsalternativen för bearbetning av presentationsdokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - presentationsvisningsalternativen för att bearbeta presentationsdokument.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Ställer in visningsalternativen för bearbetning av presentationsdokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Presentationsvisningsalternativen för att bearbeta presentationsdokument. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Hämtar renderingsalternativen som möjliggör anpassning av utdataformatens utseende för HTML/PDF/PNG/JPEG
vid rendering av webb‑dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - WebDocumentOptions-objektet för att anpassa renderingsalternativen.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Ställer in renderingsalternativen som möjliggör anpassning av utdataformatens utseende för HTML/PDF/PNG/JPEG
vid rendering av webb‑dokument.


För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | WebDocumentOptions-objektet för att anpassa renderingsalternativen. |
|

