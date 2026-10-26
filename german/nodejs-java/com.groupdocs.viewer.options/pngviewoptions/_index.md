---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Dokumenten in das PNG‑Format."
type: docs
weight: 25
url: /de/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Bietet Optionen zum Rendern von Dokumenten in das PNG‑Format.

Die PngViewOptions-Klasse kapselt zusätzliche Einstellungen und Parameter, die verwendet werden können, um die Darstellung von Dokumenten im PNG-Format in der GroupDocs.Viewer-Komponente zu steuern.

Beispielhafte Verwendung:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
| [PngViewOptions()](#PngViewOptions--) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initialisiert eine neue Instanz der PngViewOptions-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Gibt die maximale Breite eines Ausgabebildes in Pixel zurück. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Setzt die maximale Breite eines Ausgabebildes in Pixeln. |
| [getMaxHeight()](#getMaxHeight--) | Gibt die maximale Höhe eines Ausgabebildes in Pixel zurück. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Setzt die maximale Höhe eines Ausgabebildes in Pixeln. |
| [isExtractText()](#isExtractText--) | Ermittelt, ob die Textextraktion aktiviert ist. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiviert oder deaktiviert die Textextraktion. |
| [getWidth()](#getWidth--) | Gibt die Breite des Ausgabebildes in Pixel zurück. |
| [setWidth(int value)](#setWidth-int-) | Setzt die Breite des Ausgabebildes in Pixeln. |
| [getHeight()](#getHeight--) | Gibt die Höhe des Ausgabebildes in Pixel zurück. |
| [setHeight(int value)](#setHeight-int-) | Setzt die Höhe des Ausgabebildes in Pixeln. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ruft den Rückruf ab, um den Speicherfortschritt eines Dokuments zu schätzen. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Setzt den Rückruf, um den Speicherfortschritt eines Dokuments zu schätzen. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den Stream freigibt, der von der Methode erstellt wurde, die dem Parameter createPageStream zugewiesen ist. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Dieser Konstruktor initialisiert eine neue Instanz von PngViewOptions mit "p\_\{0\}.png" als Dateipfadmuster für die Ausgabedateien. Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt. Für das Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Beispielsweise werden die Ausgabedateien, wenn das Dateipfadmuster 'page\_\{0\}.png' ist, als 'page\_1.png', 'page\_2.png' usw. benannt, basierend auf der Seitennummer.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadmuster, z. B. 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initialisiert eine neue Instanz der PngViewOptions-Klasse.

Beispielsweise werden die Ausgabedateien, wenn das Dateipfadmuster 'page\_\{0\}.png' ist, als 'page\_1.png', 'page\_2.png' usw. benannt, basierend auf der Seitennummer. Für das Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Das Dateipfadmuster, z. B. 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Gibt die maximale Breite eines Ausgabebildes in Pixel zurück.

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - die maximale Breite des Ausgabebildes.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Setzt die maximale Breite eines Ausgabebildes in Pixeln.

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxWidth | int | Die maximale Breite des Ausgabebildes. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Gibt die maximale Höhe eines Ausgabebildes in Pixel zurück.

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - die maximale Höhe des Ausgabebildes.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Setzt die maximale Höhe eines Ausgabebildes in Pixeln.

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxHeight | int | Die maximale Höhe des Ausgabebildes. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Ermittelt, ob die Textextraktion aktiviert ist.

Diese Option kann nützlich sein, wenn Sie eine auswählbare Textebene über das Bild hinzufügen möchten. Verwenden Sie diese Eigenschaft, um den im Quelldokument enthaltenen Text und dessen Koordinaten zu erhalten. Anschließend können Sie diese Daten verwenden, um einen auswählbaren Text über das Bild zu legen oder eine Textsuche in bildbasierter Darstellung zu implementieren. Für das Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  wenn Textextraktion aktiviert ist,  false  sonst.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiviert oder deaktiviert die Textextraktion.

Diese Option kann nützlich sein, wenn Sie eine auswählbare Textebene über das Bild hinzufügen möchten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um die Textextraktion zu aktivieren,  false  um sie zu deaktivieren. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite des Ausgabebildes in Pixel zurück.

Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - die Breite des Ausgabebildes.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die Breite des Ausgabebildes in Pixeln.

Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Die Breite des Ausgabebildes. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe des Ausgabebildes in Pixel zurück.

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - die Höhe des Ausgabebildes.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die Höhe des Ausgabebildes in Pixeln.

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Die Höhe des Ausgabebildes. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ruft den Rückruf ab, um den Speicherfortschritt eines Dokuments zu schätzen.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback zur Schätzung des Dokumentspeicherfortschritts.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Setzt den Rückruf, um den Speicherfortschritt eines Dokuments zu schätzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback zur Schätzung des Dokumentspeicherfortschritts. |

