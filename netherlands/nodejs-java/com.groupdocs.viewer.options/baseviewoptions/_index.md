---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Bevat de basisrenderopties."
type: docs
weight: 12
url: /nl/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Bevat de basisrenderopties.

De BaseViewOptions klasse dient als basis voor renderopties in GroupDocs.Viewer. Het stelt je in staat om het rendergedrag van de uitvoer‑HTML, PDF, PNG en JPEG bestanden aan te passen bij het renderen van specifieke documentformaten.

***Note:** For internal usage.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | Haalt de opties op voor het splitsen van tekstbestanden in pagina's. |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Stelt de opties in voor het splitsen van tekstbestanden in pagina's. |
| [isRenderComments()](#isRenderComments--) | Schakelt het renderen van opmerkingen in. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | Schakelt het renderen van opmerkingen in. |
| [isRemoveComments()](#isRemoveComments--) | Schakelt het renderen van opmerkingen uit wanneer ingesteld op true. |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Schakelt het renderen van opmerkingen uit wanneer ingesteld op true. |
| [isRenderNotes()](#isRenderNotes--) | Schakelt het renderen van notities in. |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Schakelt het renderen van notities in. |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | Schakelt het renderen van verborgen pagina's in. |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Schakelt het renderen van verborgen pagina's in. |
| [getDefaultFontName()](#getDefaultFontName--) | Standaardlettertype dat wordt gebruikt wanneer een specifiek lettertype in het document niet kan worden gevonden. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Standaardlettertype dat wordt gebruikt wanneer een specifiek lettertype in het document niet kan worden gevonden. |
| [getArchiveOptions()](#getArchiveOptions--) | Haalt de weergave‑opties voor archiefbestanden op. |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Stelt de weergave‑opties voor archiefbestanden in. |
| [getCadOptions()](#getCadOptions--) | Haalt de weergave‑opties voor CAD-tekeningen op. |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Stelt de weergave‑opties voor CAD-tekeningen in. |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | Haalt de weergave‑opties voor e‑mailberichten op. |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Stelt de weergave‑opties voor e‑mailberichten in. |
| [getOutlookOptions()](#getOutlookOptions--) | Haalt de weergave‑opties voor MS Outlook-gegevensbestanden op. |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Stelt de weergave‑opties voor MS Outlook-gegevensbestanden in. |
| [getPdfOptions()](#getPdfOptions--) | Haalt de weergaveopties voor PDF-documenten op. |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Haalt de weergaveopties voor PDF-documenten op. |
| [getMailStorageOptions()](#getMailStorageOptions--) | Haalt de weergaveopties voor Lotus Notes-opslaggegevensbestanden op. |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Stelt de weergaveopties voor Lotus Notes-opslaggegevensbestanden in. |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | Haalt de weergaveopties voor projectmanagementbestanden op. |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Stelt de weergaveopties voor projectmanagementbestanden in. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Haalt de weergaveopties voor spreadsheetbestanden op. |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Stelt de weergaveopties voor spreadsheetbestanden in. |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | De weergaveopties voor tekstverwerkingsbestanden. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | De weergaveopties voor tekstverwerkingsbestanden. |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Haalt de renderopties op voor het verwerken van Visio-bestanden bij het bekijken van documenten. |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Stelt de renderopties in voor het verwerken van Visio-bestanden bij het bekijken van documenten. |
| [getPresentationOptions()](#getPresentationOptions--) | Haalt de weergaveopties op voor het verwerken van presentatiedocumenten. |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Stelt de weergaveopties in voor het verwerken van presentatiedocumenten. |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | Haalt de renderopties op die aanpassing van het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG mogelijk maken bij het renderen van webdocumenten. |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Stelt de renderopties in die aanpassing van het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG mogelijk maken bij het renderen van webdocumenten. |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Haalt de opties op voor het splitsen van tekstbestanden in pagina's.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Stelt de opties in voor het splitsen van tekstbestanden in pagina's.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | De opties voor het splitsen van tekstbestanden. |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Schakelt het renderen van opmerkingen in.

Standaard rendert GroupDocs.Viewer geen opmerkingen. Om dit te doen, stel deze eigenschap in op true. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
boolean -  true  als opmerkingen moeten worden gerenderd,  false  anders.
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Schakelt het renderen van opmerkingen in.

Standaard rendert GroupDocs.Viewer geen opmerkingen. Om dit te doen, stel deze eigenschap in op true. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  als opmerkingen moeten worden gerenderd,  false  anders. |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Schakelt het renderen van opmerkingen uit wanneer ingesteld op true. Standaard is false \\u2014 worden alle opmerkingen weergegeven.

Sommige documentformaten zoals PDF en WordProcessing kunnen opmerkingen bevatten. Standaard rendert GroupDocs.Viewer ze. Met deze optie ingesteld op true kunnen de opmerkingen worden uitgesloten van het resulterende document. Deze optie vervangt de verouderde eigenschap 'RenderComments'.

**Returns:**
boolean -  true  als opmerkingen moeten worden gerenderd,  false  anders.
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Schakelt het renderen van opmerkingen uit wanneer ingesteld op true. Standaard is false \\u2014 worden alle opmerkingen weergegeven.

Sommige documentformaten zoals PDF en WordProcessing kunnen opmerkingen bevatten. Standaard rendert GroupDocs.Viewer ze. Met deze optie ingesteld op true kunnen de opmerkingen worden uitgesloten van het resulterende document. Deze optie vervangt de verouderde eigenschap 'RenderComments'.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  als opmerkingen moeten worden gerenderd,  false  anders. |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Schakelt het renderen van notities in.

Sommige bestanden, zoals presentaties of Microsoft project-bestanden, kunnen notities bevatten. Standaard rendert GroupDocs.Viewer geen notities. Om dit te doen, stel deze eigenschap in op true. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
boolean -  true  als notities moeten worden gerenderd,  false  anders.
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Schakelt het renderen van notities in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  als notities moeten worden gerenderd,  false  anders. |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Schakelt het renderen van verborgen pagina's in.

Sommige bestanden, zoals presentaties of spreadsheets, kunnen verborgen pagina's bevatten. Standaard rendert GroupDocs.Viewer deze pagina's niet. Om dit te doen, stel deze eigenschap in op true. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
boolean -  true  als verborgen pagina's moeten worden gerenderd,  false  anders.
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Schakelt het renderen van verborgen pagina's in.

Sommige bestanden, zoals presentaties of spreadsheets, kunnen verborgen pagina's bevatten. Standaard rendert GroupDocs.Viewer deze pagina's niet. Om dit te doen, stel deze eigenschap in op true. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  als verborgen pagina's moeten worden gerenderd,  false  anders. |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Standaardlettertype dat wordt gebruikt wanneer een specifiek lettertype in het document niet kan worden gevonden.

Gebruik deze eigenschap om het standaardlettertype voor een document in te stellen. GroupDocs.Viewer gebruikt dit lettertype tijdens het renderen in plaats van niet‑geïnstalleerde lettertypen. Voor code‑voorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - de naam van het standaardlettertype.
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Standaardlettertype dat wordt gebruikt wanneer een specifiek lettertype in het document niet kan worden gevonden.

Gebruik deze eigenschap om het standaardlettertype voor een document in te stellen. GroupDocs.Viewer gebruikt dit lettertype tijdens het renderen in plaats van niet‑geïnstalleerde lettertypen. Voor code‑voorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | De naam van het standaardlettertype. |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Haalt de weergave‑opties voor archiefbestanden op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Stelt de weergave‑opties voor archiefbestanden in.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | De weergave‑opties voor archiefbestanden. |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Haalt de weergave‑opties voor CAD-tekeningen op.

Voor meer informatie en code‑voorbeelden, zie de [Render CAD‑tekeningen en modellen als HTML, PDF en afbeeldingsbestanden][Render CAD drawings and models as HTML_ PDF_ and image files] en [Specificeer renderopties voor CAD‑bestanden][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Stelt de weergave‑opties voor CAD-tekeningen in.

Voor meer informatie en code‑voorbeelden, zie de [Render CAD‑tekeningen en modellen als HTML, PDF en afbeeldingsbestanden][Render CAD drawings and models as HTML_ PDF_ and image files] en [Specificeer renderopties voor CAD‑bestanden][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | De weergave‑opties voor CAD‑tekeningen. |

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


Haalt de weergave‑opties voor e‑mailberichten op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Stelt de weergave‑opties voor e‑mailberichten in.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Weergave‑opties voor e‑mailberichten. |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Haalt de weergave‑opties voor MS Outlook-gegevensbestanden op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Stelt de weergave‑opties voor MS Outlook-gegevensbestanden in.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | De weergave‑opties voor MS Outlook‑gegevensbestanden om in te stellen. |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Haalt de weergaveopties voor PDF-documenten op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Haalt de weergaveopties voor PDF-documenten op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | De weergave‑opties voor PDF‑documenten. |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Haalt de weergaveopties voor Lotus Notes-opslaggegevensbestanden op.

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Stelt de weergaveopties voor Lotus Notes-opslaggegevensbestanden in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | De weergave‑opties voor Lotus Notes‑opslagbestanden. |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Haalt de weergaveopties voor projectmanagementbestanden op.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Stelt de weergaveopties voor projectmanagementbestanden in.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | De weergave‑opties voor projectmanagement‑bestanden die moeten worden ingesteld. |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Haalt de weergaveopties voor spreadsheetbestanden op.

Voor meer informatie en code‑voorbeelden, zie de [Render Excel‑ en Apple Numbers‑spreadsheets als HTML, PDF en afbeeldingsbestanden][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Splits een werkblad in pagina's][], en [Specificeer spreadsheet‑renderopties][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Stelt de weergaveopties voor spreadsheetbestanden in.

Voor meer informatie en code‑voorbeelden, zie de [Render Excel‑ en Apple Numbers‑spreadsheets als HTML, PDF en afbeeldingsbestanden][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Splits een werkblad in pagina's][], en [Specificeer spreadsheet‑renderopties][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | De weergave‑opties voor spreadsheet‑bestanden. |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


De weergaveopties voor tekstverwerkingsbestanden.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


De weergaveopties voor tekstverwerkingsbestanden.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | De Word‑verwerkingsopties voor het renderen van Word‑documenten. |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Haalt de renderopties op voor het verwerken van Visio-bestanden bij het bekijken van documenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Stelt de renderopties in voor het verwerken van Visio-bestanden bij het bekijken van documenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | De Visio‑renderopties voor het verwerken van Visio‑bestanden. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Haalt de weergaveopties op voor het verwerken van presentatiedocumenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - de weergave‑opties voor presentaties voor het verwerken van presentatiedocumenten.
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Stelt de weergaveopties in voor het verwerken van presentatiedocumenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | De weergave‑opties voor presentaties voor het verwerken van presentatiedocumenten. |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Haalt de renderopties op die aanpassing van het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG mogelijk maken bij het renderen van webdocumenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - Het WebDocumentOptions‑object voor het aanpassen van de renderopties.
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Stelt de renderopties in die aanpassing van het uiterlijk van de uitvoer HTML/PDF/PNG/JPEG mogelijk maken bij het renderen van webdocumenten.

Voor meer informatie en codevoorbeelden, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Het WebDocumentOptions‑object voor het aanpassen van de renderopties. |

