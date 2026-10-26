---
title: "LoadOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen, die zum Öffnen einer Datei verwendet werden."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Bietet Optionen, die zum Öffnen einer Datei verwendet werden.

Die Klasse LoadOptions kapselt verschiedene Einstellungen und Parameter, die verwendet werden können, um festzulegen, wie eine Datei in der GroupDocs.Viewer‑Komponente geöffnet und geladen werden soll. Weitere Details finden Sie auf dieser [Seite][] und deren Unterseiten.

Beispielhafte Verwendung:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz der Klasse LoadOptions. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initialisiert eine neue Instanz der Klasse LoadOptions. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | Wenn aktiviert, versucht GroupDocs.Viewer strukturelle Beschädigungen in PDF‑Dokumenten zu reparieren. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Wenn aktiviert, versucht GroupDocs.Viewer strukturelle Beschädigungen in PDF‑Dokumenten zu reparieren. |
| [getFileType()](#getFileType--) | Ermittelt den Typ der zu öffnenden Datei. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Legt den Typ der zu öffnenden Datei fest. |
| [getPassword()](#getPassword--) | Ermittelt das Passwort zum Öffnen einer verschlüsselten Datei. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Legt das Passwort zum Öffnen einer verschlüsselten Datei fest. |
| [getCharset()](#getCharset--) | Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten wie [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) und [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) verwendete Zeichensatz. |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten wie [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) und [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) verwendete Zeichensatz. |
| [isDetectCharset()](#isDetectCharset--) | Diese Option aktiviert die Zeichensatz‑Erkennung für Dateien vom Typ [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Diese Option aktiviert die Zeichensatz‑Erkennung für Dateien vom Typ [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Ermittelt das Zeitlimit für das Laden externer Ressourcen. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Legt das Zeitlimit für das Laden externer Ressourcen, wie Grafiken, fest. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Ermittelt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Legt das Verbindungszeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | Ermittelt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Legt das Lesezeitlimit für die Erstellung eines [Viewer](../../com.groupdocs.viewer/viewer) mittels java.net.URL zum Laden eines Dokuments fest. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Ermittelt die Sicherheitsoptionen zur Steuerung des Vorgangs beim Extrahieren von Archiven. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Legt die Sicherheitsoptionen fest, um den Vorgang des Entpackens von Archiven zu steuern. |
| [isSkipExternalResources()](#isSkipExternalResources--) | Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer \#getWhitelistedResources().getWhitelistedResources(). |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer \#getWhitelistedResources().getWhitelistedResources(). |
| [getWhitelistedResources()](#getWhitelistedResources--) | Die Liste der URL‑Fragmente, die externen Ressourcen entsprechen und geladen werden sollen, wenn \#isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Legt die Liste der URL‑Fragmente fest, die externen Ressourcen entsprechen und geladen werden sollen, wenn \#isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz der Klasse LoadOptions.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialisiert eine neue Instanz der Klasse LoadOptions.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Typ der zu öffnenden Datei. |

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


Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF‑Dokumenten zu reparieren. Der Standardwert ist false.

Diese Funktion behandelt die folgenden Probleme in einem PDF‑Dokument:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Wenn aktiviert, versucht GroupDocs.Viewer, strukturelle Beschädigungen in PDF‑Dokumenten zu reparieren. Der Standardwert ist false.

Diese Funktion behandelt die folgenden Probleme in einem PDF‑Dokument:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Ermittelt den Typ der zu öffnenden Datei.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Legt den Typ der zu öffnenden Datei fest.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermittelt das Passwort zum Öffnen einer verschlüsselten Datei.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String – das Passwort zum Öffnen der Datei.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Legt das Passwort zum Öffnen einer verschlüsselten Datei fest.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Das Passwort zum Öffnen der Datei. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten wie [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) und [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) verwendete Zeichensatz.

Standardwert ist java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Für ein Code‑Beispiel siehe die [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Der beim Öffnen von textbasierten Dateien oder E‑Mail‑Nachrichten wie [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) und [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) verwendete Zeichensatz.

Standardwert ist java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Für ein Code‑Beispiel siehe die [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Diese Option aktiviert die Zeichensatz‑Erkennung für [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) Dateien. Falls der Zeichensatz nicht erkannt werden kann, wird der Standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) verwendet.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Wenn die Kodierung nicht erkannt werden kann, wird der Standardwert verwendet. Für ein Code‑Beispiel siehe die [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Diese Option aktiviert die Zeichensatz‑Erkennung für [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) und [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) Dateien. Falls der Zeichensatz nicht erkannt werden kann, wird der Standard‑[getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) verwendet.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Wenn die Kodierung nicht erkannt werden kann, wird der Standardwert verwendet. Für ein Code‑Beispiel siehe die [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Ermittelt das Zeitlimit für das Laden externer Ressourcen.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

Der Standardwert beträgt 30 Sekunden. Für ein Code‑Beispiel siehe die [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Legt das Zeitlimit für das Laden externer Ressourcen, wie Grafiken, fest.

***Note:** The default value is 30 seconds.*

Diese Option wird für Textverarbeitungs‑Dokumente unterstützt, die externe Ressourcen enthalten. Der Standardwert beträgt 30 Sekunden. Für ein Code‑Beispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceLoadingTimeout | int | Der Lade‑Timeout, Millisekunden. |

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
| urlConnectTimeout | int | Der Verbindungs‑Timeout. |

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
| urlReadTimeout | int | Der Lese-Timeout. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Ermittelt die Sicherheitsoptionen zur Steuerung des Vorgangs beim Extrahieren von Archiven.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - das Optionsobjekt zur Konfiguration des Vorgangs zum Extrahieren von Archiven.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Legt die Sicherheitsoptionen fest, um den Vorgang des Entpackens von Archiven zu steuern.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Das Optionsobjekt zur Konfiguration des Vorgangs zum Extrahieren von Archiven. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Wenn auf true gesetzt, werden alle externen Ressourcen wie Bilder nicht geladen, außer \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skipExternalResources | boolean | Das Flag zum Aktivieren oder Deaktivieren des Ladens externer Ressourcen. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Die Liste der URL‑Fragmente, die externen Ressourcen entsprechen und geladen werden sollen, wenn \#isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Legt die Liste der URL‑Fragmente fest, die externen Ressourcen entsprechen und geladen werden sollen, wenn \#isSkipExternalResources().isSkipExternalResources() auf `true` gesetzt ist.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | Die Liste der URL‑Fragmente, die externen Ressourcen entsprechen und geladen werden sollen. |

