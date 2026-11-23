---
title: "LoadOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen bereit, die zum Öffnen einer Datei verwendet werden."
type: docs
weight: 18
url: /de/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Stellt Optionen bereit, die zum Öffnen einer Datei verwendet werden.


Die Klasse LoadOptions kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um festzulegen, wie eine Datei in der GroupDocs.Viewer‑Komponente geöffnet und geladen werden soll.
Für Details siehe diese [Seite](../https://docs.groupdocs.com/viewer/java/loading/) und deren Unterseiten.


Beispielverwendung:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz von |
LoadOptions
Klasse.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initialisiert eine neue Instanz von |
LoadOptions
Klasse.
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. |
|
|  | [getFileType()](#getFileType--) | Ermittelt den Typ der zu öffnenden Datei. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Legt den Typ der zu öffnenden Datei fest. |
|
|  | [getPassword()](#getPassword--) | Ermittelt das Passwort zum Öffnen einer verschlüsselten Datei. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Legt das Passwort zum Öffnen einer verschlüsselten Datei fest. |
|
|  | [getCharset()](#getCharset--) | Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten verwendete Zeichensatz, wie zum Beispiel |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
und [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten verwendete Zeichensatz, wie zum Beispiel |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
und [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Diese Option aktiviert die Zeichensatz-Erkennung für [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-Dateien. |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Diese Option aktiviert die Zeichensatz-Erkennung für [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV)-Dateien. |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Ermittelt das Zeitlimit für das Laden externer Ressourcen. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Legt das Zeitlimit für das Laden externer Ressourcen fest, z. B. Grafiken. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Ermittelt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Legt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Ermittelt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Legt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Ermittelt die Sicherheitsoptionen zur Steuerung des Vorgangs zum Extrahieren von Archiven. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Legt die Sicherheitsoptionen zur Steuerung des Vorgangs zum Extrahieren von Archiven fest. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Die Liste von URL‑Fragmenten, die externen Ressourcen entsprechen und geladen werden sollen, wenn #isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Legt die Liste von URL‑Fragmenten fest, die externen Ressourcen entsprechen und geladen werden sollen, wenn #isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz von
LoadOptions
Klasse.


Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialisiert eine neue Instanz von
LoadOptions
Klasse.


Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Typ der zu öffnenden Datei. |
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


Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist false.


Diese Funktion behebt die folgenden Probleme in einem PDF-Dokument:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolesch
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist false.


Diese Funktion behebt die folgenden Probleme in einem PDF-Dokument:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryRepair | boolesch |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Ermittelt den Typ der zu öffnenden Datei.


Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Legt den Typ der zu öffnenden Datei fest.


Ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermittelt das Passwort zum Öffnen einer verschlüsselten Datei.


Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String – das Passwort zum Öffnen der Datei.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Legt das Passwort zum Öffnen einer verschlüsselten Datei fest.


Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Das Passwort zum Öffnen der Datei. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten verwendete Zeichensatz, wie zum Beispiel
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
und [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standardwert ist java.nio.charset.StandardCharsets#UTF_8.UTF_8. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Zeichensatz festlegen

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


Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten verwendete Zeichensatz, wie zum Beispiel
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
und [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Standardwert ist java.nio.charset.StandardCharsets#UTF_8.UTF_8. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Zeichensatz festlegen

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Diese Option aktiviert die Zeichensatz‑Erkennung für Dateien vom Typ [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Falls der Zeichensatz nicht erkannt werden kann, wird der Standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) verwendet.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Wenn die Kodierung nicht erkannt werden kann, wird der Standardwert verwendet. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Kodierungserkennung aktivieren

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolesch
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Diese Option aktiviert die Zeichensatz‑Erkennung für Dateien vom Typ [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Falls der Zeichensatz nicht erkannt werden kann, wird der Standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) verwendet.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Wenn die Kodierung nicht erkannt werden kann, wird der Standardwert verwendet. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Kodierungserkennung aktivieren

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| detectCharset | boolesch |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Ermittelt das Zeitlimit für das Laden externer Ressourcen.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


Der Standardwert beträgt 30 Sekunden. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Ressourcen‑Lade‑Timeout auf 5 Sekunden setzen

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


Legt das Zeitlimit für das Laden externer Ressourcen fest, z. B. Grafiken.


***Note:** The default value is 30 seconds.*


Diese Option wird für Textverarbeitungs‑Dokumente unterstützt, die externe Ressourcen enthalten.
Der Standardwert beträgt 30 Sekunden. Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | Der Lade‑Timeout in Millisekunden. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Ermittelt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments.


***Note:** The default value is 5 seconds.*


**Returns:**
int – der Verbindungs‑Timeout.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Legt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | urlConnectTimeout | int | Der Verbindungs‑Timeout. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Ermittelt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments.


***Note:** The default value is 30 seconds.*


**Returns:**
int – der Lese‑Timeout.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Legt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | urlReadTimeout | int | Der Lese‑Timeout. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Ermittelt die Sicherheitsoptionen zur Steuerung des Vorgangs zum Extrahieren von Archiven.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - das Optionsobjekt zur Konfiguration des Vorgangs zum Extrahieren von Archiven.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Legt die Sicherheitsoptionen zur Steuerung des Vorgangs zum Extrahieren von Archiven fest.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Das Optionsobjekt zur Konfiguration des Vorgangs zum Extrahieren von Archiven. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Überspringen des Ladens externer Ressourcen

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolesch
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Überspringen des Ladens externer Ressourcen

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | skipExternalResources | boolesch | Das Flag zum Aktivieren oder Deaktivieren des Ladens externer Ressourcen. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Die Liste von URL‑Fragmenten, die externen Ressourcen entsprechen und geladen werden sollen, wenn #isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Überspringen des Ladens externer Ressourcen
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Aktivieren des Ladens externer Ressourcen, die das Fragment 'avatars.githubusercontent.com' in der Ressourcen-URL enthalten.
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


Legt die Liste von URL‑Fragmenten fest, die externen Ressourcen entsprechen und geladen werden sollen, wenn #isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Überspringen des Ladens externer Ressourcen
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Aktivieren des Ladens externer Ressourcen, die das Fragment 'avatars.githubusercontent.com' in der Ressourcen-URL enthalten.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | Die Liste der URL-Fragmente, die externen Ressourcen entsprechen und geladen werden sollen. |
|

