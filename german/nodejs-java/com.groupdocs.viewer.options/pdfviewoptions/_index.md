---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Dokumenten in das PDF‑Format."
type: docs
weight: 23
url: /de/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Bietet Optionen zum Rendern von Dokumenten in das PDF‑Format.

Die PdfViewOptions-Klasse kapselt zusätzliche Einstellungen und Parameter, die verwendet werden können, um die Darstellung von Dokumenten im PDF-Format in der GroupDocs.Viewer-Komponente zu steuern. Weitere Details siehe die [documentation][].

Beispielhafte Verwendung:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse. |
| [PdfViewOptions()](#PdfViewOptions--) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse mit Standardeinstellungen. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initialisiert eine neue Instanz der  PdfViewOptions  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Ermittelt die maximale Breite eines Ausgabebildes in Pixeln. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Setzt die maximale Breite eines Ausgabebildes in Pixeln. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Ermittelt die maximale Höhe eines Ausgabebildes in Pixeln. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Setzt die maximale Höhe eines Ausgabebildes in Pixeln. |
| [getImageWidth()](#getImageWidth--) | Ermittelt die Breite des Ausgabebildes in Pixeln. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Setzt die Breite des Ausgabebildes in Pixeln. |
| [getImageHeight()](#getImageHeight--) | Ruft die Höhe des Ausgabebildes in Pixeln ab. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Setzt die Höhe des Ausgabebildes in Pixeln. |
| [getSecurity()](#getSecurity--) | Ruft die Sicherheitsoptionen für das Ausgabedokument im PDF-Format ab. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Setzt die Sicherheitsoptionen für das Ausgabedokument im PDF-Format. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ruft den Callback ab, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E-Mail-Dokuments zu schätzen. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Setzt den Callback, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E-Mail-Dokuments zu schätzen. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Die Methode, die zum Instanziieren des Streams zum Schreiben der Ausgabedateidaten verwendet wird. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Die Methode, die zum Freigeben des Streams verwendet wird, der von der Methode  createFileStream  erstellt wurde. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Die Fabrik, die Methoden zum Erzeugen und Freigeben des Ausgabedateistreams implementiert. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse mit Standardeinstellungen.

Dieser Konstruktor erstellt ein neues  PdfViewOptions  Objekt mit "output.pdf" als Dateipfadformat für die Ausgabedatei. Die Ausgabedatei wird im aktuellen Arbeitsverzeichnis der Anwendung abgelegt. Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse.

Dieser Konstruktor erstellt ein neues  PdfViewOptions  Objekt mit dem angegebenen Parameter  outputFilePath , der den Pfad für die Ausgabedatei im PDF-Format darstellt. Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFilePath | java.lang.String | Der Pfad für die Ausgabedatei im PDF-Format. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initialisiert eine neue Instanz der  PdfViewOptions  Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Der Pfad für die Ausgabedatei im PDF-Format. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen.

Diese Option wird für alle Eingabedateiformate unterstützt, die für die Konvertierung zu PDF unterstützt werden: [Unterstützte Dokumentformate][] Für Details und Codebeispiele siehe diese [Seite][] und deren Unterseiten.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen.

Diese Option wird für alle Eingabedateiformate unterstützt, die für die Konvertierung zu PDF unterstützt werden: [Unterstützte Dokumentformate][] Für Details und Codebeispiele siehe diese [Seite][] und deren Unterseiten.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions-Objekt oder null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Ruft die maximale Breite eines Ausgabebildes in Pixeln ab. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – die maximale Breite des Ausgabebildes in Pixeln.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Setzt die maximale Breite eines Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageMaxWidth | int | Die maximale Breite des Ausgabebildes in Pixeln. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Ruft die maximale Höhe eines Ausgabebildes in Pixeln ab. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – die maximale Höhe des Ausgabebildes in Pixeln.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageMaxHeight | int | Die maximale Höhe des Ausgabebildes in Pixeln. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Ermittelt die Breite des Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Weitere Details finden Sie in der [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – die Breite des Ausgabebildes in Pixeln.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Legt die Breite des Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bild-PDFs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageWidth | int | Die Breite des Ausgabebildes in Pixeln. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Ermittelt die Höhe des Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – die Höhe des Ausgabebildes in Pixeln.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Legt die Höhe des Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageHeight | int | Die Höhe des Ausgabebildes in Pixeln. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Ruft die Sicherheitsoptionen für das Ausgabedokument im PDF-Format ab.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Setzt die Sicherheitsoptionen für das Ausgabedokument im PDF-Format.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Die Sicherheitsoptionen für das Ausgabedokument im PDF-Format. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ruft den Callback ab, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E-Mail-Dokuments zu schätzen.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback zur Schätzung des Dokumentspeicherfortschritts.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Setzt den Callback, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E-Mail-Dokuments zu schätzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback zur Schätzung des Dokumentspeicherfortschritts. |

