---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni utilizzate per aprire un file."
type: docs
weight: 18
url: /it/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Fornisce opzioni utilizzate per aprire un file.


La classe LoadOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per specificare come un file dovrebbe essere aperto e caricato nel componente GroupDocs.Viewer.
Per i dettagli, vedere questa [pagina](../https://docs.groupdocs.com/viewer/java/loading/) e le relative sotto-pagine.


Esempio di utilizzo:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inizializza una nuova istanza di |
LoadOptions
classe.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Inizializza una nuova istanza di |
LoadOptions
classe.
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | Quando abilitato, GroupDocs.Viewer tenta di riparare la corruzione strutturale nei documenti PDF. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Quando abilitato, GroupDocs.Viewer tenta di riparare la corruzione strutturale nei documenti PDF. |
|
|  | [getFileType()](#getFileType--) | Ottiene il tipo del file da aprire. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Imposta il tipo del file da aprire. |
|
|  | [getPassword()](#getPassword--) | Ottiene la password per aprire un file crittografato. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per aprire un file crittografato. |
|
|  | [getCharset()](#getCharset--) | Il set di caratteri utilizzato durante l'apertura di file basati su testo o messaggi email come |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
e [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Il set di caratteri utilizzato durante l'apertura di file basati su testo o messaggi email come |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
e [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Questa opzione abilita il rilevamento del set di caratteri per i file [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) e [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Questa opzione abilita il rilevamento del set di caratteri per i file [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) e [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Ottiene il timeout per il caricamento delle risorse esterne. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Imposta il timeout per il caricamento delle risorse esterne, come le grafiche. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Ottiene il timeout di connessione per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Imposta il timeout di connessione per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Ottiene il timeout di lettura per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Imposta il timeout di lettura per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Ottiene le opzioni di sicurezza per controllare il processo di estrazione degli archivi. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Imposta le opzioni di sicurezza per controllare il processo di estrazione degli archivi. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Quando impostato su true, tutte le risorse esterne come le immagini non verranno caricate, eccetto #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Quando impostato su true, tutte le risorse esterne come le immagini non verranno caricate, eccetto #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | L'elenco dei frammenti URL corrispondenti alle risorse esterne che dovrebbero essere caricate quando #isSkipExternalResources().isSkipExternalResources() è impostato su `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Imposta l'elenco di frammenti URL corrispondenti alle risorse esterne che devono essere caricate quando #isSkipExternalResources().isSkipExternalResources() è impostato su `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inizializza una nuova istanza di
LoadOptions
classe.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Inizializza una nuova istanza di
LoadOptions
classe.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo del file da aprire. |
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


Quando abilitato, GroupDocs.Viewer tenta di riparare la corruzione strutturale nei documenti PDF. Il valore predefinito è false.


Questa funzionalità affronta i seguenti problemi in un documento PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Quando abilitato, GroupDocs.Viewer tenta di riparare la corruzione strutturale nei documenti PDF. Il valore predefinito è false.


Questa funzionalità affronta i seguenti problemi in un documento PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Ottiene il tipo del file da aprire.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Imposta il tipo del file da aprire.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene la password per aprire un file crittografato.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - la password per aprire il file.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta la password per aprire un file crittografato.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password per aprire il file. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Il set di caratteri utilizzato durante l'apertura di file basati su testo o messaggi email come
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
e [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Il valore predefinito è java.nio.charset.StandardCharsets#UTF_8.UTF_8. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Imposta il set di caratteri

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


Il set di caratteri utilizzato durante l'apertura di file basati su testo o messaggi email come
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
e [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Il valore predefinito è java.nio.charset.StandardCharsets#UTF_8.UTF_8. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Imposta il set di caratteri

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Questa opzione abilita il rilevamento del set di caratteri per i file [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) e [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Nel caso in cui il set di caratteri non possa essere rilevato, viene utilizzato il valore predefinito [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Se la codifica non può essere rilevata, viene utilizzato il valore predefinito. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Abilita il rilevamento della codifica

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


Questa opzione abilita il rilevamento del set di caratteri per i file [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) e [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Nel caso in cui il set di caratteri non possa essere rilevato, viene utilizzato il valore predefinito [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Se la codifica non può essere rilevata, viene utilizzato il valore predefinito. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Abilita il rilevamento della codifica

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Ottiene il timeout per il caricamento delle risorse esterne.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


Il valore predefinito è 30 secondi. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Imposta il timeout di caricamento delle risorse a 5 secondi

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


Imposta il timeout per il caricamento delle risorse esterne, come le grafiche.


***Note:** The default value is 30 seconds.*


Questa opzione è supportata per i documenti di elaborazione testi che contengono risorse esterne.
Il valore predefinito è 30 secondi. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | Il timeout di caricamento, millisecondi. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Ottiene il timeout di connessione per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento.


***Note:** The default value is 5 seconds.*


**Returns:**
int - il timeout di connessione.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Imposta il timeout di connessione per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | urlConnectTimeout | int | Il timeout di connessione. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Ottiene il timeout di lettura per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento.


***Note:** The default value is 30 seconds.*


**Returns:**
int - il timeout di lettura.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Imposta il timeout di lettura per creare un [Viewer](../../com.groupdocs.viewer/viewer) utilizzando java.net.URL per caricare un documento.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | urlReadTimeout | int | Il timeout di lettura. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Ottiene le opzioni di sicurezza per controllare il processo di estrazione degli archivi.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - l'oggetto opzioni per configurare il processo di estrazione degli archivi.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Imposta le opzioni di sicurezza per controllare il processo di estrazione degli archivi.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | L'oggetto opzioni per configurare il processo di estrazione degli archivi. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Quando impostato su true, tutte le risorse esterne come le immagini non verranno caricate, eccetto #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignora il caricamento di risorse esterne

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


Quando impostato su true, tutte le risorse esterne come le immagini non verranno caricate, eccetto #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignora il caricamento di risorse esterne

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | skipExternalResources | boolean | Il flag per abilitare o disabilitare il caricamento di risorse esterne. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


L'elenco dei frammenti URL corrispondenti alle risorse esterne che dovrebbero essere caricate quando #isSkipExternalResources().isSkipExternalResources() è impostato su `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignora il caricamento di risorse esterne
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Abilita il caricamento di risorse esterne che hanno il frammento 'avatars.githubusercontent.com' nell'URL della risorsa.
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


Imposta l'elenco di frammenti URL corrispondenti alle risorse esterne che devono essere caricate quando #isSkipExternalResources().isSkipExternalResources() è impostato su `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignora il caricamento di risorse esterne
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Abilita il caricamento di risorse esterne che hanno il frammento 'avatars.githubusercontent.com' nell'URL della risorsa.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | L'elenco dei frammenti URL corrispondenti alle risorse esterne che dovrebbero essere caricate. |
|

