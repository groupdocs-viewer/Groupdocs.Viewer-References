---
title: "LoadOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ som används för att öppna en fil."
type: docs
weight: 18
url: /sv/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Tillhandahåller alternativ som används för att öppna en fil.


Klassen LoadOptions kapslar in olika inställningar och parametrar som kan användas
för att specificera hur en fil ska öppnas och laddas i GroupDocs.Viewer-komponenten.
För detaljer, se denna [sida](../https://docs.groupdocs.com/viewer/java/loading/) och dess underliggande.


Exempel på användning:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initierar en ny instans av |
LoadOptions
klassen.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initierar en ny instans av |
LoadOptions
klassen.
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | När den är aktiverad försöker GroupDocs.Viewer reparera strukturell korruption i PDF-dokument. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | När den är aktiverad försöker GroupDocs.Viewer reparera strukturell korruption i PDF-dokument. |
|
|  | [getFileType()](#getFileType--) | Hämtar filens typ som ska öppnas. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Ställer in filens typ som ska öppnas. |
|
|  | [getPassword()](#getPassword--) | Hämtar lösenordet för att öppna en krypterad fil. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in lösenordet för att öppna en krypterad fil. |
|
|  | [getCharset()](#getCharset--) | Teckenkodningen som används vid öppning av textbaserade filer eller e‑postmeddelanden såsom |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
och [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Teckenkodningen som används vid öppning av textbaserade filer eller e‑postmeddelanden såsom |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
och [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Detta alternativ möjliggör teckenkodningsdetektering för [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) och [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-filer. |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Detta alternativ möjliggör teckenkodningsdetektering för [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) och [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-filer. |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Hämtar tidsgränsen för att ladda externa resurser. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Ställer in tidsgränsen för att ladda externa resurser, såsom grafik. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Hämtar anslutningstidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Ställer in anslutningstidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Hämtar lästidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Ställer in lästidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Hämtar säkerhetsalternativen för att kontrollera processen att extrahera arkiv. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Ställer in säkerhetsalternativen för att kontrollera processen att extrahera arkiv. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | När den är satt till true kommer alla externa resurser, såsom bilder, inte att laddas förutom #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | När den är satt till true kommer alla externa resurser, såsom bilder, inte att laddas förutom #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Listan över URL-fragment som motsvarar externa resurser som ska laddas när #isSkipExternalResources().isSkipExternalResources() är satt till `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Ställer in listan med URL-fragment som motsvarar externa resurser som ska laddas när #isSkipExternalResources().isSkipExternalResources() är satt till `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initierar en ny instans av
LoadOptions
klassen.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initierar en ny instans av
LoadOptions
klassen.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Typen av filen som ska öppnas. |
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


När den är aktiverad försöker GroupDocs.Viewer reparera strukturell korruption i PDF-dokument. Standardvärdet är falskt.


Denna funktion hanterar följande problem i ett PDF-dokument:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


När den är aktiverad försöker GroupDocs.Viewer reparera strukturell korruption i PDF-dokument. Standardvärdet är falskt.


Denna funktion hanterar följande problem i ett PDF-dokument:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Hämtar filens typ som ska öppnas.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Ställer in filens typ som ska öppnas.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar lösenordet för att öppna en krypterad fil.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - lösenordet för att öppna filen.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ställer in lösenordet för att öppna en krypterad fil.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Lösenordet för att öppna filen. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Teckenkodningen som används vid öppning av textbaserade filer eller e‑postmeddelanden såsom
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
och [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standardvärdet är java.nio.charset.StandardCharsets#UTF_8.UTF_8. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Ställ in teckenkodning

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


Teckenkodningen som används vid öppning av textbaserade filer eller e‑postmeddelanden såsom
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
och [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standardvärdet är java.nio.charset.StandardCharsets#UTF_8.UTF_8. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Ställ in teckenkodning

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Detta alternativ möjliggör teckenkodningsdetektering för [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) och [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-filer. Om teckenkodningen inte kan detekteras används standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Om kodningen inte kan detekteras används standardvärdet. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Aktivera kodningsdetektering

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


Detta alternativ möjliggör teckenkodningsdetektering för [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) och [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-filer. Om teckenkodningen inte kan detekteras används standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Om kodningen inte kan detekteras används standardvärdet. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Aktivera kodningsdetektering

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Hämtar tidsgränsen för att ladda externa resurser.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


Standardvärdet är 30 sekunder. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Ställ in tidsgräns för resursladdning till 5 sekunder

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


Ställer in tidsgränsen för att ladda externa resurser, såsom grafik.


***Note:** The default value is 30 seconds.*


Detta alternativ stöds för ordbehandlingsdokument som innehåller externa resurser.
Standardvärdet är 30 sekunder. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | Inläsningens timeout, millisekunder. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Hämtar anslutningstidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument.


***Note:** The default value is 5 seconds.*


**Returns:**
int - anslutningens timeout.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Ställer in anslutningstidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | urlConnectTimeout | int | Anslutningens timeout. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Hämtar lästidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument.


***Note:** The default value is 30 seconds.*


**Returns:**
int - läsningens timeout.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Ställer in lästidsgränsen för att skapa en [Viewer](../../com.groupdocs.viewer/viewer) med java.net.URL för att ladda ett dokument.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | urlReadTimeout | int | Läsningens timeout. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Hämtar säkerhetsalternativen för att kontrollera processen att extrahera arkiv.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - alternativobjektet för att konfigurera processen för att extrahera arkiv.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Ställer in säkerhetsalternativen för att kontrollera processen att extrahera arkiv.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Alternativobjektet för att konfigurera processen för att extrahera arkiv. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


När den är satt till true kommer alla externa resurser, såsom bilder, inte att laddas förutom #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Hoppa över inläsning av externa resurser

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


När den är satt till true kommer alla externa resurser, såsom bilder, inte att laddas förutom #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Hoppa över inläsning av externa resurser

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | skipExternalResources | boolean | Flaggan för att aktivera eller inaktivera inläsning av externa resurser. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Listan över URL-fragment som motsvarar externa resurser som ska laddas när #isSkipExternalResources().isSkipExternalResources() är satt till `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Hoppa över inläsning av externa resurser
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Aktivera inläsning av externa resurser som har fragmentet 'avatars.githubusercontent.com' i resursens URL.
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


Ställer in listan med URL-fragment som motsvarar externa resurser som ska laddas när #isSkipExternalResources().isSkipExternalResources() är satt till `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Hoppa över inläsning av externa resurser
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Aktivera inläsning av externa resurser som har fragmentet 'avatars.githubusercontent.com' i resursens URL.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | Listan med URL-fragment som motsvarar externa resurser som ska läsas in. |
|

