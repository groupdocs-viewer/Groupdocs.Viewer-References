---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Dokumenten im JPG-Format bereit."
type: docs
weight: 17
url: /de/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Stellt Optionen zum Rendern von Dokumenten im JPG-Format bereit.


Die Klasse JpgViewOptions kapselt zusätzliche Einstellungen und Parameter, die zur Steuerung der Dokumentdarstellung verwendet werden können
in das JPG-Format in der GroupDocs.Viewer-Komponente.


Beispielverwendung:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialisiert eine neue Instanz von |
JpgViewOptions
Klasse.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialisiert eine neue Instanz von |
JpgViewOptions
Klasse.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialisiert eine neue Instanz von |
JpgViewOptions
Klasse.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Initialisiert eine neue Instanz von |
JpgViewOptions
mit "p_{0}.jpg" als Dateipfadsformat für die Ausgabedateien.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initialisiert eine neue Instanz von |
JpgViewOptions
Klasse.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initialisiert eine neue Instanz von |
JpgViewOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Ermittelt die maximale Breite eines Ausgabebildes in Pixeln. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Legt die maximale Breite eines Ausgabebildes in Pixeln fest. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Gibt die maximale Höhe des Ausgabebildes in Pixeln zurück. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. |
|
|  | [getQuality()](#getQuality--) | Ermittelt die Qualität des Ausgabebildes. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Legt die Qualität des Ausgabebildes fest. |
|
|  | [isExtractText()](#isExtractText--) | Ermöglicht die Textextraktion. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiviert oder deaktiviert die Textextraktion. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setWidth(int value)](#setWidth-int-) | Legt die Breite des Ausgabebildes in Pixeln fest. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe des Ausgabebildes in Pixeln. |
|
|  | [setHeight(int value)](#setHeight-int-) | Legt die Höhe des Ausgabebildes in Pixeln fest. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Ermittelt die Fabrik, die Methoden zum Erzeugen und Freigeben des Ausgabeseiten‑Streams implementiert. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ermittelt den Callback, um den Speicherfortschritt eines Words- oder E‑Mail-Dokuments zu schätzen. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Setzt den Callback, um den Speicherfortschritt eines Words- oder E‑Mail-Dokuments zu schätzen. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz von
JpgViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erzeugt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz von
JpgViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erzeugt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den Stream freigibt, der von der Methode erstellt wurde, die dem Delegaten zugewiesen ist, der an den Parameter  createPageStream  übergeben wird. |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initialisiert eine neue Instanz von
JpgViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initialisiert eine neue Instanz von
JpgViewOptions
mit "p_{0}.jpg" als Dateipfadsformat für die Ausgabedateien.
Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initialisiert eine neue Instanz von
JpgViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initialisiert eine neue Instanz von
JpgViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Das Dateipfadformat, z. B. 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Ermittelt die maximale Breite eines Ausgabebildes in Pixeln.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft #setWidth(int).setWidth(int) setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int - die maximale Breite eines Ausgabebildes.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Legt die maximale Breite eines Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft #setWidth(int).setWidth(int) setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxWidth | int | Die maximale Breite eines Ausgabebildes. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Gibt die maximale Höhe des Ausgabebildes in Pixeln zurück.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft #setHeight(int).setHeight(int) setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int - die maximale Höhe eines Ausgabebildes.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Legt die maximale Höhe eines Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft #setHeight(int).setHeight(int) setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxHeight | int | Die maximale Höhe eines Ausgabebildes. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Ermittelt die Qualität des Ausgabebildes.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte – die Qualität des Ausgabebildes.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Legt die Qualität des Ausgabebildes fest.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | byte | Die Qualität des Ausgabebildes. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Ermöglicht die Textextraktion.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  wenn die Textextraktion aktiviert ist,  false  sonst.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiviert oder deaktiviert die Textextraktion.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  zum Aktivieren der Textextraktion,  false  zum Deaktivieren. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite des Ausgabebildes in Pixeln zurück.


Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft #setMaxWidth(int).setMaxWidth(int) ignoriert.


**Returns:**
int - die Breite des Ausgabebildes.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Legt die Breite des Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft #setMaxWidth(int).setMaxWidth(int) ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die Breite des Ausgabebildes. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ermittelt die Höhe des Ausgabebildes in Pixeln.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft #setMaxHeight(int).setMaxHeight(int) ignoriert.


**Returns:**
int - die Höhe des Ausgabebildes.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Legt die Höhe des Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft #setMaxHeight(int).setMaxHeight(int) ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die Höhe des Ausgabebildes. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Ermittelt die Fabrik, die Methoden zum Erzeugen und Freigeben des Ausgabeseiten‑Streams implementiert.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ermittelt den Callback, um den Speicherfortschritt eines Words- oder E‑Mail-Dokuments zu schätzen.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback zur Schätzung des Dokumentenspeicherfortschritts.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Setzt den Callback, um den Speicherfortschritt eines Words- oder E‑Mail-Dokuments zu schätzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback zur Schätzung des Dokumentenspeicherfortschritts. |
|

