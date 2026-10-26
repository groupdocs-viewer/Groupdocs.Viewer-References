---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Verwenden Sie diese Klasse, um PDF‑Optimierungsoptionen festzulegen, die auf die ausgegebene PDF‑Datei angewendet werden."
type: docs
weight: 21
url: /de/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Verwenden Sie diese Klasse, um PDF‑Optimierungsoptionen festzulegen, die auf die ausgegebene PDF‑Datei angewendet werden.

Diese Optimierungsoptionen werden für alle Eingabedateiformate unterstützt, die für den Export nach PDF unterstützt werden. Weitere Details und Codebeispiele finden Sie auf dieser [Seite][] und deren Unterseiten.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Legt Standardwerte für die Option MaxResolution auf 300 und für die Option ImageQuality auf 100 fest. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isLinearize()](#isLinearize--) | Ermöglicht die Optimierung der ausgegebenen PDF-Datei für die Online‑Ansicht in einem Webbrowser. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Legt fest, ob die ausgegebene PDF-Datei für das Online‑Durchsuchen mit einem Webbrowser optimiert werden soll. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Anmerkungen können gelöscht werden, wenn sie nicht erforderlich sind. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Legt fest, ob unnötige Anmerkungen aus der PDF entfernt werden sollen. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Wenn das PDF‑Dokument AcroForms enthält, können wir versuchen, die Dateigröße durch Flachlegen der Formularfelder zu reduzieren. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Legt fest, ob Formularfelder aus der PDF entfernt werden sollen. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | Eine PDF‑Datei besteht aus Text, Bild, Anhang, Anmerkungen, Grafiken und anderen Objekten. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Legt fest, ob die PDF in Graustufen konvertiert werden soll. |
| [isSubsetFonts()](#isSubsetFonts--) | Jede Schriftart, die zur Anzeige von Text auf der Seite verwendet wird, enthält einen Satz von Glyphen für die Schriftzeichen. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Legt fest, ob die Schriftarten in der PDF als Subset verwendet werden sollen. |
| [isCompressImages()](#isCompressImages--) | Wenn die Quell‑PDF‑Datei Bilder enthält, sollte man erwägen, die Bilder zu komprimieren und deren Qualität einzustellen. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Legt fest, ob die Bilder in der PDF komprimiert werden sollen. |
| [getImageQuality()](#getImageQuality--) | Wenn die Quell‑PDF‑Datei Bilder enthält, sollte man erwägen, die Bilder zu komprimieren und deren Qualität einzustellen. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Legt die Bildqualität für die Komprimierung der Bilder in der PDF fest. |
| [isResizeImages()](#isResizeImages--) | Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu verkleinern. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Legt fest, ob die Bilder in der PDF verkleinert werden sollen. |
| [getMaxResolution()](#getMaxResolution--) | Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu verkleinern. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Legt die maximale Auflösung für das Verkleinern der Bilder in der PDF fest. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimiert die Rahmenlinien und Schriftarten von Excel‑Tabellen für eine kleinere Ausgabedateigröße. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Legt fest, ob die Tabellen in der PDF optimiert werden sollen. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Entfernt private Informationen (Seitenstück‑Info), wenn auf true gesetzt. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Legt fest, ob private Informationen aus der PDF entfernt werden sollen. |
| [isUnembedFonts()](#isUnembedFonts--) | Wenn das Dokument eingebettete Schriftarten verwendet, bedeutet das, dass alle Schriftartdaten im Dokument gespeichert sind. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Legt fest, ob die eingebetteten Schriftarten in der PDF entbettet werden sollen. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Manchmal enthält ein Dokument mehrere identische Ressourcen‑Streams (zum Beispiel Bilder). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Legt fest, ob doppelte Streams in der PDF verlinkt werden sollen. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Wenn diese Eigenschaft auf true gesetzt ist, wird der Seiteninhalt beim Optimieren des Dokuments für identische Seiten wiederverwendet. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Legt fest, ob das Wiederverwenden von Seiteninhalt im PDF erlaubt werden soll. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Manchmal enthält ein Dokument ungenutzte Ressourcen-Streams. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Legt fest, ob ungenutzte Streams aus dem PDF entfernt werden sollen. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Ein PDF-Dokument enthält manchmal PDF-Objekte, die von keinem anderen Objekt im Dokument referenziert werden. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Legt fest, ob ungenutzte Objekte aus dem PDF entfernt werden sollen. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Legt Standardwerte für die Option MaxResolution auf 300 und für die Option ImageQuality auf 100 fest.

Weitere Details und Codebeispiele finden Sie auf dieser [Seite][] und deren Unterseiten.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Ermöglicht die Optimierung der ausgegebenen PDF-Datei für die Online‑Ansicht in einem Webbrowser.

Für ein Codebeispiel siehe diese [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolescher Wert –  true  wenn das ausgegebene PDF für das Online‑Durchsuchen optimiert ist,  false  sonst.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Legt fest, ob die ausgegebene PDF-Datei für das Online‑Durchsuchen mit einem Webbrowser optimiert werden soll.

Für ein Codebeispiel siehe diese [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linearize | boolean | true  um das ausgegebene PDF für das Online‑Durchsuchen zu optimieren,  false  sonst. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anmerkungen können gelöscht werden, wenn sie nicht erforderlich sind. Wenn sie benötigt werden, aber keine zusätzliche Bearbeitung erfordern, können sie flachgelegt werden. Dies reduziert die Dateigröße.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolescher Wert –  true  wenn Anmerkungen entfernt werden,  false  sonst.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Legt fest, ob unnötige Anmerkungen aus der PDF entfernt werden sollen.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeAnnotations | boolean | true  um unnötige Anmerkungen zu entfernen,  false  sonst. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Wenn das PDF‑Dokument AcroForms enthält, können wir versuchen, die Dateigröße durch Flachlegen der Formularfelder zu reduzieren.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolescher Wert –  true  wenn Formularfelder entfernt werden,  false  sonst.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Legt fest, ob Formularfelder aus der PDF entfernt werden sollen.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeFormFields | boolean | true  um Formularfelder zu entfernen,  false  sonst. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Eine PDF-Datei besteht aus Text, Bild, Anhang, Anmerkungen, Grafiken und anderen Objekten. Möglicherweise benötigen Sie die Umwandlung einer PDF von RGB-Farbraum in Graustufen, um beim Drucken dieser PDF-Dateien schneller zu sein. Außerdem wird beim Konvertieren in Graustufen die Dateigröße reduziert, jedoch kann dabei die Dokumentqualität leiden. Derzeit wird diese Funktion vom Pre‑Flight‑Tool von Adobe Acrobat unterstützt.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolescher Wert –  true  wenn die PDF in Graustufen konvertiert wird,  false  sonst.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Legt fest, ob die PDF in Graustufen konvertiert werden soll.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertToGrayScale | boolean | true  um die PDF in Graustufen zu konvertieren,  false  sonst. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Jede Schrift, die zur Anzeige von Text auf der Seite verwendet wird, enthält einen Satz von Glyphen für die Schriftzeichen. Die PDF‑Spezifikation unterstützt das "Font Subset", d. h. eine Schriftart nur mit den tatsächlich verwendeten Glyphen. Dies kann Probleme verursachen, wenn Text aktualisiert werden soll (da möglicherweise erforderliche Glyphen in der Schrift fehlen), aber für ein Dokument, das nicht geändert werden soll, ermöglicht dies eine Reduzierung der Größe.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolescher Wert –  true  wenn Schriften subsettet werden,  false  sonst.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Legt fest, ob die Schriftarten in der PDF als Subset verwendet werden sollen.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subsetFonts | boolean | true  um die Schriften zu subsettieren,  false  sonst. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Wenn die Quell-PDF-Datei Bilder enthält, sollten Sie die Bilder komprimieren und deren Qualität einstellen. Um die Bildkomprimierung zu aktivieren, setzen Sie diese Option auf true. Alle Bilder in einem Dokument werden neu komprimiert. Die Komprimierung wird durch die ImageQuality‑Eigenschaft definiert, die den Qualitätswert in Prozent angibt. 100 % bedeutet unveränderte Qualität. Um die Bildqualität zu verringern, setzen Sie die ImageQuality‑Eigenschaft auf einen Wert unter 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  wenn Bilder komprimiert sind,  false  sonst.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Legt fest, ob die Bilder in der PDF komprimiert werden sollen.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressImages | boolean | true  zum Komprimieren der Bilder,  false  sonst. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Wenn die Quell-PDF-Datei Bilder enthält, sollten Sie die Bilder komprimieren und deren Qualität einstellen. Um die Bildkomprimierung zu aktivieren, setzen Sie die Option CompressImages auf true. Alle Bilder in einem Dokument werden neu komprimiert. Die Komprimierung wird durch die ImageQuality‑Eigenschaft definiert, die den Qualitätswert in Prozent angibt. 100 % bedeutet unveränderte Qualität. Um die Bildqualität zu verringern, setzen Sie die Option CompressImages auf true und die ImageQuality‑Eigenschaft auf einen Wert unter 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - die Bildqualität (Wert zwischen 1 und 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Legt die Bildqualität für die Komprimierung der Bilder in der PDF fest.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageQuality | int | die Bildqualität (Wert zwischen 1 und 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren. In diesem Fall sollten wir CompressImage auf true, ResizeImages auf true und MaxResolution auf den entsprechenden Wert setzen.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  wenn Bilder skaliert werden,  false  sonst.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Legt fest, ob die Bilder in der PDF verkleinert werden sollen.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeImages | boolean | true  zum Skalieren der Bilder,  false  sonst. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren. In diesem Fall sollten wir CompressImage auf true, ResizeImages auf true und MaxResolution auf den entsprechenden Wert setzen.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - die maximale Auflösung für die Bilder.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Legt die maximale Auflösung für das Verkleinern der Bilder in der PDF fest.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxResolution | int | die maximale Auflösung für die Bilder. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimiert die Rahmenlinien und Schriftarten von Excel‑Tabellen für eine kleinere Ausgabedateigröße.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  wenn Tabellenkalkulationen optimiert werden,  false  sonst.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Legt fest, ob die Tabellen in der PDF optimiert werden sollen.

Für ein Codebeispiel siehe diese [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  zum Optimieren der Tabellenkalkulationen,  false  sonst. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Entfernt private Informationen (Seitenstück‑Info), wenn auf true gesetzt.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn private Informationen entfernt werden,  false  sonst.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Legt fest, ob private Informationen aus der PDF entfernt werden sollen.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removePrivateInfo | boolean | true  zum Entfernen privater Informationen,  false  sonst. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Wenn das Dokument eingebettete Schriftarten verwendet, bedeutet das, dass alle Schriftartdaten im Dokument platziert sind. Der Vorteil ist, dass das Dokument unabhängig davon angezeigt werden kann, ob die Schriftart auf dem Benutzer\\u2019s Rechner installiert ist oder nicht. Das Einbetten von Schriftarten vergrößert jedoch das Dokument. Die Methode zum Entfernen eingebetteter Schriftarten entfernt alle eingebetteten Schriftarten. Dies verringert die Dokumentgröße, kann jedoch dazu führen, dass das Dokument nicht lesbar ist, wenn die korrekte Schriftart nicht installiert ist.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn eingebettete Schriftarten entfernt wurden,  false  sonst.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Legt fest, ob die eingebetteten Schriftarten in der PDF entbettet werden sollen.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unembedFonts | boolean | true  zum Entfernen der eingebetteten Schriftarten,  false  sonst. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Manchmal enthält ein Dokument mehrere identische Ressourcen-Streams (zum Beispiel Bilder). Dies kann zum Beispiel passieren, wenn ein Dokument mit sich selbst verkettet wird. Das Ausgabedokument enthält zwei unabhängige Kopien desselben Ressourcen-Streams. Wir analysieren alle Ressourcen-Streams und vergleichen sie. Wenn Streams dupliziert sind, werden sie zusammengeführt, das heißt, es bleibt nur eine Kopie, Verweise werden entsprechend geändert und Kopien des Objekts werden entfernt. Manchmal verringert dies die Dokumentgröße.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn doppelte Streams verknüpft sind,  false  sonst.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Legt fest, ob doppelte Streams in der PDF verlinkt werden sollen.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  zum Verknüpfen doppelter Streams,  false  sonst. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Wenn diese Eigenschaft auf true gesetzt ist, wird der Seiteninhalt beim Optimieren des Dokuments für identische Seiten wiederverwendet.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn Seiteninhalt wiederverwendet wird,  false  sonst.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Legt fest, ob das Wiederverwenden von Seiteninhalt im PDF erlaubt werden soll.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowReusePageContent | boolean | true  um die Wiederverwendung von Seiteninhalt zu erlauben,  false  sonst. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Manchmal enthält ein Dokument ungenutzte Ressourcen-Streams. Diese Streams sind nicht \\u201cunused objects\\u201d, weil sie aus dem Ressourcenwörterbuch einer Seite referenziert werden. Das kann vorkommen, wenn ein Bild von der Seite entfernt wurde, aber nicht aus den Seitenressourcen. Außerdem tritt diese Situation häufig auf, wenn Seiten aus dem Dokument extrahiert werden und die Dokumentseiten \\u201ccommon\\u201d Ressourcen haben, das heißt, dasselbe Resources-Objekt. Der Seiteninhalt wird analysiert, um festzustellen, ob ein Ressourcen-Stream verwendet wird oder nicht. Unbenutzte Streams werden entfernt. Manchmal verringert dies die Dokumentgröße.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn ungenutzte Streams entfernt werden,  false  sonst.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Legt fest, ob ungenutzte Streams aus dem PDF entfernt werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  zum Entfernen ungenutzter Streams,  false  sonst. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Ein PDF-Dokument enthält manchmal PDF-Objekte, die von keinem anderen Objekt im Dokument referenziert werden. Das kann zum Beispiel passieren, wenn eine Seite aus dem Dokumentseitenbaum entfernt wird, das Seitenobjekt selbst jedoch nicht entfernt wird. Das Entfernen dieser Objekte macht das Dokument nicht ungültig, sondern verkleinert es.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  wenn ungenutzte Objekte entfernt werden,  false  sonst.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Legt fest, ob ungenutzte Objekte aus dem PDF entfernt werden sollen.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  zum Entfernen ungenutzter Objekte,  false  sonst. |

