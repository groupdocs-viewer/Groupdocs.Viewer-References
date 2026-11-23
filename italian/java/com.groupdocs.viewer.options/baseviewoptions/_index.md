---
title: "BaseViewOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Contiene le opzioni di rendering di base."
type: docs
weight: 12
url: /it/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Contiene le opzioni di rendering di base.


Il
BaseViewOptions
la classe funge da base per le opzioni di rendering in GroupDocs.Viewer.
Consente di personalizzare il comportamento di rendering dei file HTML, PDF, PNG e JPEG di output durante il rendering
formati di documento specifici.


***Note:** For internal usage.*

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Recupera le opzioni per suddividere i file di testo in pagine. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Imposta le opzioni per suddividere i file di testo in pagine. |
|
|  | [isRenderComments()](#isRenderComments--) | Abilita il rendering dei commenti. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Abilita il rendering dei commenti. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Disabilita il rendering dei commenti quando impostato su true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Disabilita il rendering dei commenti quando impostato su true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Abilita il rendering delle note. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Abilita il rendering delle note. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Abilita il rendering delle pagine nascoste. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Abilita il rendering delle pagine nascoste. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Font predefinito da utilizzare quando un determinato font presente nel documento non può essere trovato. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Font predefinito da utilizzare quando un determinato font presente nel documento non può essere trovato. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Recupera le opzioni di visualizzazione dei file di archivio. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Imposta le opzioni di visualizzazione dei file di archivio. |
|
|  | [getCadOptions()](#getCadOptions--) | Recupera le opzioni di visualizzazione dei disegni CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Imposta le opzioni di visualizzazione dei disegni CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Recupera le opzioni di visualizzazione dei messaggi email. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Imposta le opzioni di visualizzazione dei messaggi email. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Recupera le opzioni di visualizzazione dei file dati di MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Imposta le opzioni di visualizzazione dei file dati di MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Recupera le opzioni di visualizzazione dei documenti PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Recupera le opzioni di visualizzazione dei documenti PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Recupera le opzioni di visualizzazione dei file di dati di archiviazione Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Imposta le opzioni di visualizzazione dei file di dati di archiviazione Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Recupera le opzioni di visualizzazione dei file di gestione progetti. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Imposta le opzioni di visualizzazione dei file di gestione progetti. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Recupera le opzioni di visualizzazione dei file di foglio di calcolo. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Imposta le opzioni di visualizzazione dei file di foglio di calcolo. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Le opzioni di visualizzazione dei file di elaborazione testi. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Le opzioni di visualizzazione dei file di elaborazione testi. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Recupera le opzioni di rendering per l'elaborazione dei file Visio durante la visualizzazione dei documenti. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Imposta le opzioni di rendering per l'elaborazione dei file Visio durante la visualizzazione dei documenti. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Recupera le opzioni di visualizzazione per l'elaborazione dei documenti di presentazione. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Imposta le opzioni di visualizzazione per l'elaborazione dei documenti di presentazione. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Ottiene le opzioni di rendering che consentono la personalizzazione dell'aspetto dell'output HTML/PDF/PNG/JPEG |
quando si rendono documenti Web.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Imposta le opzioni di rendering che consentono la personalizzazione dell'aspetto dell'output HTML/PDF/PNG/JPEG |
quando si rendono documenti Web.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Recupera le opzioni per suddividere i file di testo in pagine.


Per ulteriori informazioni ed esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Imposta le opzioni per suddividere i file di testo in pagine.


Per ulteriori informazioni ed esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Le opzioni di divisione dei file di testo. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Abilita il rendering dei commenti.


Per impostazione predefinita, GroupDocs.Viewer non rende i commenti. Per farlo, impostare questa proprietà su true.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  se i commenti devono essere renderizzati,  false  altrimenti.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Abilita il rendering dei commenti.


Per impostazione predefinita, GroupDocs.Viewer non rende i commenti. Per farlo, impostare questa proprietà su true.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se i commenti devono essere renderizzati,  false  altrimenti. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Disabilita il rendering dei commenti quando impostato su true. Per impostazione predefinita è false \\u2014 tutti i commenti sono visualizzati.


Alcuni formati di documento come PDF e WordProcessing possono contenere commenti. Per impostazione predefinita GroupDocs.Viewer li rende. Con questa opzione impostata su true i commenti possono essere esclusi dal documento risultante.
Questa opzione sostituisce la proprietà obsoleta 'RenderComments'.


**Returns:**
boolean -  true  se i commenti devono essere renderizzati,  false  altrimenti.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Disabilita il rendering dei commenti quando impostato su true. Per impostazione predefinita è false \\u2014 tutti i commenti sono visualizzati.


Alcuni formati di documento come PDF e WordProcessing possono contenere commenti. Per impostazione predefinita GroupDocs.Viewer li rende. Con questa opzione impostata su true i commenti possono essere esclusi dal documento risultante.
Questa opzione sostituisce la proprietà obsoleta 'RenderComments'.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se i commenti devono essere renderizzati,  false  altrimenti. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Abilita il rendering delle note.


Alcuni file, come presentazioni o file Microsoft Project, possono contenere note. Per impostazione predefinita, GroupDocs.Viewer non rende le note. Per farlo, impostare questa proprietà su true.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  se le note devono essere renderizzate,  false  altrimenti.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Abilita il rendering delle note.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se le note devono essere renderizzate,  false  altrimenti. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Abilita il rendering delle pagine nascoste.


Alcuni file, come presentazioni o fogli di calcolo, possono contenere pagine nascoste. Per impostazione predefinita, GroupDocs.Viewer non rende queste pagine. Per farlo, impostare questa proprietà su true.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  se le pagine nascoste devono essere renderizzate,  false  altrimenti.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Abilita il rendering delle pagine nascoste.


Alcuni file, come presentazioni o fogli di calcolo, possono contenere pagine nascoste. Per impostazione predefinita, GroupDocs.Viewer non rende queste pagine. Per farlo, impostare questa proprietà su true.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se le pagine nascoste devono essere renderizzate,  false  altrimenti. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Font predefinito da utilizzare quando un determinato font presente nel documento non può essere trovato.


Utilizza questa proprietà per impostare il carattere predefinito per un documento. GroupDocs.Viewer utilizza questo carattere durante il rendering invece di qualsiasi carattere non installato.
Per esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - il nome del carattere predefinito.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Font predefinito da utilizzare quando un determinato font presente nel documento non può essere trovato.


Utilizza questa proprietà per impostare il carattere predefinito per un documento. GroupDocs.Viewer utilizza questo carattere durante il rendering invece di qualsiasi carattere non installato.
Per esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome del carattere predefinito. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Recupera le opzioni di visualizzazione dei file di archivio.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Imposta le opzioni di visualizzazione dei file di archivio.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Le opzioni di visualizzazione dei file di archivio. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Recupera le opzioni di visualizzazione dei disegni CAD.


Per ulteriori informazioni ed esempi di codice, vedi il [Rendering di disegni CAD e modelli come file HTML, PDF e immagine](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) e le [Opzioni di rendering per file CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Imposta le opzioni di visualizzazione dei disegni CAD.


Per ulteriori informazioni ed esempi di codice, vedi il [Rendering di disegni CAD e modelli come file HTML, PDF e immagine](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) e le [Opzioni di rendering per file CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Le opzioni di visualizzazione del disegno CAD. |
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


Recupera le opzioni di visualizzazione dei messaggi email.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Imposta le opzioni di visualizzazione dei messaggi email.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Le opzioni di visualizzazione dei messaggi email. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Recupera le opzioni di visualizzazione dei file dati di MS Outlook.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Imposta le opzioni di visualizzazione dei file dati di MS Outlook.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Le opzioni di visualizzazione dei file dati di MS Outlook da impostare. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Recupera le opzioni di visualizzazione dei documenti PDF.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Recupera le opzioni di visualizzazione dei documenti PDF.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Le opzioni di visualizzazione dei documenti PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Recupera le opzioni di visualizzazione dei file di dati di archiviazione Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Imposta le opzioni di visualizzazione dei file di dati di archiviazione Lotus Notes.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Le opzioni di visualizzazione dei file di dati di archiviazione Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Recupera le opzioni di visualizzazione dei file di gestione progetti.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Imposta le opzioni di visualizzazione dei file di gestione progetti.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Le opzioni di visualizzazione dei file di gestione progetti da impostare. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Recupera le opzioni di visualizzazione dei file di foglio di calcolo.


Per ulteriori informazioni ed esempi di codice, vedi il [Rendering di fogli di calcolo Excel e Apple Numbers come file HTML, PDF e immagine](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), il [Dividi un foglio di lavoro in pagine](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), e le [Opzioni di rendering dei fogli di calcolo](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Imposta le opzioni di visualizzazione dei file di foglio di calcolo.


Per ulteriori informazioni ed esempi di codice, vedi il [Rendering di fogli di calcolo Excel e Apple Numbers come file HTML, PDF e immagine](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), il [Dividi un foglio di lavoro in pagine](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), e le [Opzioni di rendering dei fogli di calcolo](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Le opzioni di visualizzazione dei file di foglio di calcolo. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Le opzioni di visualizzazione dei file di elaborazione testi.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Le opzioni di visualizzazione dei file di elaborazione testi.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Le opzioni di elaborazione testi per il rendering dei documenti Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Recupera le opzioni di rendering per l'elaborazione dei file Visio durante la visualizzazione dei documenti.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Imposta le opzioni di rendering per l'elaborazione dei file Visio durante la visualizzazione dei documenti.


Per ulteriori informazioni ed esempi di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Le opzioni di rendering Visio per l'elaborazione dei file Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Recupera le opzioni di visualizzazione per l'elaborazione dei documenti di presentazione.


Per ulteriori informazioni e esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - le opzioni di visualizzazione della presentazione per l'elaborazione dei documenti di presentazione.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Imposta le opzioni di visualizzazione per l'elaborazione dei documenti di presentazione.


Per ulteriori informazioni e esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Le opzioni di visualizzazione della presentazione per l'elaborazione dei documenti di presentazione. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Ottiene le opzioni di rendering che consentono la personalizzazione dell'aspetto dell'output HTML/PDF/PNG/JPEG
quando si rendono documenti Web.


Per ulteriori informazioni e esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - L'oggetto WebDocumentOptions per personalizzare le opzioni di rendering.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Imposta le opzioni di rendering che consentono la personalizzazione dell'aspetto dell'output HTML/PDF/PNG/JPEG
quando si rendono documenti Web.


Per ulteriori informazioni e esempi di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | L'oggetto WebDocumentOptions per personalizzare le opzioni di rendering. |
|

