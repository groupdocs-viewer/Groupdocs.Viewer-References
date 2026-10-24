---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Enthält die grundlegenden Rendering-Optionen."
type: docs
weight: 12
url: /de/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Enthält die grundlegenden Rendering-Optionen.


Die
BaseViewOptions
Klasse dient als Basis für Rendering‑Optionen in GroupDocs.Viewer.
Sie ermöglicht es Ihnen, das Rendering‑Verhalten der Ausgabe‑HTML, PDF, PNG und JPEG Dateien beim Rendern anzupassen
spezifischer Dokumentformate.


***Note:** For internal usage.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Gibt die Optionen zum Aufteilen von Textdateien in Seiten zurück. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Setzt die Optionen zum Aufteilen von Textdateien in Seiten. |
|
|  | [isRenderComments()](#isRenderComments--) | Aktiviert das Rendern von Kommentaren. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Aktiviert das Rendern von Kommentaren. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Deaktiviert das Rendern von Kommentaren, wenn auf true gesetzt. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Deaktiviert das Rendern von Kommentaren, wenn auf true gesetzt. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Aktiviert das Rendern von Notizen. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Aktiviert das Rendern von Notizen. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Aktiviert das Rendern versteckter Seiten. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Aktiviert das Rendern versteckter Seiten. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Standard-Schriftart, die verwendet wird, wenn eine im Dokument verwendete Schriftart nicht gefunden werden kann. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Standard-Schriftart, die verwendet wird, wenn eine im Dokument verwendete Schriftart nicht gefunden werden kann. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Ruft die Anzeigeoptionen für Archivdateien ab. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Legt die Anzeigeoptionen für Archivdateien fest. |
|
|  | [getCadOptions()](#getCadOptions--) | Ruft die Anzeigeoptionen für CAD-Zeichnungen ab. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Legt die Anzeigeoptionen für CAD-Zeichnungen fest. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Ruft die Anzeigeoptionen für E-Mail-Nachrichten ab. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Legt die Anzeigeoptionen für E-Mail-Nachrichten fest. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Ruft die Anzeigeoptionen für MS Outlook-Datendateien ab. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Legt die Anzeigeoptionen für MS Outlook-Datendateien fest. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Ruft die Anzeigeoptionen für PDF-Dokumente ab. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Ruft die Anzeigeoptionen für PDF-Dokumente ab. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Ruft die Anzeigeoptionen für Lotus Notes-Speicherdatendateien ab. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Legt die Anzeigeoptionen für Lotus Notes-Speicherdatendateien fest. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Ruft die Anzeigeoptionen für Projektmanagementdateien ab. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Legt die Anzeigeoptionen für Projektmanagementdateien fest. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ruft die Anzeigeoptionen für Tabellenkalkulationsdateien ab. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Legt die Anzeigeoptionen für Tabellenkalkulationsdateien fest. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Die Anzeigeoptionen für Textverarbeitungsdateien. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Die Anzeigeoptionen für Textverarbeitungsdateien. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Ruft die Rendering-Optionen für die Verarbeitung von Visio-Dateien beim Anzeigen von Dokumenten ab. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Legt die Rendering-Optionen für die Verarbeitung von Visio-Dateien beim Anzeigen von Dokumenten fest. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Ruft die Anzeigeoptionen für die Verarbeitung von Präsentationsdokumenten ab. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Legt die Anzeigeoptionen für die Verarbeitung von Präsentationsdokumenten fest. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Ruft die Rendering-Optionen ab, die die Anpassung des Erscheinungsbildes der Ausgabe-HTML/PDF/PNG/JPEG ermöglichen |
beim Rendern von Webdokumenten.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Legt die Rendering-Optionen fest, die die Anpassung des Erscheinungsbildes der Ausgabe-HTML/PDF/PNG/JPEG ermöglichen |
beim Rendern von Webdokumenten.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Gibt die Optionen zum Aufteilen von Textdateien in Seiten zurück.


Weitere Informationen und Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Setzt die Optionen zum Aufteilen von Textdateien in Seiten.


Weitere Informationen und Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Die Optionen zum Aufteilen von Textdateien. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Aktiviert das Rendern von Kommentaren.


Standardmäßig rendert GroupDocs.Viewer keine Kommentare. Um dies zu tun, setzen Sie diese Eigenschaft auf true.
Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  wenn Kommentare gerendert werden sollen,  false  andernfalls.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Aktiviert das Rendern von Kommentaren.


Standardmäßig rendert GroupDocs.Viewer keine Kommentare. Um dies zu tun, setzen Sie diese Eigenschaft auf true.
Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  wenn Kommentare gerendert werden sollen,  false  andernfalls. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Deaktiviert das Rendern von Kommentaren, wenn auf true gesetzt. Standardmäßig ist false \u2014 alle Kommentare werden angezeigt.


Einige Dokumentformate wie PDF und WordProcessing können Kommentare enthalten. Standardmäßig rendert GroupDocs.Viewer diese. Wenn diese Option auf true gesetzt ist, können die Kommentare aus dem resultierenden Dokument ausgeschlossen werden.
Diese Option ersetzt die veraltete Eigenschaft 'RenderComments'.


**Returns:**
boolean -  true  wenn Kommentare gerendert werden sollen,  false  andernfalls.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Deaktiviert das Rendern von Kommentaren, wenn auf true gesetzt. Standardmäßig ist false \u2014 alle Kommentare werden angezeigt.


Einige Dokumentformate wie PDF und WordProcessing können Kommentare enthalten. Standardmäßig rendert GroupDocs.Viewer diese. Wenn diese Option auf true gesetzt ist, können die Kommentare aus dem resultierenden Dokument ausgeschlossen werden.
Diese Option ersetzt die veraltete Eigenschaft 'RenderComments'.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  wenn Kommentare gerendert werden sollen,  false  andernfalls. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Aktiviert das Rendern von Notizen.


Einige Dateien, wie Präsentationen oder Microsoft‑Project‑Dateien, können Notizen enthalten. Standardmäßig rendert GroupDocs.Viewer keine Notizen. Um dies zu tun, setzen Sie diese Eigenschaft auf true.
Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  wenn Notizen gerendert werden sollen,  false  andernfalls.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Aktiviert das Rendern von Notizen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  wenn Notizen gerendert werden sollen,  false  andernfalls. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Aktiviert das Rendern versteckter Seiten.


Einige Dateien, wie Präsentationen oder Tabellenkalkulationen, können versteckte Seiten enthalten. Standardmäßig rendert GroupDocs.Viewer diese Seiten nicht. Um dies zu tun, setzen Sie diese Eigenschaft auf true.
Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  wenn versteckte Seiten gerendert werden sollen,  false  andernfalls.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Aktiviert das Rendern versteckter Seiten.


Einige Dateien, wie Präsentationen oder Tabellenkalkulationen, können versteckte Seiten enthalten. Standardmäßig rendert GroupDocs.Viewer diese Seiten nicht. Um dies zu tun, setzen Sie diese Eigenschaft auf true.
Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  wenn versteckte Seiten gerendert werden sollen,  false  andernfalls. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Standard-Schriftart, die verwendet wird, wenn eine im Dokument verwendete Schriftart nicht gefunden werden kann.


Verwenden Sie diese Eigenschaft, um die Standardschriftart für ein Dokument festzulegen. GroupDocs.Viewer verwendet diese Schriftart beim Rendern anstelle nicht installierter Schriften.
Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - der Name der Standardschriftart.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Standard-Schriftart, die verwendet wird, wenn eine im Dokument verwendete Schriftart nicht gefunden werden kann.


Verwenden Sie diese Eigenschaft, um die Standardschriftart für ein Dokument festzulegen. GroupDocs.Viewer verwendet diese Schriftart beim Rendern anstelle nicht installierter Schriften.
Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Name der Standardschriftart. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Ruft die Anzeigeoptionen für Archivdateien ab.


Weitere Informationen und Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Legt die Anzeigeoptionen für Archivdateien fest.


Weitere Informationen und Codebeispiele finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Die Ansichtoptionen für Archivdateien. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Ruft die Anzeigeoptionen für CAD-Zeichnungen ab.


Für weitere Informationen und Codebeispiele siehe die [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) und [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Legt die Anzeigeoptionen für CAD-Zeichnungen fest.


Für weitere Informationen und Codebeispiele siehe die [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) und [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Die Ansichtoptionen für CAD-Zeichnungen. |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolesch
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


Ruft die Anzeigeoptionen für E-Mail-Nachrichten ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Legt die Anzeigeoptionen für E-Mail-Nachrichten fest.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Ansichtoptionen für E-Mail-Nachrichten. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Ruft die Anzeigeoptionen für MS Outlook-Datendateien ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Legt die Anzeigeoptionen für MS Outlook-Datendateien fest.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Die Ansichtoptionen für MS Outlook-Datendateien zum Festlegen. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Ruft die Anzeigeoptionen für PDF-Dokumente ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Ruft die Anzeigeoptionen für PDF-Dokumente ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Die Ansichtoptionen für PDF-Dokumente. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Ruft die Anzeigeoptionen für Lotus Notes-Speicherdatendateien ab.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Legt die Anzeigeoptionen für Lotus Notes-Speicherdatendateien fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Die Ansichtoptionen für Lotus Notes Speicherdateien. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Ruft die Anzeigeoptionen für Projektmanagementdateien ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Legt die Anzeigeoptionen für Projektmanagementdateien fest.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Die Ansichtoptionen für Projektmanagementdateien zum Festlegen. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Ruft die Anzeigeoptionen für Tabellenkalkulationsdateien ab.


Für weitere Informationen und Codebeispiele siehe die [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), und [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Legt die Anzeigeoptionen für Tabellenkalkulationsdateien fest.


Für weitere Informationen und Codebeispiele siehe die [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), und [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Die Ansichtoptionen für Tabellenkalkulationsdateien. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Die Anzeigeoptionen für Textverarbeitungsdateien.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Die Anzeigeoptionen für Textverarbeitungsdateien.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Die Word-Verarbeitungsoptionen für das Rendern von Word-Dokumenten. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Ruft die Rendering-Optionen für die Verarbeitung von Visio-Dateien beim Anzeigen von Dokumenten ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Legt die Rendering-Optionen für die Verarbeitung von Visio-Dateien beim Anzeigen von Dokumenten fest.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Die Visio-Renderoptionen für die Verarbeitung von Visio-Dateien. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Ruft die Anzeigeoptionen für die Verarbeitung von Präsentationsdokumenten ab.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - die Präsentationsansichtsoptionen für die Verarbeitung von Präsentationsdokumenten.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Legt die Anzeigeoptionen für die Verarbeitung von Präsentationsdokumenten fest.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Die Präsentationsansichtsoptionen für die Verarbeitung von Präsentationsdokumenten. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Ruft die Rendering-Optionen ab, die die Anpassung des Erscheinungsbildes der Ausgabe-HTML/PDF/PNG/JPEG ermöglichen
beim Rendern von Webdokumenten.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - Das WebDocumentOptions-Objekt zum Anpassen der Rendering-Optionen.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Legt die Rendering-Optionen fest, die die Anpassung des Erscheinungsbildes der Ausgabe-HTML/PDF/PNG/JPEG ermöglichen
beim Rendern von Webdokumenten.


Für weitere Informationen und Codebeispiele siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Das WebDocumentOptions-Objekt zum Anpassen der Rendering-Optionen. |
|

