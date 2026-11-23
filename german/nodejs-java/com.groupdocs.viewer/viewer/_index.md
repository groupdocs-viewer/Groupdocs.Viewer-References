---
title: "Viewer"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokument-Renderprozess steuert."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Stellt die Hauptklasse dar, die den Dokument-Renderprozess steuert.

Die Viewer-Klasse ist der Einstiegspunkt für das Rendern von Dokumenten mithilfe der GroupDocs.Viewer-Komponente. Sie bietet Methoden und Optionen zum Laden von Dokumenten aus verschiedenen Quellen, zur Anpassung des Rendering‑Prozesses und zum Abrufen der gerenderten Ausgabe in verschiedenen Formaten.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(URL url)](#Viewer-java.net.URL-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(String filePath)](#Viewer-java.lang.String-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
| [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialisiert eine neue Instanz der Viewer-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Gibt Informationen zur Ansicht und dokumentenspezifische Informationen zurück. |
| [getAttachments()](#getAttachments--) | Gibt die im Dokument enthaltenen Anhänge zurück. |
| [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Speichert eine Anhangsdatei in den Zielstream. |
| [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Erstellt eine Ansicht aller Dokumentseiten. |
| [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Erstellt eine Ansicht bestimmter Dokumentseiten. |
| [getAllFonts()](#getAllFonts--) | Gibt alle in den geladenen Dokumenten verwendeten Schriftarten zurück, einschließlich der im Dokument eingebetteten und der im Betriebssystem installierten Systemschriftarten, die im Dokument verwendet werden. |
| [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Führt eine Textsuche durch und hebt gefundene Treffer im geladenen Dokument gemäß den angegebenen Optionen hervor. |
| [getFileInfo()](#getFileInfo--) | Gibt Informationen über die Datei zurück, wie Dateityp und ein Flag, das angibt, ob die Datei verschlüsselt ist. |
| [close()](#close--) | Gibt den Dateistream und verwaltete interne Ressourcen frei. |
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

Mehr über von GroupDocs.Viewer unterstützte Dateitypen: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Die Methode, die einen lesbaren Stream zurückgibt. |

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| leaveOpen | boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts geöffnet zu lassen; andernfalls false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der lesbare Stream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| leaveOpen | boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts geöffnet zu lassen; andernfalls false. |

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |
| leaveOpen | boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts geöffnet zu lassen; andernfalls false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStream | java.io.InputStream | Der Dateistream. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |
| leaveOpen | boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts geöffnet zu lassen; andernfalls false. |

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

Mehr über von GroupDocs.Viewer unterstützte Dateitypen: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.net.URL | Eine URL zu einer Datei, die in den Viewer geladen werden soll. |

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.net.URL | Eine URL zu einer Datei, die in den Viewer geladen werden soll. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.net.URL | Eine URL zu einer Datei, die in den Viewer geladen werden soll. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.net.URL | Eine URL zu einer Datei, die in den Viewer geladen werden soll. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

Dieser Konstruktor ermöglicht es Ihnen, ein Viewer-Objekt zu erstellen, um ein Dokument aus einem [FileReader](../../com.groupdocs.viewer.interfaces/filereader) mit den angegebenen [ViewerSettings](../../com.groupdocs.viewer/viewersettings) anzuzeigen.

 **Learn more**

 *  To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer][]
 *  To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Der [FileReader](../../com.groupdocs.viewer.interfaces/filereader), der das in den Viewer zu ladende Dokument enthält. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die [ViewerSettings](../../com.groupdocs.viewer/viewersettings), die auf den Viewer angewendet werden sollen. |

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

Bietet Funktionalität zum Laden und Anzeigen von Dokumenten mit GroupDocs.Viewer.

**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Der Dateileser. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more:**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Pfad zur zu rendernden Datei. |

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.nio.file.Path | Der Pfad zur zu rendernden Datei. |

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Pfad zur zu rendernden Datei. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view a document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.nio.file.Path | Der Pfad zur zu rendernden Datei. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Pfad zur zu rendernden Datei. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.nio.file.Path | Der Pfad zur zu rendernden Datei. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Pfad zur zu rendernden Datei. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initialisiert eine neue Instanz der Viewer-Klasse.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.nio.file.Path | Der Pfad zur zu rendernden Datei. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Die Dokument-Ladeoptionen. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Die Viewer-Einstellungen. |

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


Gibt Informationen zur Ansicht und dokumentenspezifische Informationen zurück.

 **Learn more:**

 *  Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer][]


[How to get file information using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+file+information

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Die Ansicht-Info-Optionen. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.
### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Gibt die im Dokument enthaltenen Anhänge zurück.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - Anhänge, die das Dokument enthalten.
### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Speichert eine Anhangsdatei in den Zielstream.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Der Anhang. |
| Ziel | java.io.OutputStream | Der beschreibbare Stream. |

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Erstellt eine Ansicht aller Dokumentseiten.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Die Ansicht-Optionen. |

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Erstellt eine Ansicht bestimmter Dokumentseiten.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Die Ansicht-Optionen. |
| pageNumbers | int[] | Die Seitenzahlen, die angezeigt werden sollen. |

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Gibt alle in den geladenen Dokumenten verwendeten Schriftarten zurück, einschließlich der im Dokument eingebetteten und der im Betriebssystem installierten Systemschriftarten, die im Dokument verwendet werden.

Für Details siehe die [ Dokumentation][documentation].


[documentation]: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Nicht‑null-Liste aller Schriften, die im Dokument verwendet werden, das in diese [Viewer](../../com.groupdocs.viewer/viewer)-Instanz geladen wurde.
### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Führt eine Textsuche durch und hebt gefundene Treffer im geladenen Dokument gemäß den angegebenen Optionen hervor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Optionen | com.groupdocs.viewer.options.SearchHighlightOptions | Search and highlight options, including a text phrase to search. Cannot be null. |

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Gibt Informationen über die Datei zurück, wie Dateityp und ein Flag, das angibt, ob die Datei verschlüsselt ist.

**Learn more:**

 *  Learn more about how to check if a file is encrypted: [How to check if a file is encrypted][]


[How to check if a file is encrypted]: https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.
### close() {#close--}
```
public final void close()
```


Gibt den Dateistream und verwaltete interne Ressourcen frei.

