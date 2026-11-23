---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Verwenden Sie diese Klasse, um PDF‑Optimierungsoptionen festzulegen, die auf die Ausgabedatei im PDF‑Format angewendet werden."
type: docs
weight: 21
url: /de/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Verwenden Sie diese Klasse, um PDF‑Optimierungsoptionen festzulegen, die auf die Ausgabedatei im PDF‑Format angewendet werden.


Diese Optimierungsoptionen werden für alle Eingabedateiformate unterstützt, die für den Export nach PDF unterstützt werden.
Für Details und Codebeispiele siehe diese [Seite](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) und deren Unterseiten.


Beispielverwendung:

````

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
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Legt die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100 fest. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Aktiviert die Optimierung der Ausgabepdf-Datei für die Online-Anzeige in einem Webbrowser. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Legt fest, ob das Ausgabepdf für das Online‑Durchsuchen mit einem Webbrowser optimiert werden soll. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Anmerkungen können gelöscht werden, wenn sie nicht erforderlich sind. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Legt fest, ob unnötige Anmerkungen aus dem PDF entfernt werden sollen. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Wenn das PDF-Dokument AcroForms enthält, können wir versuchen, die Dateigröße zu reduzieren, indem Formularfelder abgeflacht werden. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Legt fest, ob Formularfelder aus dem PDF entfernt werden sollen. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | Eine PDF-Datei besteht aus Text, Bild, Anhang, Anmerkungen, Grafiken und anderen Objekten. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Legt fest, ob das PDF in Graustufen konvertiert werden soll. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Jede Schriftart, die zur Anzeige von Text auf der Seite verwendet wird, enthält einen Satz von Glyphen für die Schriftzeichen. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Legt fest, ob die Schriftarten im PDF teilunterteilt werden sollen. |
|
|  | [isCompressImages()](#isCompressImages--) | Wenn die Quell-PDF-Datei Bilder enthält, sollte man in Erwägung ziehen, die Bilder zu komprimieren und deren Qualität festzulegen. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Legt fest, ob die Bilder im PDF komprimiert werden sollen. |
|
|  | [getImageQuality()](#getImageQuality--) | Wenn die Quell-PDF-Datei Bilder enthält, sollte man in Erwägung ziehen, die Bilder zu komprimieren und deren Qualität festzulegen. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Legt die Bildqualität für die Komprimierung der Bilder im PDF fest. |
|
|  | [isResizeImages()](#isResizeImages--) | Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Legt fest, ob die Bilder im PDF skaliert werden sollen. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Legt die maximale Auflösung für das Skalieren der Bilder im PDF fest. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimiert die Rahmenlinien und Schriftarten von Excel‑Tabellen für eine kleinere Ausgabedateigröße. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Legt fest, ob die Tabellen im PDF optimiert werden sollen. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Entfernt private Informationen (Seitenstück‑Info), wenn auf true gesetzt. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Legt fest, ob private Informationen aus dem PDF entfernt werden sollen. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Wenn das Dokument eingebettete Schriftarten verwendet, bedeutet das, dass alle Schriftartdaten im Dokument abgelegt sind. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Legt fest, ob die eingebetteten Schriftarten im PDF entbettet werden sollen. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Manchmal enthält ein Dokument mehrere identische Ressourcenströme (zum Beispiel Bilder). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Legt fest, ob doppelte Ströme im PDF verlinkt werden sollen. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Wenn diese Eigenschaft auf true gesetzt ist, wird der Seiteninhalt beim Optimieren des Dokuments für identische Seiten wiederverwendet. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Legt fest, ob die Wiederverwendung von Seiteninhalt im PDF erlaubt werden soll. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Manchmal enthält ein Dokument ungenutzte Ressourcenströme. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Legt fest, ob ungenutzte Ströme aus dem PDF entfernt werden sollen. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Ein PDF-Dokument enthält manchmal PDF-Objekte, die nicht referenziert werden |
von irgendeinem anderen Objekt im Dokument.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Legt fest, ob ungenutzte Objekte aus dem PDF entfernt werden sollen. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Legt die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100 fest.


Für Details und Codebeispiele siehe diese [Seite](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) und deren Unterseiten.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Aktiviert die Optimierung der Ausgabepdf-Datei für die Online-Anzeige in einem Webbrowser.


Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  wenn das ausgegebene PDF für das Online‑Durchsuchen optimiert ist,  false  sonst.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Legt fest, ob das Ausgabepdf für das Online‑Durchsuchen mit einem Webbrowser optimiert werden soll.


Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | linearize | boolesch | true  um das ausgegebene PDF für das Online‑Durchsuchen zu optimieren,  false  sonst. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anmerkungen können gelöscht werden, wenn sie nicht benötigt werden. Wenn sie benötigt werden, aber keine zusätzliche Bearbeitung erfordern, können sie flachgelegt werden. Dies reduziert die Dateigröße.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  wenn Anmerkungen entfernt werden,  false  sonst.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Legt fest, ob unnötige Anmerkungen aus dem PDF entfernt werden sollen.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | removeAnnotations | boolesch | true  um unnötige Anmerkungen zu entfernen,  false  sonst. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Wenn das PDF-Dokument AcroForms enthält, können wir versuchen, die Dateigröße zu reduzieren, indem Formularfelder abgeflacht werden.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  wenn Formularfelder entfernt werden,  false  sonst.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Legt fest, ob Formularfelder aus dem PDF entfernt werden sollen.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | removeFormFields | boolesch | true  um Formularfelder zu entfernen,  false  sonst. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Eine PDF-Datei besteht aus Text, Bild, Anhang, Anmerkungen, Grafiken und anderen Objekten.
Möglicherweise stoßen Sie auf die Anforderung, ein PDF vom RGB-Farbraum in Graustufen zu konvertieren, damit es beim Drucken dieser PDF-Dateien schneller ist.
Wenn die Datei außerdem in Graustufen konvertiert wird, wird die Dokumentgröße ebenfalls reduziert, jedoch kann dabei die Qualität des Dokuments sinken.
Derzeit wird diese Funktion von der Pre-Flight-Funktion von Adobe Acrobat unterstützt.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  wenn das PDF in Graustufen konvertiert wird,  false  sonst.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Legt fest, ob das PDF in Graustufen konvertiert werden soll.


***Note:** The default value is 
false
.*
Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | convertToGrayScale | boolesch | true  um das PDF in Graustufen zu konvertieren,  false  sonst. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Jede Schriftart, die zur Anzeige von Text auf der Seite verwendet wird, enthält einen Satz von Glyphen für die Schriftzeichen.
Die PDF-Spezifikation unterstützt "Font Subset", d.h. Schriftarten nur mit den tatsächlich verwendeten Glyphen.
Dies kann Probleme verursachen, wenn Text aktualisiert werden soll (da möglicherweise erforderliche Glyphen in der Schriftart fehlen), aber für ein Dokument, das nicht geändert werden soll, ermöglicht dies eine Größenreduzierung.


***Note:** The default value is 
false
.*
Wenn die Datei eingebettete Schriftarten verwendet, enthält sie alle Schriftartdaten. GroupDocs.Viewer kann eingebettete Schriftarten subsetten, um die Dateigröße zu reduzieren. Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  wenn Schriftarten unterteilt wurden,  false  sonst.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Legt fest, ob die Schriftarten im PDF teilunterteilt werden sollen.


***Note:** The default value is 
false
.*
Wenn die Datei eingebettete Schriftarten verwendet, enthält sie alle Schriftartdaten. GroupDocs.Viewer kann eingebettete Schriftarten subsetten, um die Dateigröße zu reduzieren. Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | subsetFonts | boolesch | true  um die Schriftarten zu subsetten,  false  sonst. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Wenn die Quell-PDF-Datei Bilder enthält, sollte man in Erwägung ziehen, die Bilder zu komprimieren und deren Qualität festzulegen.
Um die Bildkompression zu aktivieren, setzen Sie diese Option auf true. Alle Bilder in einem Dokument werden erneut komprimiert.
Die Kompression wird durch die ImageQuality-Eigenschaft definiert, die den Qualitätswert in Prozent angibt.
100 % ist unveränderte Qualität. Um die Bildqualität zu verringern, setzen Sie die ImageQuality-Eigenschaft auf einen Wert unter 100.


***Note:** The default value is 
false
.*
Verwenden Sie diese Option, um weitere Komprimierungsoptionen zu ermöglichen: #setImageQuality(int).setImageQuality(int) und . Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  wenn Bilder komprimiert werden,  false  sonst.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Legt fest, ob die Bilder im PDF komprimiert werden sollen.


***Note:** The default value is 
false
.*
Verwenden Sie diese Option, um weitere Komprimierungsoptionen zu ermöglichen: #setImageQuality(int).setImageQuality(int) und . Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | compressImages | boolesch | true  um die Bilder zu komprimieren,  false  sonst. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Wenn die Quell-PDF-Datei Bilder enthält, sollten Sie die Bilder komprimieren und deren Qualität einstellen. Um die Bildkompression zu aktivieren, setzen Sie die Option CompressImages auf true. Alle Bilder in einem Dokument werden erneut komprimiert. Die Kompression wird durch die ImageQuality-Eigenschaft definiert, die den Qualitätswert in Prozent angibt. 100 % ist unveränderte Qualität. Um die Bildqualität zu verringern, setzen Sie die Option CompressImages auf true und die ImageQuality-Eigenschaft auf einen Wert unter 100.

<br />


***Note:** The default value is 
100
.*
Um die Bildqualität zu ändern, setzen Sie zuerst die Eigenschaft #setCompressImages(boolean).setCompressImages(boolean) auf true. Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - die Bildqualität (Wert zwischen 1 und 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Legt die Bildqualität für die Komprimierung der Bilder im PDF fest.


***Note:** The default value is 
100
.*
Um die Bildqualität zu ändern, setzen Sie zuerst die Eigenschaft #setCompressImages(boolean).setCompressImages(boolean) auf true. Für ein Codebeispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageQuality | int | die Bildqualität (Wert zwischen 1 und 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kann zusammen mit der Option CompressImages verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren.
In diesem Fall sollten wir CompressImage auf true, ResizeImages auf true und MaxResolution auf den entsprechenden Wert setzen.


***Note:** The default value is 
false
.*
Um diese Option zu aktivieren, setzen Sie die Eigenschaft auf true. Diese Option ermöglicht das Setzen der Eigenschaft. Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  wenn Bilder skaliert werden,  false  sonst.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Legt fest, ob die Bilder im PDF skaliert werden sollen.


***Note:** The default value is 
false
.*
Um diese Option zu aktivieren, setzen Sie die Eigenschaft auf true. Diese Option ermöglicht das Setzen der Eigenschaft. Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | resizeImages | boolesch | true  um die Bilder zu skalieren,  false  sonst. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kann zusammen mit der CompressImages‑Option verwendet werden, um die Bilder mit einer niedrigeren Auflösung zu skalieren. In diesem Fall sollten wir CompressImage auf true, ResizeImages auf true und MaxResolution auf den entsprechenden Wert setzen.


***Note:** The default value is 
300
.*
Um diese Option zu aktivieren, setzen Sie die Eigenschaften #setCompressImages(boolean).setCompressImages(boolean) und #setMaxResolution(int).setMaxResolution(int) auf true.
Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - die maximale Auflösung für die Bilder.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Legt die maximale Auflösung für das Skalieren der Bilder im PDF fest.


***Note:** The default value is 
300
.*
Um diese Option zu aktivieren, setzen Sie die Eigenschaften #setCompressImages(boolean).setCompressImages(boolean) und #setMaxResolution(int).setMaxResolution(int) auf true.
Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxResolution | int | die maximale Auflösung für die Bilder. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimiert die Rahmenlinien und Schriftarten von Excel‑Tabellen für eine kleinere Ausgabedateigröße.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  wenn Tabellenkalkulationen optimiert werden,  false  sonst.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Legt fest, ob die Tabellen im PDF optimiert werden sollen.


Für ein Code‑Beispiel siehe diese [Dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolesch | true  um die Tabellenkalkulationen zu optimieren,  false  sonst. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Entfernt private Informationen (Seitenstück‑Info), wenn auf true gesetzt.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn private Informationen entfernt werden,  false  sonst.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Legt fest, ob private Informationen aus dem PDF entfernt werden sollen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | removePrivateInfo | boolesch | true  um private Informationen zu entfernen,  false  sonst. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Wenn das Dokument eingebettete Schriftarten verwendet, bedeutet das, dass alle Schriftartdaten im Dokument abgelegt sind.
Der Vorteil ist, dass das Dokument unabhängig davon, ob die Schriftart auf dem Rechner des Benutzers installiert ist, angezeigt werden kann. Das Einbetten von Schriftarten vergrößert jedoch das Dokument.
Die Methode zum Entfernen eingebetteter Schriftarten entfernt alle eingebetteten Schriftarten. Dadurch wird die Dokumentgröße reduziert, aber das Dokument kann unlesbar werden, wenn die korrekte Schriftart nicht installiert ist.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn eingebettete Schriftarten entfernt werden,  false  sonst.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Legt fest, ob die eingebetteten Schriftarten im PDF entbettet werden sollen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | unembedFonts | boolesch | true  um die eingebetteten Schriftarten zu entfernen,  false  sonst. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Manchmal enthält ein Dokument mehrere identische Ressourcenströme (zum Beispiel Bilder).
Dies kann zum Beispiel auftreten, wenn ein Dokument mit sich selbst verkettet wird.
Das Ausgabedokument enthält zwei unabhängige Kopien desselben Ressourcen‑Streams.
Wir analysieren alle Ressourcen-Streams und vergleichen sie. Wenn Streams dupliziert sind, werden sie zusammengeführt, das heißt, es bleibt nur eine Kopie übrig, Verweise werden entsprechend geändert und Kopien des Objekts werden entfernt.
Manchmal verringert dies die Dokumentgröße.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn duplizierte Streams verlinkt sind,  false  sonst.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Legt fest, ob doppelte Ströme im PDF verlinkt werden sollen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | linkDuplicateStreams | boolesch | true  um duplizierte Streams zu verlinken,  false  sonst. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Wenn diese Eigenschaft auf true gesetzt ist, wird der Seiteninhalt beim Optimieren des Dokuments für identische Seiten wiederverwendet.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn Seiteninhalt wiederverwendet wird,  false  sonst.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Legt fest, ob die Wiederverwendung von Seiteninhalt im PDF erlaubt werden soll.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | allowReusePageContent | boolesch | true  um die Wiederverwendung von Seiteninhalt zu erlauben,  false  sonst. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Manchmal enthält ein Dokument ungenutzte Ressourcenströme.
Diese Streams sind nicht \\u201cunbenutzte Objekte\\u201d, weil sie aus dem Ressourcen‑Dictionary einer Seite referenziert werden.
Dies kann vorkommen, wenn ein Bild von der Seite entfernt wurde, aber nicht aus den Seitenressourcen.
Außerdem tritt diese Situation häufig auf, wenn Seiten aus dem Dokument extrahiert werden und Dokumentseiten \\u201cgemeinsame\\u201d Ressourcen haben,
das heißt, das gleiche Resources‑Objekt. Seiteninhalte werden analysiert, um festzustellen, ob ein Ressourcen‑Stream
verwendet wird oder nicht. Unbenutzte Streams werden entfernt. Manchmal verringert dies die Dokumentgröße.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn unbenutzte Streams entfernt werden,  false  sonst.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Legt fest, ob ungenutzte Ströme aus dem PDF entfernt werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | removeUnusedStreams | boolesch | true  um unbenutzte Streams zu entfernen,  false  sonst. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Ein PDF-Dokument enthält manchmal PDF-Objekte, die nicht referenziert werden
von jedem anderen Objekt im Dokument. Dies kann beispielsweise vorkommen,
wenn eine Seite aus dem Dokumentseiten‑Baum entfernt wird, das Seitenobjekt selbst jedoch nicht entfernt wird.
Das Entfernen dieser Objekte macht das Dokument nicht ungültig, sondern verkleinert es.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn unbenutzte Objekte entfernt werden,  false  sonst.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Legt fest, ob ungenutzte Objekte aus dem PDF entfernt werden sollen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | removeUnusedObjects | boolesch | true  um unbenutzte Objekte zu entfernen,  false  sonst. |
|

