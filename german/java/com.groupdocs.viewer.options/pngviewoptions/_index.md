---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Dokumenten in das PNG‑Format bereit."
type: docs
weight: 25
url: /de/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Stellt Optionen zum Rendern von Dokumenten in das PNG‑Format bereit.


Die PngViewOptions-Klasse kapselt zusätzliche Einstellungen und Parameter, die verwendet werden können
um die Darstellung von Dokumenten im PNG-Format in der GroupDocs.Viewer-Komponente zu steuern.


Beispielverwendung:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Weitere Details finden Sie auf dieser [Seite](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) und deren Unterseiten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
|  | [PngViewOptions()](#PngViewOptions--) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initialisiert eine neue Instanz von |
PngViewOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Gibt die maximale Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Legt die maximale Breite eines Ausgabebildes in Pixeln fest. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Gibt die maximale Höhe eines Ausgabebildes in Pixeln zurück. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. |
|
|  | [isExtractText()](#isExtractText--) | Bestimmt, ob die Textextraktion aktiviert ist. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiviert oder deaktiviert die Textextraktion. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setWidth(int value)](#setWidth-int-) | Legt die Breite des Ausgabebildes in Pixeln fest. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe des Ausgabebildes in Pixeln zurück. |
|
|  | [setHeight(int value)](#setHeight-int-) | Legt die Höhe des Ausgabebildes in Pixeln fest. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ruft den Rückruf zur Schätzung des Speicherfortschritts eines Dokuments ab. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Setzt den Rückruf zur Schätzung des Speicherfortschritts eines Dokuments. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erzeugt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erzeugt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den vom der createPageStream-Parameter zugewiesenen Methode erstellten Stream freigibt. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Dieser Konstruktor initialisiert eine neue Instanz von
PngViewOptions

mit \"p_{0}.png\" als Dateipfadformat für die Ausgabedateien.
Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Zum Beispiel, wenn das Dateipfadformat 'page_{0}.png' ist, werden die Ausgabedateien
benannt als 'page_1.png', 'page_2.png' usw., basierend auf der Seitenzahl.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initialisiert eine neue Instanz von
PngViewOptions
Klasse.


Zum Beispiel, wenn das Dateipfadformat 'page_{0}.png' ist, werden die Ausgabedateien
benannt als 'page_1.png', 'page_2.png' usw., basierend auf der Seitenzahl.
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Das Dateipfadformat, z. B. 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Gibt die maximale Breite des Ausgabebildes in Pixeln zurück.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int – die maximale Breite des Ausgabebildes.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Legt die maximale Breite eines Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxWidth | int | Die maximale Breite des Ausgabebildes. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Gibt die maximale Höhe eines Ausgabebildes in Pixeln zurück.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Returns:**
int - die maximale Höhe des Ausgabebildes.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Legt die maximale Höhe eines Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Wenn Sie die Eigenschaft setzen, wird diese Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxHeight | int | Die maximale Höhe des Ausgabebildes. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Bestimmt, ob die Textextraktion aktiviert ist.


Diese Option kann nützlich sein, wenn Sie eine auswählbare Textebene über dem Bild hinzufügen möchten.
Verwenden Sie diese Eigenschaft, um den Text aus einem Quelldokument und dessen Koordinaten zu erhalten. Anschließend können Sie diese Daten nutzen, um einen auswählbaren Text über das Bild zu legen oder eine Textsuche bei bildbasierter Darstellung zu implementieren.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  wenn die Textextraktion aktiviert ist,  false  sonst.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiviert oder deaktiviert die Textextraktion.


Diese Option kann nützlich sein, wenn Sie eine auswählbare Textebene über dem Bild hinzufügen möchten.


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
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Returns:**
int - die Breite des Ausgabebildes.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Legt die Breite des Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die Breite des Ausgabebildes. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe des Ausgabebildes in Pixeln zurück.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Returns:**
int - die Höhe des Ausgabebildes.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Legt die Höhe des Ausgabebildes in Pixeln fest.


Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Wenn Sie diese Eigenschaft setzen, wird die Eigenschaft ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die Höhe des Ausgabebildes. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ruft den Rückruf zur Schätzung des Speicherfortschritts eines Dokuments ab.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback zur Schätzung des Dokumentenspeicherfortschritts.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Setzt den Rückruf zur Schätzung des Speicherfortschritts eines Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback zur Schätzung des Dokumentenspeicherfortschritts. |
|

