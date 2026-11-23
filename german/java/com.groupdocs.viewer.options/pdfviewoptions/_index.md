---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Dokumenten in das PDF‑Format bereit."
type: docs
weight: 23
url: /de/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Stellt Optionen zum Rendern von Dokumenten in das PDF‑Format bereit.


Die Klasse PdfViewOptions kapselt zusätzliche Einstellungen und Parameter.
die verwendet werden können, um das Rendern von Dokumenten in das PDF-Format in der GroupDocs.Viewer-Komponente zu steuern.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


Beispielverwendung:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initialisiert eine neue Instanz von |
PdfViewOptions
Klasse.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initialisiert eine neue Instanz von |
PdfViewOptions
Klasse.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initialisiert eine neue Instanz der Klasse PdfViewOptions. |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | Initialisiert eine neue Instanz der Klasse PdfViewOptions mit den Standardeinstellungen. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initialisiert eine neue Instanz von |
PdfViewOptions
Klasse.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initialisiert eine neue Instanz von |
PdfViewOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Gibt die maximale Breite eines Ausgabebildes in Pixeln zurück. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Legt die maximale Breite eines Ausgabebildes in Pixeln fest. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Gibt die maximale Höhe eines Ausgabebildes in Pixeln zurück. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. |
|
|  | [getImageWidth()](#getImageWidth--) | Gibt die Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Legt die Breite des Ausgabebildes in Pixeln fest. |
|
|  | [getImageHeight()](#getImageHeight--) | Gibt die Höhe des Ausgabebildes in Pixeln zurück. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Legt die Höhe des Ausgabebildes in Pixeln fest. |
|
|  | [getSecurity()](#getSecurity--) | Gibt die Sicherheitsoptionen für das ausgegebene PDF-Dokument zurück. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Legt die Sicherheitsoptionen für das ausgegebene PDF-Dokument fest. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Gibt den Callback zurück, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E‑Mail-Dokuments abzuschätzen. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Legt den Callback fest, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E‑Mail-Dokuments abzuschätzen. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initialisiert eine neue Instanz von
PdfViewOptions
Klasse.


Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initialisiert eine neue Instanz von
PdfViewOptions
Klasse.


Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Die Methode, die zum Instanziieren des Streams zum Schreiben der Ausgabedateidaten verwendet wird. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Die Methode, die zum Freigeben des von der Methode  createFileStream  erstellten Streams verwendet wird. |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initialisiert eine neue Instanz der Klasse PdfViewOptions.


Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Die Fabrik, die Methoden zum Erzeugen und Freigeben des Ausgabedatei‑Streams implementiert. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initialisiert eine neue Instanz der Klasse PdfViewOptions mit den Standardeinstellungen.


Dieser Konstruktor erstellt ein neues
PdfViewOptions
Objekt mit "output.pdf" als Dateipfadformat für die Ausgabedatei.
Die Ausgabedatei wird im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.
Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initialisiert eine neue Instanz von
PdfViewOptions
Klasse.


Dieser Konstruktor erstellt ein neues
PdfViewOptions
Objekt mit dem angegebenen
outputFilePath
Parameter
der den Pfad für die Ausgabedatei im PDF-Format darstellt.
Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | Der Pfad für die Ausgabedatei im PDF-Format. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initialisiert eine neue Instanz von
PdfViewOptions
Klasse.


Für das Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | Der Pfad für die Ausgabedatei im PDF-Format. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen.


Diese Option wird für alle Eingabedateiformate unterstützt, die für die Konvertierung zu PDF unterstützt werden: [Unterstützte Dokumentformate](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Für Details und Code‑Beispiele siehe diese [Seite](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) und deren Unterseiten.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Reduziert die Größe der ausgegebenen PDF-Datei durch Anwendung von Optimierungstechniken mit verschiedenen Optionen.


Diese Option wird für alle Eingabedateiformate unterstützt, die für die Konvertierung zu PDF unterstützt werden: [Unterstützte Dokumentformate](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Für Details und Code‑Beispiele siehe diese [Seite](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) und deren Unterseiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions‑Objekt oder null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Ermittelt die maximale Breite eines Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int – die maximale Breite des Ausgabebildes in Pixeln.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Legt die maximale Breite eines Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageMaxWidth | int | Die maximale Breite des Ausgabebildes in Pixeln. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Ermittelt die maximale Höhe eines Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Für Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int – die maximale Höhe des Ausgabebildes in Pixeln.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageMaxHeight | int | Die maximale Höhe des Ausgabebildes in Pixeln. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Ermittelt die Breite des Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft beim Rendern eines einzelnen Bildes zu PDF an. Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Returns:**
int – die Breite des Ausgabebildes in Pixeln.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Legt die Breite des Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bild‑PDFs.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageWidth | int | Die Breite des Ausgabebildes in Pixeln. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Ermittelt die Höhe des Ausgabebildes in Pixeln. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Returns:**
int – die Höhe des Ausgabebildes in Pixeln.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Legt die Höhe des Ausgabebildes in Pixeln fest. Dieser Parameter gilt nur beim Konvertieren eines einzelnen Bildes zu HTML.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageHeight | int | Die Höhe des Ausgabebildes in Pixeln. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Gibt die Sicherheitsoptionen für das ausgegebene PDF-Dokument zurück.


Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Legt die Sicherheitsoptionen für das ausgegebene PDF-Dokument fest.


Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | Die Sicherheitsoptionen für das Ausgabedokument im PDF-Format. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Gibt den Callback zurück, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E‑Mail-Dokuments abzuschätzen.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback zur Schätzung des Dokumentenspeicherfortschritts.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Legt den Callback fest, der verwendet wird, um den Fortschritt beim Speichern eines Words- oder E‑Mail-Dokuments abzuschätzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback zur Schätzung des Dokumentenspeicherfortschritts. |
|

