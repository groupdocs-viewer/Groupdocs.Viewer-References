---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties die worden gebruikt om een bestand te openen."
type: docs
weight: 18
url: /nl/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Biedt opties die worden gebruikt om een bestand te openen.


De LoadOptions‑klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt
om te specificeren hoe een bestand moet worden geopend en geladen in de GroupDocs.Viewer‑component.
Voor details, zie deze [pagina](../https://docs.groupdocs.com/viewer/java/loading/) en de onderliggende pagina's.


Voorbeeldgebruik:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialiseert een nieuw exemplaar van de |
LoadOptions
klasse.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initialiseert een nieuw exemplaar van de |
LoadOptions
klasse.
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | Wanneer ingeschakeld, probeert GroupDocs.Viewer structurele corruptie in PDF‑documenten te repareren. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Wanneer ingeschakeld, probeert GroupDocs.Viewer structurele corruptie in PDF‑documenten te repareren. |
|
|  | [getFileType()](#getFileType--) | Haalt het type van het te openen bestand op. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Stelt het type van het te openen bestand in. |
|
|  | [getPassword()](#getPassword--) | Haalt het wachtwoord op voor het openen van een versleuteld bestand. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stelt het wachtwoord in voor het openen van een versleuteld bestand. |
|
|  | [getCharset()](#getCharset--) | De tekenset die wordt gebruikt bij het openen van tekstgebaseerde bestanden of e‑mailberichten zoals |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
en [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | De tekenset die wordt gebruikt bij het openen van tekstgebaseerde bestanden of e‑mailberichten zoals |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
en [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Deze optie schakelt de tekensetdetectie in voor [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) en [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) bestanden. |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Deze optie schakelt de tekensetdetectie in voor [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) en [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) bestanden. |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Haalt de time‑out op voor het laden van externe bronnen. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Stelt de time‑out in voor het laden van externe bronnen, zoals afbeeldingen. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Haalt de verbindings‑time‑out op voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Stelt de verbindings‑time‑out in voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Haalt de lees‑time‑out op voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Stelt de lees‑time‑out in voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Haalt de beveiligingsopties op om het proces van het uitpakken van archieven te beheersen. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Stelt de beveiligingsopties in om het proces van het uitpakken van archieven te beheersen. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Wanneer ingesteld op true, worden alle externe bronnen zoals afbeeldingen niet geladen, behalve #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Wanneer ingesteld op true, worden alle externe bronnen zoals afbeeldingen niet geladen, behalve #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | De lijst met URL‑fragmenten die overeenkomen met externe bronnen die geladen moeten worden wanneer #isSkipExternalResources().isSkipExternalResources() is ingesteld op `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Stelt de lijst met URL-fragmenten in die overeenkomen met externe bronnen die geladen moeten worden wanneer #isSkipExternalResources().isSkipExternalResources() is ingesteld op `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialiseert een nieuw exemplaar van de
LoadOptions
klasse.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de
LoadOptions
klasse.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het type van het bestand dat geopend moet worden. |
|

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


Wanneer ingeschakeld, probeert GroupDocs.Viewer structurele corruptie in PDF-documenten te herstellen. Standaardwaarde is false.


Deze functie lost de volgende problemen op in een PDF-document:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Wanneer ingeschakeld, probeert GroupDocs.Viewer structurele corruptie in PDF-documenten te herstellen. Standaardwaarde is false.


Deze functie lost de volgende problemen op in een PDF-document:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Haalt het type van het te openen bestand op.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Stelt het type van het te openen bestand in.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt het wachtwoord op voor het openen van een versleuteld bestand.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - het wachtwoord voor het openen van het bestand.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stelt het wachtwoord in voor het openen van een versleuteld bestand.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het wachtwoord voor het openen van het bestand. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


De tekenset die wordt gebruikt bij het openen van tekstgebaseerde bestanden of e‑mailberichten zoals
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
en [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standaardwaarde is java.nio.charset.StandardCharsets#UTF_8.UTF_8. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Stel de tekenset in

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


De tekenset die wordt gebruikt bij het openen van tekstgebaseerde bestanden of e‑mailberichten zoals
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
en [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standaardwaarde is java.nio.charset.StandardCharsets#UTF_8.UTF_8. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Stel de tekenset in

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Deze optie schakelt de tekensetdetectie voor [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), en [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) bestanden in. In het geval dat de tekenset niet kan worden gedetecteerd, wordt de standaard [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) gebruikt.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Als de codering niet kan worden gedetecteerd, wordt de standaard gebruikt. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Coderingdetectie inschakelen

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Deze optie schakelt de tekensetdetectie voor [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), en [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) bestanden in. In het geval dat de tekenset niet kan worden gedetecteerd, wordt de standaard [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) gebruikt.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Als de codering niet kan worden gedetecteerd, wordt de standaard gebruikt. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Coderingdetectie inschakelen

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Haalt de time‑out op voor het laden van externe bronnen.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


De standaardwaarde is 30 seconden. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Stel de time-out voor het laden van bronnen in op 5 seconden

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Stelt de time‑out in voor het laden van externe bronnen, zoals afbeeldingen.


***Note:** The default value is 30 seconds.*


Deze optie wordt ondersteund voor Word Processing-documenten die externe bronnen bevatten.
De standaardwaarde is 30 seconden. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | De laadtijd, milliseconden. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Haalt de verbindings‑time‑out op voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden.


***Note:** The default value is 5 seconds.*


**Returns:**
int - de verbindings‑timeout.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Stelt de verbindings‑time‑out in voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | urlConnectTimeout | int | De verbindings‑timeout. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Haalt de lees‑time‑out op voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden.


***Note:** The default value is 30 seconds.*


**Returns:**
int - de lees‑timeout.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Stelt de lees‑time‑out in voor het maken van een [Viewer](../../com.groupdocs.viewer/viewer) met java.net.URL om een document te laden.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | urlReadTimeout | int | De lees‑timeout. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Haalt de beveiligingsopties op om het proces van het uitpakken van archieven te beheersen.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - het optiesobject om het proces van het uitpakken van archieven te configureren.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Stelt de beveiligingsopties in om het proces van het uitpakken van archieven te beheersen.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Het optiesobject om het proces van het uitpakken van archieven te configureren. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Wanneer ingesteld op true, worden alle externe bronnen zoals afbeeldingen niet geladen, behalve #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Sla het laden van externe bronnen over

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Wanneer ingesteld op true, worden alle externe bronnen zoals afbeeldingen niet geladen, behalve #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Sla het laden van externe bronnen over

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | skipExternalResources | boolean | De vlag om het laden van externe bronnen in of uit te schakelen. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


De lijst met URL‑fragmenten die overeenkomen met externe bronnen die geladen moeten worden wanneer #isSkipExternalResources().isSkipExternalResources() is ingesteld op `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Sla het laden van externe bronnen over
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Schakel het laden van externe bronnen in die een 'avatars.githubusercontent.com' fragment in de resource‑URL hebben.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Stelt de lijst met URL-fragmenten in die overeenkomen met externe bronnen die geladen moeten worden wanneer #isSkipExternalResources().isSkipExternalResources() is ingesteld op `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Sla het laden van externe bronnen over
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Schakel het laden van externe bronnen in die een 'avatars.githubusercontent.com' fragment in de resource‑URL hebben.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | De lijst met URL‑fragmenten die overeenkomen met externe bronnen die geladen moeten worden. |
|

